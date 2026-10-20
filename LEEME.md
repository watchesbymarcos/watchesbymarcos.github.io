# Watches by Marcos: cómo publicar la página (gratis)

La página queda en **GitHub Pages** (hosting gratis) y Marcos la edita desde **Pages CMS** (panel gratis, anda en celular y compu). No hace falta Firebase, Netlify ni pagar nada.

Dirección final: `https://NOMBRE-DE-USUARIO.github.io` (por ejemplo `https://watchesbymarcos.github.io`).

---

## Parte 1: Publicar la página (lo hace Julio, una sola vez, unos 15 minutos)

1. **Crear la cuenta de GitHub.** Entrá a github.com y creá una cuenta gratis. El nombre de usuario es el que va a aparecer en la dirección, así que usá **watchesbymarcos** (o el más parecido que esté libre).

2. **Crear el repositorio.** Arriba a la derecha, tocá **+ → New repository**.
   - Nombre exacto: `watchesbymarcos.github.io` (tu usuario + `.github.io`).
   - Marcalo como **Public**.
   - Tocá **Create repository**.

3. **Subir los archivos.** En el repositorio vacío, tocá **uploading an existing file**. Arrastrá **todo lo que está dentro** de la carpeta descomprimida: `index.html`, `pages.yml`, `LEEME.md` y las carpetas `data` e `images`. Abajo, tocá **Commit changes**.

4. **Renombrar el archivo del panel.** Abrí `pages.yml`, tocá el lápiz (Edit) y, en el nombre del archivo arriba, cambiá `pages.yml` por **`.pages.yml`** (con un punto adelante). Tocá **Commit changes**.

5. **Activar la página.** Andá a **Settings → Pages**.
   - En **Source** elegí **Deploy from a branch**.
   - En Branch, elegí **main** y la carpeta **/(root)**. Tocá **Save**.
   - Esperá 1 o 2 minutos y entrá a `https://watchesbymarcos.github.io`. La página ya está online.

## Parte 2: Darle el panel a Marcos (lo hace Julio, 5 minutos)

6. Entrá a **pagescms.org**, tocá **Sign in** y entrá con tu cuenta de GitHub.
7. Te va a pedir instalar la app de Pages CMS en GitHub. Dale acceso **solo** al repositorio `watchesbymarcos.github.io`.
8. Abrí el repositorio desde Pages CMS. Vas a ver tres secciones: **Relojes**, **Portada (carrusel)** y **Datos de la tienda**.
9. Buscá la sección de **colaboradores (Collaborators)** e invitá a **marcosmolina548@gmail.com**. Marcos no necesita cuenta de GitHub: le llega un mail para entrar.

Solo pueden editar Marcos y vos. Los visitantes solo ven la página.

## Parte 3: Cómo edita Marcos (desde el celu o la compu)

- Entra a **pagescms.org** con el mail de la invitación y abre la tienda.
- **Relojes:** tocar **+** para agregar uno. Completa nombre, marca, precio, foto y descripción. Para uno agotado, destilda **Hay stock**. Para uno que ya no vende, lo borra de la lista.
- **Portada:** cambia títulos, fotos y a qué marca lleva cada botón.
- **Datos de la tienda:** WhatsApp, Instagram, promos, medios de pago y beneficios.
- Al terminar, toca **Save**. La página se actualiza sola en **1 o 2 minutos**.

**Consejos para las fotos:**
- Que sean **cuadradas** y con fondo limpio para los relojes, y **horizontales** para la portada.
- Las fotos de celular pesan mucho y hacen la página lenta. Antes de subirlas, conviene achicarlas. Una forma fácil es mandársela a uno mismo por WhatsApp y guardar esa versión, que ya queda comprimida.
- Las fotos que vienen cargadas salieron de una captura y son de baja resolución: conviene reemplazarlas por las originales.

## Opcional: dominio propio

Si más adelante quieren `watchesbymarcos.com.ar`, se registra en **nic.ar** (pago anual, con clave fiscal) y se conecta en **Settings → Pages → Custom domain**. El hosting sigue siendo gratis.

## Agregar una marca nueva

Las marcas de la lista desplegable de cada reloj están en `.pages.yml` (línea `values: [Citizen, Orient, Seiko, Otros]`). Para sumar una, editá esa línea en GitHub y agregala también en **Datos de la tienda → Marcas**.
