# Maraketo

Plano keto de 7 dias (26/11/2026 a 02/12/2026), lista de compras e registro de peso com gráfico.
App instalável (PWA): funciona offline depois da primeira abertura.

Os dados (pesos, marcações, trocas) ficam só no navegador de cada aparelho.
Use Exportar e Importar na aba Peso para fazer backup ou levar os dados para outro aparelho.

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub (por exemplo `maraketo`) e envie estes arquivos para a raiz dele.
2. No repositório: Settings > Pages > Source: "Deploy from a branch" > Branch: `main` e pasta `/ (root)` > Save.
3. Depois de 1 a 2 minutos o app fica em `https://SEU-USUARIO.github.io/maraketo/`.
4. No celular, abra o link e use "Instalar app" (Android/Chrome) ou Compartilhar > "Adicionar à Tela de Início" (iPhone/Safari).

Para atualizar o app depois: altere os arquivos, troque o número em `CACHE` no `sw.js` (ex.: `maraketo-v2`) e envie de novo.
