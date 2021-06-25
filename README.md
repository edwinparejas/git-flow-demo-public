# git-flow-demo-public

## Comandos git flow

### Incializar git flow

```bash
# Inicialización simple
git flow init

# Inicialización con valores por defecto
git flow init -y

# Forzar reinicialización
git flow init -f
```

```bash
# Inicializar feature
$ git flow feature start <feature>

# Subir cambios (Primera vez)
$ git flow feature publish <feature>

# Subir cambios (Segunda vez a +)
$ git push

# Opcional: Obtener cambios
$ git pull

# Finalizar feature
$ git flow feature finish <feature>
$ git push

# Opcional: obtener últimos cambios si se desea crear un nuevo feature
$ git pull
```
