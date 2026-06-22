# 🛍️ Casa & Lar - Landing Page de E-Commerce

Uma landing page de e-commerce moderna, fluida, responsiva e focada em performance para a **Casa & Lar**, uma loja fictícia especializada em móveis, plantas, decorações e produtos artesanais de alta qualidade.

Este projeto foi construído para fornecer uma experiência de compra visualmente atraente e interativa, com design premium, transições suaves e design responsivo adaptável para celulares, tablets e desktops.

---

## 🚀 Tecnologias Utilizadas

| Tecnologia |
| :--- |
| HTML5 |
| Tailwind CSS v3 |
| PostCSS |
| Autoprefixer |
| JavaScript (ES6+) |
| Google Fonts |
| Material Symbols |
| IonIcons |

---

## ✨ Principais Funcionalidades

1. **Cabeçalho Inteligente (Sticky Header)**: Barra de navegação que se fixa no topo da página quando o usuário rola para baixo (após 50px), mudando seu plano de fundo para garantir leitura perfeita.
2. **Menu Responsivo (Mobile Off-canvas Menu)**: Menu lateral interativo que se abre em dispositivos menores, melhorando a navegabilidade em smartphones.
3. **Menu Dropdown Interativo**: Submenu dinâmico para categorias da loja (Produtos, Roupas, Plantas, Acessórios, Mochilas, Relógios e Promoções).
4. **Carrinho de Compras Modal**: Janela modal interativa para visualização fácil de itens selecionados.
5. **Slider de Avaliações / Testemunhos (Custom Slider)**:
   - Carrossel automático com transição a cada 2 segundos.
   - Botões manuais de navegação ("Anterior" e "Próximo").
   - Pausa inteligente no carrossel quando o usuário passa o mouse por cima (hover) para facilitar a leitura das avaliações dos clientes, retornando o movimento ao tirar o ponteiro.
6. **Efeitos Visuais Premium**: Elementos com blur dinâmico, efeitos de zoom suave em imagens durante o hover e seções de destaque para promoções selecionadas.

---

## 📁 Estrutura do Projeto

Abaixo está o mapeamento dos principais arquivos e pastas do projeto:

```text
casaelar/
├── assets/                  # Arquivos estáticos e recursos do site
│   ├── imgs/                # Imagens do e-commerce (móveis, roupas, etc.)
│   ├── images/              # Ícones e imagens originais do template base
│   └── js/
│       └── script.js        # Lógica JavaScript (Slider, Navbar, Modal)
├── dist/                    # Pasta de distribuição gerada pelo Tailwind
│   └── style.css            # CSS compilado e otimizado para produção
├── src/                     # Pasta de código fonte dos estilos
│   └── style.css            # Estilo fonte utilizando diretivas do Tailwind
├── index.html               # Página principal da aplicação
├── package.json             # Dependências de desenvolvimento e scripts
├── postcss.config.js        # Configuração do PostCSS
├── tailwind.config.js       # Customizações do Tailwind (paleta de cores, fontes)
└── README.md                # Documentação técnica e do projeto
```

---

## 🔧 Como Executar o Projeto Localmente

Siga o passo a passo abaixo para rodar o projeto em sua máquina:

