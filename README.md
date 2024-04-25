
# DIO | Passos iniciais com Git e GitHub

Repositório para armazenar resumos sobre Git e GitHub do curdo de versionamento de código da [Digital Innovation One](https://www.dio.me/).

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com)

# 📓 Resumos das aulas

| Aulas | Resumos |
|-------|-------- |
|Criando e clonando repositórios|[Resumo]()|
|Sanvando alterações no Repositório Local|[Resumo]()|
|Desfazendo alterações no Repositório Local|[Resumo]()|
|Enviando e baixando alterações com o repositório remoto|[Resumo]()|
|Trabalhando com branches: Criando, mesclando, deletando e tratando conflitos|[Resumo]()|
|Trabalhando com branches: Comandos úteis no dia a dia|[Resumo]()|


### Comandos do git
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


## Referências
- [Digital Innovation One](https://www.dio.me)