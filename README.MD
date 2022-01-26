# iniciar o yarn
- yarn init -y

# instala as boblioitecas
- yarn add next react react-dom
- Adicionar scripts ao arquivo package.json:
  
"scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
    }

# Criar uma pasta "pages"
# adicionar um arquivo "index.js"

function HomePage() {
    return <div>Welcome to Next.js!</div>
}

export default HomePage

# documentação nextjs
https://nextjs.org/docs/getting-started

# documentação styled jsx
https://github.com/vercel/styled-jsx
- npm install --save styled-jsx
