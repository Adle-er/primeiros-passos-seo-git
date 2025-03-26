# 📈 Auditoria técnica com o Scraming Frog

O **Screaming Frog SEO Spider** é uma das principais ferramentas para auditoria técnica de SEO, permitindo rastrear o site e identificar problemas que podem impactar o ranqueamento nos motores de busca, além de gerar sitemap.

***

### Configuração e principais funcionalidades

Antes de iniciar a auditoria, é importante configurar o Screaming Frog corretamente:

#### Modo de Rastreamento:

Spider Mode (Padrão): Rastreia o site como um bot do Google, identificando URLs, meta tags, erros, entre outros.

List Mode: Permite importar uma lista de URLs para auditoria específica.

#### Configurações Essenciais:

Em Config > Spider, ativar a opção "Crawl all subdomains", se necessário.

Ajustar o User-Agent para "Googlebot" para simular o comportamento do rastreador do Google.

Definir um limite de rastreamento para sites grandes, evitando sobrecarga no servidor.

***

### Como interpretar relatórios do Screaming Frog

Após o rastreamento, os dados podem ser analisados nas seguintes abas:

1. Overview (Visão geral)
Mostra um resumo dos principais problemas encontrados no site.

2. Internal (Páginas internas)
Lista todas as URLs rastreadas e permite identificar problemas como páginas duplicadas e redirecionamentos.

3. Response codes (Códigos de resposta HTTP)
 - 200 (OK): Página funcionando corretamente.

- 301/302 (Redirecionamentos): Verificar se estão configurados corretamente.

- 404 (Página não encontrada): Identificar links quebrados e corrigir.

- 500 (Erro no servidor): Necessário [acionar a equipe](/contatos.md).

4. Page Titles & Meta Descriptions
Identifica títulos e descrições ausentes, duplicados ou muito longos/curtos.

5. H1 & H2
Verifica a hierarquia dos cabeçalhos e se há duplicações ou falta de H1.

6. Images
Detecta imagens pesadas e sem atributo alt, impactando acessibilidade e desempenho.

7. Canonicals
Confirma se as tags canonical estão corretamente configuradas para evitar conteúdo duplicado.

8. Indexability
Mostra quais páginas estão ou não indexáveis, identificando problemas com meta tags noindex ou bloqueios no robots.txt.

***

### Identificação de erros comuns

A auditoria do Screaming Frog ajuda a detectar e corrigir diversos problemas, como:

✅ Erros de rastreamento e indexação: Bloqueios no robots.txt ou meta noindex indevidos.

✅ Páginas órfãs: URLs que não possuem links internos apontando para elas.

✅ Problemas de redirecionamento: Cadeias de redirecionamento longas ou redirecionamentos desnecessários.

✅ Duplicação de conteúdo: Títulos, meta descriptions e H1 duplicados que podem confundir o Google.

✅ Erros de velocidade e carregamento: Identificação de imagens pesadas e scripts excessivos.