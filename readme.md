# Portfolio

Este proyecto es un portafolio personal donde se muestran mis trabajos, habilidades y experiencia profesional.

## Características

- Presentación personal
- Listado de proyectos destacados
- Información de contacto
- Diseño responsivo

## Tecnologías utilizadas

- HTML5
- CSS3 / SASS
- JavaScript
- [Framework o librería utilizada, ej. React, Vue, etc.]

## Instalación

1. Clona el repositorio:

    ```bash
    git clone https://github.com/tu-usuario/portfolio.git
    ```

2. Copia el contenido de la carpeta `portfolio` al directorio raíz de tu servidor Nginx.

3. Configura Nginx para servir los archivos estáticos. Un ejemplo básico de configuración:

    ```nginx
    server {
        listen 80;
        server_name tu-dominio.com;

        root /ruta/a/tu/carpeta/portfolio;
        index index.html;

        location / {
            try_files $uri $uri/ =404;
        }
    }
    

## Uso

Explora el portafolio para conocer más sobre mis proyectos y experiencia. Puedes contactarme a través del formulario de contacto incluido.

## Licencia

[MIT](LICENSE)

---

Desarrollado por Steven Barragan.