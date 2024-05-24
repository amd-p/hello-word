# DIO | Resumos Git e Github

## Aula 02: Salvando alterações no repositório local

Repositório para armazenar resumo da Aula 02: Salvando alterações no repositório local, do curso Versionamento de Código com Git e GitHub da plataforma [Digital Innovation One](https://web.dio.me/home).

## 📄 Resumo
**Alterações no repositório**
Após realizar as alterações necessárias em seu arquivo, vamos utilizar principalmente três comandos no Git para salvar essas alterações, são eles:

```
git add, git status e git commit
```
O comando _git commit_ captura um instantâneo das mudanças preparadas do projeto no momento. Os instantâneos com commit podem ser considerados versões "seguras" de um projeto, o Git nunca os altera, a menos que você peça a ele. 
Antes da execução de _git commit_, o comando _git add_ é usado para promover ou "preparar" alterações no projeto que são armazenadas em uma confirmação. 
Estes dois comandos, git commit e git add, estão entre os mais usados.

- **git add** 
Comando utilizado para salvar alterações na área de staging, isso significa que essas mudanças estão sinalizadas para serem salvas no próximo commit, ou seja, ainda não foram aplicadas.
```
git add nome-do-arquivo
```
Se, logo após, usarmos o comando _git status_, percebemos que o arquivo ainda não foi salvo e para salva-lo utilizaremos o comando a seguir.

- **git commit**
Comando responsável por salvar as alterações da área de staging para o diretório final.  Você pode adicionar uma mensagem ao seu commit. Veremos no exemplo a seguir:
```
git commit -m "mensagem"
```
Nos permite escrever uma mensagem entre as aspas, que será salva junto a alteração.

- **git status**
Exibe as condições do diretório de trabalho e da área de staging. Ele permite que você veja quais alterações foram despreparadas, quais não foram e quais arquivos não estão sendo monitorados pelo Git. Este comando pode ser utilizado a qualquer momento.
```
git status
```



## 🔍 Referências 
- [Digital Innovation One](https://web.dio.me/home)
- [Atlassian](https://www.atlassian.com/br)
- [Rocketseat](https://blog.rocketseat.com.br/como-fazer-um-bom-readme/)
- [Codecademy](https://www.codecademy.com/resources/docs/markdown)