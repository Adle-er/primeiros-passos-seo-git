# ⚠️ Boas práticas e processos internos

Para garantir a **eficiência das auditorias e otimizações**, é importante seguir processos padronizados e manter a organização das atividades de SEO.

###  Fluxo de trabalho para configurações iniciais do Wordpress

#### Importação do tema padrão

1. Ao acessar o WordPress pela primeira vez, navegue até a seção de **Plugins** e selecione **Adicionar novo**.

2. Procure por **All-In-One WP Migration**, instale e ative o plugin.

3. Faça o download do arquivo do tema, [clicando aqui](https://drive.google.com/drive/u/0/folders/1doE2kIsFDtMoIXKVFHlJOmAsNGOLlKV9).

4. Abra o plugin **All-In-One WP Migration**, vá em **Importar** e selecione o arquivo do tema baixado.

*<span style="color: #FF6347">Lembre-se que ao importar o tema, todo o conteúdo existente será excluído. Portanto, essa ação deve ser realizada antes de adicionar qualquer outro conteúdo.</span>*

#### Configurações pós-instalação

1. Após a instalação do tema, faça login com as informações abaixo:

    - **Usuário**: factory
    
    - **Senha**: Factory123#

2. Atualize o email de administrador para: analytics@idealtrends.com.br.

#### Criando um novo usuário administrador

1. Crie um novo usuário administrador com o login **growthia** e uma senha gerada automaticamente pelo WordPress.

2. Preencha as informações [nesta planilha](https://docs.google.com/spreadsheets/d/1zObnwCpNGBQIc88VnwItstgkwY_tcbFm2xhhCX89PnY/edit?gid=250319567#gid=250319567).

3. Faça login com o novo usuário administrador.

4. Vá na sessão **Usuários** e exclua o usuário factory.

#### Configurações de categorias

1. Obtenha a lista de categorias dos redatores e crie-as na seção **Posts > Categorias** do WordPress.

2. Após a criação, edite a **slug** das categorias para excluir preposições como (*<span style="color: #FF6347">a, o, as, os, de, da, dos, para</span>*).

3. Vá em **Configurações** > **Escrita** e altere a **Categoria padrão de post** para uma das novas categorias criadas.

4. Exclua a categoria **Benefícios da Meditação**.

#### Configurações de plugins

1. Na aba lateral, acesse **Link Whisper** (Ao acessar pela primeira vez, insira a chave:)

8. Na aba lateral, acesse **Wordfence** (Ao acessar pela primeira vez, utilize o email blognomedoblog@gmail.com para registro).

***

#### Configuração de otimização via WP Rocket

Cada site possui características únicas que devem ser consideradas durante o processo de otimização. Portanto, é essencial que o analista responsável pela otimização execute uma avaliação detalhada e meticulosa das funcionalidades e do layout do site antes de realizar qualquer alteração nas configurações.

A minificação de arquivos CSS e JavaScript é uma prática comum para melhorar o desempenho do site. No entanto, essa ação pode ter efeitos adversos, tanto em termos de funcionalidade quanto estéticos, se não for realizada com cuidado. Alterações inadequadas podem comprometer o design e a usabilidade do site.

***

#### Criação de usuários

Após o envio dos usuários relacionados ao blog pelo setor responsável, crie-os dentro de **Usuários** > **Adicionar novo usuário** e preencha os campos com os dados enviados, todos devem ser cadastrados com a função **Editor**. Após isso, [acesse a planilha](https://docs.google.com/spreadsheets/d/1zObnwCpNGBQIc88VnwItstgkwY_tcbFm2xhhCX89PnY/edit?gid=250319567#gid=250319567) e preencha os campos seguindo os padrões utilizados.

Finalizada a criação dos usuários, é necessário que se faça login em cada um dos 

<span style="color: #FF6347">*Obs: O campo **Nome de usuário** não pode conter caracteres especiais.*</span>

***

###  Fluxo de trabalho para auditorias SEO

#### Coleta de dados

1. Rodar o **Screaming Frog** para os identificar erros técnicos e gerar um novo sitemap.xml. 

#### Ao abrir o Screaming Frog:
- Vá em **Configuration** > **robots.txt** e selecione **Ignore robots.txt.**

#### Em segudia acesse Sitemaps:
- Aba Pages e deixe selecionado:
    - **Noindex pages**.
    - **Canonicalised**.
    - **Paginated URLs**.
    - **PDFs**.

- Aba Priority:
    - **Crawl Depth 0 = 1**.
    - **Crawl Depth 1 a 5+ = 0,9**.

- Aba Change Frequency:
    - Selecione **Use crawl depth settings**.
    - Configure todos os campos para **Weekly**.

#### Após isso:
- Insira a URL do site a ser analisado (**incluindo https://**).    
- Aguarde até que o carregamento seja concluído.
- Quando a varredura terminar, confira aqui [**como interpretar os relatórios do Screaming Frog**](/auditoria-screaming-frog#como-interpretar-relatórios-do-screaming-frog).
- Ao finalizar a correção dos erros apresentados vá em **Sitemaps** > **XML Sitemaps** > **Export** e substitua o sitemap.xml pelo que está presente na pasta raíz do projeto.

***

2. Analisar o **Google Search Console** para verificar problemas de indexação.

#### Ao acessar o Google Search Console

- Vá até o menu **Páginas** e faça uma breve análise dos erros apresentados na seção.

- Clique no erro pontuado e, após isso, clique em **Validar correção**.

***

3. Executar o **Google Lighthouse** para validar desempenho e acessibilidade.

- [Acesse a URL](https://pagespeed.web.dev).

- Insira a URL do site a ser analisado e inicie a análise.

- [Veja aqui](validacao-google-lighthouse#métricas-principais-avaliadas-pelo-lighthouse) as métricas principais avalidadas pelo Lighthouse

***

#### Identificação de problemas prioritários

1. URLs quebradas (404), redirecionamentos incorretos (301/302).

2. Problemas de layout.

3. Títulos e meta descriptions duplicados ou ausentes.

4. Banner home sem link.

5. Imagens sem alt e title.

6. Links sem title.

7. Erros de W3C.

8. Problemas de velocidade e carregamento.

#### Planejamento de correções

1. Abrir o formulário SEO GIT e preencher as informações com os dados atuais do projeto.

2. Salvar o PDF e o CSV gerados pelo formulário dentro da pasta [Prontuários projetos SEO GIT](https://drive.google.com/drive/folders/1ur3210si17C62YUpwh2z67N83aDOcrLE?usp=drive_link) no Google Drive. 

3. Alinhar as mudanças com a equipe.

4. Para garantir garantir que as correções foram aplicadas corretamente, repita o processo de coleta de dados após as alterações.

#### Monitoramento contínuo

Revisar métricas no Google Search Console e Analytics semanalmente.

Atualizar conteúdos antigos com novas palavras-chave e otimizações.

Testar semanalmente o site com o Screaming Frog e PageSpeed Insights.

Abrir o formulário SEO GIT a cada 15 dias e preencher as informações com os dados atuais do projeto a fim de comparações com os 15 dias anteriores.

### Boas práticas

Ao revisar o conteúdo, é interessante que tenhamos, no mínimo, **3% de repetições ou sinônimos** da palavra-chave direcionada para àquele artigo. Exemplo: **Um conteúdo com 1500 palavras deverá conter, no mínimo, 45 repetições ou sinônimos da palavra-chave**.

Usar linkagem interna para melhorar a navegação e distribuição de autoridade.

Manter URLs amigáveis e bem estruturadas para facilitar a indexação.

Implementar dados estruturados para melhorar a exibição nos resultados do Google.

Evitar o uso excessivo de JavaScript que pode dificultar a indexação das páginas.