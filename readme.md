# Programación y Plataformas Web  (PPW)
---
# Practica 1 - Explorando los Estándares Web con HTML

**Asignatura:** Programación y Plataformas Web
**Unidad:** 1.2 - Estándares Web
**Estudiante:** Rafael Prieto
**Respositorio:**[https://github.com/Raet0/icc-ppw-u1-miPrimeraPagina](https://github.com/Raet0/icc-ppw-u1-miPrimeraPagina)
**Página desplegada (GitHub Pages):**[https://raet0.github.io/icc-ppw-u1-miPrimeraPagina/](https://raet0.github.io/icc-ppw-u1-miPrimeraPagina/)

# 📘 Práctica – Página Web "El Manifiesto de Unabomber"

---

## 🧱 Estructura HTML utilizada

| Componente | Descripción | Implementación |
|-------------|--------------|----------------|
| `<!DOCTYPE html>` | Define el documento como HTML5 | Línea 1 |
| `<html lang="es">` | Indica que el idioma del documento es español | Atributo `lang="es"` |
| `<head>` | Contiene metadatos y el enlace a la hoja de estilos | Incluye `<meta>`, `<title>` y `<link>` |
| `<header>` | Encabezado principal de la página | Contiene el título `<h1>` “El Manifiesto de Unabomber” |
| `<section>` | Agrupa los apartados principales | Se usa para síntesis, resumen y enlaces |
| `<aside>` | Información adicional o complementaria | Breve biografía de Theodore Kaczynski |
| `<table>` | Muestra los pros y contras del manifiesto | Varias filas con celdas `<td>` y encabezados `<th>` |
| `<dl>` | Lista de definiciones | Resume los puntos principales del manifiesto |
| `<ul>` | Lista de enlaces externos | Contiene links a la UPS y GitHub |
| `<footer>` | Pie de página | Nombre del estudiante y asignatura |

---

## 🧩 Nuevas etiquetas exploradas

| Etiqueta | Descripción | Implementación |
|-----------|--------------|----------------|
| `<aside>` | Presenta información complementaria | Biografía del autor al costado del texto principal |
| `<dl>`, `<dt>`, `<dd>` | Lista de definiciones estructurada | Se usa para explicar los 4 puntos del manifiesto |
| `<section>` | Estructura el documento por bloques temáticos | “Síntesis”, “Resumen” y “Links” |
| `<img>` | Inserta imagen ilustrativa | Fotografía de Theodore Kaczynski centrada |

**Código usado:**
```html
<aside>
  <p>Theodore John Kaczynski, conocido como Ted Kaczynski o el Unabomber, nació el 22 de mayo de 1942 en Chicago.</p>
</aside>

<dl>
  <dt>1) Crítica al sistema tecnológico:</dt>
  <dd>Kaczynski argumenta que la tecnología moderna controla a las personas.</dd>
</dl>
```

## Capturas de pantalla del proyecto final

![captura](<images/captura-primer-trabajo.png>)