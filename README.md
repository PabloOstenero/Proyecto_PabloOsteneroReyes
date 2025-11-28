# Planificación del proyecto
---

## Vista general

RA2 se centra en la definición y viabilidad del proyecto: recopilar información, fijar objetivos, fases, recursos y financiación.  
RA3 aborda la planificación detallada: secuenciación de tareas, asignación de recursos, logística, permisos y valoración económica.

## RA2 – Definición y viabilidad del proyecto

### a) Recopilación de información

**Objetivo:** Construir una base sólida para decisiones.

**Fuentes típicas:**

- Documentación previa, normativas, estándares técnicos (ISO, UNE, GDPR, etc.).
- Estudios de mercado, benchmarking de competidores.
- Entrevistas con stakeholders / cuestionarios.
- Datos de clientes, analítica histórica, métricas de rendimiento actual.

**Buenas prácticas:**

- Fichas de fuente (origen, fecha, fiabilidad).
- Matriz de stakeholders (interés vs influencia).
- Registro de supuestos (*assumptions log*).

---

### b) Estudio de viabilidad técnica

**Dimensiones:**

- Tecnología disponible vs requerida.
- Compatibilidad e integración (APIs, *legacy systems*).
- Riesgos técnicos (obsolescencia, escalabilidad, seguridad).
- Capacidad interna (skills del equipo).

**Herramientas:**

- Análisis GAP.
- Matriz de riesgos (probabilidad × impacto).
- Prototipos rápidos (PoC / MVP).

**Criterios de aprobación:**

- Factibilidad (sí/no).
- Coste estimado.
- Tiempo estimado.
- Riesgos mitigables.

---

### c) Identificación de fases con contenido y plazos

**Ejemplo de fases:**

1. Análisis / Requisitos  
2. Diseño (funcional y técnico)  
3. Implementación / Desarrollo  
4. Pruebas y aseguramiento de calidad  
5. Despliegue / Implantación  
6. Formación y transferencia  
7. Cierre / Evaluación  

Para cada fase:

- Entregables.
- Duración estimada.
- Responsables.
- Hitos (*milestones*).

**Representación:**

- Diagrama de Gantt.
- Ruta crítica (CPM).
- WBS (*Work Breakdown Structure*).

---

### d) Establecimiento de objetivos y alcance

**Tipos de objetivos:**

- Estratégicos (alineados con la organización).
- Técnicos (rendimiento, disponibilidad, seguridad).
- Funcionales (qué funcionalidades cubrir).
- Económicos (ROI, reducción de costes).

**SMART:** Específicos, Medibles, Alcanzables, Relevantes, Temporales.

**Alcance:**

- Incluir lo que se hace.
- Explicitar lo que NO se hace (lista de exclusiones).

**Control:**

- Matriz de requisitos.
- Control de cambios (*Change Log*).

---

### e) Determinación de actividades necesarias

- Descomponer objetivos en paquetes de trabajo (WBS) y éstos en actividades.

**Criterios:**

- Claridad.
- Duración estimable.
- Responsable único.

**Herramientas:**

- WBS.
- Diccionario de WBS.
- Kanban para gestión de flujo.

**Evitar:** actividades demasiado grandes (riesgo de estimación errónea).

---

### f) Recursos materiales y personales

**Recursos materiales:**

- Hardware, software, licencias.
- Infraestructura, laboratorios.
- Vehículos.
- EPIs.

**Recursos humanos:**

- Roles: PM, analista, dev backend/frontend, QA, DevOps, UX, legal.

**Herramientas de gestión:**

- Matriz RACI:
  - Responsible
  - Accountable
  - Consulted
  - Informed
- Plan de capacitación si hay brechas de habilidades.

---

### g) Necesidades de financiación

**Componentes de coste:**

- CAPEX (infraestructura, equipamiento inicial).
- OPEX (sueldos, hosting, mantenimiento).
- Costes indirectos (seguridad, seguros, *compliance*, formación).

