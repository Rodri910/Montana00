# Montañas By Rodri — PWA para móvil

## Pasos para publicar en GitHub Pages

### 1. Crear repositorio en GitHub
- Ve a https://github.com/new
- Nombre: `montanas-by-rodri` (o el que quieras)
- Visibilidad: **Public** (necesario para GitHub Pages gratis)
- Clic en **Create repository**

### 2. Subir los archivos
Desde tu PC, abre CMD en la carpeta `montanas-pwa` y ejecuta:

```bash
git init
git add .
git commit -m "Primera versión"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/montanas-by-rodri.git
git push -u origin main
```

### 3. Activar GitHub Pages
- Ve a tu repositorio en GitHub
- Settings → Pages
- Source: **GitHub Actions**
- El despliegue es automático cada vez que hagas push

### 4. Acceder a la app
La URL será: `https://TU_USUARIO.github.io/montanas-by-rodri/montanas_by_rodri.html`

---

## Instalar en el móvil

### Android (Chrome)
1. Abre la URL en Chrome
2. Aparecerá un banner "Añadir a pantalla de inicio"
3. O pulsa ⋮ → "Añadir a pantalla de inicio"
4. La app se instala como nativa con tu icono

### iPhone/iPad (Safari)
1. Abre la URL en Safari
2. Pulsa el botón compartir (cuadrado con flecha)
3. Selecciona "Añadir a pantalla de inicio"
4. La app se instala con tu icono

---

## Actualizar la app
1. Sustituye `montanas_by_rodri.html` por la nueva versión
2. Ejecuta `git add . && git commit -m "Actualización" && git push`
3. GitHub Actions despliega automáticamente en ~1 minuto

## Notas
- Los datos se guardan en el dispositivo (localStorage)
- Funciona sin conexión a internet (Service Worker)
- Compatible con Android e iOS
