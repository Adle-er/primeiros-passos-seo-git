# 🚨 Validação com Google Lighthouse

O **Google Lighthouse** é uma ferramenta essencial para avaliar e otimizar o desempenho de uma página, garantindo que ela atenda aos padrões de SEO, acessibilidade, boas práticas e experiência do usuário. Ele gera relatórios detalhados e sugere melhorias que podem impactar diretamente o ranqueamento no Google.

***

### Como utilizar o Google Lighthouse

O Lighthouse pode ser acessado de três formas:

#### Google Chrome DevTools:

1. Acesse a página a ser analisada.

2. Pressione F12 ou Ctrl + Shift + I para abrir o DevTools.

3. Vá até a aba "Lighthouse" e selecione as categorias desejadas.

4. Clique em "Analyze page load" para iniciar a auditoria.

#### Extensão do Chrome:

1. Instale a extensão Google Lighthouse na Chrome Web Store.

2. Acesse a página e clique no ícone da extensão para rodar a análise.

#### Google PageSpeed Insights:

1. Acesse PageSpeed Insights e insira a URL da página.

2. O relatório gerado é baseado no Lighthouse e inclui sugestões de otimização.

***

### Métricas principais avaliadas pelo Lighthouse

O relatório do Lighthouse é dividido em cinco categorias:

#### 1. Performance 🚀

Avalia a velocidade e a eficiência do carregamento da página.

Largest Contentful Paint (LCP): Mede o tempo de carregamento do maior elemento visível na tela.

First Input Delay (FID): Mede o tempo de resposta da página após a primeira interação do usuário.

Cumulative Layout Shift (CLS): Mede a estabilidade visual da página, evitando mudanças bruscas de layout.

Total Blocking Time (TBT): Avalia a quantidade de tempo que a página permanece não responsiva durante o carregamento.

#### 2. Acessibilidade ♿

Verifica se a página está adaptada para usuários com necessidades especiais.

Uso correto de alt text em imagens.

Contraste adequado entre texto e fundo.

Elementos interativos acessíveis por teclado.

#### 3. Melhores práticas ✅

Avalia se a página segue padrões modernos de desenvolvimento web.

Segurança de conexões HTTPS.

Uso de tecnologias otimizadas e atualizadas.

Evita o uso de bibliotecas JavaScript desatualizadas ou vulneráveis.

#### 4. SEO 🔍

Verifica a otimização da página para motores de busca.

Uso correto de meta tags (title, description).

Presença de tags alt em imagens.

Uso adequado de cabeçalhos (H1, H2, H3...).

Compatibilidade com dispositivos móveis (mobile-friendly).

#### 5. Progressive Web App (PWA) 📱

Avalia se a página segue os princípios de uma aplicação web progressiva.

Suporte a navegação offline.

Design responsivo e compatível com diferentes dispositivos.

***

### Como interpretar os resultados

Os resultados são apresentados em uma escala de 0 a 100, onde:

90 a 100 (verde): Excelente, bem otimizado.

50 a 89 (laranja): Médio, precisa de ajustes.

0 a 49 (vermelho): Ruim, exige otimizações urgentes.