**Estimaciones:**

- *Top-down* (análogos).
- *Bottom-up* (actividad a actividad).
- Paramétricas.

**Indicadores financieros:**

- VAN (NPV).
- TIR (IRR).
- *Payback*.
- ROI.

**Planificación financiera:**

- Preparar escenarios: base, optimista, pesimista.

---

## RA3 – Planificación operativa y ejecución

### a) Secuenciación de tareas según necesidades

**Dependencias:**

- Fin–Inicio (FS): más común.
- Inicio–Inicio (SS).
- Fin–Fin (FF).
- Inicio–Fin (SF, menos usual).

**Herramientas:**

- Diagrama de precedencias (PDM).
- Red CPM.
- Análisis de holguras (*float*).

**Objetivo:** identificar ruta crítica y posibles cuellos de botella.

---

### b) Recursos y logística por tarea

**Asignación:**

- Necesidad exacta por tarea (horas-hombre, equipos, entornos).

**Logística:**

- Aprovisionamiento.
- Plazos de entrega.
- Almacenamiento.
- Soporte técnico.

**Riesgos logísticos:**

- Retrasos de proveedores.
- Dependencia de importaciones.
- *Lead time* de licencias.

---

### c) Permisos y autorizaciones

**Tipos:**

- Regulatorios (ambientales, municipales, RGPD, seguridad eléctrica).
- Internos (aprobación de arquitectura, seguridad TI, comité de dirección).
- Externos (operadores de red, certificadores).

**Gestión:**

- Registrar quién lo concede.
- Tiempo de tramitación.
- Documentación requerida.

Incluir actividades de obtención de permisos en el cronograma (no suponer que son instantáneos).

---

### f) Planificación de asignación de recursos según tiempos

**Balanceo de carga (*resource leveling*):**

- Evitar picos excesivos.

**Técnicas:**

- *Resource smoothing* (mantener fechas claves).
- Ajuste de calendario laboral (festivos, vacaciones).

**Control:**

- Hoja de horas.
- *Burndown*.
- *Capacity planning* por sprint (si ágil).

**Indicadores:**

- Utilización (%).
- Desviación de horas.
- Coste real vs planificado.

---

### g) Valoración económica de la ejecución

**Presupuesto definitivo:**

- Integrar estimaciones + reservas (contingencia y gestión).

**Tipos de coste por tarea:**

- Directo.
- Indirecto.
- Fijo.
- Variable.

**Curva S:** coste acumulado vs tiempo.

**Seguimiento – Earned Value Management (EVM):**

- PV (*Planned Value*).
- EV (*Earned Value*).
- AC (*Actual Cost*).

**Indicadores:**

- `CV = EV - AC` (*Cost Variance*).
- `SV = EV - PV` (*Schedule Variance*).
- `CPI = EV / AC`.
- `SPI = EV / PV`.

---

## Tabla síntesis RA2 y RA3

| Aspecto    | RA2 (Definición / Viabilidad)                                                                 | RA3 (Planificación / Ejecución)                                                                 |
|-----------|------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Foco      | Qué y por qué                                                                                  | Cómo y cuándo                                                                                    |
| Entregables clave | Estudio viabilidad, objetivos, fases, alcance, recursos iniciales, presupuesto preliminar | Cronograma detallado, asignación de recursos, matriz de dependencias, permisos, presupuesto ejecutable |
| Herramientas | Benchmarking, WBS inicial, análisis GAP, SMART, matriz de riesgos                            | Gantt/CPM, RACI, EVM, *resource leveling*, logística, control de costes                         |
| Riesgos principales | Definición incompleta, objetivos poco claros, subestimación de recursos                 | Retrasos, sobrecarga de recursos, permisos tardíos, desvío presupuestario                        |
| Finanzas  | Estimaciones macro, escenarios                                                                 | Costeo detallado, reservas, control y KPIs                                                      |

