# Primeros cambios git rebase
Vamos a hacer un par de commits para que haya algo en el main

```bash
git add README.md
git commit -m "XXXX"
```

Este cambio va a ser algo en lo que vamos a ir trabajando
```bash
echo primera linea
echo segunda linea
```

Esta funcion es parte de la rama feature


Soy el Colaborador Saul y voy a hacer commits en el feature
```bash
echo mi parte
```

SAUL : Como colaborador voy a hacer un segundo COMMIT

```bash
git add README.md
git commit -m "MEUDEUUUS"
```


## Hacer el rebase
para traer los cambios que he hecho en main a la feature se hace un rebase
para ello
```bash
git checkout feature
git rebase main
```
despues seria corregir los errores, hacer un commit y ya estaria