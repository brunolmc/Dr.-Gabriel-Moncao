# Site — Dr. Gabriel Ataide Monção

Site estático (HTML/CSS puro). Pronto para publicar no Vercel.

## Estrutura
- `index.html` — página única (landing page)
- `styles.css` — entrada de estilos (importa `tokens/`)
- `tokens/` — variáveis de cor, tipografia, espaçamento e fontes
- `assets/` — logo, favicon e fotos
- `vercel.json` — configuração mínima (URLs limpas)

## Publicar no Vercel
Opção A — painel web:
1. Acesse vercel.com e clique em **Add New → Project**.
2. Arraste esta pasta (ou faça upload do .zip descompactado).
3. Framework Preset: **Other**. Root: a própria pasta. Clique em **Deploy**.

Opção B — CLI:
1. Instale: `npm i -g vercel`
2. Dentro desta pasta, rode `vercel` e siga as instruções.

Não há build: é um site estático, servido direto.

## Observações
- As fontes (Spectral, Public Sans) e os ícones (Lucide) carregam via CDN — requer internet no acesso.
- WhatsApp oficial configurado: (38) 99172-1201.
