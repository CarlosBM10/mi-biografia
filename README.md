# Mi Biografía

**Nombre completo:** Carlos
**Edad:** 21
**Carrera:** Ingeniera Informática


## Hobbies
- Leer
- Escuchar música
- Jugar videojuegos

## Contacto
- Email: carloscrmora@gmail.com



mkdir ~/mi-biografia
cd ~/mi-biografia


git init


echo "# Mi Biografía

**Nombre completo:** Carlos
**Edad:** 21
**Carrera:** Ingeniera Informática
" > README.md


git add README.md
git commit -m "Agregar biografía personal"


git branch -M main

git remote set-url origin https://github.com/CarlosBM10/mi-biografia.git

git push -u origin main



git checkout -b agregar-hobbies


echo -e "\n## Hobbies\n- Leer\n- Escuchar música\n- Jugar videojuegos" >> README.md


git add README.md
git commit -m "Agregar sección de hobbies"
git push origin agregar-hobbies



git checkout -b agregar-contacto

echo -e "\n## Contacto\n- Email: carloscrmora@gmail.com" >> README.md


git add README.md
git commit -m "Agregar sección de contacto"
git push origin agregar-contacto
