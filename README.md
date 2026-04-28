# 🎯 SyntaxWear - E-commerce de Tênis e Sneakers

Uma plataforma de e-commerce moderna e responsiva para venda de tênis e sneakers, desenvolvida com HTML5, CSS3 e estrutura organizada em componentes.

![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Mobile%20First-green)

---


## 🌐 Visão Geral

**SyntaxWear** é uma plataforma de e-commerce especializada na venda de tênis e sneakers online. O site foi desenvolvido seguindo os princípios de design moderno, acessibilidade e responsividade para proporcionar uma excelente experiência de compra em qualquer dispositivo.

### Principais Destaques:
- ✅ Design responsivo (Mobile First)
- ✅ Interface limpa e intuitiva
- ✅ Navegação acessível com ARIA labels
- ✅ Estrutura CSS modularizada em componentes
- ✅ Múltiplas categorias de produtos
- ✅ Seção de destaque (Hero) com call-to-action
- ✅ Grid de produtos em destaque
- ✅ Newsletter para inscrições
- ✅ Integração com redes sociais

---

## 📁 Estrutura do Projeto

```
ecommerce-syntaxwear/
│
├── index.html                  # Página principal do site
├── README.md                   # Este arquivo
│
├── css/                        # Estilos CSS
│   ├── reset.css              # Reset de estilos padrão do navegador
│   ├── variables.css          # Variáveis CSS (cores, fonts, espaçamentos)
│   ├── base.css               # Estilos base e globais
│   ├── layout.css             # Layout geral da página
│   │
│   └── components/            # Estilos dos componentes
│       ├── header.css         # Estilo do cabeçalho e navegação
│       ├── hero.css           # Estilo da seção hero/banner principal
│       ├── product-category.css # Estilo das categorias de produtos
│       ├── product-grid.css   # Estilo do grid de produtos em destaque
│       └── footer.css         # Estilo do rodapé
│
├── images/                     # Imagens e assets
│   ├── banners/               # Imagens dos banners e hero sections
│   ├── favicons/              # Ícones do site (favicon, etc)
│   ├── icons/                 # Ícones SVG (menu, user, carrinho, etc)
│   ├── logo/                  # Logo da empresa
│   └── products/              # Imagens dos produtos
│
├── js/                        # Arquivos JavaScript (em desenvolvimento)
│   └── (Em breve)
│
└── .git/                      # Controle de versão Git
```

---

## ✨ Características

### 1. **Header Responsivo**
- Logo da marca com link para home
- Menu hambúrguer para dispositivos mobile
- Navegação por categorias (Masculino, Feminino, Outlet)
- Links de acesso rápido (Lojas, Sobre, Minha Conta, Ajuda, Carrinho)
- Ícones SVG para melhor qualidade em qualquer resolução

### 2. **Seção Hero**
- Banner destaque com imagem de fundo
- Conteúdo sobreposto com título, subtítulo e CTA
- Botões para navegação ("Ver modelos" e "Comprar")
- Design atrativo com overlay

### 3. **Categorias de Produtos**
- 4 categorias principais: Casual, Esporte, Moderno, Futurista
- Cards com imagens de fundo e overlay
- Links navegáveis para cada categoria

### 4. **Grid de Produtos em Destaque**
- Layout em grid responsivo
- 6 cards de produtos em diferentes tamanhos
- Produto em destaque (Krypton One) com conteúdo próprio
- Botões CTA com opções de gênero

### 5. **Rodapé**
- Formulário de newsletter para inscrições
- Links de redes sociais
- Informações de contato e política
- Design limpo e profissional

---

## 🛠️ Tecnologias

| Tecnologia | Descrição |
|-----------|-----------|
| **HTML5** | Estrutura semântica e acessível |
| **CSS3** | Estilização moderna com Flexbox e Grid |
| **SVG** | Ícones escaláveis e logos |
| **Responsive Design** | Mobile First approach |
| **Acessibilidade (ARIA)** | Labels ARIA para navegação acessível |

### Suporte de Navegadores:
- Chrome (última versão)
- Firefox (última versão)
- Safari (última versão)
- Edge (última versão)
- Navegadores mobile (iOS Safari, Chrome Mobile)

---

## 🚀 Como Usar

### Instalação

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/ecommerce-syntaxwear.git
   ```

2. **Navegue até a pasta do projeto:**
   ```bash
   cd ecommerce-syntaxwear
   ```

3. **Abra o arquivo index.html no navegador:**
   - Método 1: Clique duplo no `index.html`
   - Método 2: Use um servidor local (recomendado)

### Usando um Servidor Local (Recomendado)

Se você tem Python instalado:
```bash
python -m http.server 8000
```

Depois acesse: `http://localhost:8000`