### Pré-requisitos
Certifique-se de ter o [Node.js](https://nodejs.org/) instalado em seu computador para poder instalar as dependências e compilar os estilos do Tailwind CSS.

### Passo 1: Clone este Repositório
Abra o terminal e execute o comando abaixo para clonar o repositório em sua máquina:
```bash
git clone https://github.com/allespin/ecommerce-landing-page-casa-e-lar.git
```

### Passo 2: Instalar Dependências
Navegue até a pasta do projeto clonado e execute o comando para instalar as ferramentas de desenvolvimento (Tailwind CSS, PostCSS, Autoprefixer):
```bash
npm install
```

### Passo 3: Compilar os Estilos (CSS)
Para gerar o arquivo final de CSS compilado na pasta `dist/style.css`, você possui dois scripts configurados:

*   **Para Desenvolvimento (Modo Observador / Watch):**
    Este comando observa as alterações nos seus arquivos HTML e CSS fonte e recompila automaticamente sempre que você salvar algo:
    ```bash
    npm run watch
    ```

*   **Para Produção (Build Único):**
    Gera o CSS compilado final de uma só vez:
    ```bash
    npm run build
    ```

### Passo 4: Visualizar no Navegador
Após compilar o CSS pelo menos uma vez, basta abrir o arquivo [index.html](file:///D:/Iury/Programa%C3%A7%C3%A3o/casaelar/index.html) diretamente em qualquer navegador, ou utilizar extensões como o **Live Server** (do VS Code) para ter atualizações automáticas em tempo real.

---

## 🛠️ Detalhes de Customização do Tailwind CSS

No arquivo `tailwind.config.js`, foram mapeadas cores específicas que dão a identidade visual aconchegante da marca:

- **`papaya_whip` (`#ffefd5`)**: O tom claro e elegante de fundo.
- **`caf_noir` (`#4f3120`)**: O tom marrom escuro sofisticado usado para textos principais e botões.
- **`jet` (`#333333`)**: Textos secundários.
- **`butterscotch` (`#e9973f`)**: Destaques de preços, descontos e taxas de desconto de promoções.

---

# 🛍️ Casa & Lar - E-Commerce Landing Page

A modern, fluid, responsive, and performance-focused e-commerce landing page for **Casa & Lar**, a fictional store specializing in high-quality furniture, plants, decor, and handcrafted items.

This project was built to provide a visually attractive and interactive shopping experience with premium design, smooth transitions, and a responsive layout that adapts to mobile devices, tablets, and desktops.

---

## 🚀 Technologies Used

| Technology |
| :--- |
| HTML5 |
| Tailwind CSS v3 |
| PostCSS |
| Autoprefixer |
| JavaScript (ES6+) |
| Google Fonts |
| Material Symbols |
| IonIcons |

---

## ✨ Key Features

1. **Sticky Header**: Navigation bar that sticks to the top of the page when the user scrolls down (after 50px), changing its background to ensure perfect readability.
2. **Mobile Off-canvas Menu**: An interactive sidebar menu that opens on smaller devices, improving navigation on smartphones.
3. **Interactive Dropdown Menu**: A dynamic submenu for store categories (Products, Clothes, Plants, Accessories, Backpacks, Watches, and Sales).
4. **Shopping Cart Modal**: An interactive modal window for easily viewing selected items.
5. **Review / Testimonial Slider (Custom Slider)**:
   - Auto-sliding carousel that transitions every 2 seconds.
   - Manual navigation buttons ("Prev" and "Next").
   - Smart pause on hover so users can comfortably read client reviews, resuming movement when the mouse pointer leaves.
6. **Premium Visual Effects**: Dynamic blur elements, smooth zoom effects on images during hover, and highlighted sections for special deals.

---

## 📁 Project Structure

Below is the directory mapping of the main project files and folders:

```text
casaelar/
├── assets/                  # Static assets and site resources
│   ├── imgs/                # E-commerce images (furniture, clothes, etc.)
│   ├── images/              # Icons and original images from base template
│   └── js/
│       └── script.js        # JavaScript logic (Slider, Navbar, Modal)
├── dist/                    # Distribution folder generated by Tailwind
│   └── style.css            # Compiled and optimized CSS for production
├── src/                     # Style source files folder
│   └── style.css            # Source CSS using Tailwind directives
├── index.html               # Main application HTML file
├── package.json             # Dev dependencies and scripts
├── postcss.config.js        # PostCSS configuration
├── tailwind.config.js       # Tailwind configuration (color palette, fonts)
└── README.md                # Project and technical documentation
```

---

## 🔧 How to Run the Project Locally

Follow the steps below to run the project on your machine:

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) installed on your computer to install development dependencies and compile Tailwind CSS styles.

### Step 1: Clone this Repository
Open the terminal and run the command below to clone the repository to your machine:
```bash
git clone https://github.com/allespin/ecommerce-landing-page-casa-e-lar.git
```

### Step 2: Install Dependencies
Navigate into the cloned project folder and execute the command to install dev tools (Tailwind CSS, PostCSS, Autoprefixer):
```bash
npm install
```

### Step 3: Compile Styles (CSS)
To compile the CSS styles into the `dist/style.css` file, you have two configured scripts:

*   **For Development (Watch Mode):**
    This command watches for changes in your HTML and source CSS files and automatically recompiles whenever you save:
    ```bash
    npm run watch
    ```

*   **For Production (Single Build):**
    Generates the final compiled CSS in one run:
    ```bash
    npm run build
    ```

### Step 4: View in Browser
After compiling the CSS at least once, simply open [index.html](file:///D:/Iury/Programa%C3%A7%C3%A3o/casaelar/index.html) directly in any browser, or use extensions like VS Code's **Live Server** to get real-time hot reloading.

---

## 🛠️ Tailwind CSS Customization Details

In the `tailwind.config.js` file, specific colors were mapped to give the brand its cozy visual identity:

- **`papaya_whip` (`#ffefd5`)**: The light and elegant background tone.
- **`caf_noir` (`#4f3120`)**: The sophisticated dark brown tone used for primary text and buttons.
- **`jet` (`#333333`)**: Secondary text color.
- **`butterscotch` (`#e9973f`)**: Highlights for prices, discounts, and sale badges.
