# 🔼 Melhoria de velocidade e performance

A **velocidade de carregamento de um site é um fator essencial** para SEO e experiência do usuário. O Google considera a performance como um critério de ranqueamento, **especialmente para dispositivos móveis**. Além disso, páginas lentas aumentam a taxa de rejeição e reduzem a taxa de conversão.

***

### Otimização dos Core Web Vitals

Os Core Web Vitals são métricas de experiência do usuário que o Google utiliza para avaliar a performance de um site. Eles incluem:

Largest Contentful Paint (LCP): Mede o tempo de carregamento do maior elemento visível na página.

First Input Delay (FID): Mede a interatividade da página, ou seja, o tempo de resposta ao primeiro clique do usuário.

Cumulative Layout Shift (CLS): Mede a estabilidade visual da página, evitando mudanças bruscas no layout.

***

### Como melhorar os Core Web Vitals:

✅ Otimizar imagens e vídeos: Usar formatos mais leves (WebP para imagens e MP4 para vídeos) e compressão sem perda de qualidade.

✅ Utilizar carregamento assíncrono para scripts: Adicionar async ou defer para evitar bloqueios no carregamento da página.

✅ Implementar Lazy Loading: Carregar imagens e vídeos somente quando estiverem próximos da área visível.

✅ Minificar arquivos CSS, JavaScript e HTML: Reduzir o tamanho dos arquivos removendo espaços desnecessários e comentários.

✅ Definir tamanhos fixos para elementos dinâmicos: Evita mudanças inesperadas na estrutura da página (CLS).

***

### Técnicas para reduzir o tempo de carregamento

Reduzir o tempo de carregamento melhora tanto o SEO quanto a experiência do usuário. Algumas técnicas essenciais incluem:

#### 1. Uso de CDN (Content Delivery Network)
Uma CDN distribui o conteúdo do site em servidores ao redor do mundo, reduzindo a latência e melhorando o tempo de resposta para usuários de diferentes localidades.

#### 2. Ativação de cache
O uso de cache permite que elementos da página sejam armazenados temporariamente no navegador do usuário, evitando recarregamentos desnecessários.

Cache no navegador: Configurar Cache-Control e Expires para arquivos estáticos (imagens, CSS, JS).

Cache no servidor: Usar plugins de cache para WordPress (ex: WP Rocket) ou configurar caching em servidores Apache/Nginx.

#### 3. Redução do tempo de resposta do servidor (TTFB)
O TTFB (Time to First Byte) deve ser inferior a 600ms para garantir um carregamento rápido.

Utilizar hospedagem de alta performance.

Implementar HTTP/2 para carregamento simultâneo de arquivos.

Reduzir consultas ao banco de dados e otimizar a estrutura do site.

#### 4. Remoção de recursos bloqueadores de renderização
Recursos como arquivos CSS e JS não otimizados podem impedir que a página seja carregada rapidamente.

Combinar e minificar arquivos CSS e JS para reduzir solicitações.

Carregar scripts no final do HTML para não bloquear a renderização.

Utilizar Google Fonts locais ou pré-carregamento para evitar atrasos no carregamento de fontes.

#### 5. Otimização de fontes e imagens
Converter imagens para WebP em vez de PNG ou JPEG.

Habilitar compressão Gzip ou Brotli para reduzir o tamanho dos arquivos.

Evitar fontes personalizadas pesadas, carregando apenas os estilos necessários.

