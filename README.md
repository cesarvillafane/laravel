# Proyecto Laravel

Este es un proyecto base de Laravel.

## Requisitos

*   PHP (^7.3|^8.0)
*   Composer
*   Node.js y NPM (opcional, para la compilación de assets)
*   Una base de datos compatible (MySQL, PostgreSQL, SQLite, SQL Server)

## Instalación

1.  Clonar el repositorio:
    ```bash
    git clone <url-del-repositorio>
    cd <nombre-del-directorio-del-proyecto>
    ```
2.  Copiar el archivo de ejemplo de entorno:
    ```bash
    cp .env.example .env
    ```
3.  Configurar las variables de entorno necesarias en el archivo `.env`. Como mínimo, deberás configurar `APP_KEY` y los detalles de conexión a la base de datos (`DB_CONNECTION`, `DB_HOST`, `DB_PORT`, `DB_DATABASE`, `DB_USERNAME`, `DB_PASSWORD`).
4.  Instalar dependencias de PHP:
    ```bash
    composer install
    ```
5.  Generar la clave de aplicación:
    ```bash
    php artisan key:generate
    ```
6.  Ejecutar las migraciones de la base de datos:
    ```bash
    php artisan migrate
    ```
7.  (Opcional) Instalar dependencias de Node.js:
    ```bash
    npm install
    ```
8.  (Opcional) Compilar assets de frontend:
    ```bash
    npm run dev
    ```
    o para producción:
    ```bash
    npm run prod
    ```

## Uso (Cómo ejecutar el proyecto)

Para iniciar el servidor de desarrollo de Laravel, ejecuta:
```bash
php artisan serve
```
Por defecto, el servidor se iniciará en `http://127.0.0.1:8000`.

## Ejecución de Pruebas

Para ejecutar el conjunto de pruebas automatizadas, utiliza el siguiente comando:
```bash
php artisan test
```

## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir, por favor:

1.  Haz un fork del repositorio.
2.  Crea una nueva rama para tu feature (`git checkout -b feature/nueva-funcionalidad`).
3.  Realiza tus cambios y haz commit (`git commit -am 'Añade nueva funcionalidad'`).
4.  Empuja tu rama (`git push origin feature/nueva-funcionalidad`).
5.  Abre un Pull Request.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles (aunque Laravel por defecto usa la licencia MIT, un archivo LICENSE físico podría no estar presente en todos los proyectos base, pero se especifica en `composer.json`).
The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
