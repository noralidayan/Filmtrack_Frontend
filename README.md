# 🌐 FilmTrack Front-End

**FilmTrack Front-End** es la interfaz visual del proyecto **FilmTrack**, una aplicación web que permite gestionar y registrar películas y series favoritas.
Está desarrollada en **HTML, CSS y JavaScript puro**, y se conecta con un backend en **Java + Spring Boot** para ofrecer las funcionalidades dinámicas (registro, login, historial, favoritos, etc.).

---

## 🎯 Objetivo

Brindar una experiencia de usuario moderna, visual y adaptable, donde el usuario pueda:

* Registrarse e iniciar sesión
* Consultar, puntuar y guardar contenidos audiovisuales
* Visualizar su historial y lista de favoritos

---

## 🖥️ Tecnologías utilizadas

* **HTML5**
* **CSS3**
* **JavaScript (fetch API)**
* **Live Server / IntelliJ IDEA**
* **Integración con backend Spring Boot**

---

## 🚀 Visualización del proyecto

Podés explorar el **front-end publicado online** desde GitHub Pages:
👉 [https://noralidayan.github.io/Filmtrack_Frontend/](https://noralidayan.github.io/Filmtrack_Frontend/)

> 💬 Esta versión muestra el diseño y estructura de la aplicación, pero **no permite guardar datos ni autenticarse**.
> Para acceder a las funciones dinámicas, se debe ejecutar el backend en local.

---

## 🔗 Conexión con el backend

Para habilitar las funciones completas (registro, login, favoritos, historial, etc.), es necesario ejecutar el backend disponible en el siguiente repositorio:

👉 [https://github.com/noralidayan/Filmtrack](https://github.com/noralidayan/Filmtrack)

### Ejecución del backend:

1. Cloná el repositorio:

   ```bash
   git clone https://github.com/noralidayan/Filmtrack
   ```
2. Importá el script SQL (`filmtrack-spring.sql`) en tu servidor MySQL.
3. Configurá las credenciales en `application.properties`.
4. Iniciá el servidor con:

   ```bash
   mvn spring-boot:run
   ```
5. El backend estará disponible en:
   👉 [http://localhost:8080](http://localhost:8080)

---

## ⚙️ Ejecución local del front-end

Podés ejecutar el front de dos formas:

### 🩵 1. **Con Live Server (Visual Studio Code)**

Abrí `filmtrack.html` y ejecutá con Live Server.
La aplicación estará disponible en:

```
http://127.0.0.1:5500/filmtrack.html
```

### 💜 2. **Desde IntelliJ IDEA**

Abrí el archivo `filmtrack.html` y seleccioná “Open in Browser”.
Funciona igual si el backend ya está corriendo en el puerto 8080.


---

## ✨ Créditos

Desarrollado por **Norali Lucía Dayan**
📚 Proyecto académico y de práctica profesional – *Tecnicatura Superior en Análisis de Sistemas*
💻 GitHub: [noralidayan](https://github.com/noralidayan)
