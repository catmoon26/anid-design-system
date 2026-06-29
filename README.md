# ANID Design System

Sistema de diseño de la **Agencia Nacional de Investigación y Desarrollo (ANID)** — Gobierno de Chile.

Tokens de marca, plantillas y componentes para generar presentaciones, documentos y materiales institucionales con identidad visual consistente.

## Estructura

```
anid-design-system/
├── tokens/
│   ├── brand.json              # Tokens de marca (colores, tipografía, espaciado)
│   └── design-tokens.css       # Variables CSS listas para usar
├── templates/
│   ├── Presentacion_ANID_2026_azul.pptx    # Plantilla oficial (fondo azul)
│   ├── Presentacion_ANID_2026_blanco.pptx  # Plantilla oficial (fondo blanco)
│   ├── Formato_hoja_carta_ANID_2026.docx   # Formato carta oficial
│   ├── Formato_oficio_ANID_2026.docx       # Formato oficio oficial
│   ├── Formato_oficio_ordinario_2026.docx  # Formato oficio ordinario
│   ├── presentacion-azul.html              # Template HTML (variante azul)
│   ├── presentacion-blanca.html            # Template HTML (variante blanca)
│   └── documento-carta.html               # Template HTML documento
├── assets/
│   └── logos/
│       ├── anid-logo.svg                   # Logo color
│       └── anid-logo-white.svg             # Logo blanco
├── examples/
│   └── demo.html              # Demo interactiva de todos los componentes
└── brand-guidelines.md        # Guía completa de marca
```

## Colores Institucionales

| Color | Hex | Muestra |
|-------|-----|---------|
| Navy | `#0E2841` | ![](https://via.placeholder.com/16/0E2841/0E2841) |
| Azul ANID | `#156082` | ![](https://via.placeholder.com/16/156082/156082) |
| Azul Claro | `#0F9ED5` | ![](https://via.placeholder.com/16/0F9ED5/0F9ED5) |
| Naranja | `#E97132` | ![](https://via.placeholder.com/16/E97132/E97132) |
| Verde | `#196B24` | ![](https://via.placeholder.com/16/196B24/196B24) |
| Verde Claro | `#4EA72E` | ![](https://via.placeholder.com/16/4EA72E/4EA72E) |
| Púrpura | `#A02B93` | ![](https://via.placeholder.com/16/A02B93/A02B93) |

## Tipografía

**Verdana** — Fuente institucional para todas las comunicaciones oficiales.

## Barra Multicolor

Elemento distintivo de identidad: franja horizontal con los 6 colores de acento en secuencia.

```css
background: linear-gradient(to right,
  #E97132, #0F9ED5, #156082, #196B24, #4EA72E, #A02B93
);
```

## Uso

### CSS
```html
<link rel="stylesheet" href="tokens/design-tokens.css">
```
```css
.header {
  background-color: var(--anid-navy);
  color: var(--anid-white);
  font-family: var(--anid-font-family);
}
```

### JSON (para integraciones)
Los tokens están disponibles en `tokens/brand.json` para integrar con cualquier herramienta de diseño o generación de documentos.

## Demo

Abre `examples/demo.html` en un navegador para ver todos los componentes en acción.

---

ANID — Gobierno de Chile — 2026