---

## Ejemplo resumido aplicado (mini-caso)

**Proyecto:** Plataforma web de gestión de inventarios.

### RA2

- **Información:** entrevistas a logística, análisis de ERP actual, normativa de datos.
- **Viabilidad técnica:** stack Node.js + PostgreSQL viable con equipo existente; riesgo moderado de escalabilidad.
- **Fases:**  
  - Análisis (2 sem)  
  - Diseño (2 sem)  
  - Desarrollo (8 sem)  
  - Pruebas (3 sem)  
  - Despliegue (1 sem)
- **Objetivos SMART:** reducir tiempo de registro de stock en 40% en 6 meses.
- **Actividades:** modelado de datos, desarrollo API, interfaz React, integración con escáneres.
- **Recursos:** 1 PM, 2 dev backend, 2 frontend, 1 QA, 1 DevOps, servidores cloud.
- **Financiación:** CAPEX licencias iniciales 5k€, OPEX mensual 1.2k€, ROI proyectado en 18 meses.

### RA3

- **Secuenciación:** API antes de UI; integración antes de pruebas de rendimiento.
- **Recursos por tarea:**  
  - API: 2 dev backend, 160h.  
  - UI: 2 dev frontend, 200h.  
  - QA: 1 tester, 120h.
- **Permisos:** aprobación seguridad TI (1 sem), revisión legal RGPD (1 sem).
- **Asignación:** evitar que backend y QA coincidan en vacaciones (*resource smoothing*).
- **Valoración económica:** presupuesto ejecución 45k€, reserva de contingencia 10% (4.5k€); CPI y SPI monitorizados quincenalmente.

---

## Indicadores útiles

**RA2:**

- % requisitos documentados respecto total identificado.
- Tiempo medio de aprobación de viabilidad.
- Desviación estimación inicial vs final (<10% ideal).

**RA3:**

- SPI y CPI dentro de 0.9–1.1.
- % permisos obtenidos a tiempo.
- Tasa de sobreasignación (>100% capacidad semanal).
- Variación de coste acumulado vs curva S (<15%).

---

## Riesgos frecuentes y mitigación

- Objetivos ambiguos → Taller de alineación con stakeholders temprano.
- Subestimación de tiempo de permisos → Añadir *buffer* y seguimiento semanal.
- Falta de competencias técnicas → Plan de capacitación o contratación temprana.
- Dependencias externas críticas → Contratos SLA, plan alternativo (*fallback*).
- Inflación de alcance (*scope creep*) → Proceso formal de gestión de cambios.

---

## Checklist rápida RA2

1. Fuentes y evidencia recopiladas y catalogadas.  
2. Objetivos SMART aprobados.  
3. Alcance y exclusiones documentadas.  
4. Fases con entregables y duración estimada.  
5. WBS inicial creada.  
6. Recursos humanos y materiales listados.  
7. Estimación financiera preliminar con escenarios.  
8. Riesgos iniciales priorizados.  

---

## Checklist rápida RA3

1. Tareas desglosadas y ordenadas con dependencias.  
2. Cronograma con ruta crítica identificada.  
3. Permisos listados con responsables y plazos.  
4. Asignación de recursos sin sobrecargas críticas.  
5. Presupuesto detallado + reservas (contingencia/gestión).  
6. Indicadores (EVM) definidos y frecuencia de reporte.  
7. Plan de gestión de cambios y riesgos operativo.  
8. Logística (aprovisionamiento / entornos) calendarizada.  

---

## Consejos finales

- Mantén viva la documentación: versiona cada actualización de alcance o costes.
- Visualiza dependencias complejas con un diagrama de red, no solo Gantt.
- Empieza a recolectar métricas desde el día 1 (no esperar al primer hito).
- Documenta supuestos; muchos problemas nacen de supuestos implícitos.
- Aplica revisiones retrospectivas por fase para afinar las siguientes.
