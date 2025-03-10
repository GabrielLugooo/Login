<img align="center" src="https://media.licdn.com/dms/image/v2/D4D16AQGUNxQ7NSC05A/profile-displaybackgroundimage-shrink_350_1400/profile-displaybackgroundimage-shrink_350_1400/0/1738695150340?e=1744243200&v=beta&t=oXX-ixT9bR3dJcYCLv4KBs5wjKFoeP0524kFGHQMYmQ" alt="gabriellugo" />

# LOGIN

<a href="https://github.com/GabrielLugooo/Login" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/English%20Login-000000" alt="English Login" /></a>
<a href="https://github.com/GabrielLugooo/Login/blob/main/README%20Spanish.md" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Spanish%20Login-green" alt="Spanish Login" /></a>

### Objective

This project aims to develop a graphical login interface using the `customtkinter` library. The design is minimalist and modern, allowing users to enter a username and password with an enhanced visual experience.

Additionally, this project serves as an introduction to creating graphical interfaces in Python, allowing the exploration of `customtkinter` as an alternative to `tkinter`, with a focus on customization and appearance.

### Skills Learned

- Creating graphical interfaces in Python.
- Using `customtkinter` to customize the appearance.
- Handling basic widgets such as buttons, labels, and entry fields.
- Organizing elements with `CTkFrame`.
- Interacting with events through functions linked to buttons.

### Tools Used

![Static Badge](https://img.shields.io/badge/Python-000000?logo=python&logoSize=auto)

- Python.
- `customtkinter` (GUI development) for the graphical interface.

### Project

#### Preview

<img align="center" src="https://i.imgur.com/vksNgqS.jpeg" alt="Login01" />
<img align="center" src="https://i.imgur.com/D4w03G0.jpeg" alt="Login02" height="250" />

#### Code with Comments (English)

```python
# Login

# Import the library needed for the graphical interface
import customtkinter

# Setting the appearance and theme of the application
customtkinter.set_appearance_mode('dark') # Dark mode
customtkinter.set_default_color_theme('blue') # Blue theme

# Create the main window
root = customtkinter.CTk()
root.geometry('350x300') # Set the window size

def login():
    """
    Function that is executed when the Login button is pressed.
    Currently it only prints a welcome message.
    """
    print('Welcome')

# Create a frame inside the main window
frame = customtkinter.CTkFrame(master=root)
frame.pack(pady=20, padx=60, fill='both', expand=True)

# Label with the title "User Login"
label = customtkinter.CTkLabel(master=frame, text='User Login')
label.pack(pady=12, padx=9)

# Input field for username
entry1 = customtkinter.CTkEntry(master=frame, placeholder_text='Username')
entry1.pack(pady=12, padx=10)

# Input field for password with hidden characters
entry2 = customtkinter.CTkEntry(master=frame, placeholder_text='Password', show='*')
entry2.pack(pady=12, padx=10)

# Button to log in, linked to the login function
button = customtkinter.CTkButton(master=frame, text='Login', command=login)
button.pack(pady=12, padx=10)

# Run the main loop of the application
root.mainloop()
```

### Limitations

Login it's just for educational purpose under the MIT License.
The code for the minimal version is also available.

---

<h3 align="left">Connect with me</h3>

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
<a href="https://github.com/GabrielLugooo/GabrielLugooo/blob/main/README.md" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/English%20Version-000000" alt="English Version" /></a>
<a href="https://github.com/GabrielLugooo/GabrielLugooo/blob/main/Readme%20Spanish.md" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Spanish%20Version-Green" alt="Spanish Version" /></a>
</p>

<a href="https://linktr.ee/gabriellugooo" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/Credits-Gabriel%20Lugo-green" alt="Credits" /></a>
<img align="center" src="https://komarev.com/ghpvc/?username=GabrielLugoo&label=Profile%20views&color=green&base=2000" alt="GabrielLugooo" />
<a href="" target="_blank" rel="noreferrer noopener"> <img align="center" src="https://img.shields.io/badge/License-MIT-green" alt="MIT License" /></a>
