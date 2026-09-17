# SyntaxWear

Landing page de uma loja de tênis e sneakers com estética urbana, navegação por categorias e layout responsivo para desktop e dispositivos móveis.

## Visão geral

O SyntaxWear apresenta a coleção **Kripton One** e organiza os produtos por estilo:

- Casual
- Esporte
- Moderno
- Futurista

A página também possui navegação para as áreas masculina, feminina e outlet, atalhos de conta, ajuda e carrinho, formulário de inscrição por e-mail e links para redes sociais.

> **Status:** projeto de front-end estático. Os links, o formulário de newsletter e os atalhos de e-commerce são elementos visuais e ainda não estão conectados a um back-end.

## Funcionalidades

- Hero banner com chamada principal e botões de ação.
- Menu de navegação com categorias da loja.
- Menu mobile acionado por checkbox e ícone de hambúrguer.
- Cards de categorias com imagens de destaque.
- Galeria de produtos com CSS Grid.
- Rodapé com navegação, newsletter e redes sociais.
- Layout adaptado para diferentes tamanhos de tela.
- Imagens, ícones e identidade visual armazenados no próprio projeto.

## Tecnologias

- HTML5 semântico
- CSS3
- CSS Grid e Flexbox
- Media queries para responsividade
- Google Fonts (Roboto Mono, Roboto e Ubuntu)

Não há framework, bundler ou dependências de Node.js neste projeto.

## Como executar

### Opção 1: abrir diretamente no navegador

1. Clone ou baixe este repositório.
2. Acesse a pasta `ecommerce-syntaxwear`.
3. Abra o arquivo `index.html` no navegador.

### Opção 2: usar um servidor local

Para evitar limitações de carregamento de arquivos locais e simular um ambiente web, inicie um servidor HTTP na pasta do projeto:

```bash
cd ecommerce-syntaxwear
python -m http.server 8000
```

Depois, abra <http://localhost:8000> no navegador.

Também é possível usar a extensão **Live Server** no VS Code.

## Estrutura do projeto

```text
ecommerce-syntaxwear/
├── index.html
├── css/
│   ├── reset.css
│   ├── variables.css
│   ├── styles.css
│   └── componentes/
│       ├── base.css
│       ├── footer.css
│       ├── header.css
│       ├── hero.css
│       ├── product-category.css
│       └── product-grid.css
└── images/
    ├── banners/
    ├── icons/
    ├── logo/
    └── products/
```

### Organização dos estilos

- `reset.css`: normalização dos estilos padrão do navegador.
- `variables.css`: variáveis visuais e regras gerais da página.
- `styles.css`: estilos da composição principal e dos botões.
- `css/componentes/`: estilos separados por área da interface.

## Personalização

- Altere as cores globais em `css/variables.css`.
- Troque o banner principal em `css/componentes/hero.css`.
- Atualize imagens de categorias e produtos nos arquivos correspondentes em `css/componentes/`.
- Edite textos, links e conteúdo das seções diretamente em `index.html`.
- Para adicionar produtos à galeria, crie um novo card em `index.html` e defina sua imagem no CSS.

## Próximos passos

Algumas evoluções possíveis para transformar a landing page em uma loja funcional:

- Conectar os links de navegação às páginas de categoria.
- Implementar catálogo, busca e filtros de produtos.
- Adicionar carrinho e checkout.
- Integrar o formulário de newsletter a um serviço de e-mail.
- Substituir os links provisórios das redes sociais e áreas institucionais.
- Adicionar testes de acessibilidade e otimização das imagens.

## Licença

Este projeto não possui uma licença definida. Consulte os responsáveis pelo repositório antes de reutilizar o código ou os assets.
