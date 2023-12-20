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

----------------------------Fim do Guia Iniciante-----------------------------

#Guia Intermediário para Uso do GitHub e Git
Parabéns por continuar sua jornada no mundo do Git e GitHub! Nesta etapa, você aprenderá a interagir ainda mais com repositórios, realizar alterações, visualizar o histórico e colaborar com outras pessoas.

Novos Conhecimentos Adquiridos

## 6. Baixar um Repositório com git clone
Clone um repositório do GitHub para o seu computador:

bash
Copy code
git clone <URL_do_Repositorio_Remoto>

## 7. Realizar Alterações e Registrar Commits
Faça alterações em seus arquivos e registre essas mudanças com commits:

bash
Copy code
git add .
git commit -m "Descrição concisa da alteração"

## 8. Visualizar Modificações Locais
Veja quais arquivos foram modificados no repositório local:

bash
Copy code
git status

## 9. Listar Commits com git log
Obtenha uma lista de commits com detalhes do autor, data e mensagem:

bash
Copy code
git log

## 10. Visualizar Repositórios Remotos com git remote
Veja os repositórios remotos vinculados ao seu repositório local:

bash
Copy code
git remote -v

## 11. Enviar Commits para o Repositório Remoto
Envie seus commits para o repositório remoto no GitHub:

bash
Copy code
git push origin master

## 12. Baixar Commits do Repositório Remoto
Baixe commits do repositório remoto para o repositório local:

bash
Copy code
git pull origin master

## 13. Adicionar Colaboradores no GitHub
No GitHub, vá para as configurações do seu repositório, clique em "Manage access" (Gerenciar acesso), e adicione colaboradores pelo nome de usuário ou endereço de e-mail.

## 14. Aceitar Convites de Colaboração
Se você foi convidado como colaborador, aceite o convite na seção de convites do seu perfil no GitHub.

Lembre-se, esses são passos básicos, e há muito mais para aprender. Consulte a documentação oficial do Git e documentação do GitHub para aprofundar seu conhecimento.

Continue explorando e praticando para se tornar cada vez mais proficiente no uso do Git e GitHub. Boas colaborações!
