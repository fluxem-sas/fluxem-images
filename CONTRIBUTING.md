# Guía de Contribución

¡Gracias por tu interés en contribuir al repositorio de assets de Fluxem! Esta guía te ayudará a contribuir de manera efectiva.

## 🎯 Tipos de Contribuciones

Aceptamos los siguientes tipos de contribuciones:

- **Nuevos Assets**: Logos, iconos, imágenes para proyectos
- **Optimización**: Mejoras en calidad o tamaño de assets existentes
- **Organización**: Mejoras en la estructura del repositorio
- **Documentación**: Mejoras en README, guías y documentación
- **Correcciones**: Fixes de assets incorrectos o desactualizados

## 📋 Antes de Contribuir

### Requisitos Previos
- Cuenta de GitHub
- Conocimientos básicos de Git
- Herramientas de edición de imágenes (recomendado)

### Checklist Pre-Contribución
- [ ] ¿Tienes los derechos legales para compartir el asset?
- [ ] ¿El asset sigue nuestras convenciones de nomenclatura?
- [ ] ¿El archivo está optimizado para web?
- [ ] ¿Has verificado que no existe un asset similar?

## 🚀 Proceso de Contribución

### 1. Fork y Clone
```bash
# Fork el repositorio en GitHub, luego clona tu fork
git clone https://github.com/TU-USUARIO/fluxem-images.git
cd fluxem-images
```

### 2. Crear Rama
```bash
# Crea una nueva rama para tu contribución
git checkout -b feature/descripcion-del-cambio
# Ejemplos:
# git checkout -b feature/add-new-project-logos
# git checkout -b fix/optimize-existing-images
```

### 3. Realizar Cambios
- Añade tus assets siguiendo la estructura del repositorio
- Sigue nuestras convenciones de nomenclatura
- Optimiza las imágenes antes de subirlas

### 4. Commit y Push
```bash
# Añade los archivos
git add .

# Commit con mensaje descriptivo
git commit -m "Add: Nuevos logos para proyecto XYZ"

# Push a tu fork
git push origin feature/descripcion-del-cambio
```

### 5. Pull Request
1. Ve a GitHub y crea un Pull Request
2. Usa nuestro template de PR
3. Proporciona descripción detallada
4. Espera la revisión del equipo

## 📁 Estructura y Organización

### Estructura de Directorios
```
fluxem-images/
├── proyecto-a/
│   ├── logos/
│   ├── icons/
│   └── banners/
├── proyecto-b/
└── shared/
    ├── backgrounds/
    └── patterns/
```

### Convenciones de Nomenclatura

#### Para Archivos
- Usa **lowercase** y **guiones** para separar palabras
- Incluye el tipo de asset en el nombre
- Sé descriptivo pero conciso

```
✅ Correcto:
- logo-fluxem-horizontal.png
- icon-kiaro-32x32.png
- banner-marketing-2024.jpg

❌ Incorrecto:
- LogoFluxem.PNG
- icon.png
- banner final final v2.jpg
```

#### Para Directorios
- Usa nombres de proyecto o categorías claras
- Mantén consistencia con proyectos existentes
- Agrupa assets relacionados

## 🎨 Especificaciones Técnicas

### Formatos Aceptados
| Tipo | Formato Preferido | Formato Alternativo |
|------|------------------|-------------------|
| Logos | SVG | PNG (alta resolución) |
| Iconos | SVG | PNG (múltiples tamaños) |
| Fotografías | JPG | PNG |
| Gráficos | PNG | SVG |

### Especificaciones de Calidad
- **Resolución mínima**: 300 DPI para impresión, 72 DPI para web
- **Tamaño máximo**: 5 MB por archivo
- **Compresión**: Optimizada para web cuando sea posible
- **Transparencia**: PNG para assets con transparencia

### Tamaños Estándar para Iconos
- 16x16, 32x32, 64x64, 128x128, 256x256, 512x512 px
- Proporciona múltiples tamaños cuando sea posible

## ✍️ Template de Pull Request

Usa este template al crear tu PR:

```markdown
## Descripción
Breve descripción de los assets añadidos/modificados.

## Tipo de cambio
- [ ] Nuevos assets
- [ ] Optimización de assets existentes
- [ ] Corrección de assets
- [ ] Mejora de documentación
- [ ] Reorganización de estructura

## Assets incluidos
- [ ] Logos
- [ ] Iconos  
- [ ] Banners
- [ ] Otros: ___________

## Checklist
- [ ] Los assets siguen las convenciones de nomenclatura
- [ ] Los archivos están optimizados
- [ ] Tengo los derechos para compartir estos assets
- [ ] He verificado que no hay duplicados
- [ ] Los assets funcionan en diferentes fondos (si aplica)

## Información adicional
- **Proyecto relacionado**: 
- **Uso previsto**: 
- **Fuente original**: 
- **Licencia**: 

## Screenshots (si aplica)
[Incluye capturas de pantalla de los assets]
```

## 🔍 Proceso de Revisión

### Criterios de Revisión
1. **Calidad técnica**: Resolución, optimización, formato
2. **Consistencia**: Alineación con estilo de marca
3. **Derechos**: Verificación de licencias y permisos
4. **Organización**: Estructura y nomenclatura correcta
5. **Documentación**: Información completa en el PR

### Tiempos de Respuesta
- **Revisión inicial**: 2-3 días hábiles
- **Feedback**: Proporcionamos comentarios constructivos
- **Iteraciones**: Trabajamos contigo para perfeccionar la contribución
- **Aprobación**: Una vez que cumple todos los criterios

## 🛠️ Herramientas Recomendadas

### Edición de Imágenes
- **GIMP** (gratuito): Editor de imágenes completo
- **Inkscape** (gratuito): Editor de vectores
- **Adobe Creative Suite**: Photoshop, Illustrator
- **Figma**: Diseño colaborativo en línea

### Optimización
- **TinyPNG**: Compresión de PNG y JPG
- **SVGO**: Optimización de archivos SVG
- **ImageOptim**: Optimización batch (Mac)
- **Squoosh**: Herramienta web de Google

## 🤔 ¿Necesitas Ayuda?

### Recursos
- [Documentación de Git](https://git-scm.com/doc)
- [Guía de GitHub](https://guides.github.com/)
- [Mejores prácticas de design systems](https://designsystemsrepo.com/)

### Contacto
- **Issues**: Para preguntas generales
- **Email**: contact@fluxem.com
- **Discussions**: Para conversaciones sobre mejoras

## 🎉 Reconocimiento

Los contribuyentes serán reconocidos en:
- Lista de contribuyentes del repositorio
- Releases notes (para contribuciones significativas)
- Nuestro sitio web (contribuciones excepcionales)

---

¡Gracias por contribuir al ecosistema Fluxem! 🚀