# 🛍️ Casa & Lar - Landing Page de E-Commerce

Uma landing page de e-commerce moderna, fluida, responsiva e focada em performance para a **Casa & Lar**, uma loja fictícia especializada em móveis, plantas, decorações e produtos artesanais de alta qualidade.

Este projeto foi construído para fornecer uma experiência de compra visualmente atraente e interativa, com design premium, transições suaves e design responsivo adaptável para celulares, tablets e desktops.

---

## 🚀 Tecnologias Utilizadas

O projeto utiliza uma stack front-end moderna e simplificada:

- **HTML5 Semântico**: Estruturação clara para melhor acessibilidade e SEO.
- **Tailwind CSS v3**: Estilização baseada em utilitários para desenvolvimento rápido de interfaces modernas.
- **PostCSS & Autoprefixer**: Otimização e retrocompatibilidade de CSS para navegadores antigos.
- **JavaScript Moderno (ES6+)**: Controle de comportamento da página, interações e sliders personalizados.
- **Google Fonts (Montserrat & Cormorant Garamond)**: Tipografia premium e elegante que reflete o tom sofisticado da marca.
- **Material Symbols & IonIcons**: Ícones limpos e modernos para enriquecer o visual.

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

### Passo 1: Instalar Dependências
No terminal do seu projeto, execute o comando abaixo para instalar as ferramentas de desenvolvimento (Tailwind CSS, PostCSS, Autoprefixer):

```bash
npm install
```

### Passo 2: Compilar os Estilos (CSS)
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

### Passo 3: Visualizar no Navegador
Após compilar o CSS pelo menos uma vez, basta abrir o arquivo [index.html](file:///D:/Iury/Programa%C3%A7%C3%A3o/casaelar/index.html) diretamente em qualquer navegador, ou utilizar extensões como o **Live Server** (do VS Code) para ter atualizações automáticas em tempo real.

---

## 🛠️ Detalhes de Customização do Tailwind CSS

No arquivo `tailwind.config.js`, foram mapeadas cores específicas que dão a identidade visual aconchegante da marca:

- **`papaya_whip` (`#ffefd5`)**: O tom claro e elegante de fundo.
- **`caf_noir` (`#4f3120`)**: O tom marrom escuro sofisticado usado para textos principais e botões.
- **`jet` (`#333333`)**: Textos secundários.
- **`butterscotch` (`#e9973f`)**: Destaques de preços, descontos e taxas de desconto de promoções.
