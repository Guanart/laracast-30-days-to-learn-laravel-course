# Curso Laracast - Laravel en 30 d{ias
## Instalación
Ejecuta el siguiente comando para iniciar el entorno de desarrollo utilizando Laravel Sail (modificar la imagen `laravelsail/php81-composer` según la versión php del proyecto)

```bash
docker run --rm \
  -u "$(id -u):$(id -g)" \
  -v $(pwd):/var/www/html \
  -w /var/www/html \
  laravelsail/php81-composer:latest \
  composer install --ignore-platform-reqs

# O sino
docker run --rm -v $(pwd):/app -w /app composer install --ignore-platform-reqs
```

### ¿Por dónde voy?
- Hice hasta el capítulo 7 inclusive.
