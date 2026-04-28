# Práctica Temática: Propuesta de Mini Proyecto Documentado (LOOM)

## 1) Título de la práctica
**Diseño de Propuesta para Proyecto Pequeño en Terminal**

> Ejemplos de título final que puedes usar para tu proyecto:
> - *Mini Toolkit en ARM64*
> - *Asistente de Estudio en Terminal*
> - *Reporteador de Información del Sistema*
> - *Organizador de Archivos*
> - *Juego de Aprendizaje en Línea de Comandos*

---

## 2) Descripción general
En esta actividad **no vas a empezar programando en grande**; primero vas a diseñar una propuesta clara y completa de un proyecto pequeño.  
Tu objetivo es demostrar que sabes **plantear, justificar y estructurar** una solución antes de desarrollar código.

### Lenguaje principal (elige uno)
- ARM64 Assembly
- C
- Python
- Bash

> **Nota importante:** si eliges **ARM64 Assembly**, tu propuesta debe ser para un programa **muy pequeño y bien delimitado**.

### Enfoque principal de la práctica
- Documentación técnica.
- Planeación de trabajo.
- Estructura del repositorio.
- Definición del caso de uso.
- Plan de pruebas.

### Restricciones del proyecto
Para mantener el alcance realista (compatible con herramientas de IA con límites de uso), tu proyecto debe ser:
- Pequeño.
- Ejecutable en entorno local.
- Sin frameworks grandes.
- Sin APIs pagadas.
- Sin base de datos.
- Sin servicios en la nube.
- Sin contenedores.
- Sin dependencias complejas.

---

## 3) Entregables del estudiante
Tu repositorio debe incluir, como mínimo, los siguientes archivos:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Además, son opcionales (si ya quieres incluir prototipo):
- `src/`
- `scripts/`
- `tests/`

---

## 4) Estructura recomendada del repositorio
Usa esta estructura mínima como referencia:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

---

## 5) Contenido mínimo esperado por archivo

### `README.md`
Incluye:
1. Nombre del proyecto.
2. Lenguaje principal elegido y justificación breve.
3. Objetivo general.
4. Alcance (qué sí incluye y qué no incluye).
5. Instrucciones básicas de ejecución (aunque sea preliminar).

### `docs/propuesta.md`
Incluye:
1. Problema que quieres resolver.
2. Idea de solución.
3. Usuarios objetivo.
4. Entradas y salidas esperadas.
5. Limitaciones del proyecto.
6. Criterios de éxito.

### `docs/caso_de_uso.md`
Incluye:
1. Escenario principal de uso.
2. Pasos del usuario (flujo básico).
3. Resultado esperado.
4. Posibles errores de usuario y cómo responderá el sistema.

### `docs/estructura_repositorio.md`
Incluye:
1. Árbol de carpetas propuesto.
2. Función de cada carpeta/archivo.
3. Convención de nombres.
4. Estrategia para mantener orden y legibilidad.

### `docs/plan_de_pruebas.md`
Incluye:
1. Casos de prueba funcionales mínimos.
2. Datos de entrada de ejemplo.
3. Resultado esperado por cada caso.
4. Criterios para considerar válida la práctica.

---

## 6) Reglas de diseño de la propuesta
1. El proyecto debe poder explicarse en menos de una cuartilla por sección.
2. Evita “proyectos plataforma” (demasiado grandes).
3. Prioriza herramientas de línea de comandos y archivos locales.
4. Si usas IA de apoyo, documenta qué parte te ayudó a planear y qué parte redactaste tú.
5. Si planteas código, que sea prototipo mínimo, no producto final.

---

## 7) Rúbrica sugerida (100 puntos)
- **Claridad de la propuesta (25 pts):** objetivo, problema y alcance bien definidos.
- **Calidad de documentación (25 pts):** estructura, redacción técnica y coherencia entre archivos.
- **Viabilidad técnica (20 pts):** tamaño adecuado, factible en tiempo y recursos.
- **Caso de uso y pruebas (20 pts):** escenarios útiles y criterios verificables.
- **Orden del repositorio (10 pts):** estructura limpia, nombres consistentes, navegación fácil.

---

## 8) Sugerencias temáticas de bajo alcance
Si no sabes qué elegir, puedes tomar una de estas ideas:
1. **Organizador de apuntes por fecha y materia** (Bash/Python).
2. **Validador simple de formato de archivos CSV** (Python/C).
3. **Mini calculadora de conversiones** (C/Python).
4. **Script para resumen de uso básico del sistema** (Bash).
5. **Programa mínimo de menú en ARM64** (solo operaciones básicas de entrada/salida).

---

## 9) Entrega
- Sube tu propuesta al repositorio asignado en GitHub Classroom.
- Verifica que todos los archivos solicitados existan y estén completos.
- Asegúrate de que la propuesta se entienda por sí sola, sin explicación adicional en clase.

---

## 10) Criterio de aceptación rápida (checklist)
Antes de entregar, confirma:
- [ ] Elegí **un** lenguaje principal y lo justifiqué.
- [ ] Mi proyecto es pequeño y viable.
- [ ] Incluí todos los documentos obligatorios en `docs/`.
- [ ] Definí al menos 3 casos de prueba con entrada y salida esperada.
- [ ] Mi `README.md` explica claramente el objetivo y alcance.
- [ ] La estructura del repositorio coincide con lo documentado.

---

### Nota final para estudiantes
Esta práctica evalúa tu capacidad de **pensar como arquitecto(a) de software**: analizar, delimitar, justificar y planear. El código puede ser mínimo; la **calidad de tu diseño documental** es lo más importante.