Se você tem Node.js com Live Server:
```bash
npm install -g live-server
live-server
```

---

## 🎨 Componentes

### Header
**Arquivo:** `css/components/header.css`
- Navigation bar com logo
- Menu responsivo com toggle checkbox
- Links para categorias e acesso rápido
- Ícones de interação

### Hero Section
**Arquivo:** `css/components/hero.css`
- Banner principal com background image
- Texto sobreposto (título, subtítulo, CTA)
- Overlay para melhor contraste
- Buttons responsivos

### Product Categories
**Arquivo:** `css/components/product-category.css`
- Cards de categorias (4 tipos)
- Background images para cada categoria
- Hover effects com overlay
- Links interativos

### Product Grid
**Arquivo:** `css/components/product-grid.css`
- Grid responsivo (CSS Grid)
- 6 produtos em diferentes tamanhos
- Card em destaque (top1)
- Adaptável para diferentes resoluções

### Footer
**Arquivo:** `css/components/footer.css`
- Seção de newsletter
- Links de redes sociais
- Informações de contato
- Copyright e policies

---

## 🎨 Organização de Estilos

### reset.css
Remove os estilos padrão do navegador para ter uma base consistente.

### variables.css
Define variáveis CSS globais:
- **Cores:** Primárias, secundárias, neutras
- **Tipografia:** Famílias de fontes, tamanhos
- **Espaçamentos:** Margens, paddings padrão
- **Breakpoints:** Pontos de pausa responsivos

### base.css
Estilos globais aplicados em toda a página:
- Tipografia base
- Estilos de links
- Inputs e forms
- Classes utilitárias

### layout.css
Estrutura geral e layout da página:
- Container principal
- Grid system
- Flexbox utilities

### components/ (Modulares)
Cada componente tem seu próprio arquivo CSS para melhor manutenção:
- Encapsulamento de estilos
- Reutilização de código
- Fácil identificação e modificação

---

## 🖼️ Imagens e Assets

### Estrutura de Pastas de Imagens:

**banners/** - Imagens grandes de banners e hero sections
- Formato: JPG/WebP (comprimido)
- Tamanho: 1920px de largura mínima

**favicons/** - Ícones do site
- Formatos: .ico, .png (múltiplos tamanhos)
- Tamanho: 16x16, 32x32, 192x192, 512x512

**icons/** - Ícones SVG para UI
- hamburguer.svg - Menu mobile
- user.svg - Ícone de usuário
- help.svg - Ícone de ajuda
- bag.svg - Ícone de carrinho
- Outros ícones de interação

**logo/** - Logo da marca
- logo.svg - Logo principal
- Formato vetorial para qualquer resolução

**products/** - Imagens dos produtos
- Formato: JPG/WebP
- Resolução: Mínimo 400x400px
- Background branco ou transparente

---

## 📱 Responsividade

O site segue a abordagem **Mobile First** com breakpoints:

```css
/* Mobile: 0px - 640px */
/* Tablet: 641px - 1024px */
/* Desktop: 1025px+ */
```

Todos os componentes são testados e otimizados para:
- ✅ Smartphones (320px+)
- ✅ Tablets (768px+)
- ✅ Desktops (1024px+)

---

## ♿ Acessibilidade

O projeto segue as melhores práticas de acessibilidade:

- **ARIA Labels:** Descrições significativas para leitores de tela
- **Semântica HTML:** Tags apropriadas (`<header>`, `<nav>`, `<main>`, `<footer>`)
- **Contraste:** Cores com contraste suficiente
- **Text Alternatives:** Texto alternativo em todas as imagens
- **Navegação por Teclado:** Interface navegável sem mouse

---

## 🔧 Desenvolvimento

### Adicionando Novos Componentes

1. Crie um novo arquivo em `css/components/componente.css`
2. Importe no `index.html` após o arquivo base.css
3. Use classes BEM para nomenclatura:
   ```css
   .component { }
   .component__element { }
   .component--modifier { }
   ```

### Modificando Variáveis

Todas as cores, fonts e espaçamentos estão em `css/variables.css`:
```css
:root {
  --color-primary: #000;
  --color-secondary: #fff;
  --spacing-unit: 8px;
  /* ... mais variáveis */
}
```
