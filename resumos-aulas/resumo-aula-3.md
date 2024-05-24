
# DIO | Resumos Git e Github

## Aula 03: Desfazendo alterações no repositório local

Repositório para armazenar resumo da Aula 03: Desfazendo alterações no repositório local, do curso Versionamento de Código com Git e GitHub da plataforma [Digital Innovation One](https://web.dio.me/home).

## 📄 Resumo
**Desfazendo alterações**
Caso tenha realizado alguma alteração errônea em seu projeto, podemos utilizar alguns comandos para desfaze-lo, são eles:

- **rm -rf .git**
Comando utilizado para desfazer o versionamento de uma pasta, ocorre quando utilizamos _git init_ na pasta incorreta.

- **git restore** 
Trata da restauração dos arquivos na árvore de trabalho do índice ou de outro commit. Restaura para ultima versão commitada.
```
git restore
```

- **git commit --amend -m ""**
Comando responsável por alterar mensagem do commit. Não altera o conteúdo.  A mensagem deve ser inserida entre as aspas. Exemplo:
```
git commit --amend -m "nova-mensagem"
```

- **git reset**
Comando responsável por desfazer alterações no conteúdo de um commit. Utilizamos adjunto de outro comando, temos três:

**soft:**
```
git reset --soft hash-do-commit
```
Faz o repositório apontar para o commit especificado e reverte o(s) arquivo(s) modificado(s) para staged. Ou seja, se executarmos o comando _git commit_ após executar o comando _git reset --soft_, nós teremos um novo commit com as mesmas mudanças do commit revertido.

**mixed:**
```
git reset --mixed hash-do-commit
```
Faz o repositório apontar para o commit especificado assim como o comando __git reset --soft_, porém reverte o(s) arquivo(s) modificado(s) para unstaged. Ou seja, se executarmos o comando _git commit_ após executar o comando _git reset --mixed_, não irá funcionar.

**hard**
```
git reset --hard hash-do-commit
```
O comando _git reset --hard_ faz o repositório apontar para o commit especificado assim como os demais comandos _git reset_, porém descarta todos os arquivos staged bem como os arquivos unstaged.


## 🔍 Referências 
- [Digital Innovation One](https://web.dio.me/home)
- [Atlassian](https://www.atlassian.com/br)
- [Rocketseat](https://blog.rocketseat.com.br/como-fazer-um-bom-readme/)
- [Codecademy](https://www.codecademy.com/resources/docs/markdown)