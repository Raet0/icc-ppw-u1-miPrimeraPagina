# Programación y Plataformas Web (PPW)
---

# Práctica 1 - Explorando los Estándares Web con HTML, CSS y JS

**Asignatura:** Programación y Plataformas Web  
**Unidad:** 1.2 - Estándares Web  
**Estudiante:** Rafael Prieto  
**Repositorio:** [https://github.com/Raet0/icc-ppw-u1-miPrimeraPagina](https://github.com/Raet0/icc-ppw-u1-miPrimeraPagina)  
**Página desplegada (GitHub Pages):** [https://raet0.github.io/icc-ppw-u1-miPrimeraPagina/](https://raet0.github.io/icc-ppw-u1-miPrimeraPagina/)

---

# 📘 Práctica – Página Web *“El Manifiesto de Unabomber”*

Esta práctica consistió en la creación de una página web informativa sobre el *Manifiesto de Unabomber*, aplicando los **principios de HTML semántico**, **estilos con CSS** y una **funcionalidad con JavaScript** para implementar un modo oscuro dinámico.

---

## 🧱 Estructura HTML utilizada

| Componente | Descripción | Implementación |
|-------------|--------------|----------------|
| `<!DOCTYPE html>` | Define el documento como HTML5 | Línea 1 |
| `<html lang="es">` | Indica el idioma principal del documento | Atributo `lang="es"` |
| `<head>` | Contiene metadatos, título y enlace al CSS | `<meta>`, `<title>`, `<link>` |
| `<header>` | Encabezado principal de la página | Título y descripción del contenido |
| `<section>` | Agrupa apartados principales | “Síntesis”, “Resumen”, “Etiquetas Usadas” |
| `<aside>` | Información complementaria | Biografía de Theodore Kaczynski |
| `<table>` | Muestra los pros y contras del manifiesto | Celdas `<td>` y encabezados `<th>` |
| `<dl>` | Lista de definiciones | Resume los puntos clave del manifiesto |
| `<ul>` | Lista de enlaces externos | Links a GitHub y la UPS |
| `<footer>` | Pie de página informativo | Datos del autor y asignatura |
| `<script>` | Enlaza el archivo JavaScript externo | Archivo: `js/main.js` |

---

## 🧩 Nuevas etiquetas y componentes explorados

| Elemento | Descripción | Implementación |
|-----------|--------------|----------------|
| `<aside>` | Contiene información complementaria | Biografía del autor al costado |
| `<dl>`, `<dt>`, `<dd>` | Estructura de definiciones | Explicación de los puntos del manifiesto |
| `<img>` | Inserta imagen ilustrativa centrada | Fotografía de Theodore Kaczynski |
| `<button>` | Botón interactivo con ícono | Usado para activar el modo oscuro |
| `<link>` | Conecta el CSS externo | `href="css/styles.css"` |
| `<script>` | Conecta el JavaScript externo | `src="js/main.js"` |

**Código ejemplo:**
```html
<header>
  <section id="etiquetasDescubiertas">
    <div>
      <h2>Etiquetas Usadas</h2>
      <button id="toggle-dark-mode"><img src="images/luna.png" height="30" width="30"></button>
      <p>En esta sección podrás encontrar la explicación de las etiquetas usadas para este sitio web.</p>
    </div>
  </section>
</header>
```
## Capturas de pantalla del proyecto final

![captura](<images/captura2.png>)