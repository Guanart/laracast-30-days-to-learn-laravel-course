# Curso Laracast - Laravel en 30 días

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
````

### ¿Por dónde voy?

* Hice hasta el capítulo 7 inclusive.

### Cronograma

🔹 **Eloquent** (\~1 h 55 min, 6 episodios)

| Fecha  | Episodios | Tiempo aprox. | Enfoque clave                                         |
| ------ | --------- | ------------- | ----------------------------------------------------- |
| 16 Jul | 9–11      | \~60 min      | Meet Eloquent, consultas básicas y relaciones simples |
| 23 Jul | 12–13     | \~40 min      | Pivot tables y eager loading (N+1 problem)            |
| 30 Jul | 14        | \~25 min      | Scopes, agregados y consultas avanzadas               |

🔹 **Forms + Primer repaso** (\~1 h 10 min + 20 min)

| Fecha | Episodios  | Tiempo aprox. | Enfoque clave                       |
| ----- | ---------- | ------------- | ----------------------------------- |
| 6 Ago | 16–17      | \~70 min      | Formularios, CSRF y validación      |
| 6 Ago | repaso Elt | \~20 min      | Pequeño repaso/práctica de Eloquent |

🔹 **Authentication + Digging Deeper** (\~1 h 15 min + 40 min)

| Fecha  | Episodios | Tiempo aprox. | Enfoque clave                                           |
| ------ | --------- | ------------- | ------------------------------------------------------- |
| 13 Ago | 20        | \~30 min      | Starter kits (Breeze, UI, etc.)                         |
| 13 Ago | 22–23     | \~45 min      | Login y autorización                                    |
| 20 Ago | 18–19     | \~40 min      | Middleware, rutas avanzadas y peticiones HTTP avanzadas |

🔹 **Reforzamiento & prácticas** (\~60 min)

| Fecha  | Actividad  | Tiempo aprox. | Enfoque clave                                   |
| ------ | ---------- | ------------- | ----------------------------------------------- |
| 27 Ago | Ejercicios | \~60 min      | Mini-proyecto: CRUD con Eloquent + Forms + Auth |

🔹 **Final Project** (\~2 h, 6 episodios)

| Fecha  | Episodios | Tiempo aprox. | Enfoque clave                              |
| ------ | --------- | ------------- | ------------------------------------------ |
| 3 Sep  | 25–27     | \~70 min      | Inicio del proyecto, pruebas y TDD inicial |
| 10 Sep | 28–30     | \~50 min      | Continuación y “Everything Episode”        |

🔹 **Buffer y pulido final** (\~60 min)

| Fecha  | Actividad      | Tiempo aprox. | Enfoque clave                           |
| ------ | -------------- | ------------- | --------------------------------------- |
| 17 Sep | Revisión total | \~60 min      | Ajustes, bugs, optimizaciones y Q\&A    |
| 24 Sep | Presentación   | \~60 min      | Demo final y documentación del proyecto |