# Meu Desconto — MVP inicial

Site estático para publicar no Netlify Free conectado ao GitHub.

## Incluído
- Página inicial responsiva e páginas individuais para as cinco marcas.
- Títulos e descrições SEO iniciais, `robots.txt` e `sitemap.xml`.
- Aviso de transparência sobre links afiliados.
- Dados centrais em `assets/offers.js`.

## Antes de divulgar
Edite `assets/offers.js` e as páginas em `marcas/`: troque `A CONFIRMAR` pelos códigos vigentes e `#` pelos links afiliados reais. Preencha desconto, regras, validade e data da verificação. Os placeholders não são cupons válidos.

## Publicação
1. Crie um repositório GitHub chamado `meu-desconto` e envie o conteúdo desta pasta para a raiz.
2. Crie conta no Netlify, escolha **Add new site → Import an existing project**, conecte GitHub e selecione o repositório.
3. Para este site estático, use a raiz do repositório como diretório de publicação; não há comando de build.
4. Publique e teste a URL `*.netlify.app`.
5. Atualize canonical e sitemap com a URL exata gerada pelo Netlify antes de solicitar indexação.

Não habilite recarga automática nem serviços pagos. Limites e condições do plano gratuito podem mudar.
