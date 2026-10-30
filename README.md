# DiscoGuía Mecanismos

Guía de bolsillo para detectar **mecanismos de resistencia antimicrobiana por difusión con discos**: dónde colocar cada disco, cómo se ve un resultado positivo, qué se deduce y cómo informarlo. Compara lado a lado **CLSI M100 (36.ª ed., 2026)** y **EUCAST (tablas v16.1, 2026)**.

**Doce pruebas con placa animada paso a paso:**

- **Gramnegativos:** BLEE con clavulánico, AmpC plasmídica con ácido borónico, AmpC cromosómica inducible (imipenem–ceftriaxona), KPC con ácido borónico y metalo-β-lactamasas con EDTA.
- **Grampositivos:** SARM con cefoxitina, penicilinasa por el borde del halo, prueba D, enterococo resistente a vancomicina y alto nivel de resistencia a aminoglucósidos.
- **Fastidiosos:** *S. pneumoniae* con oxacilina 1 µg y *H. influenzae* con β-lactamasa, BLNAR y bencilpenicilina 1 U.

## Uso
- Se abre en cualquier navegador y funciona en el teléfono.
- **Instalar en el teléfono:**
  - Android (Chrome): menú ⋮ → «Instalar app» o «Agregar a la pantalla principal».
  - iPhone (Safari): botón Compartir → «Agregar a inicio».
- **Sin conexión:** después de la primera visita, la app funciona sin internet.

## Archivos
| Archivo | Para qué sirve |
|---|---|
| `index.html` | La app completa en un solo archivo, con fuentes incluidas |
| `manifest.webmanifest`, `icons/` | Instalación como app y sus íconos |
| `sw.js` | Uso sin conexión |
| `.nojekyll` | Indica a GitHub Pages que publique los archivos tal cual |

## Publicar una versión nueva
1. Reemplaza `index.html`.
2. En `sw.js`, cambia el valor de `VERSION` (por ejemplo, `dgm-2026-11-15`) para que los teléfonos descarguen la versión nueva.
3. Sube los cambios a la rama `main`. GitHub Pages se actualiza en uno o dos minutos.

## Fuentes y advertencia
Cada dato de la app enlaza a su fuente en la pestaña **Fuentes**. Las principales son:

- CLSI M100 36.ª ed.
- EUCAST Breakpoint Tables v16.1.
- Guía EUCAST de mecanismos de resistencia v2.01.
- Documentos de laboratorios de referencia (INEI-ANLIS Malbrán, ISP Chile, INS Perú).

La app es una ayuda para el profesional del laboratorio y **no reemplaza** los documentos CLSI M02/M100 ni las tablas EUCAST vigentes. Los diámetros dibujados en las placas son ilustrativos.

Proyecto personal y sin fines de lucro. Tipografía IBM Plex © IBM Corp., bajo licencia SIL Open Font License 1.1.
