# Presupuesto de panadería

Aplicación web instalable para calcular costos y precios de recetas de panadería.

## Usarla desde el celular

Después de publicar la rama `main` en GitHub Pages, el enlace será:

**https://mnicolas707-bit.github.io/Presupuesto_panaderia/**

Abrí el enlace una vez con internet. Desde el menú del navegador elegí **Agregar a pantalla de inicio** (o **Instalar aplicación**). Luego podrás abrirla sin internet; también funcionará el importador de PDF porque PDF.js queda guardado en la caché del dispositivo.

## Publicación

El workflow `.github/workflows/deploy-pages.yml` publica automáticamente la aplicación cada vez que hay cambios en `main`. En la configuración del repositorio, GitHub Pages debe usar **GitHub Actions** como fuente.
