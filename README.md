Este repositorio contiene todos los archivos necesarios para poner en funcionamiento
nuestro blog en "http://blog.enjambrelab.com.ar".

Para repetir el deploy o actualizar ghost, deberías añadir dokku como
destino para git:

```
git remote add dokku dokku@enjambrelab.com.ar:blog
git push dokku master
```


