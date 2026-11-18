# parcial2-v2-software

Nombre: Franco Marchetta
Fecha: 18/11/2026

## Cómo construir e iniciar el contenedor

Paso 1. Abrir una terminal en la carpeta del proyecto.

Paso 2. Construir la imagen:

```bash
docker build -t parcial2-v2-software .
```

Paso 3. Iniciar el contenedor:

```bash
docker run -d --name parcial2-v2-software -p 8080:80 parcial2-v2-software
```

Paso 4. Abrir en el navegador: http://localhost:8080
