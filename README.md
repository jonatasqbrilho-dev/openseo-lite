# OpenSEO Lite

Ferramenta independente e gratuita para pesquisa básica de palavras-chave e auditoria SEO, com foco em pequenos sites e afiliados.

## Sem custos e sem cadastro
- Sem cartão, assinatura, chave de API ou serviço pago.
- Executa no navegador; palavras salvas ficam no armazenamento local.
- O HTML da auditoria é analisado localmente, sem upload.
- Não usa DataForSEO, OpenRouter, R2, banco remoto ou backend pago.

## Funcionalidades
1. Sugestões públicas do Google (se o navegador permitir a requisição).
2. Variações locais de intenção de busca.
3. Agrupamento de termos semelhantes.
4. Auditoria on-page do HTML colado: title, description, H1/H2, ALT, links, canonical e viewport.
5. Lista local e exportação CSV.

## Executar
Abra `index.html` no navegador ou publique como site estático no GitHub Pages/Netlify. Não há dependências para instalar.

## Limitações
Sugestões não representam volume de busca, dificuldade, posição orgânica nem garantia de vendas. O endpoint público pode bloquear requisições CORS. A auditoria de URL externa costuma ser limitada por CORS; cole o HTML-fonte. Backlinks e SERP profissional exigem provedores externos e não são simulados.

## Privacidade
Os termos ficam no localStorage do navegador. O termo pesquisado é enviado ao endpoint público de sugestões do Google quando você usa a pesquisa.

## Licença
MIT para os arquivos originais deste projeto.
