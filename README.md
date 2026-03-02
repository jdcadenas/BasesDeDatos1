# GitHub Pages Deployment Guide

## Bases de Datos I - UPTAEB

Este repositorio contiene la presentación de la Unidad I: Fundamentos de Bases de Datos para los estudiantes del PNF Informática de la UPTAEB.

## 🚀 Despliegue en GitHub Pages

### Opción 1: GitHub Actions (Recomendado)

1. Ve a **Settings** → **Pages**
2. En **Source**, selecciona **GitHub Actions**
3. El workflow se ejecutará automáticamente

### Opción 2: Rama gh-pages

1. Ve a **Settings** → **Pages**
2. En **Source**, selecciona **Deploy from a branch**
3. Selecciona la rama **main** y la carpeta **/ (root)**
4. Haz clic en **Save**

### Opción 3: Usando el workflow incluido

Este repositorio incluye un workflow automático que:
- Se ejecuta al hacer push a la rama `main`
- Despliega automáticamente el contenido

## 📁 Estructura del Proyecto

```
BasesDeDatos1/
├── index.html              # Página principal (menú)
├── assets/                 # Logos e imágenes institucionales
├── semana-1-2/            # Presentación Unidad I (12 puntos)
│   ├── index.html         # Presentación completa
│   └── images/            # Imágenes de la presentación
├── material/              # Bibliografía en PDF
└── .github/
    └── workflows/
        └── pages.yml      # Workflow de despliegue
```

## 🎨 Colores Institucionales UPTAEB

- **Azul UPTAEB**: `#003876`
- **Rojo**: `#E63946`
- **Dorado**: `#FFD700`

## 📊 Contenido de la Unidad I

La presentación cubre los **12 puntos fundamentales**:

1. ✅ Introducción y Motivación
2. ✅ Evolución del Manejo de Datos
3. ✅ Conceptos Fundamentales (James Martín)
4. ✅ Modelos de Datos (Jerárquico, Red, Relacional)
5. ✅ Estructura Relacional (Codd, 1970)
6. ✅ Arquitectura ANSI/SPARC (3 niveles)
7. ✅ Administración y DBA
8. ✅ Lenguaje SQL (DDL y DML)
9. ✅ Integridad de Datos
10. ✅ Transacciones y Concurrencia (ACID)
11. ✅ Las 12 Reglas de Codd
12. ✅ Práctica Integradora

## 🔗 URLs de Acceso

Una vez desplegado, podrás acceder a:

- **Página Principal**: `https://[tu-usuario].github.io/BasesDeDatos1/`
- **Presentación Unidad I**: `https://[tu-usuario].github.io/BasesDeDatos1/semana-1-2/`
- **Biblioteca**: `https://[tu-usuario].github.io/BasesDeDatos1/material/`

## 🛠️ Desarrollo Local

Para probar localmente:

```bash
# Opción 1: Usando Python
python -m http.server 8000

# Opción 2: Usando Node.js
npx http-server -p 8000

# Opción 3: Usando PHP
php -S localhost:8000
```

Luego abre: `http://localhost:8000`

## 📝 Notas Importantes

- Todas las rutas de imágenes son relativas
- El diseño es responsive (móvil y escritorio)
- Se recomienda usar GitHub Actions para despliegues automáticos
- Los PDFs del material bibliográfico deben estar en la carpeta `material/`

## 👨‍💻 Autor

Presentación creada para la cátedra **Bases de Datos I** del PNF Informática - UPTAEB (2026)

## 📄 Licencia

Material educativo de uso académico para la UPTAEB.
