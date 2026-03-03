# 🚀 CRUD con Go y MySQL

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

## 📌 Descripción

Este proyecto es una aplicación web que implementa las cuatro operaciones básicas de un sistema **CRUD** (Crear, Leer, Actualizar y Eliminar). Está desarrollado en el backend utilizando **Go (Golang)** y se conecta a una base de datos relacional **MySQL**.

Las vistas están construidas utilizando el paquete `html/template` de Go y estilizadas con **Bootstrap 4** para garantizar una interfaz limpia y responsiva. Este proyecto forma parte de mi portafolio profesional y demuestra la integración completa entre un servidor robusto, gestión de base de datos y renderizado de interfaces.

## ✨ Características

- **Crear:** Formulario para insertar nuevos registros en la base de datos.
- **Leer:** Tabla dinámica que lista todos los registros almacenados.
- **Actualizar:** Vista de edición para modificar datos existentes.
- **Eliminar:** Borrado seguro de registros desde la interfaz.
- **Arquitectura:** Separación clara entre la lógica de conexión, el enrutamiento y las plantillas web.

## 🛠️ Tecnologías Utilizadas

- **Backend:** Go (Golang)
- **Base de Datos:** MySQL (Ejecutado localmente con XAMPP)
- **Frontend:** HTML5, CSS3, Bootstrap 4.6
- **Librerías/Drivers:** `go-sql-driver/mysql`
- **Herramientas de BD:** DBeaver (Cliente SQL)

## ⚙️ Requisitos Previos

Asegúrate de tener instalado lo siguiente en tu entorno local:

- [Go](https://go.dev/dl/) (versión 1.18 o superior recomendada)
- [XAMPP](https://www.apachefriends.org/es/index.html) (Para inicializar el motor de MySQL)
- [DBeaver](https://dbeaver.io/) (Gestor visual de base de datos)
- Un editor de código (como Visual Studio Code)

## 🚀 Instalación y Uso

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/tu-usuario/nombre-del-repo.git](https://github.com/tu-usuario/nombre-del-repo.git)
   cd nombre-del-repo
   ```
2. **Configurar el entorno de Base de Datos:**

Abre XAMPP e inicia únicamente el servicio de MySQL.

Nota de configuración: Este proyecto está configurado para conectarse por el puerto 3308 para evitar conflictos con instalaciones previas. Asegúrate de configurar este puerto en tu archivo my.ini de XAMPP.

Abre DBeaver y crea una conexión a MySQL apuntando a localhost en el puerto 3308 (usuario root, sin contraseña).

Desde DBeaver, crea la base de datos sistema y ejecuta el script SQL del proyecto para generar la tabla empleados.

3. **Instalar dependencias:**

```
Bash
go mod init crud_go
go get -u [github.com/go-sql-driver/mysql](https://github.com/go-sql-driver/mysql)
```

4. Ejecutar la aplicación:

```
Bash
go run main.go
```

5. Abrir en el navegador:
   Visita http://localhost:8080 para interactuar con la aplicación.

👨‍💻 Autor
Johan Sebastian Vasquez Diaz Ingeniero de Sistemas / Front-end Developer
