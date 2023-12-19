# Guia Inicial para Uso do GitHub e Git

Bem-vindo ao mundo do controle de versão com Git e hospedagem de código no GitHub! Este guia fornecerá os passos iniciais para você começar a compartilhar seus projetos de software, colaborar em projetos de outras pessoas e gerenciar suas versões de código.

## 1. Crie sua conta no GitHub

Acesse [GitHub](https://github.com/) e crie uma conta. Se você já tiver uma conta, faça login.

## 2. Baixe e instale o Git

Instale o Git em seu computador seguindo as instruções específicas para o seu sistema operacional, disponíveis em [Git Downloads](https://git-scm.com/downloads).

## 3. Configure sua conta Git

Abra um terminal e configure seu nome de usuário e endereço de e-mail no Git. Substitua `<SeuNome>` e `<SeuEmail>` pelos seus próprios dados.

```bash
git config --global user.name "<SeuNome>"
git config --global user.email "<SeuEmail>"
```

## 4. Crie um Repositório Remoto no GitHub

No GitHub, crie um novo repositório clicando no botão "New" (Novo) em seu perfil. Dê um nome ao repositório, adicione uma descrição opcional e clique em "Create Repository" (Criar Repositório).

## 5. Crie e Conecte seu Repositório Local

### 5.1. Inicialize seu Repositório Local

No terminal, navegue até o diretório do seu projeto e execute:

```bash
git init
```

### 5.2. Adicione e Comite Seu Código

Adicione seus arquivos ao repositório local e faça o primeiro commit:

```bash
git add .
git commit -m "Primeiro commit"
```

### 5.3. Conecte seu Repositório Local ao Remoto

Copie o URL do seu repositório remoto no GitHub e adicione-o como origem para o repositório local:

```bash
git remote add origin <URL_do_Repositorio_Remoto>
```

### 5.4. Faça o Push do Código para o Repositório Remoto

Envie seus commits para o repositório remoto no GitHub:

```bash
git push -u origin master
```

Parabéns! Você agora tem seu código no GitHub e está pronto para colaborar ou compartilhar seu trabalho com outras pessoas.

Lembre-se de consultar a [documentação do Git](https://git-scm.com/doc) e a [documentação do GitHub](https://docs.github.com/) para aprender mais sobre as capacidades avançadas dessas poderosas ferramentas.
