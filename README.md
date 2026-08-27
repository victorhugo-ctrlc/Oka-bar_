# OKA — site estático V4

## Deploy no GitHub + Vercel
1. Suba **todos os arquivos desta pasta** para a raiz do repositório.
2. No Vercel, importe o repositório.
3. Framework Preset: **Other**.
4. Build Command: deixe vazio.
5. Output Directory: deixe vazio / raiz.
6. Deploy.

### Importante
Não coloque `index.html` dentro de uma subpasta se o projeto Vercel estiver apontando para a raiz.

Esta versão não depende de React, Next, Tailwind ou JavaScript para renderizar o conteúdo principal. O HTML já contém o conteúdo, e o JS só adiciona interações.

As fotos públicas externas têm fallback local para evitar blocos vazios caso o servidor externo não responda.
