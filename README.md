# Lineamientos para la Gestión de Coherencia de Datos en Microservicios

Repositorio académico asociado al Trabajo Especial de Grado titulado:

**Lineamientos para mejorar la gestión de coherencia de datos en transacciones distribuidas de arquitecturas de microservicios**

**Autor:** Luis Fernando Araujo Giardinella  
**Universidad:** Universidad Valle del Momboy  
**Facultad:** Facultad de Ingeniería  
**Carrera:** Ingeniería en Computación  
**Año:** 2026  

---

## Descripción

Este repositorio contiene los recursos complementarios desarrollados como parte del Trabajo Especial de Grado orientado a proponer lineamientos organizacionales y operacionales para mejorar la gestión de coherencia de datos en transacciones distribuidas de arquitecturas de microservicios.

La investigación aborda una problemática frecuente en sistemas distribuidos: la dificultad de mantener correspondencia lógica entre servicios independientes cuando una operación crítica involucra órdenes, pagos, inventario, facturación, notificaciones u otros componentes desacoplados.

Como aporte práctico, se desarrolló un instrumento en formato HTML que permite aplicar, evaluar y documentar los diez lineamientos propuestos en la investigación.

---

## Contenido del repositorio

```text
/
├── Instrumento_Aplicacion_Lineamientos_Microservicios_UVM_v1_1.html
├── Instrumento_Caso_Hipotetico_Comercial_Andina_Digital_UVM.html
├── TEG_Lineamientos_Coherencia_Datos_Microservicios.pdf
└── README.md
```

---

## Archivos principales

### 1. Instrumento de aplicación de lineamientos

**Archivo:**

```text
Instrumento_Aplicacion_Lineamientos_Microservicios_UVM_v1_1.html
```

Este archivo contiene el instrumento general para evaluar la aplicación de los diez lineamientos propuestos. Permite registrar datos del proceso evaluado, diagnosticar el nivel de madurez transaccional, evaluar cada lineamiento, seleccionar un patrón transaccional, revisar indicadores y generar un reporte imprimible.

---

### 2. Caso hipotético prellenado

**Archivo:**

```text
Instrumento_Caso_Hipotetico_Comercial_Andina_Digital_UVM.html
```

Este archivo contiene una versión prellenada del instrumento con base en el caso hipotético **Comercial Andina Digital, C.A.**, desarrollado en la sección 4.9 del Trabajo Especial de Grado.

El caso simula una empresa venezolana de comercio electrónico que utiliza microservicios para un flujo de compra en línea con pago electrónico, actualización de inventario, facturación y notificaciones.

---

### 3. Documento del Trabajo Especial de Grado

**Archivo:**

```text
TEG_Lineamientos_Coherencia_Datos_Microservicios.pdf
```

Documento académico completo entregado para revisión y defensa ante la Universidad Valle del Momboy.

---

## Funcionalidades del instrumento

El instrumento HTML permite:

- Registrar datos generales de la organización o proceso evaluado.
- Diagnosticar el nivel de madurez transaccional mediante el Modelo de Madurez Transaccional para Microservicios.
- Evaluar los diez lineamientos propuestos mediante una escala de aplicación.
- Registrar evidencias, observaciones y acciones pendientes.
- Orientar la selección de patrones transaccionales como Transactional Outbox, Saga, CQRS o Event Sourcing.
- Evaluar indicadores operacionales relacionados con la coherencia de datos.
- Generar un reporte final imprimible o exportable como PDF desde el navegador.
- Guardar el avance localmente en el navegador.

---

## Uso del instrumento

1. Descargar o clonar el repositorio.
2. Abrir el archivo HTML en cualquier navegador moderno.
3. Completar los datos del proceso evaluado.
4. Aplicar la evaluación de los diez lineamientos.
5. Revisar la recomendación de patrón transaccional.
6. Completar los indicadores operacionales.
7. Generar el reporte final.
8. Imprimir o guardar el reporte como PDF desde el navegador.

---

## Propósito académico

El repositorio tiene como finalidad complementar la propuesta del Trabajo Especial de Grado, demostrando que los lineamientos no se limitan a una formulación teórica, sino que pueden organizarse en un instrumento práctico de aplicación, evaluación y seguimiento.

El instrumento sirve como apoyo para:

- Demostrar la aplicabilidad de los lineamientos propuestos.
- Evaluar procesos distribuidos basados en microservicios.
- Documentar evidencias y acciones pendientes.
- Orientar decisiones sobre patrones transaccionales.
- Generar reportes de seguimiento para revisión técnica o académica.

---

## Nota metodológica

El caso **Comercial Andina Digital, C.A.** es un caso hipotético construido con fines académicos. No corresponde a una empresa real ni a una intervención de campo. Su propósito es ilustrar la posible aplicación de los lineamientos en un escenario empresarial simulado.

Los indicadores incluidos en el caso hipotético deben entenderse como metas esperadas o referenciales, no como mediciones reales de producción.

---

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript
- Almacenamiento local del navegador

---

## Estructura conceptual del instrumento

El instrumento se organiza en seis secciones principales:

1. **Datos generales:** identificación de la organización, proceso, responsables y servicios involucrados.
2. **Diagnóstico inicial:** selección del nivel de madurez transaccional y criticidad del proceso.
3. **Evaluación de lineamientos:** aplicación de los diez lineamientos con escala, evidencias y acciones pendientes.
4. **Selección de patrón transaccional:** orientación para elegir mecanismos como Transactional Outbox, Saga, CQRS o Event Sourcing.
5. **Indicadores operacionales:** revisión de KPIs asociados con coherencia de datos.
6. **Reporte final:** generación de una síntesis imprimible del resultado de la evaluación.

---

## Lineamientos evaluados

El instrumento permite evaluar los siguientes diez lineamientos:

1. Diagnosticar el nivel de madurez transaccional de la organización.
2. Identificar y priorizar procesos críticos distribuidos.
3. Documentar la propiedad de datos por microservicio.
4. Registrar los flujos transaccionales críticos de extremo a extremo.
5. Controlar la publicación de eventos y prevenir el riesgo de doble escritura.
6. Seleccionar patrones transaccionales según el contexto del proceso.
7. Definir compensaciones, reintentos e idempotencia en procesos críticos.
8. Incorporar observabilidad transaccional en operaciones críticas.
9. Formalizar la gestión de incidentes por inconsistencia de datos.
10. Evaluar la gestión de coherencia de datos mediante KPIs y mejora continua.

---

## Licencia y uso

Este repositorio se publica con fines académicos, demostrativos y de consulta.

Cualquier reutilización, adaptación o referencia debe reconocer la autoría del Trabajo Especial de Grado y su contexto institucional.

---

## Referencia académica sugerida

Araujo Giardinella, L. F. (2026). *Lineamientos para mejorar la gestión de coherencia de datos en transacciones distribuidas de arquitecturas de microservicios* [Trabajo Especial de Grado, Universidad Valle del Momboy].
