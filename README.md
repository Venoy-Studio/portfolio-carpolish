# Carpolish - Clone com Dados Fictícios

Este projeto é um clone completo e fiel do site [carpolish-vert.vercel.app](https://carpolish-vert.vercel.app/), mantendo 100% dos layouts, estilos, animações (GSAP/ScrollTrigger), fontes e todas as imagens/mídias em alta resolução, substituindo estritamente os dados de contato reais por dados fictícios.

## 📋 Dados de Contato Fictícios Substituídos

| Campo | Dado Original | Dado Fictício |
|---|---|---|
| **WhatsApp / Telefone** | +55 11 97054-1116 | **+55 11 99999-0000** |
| **Exibição do Telefone**| (11) 97054-1116 | **(11) 99999-0000** |
| **E-mail** | carpolish.oficial@gmail.com | **contato@carpolish.com.br** |
| **CNPJ** | 52.822.409/0001-97 | **00.000.000/0001-91** |
| **Endereço** | Av. Henrique Eroles, 894 — Alto Ipiranga, Mogi das Cruzes - SP | **Av. Paulista, 1000 — Bela Vista, São Paulo - SP** |
| **CEP** | 08730-590 | **01310-100** |
| **Instagram** | @carpolish.oficial | **@carpolish.exemplo** |
| **Google Maps** | Localização de Mogi das Cruzes | **Pesquisa genérica / Av. Paulista, São Paulo** |

---

## 🚀 Como Executar

O projeto já possui um servidor HTTP embutido com zero dependências externas:

```bash
npm start
```
Ou diretamente:
```bash
node server.js
```

O site estará acessível em:
👉 **[http://localhost:8080](http://localhost:8080)** (ou porta subsequente caso a 8080 esteja ocupada).

---

## 📁 Estrutura do Projeto

- `index.html`: Documento HTML principal com meta tags SEO, Open Graph e Schema.org JSON-LD atualizados com os dados fictícios.
- `server.js`: Servidor HTTP leve Node.js com suporte a fallback SPA e roteamento de assets estáticos.
- `public/`:
  - `assets/`: Todos os 108 assets originais (imagens AVIF/WebP, fontes JetBrains Mono e Archivo, estilos e scripts com os dados substituídos).
  - `favicon.png`, `apple-touch-icon.png`, `og-image.jpg`.
