# myTest

### Pasos a seguir para Pushear nuestro primer repo

```
Inicializamos un repo local
> git init

Chequeamos si hay cosas para agregar (obvio que si)
> git status

Agregamos los archivos que deseemos
> git add .  

Cambiamos a el branch main (por defecto me aparece en master)
> git checkout -b main     

Agregamos como origen un repo en GitHub (preferentemente vacio y sin README.md)
> git remote add origin <url del repo>

Hacemos un commit
> git commit -m "mensaje a agregar"

Pusheamos al repo remoto
> git push -f -u origin main

Para hacer un pull request
> git pull 'remote_name' 'branch_name'.

```

