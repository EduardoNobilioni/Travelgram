# Travelgram — Perfil de viagens

![Logo do Travelgram](./assets/Logo.svg)

Projeto desenvolvido durante o curso de Desenvolvimento Full Stack da **Rocketseat**, para praticar a construção de páginas web com **HTML e CSS**.

O Travelgram apresenta uma página de perfil de uma rede social de viagens, com informações da viajante Isabela Torres e uma galeria de registros dos destinos visitados.

## Sobre o projeto

A página reúne:

- Barra de navegação com logo, ícone de busca, links e foto de perfil.
- Apresentação da viajante com foto, nome e biografia.
- Informações de localização, países visitados e quantidade de fotos.
- Galeria com 12 fotografias de viagens.
- Rodapé com direitos autorais e textos de termos de uso e privacidade.

Este é um projeto estático de estudo. Os links de navegação são ilustrativos, e a página não implementa busca, autenticação ou publicação de fotos.

## Tecnologias utilizadas

- **HTML5:** estrutura e organização semântica do conteúdo.
- **CSS3:** estilização, espaçamento e organização do layout com Flexbox.
- **Google Fonts:** fonte Poppins.
- **SVG e PNG:** ícones, logotipo e fotografias.

## Aprendizados

- Uso de elementos semânticos como `nav`, `header`, `main` e `footer`.
- Alinhamento e distribuição de elementos com Flexbox.
- Organização da galeria com `flex-wrap` e `gap`.
- Definição de cores e tipografia com variáveis CSS.
- Separação dos estilos em arquivos por seção e importação com `@import`.
- Estilização de imagens, links e estados de `hover`.

## Como executar


1. Acesse https://eduardonobilioni.github.io/Travelgram/
2. Navegue pela página para conferir o layout 


Também é possível abrir a pasta no Visual Studio Code e executar o `index.html` com a extensão **Live Server** para acompanhar as alterações durante o desenvolvimento.

Não é necessário instalar dependências ou executar comandos de build. A fonte Poppins é carregada pelo Google Fonts e depende de conexão com a internet.

## Estrutura de arquivos

```text
Travelgram/
├── assets/
│   ├── icons/          # Ícones em SVG
│   ├── images/         # Fotografias da galeria
│   ├── Logo.svg
│   └── Profile pic.png
├── styles/
│   ├── global.css      # Estilos globais, variáveis e container
│   ├── nav.css         # Barra de navegação
│   ├── header.css      # Perfil e informações da viajante
│   ├── main.css        # Galeria de fotos
│   ├── footer.css      # Rodapé
│   └── index.css       # Importação das folhas de estilo
├── index.html
└── README.md
```

## Créditos

Projeto realizado como parte dos estudos do curso de Desenvolvimento Full Stack da **Rocketseat**.
