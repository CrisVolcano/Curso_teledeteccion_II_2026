# GF0662 Teledeteccion UCR

Repositorio del curso **GF0662 - Teledeteccion** de la Universidad de Costa Rica.

Este espacio organiza el programa, lecturas, recursos de apoyo y materiales de laboratorio para que el estudiantado pueda encontrar rapidamente lo necesario durante el ciclo 2026.

## Entrada recomendada

Cuando GitHub Pages este activo, la portada del curso puede publicarse desde este mismo repositorio usando el archivo:

- [index.html](index.html)

Mi recomendacion es usar **GitHub Pages desde la rama `main` y la carpeta `/ (root)`**. Asi la pagina inicial funciona como una puerta de entrada atractiva para estudiantes, mientras GitHub mantiene el historial, los archivos descargables y la organizacion completa del curso.

## Estructura

- `docs/`: programa del curso e instrucciones academicas.
- `extras/`: guias rapidas para crear cuentas y preparar plataformas.
- `resources/`: bibliografia obligatoria, complementaria y recursos externos.
- `labs/`: practicas y ejercicios de laboratorio.
- `scripts/`: scripts de apoyo y procesamiento.
- `data/`: datos de ejemplo o insumos pequenos para practicas.

## Primeros pasos para estudiantes

1. Revisar el programa del curso en `docs/programa_curso_2026/`.
2. Crear las cuentas necesarias desde `extras/`.
3. Consultar la bibliografia obligatoria por semana en `resources/bibliografia/obligatoria/`.
4. Usar `labs/` y `scripts/` cuando se publiquen las practicas.

## Publicacion en GitHub

Para vincular esta carpeta con el repositorio remoto:

```bash
git branch -M main
git remote add origin https://github.com/OWNER/GF0662-Teledeteccion-UCR.git
git add .
git commit -m "Agregar materiales iniciales del curso"
git push -u origin main
```

Luego, en GitHub:

1. Ir a **Settings > Pages**.
2. En **Build and deployment**, seleccionar **Deploy from a branch**.
3. Elegir la rama `main` y la carpeta `/ (root)`.
4. Guardar.

## Nota sobre archivos grandes

El repositorio completo pesa aproximadamente 188 MB, pero no se detectaron archivos individuales mayores a 50 MB. Esto esta dentro del limite habitual de GitHub para archivos normales, aunque conviene evitar subir datos pesados o resultados derivados.
