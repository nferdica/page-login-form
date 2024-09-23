# Projeto de Página de Login e Cadastro

Este projeto é uma interface simples de login e cadastro, desenvolvida com HTML, CSS e utiliza a fonte Roboto. A aplicação possui duas páginas principais: uma de login e outra de cadastro, ambas estilizadas para serem responsivas e funcionarem bem em diferentes tamanhos de tela.

## Estrutura do Projeto

- `index.html`: Página de login.
- `signup.html`: Página de cadastro.
- `style.css`: Arquivo de estilo responsável pela aparência das páginas.

## Funcionalidades

### Página de Login (`index.html`):
- Um formulário simples de login, com campos para e-mail e senha.
- Um botão para realizar o login.
- Link para a página de cadastro, caso o usuário não tenha uma conta.

### Página de Cadastro (`signup.html`):
- Um formulário de cadastro, com campos para nome, e-mail e senha.
- Um campo checkbox para que o usuário aceite os termos de uso.
- Um botão para criar a conta.
- Link para voltar à página de login, caso o usuário já tenha uma conta.

### Estilização (`style.css`):
- Uso da fonte Roboto para um visual moderno.
- Layout flexível que se ajusta ao tamanho da tela.
- Estilização personalizada para botões, inputs e links.
- Animação de transição suave nos botões.
- Elementos responsivos que se adaptam em dispositivos móveis.

## Como Executar

1. Clone o repositório ou faça o download dos arquivos.
2. Abra o arquivo `index.html` ou `signup.html` em um navegador para visualizar as páginas.

### Fonte Utilizada

A fonte `Roboto` foi carregada diretamente do Google Fonts:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
```

## Estrutura de Pastas

```
├── assets/
│   ├── info.png      # Imagem ilustrativa usada na página
│   ├── code.svg      # Ícone decorativo no formulário
├── index.html        # Página de login
├── signup.html       # Página de cadastro
├── style.css         # Arquivo de estilos
```

## Responsividade

O layout foi projetado para ser responsivo, utilizando media queries para ajustar os elementos em telas menores. A partir de 700px e 500px, as imagens e textos se adaptam para melhorar a legibilidade e o uso em dispositivos móveis.

## Licença

Este projeto é de código aberto e pode ser usado livremente para estudos e personalizações.