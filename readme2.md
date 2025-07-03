# CRUD de Productos y Categorías con Yii2 y Frontend HTML

Este proyecto es una prueba técnica desarrollada con el framework Yii2 (REST API) y un frontend basado en HTML, CSS y JavaScript puro. Permite gestionar productos y categorías mediante un sistema CRUD completo y consumo de API.

## Tecnologías utilizadas

- Backend: [Yii2 Framework](https://www.yiiframework.com/)
- Base de datos: MySQL / MariaDB
- Frontend: HTML, CSS y JavaScript
- API RESTful para productos y categorías

---

## Instrucciones de instalación

### 1. Clona el repositorio
```bash
git clone https://github.com/tuusuario/tu-repo.git
cd tu-repo

2. Instala dependencias con Composer

composer install

3. Configura la base de datos

Edita el archivo config/db.php con tus credenciales:

return [
    'class' => 'yii\db\Connection',
    'dsn' => 'mysql:host=localhost;dbname=nombre_bd',
    'username' => 'usuario',
    'password' => 'contraseña',
    'charset' => 'utf8',
];

4. Crea la base de datos

Ejecuta los scripts SQL desde /sql/estructura.sql para crear las tablas producto y categoria.
5. Inicia el servidor Yii2

php yii serve --port=8888