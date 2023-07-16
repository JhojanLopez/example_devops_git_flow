# Instalacion
para poder usar git flow se recomienda instalar la extension:

```bash
sudo apt-get install git-flow
```

para comprobar instalacion y ver la version:
```bash
git-flow version
```

# Iniciar
para crear el repositorio git flow usamos:
```bash
 git flow init
```
nos preguntara sobre los nombres a establecer si queremos cambiarlo se debe digitar el nombre y oprimir enter de lo contrario solo
es oprimir enter. por defecto creara la rama master y la develop
![create-git-flow.png](assets%2Fcreate-git-flow.png)

ver ramas creadas
```bash
git branch -a
```

para crear ramas feature usamos:
```bash
 git flow feature start <id-feature>
```

para finalizar la rama feature y hacer merge en develop usamos:
```bash
 git flow feature finish <id-feature>
```
