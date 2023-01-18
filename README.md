#Práctica Git

## Práctica 1: Creación e conexión git

### Comandos empregados

``` bash
git init
```
>Sirve para inicializar un repo local.

```bash
git add 'ficheiros a engadir'
```
>Sirve para engadir os arquivos gardados á fase staged, se poñemos '.' engádense todos os ficheiros do repositorio.

```bash
git config --user.name "nome usuario"
git config --user.email "email usuario"
git config --list
```
>Estes comandos config serven para modifiacar a configuración de git, estes dous cambian o nome de usuario e o email.
>O terceiro comando non modifica a configuración, mostraa por pantalla.

```bash
git status
```
>Status mostra o estado do repositorio.

```bash
git commit -m "mensaxe"
```
>Este comando efectua un commit creando unha nova versión do proxecto. -m serve para engadir unha mensaxe á nova versión,
>utilizase normalmente para comentar os cambios que se fixeron na nova versión.

```bash
git diff
```
>Este comando mostra os cambios que hai nos arquivos con respecto ao último commit.

```bash
git show
```
>Este comando mostra os cambios efectuados entre os dous últimos commit.

```bash
git log
```
>Mostra todos os commit efectuados.

```bash
git clone "url"
```
>Este comando serve para descargar un repositorio da rede.

```bash
git push
```
>Este comando envía todos os cambios que fixemos no repositorio local ao repositorio remoto.

```bash
git pull
```
>Este comando permitenos sincronizar o repositorio local co remoto baixando os cambios do remoto.

### Pasos a seguir na práctica

1. Inicializar repositorio local co comando 'git init'.
2. Crear os ficheiros.
3. Engadir os ficheiros co comando'git add .'.
4. Facer un commit para gardar os cambios nunha nova versión do repositorio.
5. 
