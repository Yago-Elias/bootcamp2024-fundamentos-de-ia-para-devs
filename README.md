
# DIO | Passos iniciais com Git e GitHub

Repositório para armazenar resumos sobre Git e GitHub do curdo de versionamento de código da [Digital Innovation One](https://www.dio.me/).

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com)

# 📓 Resumos das aulas

| Aulas | Resumos |
|-------|-------- |
|Criando e clonando repositórios|[`Aula 1`](#aula-1)|
|Sanvando alterações no Repositório Local|[`Aula 2`](#aula-2)|
|Desfazendo alterações no Repositório Local|[`Aula 3`](#aula-3)|
|Enviando e baixando alterações com o repositório remoto|[`Aula 4`](#aula-4)|
|Trabalhando com branches: Criando, mesclando, deletando e tratando conflitos|[`Aula 5`](#aula-5)|
|Trabalhando com branches: Comandos úteis no dia a dia|[`Aula 6`](#aula-6)|


## Comandos do git

### Aula 1
Definindo o diretório atual para ser versionado.
```
$ git init
```
Clonando um repositório remote no diretório local.
```
$ git clone url
```
Faz o mesmo processo que o comando anterior com o adicional de criar o repositório local com o nome de `nome-do-diretório`.
```
$ git clone url nome-do-diretorio
```
Clonando uma branch específica.
```
$ git clone --branch nome-da-branch --single-branch
```
Mostra a url do repositório remoto.
```
$ git remote -v
```
Adiciona uma url do repositório remoto na configuração do repositório local.
```
$ git remote add origin url
```

### Aula 2
Mostra o estado dos arquivos do repositório local.
```
$ git status
```
Adiciona o(s) arquivo(s) `nome-do-arquivo` para fazer o commit.
```
$ git add nome-do-arquivo
```
Salva o estado do(s) arquivo(s) e adiciona um comentário com a opção `-m`.
```
$ git commit -m"cometario"
```

### Aula 3
Descarta todas as alterações realizadas no `arquivo`.
```
$ git restore arquivo
```
Mostra o histórico de commits
```
$ git log
```
Abri um editor de texto para alterer o comentário do último commit.
```
$ git commit --amend
```
Retorna o estado do último commit para a área de preparação.
```
$ git reset --soft hash
```
Retorna o estado do último commit para a área de trabalho, esse comando é o mesmo que fazer `git reset hash`.
```
$ git reset --mixed hash
```
Retorna para o commit especificando por meio do hash, e desfazendo qualquer alteração após ao commit especificado.
```
$ git reset --hard hash
```
Mostra todas as alterações realizadas
```
$ git reflog
```
Remove o `arquivo` da área de preparação.
```
$ git restore --staged arquivo
```

### Aula 4
Baixa as alterações do repositório remoto para o repositório local.
```
$ git pull
```
Envia as alterações do repositório local para o repositório remoto. O argumento `-u` é uma abreviação de `--set-upstream` que diz pro git para configurar a branch `main` com o repositório remoto `origin`.
```
$ git push -u origin main
```

## Referências
- [Digital Innovation One](https://www.dio.me)