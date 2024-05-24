
# DIO | Resumos Git e Github

## Aula 01: Criando e clonando repositórios

Repositório para armazenar resumo da Aula 01: Criando e clonando repositórios, do curso Versionamento de Código com Git e GitHub da plataforma [Digital Innovation One](https://web.dio.me/home).

## 📄 Resumo
**Criando repositórios**
Existem duas formas de obter um repositório Git na sua máquina:

- **Transformar um repositório local em Git** 

Abra o Git Bash e localize a pasta que deseja transformar. Utilizaremos então o comando _"mkdir"_ (make directory) e o nome que gostaríamos de colocar na pasta:
```
mkdir nome-da-pasta
```
Esse comando criará um diretório na pasta em questão. Para acessá-lo utilize o comando _"cd"_ + nome-da-pasta.
```
cd nome-da-pasta
```
Após acessar a pasta vamos utilizar outro comando para transformá-la em Git:
```
git init
```
Esse é um comando único que você usa durante a configuração inicial de um novo repositório. A execução desse comando cria um novo subdiretório _.git_ no diretório de trabalho atual. Essa ação também vai criar uma ramificação principal.

- **Clonar um repositório existente**
>>Para clonar um repositório copiaremos a url dele + o comando _"git clone"_:
```
git clone url-do-repositório-github.com
```
Também é possível utilizar esse mesmo comando + nome-da-pasta, assim não é obrigatório estar com a pasta aberta no Git Bash, e o repositório local não fica com o mesmo nome do remoto.
```
git clone url-do-repositório-github.com nome-da-pasta
```
Caso queira, é possível clonar uma branch específica, utilizando o mesmo comando + nome-da-branch + _"--single-branch"_, exemplo:
```
git clone url-do-repositório-github.com --branch feature-1 --single branch
```
Lembrando que se a branch não for especificada dessa forma, automaticamente o Git clona a _main_ ou _master_ branch, ou seja a branch principal.

```
git remote add origin url-do-repositório-github.com
```
Esse comando é utilizado para conectar um repositório local com um repositório remoto, na próxima aula veremos como salvar alterações de um para o outro.


## 🔍 Referências 
- [Digital Innovation One](https://web.dio.me/home)
- [Atlassian](https://www.atlassian.com/br)
- [Rocketseat](https://blog.rocketseat.com.br/como-fazer-um-bom-readme/)
- [Codecademy](https://www.codecademy.com/resources/docs/markdown)