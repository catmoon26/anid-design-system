# ANID - Guía de Marca e Identidad Visual

## Agencia Nacional de Investigación y Desarrollo — Gobierno de Chile

---

## 1. Colores Institucionales

### Primarios
| Color        | Hex       | Uso                                    |
|-------------|-----------|----------------------------------------|
| Navy        | `#0E2841` | Fondo principal (variante azul)        |
| Azul ANID   | `#156082` | Acento principal, encabezados          |
| Azul Claro  | `#0F9ED5` | Acento secundario, destacados          |

### Secundarios
| Color        | Hex       | Uso                                    |
|-------------|-----------|----------------------------------------|
| Naranja     | `#E97132` | Acento, barra multicolor               |
| Verde Oscuro| `#196B24` | Acento, barra multicolor               |
| Verde Claro | `#4EA72E` | Acento, barra multicolor               |
| Púrpura     | `#A02B93` | Acento, barra multicolor               |

### Neutrales
| Color        | Hex       | Uso                                    |
|-------------|-----------|----------------------------------------|
| Blanco      | `#FFFFFF` | Fondo (variante blanca), texto claro   |
| Gris Claro  | `#E8E8E8` | Fondos secundarios, separadores        |
| Negro       | `#000000` | Texto principal (variante blanca)      |

---

## 2. Tipografía

**Fuente principal: Verdana**

Verdana se usa en todas las comunicaciones oficiales de ANID: presentaciones, documentos oficiales, oficios y material institucional.

| Elemento   | Tamaño (presentación) | Peso    |
|------------|----------------------|---------|
| Título     | 40pt                 | Regular |
| Subtítulo  | 24pt                 | Regular |
| Cuerpo     | 28pt                 | Regular |
| Cuerpo 2   | 24pt                 | Regular |
| Pie/caption| 18pt                 | Regular |

**Interlineado**: 90% del tamaño de fuente.

---

## 3. Barra Multicolor

Elemento distintivo de la identidad ANID. Es una franja horizontal delgada compuesta por los colores de acento en secuencia:

```
Naranja → Azul Claro → Azul ANID → Verde Oscuro → Verde Claro → Púrpura
#E97132   #0F9ED5     #156082     #196B24        #4EA72E       #A02B93
```

**Ubicación**: parte superior de las diapositivas y documentos.

---

## 4. Presentaciones

### Formato
- Tamaño: 16:9 (33.867 cm × 19.05 cm)
- Fuente: Verdana

### Variante Azul (fondo oscuro)
- Fondo: Navy (#0E2841)
- Texto: Blanco (#FFFFFF)
- Logo ANID: versión blanca, centrado en parte superior
- Barra multicolor: franja superior
- Pie: logos institucionales (Gobierno de Chile, ANID)

### Variante Blanca (fondo claro)
- Fondo: Blanco (#FFFFFF)
- Texto: Negro (#000000)
- Logo ANID: versión color, junto al título
- Barra multicolor: franja superior
- Pie: logos institucionales (Gobierno de Chile, ANID)

---

## 5. Documentos Oficiales

### Formatos disponibles
- **Hoja carta**: documentos generales
- **Oficio**: comunicaciones formales
- **Oficio ordinario**: comunicaciones oficiales numeradas

### Reglas
- Tamaño de página: Carta (216mm × 279mm)
- Fuente: Verdana
- Logo ANID en encabezado
- Barra multicolor como separador visual

---

## 6. Logos

El logo de ANID incluye el escudo de Chile y el texto "ANID" junto con "Agencia Nacional de Investigación y Desarrollo".

### Versiones
- **Logo color**: para fondos blancos/claros
- **Logo blanco**: para fondos oscuros (navy)
- **Logo monocromático**: para impresión B/N

### Área de protección
Mantener espacio libre alrededor del logo equivalente a la altura de la letra "A" de ANID.

---

## 7. Estructura de Archivos

```
anid-design-system/
├── tokens/
│   ├── brand.json          # Tokens de marca en JSON
│   └── design-tokens.css   # Variables CSS
├── templates/
│   ├── presentacion-azul.html    # Template presentación fondo azul
│   └── presentacion-blanca.html  # Template presentación fondo blanco
├── examples/
│   └── demo.html           # Demo interactiva de componentes
├── assets/
│   └── logos/              # Logos ANID (SVG)
└── brand-guidelines.md     # Este archivo
```
