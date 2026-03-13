
# Aula de Git e GitHub

Este repositório será utilizado nas aulas de **Versionamento de Código** para praticarmos o uso do **Git** e do **GitHub**.

O objetivo da atividade é aprender o fluxo básico utilizado por desenvolvedores para registrar e compartilhar alterações em projetos.

---

# Estrutura do repositório
```
Versionamento
│
├── alunos
│   └── .gitkeep
│
└── README.md
```
Cada aluno deverá criar **uma pasta com seu nome** dentro da pasta `alunos`.

Exemplo:
```
alunos
├── ana
├── bruno
├── larissa
└── nicolly
```
---

# Atividade

Cada aluno deverá:

1. Clonar o repositório
2. Criar uma pasta com seu nome dentro de `alunos`
3. Criar um arquivo `README.md` dentro da sua pasta
4. Fazer commit das alterações
5. Enviar as alterações para o GitHub

---

# Passo a passo

## 1. Clonar o repositório

git clone URL_DO_REPOSITORIO

---

## 2. Entrar na pasta do projeto

cd Versionamento

---

## 3. Criar sua pasta

Exemplo:

mkdir alunos/larissa

---

## 4. Criar um README dentro da pasta

Exemplo:

alunos/larissa/README.md

Conteúdo sugerido:

Nome: Larissa  
Turma: ___  

Objetivo no curso:  
Aprender desenvolvimento de software e versionamento de código.

---

## 5. Registrar alterações

git add .  
git commit -m "Adiciona pasta do aluno"

---

## 6. PASSO IMPORTANTE – Atualizar o repositório antes de enviar

Antes de enviar suas alterações, execute sempre:

git pull origin main

Isso evita erros comuns como:

- rejected
- fetch first
- conflitos de histórico

---

## 7. Enviar alterações para o GitHub

git push origin main

---

# Fluxo básico do Git

O fluxo utilizado pelos desenvolvedores geralmente segue esta sequência:

1. editar arquivos  
2. git add  
3. git commit  
4. git pull  
5. git push  

---

# Regras da atividade

- Cada aluno deve trabalhar **apenas na sua pasta**.
- Não alterar arquivos de outros colegas.
- Sempre executar **git pull antes do git push**.

---

# Próximas aulas

Nas próximas aulas aprenderemos:

- Branches
- Pull Requests
- Trabalho colaborativo em equipe
