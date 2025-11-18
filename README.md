# 📘 Fundamentos de Algebra - Actividad #17. GitHub - Editor de imágenes matricial

## 👨‍💻 Información del Estudiante

- **Nombre:** Joaquin Uriona
- **Matrícula:** SW2509057
- **Grupo:** 1-C
- **Cuatrimestre:** Primer Cuatrimestre
- **Carrera:** TSU en Desarrollo e Innovación de Software
- **Profesor:** Jorge Javier Pedrozo Romero

---

## 📋 Descripción del Proyecto

Este repositorio contiene mi solución a la práctica de **Fundamentos de Algebra**, donde implemento funciones en JavaScript para Manipular imágenes PNG aplicando operaciones matriciales del álgebra lineal.

## 🎯 Objetivos Alcanzados

- ✅ Dominar variables y tipos de datos en JavaScript
- ✅ Implementar estructuras condicionales
- ✅ Utilizar bucles y funciones
- ✅ Manipular arrays unidimensionales
- ✅ Trabajar con arrays bidimensionales (matrices)
- ✅ Aplicar control de versiones con Git y GitHub

---

## 📊 Progreso de Ejercicios

### Sección 1: Fundamentos - Conversión Imagen ↔ Matriz (20 puntos)
- [x] 1.1 Cargar imagen pequeña (5 pts) ✅
- [x] 1.2 Guardar matriz como PNG (5 pts) ✅
- [x] 1.3 Extraer canal rojo (5 pts) ✅
- [x] 1.4 Leer dimensiones (5 pts) ✅

**Puntos obtenidos: 20/20**

### Sección 2: Operaciones Básicas (25 puntos)
- [x] 2.1 Aumentar brillo (8 pts) ✅
- [x] 2.2 Negativo de imagen (8 pts) ✅
- [x] 2.3 Blanco y negro (9 pts) ✅

**Puntos obtenidos: 25/25**

### Sección 3: Transformaciones Geométricas (30 puntos)
- [x] 3.1 Efecto espejo (10 pts) ✅
- [x] 3.2 Arriba-abajo (10 pts) ✅
- [x] 3.3 Rotación horaria (10 pts) ✅

**Puntos obtenidos: 30/30**

### Sección 4: Filtros Avanzados (25 puntos)
- [x] 4.1 Blend de dos imágenes (8 pts) ✅
- [x] 4.2 Efecto vintage (9 pts) ✅
- [x] 4.3 Detección simple (8 pts) ✅

**Puntos obtenidos: 25/25**

---

## 📈 Calificación Final

```
┌────────────────────────────────────────┐
│  REPORTE DE CALIFICACIÓN               │
├────────────────────────────────────────┤
│  Puntos obtenidos: 100/100             │
│  Porcentaje: 100%                      │
│  🎓 Calificación: A - Excelente        │
└────────────────────────────────────────┘
```

![Tests](../../actions/workflows/test.yml/badge.svg)

---

## 🚀 Instalación y Uso

### Prerrequisitos
- Node.js (versión 14 o superior)
- Git

### Clonar el repositorio
```bash
git clone https://github.com/TU-USUARIO/editor-imagenes-matricial.git
cd editor-imagenes-matricial
```

### Instalar dependencias
```bash
npm install
```

### Ejecutar tests
```bash
npm test
```

### Ejecutar tests en modo watch
```bash
npm run test:watch
```

### Ver cobertura de código
```bash
npm run test:coverage
```

---

## 📁 Estructura del Proyecto

```
editor-imagenes-matricial/
│
├── generar-imagenes-prueba.js
├── package.json                    # Configuración del proyecto
├── package-lock.json
├── README.md                       # Este archivo
├── .gitignore
│
├── src/
│   ├── ejercicios.js               # ⭐ Archivo principal con mis soluciones
│   ├── ejercicios.test.js          # Tests automatizados (no modificar)
│   ├── matriz.js
│   └── utilidades.js
│
├── imagenes/
│   ├── entrada/        
│   └── salida/       
│
└── .github/
    └── workflows/
              └── test.yml           # Configuración de GitHub Actions

```


---

## 💡 Aprendizajes Clave

### Lo que más me costó
- **Ejercicio 4.3 **: Entender cómo comparar el pixel derecho y pixel inferior
- **Ejercicio 4.1 **: No entendi como mezclar dos imágenes usando un factor de mezcla.

### Lo que más me gustó
- **Testing Automático**: Es increíble ver los tests correr y obtener retroalimentación inmediata.

### Técnicas aplicadas
- Uso de `for` loops para iteraciones
- Arrays dinámicos con `.push()`
- Bucles anidados 

---

## 🔧 Ejemplos de Código

### Función Favorita: Transponer Matriz
```javascript 
  
  const buffer = fs.readFileSync(rutaImagen);

  const png = PNG.sync.read(buffer);

  const alto = png.height;

  const ancho = png.width;
  
  return { ancho: ancho, alto: alto, totalPixeles: ancho * alto };
```

**Por qué me gusta:** Demuestra cómo obtener dimensiones sin cargar toda la imagen en memoria.

---

## 📚 Recursos Utilizados

- **Guía Estudiantes:** `guias/GUIA_ESTUDIANTES.md`
- **Conceptos Álgebra:** `guias/CONCEPTOS_ALGEBRA.md`
- **Documentación pngjs:** [npmjs.com/package/pngjs](https://www.npmjs.com/package/pngjs)

---

## 🎯 Próximos Pasos

Este proyecto me prepara para:
- ✨ Manipulación de matrices
- 🖼️ Edición y transformación más avanzada de imágenes
- 🔐 Procesamiento digital de imágenes
- 📊 Algoritmos basados en manipulación binaria o matricial

---

## 📝 Historial de Commits

```bash
# Ver mi historial completo
git log --oneline --graph --decorate
```

**Commits destacados:**
- `feat: Completar Sección 1 - Variables y tipos de datos`
- `feat: Implementar ejercicios de condicionales`
- `feat: Resolver funciones y bucles`
- `feat: Completar manipulación de arrays`
- `feat: Finalizar arrays bidimensionales - matrices`
- `docs: Actualizar README con resultados finales`

---

## 🤝 Agradecimientos

- **Profesor Jorge Javier Pedrozo Romero** por la estructura del curso y la práctica
- **Tecnológico de Software** por la formación integral

---

## 📧 Contacto

- **Email Institucional:** [joaquin.uriona@tecdesoftware.edu.mx]
- **GitHub:** [Joako601](https://github.com/TU-USUARIO)

---

## 📄 Licencia

Este proyecto es parte de las actividades académicas del **Tecnológico de Software** y está bajo la licencia MIT.

---

<div align="center">

**⭐ Si te gustó este proyecto, dale una estrella ⭐**

Hecho con 💙 por [Joaquin Uriona] - 2025

</div>
