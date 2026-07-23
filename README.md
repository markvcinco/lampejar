# Lampejar

Site institucional da **Lampejar** — conteúdo estratégico com praticidade, organização e criatividade.

Site estático de página única, publicado na Vercel.

## Estrutura

| Arquivo | Descrição |
|---|---|
| `index.html` | Página única do site (estilos e imagens embutidos). |
| `favicon.svg` | Favicon vetorial da lâmpada (nítido em qualquer tamanho). |
| `favicon.ico` | Favicon multi-tamanho (16/32/48) para navegadores legados. |
| `favicon-16.png`, `favicon-32.png` | Favicons PNG. |
| `apple-touch-icon.png` | Ícone 180×180 para iOS. |
| `icon-192.png`, `icon-512.png` | Ícones para PWA / manifest. |
| `site.webmanifest` | Web app manifest. |

## Desenvolvimento

Como é um site estático, basta servir a pasta:

```bash
python3 -m http.server 8000
# abra http://localhost:8000
```

## Deploy

Publicado na Vercel a partir deste repositório (deploy estático — sem build step).
