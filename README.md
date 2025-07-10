# administracion-de-estudiantes

Este proyecto es una **Single Page Application (SPA)** desarrollada con tecnologías básicas del frontend, que simula un panel de administración de usuarios con operaciones CRUD completas, navegación entre secciones y diseño responsivo.

---

## 🚀 Tecnologías Utilizadas

- HTML5
- CSS3 (con Flexbox y Grid)
- JavaScript (ES6+)
- [json-server](https://www.npmjs.com/package/json-server) (para simular una API REST)

---

## 📂 Estructura del Proyecto

📁 admin-panel/
├── index.html
├── styles.css
├── app.js
├── db.json
├── assets/
│ └── perfil.jpeg
└── README.md


---

## 🧑‍💻 Funcionalidades

- ✅ Crear, leer, actualizar y eliminar usuarios.
- ✅ Validación de formularios.
- ✅ Navegación SPA entre secciones: Home, Course, Users, Payment, Report, About Me, Contacto, Settings.
- ✅ Modal para crear/editar usuarios.
- ✅ Estilo responsivo para móviles y escritorio.
- ✅ Simulación de login y logout usando `localStorage`.

---

## 🧪 Datos de Usuario

```json

#
{
  "id": 1,
  "name": "Nombre Completo",
  "email": "correo@ejemplo.com",
  "phone": "1234567890",
  "enrollNumber": "12345678901234",
  "dateOfAdmission": "2025-07-10"
}

🛠️ Instalación y Uso
1. Clona el repositorio

git clone https://github.com/tuusuario/admin-usuarios-spa.git
cd admin-usuarios-spa

2. Instala json-server

Si no lo tienes aún, instálalo globalmente:

npm install -g json-server

3. Inicia el servidor

json-server --watch db.json --port 3000

Esto abrirá la API simulada en:
👉 http://localhost:3000/usuarios
4. Abre el proyecto en tu navegador

Solo abre index.html con tu navegador favorito (no necesitas servidor web).
📸 Capturas
Login	Panel CRUD	Secciones SPA
	
	
📌 Notas Importantes

    No se usaron frameworks o librerías externas.

    El proyecto es totalmente educativo y apto para principiantes.

    Puedes extenderlo agregando validaciones avanzadas, autenticación real, o conexión con una API real.

🧠 Autor

David Dev– Desarrollador Junior en formación


Este proyecto es de uso libre para fines educativos.
¡Cualquier mejora es bienvenida!


---

### ✅ Siguiente paso:
1. Guarda este archivo como `README.md` en la raíz de tu proyecto.
2. Súbelo a tu repositorio en GitHub.
3. Comparte tu proyecto con orgullo 💼🌟

¿Quieres que te ayude también con el `.gitignore` o con los comandos para subir a GitHub desde cero?

