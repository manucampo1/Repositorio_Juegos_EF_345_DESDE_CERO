# Repositorio de Juegos de Educación Física

Versión completa y reconstruida con **345 juegos**.

La web tiene todos sus archivos directamente en la raíz para evitar confusiones de carpetas al desplegarla en GitHub Pages o Vercel.

## Comprobar el catálogo

```bash
npm run check
```

El resultado correcto es:

```text
Comprobación correcta: 345 juegos y ningún título duplicado.
```

## GitHub Desktop

1. Descomprime el ZIP.
2. Abre GitHub Desktop.
3. Usa **File > Add local repository** y selecciona esta carpeta.
4. Si todavía no es un repositorio, elige **Create a repository**.
5. Realiza el commit y pulsa **Publish repository** o **Push origin**.

## Vercel

1. Importa el repositorio de GitHub.
2. Selecciona **Framework Preset: Other**.
3. Deja **Root Directory** en `./`.
4. Deja vacíos **Build Command** y **Output Directory**.
5. Pulsa **Deploy**.

Vercel encontrará `index.html` directamente en la raíz.

## GitHub Pages

En **Settings > Pages**, selecciona **Deploy from a branch**, rama `main` y carpeta `/(root)`.
