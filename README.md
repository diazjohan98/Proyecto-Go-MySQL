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
- **Base de Datos:** MySQL
- **Frontend:** HTML5, CSS3, Bootstrap 4.6
- **Librerías/Drivers:** `go-sql-driver/mysql`

## ⚙️ Requisitos Previos

Asegúrate de tener instalado lo siguiente en tu entorno local:

- [Go](https://go.dev/dl/) (versión 1.18 o superior recomendada)
- [MySQL Server](https://dev.mysql.com/downloads/)
- Un editor de código (como Visual Studio Code)

## 🚀 Instalación y Uso

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/tu-usuario/nombre-del-repo.git](https://github.com/tu-usuario/nombre-del-repo.git)
   cd nombre-del-repo
   ```
2. **Configurar la base de datos:**
   Ejecuta el script SQL incluido en el proyecto (o crea una base de datos llamada crud_go y configura la tabla correspondiente).

3. **Instalar dependencias:**

```Bash
go mod init crud_go
go get -u [github.com/go-sql-driver/mysql](https://github.com/go-sql-driver/mysql)
```

4. **Ejecutar la aplicación:**

```Bash
go run main.go
```

5. **Abrir en el navegador:**
   Visita http://localhost:8080 para interactuar con la aplicación.

```
👨‍💻 Autor
Johan Sebastian Vasquez Diaz

Ingeniero de Sistemas


---

Solo tienes que ajustar los enlaces de tu repositorio, tu LinkedIn y tu portafolio donde dice `tu-usuario` y `tu-enlace`.

¿Te gustaría que empecemos a escribir el código del archivo `main.go` para inicializar el servidor y pr
```
