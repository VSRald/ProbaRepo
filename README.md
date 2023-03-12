#Práctica Git

## Prácticas Git

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
git clone url
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

```bash
git reset [--soft|--mixed|--hard] HEAD~
```
>O comando reset serve para desfacer commits. No caso de poñer --soft solo de desfará o comit, pero a fase staged e o directorio de traballo manterán os cambios antes do commit. No caso de --mixed desfará o commit e os cambios dos ficheiros so estarán no directorio de traballo. No caso de --hard desfaranse todos os cambios no commit, no staged e no directorio de traballo. Nesta liña de comando está posto que o reset volva á versión anterior á que apunta o HEAD, pero no lugar de HEAD~ podemos poñer o código do commit ao que queremos volver.

```bash
git checkout arquivo
git restore arquivo
```
>Estes comandos desfan os cambios que se fixeron nos arquivos que lle indiquemos.

```bash
git clean -f
```
>O comando clean co parametro -f borra os arquivos que non estaban no commit da vesión na que estamos trabalando nese momento.

### Pasos a seguir na práctica 1.

1. Crear unha carpeta e abrila no terminal.
2. Inicializar repositorio local co comando 'git init'.
3. Crear os ficheiros.
4. Engadir os ficheiros co comando'git add .'.
5. Facer un commit para gardar os cambios nunha nova versión do repositorio.
6. Creamos un repositorio en GitHub.
7. A continuación vinculamos o repositorio local co remoto co comando 'git remote add origin url'.
8. Para rematar facemos un 'git push origin main' para subir ao reposotorio remoto os commits do repositorio local

### Pasos a seguir na práctica 2.

1. Creamos unha nova carpeta no ordenador, e nesa carpeta co comando ' git clone url' facemos unha copia do repositorio remoto.
2. Facemos os cambios que queremos facer nos arquivos, e cando queiramos subilos ao repositorio remoto facemos un ' git push origin main'.
