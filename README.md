# Cadastro Responsivo

Formulário de cadastro (criação de conta) totalmente responsivo, desenvolvido com **HTML, CSS e JavaScript puro**, com validação de campos no front-end.

🔗 **[Ver projeto online](https://cadastro-responsivo-3lvrs4133-gabriel-luz.vercel.app)**

## 📋 Sobre o projeto

A ideia foi construir, do zero e sem frameworks, um formulário de cadastro completo — cobrindo desde a estruturação semântica do HTML até a validação dos dados digitados pelo usuário, sempre com feedback visual claro sobre o que está certo ou errado em cada campo.

## ✨ Funcionalidades

- Formulário com os campos: primeiro nome, sobrenome, data de nascimento, e-mail, senha, confirmação de senha e gênero (via radio buttons)
- Validação de todos os campos no envio do formulário:
  - **Nome / Sobrenome**: obrigatório, mínimo de 3 caracteres, apenas letras
  - **Data de nascimento**: obrigatória, ano entre 1920 e o ano atual
  - **E-mail**: obrigatório, precisa ter um formato válido
  - **Senha**: obrigatória, mínimo de 8 caracteres, com pelo menos 1 letra maiúscula, 1 minúscula, 1 número e 1 caractere especial
  - **Confirmar senha**: precisa ser idêntica à senha informada
  - **Gênero**: seleção obrigatória
- Feedback visual imediato (borda e texto verde para campo válido, vermelho com mensagem de erro para campo inválido)
- Botão de mostrar/ocultar senha (ícone de olho)
- Layout adaptado para telas menores (mobile)

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3 (Flexbox, Grid e Media Queries)
- JavaScript (manipulação de DOM e expressões regulares)
- [Font Awesome](https://fontawesome.com/) — ícones
- [Google Fonts](https://fonts.google.com/) — fonte Poppins

## 📁 Estrutura do projeto

```
cadastro-responsivo/
├── index.html   # Estrutura do formulário
├── style.css    # Estilização e responsividade
├── script.js    # Lógica de validação dos campos
└── README.md
```

## 🚀 Como executar

Por ser um projeto estático, não há dependências para instalar.

```bash
# 1. Clone o repositório
git clone https://github.com/GabrielCagliariLuz/cadastro-responsivo.git

# 2. Entre na pasta do projeto
cd cadastro-responsivo

# 3. Abra o index.html no navegador
```

> Dica: usar a extensão **Live Server** (VS Code) facilita bastante, pois recarrega a página automaticamente a cada alteração.

## 🧠 Conceitos praticados

- Manipulação do DOM com JavaScript
- Expressões regulares (regex) para validação de campos
- Eventos de formulário (`submit`, `click`)
- Design responsivo com Media Queries
- Boas práticas de UX em formulários (feedback de erro/sucesso por campo)

## 👤 Autor

[@GabrielCagliariLuz](https://github.com/GabrielCagliariLuz)
