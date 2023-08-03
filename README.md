Para agregar imagenes en un proyecto Django
1. Instalar pillow (pip install pillow)
2. Setting.py creamos MEDIA_URL y MEDIA_ROOT
3. urls.py (del Proyecto) creamos la entrada en urlspatterns
4. Models.py creamos el modelo del Avatar (FK User)
5. Forms.py creamos el formulario del Avatar
6. agregarAvatar.html 
7. Views.py crear la funcion 
8. urls.py (de la App) creamos la entrada de ruta agregar_avatar
9. python manage.py makemigrations
10. python manage.py migrate
11. Opcional (agregar al admin.py el modelo Avatar)
12. Modificar base.html mostrando el avatar