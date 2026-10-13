# Biblioteca Digital UniFECAF

Projeto front-end estático desenvolvido como atividade acadêmica de Web Design para apresentar uma biblioteca digital institucional da UniFECAF. A página foi estruturada em HTML5 e estilizada em CSS3, com foco em responsividade, navegação por seções e apresentação visual moderna para estudantes e usuários da instituição.

## Visão geral

Este projeto simula uma landing page de uma biblioteca universitária, com objetivo de divulgar os serviços, recursos, acervo e áreas de atendimento da instituição. O site foi pensado para transmitir uma imagem moderna, confiável e tecnológica, reforçando a ideia de acesso digital e de suporte ao aprendizado.

A página inclui:
- apresentação institucional da biblioteca;
- destaque para a proposta digital e acadêmica;
- seção de livros e materiais de estudo;
- apresentação das unidades da instituição;
- área de contato e localização;
- layout responsivo para desktop e mobile.

## Objetivo do projeto

O principal objetivo do site é demonstrar, de forma visual e organizada, como uma biblioteca digital pode oferecer acesso ao conhecimento de maneira prática e acessível. A página reforça a ideia de que a tecnologia pode facilitar o estudo, reduzir barreiras físicas e aproximar os alunos de conteúdos de qualidade.

## Tecnologias utilizadas

- HTML5: estrutura semântica da página
- CSS3: layout, cores, responsividade, imagens e espaçamento
- Google Fonts: tipografia Poppins
- Imagens locais: arquivos de mídia armazenados na pasta `css/image`

## Estrutura do projeto

```text
TRABALHO_HTML_FECAF/
├── index.html
├── css/
│   ├── style.css
│   └── image/
│       ├── biblioteca1.jpg
│       ├── biblioteca2.jpg
│       ├── biblioteca3.jpg
│       ├── biblioteca4.jpg
│       ├── biblioteca5.jpg
│       ├── livro1.webp
│       ├── livro2.webp
│       ├── livro3.jpg
│       ├── livro4.jpg
│       ├── livro5.jpg
│       ├── livro6.jpg
│       ├── unidade1.jpg
│       ├── unidade2.webp
│       ├── unidade3.jpg
│       ├── logo.png
│       ├── lobo.png
│       ├── img2.jpg
│       └── ...
└── README.md
```

## Descrição das seções da página

### 1. Cabeçalho e navegação
O topo da página contém um menu de navegação com links para:
- Biblioteca
- Livros
- Unidades
- Contato

A navegação foi pensada para orientar o usuário de forma direta e criar uma experiência mais fluida de leitura.

### 2. Seção de apresentação da biblioteca
A primeira área de conteúdo destaca a biblioteca digital da UniFECAF, explicando os benefícios do acesso on-line a materiais acadêmicos. A mensagem reforça a acessibilidade, a disponibilidade 24 horas e a praticidade de estudar sem depender de deslocamentos físicos.

### 3. Galeria visual
A página utiliza uma combinação de imagens para ilustrar o ambiente acadêmico e a proposta da biblioteca. Essa parte ajuda a criar identidade visual e a transmitir uma imagem institucional moderna.

### 4. Seção de livros
Nesta seção, o site apresenta uma grade com seis livros, cada um com:
- título;
- imagem representativa;
- descrição do tema abordado.

Os conteúdos abordados incluem lógica de programação, JavaScript, Java, Rust, SQL e UX. Essa seleção reforça a proposta de apoio acadêmico e desenvolvimento profissional.

### 5. Seção de unidades
A página mostra as diferentes unidades da instituição, com imagens e textos curtos explicando os espaços e os serviços oferecidos. A ideia é demonstrar que a universidade possui estrutura e apoio em diversos ambientes.

### 6. Seção de contato
A última parte do site possui informações de contato, incluindo:
- local da sede;
- telefone/WhatsApp;
- mensagem institucional de apoio ao aluno.

A seção também inclui um mascote visual, o que torna a identidade da página mais amigável e memorável.

### 7. Rodapé
O rodapé encerra a página com informações institucionais e autoria do projeto, deixando o layout completo e profissional.

## Design e experiência do usuário

O projeto foi desenvolvido com foco em:
- legibilidade;
- contraste adequado entre fundo e texto;
- organização visual por blocos;
- layouts responsivos para diferentes tamanhos de tela;
- interface limpa e intuitiva.

O CSS inclui media queries para adaptar o conteúdo em telas menores, mantendo leitura confortável e bom aproveitamento do espaço.

## Como executar o projeto

Como trata-se de uma página estática, você pode abrir o arquivo `index.html` diretamente no navegador. Também é possível servir a pasta localmente com um servidor simples.

### Opção 1: abrir diretamente
1. Abra a pasta do projeto no explorador.
2. Clique duas vezes em `index.html`.
3. O navegador abrirá a página automaticamente.

### Opção 2: via servidor local
No terminal, na raiz do projeto, execute:

```bash
python -m http.server 8000
```

Depois, abra no navegador:

```text
http://localhost:8000
```

## Personalização

Para adaptar o projeto, você pode alterar:
- textos e descrições das seções;
- imagens da pasta `css/image`;
- cores e estilos no arquivo `css/style.css`;
- títulos, textos de contato e informações institucionais em `index.html`.

## Observações

Este é um projeto acadêmico e didático, voltado para prática de desenvolvimento front-end com HTML e CSS. O foco principal está no layout e na apresentação visual, sem uso de frameworks ou JavaScript para interações complexas.

## Autor

Projeto desenvolvido por: Fabio Ramos Cardoso

## Licença

Este projeto foi criado para fins acadêmicos e de apresentação. Caso queira reutilizá-lo, é recomendável manter os créditos e referências do autor e da instituição mencionados no projeto.
