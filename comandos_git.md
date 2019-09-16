### Configurando identidad 
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com

### Comprobando tu configuración
git config --list

### Clonar repositorio 
git clone git://github.com/schacon/grit.git

### Verificar estado del repositorio
git status

### Agregando archivos
git add [file] (agrega solo un archivo)
O 
git add .  (agrega todos los cambios en el repo)

### Confirmar cambios
git commit -m 'initial commit'

### Estado del repositorio
git log

### Ignorando archivos
.gitignore

### Repositorios Remotos
git clone git://github.com/schacon/ticgit.git
git remote -v

### Añadiendo repositorios remotos
git remote add pb git://github.com/paulboone/ticgit.git

### Verficar repositorios remotos
git remote -v

### Enviando cambios a Github
git push -u origin rama

### Actualizando repositorio local
git pull origin [branch]
git merge [remote]/[branch]

### Crear una rama
git checkout -b testing
