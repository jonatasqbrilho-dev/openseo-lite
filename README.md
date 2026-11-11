# OpenSEO Lite

Ferramenta gratuita e independente para pesquisa inicial de palavras-chave e auditoria SEO, com foco em conteúdo e afiliados de marketplace (incluindo Shopee).

## Princípios
- Sem API paga, sem cartão e sem serviços que gerem cobrança.
- Sem DataForSEO, OpenRouter, R2 ou banco obrigatório.
- Sugestões de pesquisa obtidas sob demanda por função Netlify usando Google Autocomplete. A disponibilidade depende do serviço externo.
- Métricas como volume mensal, CPC, dificuldade real, backlinks e posição de ranking **não são inventadas** e não são fornecidas nesta versão.

## Funcionalidades iniciais
- Sugestões de palavras-chave e perguntas relacionadas a partir do autocomplete.
- Expansão de termos com modificadores úteis para títulos e descrições de produtos.
- Agrupamento local de palavras-chave por similaridade lexical.
- Auditoria básica de página pública: title, meta description, H1, headings, canonical, imagens sem alt, links e tamanho do conteúdo.
- Exportação CSV de resultados.

## Executar localmente
Requer Node.js 18+.

```bash
npm install
npm run dev
```

Abra o endereço indicado pelo Netlify CLI. Alternativamente, publique este repositório no Netlify; o plano gratuito pode ter limites e políticas próprias. Não configure add-ons pagos nem informe cartão.

## Publicar no Netlify (opcional)
1. Importe este repositório no Netlify.
2. Use o comando de build vazio e diretório de publicação `.`.
3. As funções ficam em `netlify/functions`.
4. Confira o painel de uso e mantenha-se no plano gratuito.

## Limitações honestas
Esta é uma ferramenta de pesquisa exploratória, não substitui plataformas profissionais. Autocomplete não representa volume de busca nem garante intenção de compra. Auditoria depende do HTML público acessível e pode ser limitada por bloqueios, JavaScript ou políticas anti-bot.

## Privacidade
As palavras-chave enviadas à função de sugestões são encaminhadas ao endpoint público de autocomplete. A URL auditada é consultada pelo servidor da função para obter HTML. Não há conta, rastreamento próprio ou banco de dados nesta versão.
