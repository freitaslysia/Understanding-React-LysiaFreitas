## Understanding React - Lysia Freitas

### O que é Git?

Git é um sistema de controle de versão, que permite que você acompanhe e gerencie as mudanças feitas em arquivos ao longo do tempo. Ele é usado para colaboração, rastreamento de histórico e garantia de que várias pessoas possam trabalhar em um projeto sem conflitos.

### O que é GitHub?

O GitHub é uma plataforma online que você cria e "guarda" os seus repositórios, podendo hospedar os projetos, colaborador com open-sources, seguir outros programadores e interagir com código de terceiros.

---

---

## Okay, mas qual é o próximo passo?

### Utilizando o Git

<strong>Passo 1: Instalação do Git</strong>

<ul>
<li> Baixe e instale o Git no seu computador. Entre no link do site oficial do Git <a>https://git-scm.com/</a> e siga as instruções para sua plataforma.
</li></ul>

<strong>Passo 2: Configuração Inicial</strong>

<ul>
<li> Abra o terminal (no Windows, você pode usar o Git Bash ou cmd) e configure seu nome e email usando os seguintes comandos:</li></ul>

```
git config --global user.name "Seu nome aqui"
git config --global user.email "seuemail@exemplo.com"
```

<strong>Passo 3: Iniciando um Repositório</strong>

<ul>
<li> Navegue para a pasta do seu projeto no terminal.
<li> Execute o comando:

```
git init
```

Isso vai tornar a sua pasta em um repositório Git.

</ul>

<strong>Passo 4: Adicionando e Registrando Alterações</strong>

<ul>
<li> Crie ou modifique arquivos no seu projeto;
<li> Use o comando para verificar o status dos arquivos:

```
git status
```

<li> Adicione as mudanças para prepará-las para o commit:

```
git add . (ou git add arquivo)
```

<li> Faça o Commit das alterações com uma mensagem de texto explicativo:

```
git commit -m "Mensagem curta de alteração"
```

</ul>

---

---

### Utilizando o GitHub

<strong>Passo 5: Criando um Repositório no GitHub</strong>

<ul>
<li> Acesse o GitHub <a>https://github.com/</a> e faça login ou crie uma conta.
<li> Clique no botão "+", no canto superior direito, e escolha "New Repository".
<li> Dê um nome ao repositório, adicione uma descrição e escolha as configurações desejadas.
<li> Clique em "Create repository".
</ul>

<strong>Passo 6: Conectando Repositório Local ao GitHub</strong>

<ul>
<li> No seu repositório local (passo 3), copie o URL do repositório no GitHub.
<li> No terminal, adicione o link remoto ao seu repositório local:</ul>

```
git remote add origin URL-do-repositório
```

<strong>Passo 7: Enviando os Arquivos para o GitHub</strong>

<ul>
<li>Faça commits locais conforme o "Passo 4".
<li>Use o comando para enviar as alterações para o GitHub:

```
git push origin nome-da-branch
```

</ul>

<strong>Passo 8: Colaborando no GitHub</strong>

<ul>
<li>Convite colaboradores para o repositório no GitHub.
<li>Eles podem clonar o repositório para seus computadores, fazer mudanças e enviar pull requests.
<li>Você pode revisar as mudanças e, se estiverem boas, mesclá-las ao seu repositório.
