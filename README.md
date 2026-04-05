# Associação Pró Família

Site institucional estático da Associação Pró Família, com foco em apresentar a história da organização, projetos sociais e formas de apoio.

## Visão geral

O projeto foi construído como um website multi-página, sem backend, para comunicar:

- A missão da associação
- O impacto social dos projetos
- A trajetória da instituição
- As opções de doação e voluntariado

## Stack utilizada

### Frontend

- HTML5 (páginas estáticas)
- CSS3 (estilos customizados em `css/styles.css`)
- Tailwind CSS via CDN (`https://cdn.tailwindcss.com`)

### Tipografia e ícones

- Google Fonts:
	- Plus Jakarta Sans
	- Lexend
- Material Symbols Outlined (Google)

### Hospedagem (provável)

- Estrutura compatível com hospedagem estática (ex.: GitHub Pages)
- Arquivo `CNAME` presente para domínio personalizado

## Estrutura do projeto

```text
Associacao-Pro-Familia/
├── CNAME
├── projetos.html
├── index.html
├── sobre.html
├── ajuda.html
├── css/
│   └── styles.css
└── assets/
		└── images/
```

## Páginas principais

- `index.html`: página inicial institucional
- `projetos.html`: seção de projetos de impacto
- `sobre.html`: história e trajetória da associação
- `ajuda.html`: formas de contribuir (doação/voluntariado)

## Mapa do site (visual)

```text
index.html (Início)
├── sobre.html (Nossa História)
├── projetos.html (Projetos)
└── ajuda.html (Como Ajudar)
```

## Mapa do site (listado e descrito)

1. `index.html` - Início
	- Hero institucional
	- Seção da escola e missão
	- Bloco de iniciativas/notícias
	- CTA para doação e voluntariado

2. `sobre.html` - Nossa História
	- Hero da trajetória
	- Linha do tempo (marcos históricos)
	- Bloco de valores e identidade
	- CTA institucional

3. `projetos.html` - Projetos
	- Cabeçalho de projetos de impacto
	- Projeto em destaque
	- Grade de projetos sociais
	- Bloco de engajamento/newsletter

4. `ajuda.html` - Como Ajudar
	- Hero de engajamento
	- Opções e impacto de doação
	- Oportunidades de voluntariado
	- Doação de itens e chamada final

### Navegação principal

O menu principal está presente nas quatro páginas e conecta diretamente:

- Início -> `index.html`
- Nossa História -> `sobre.html`
- Projetos -> `projetos.html`
- Como Ajudar -> `ajuda.html`

## Como executar localmente

Como é um projeto estático, existem duas formas simples:

1. Abrir diretamente os arquivos `.html` no navegador.
2. Rodar um servidor local (recomendado para navegação completa entre páginas).

Exemplo com VS Code Live Server:

1. Instale a extensão Live Server.
2. Clique com o botão direito em `index.html`.
3. Selecione **Open with Live Server**.

Exemplo com Python:

```bash
python -m http.server 5500
```

Depois, acesse:

```text
http://localhost:5500/index.html
```

## Características técnicas

- Layout responsivo com utilitários Tailwind
- Tema visual consistente com paleta customizada no `tailwind.config` inline de cada página
- Estilos compartilhados em `css/styles.css`
- Navegação simples entre páginas estáticas

## Melhorias futuras sugeridas

- Centralizar o `tailwind.config` para evitar repetição entre páginas
- Adicionar JavaScript modular para interações (menu mobile, formulários, analytics)
- Incluir pipeline de build (Vite) para otimização de CSS e assets
- Configurar SEO técnico adicional (Open Graph, sitemap, robots.txt)

## Licença

Definir licença de uso do código e dos ativos visuais (imagens e identidade da associação).