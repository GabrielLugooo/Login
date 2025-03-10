<img align="center" src="https://media.licdn.com/dms/image/v2/D4D16AQGUNxQ7NSC05A/profile-displaybackgroundimage-shrink_350_1400/profile-displaybackgroundimage-shrink_350_1400/0/1738695150340?e=1744243200&v=beta&t=oXX-ixT9bR3dJcYCLv4KBs5wjKFoeP0524kFGHQMYmQ" alt="gabriellugo" />

# LOGIN

<a href="https://github.com/GabrielLugooo/Login/blob/main/README%20Spanish.md" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Login%20Español-000000" alt="Login Español" /></a>
<a href="https://github.com/GabrielLugooo/Login" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Login%20Inglés-green" alt="Login Inglés" /></a>

### Objetivos

Este proyecto tiene como objetivo desarrollar una interfaz gráfica de inicio de sesión utilizando la librería `customtkinter`. El diseño es minimalista y moderno, permitiendo a los usuarios ingresar un nombre de usuario y contraseña con una experiencia visual mejorada.

Además, este proyecto sirve como una introducción a la creación de interfaces gráficas en Python, permitiendo la exploración de `customtkinter` como alternativa a `tkinter`, con un enfoque en personalización y apariencia.

### Habilidades Aprendidas

- Creación de interfaces gráficas en Python.
- Uso de `customtkinter` para personalizar la apariencia.
- Manejo de widgets básicos como botones, etiquetas y campos de entrada.
- Organización de elementos con `CTkFrame`.
- Interacción con eventos mediante funciones asociadas a botones.

### Herramientas Usadas

![Static Badge](https://img.shields.io/badge/Python-000000?logo=python&logoSize=auto)

- Python.
- `customtkinter` (desarrollo de GUI) para la interfaz gráfica.

### Proyecto

#### Vista Previa

<img align="center" src="https://i.imgur.com/vksNgqS.jpeg" alt="Login01" />
<img align="center" src="https://i.imgur.com/D4w03G0.jpeg" alt="Login02" height="250" />

#### Código con Comentarios (Español)

```python
# Login

# Importar la librería necesaria para la interfaz gráfica
import customtkinter

# Configuración de la apariencia y tema de la aplicación
customtkinter.set_appearance_mode('dark')  # Modo oscuro
customtkinter.set_default_color_theme('blue')  # Tema azul

# Crear la ventana principal
root = customtkinter.CTk()
root.geometry('350x300')  # Definir tamaño de la ventana

def login():
    """
    Función que se ejecuta al presionar el botón de Login.
    Actualmente solo imprime un mensaje de bienvenida.
    """
    print('Bienvenido')

# Crear un frame dentro de la ventana principal
frame = customtkinter.CTkFrame(master=root)
frame.pack(pady=20, padx=60, fill='both', expand=True)

# Etiqueta con el título "User Login"
label = customtkinter.CTkLabel(master=frame, text='User Login')
label.pack(pady=12, padx=9)

# Campo de entrada para el nombre de usuario
entry1 = customtkinter.CTkEntry(master=frame, placeholder_text='Username')
entry1.pack(pady=12, padx=10)

# Campo de entrada para la contraseña con ocultación de caracteres
entry2 = customtkinter.CTkEntry(master=frame, placeholder_text='Password', show='*')
entry2.pack(pady=12, padx=10)

# Botón para iniciar sesión, vinculado a la función login
button = customtkinter.CTkButton(master=frame, text='Login', command=login)
button.pack(pady=12, padx=10)

# Ejecutar el bucle principal de la aplicación
root.mainloop()
```

### Limitaciones

El Login es solo para fines educativos bajo la licencia MIT.
También esta disponible el código de la versión mínimal.

---

<h3 align="left">Conecta Conmigo</h3>

<p align="left">
<a href="https://www.youtube.com/@gabriellugooo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.icons8.com/?size=50&id=55200&format=png" alt="@gabriellugooo" height="40" width="40" /></a>
<a href="http://www.tiktok.com/@gabriellugooo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.icons8.com/?size=50&id=118638&format=png" alt="@gabriellugooo" height="40" width="40" /></a>
<a href="https://instagram.com/lugooogabriel" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.icons8.com/?size=50&id=32309&format=png" alt="lugooogabriel" height="40" width="40" /></a>
<a href="https://twitter.com/gabriellugo__" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.icons8.com/?size=50&id=phOKFKYpe00C&format=png" alt="gabriellugo__" height="40" width="40" /></a>
<a href="https://www.linkedin.com/in/hernando-gabriel-lugo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.icons8.com/?size=50&id=8808&format=png" alt="hernando-gabriel-lugo" height="40" width="40" /></a>
<a href="https://github.com/GabrielLugooo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.icons8.com/?size=80&id=AngkmzgE6d3E&format=png" alt="gabriellugooo" height="34" width="34" /></a>
<a href="mailto:lugohernandogabriel@gmail.com"> <img align="center" src="https://img.icons8.com/?size=50&id=38036&format=png" alt="lugohernandogabriel@gmail.com" height="40" width="40" /></a>
<a href="https://linktr.ee/gabriellugooo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://simpleicons.org/icons/linktree.svg" alt="gabriellugooo" height="40" width="40" /></a>
</p>

<p align="left">
<a href="https://github.com/GabrielLugooo/GabrielLugooo/blob/main/Readme%20Spanish.md" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Versión%20Español-000000" alt="Versión Español" /></a>
<a href="https://github.com/GabrielLugooo/GabrielLugooo/blob/main/README.md" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Versión%20Inglés-Green" alt="Versión Inglés" /></a>

</p>

<a href="https://linktr.ee/gabriellugooo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Créditos-Gabriel%20Lugo-green" alt="Créditos" /></a>
<img align="center" src="https://komarev.com/ghpvc/?username=GabrielLugoo&label=Vistas%20del%20Perfil&color=green&base=2000" alt="GabrielLugooo" />
<a href="" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/License-MIT-green" alt="MIT License" /></a>
