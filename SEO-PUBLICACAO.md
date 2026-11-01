# SEO local — Rise Up Fitness

Este conjunto foi preparado para o domínio oficial `https://studioriseup.com.br/` em 31/10/2026.

## O que mudou
- `index.html`: título e descrição orientados a Pilates Solo e treino personalizado em Sabará; canonical; Open Graph; JSON-LD `HealthClub` usando apenas endereço, telefone, Instagram e mapa já publicados.
- `robots.txt`: orienta rastreadores e informa o sitemap.
- `sitemap.xml`: lista apenas a homepage, pois o site é uma página única.
- `llms.txt`: resumo opcional. O Google declara que esse arquivo não influencia seus rankings nem suas funcionalidades de IA.

## Publicação (atenção)
O deploy publicado em Netlify `clube-rise-up-fitness` foi feito por upload/API (sem branch ou commit GitHub vinculado). MERGE NO GITHUB NÃO PUBLICA O SITE.
Preservar os arquivos da versão ativa e publicar um pacote revisado no projeto EXISTENTE, não em um novo site.
Antes de subir, comparar a versão ativa com este `index.html`, especialmente imagens, links, preços e outros arquivos do deploy que não estejam no repositório.
Colocar `robots.txt`, `sitemap.xml` e `llms.txt` na raiz pública do mesmo diretório que entrega `index.html`.
Depois, conferir respostas HTTP 200 e tipo de conteúdo adequado nos três URLs; confirmar canonical e JSON-LD no HTML final.

## Google Search Console
1. Abrir https://search.google.com/search-console e adicionar a propriedade de domínio `studioriseup.com.br`.
2. Verificar a propriedade com o registro DNS TXT informado pelo próprio Google, SEM inventar valor.
3. Em Sitemaps, enviar `sitemap.xml`.
4. Em Inspeção de URL, verificar `https://studioriseup.com.br/` e solicitar indexação se necessário.
5. Acompanhar consultas, impressões, cliques, CTR, posição média e páginas indexadas.

## SEO local de maior impacto
- Conferir se o Perfil da Empresa no Google está verificado, endereço e telefone consistentes e categoria apropriada.
- Publicar fotos reais e avaliações autênticas, responder comentários.
- Criar posteriormente páginas úteis com conteúdo original para Pilates Solo e treino personalizado, sem páginas de localizações fictícias.
- Medir cliques no WhatsApp como conversão.

## Cuidados
- O arquivo `meta keywords` não é utilizado pelo Google.
- Não há garantia de primeira posição.
- `llms.txt` é experimental/opcional; não prometer ganhos de IA.
- Não inventar horários, preços ou avaliações em dados estruturados.
