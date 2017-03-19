# dockerapp
Esta aplicacion se hace para acceder por autenticacion ssh desde el potatil a github, con esto se evita que pida siempre credenciales una y otra vez, esto con el fin de crear un sistema continuos integration con circleCI.  El cual permite un sistema continuo de testing cuando se esta en produccion y se verifica errores antes de montar a produccion y da notificaciones para evitar problemas, ademas actualiza instantaneamente


1. se instala ssh con el comando 
```
sudo apt-get install ssh
```

2. se verifica si se tiene una ssh 

https://help.github.com/articles/checking-for-existing-ssh-keys/

3. se añade un ssh nuevo, se siguen las instrucciones de :

https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/

4. se añande el ssh nuevo a github, donde dice copiar ssh se copia el archivo .pub que es la clave publica


https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/
