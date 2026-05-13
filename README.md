<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/1179/1179069.png" />

# 🎬 Movie Database Management System

### Sistema de gestión multimedia y base de datos de películas 🚀

<p align="center">
  <b>Movie Database Management System</b> es una aplicación desarrollada en Java y Maven que permite administrar información de películas, actores y clientes mediante operaciones CRUD y consultas SQL dinámicas.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-Backend-orange?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/Maven-Build%20Tool-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/CLI-Terminal-black?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-funcionalidades">Funciones</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-comandos-sql">SQL</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Movie Database Management System** es un sistema de consola diseñado para gestionar bases de datos de películas, actores y clientes.

El proyecto permite realizar operaciones CRUD, ejecutar comandos SQL y administrar registros multimedia desde terminal.

El sistema fue desarrollado para practicar:

- ☕ Programación en Java
- 🗄️ Bases de datos MySQL
- ⚙️ Maven
- 🖥️ Aplicaciones CLI
- 📡 Gestión de datos
- 🎬 Sistemas multimedia

---

# ✨ Funcionalidades

## 🎬 Gestión de películas

- 🔍 Buscar películas por actor
- 🎭 Consultar información multimedia
- 📄 Mostrar resultados dinámicos

---

## 👤 Gestión de usuarios

- ➕ Agregar clientes
- ❌ Eliminar clientes
- 💳 Validación de tarjetas
- 📧 Gestión de información personal

---

## 🌟 Gestión de actores

- ➕ Registrar nuevas estrellas
- 📅 Guardar fechas de nacimiento
- 🖼️ Agregar URLs de imágenes

---

## 🗄️ Base de datos

- 📊 Mostrar esquema de tablas
- ⚡ Ejecutar SQL manualmente
- 🔄 Operaciones CRUD completas

---

# 🛠️ Tecnologías utilizadas

## ☕ Backend

<p>
  <img src="https://skillicons.dev/icons?i=java" />
</p>

- Java
- Java CLI
- JDBC

---

## ⚙️ Build System

<p>
  <img src="https://skillicons.dev/icons?i=maven" />
</p>

- Apache Maven 3.3.9

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- SQL Queries
- Database Schema

---

## 🖥️ Entorno

- Linux Bash
- Ubuntu Server
- Terminal CLI

---

# 📂 Estructura del proyecto

```bash
SistemaGestionMultimedia/
│
├── src/
├── database/
├── pom.xml
├── backend/
├── scripts/
└── README.md
```

---

# ⚡ Instalación

## 📋 Requisitos

- Java JDK
- Apache Maven 3.3.9
- MySQL
- Linux / Ubuntu

---

# 🚀 Compilación del proyecto

## 1️⃣ Compilar en localhost

```bash
cd ../yourPath/project1/movies
mvn clean compile
```

---

## 2️⃣ Compilar en servidor

Conectarse al servidor Ubuntu:

```bash
/home/ubuntu/makeJava
```

⚡ `makeJava` es el script bash encargado de compilar el proyecto.

---

# ▶️ Ejecución del sistema

## 🖥️ Ejecutar en localhost

```bash
mvn exec:java -Dexec.mainClass="com.fablix.moviedb.view.View" -Dexec.classpathScope=runtime
```

---

## 🔐 Credenciales

```bash
Username: root
Password: [presionar enter]
```

---

## ☁️ Ejecutar en servidor

```bash
/home/ubuntu/runJava
```

Luego ingresar:

```bash
Username: root
Password: 1993zhangtianle
```

---

# 🎬 Funciones del sistema

## 🔍 Buscar películas por actor

- Buscar usando:
  - Nombre
  - Apellido
  - ID del actor

---

## ➕ Agregar nueva estrella

Permite registrar:

- Nombre
- Apellido
- Fecha de nacimiento
- URL de fotografía

---

## 👤 Agregar cliente

Permite guardar:

- Nombre
- Contraseña
- Dirección
- Email
- Tarjeta de crédito

---

## ❌ Eliminar cliente

- Eliminación mediante tarjeta de crédito válida.

---

## 📊 Mostrar esquema de base de datos

- Visualización de:
  - Tablas
  - Tipos de atributos
  - Estructura SQL

---

## ⚡ Ejecutar comandos SQL

- Consultas SQL dinámicas
- Validación de errores
- Ejecución manual

---

## 🚪 Opciones de salida

- Salir del menú
- Cerrar programa completo

---

# 🗄️ Comandos SQL útiles

## 📄 SELECT

```sql
select <column name or *> from <table name> where <condition>;
```

---

## ✏️ UPDATE

```sql
update <table name> set <column1 = newvalue1> where <condition>;
```

---

## ➕ INSERT

```sql
insert into <table name> values ('value1','value2');
```

---

## ❌ DELETE

```sql
delete from <table name> where <condition>;
```

---

# 📸 Vista previa

<div align="center">

<img width="1000" src="https://images.unsplash.com/photo-1516110833967-0b5716ca1387?q=80&w=1200&auto=format&fit=crop" />

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Aprender y practicar

- Java Programming
- Maven
- SQL
- JDBC
- CRUD Systems
- CLI Development
- Database Management
- Backend Architecture

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 🌐 Interfaz web
- 📱 Aplicación móvil
- 🔐 Sistema de autenticación avanzada
- 📊 Dashboard administrativo
- 🎥 Streaming multimedia
- ☁️ Integración cloud
- 📡 API REST

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/new-feature
```

2. Commit de cambios

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push al repositorio

```bash
git push origin feature/new-feature
```

4. Crear Pull Request 🚀

---

# 👨‍💻 Autor

<div align="center">

##Isai Reyes Developer

Desarrolladores enfocados en plataformas multimedia y experiencias modernas de streaming web.

</div>


---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto educativo desarrollado para práctica de Java, Maven y sistemas de bases de datos multimedia.

---

<div align="center">

### 🎬 Movie Database Management System — administración multimedia desde terminal 🚀

</div>
