# ⛩️ Anime Tracker - iOS Liquid Glass Edition

**Anime Tracker** es una aplicación web moderna, rápida y minimalista diseñada con una estética **iOS Liquid Glass (Glassmorphism)** y un tema de color **verde esmeralda**. Te permite organizar tu biblioteca de anime, realizar búsquedas en tiempo real a través de la API oficial de **AniList**, llevar el registro de tus episodios vistos, filtrar por géneros/categorías y acceder directamente al episodio que te toca ver en **AnimeAV1**.

---

## 🌟 Características Principales

* 📱 **Diseño iOS Liquid Glass:** Interfaz limpia con efectos de cristal translúcido (`backdrop-filter`), bordes suaves y modo oscuro/claro integrado.
* 🎠 **Carrusel Hero (Watching):** Muestra hasta 5 animes que estés viendo actualmente con un slider interactivo, accesos rápidos y datos del siguiente episodio.
* 🔍 **Búsqueda AniList GraphQL:** Conexión directa a la API pública de AniList sin necesidad de claves API para buscar cualquier anime en tiempo real (portadas, sinopsis limpias, temporadas, puntuaciones y personajes).
* 🏷️ **Filtro de Géneros en Cápsulas:** Extrae automáticamente todos los géneros de tu biblioteca (*Shounen, Isekai, Romance, Fantasy, Slice of Life, etc.*) y te permite filtrarlos al instante mediante píldoras de cristal interactivas.
* 🎬 **Enlace Directo a Episodio en AnimeAV1:** Al hacer clic en *"Ver Episodio X en AnimeAV1"*, la app busca automáticamente el título y el episodio exacto en `https://animeav1.com`.
* 📊 **Estadísticas en Tiempo Real:** Contador automático de total de animes, episodios vistos, animes completados, viendo y planeados.
* 💾 **Almacenamiento Local (`localStorage`):** Tu biblioteca se guarda de forma 100% privada y local en tu navegador sin requerir bases de datos ni servidores externos.

---

## 🚀 Cómo Usarlo

1. **Buscar un Anime:**
   * Escribe el nombre del anime en la barra de búsqueda superior y presiona **Enter** o haz clic en **Search**.
2. **Agregar a tu Biblioteca:**
   * Se abrirá una ventana de vista previa. Elige tu estado (*Watching, Plan to Watch, Completed, On Hold, Dropped*), asigna los episodios que has visto y haz clic en **Add to Library**.
3. **Controlar tu Progreso:**
   * Haz clic en cualquier tarjeta de anime para abrir sus detalles. Usa los botones `+ Episode` o `− Episode` para actualizar tu progreso.
4. **Ver Episodios Online:**
   * Haz clic en el botón verde **"Ver Episodio X en AnimeAV1"** en el carrusel principal o en los detalles del anime para abrir la búsqueda directa del episodio.
5. **Filtrar por Categorías:**
   * Haz clic en los botones laterales para filtrar por estado, o usa las píldoras de género horizontales para ver solo tus animes de *Isekai, Acción, etc.*

---

## 📄 Licencia

Este proyecto es de código abierto bajo la licencia **MIT**.
