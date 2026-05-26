# TiendaVirtual_GrupoX
# 1. Configurar nombre y correo (solo una vez en el computador)

git config --global user.name "Maria Camila Becerra Santisteban"
git config --global user.email "camilabs1909@gmail.com"

# 2. Crear carpeta del proyecto

mkdir TiendaVirtual_GrupoX
cd TiendaVirtual_GrupoX


# 3. Inicializar repositorio Git

git init


# 4. Crear archivo README.md

echo "# Tienda Virtual - Proyecto POO" > README.md
echo "Integrantes: Nombre1, Nombre2" >> README.md


# 5. Agregar archivo y hacer primer commit

git add README.md
git commit -m "Primer commit: creación del README"


# 6. Conectar con GitHub
# (REEMPLAZA 'tu-usuario' por tu usuario real de GitHub)

git remote add origin https://github.com/tu-usuario/TiendaVirtual_GrupoX.git


# 7. Cambiar nombre de rama principal a main

git branch -M main


# 8. Subir proyecto a GitHub

git push -u origin main
