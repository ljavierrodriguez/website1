# Documentacion con Markdown

### Comandos de Git 

1. Crear un repositorio de git

```shell
$ git init
```

2. Crear stage de los archivos 

```shell
$ git add -A
$ git add .
$ git add *
```

3. Guardar los archivos en el repositorio

```shell
$ git commit -m "mensaje"
```

4. Deshacer cambios en mi proyecto o archivo

```shell
$ git checkout <filename>
```

5. Ver el estado o status de nuestro repositorio

```shell
$ git status
````

6. Resetar el respositorio a un commit especifico

```shell
$ git reset --hard HEAD~5
```

7. Listar todas las ramas(branch)

```shell
$ git branch
```

8. Crear una nueva rama (branch)

```shell
$ git branch <name>
````

9. Activar una rama (branch)

```shell
$ git checkout <branch>
```

10. Traer cambios entre ramas (branch). Trae los cambios desde la rama especificada hacia la rama activa

```shell
$ git merge <branch>
```

