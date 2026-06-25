# Plan de Gestión de Proyecto
## Aplicación de Gestión de Residuos – WasteTrack
**Versión:** 2.0  
**Fecha de emisión:** 2026-06-24  
**Identificador único:** PMP-WT-2025-v2.0  
**Organización emisora:** Grupo 09 – Calidad de Software 2025-2  
**Profesor:** Albeiro Espinosa Bedoya, Ph.D., M.Sc.

---

## Página de firmas

| Rol | Nombre | Firma | Fecha |
|-----|--------|-------|-------|
| Jefe de Proyecto | ________________________ | _________ | ________ |
| Líder técnico | ________________________ | _________ | ________ |
| Responsable de calidad | ________________________ | _________ | ________ |
| Docente revisor | Albeiro Espinosa Bedoya | _________ | ________ |

---

## Historial de cambios

| Versión | Fecha | Páginas modificadas | Descripción del cambio |
|---------|-------|---------------------|------------------------|
| 1.0 | 2026-05-10 | Todas | Versión inicial del PMP — Entregable 1 del curso |
| 2.0 | 2026-06-24 | §5.2, §5.3, §4.5, §4.6, §5.9, §5.10, §8.2 | Ajustes por retroalimentación docente: estimación FPA + UCP, dependencias y camino crítico, riesgos con probabilidad e impacto, presupuesto vinculado a esfuerzo, criterios de aceptación medibles |

---

## Registro de Ajustes al Entregable 1

> Esta sección documenta explícitamente los ajustes realizados en respuesta a la retroalimentación recibida del docente sobre la versión 1.0 del PMP (Entregable 1 del curso Calidad de Software 2025-2), de conformidad con el proceso de mejora continua establecido en ISO/IEC 12207.

### Retroalimentación recibida y ajustes realizados

| # | Retroalimentación del docente (v1.0) | Sección afectada v1.0 | Ajuste realizado en v2.0 | Sección v2.0 | Estado |
|---|--------------------------------------|-----------------------|--------------------------|--------------|--------|
| 1 | **Estimación sin metodología formal:** la sección de estimación listaba Story Points pero no aplicaba los métodos vistos en clase (FPA – IFPUG, UCP). No se apreciaban cálculos de Puntos de Función ni de Puntos de Caso de Uso; tampoco se justificaba la velocidad del equipo. | §5.2 | Sección completamente reescrita con: (a) FPA completo — clasificación de ILF, EIF, EI, EO, EQ con complejidades, UFP=151, VAF=1,12 (14 factores TDI=47), FP=169, factor de productividad 12 h/FP, E_FPA=2.028 h; (b) UCP completo — 6 actores UAW=13, 11 casos de uso UUCW=95, UUCP=108, 13 factores TCF=1,08, 8 factores EF=0,935, UCP=109, PF=21,3 h/UCP, E_UCP=2.322 h; (c) consolidación — promedio 2.175 h con diferencia < 15 %; (d) Story Points — velocidad 20 SP/sprint justificada con cálculo de capacidad neta. | §5.2.1 – §5.2.4 | ✅ Completado |
| 2 | **Sin dependencias entre actividades:** el cronograma presentaba actividades por mes pero sin relaciones de precedencia ni identificación del camino crítico. Imposible determinar qué actividades son críticas para la fecha de entrega. | §5.6 / §5.7 | Se agregó sección §5.10 con tabla de 22 actividades (A01–A22), identificación de predecesoras por ID, mes de ejecución y marcado de actividades críticas (★). Camino crítico identificado: A01→A02→A03→A04→A08→A09→A10→A12→A13→A14→A16→A19→A20→A21. | §5.10 | ✅ Completado |
| 3 | **Riesgos superficiales:** los riesgos eran listados sin cuantificar probabilidad ni impacto. No se diferenciaba entre riesgos de alta y baja severidad. Las estrategias de mitigación eran genéricas. | §8.2 | Registro de riesgos actualizado con 7 riesgos (R01–R07), cada uno con: probabilidad (Alta/Media/Baja), impacto (Alto/Medio/Bajo), severidad calculada, estrategia específica (Mitigar/Contingencia/Aceptar) y responsable asignado. | §8.2 | ✅ Completado |
| 4 | **Presupuesto desconectado del esfuerzo:** la tabla de presupuesto no tenía relación con las horas estimadas. No era posible verificar que el cronograma y el presupuesto fueran coherentes entre sí. | §5.9 | Sección actualizada con distribución de horas por fase (coherente con los porcentajes de FPA), vinculación explícita de horas a costos, cálculo de costo de oportunidad a tarifa junior ($8 USD/h = $17.400 USD) y tabla completa que conecta % presupuesto, USD y horas FPA. | §5.9 | ✅ Completado |
| 5 | **Criterios de aceptación vagos:** los criterios de aceptación del producto usaban expresiones no medibles: "el sistema debe ser rápido", "la interfaz debe ser amigable". No se podía determinar cuándo el sistema estaría listo para entrega. | §4.5 | Criterios de aceptación reemplazados por métricas cuantitativas y verificables: tiempo de respuesta ≤ 2 s, tiempo de carga ≤ 3 s, disponibilidad ≥ 99 %, satisfacción ≥ 85 % (encuesta), cobertura de pruebas unitarias ≥ 80 %, 0 defectos críticos abiertos en entrega. | §4.5 | ✅ Completado |
| 6 | **Organización del proyecto poco detallada:** los roles eran mencionados pero sin descripción de responsabilidades ni jerarquía de autoridad. No quedaba claro quién tomaba decisiones en cada área. | §4.6 | Organigrama actualizado con jerarquía clara, tabla de autoridades y responsabilidades por rol (Jefe de Proyecto, Líder Frontend, Líder Backend, QA, UX/UI) y descripción de interfaces externas e internas. | §4.6 | ✅ Completado |
| 7 | **Estructura ISO 16326 incompleta:** faltaban subcláusulas requeridas por la norma como plan de capacitación (4.4), plan de infraestructura (4.3), plan de cierre (6.6), gestión de configuración (8.3) y gestión de la información (8.4). | Múltiples | Se añadieron secciones §4.3 (infraestructura tecnológica), §4.4 (métodos y herramientas), §5.3 (plan de personal), §5.4 (adquisición de recursos), §5.5 (capacitación del equipo), §6.3 (control del cronograma con SPI), §6.4 (control del presupuesto con CPI), §6.6 (plan de cierre), §8.3 (gestión de configuración – GitFlow, baseline, CCB) y §8.4 (gestión de la información). | §4.3 – §8.4 | ✅ Completado |

### Resumen de mejoras incorporadas

| Área de mejora | Estado v1.0 | Estado v2.0 |
|----------------|-------------|-------------|
| Estimación de esfuerzo (FPA) | Ausente | ✅ Completo — 169 FP, 2.028 h |
| Estimación de esfuerzo (UCP) | Ausente | ✅ Completo — 109 UCP, 2.322 h |
| Justificación de velocidad (SP) | Sin justificación | ✅ Justificado con cálculo de capacidad neta |
| Dependencias entre actividades | Ausentes | ✅ 22 actividades con predecesoras |
| Camino crítico | Ausente | ✅ Identificado (A01→A21) |
| Riesgos cuantificados | Superficiales | ✅ 7 riesgos con probabilidad, impacto, severidad |
| Presupuesto vinculado al esfuerzo | Desconectado | ✅ Por fase, coherente con FPA |
| Criterios de aceptación medibles | Vagos | ✅ 6 métricas cuantitativas |
| Estructura ISO 16326 completa | Parcial | ✅ Cláusulas 1–8 cubiertas |

---

## Prefacio

Este documento es el Plan de Gestión de Proyecto (PMP) para el desarrollo de **WasteTrack**, una aplicación móvil y web de gestión de residuos urbanos. Está redactado conforme a la norma **ISO/IEC/IEEE 16326:2009** y es el documento rector de todas las actividades de planificación, ejecución y control del proyecto.

**Audiencia:** Equipo de desarrollo, docente asesor y evaluadores del curso Calidad de Software 2025-2.

El PMP es un documento vivo; se actualiza ante cambios de alcance, cronograma o recursos y toda revisión queda registrada en el historial de cambios.

---

## Tabla de contenidos

1. Resumen del proyecto  
2. Referencias  
3. Definiciones  
4. Contexto del proyecto  
5. Planificación del proyecto  
6. Evaluación y control del proyecto  
7. Entrega del producto  
8. Planes de procesos de soporte  

---

## 1. Resumen del proyecto (Cláusula 1 del PMP)

### 1.1 Propósito, alcance y objetivos (Subcláusula 1.1.1)

**Propósito**  
Desarrollar una plataforma digital (web + móvil) que integre a ciudadanos, administradores de residuos y autoridades locales para optimizar la recolección y tratamiento de residuos urbanos, fomentando una cultura de responsabilidad ambiental.

**Alcance**  
- Aplicación web y móvil multiplataforma.  
- Área geográfica: ciudad piloto (áreas urbanas).  
- Actores cubiertos: ciudadanos, administradores de residuos, autoridades locales.  
- Excluido: gestión de residuos industriales o rurales; integraciones con sistemas de terceros fuera del piloto.

**Objetivos específicos**

| # | Objetivo | Indicador de éxito |
|---|----------|--------------------|
| O1 | Crear sistema de notificaciones en tiempo real para recolección | Latencia de notificación ≤ 2 s |
| O2 | Implementar módulo de información sobre reciclaje y separación | Disponible en versión 1.0 |
| O3 | Implementar sistema de análisis de datos para autoridades | Panel funcional con datos históricos |
| O4 | Optimizar rutas de recolección | Reducción ≥ 15 % en costos operacionales (piloto) |
| O5 | Incrementar tasa de reciclaje ciudadano | Incremento medible en ciudad piloto |

---

### 1.2 Supuestos y restricciones (Subcláusula 1.1.2)

**Supuestos**
- El cliente (municipio piloto) provee datos geográficos de rutas actuales.
- Los ciudadanos disponen de smartphone con Android ≥ 8.0 o iOS ≥ 13.
- El equipo tiene acceso continuo a internet y herramientas de desarrollo.
- Los servidores en la nube estarán disponibles desde el mes 3.

**Restricciones**
- Duración fija: **6 meses** (enero – junio 2026).
- Presupuesto fijo académico; sin contratación externa.
- Stack tecnológico definido: React, Node.js, base de datos NoSQL.
- El sistema debe cumplir normativas medioambientales locales aplicables.

---

### 1.3 Entregables del proyecto (Subcláusula 1.1.3)

| Entregable | Descripción | Fecha límite |
|------------|-------------|--------------|
| E1 – Documento de requisitos | Requisitos funcionales, no funcionales y de calidad completos | Fin mes 1 |
| E2 – Prototipos UI/UX | Wireframes y mockups validados con usuarios | Fin mes 2 |
| E3 – Release Alfa | Backend funcional + módulo ciudadanos | Fin mes 3 |
| E4 – Release Beta | Sistema completo con módulos administrador y autoridades | Fin mes 4 |
| E5 – Informe de pruebas | Resultados de pruebas unitarias, integración y usuario | Fin mes 5 |
| E6 – Sistema desplegado | Aplicación en producción en ciudad piloto | Fin mes 6 |
| E7 – PMP actualizado | Versión final del plan con lecciones aprendidas | Fin mes 6 |

---

### 1.4 Resumen de cronograma y presupuesto (Subcláusula 1.1.4)

**Cronograma resumido**

```
Mes 1: Investigación y levantamiento de requisitos
Mes 2: Diseño de arquitectura y UI/UX
Mes 3: Desarrollo – Módulo ciudadanos y backend base
Mes 4: Desarrollo – Módulo administrador y autoridades
Mes 5: Pruebas, corrección de defectos y optimización
Mes 6: Despliegue, piloto y cierre
```

**Presupuesto estimado**

| Categoría | Estimado |
|-----------|----------|
| Recursos humanos (4 desarrolladores × 6 meses) | Valorizado en créditos académicos |
| Infraestructura cloud (servidor, BD, CI/CD) | $150 USD/mes × 4 meses = $600 USD |
| Herramientas y licencias | $0 (herramientas open source) |
| Pruebas con usuarios | $50 USD (compensaciones piloto) |
| **Total** | **≈ $650 USD** |

---

### 1.5 Evolución del plan (Subcláusula 1.2)

El PMP se revisará al cierre de cada fase. Las actualizaciones requerirán aprobación del jefe de proyecto y del docente asesor. Los cambios significativos al alcance activan el proceso de control de cambios (Sección 6.2).

---

## 2. Referencias (Cláusula 2 del PMP)

| Ref | Documento |
|-----|-----------|
| [1] | ISO/IEC/IEEE 16326:2009 – Systems and software engineering – Life cycle processes – Project management |
| [2] | ISO/IEC 12207:2008 – Software life cycle processes |
| [3] | ISO/IEC 25010:2011 – Systems and software Quality Requirements and Evaluation (SQuaRE) |
| [4] | ISO 10006:2003 – Quality management in projects |
| [5] | Grupo09_aplicacion-de-gestion-de-residuos-wastetrack.pdf – Descripción del proyecto |
| [6] | React Documentation – https://react.dev |
| [7] | Node.js Documentation – https://nodejs.org |

---

## 3. Definiciones (Cláusula 3 del PMP)

| Término | Definición |
|---------|------------|
| **WasteTrack** | Nombre del sistema de gestión de residuos urbanos objeto de este proyecto |
| **PMP** | Plan de Gestión de Proyecto (Project Management Plan) |
| **WBS** | Estructura de Desglose del Trabajo (Work Breakdown Structure) |
| **Ciudadano** | Usuario final que reporta y consulta información de recolección |
| **Administrador de residuos** | Operador que gestiona rutas y responde reportes |
| **Autoridad local** | Ente gubernamental con acceso al panel de análisis y políticas |
| **Release Alfa** | Primera versión funcional con funcionalidades básicas para prueba interna |
| **Release Beta** | Versión completa para prueba con usuarios reales antes del despliegue |
| **Sprint** | Ciclo de desarrollo iterativo de 2 semanas |

---

## 4. Contexto del proyecto (Cláusula 4 del PMP)

### 4.1 Modelo de proceso (Subcláusula 4.1)

Se adopta un ciclo de vida **iterativo-incremental** con marcos de **Scrum** adaptado:

- Sprints de 2 semanas.
- Revisión de Sprint al final de cada iteración.
- Backlog priorizado por valor de negocio y riesgo técnico.
- 3 sprints por mes en promedio.
- Entregables incrementales al final de cada fase.

**Fases del ciclo de vida:**

```
[Investigación] → [Diseño] → [Desarrollo] → [Pruebas] → [Despliegue] → [Cierre]
```

### 4.2 Plan de mejora de procesos (Subcláusula 4.2)

- Retrospectiva al final de cada sprint.
- Métricas de velocidad de equipo rastreadas por sprint.
- Revisión mensual de métricas de calidad.

### 4.3 Plan de infraestructura (Subcláusula 4.3)

| Componente | Tecnología | Detalle |
|------------|------------|---------|
| Frontend web | React 18+ | SPA, despliegue en Vercel |
| Aplicación móvil | React Native | Android + iOS |
| Backend | Node.js + Express | API REST |
| Base de datos | MongoDB (NoSQL) | Colecciones: usuarios, residuos, rutas, reportes |
| Autenticación | JWT + OAuth 2.0 | — |
| CI/CD | GitHub Actions | Despliegue automático en rama main |
| Almacenamiento | AWS S3 o similar | Imágenes de reportes |
| Monitoreo | Grafana + Prometheus | Disponibilidad y performance |

### 4.4 Métodos, herramientas y técnicas (Subcláusula 4.4)

| Área | Herramienta |
|------|-------------|
| Gestión de proyecto | GitHub Projects / Trello |
| Control de versiones | Git + GitHub |
| Diseño UI/UX | Figma |
| Documentación | Markdown + Notion |
| Pruebas unitarias | Jest (backend) + React Testing Library (frontend) |
| Pruebas de integración | Supertest |
| Pruebas de rendimiento | k6 |
| Análisis estático | ESLint + Prettier |
| Revisión de código | Pull Requests con mínimo 1 aprobador |

### 4.5 Plan de aceptación del producto (Subcláusula 4.5)

El producto se aceptará cuando cumpla **todos** los criterios siguientes:

| Criterio | Meta |
|----------|------|
| Tiempo de respuesta de búsqueda y notificación | ≤ 2 segundos |
| Tiempo de carga de pantalla | ≤ 3 segundos en condiciones óptimas |
| Disponibilidad del sistema | ≥ 99 % |
| Satisfacción de usabilidad (encuesta usuarios) | ≥ 85 % de evaluación positiva |
| Cobertura de pruebas unitarias | ≥ 80 % |
| Defectos críticos abiertos en entrega | 0 |

### 4.6 Organización del proyecto (Subcláusula 4.6)

```
Jefe de Proyecto
├── Líder de Desarrollo Frontend
│   └── Desarrollador(es) React / React Native
├── Líder de Desarrollo Backend
│   └── Desarrollador(es) Node.js / MongoDB
├── Responsable de Calidad (QA)
│   └── Analista de pruebas
└── Diseñador UX/UI
```

**Interfaces externas:** Docente asesor (revisión quincenal), municipio piloto (retroalimentación en pruebas).  
**Interfaces internas:** Reunión de equipo semanal (standup diario de 15 min).

**Autoridades y responsabilidades:**

| Rol | Responsabilidad principal |
|-----|--------------------------|
| Jefe de Proyecto | Cronograma, riesgos, comunicación con stakeholders |
| Líder Frontend | Arquitectura UI, revisión de código frontend |
| Líder Backend | Arquitectura API, revisión de código backend |
| QA | Plan de pruebas, reporte de defectos, métricas de calidad |
| UX/UI | Wireframes, pruebas de usabilidad, guía de estilos |

---

## 5. Planificación del proyecto (Cláusula 5 del PMP)

### 5.1 Iniciación del proyecto

| Actividad | Descripción | Responsable |
|-----------|-------------|-------------|
| Kick-off | Reunión inicial con equipo y stakeholders | Jefe de Proyecto |
| Configuración de repositorio | GitHub org, branches, pipelines CI/CD | Líder Backend |
| Configuración de ambientes | Dev, Staging, Producción | Líder Backend |
| Incorporación del equipo | Accesos, herramientas, onboarding | Jefe de Proyecto |

### 5.2 Plan de estimación

Se aplican dos métodos complementarios conforme a lo establecido en ISO/IEC/IEEE 16326 y a las técnicas vistas en clase (Sesiones 06 y 07):

1. **Método principal: Análisis de Puntos de Función (FPA – IFPUG)**
2. **Método de validación cruzada: Puntos de Caso de Uso (UCP)**
3. **Planificación de sprints: Story Points (Planning Poker)**

---

#### 5.2.1 Análisis de Puntos de Función (FPA)

**Paso 1 – Identificación y clasificación de funciones**

##### Archivos Lógicos Internos (ILF) — datos controlados por WasteTrack

| ILF | RET | DET | Complejidad | PF |
|-----|-----|-----|-------------|-----|
| Usuarios (ciudadanos, admins, autoridades) | 3 | 10 | Media | 10 |
| Reportes de recolección | 2 | 8 | Media | 10 |
| Rutas de recolección (con datos geoespaciales) | 4 | 15 | Alta | 15 |
| Notificaciones push | 1 | 6 | Baja | 7 |
| Contenido de información de reciclaje | 1 | 5 | Baja | 7 |
| Estadísticas e historial de análisis | 3 | 12 | Alta | 15 |
| **Total ILF** | | | | **64** |

##### Archivos de Interfaz Externa (EIF) — datos de sistemas externos

| EIF | RET | DET | Complejidad | PF |
|-----|-----|-----|-------------|-----|
| Datos georreferenciados del municipio piloto | 1 | 5 | Baja | 5 |
| Servicio OAuth 2.0 (autenticación externa) | 1 | 3 | Baja | 5 |
| AWS S3 (almacenamiento de imágenes de reportes) | 1 | 3 | Baja | 5 |
| **Total EIF** | | | | **15** |

##### Entradas Externas (EI) — procesos que modifican datos internos

| EI | FTR | DET | Complejidad | PF |
|----|-----|-----|-------------|-----|
| Registro y actualización de perfil de usuario | 1 | 5 | Baja | 3 |
| Inicio de sesión (OAuth 2.0 + JWT) | 1 | 4 | Baja | 3 |
| Crear reporte de recolección (foto + geolocalización) | 2 | 8 | Media | 4 |
| Actualizar estado de reporte (administrador) | 2 | 7 | Media | 4 |
| Crear / editar ruta de recolección | 3 | 12 | Alta | 6 |
| Cargar contenido de información de reciclaje | 2 | 6 | Media | 4 |
| Configurar parámetros del panel de autoridad | 2 | 8 | Media | 4 |
| Registrar token de notificación push | 1 | 5 | Baja | 3 |
| **Total EI** | | | | **31** |

##### Salidas Externas (EO) — salidas con procesamiento complejo

| EO | FTR | DET | Complejidad | PF |
|----|-----|-----|-------------|-----|
| Dashboard de análisis histórico (autoridades) | 4 | 15 | Alta | 7 |
| Reporte de rutas optimizadas (administrador) | 3 | 10 | Alta | 7 |
| Notificación push en tiempo real | 2 | 6 | Media | 5 |
| Informe estadístico de reciclaje | 3 | 8 | Media | 5 |
| **Total EO** | | | | **24** |

##### Consultas Externas (EQ) — consultas simples sin modificación de datos

| EQ | FTR | DET | Complejidad | PF |
|----|-----|-----|-------------|-----|
| Consultar estado de recolección (ciudadano) | 1 | 4 | Baja | 3 |
| Ver perfil de usuario | 1 | 5 | Baja | 3 |
| Ver información de reciclaje | 1 | 4 | Baja | 3 |
| Consultar historial de reportes propios | 2 | 6 | Media | 4 |
| Ver estadísticas en tiempo real (administrador) | 2 | 8 | Media | 4 |
| **Total EQ** | | | | **17** |

**Paso 2 – Puntos de Función Sin Ajustar (UFP)**

```
UFP = ILF + EIF + EI + EO + EQ
UFP = 64 + 15 + 31 + 24 + 17 = 151
```

**Paso 3 – Factor de Ajuste de Valor (VAF)**

| # | Factor de ajuste | Valor (0–5) | Justificación |
|---|-----------------|-------------|---------------|
| 1 | Comunicación de datos | 4 | API REST + WebSockets para notificaciones push |
| 2 | Procesamiento distribuido | 3 | Web + móvil + nube (cloud) |
| 3 | Nivel de desempeño | 4 | Requisito: latencia ≤ 2 s |
| 4 | Disponibilidad del software | 5 | Requisito: ≥ 99 % uptime |
| 5 | Volumen de transacciones | 3 | Ciudad piloto; escala moderada |
| 6 | Ingreso interactivo | 4 | Múltiples formularios en móvil y web |
| 7 | Interfaz de usuario | 4 | 3 tipos de usuario + dashboards de análisis |
| 8 | Actualización en línea | 4 | Reportes y notificaciones en tiempo real |
| 9 | Complejidad interna | 3 | Optimización de rutas con datos geoespaciales |
| 10 | Reusabilidad | 2 | Componentes React compartidos |
| 11 | Facilidad de instalación | 3 | CI/CD automatizado con GitHub Actions |
| 12 | Complejidad externa de procesamiento | 3 | OAuth + AWS S3 + FCM |
| 13 | Multiplicidad | 2 | Un municipio piloto (escalable) |
| 14 | Adaptabilidad | 3 | Arquitectura modular y mantenible |

```
TDI = 4+3+4+5+3+4+4+4+3+2+3+3+2+3 = 47

VAF = 0,65 + (0,01 × 47) = 1,12
```

**Paso 4 – Puntos de Función Ajustados (FP)**

```
FP = UFP × VAF = 151 × 1,12 ≈ 169 FP
```

**Paso 5 – Factor de productividad**

Según los valores industriales típicos (Sesión 06), WasteTrack combina características de "Aplicación móvil enterprise" (12–25 h/FP) y "Plataforma cloud-native" (8–15 h/FP). Dado que el equipo es académico con experiencia media en React/Node.js y primera exposición a React Native, se selecciona **12 h/FP** como valor conservador dentro del rango inferior.

**Paso 6 – Esfuerzo total estimado**

```
E_FPA = FP × Factor de productividad
E_FPA = 169 × 12 = 2.028 horas
```

**Paso 7 – Distribución del esfuerzo por fase**

| Fase | % | Horas estimadas |
|------|---|-----------------|
| Análisis y requisitos | 20 % | 406 h |
| Diseño | 20 % | 406 h |
| Desarrollo / programación | 35 % | 710 h |
| Pruebas | 20 % | 406 h |
| Despliegue | 5 % | 101 h |
| **Total** | **100 %** | **2.028 h** |

**Duración estimada:**

```
Meses-persona = E / jornada mensual = 2.028 / 160 = 12,68 meses-persona
```

Con la composición del equipo definida en la Sección 5.3, la capacidad total disponible es de aproximadamente 16,5 personas-mes × 160 horas, equivalente a **2.640 horas**.

Tomando como línea base definitiva el esfuerzo estimado de **2.175 horas**, la utilización proyectada del equipo es:

```
Utilización = 2.175 / 2.640 × 100 = 82,39 %
```

Por tanto, el proyecto utiliza aproximadamente el **82,4 %** de la capacidad disponible y conserva un margen de gestión del **17,6 %** para imprevistos, correcciones y cambios controlados de alcance. Bajo estas condiciones, el cronograma de seis meses se considera viable.

---

#### 5.2.2 Validación cruzada: Puntos de Caso de Uso (UCP)

**Actores del sistema (UAW):**

| Actor | Interacción | Tipo | Peso |
|-------|------------|------|------|
| Ciudadano | GUI web + móvil (React Native) | Complejo | 3 |
| Administrador de residuos | GUI web (React) | Complejo | 3 |
| Autoridad local | GUI web – dashboards | Complejo | 3 |
| Servicio OAuth 2.0 | API programática (REST) | Simple | 1 |
| AWS S3 | API programática (SDK) | Simple | 1 |
| Servicio FCM / Push | Protocolo (HTTP/2) | Medio | 2 |

```
UAW = 3 + 3 + 3 + 1 + 1 + 2 = 13
```

**Casos de uso clasificados (UUCW):**

| Caso de uso | Transacciones | Tipo | Peso |
|-------------|--------------|------|------|
| Registrarse / actualizar perfil | 3 | Simple | 5 |
| Iniciar sesión OAuth | 3 | Simple | 5 |
| Crear reporte de recolección (foto + geoloc) | 6 | Medio | 10 |
| Ver estado de recolección (ciudadano) | 2 | Simple | 5 |
| Ver información de reciclaje | 2 | Simple | 5 |
| Recibir notificaciones push | 2 | Simple | 5 |
| Gestionar rutas de recolección (admin) | 10 | Complejo | 15 |
| Ver estadísticas en tiempo real (admin) | 5 | Medio | 10 |
| Gestionar reportes ciudadanos (admin) | 5 | Medio | 10 |
| Ver panel de análisis histórico (autoridad) | 8 | Complejo | 15 |
| Exportar informes de datos (autoridad) | 5 | Medio | 10 |

```
UUCW = 5+5+10+5+5+5+15+10+10+15+10 = 95

UUCP = UAW + UUCW = 13 + 95 = 108
```

**Factores de complejidad técnica (TCF):**

| Factor | Descripción | Peso | Valor | Producto |
|--------|------------|------|-------|----------|
| T1 | Sistema distribuido | 2 | 3 | 6 |
| T2 | Performance / tiempo de respuesta | 1 | 5 | 5 |
| T3 | Eficiencia del usuario final | 1 | 4 | 4 |
| T4 | Procesamiento interno complejo | 1 | 3 | 3 |
| T5 | Código reutilizable | 1 | 3 | 3 |
| T6 | Facilidad de instalación | 0,5 | 4 | 2 |
| T7 | Facilidad de uso | 0,5 | 4 | 2 |
| T8 | Portabilidad (Android + iOS + web) | 2 | 4 | 8 |
| T9 | Facilidad de cambio | 1 | 3 | 3 |
| T10 | Concurrencia | 1 | 4 | 4 |
| T11 | Seguridad especial | 1 | 3 | 3 |
| T12 | Acceso a terceros (OAuth, FCM, S3) | 1 | 3 | 3 |
| T13 | Entrenamiento a usuario | 1 | 2 | 2 |

```
TF = 48
TCF = 0,6 + (0,01 × 48) = 1,08
```

**Factores ambientales (EF):**

| Factor | Descripción | Peso | Valor | Producto |
|--------|------------|------|-------|----------|
| E1 | Familiaridad con modelo de proyecto (Scrum) | 1,5 | 3 | 4,5 |
| E2 | Experiencia en la aplicación (gestión de residuos) | 0,5 | 2 | 1,0 |
| E3 | Experiencia en OO / componentes React | 1 | 3 | 3,0 |
| E4 | Capacidad del analista líder | 0,5 | 4 | 2,0 |
| E5 | Motivación del equipo | 1 | 4 | 4,0 |
| E6 | Estabilidad de los requerimientos | 2 | 3 | 6,0 |
| E7 | Personal part-time (JP 25 %, QA 50 %) | -1 | 3 | -3,0 |
| E8 | Dificultad del lenguaje (React Native nuevo) | -1 | 2 | -2,0 |

```
EFactor = 4,5 + 1,0 + 3,0 + 2,0 + 4,0 + 6,0 – 3,0 – 2,0 = 15,5

EF = 1,4 – (0,03 × 15,5) = 0,935
```

**Puntos de Caso de Uso ajustados:**

```
UCP = UUCP × TCF × EF = 108 × 1,08 × 0,935 = 109 UCP
```

**Factor de productividad (Método Continuo):**

```
PF = 20 + k × (1 – EF)   [k = 20]
PF = 20 + 20 × (1 – 0,935) = 21,3 h/UCP
```

**Esfuerzo estimado (UCP):**

```
E_UCP = UCP × PF = 109 × 21,3 = 2.322 horas
```

---

#### 5.2.3 Consolidación de estimaciones

| Método | Esfuerzo estimado | Base del cálculo |
|--------|------------------|-----------------|
| FPA (método principal) | 2.028 h | 169 FP × 12 h/FP |
| UCP (validación cruzada) | 2.322 h | 109 UCP × 21,3 h/UCP |
| **Estimación definitiva (promedio)** | **2.175 h** | Diferencia < 15 %; rango aceptable |

La convergencia entre métodos (< 15 % de diferencia) valida la estimación. Se adopta **2.175 horas** como línea base de esfuerzo.

| Parámetro | Valor |
|-----------|-------|
| Puntos de Función ajustados (FP) | 169 FP |
| Puntos de Caso de Uso ajustados (UCP) | 109 UCP |
| Esfuerzo total estimado | 2.175 h |
| Capacidad disponible del equipo | 2.640 h (6 meses) |
| Utilización del equipo | 82,4 % |
| Margen de gestión | 17,6 % |
| Cronograma resultante | 6 meses (viable) |

---

#### 5.2.4 Planificación de sprints (Story Points)

Los Story Points se usan para la planificación táctica de sprints, alineados con el esfuerzo derivado por FPA. La velocidad de **20 SP/sprint** se justifica así: 3 desarrolladores × 8 h/día × 10 días hábiles = 240 h de capacidad bruta por sprint; con una productividad efectiva del 65 % (descontando reuniones, revisiones y coordinación), la capacidad neta es ≈ 156 h de codificación, equivalente a 20 SP con complejidad media de ≈ 8 h/SP.

| Módulo | Story Points | FP equivalente |
|--------|-------------|----------------|
| Autenticación y perfiles de usuario | 13 | 18 FP |
| Reporte de necesidad de recolección (ciudadanos) | 8 | 11 FP |
| Notificaciones en tiempo real (push + web) | 13 | 18 FP |
| Módulo de información de reciclaje | 5 | 7 FP |
| Gestión de rutas de recolección (administrador) | 21 | 30 FP |
| Estadísticas en tiempo real (administrador) | 13 | 18 FP |
| Panel de control y análisis histórico (autoridades) | 21 | 30 FP |
| API REST base + autenticación JWT | 13 | 18 FP |
| Integración y despliegue | 8 | 19 FP |
| **Total** | **115 SP** | **169 FP** |

Velocidad: **20 SP/sprint** × 6 sprints de desarrollo = 120 SP (buffer de 5 SP para correcciones).

##### Aclaración sobre la línea base de Story Points

La línea base total del proyecto es de **115 Story Points**. Esta cifra incluye **107 Story Points** asociados directamente a funcionalidades del producto y **8 Story Points** correspondientes a integración, configuración técnica, despliegue y estabilización.

Todos los documentos contractuales y de planificación deberán utilizar esta misma línea base.

### 5.3 Plan de personal

| Rol | # personas | Dedicación | Meses |
|-----|-----------|------------|-------|
| Jefe de Proyecto | 1 | 25 % | 1–6 |
| Desarrollador Frontend | 1 | 100 % | 2–5 |
| Desarrollador Backend | 1 | 100 % | 2–5 |
| Desarrollador Full Stack | 1 | 100 % | 2–5 |
| Diseñador UX/UI | 1 | 50 % | 1–3 |
| QA / Analista de pruebas | 1 | 50 % | 4–5; 100 % mes 5 |

#### Capacidad estimada por rol

| Rol | Dedicación promedio | Periodo de participación | Capacidad estimada |
|-----|---------------------|--------------------------|--------------------|
| Jefe de proyecto | 25 % | 6 meses | 240 h |
| Diseñador UX/UI | 50 % | 3 meses | 240 h |
| Desarrollador frontend | 100 % | 4 meses | 640 h |
| Desarrollador backend | 100 % | 4 meses | 640 h |
| Desarrollador full stack | 100 % | 4 meses | 640 h |
| Analista QA | Variable | 3 meses | 240 h |
| **Capacidad total estimada** | — | — | **2.640 h** |

### 5.4 Plan de adquisición de recursos

| Recurso | Tipo | Cuándo | Responsable |
|---------|------|--------|-------------|
| Servidor cloud (AWS/GCP/Azure) | Infraestructura | Inicio mes 3 | Jefe de Proyecto |
| Cuenta MongoDB Atlas | Infraestructura | Inicio mes 2 | Líder Backend |
| Licencia Figma (equipo) | Herramienta | Inicio mes 1 | UX/UI |
| Dispositivos de prueba (Android/iOS) | Hardware | Inicio mes 4 | QA |

### 5.5 Plan de capacitación del equipo

| Tema | Audiencia | Cuándo |
|------|-----------|--------|
| React Native (móvil) | Desarrolladores Frontend | Mes 1 |
| MongoDB agregaciones avanzadas | Backend | Mes 1–2 |
| Pruebas con k6 (performance) | QA | Mes 4 |
| Grafana – dashboards de monitoreo | QA + Jefe Proyecto | Mes 5 |

### 5.6 Estructura de Desglose del Trabajo (WBS)

```
WasteTrack
├── 1. Gestión del Proyecto
│   ├── 1.1 Planificación y PMP
│   ├── 1.2 Seguimiento y control
│   └── 1.3 Cierre del proyecto
├── 2. Investigación y Requisitos
│   ├── 2.1 Levantamiento de requisitos con stakeholders
│   ├── 2.2 Análisis de sistemas existentes
│   └── 2.3 Documentación de requisitos (SRS)
├── 3. Diseño
│   ├── 3.1 Diseño de arquitectura del sistema
│   ├── 3.2 Diseño de base de datos
│   ├── 3.3 Diseño UI/UX (wireframes + prototipos)
│   └── 3.4 Validación de diseño con usuarios
├── 4. Desarrollo
│   ├── 4.1 Configuración de entorno y CI/CD
│   ├── 4.2 Módulo de autenticación y perfiles
│   ├── 4.3 Módulo ciudadanos (reportes + notificaciones)
│   ├── 4.4 Módulo de información de reciclaje
│   ├── 4.5 Módulo administrador (rutas + estadísticas)
│   ├── 4.6 Módulo autoridades (panel + análisis)
│   └── 4.7 Integración frontend-backend
├── 5. Pruebas
│   ├── 5.1 Pruebas unitarias
│   ├── 5.2 Pruebas de integración
│   ├── 5.3 Pruebas de rendimiento (k6)
│   ├── 5.4 Pruebas de usabilidad con usuarios reales
│   └── 5.5 Corrección de defectos
└── 6. Despliegue
    ├── 6.1 Configuración de producción
    ├── 6.2 Piloto en ciudad seleccionada
    └── 6.3 Documentación final y entrega
```

### 5.7 Cronograma detallado

| Mes | Semana | Actividad principal | Entregable |
|-----|--------|--------------------| -----------|
| **1** | 1–2 | Kick-off, levantamiento de requisitos | Acta de inicio |
| **1** | 3–4 | Análisis de sistemas, documentación SRS | E1 – Documento de requisitos |
| **2** | 5–6 | Diseño de arquitectura y base de datos | Diagrama de arquitectura |
| **2** | 7–8 | Diseño UI/UX, wireframes, validación | E2 – Prototipos validados |
| **3** | 9–10 | Config CI/CD, autenticación, módulo ciudadanos (v1) | Sprint review |
| **3** | 11–12 | Módulo ciudadanos completo + notificaciones | E3 – Release Alfa |
| **4** | 13–14 | Módulo administrador (rutas + estadísticas) | Sprint review |
| **4** | 15–16 | Módulo autoridades (panel) + integración total | E4 – Release Beta |
| **5** | 17–18 | Pruebas unitarias e integración, corrección | Reporte de defectos |
| **5** | 19–20 | Pruebas rendimiento + usabilidad, corrección final | E5 – Informe de pruebas |
| **6** | 21–22 | Despliegue en producción, piloto ciudad | Sistema en producción |
| **6** | 23–24 | Evaluación piloto, lecciones aprendidas, cierre | E6 + E7 |

### 5.8 Asignación de recursos por actividad (extracto)

| Actividad | Frontend | Backend | QA | UX | JP |
|-----------|----------|---------|----|----|-----|
| Requisitos | ✓ | ✓ | ✓ | ✓ | ✓ |
| Diseño arquitectura | ✓ | ✓ | — | ✓ | ✓ |
| Desarrollo módulos | ✓ | ✓ | — | — | — |
| Pruebas | — | — | ✓ | ✓ | — |
| Despliegue | ✓ | ✓ | ✓ | — | ✓ |

### 5.9 Asignación presupuestaria

El presupuesto monetario cubre únicamente costos de infraestructura y herramientas. El esfuerzo humano (2.175 h) está valorizado en créditos académicos; su costo de oportunidad al tarifa junior de referencia (≈ $8 USD/h) equivaldría a **$17.400 USD**, reafirmando que el proyecto es académicamente viable solo en este contexto.

| Fase | Distribución del esfuerzo | Horas asociadas | Presupuesto operativo |
|------|---------------------------|-----------------|------------------------|
| Investigación, análisis y diseño | 40 % | 870 h | $98 USD |
| Desarrollo e integración | 35 % | 761 h | $195 USD |
| Infraestructura cloud, meses 3–6 | No aplica al esfuerzo humano | — | $293 USD |
| Pruebas, despliegue y cierre | 25 % | 544 h | $65 USD |
| **Total de esfuerzo humano** | **100 %** | **2.175 h** | — |
| **Total de presupuesto operativo** | — | — | **$650 USD** |

Las horas corresponden al esfuerzo humano estimado. El presupuesto operativo cubre principalmente infraestructura, herramientas y servicios del ejercicio académico, por lo que su distribución porcentual no debe interpretarse como una distribución proporcional de las horas de trabajo.

**Reserva de contingencia:** 10 % del presupuesto = $65 USD (incluida en el total de la Sección 6.4).

---

### 5.10 Dependencias entre actividades

La siguiente tabla describe las relaciones de precedencia entre las actividades del WBS. Las actividades del **camino crítico** están marcadas con ★.

| ID | Actividad | Predecesoras | Mes |
|----|-----------|-------------|-----|
| A01 | ★ Kick-off y acta de inicio | — | 1 |
| A02 | ★ Levantamiento de requisitos con stakeholders | A01 | 1 |
| A03 | ★ Documentación SRS | A02 | 1 |
| A04 | ★ Diseño de arquitectura del sistema | A03 | 2 |
| A05 | Diseño de base de datos | A04 | 2 |
| A06 | Diseño UI/UX (wireframes) | A03 | 2 |
| A07 | Validación de diseño con usuarios | A06 | 2 |
| A08 | ★ Configuración entorno y CI/CD | A04 | 3 |
| A09 | ★ Módulo de autenticación y perfiles | A05, A08 | 3 |
| A10 | ★ Módulo ciudadanos (reportes + notificaciones) | A09 | 3–4 |
| A11 | Módulo de información de reciclaje | A09 | 3–4 |
| A12 | ★ Módulo administrador (rutas + estadísticas) | A10 | 4 |
| A13 | ★ Módulo autoridades (panel + análisis) | A12 | 4 |
| A14 | ★ Integración frontend-backend | A10, A11, A12, A13 | 4 |
| A15 | Pruebas unitarias (continuas por módulo) | A09 en adelante | 3–5 |
| A16 | ★ Pruebas de integración | A14 | 5 |
| A17 | Pruebas de rendimiento k6 | A16 | 5 |
| A18 | Pruebas de usabilidad con usuarios | A14 | 5 |
| A19 | ★ Corrección de defectos críticos | A16, A17, A18 | 5 |
| A20 | ★ Despliegue en producción | A19 | 6 |
| A21 | ★ Piloto ciudad (E6) | A20 | 6 |
| A22 | Documentación final y lecciones aprendidas (E7) | A21 | 6 |

**Camino crítico:** A01 → A02 → A03 → A04 → A08 → A09 → A10 → A12 → A13 → A14 → A16 → A19 → A20 → A21

#### Verificación del camino crítico

El camino crítico fue determinado a partir de las dependencias y duraciones planificadas. Las actividades con holgura total igual a cero se consideran críticas.

| ID | Actividad | Duración estimada | Predecesora | Holgura | Estado |
|----|-----------|-------------------|-------------|---------|--------|
| A01 | Kick-off y acta de inicio | 1 semana | — | 0 | Crítica |
| A02 | Levantamiento de requisitos con stakeholders | 2 semanas | A01 | 0 | Crítica |
| A03 | Documentación SRS | 1 semana | A02 | 0 | Crítica |
| A04 | Diseño de arquitectura del sistema | 2 semanas | A03 | 0 | Crítica |
| A08 | Configuración entorno y CI/CD | 3 semanas | A04 | 0 | Crítica |
| A09 | Módulo de autenticación y perfiles | 2 semanas | A05, A08 | 0 | Crítica |
| A10 | Módulo ciudadanos (reportes + notificaciones) | 3 semanas | A09 | 0 | Crítica |
| A12 | Módulo administrador (rutas + estadísticas) | 2 semanas | A10 | 0 | Crítica |
| A13 | Módulo autoridades (panel + análisis) | 2 semanas | A12 | 0 | Crítica |
| A14 | Integración frontend-backend | 2 semanas | A10, A11, A12, A13 | 0 | Crítica |
| A16 | Pruebas de integración | 1 semana | A14 | 0 | Crítica |
| A19 | Corrección de defectos críticos | 1 semana | A16, A17, A18 | 0 | Crítica |
| A20 | Despliegue en producción | 1 semana | A19 | 0 | Crítica |
| A21 | Piloto ciudad (E6) | 1 semana | A20 | 0 | Crítica |

Cualquier retraso en una actividad con holgura igual a cero genera un retraso equivalente en la fecha final del proyecto, salvo que se apliquen medidas de compresión del cronograma.

---

## 6. Evaluación y control del proyecto (Cláusula 6 del PMP)

### 6.1 Plan de gestión de requisitos

- Los requisitos se documentan en el SRS y se rastrean en la tabla de trazabilidad.
- Toda solicitud de cambio de requisito pasa por el proceso de control de cambios (6.2).
- Los requisitos se priorizan con técnica MoSCoW (Must/Should/Could/Won't).

### 6.2 Plan de control de cambios de alcance

1. Se registra la solicitud de cambio (Change Request – CR).  
2. El jefe de proyecto evalúa impacto en tiempo, costo y calidad.  
3. Se presenta al docente asesor si el impacto supera 1 sprint o $50 USD.  
4. Se aprueba o rechaza y se actualiza el PMP y backlog.

### 6.3 Plan de control del cronograma

- Revisión semanal del avance real vs. planificado.
- Índice de Rendimiento del Cronograma (SPI): alerta si SPI < 0.9.
- Acciones correctivas: reasignación de recursos o reducción de alcance en sprints futuros.

### 6.4 Plan de control del presupuesto

- Reporte mensual de gasto real vs. presupuestado.
- Índice de Rendimiento de Costo (CPI): alerta si CPI < 0.9.
- Reserva de contingencia: 10 % del presupuesto total ($65 USD).

### 6.5 Plan de aseguramiento de calidad

**Métricas de calidad rastreadas continuamente:**

| Métrica | Meta | Frecuencia de medición |
|---------|------|----------------------|
| Tiempo de respuesta (búsqueda / notificación) | ≤ 2 s | Cada sprint |
| Tiempo de carga de pantalla | ≤ 3 s | Cada sprint |
| Disponibilidad del sistema | ≥ 99 % | Mensual (desde mes 3) |
| Satisfacción de usabilidad | ≥ 85 % evaluación positiva | Prueba beta (mes 5) |
| Cobertura de pruebas unitarias | ≥ 80 % | Cada sprint |
| Densidad de defectos | < 5 defectos/KLOC | Cada sprint |
| Tiempo de actividad (uptime) | ≥ 99 % | Continuo (Grafana) |

**Actividades de aseguramiento:**
- Revisión de código por pares (pull request obligatorio).
- Análisis estático automático en CI/CD (ESLint).
- Ejecución automática de suite de pruebas en cada push.
- Revisión periódica de métricas de mantenibilidad del código.

### 6.6 Plan de cierre del proyecto

| Actividad de cierre | Responsable | Cuándo |
|---------------------|-------------|--------|
| Aceptación formal del sistema por cliente piloto | Jefe de Proyecto | Semana 23 |
| Documentación de lecciones aprendidas | Todo el equipo | Semana 23 |
| Versión final del PMP | Jefe de Proyecto | Semana 24 |
| Archivo de todos los artefactos del proyecto | QA | Semana 24 |
| Presentación final al docente | Todo el equipo | Semana 24 |

---

## 7. Entrega del producto (Cláusula 7 del PMP)

| Componente | Descripción | Destinatario |
|------------|-------------|-------------|
| Código fuente | Repositorio GitHub completo | Equipo + Docente |
| Aplicación web | URL de producción | Municipio piloto |
| Aplicación móvil | APK Android + TestFlight iOS | Usuarios piloto |
| Manual de usuario | Guía por tipo de actor | Ciudadanos / Admins / Autoridades |
| Manual de despliegue | Instrucciones técnicas de instalación | Equipo técnico municipio |
| Informe final de calidad | Métricas, resultados de pruebas, cobertura | Docente |

---

## 8. Planes de procesos de soporte (Cláusula 8 del PMP)

### 8.1 Gestión de decisiones

Las decisiones técnicas o de gestión con impacto mayor se documentan con el formato:  
**[Decisión] – [Alternativas consideradas] – [Criterio de selección] – [Fecha] – [Responsable]**

Decisiones significativas se revisan en la reunión semanal de equipo y se archivan en el repositorio del proyecto.

### 8.2 Gestión de riesgos

**Proceso:** Identificar → Analizar → Planificar respuesta → Monitorear

**Registro de riesgos:**

| ID | Riesgo | Prob. | Impacto | Severidad | Estrategia | Responsable |
|----|--------|-------|---------|-----------|------------|-------------|
| R01 | Rotación o baja disponibilidad de un miembro del equipo | Media | Alto | Alto | Mitigar: documentación continua; backup de conocimiento | Jefe Proyecto |
| R02 | Requisitos ambiguos o cambiantes por parte del municipio piloto | Alta | Alto | Alto | Mitigar: sesiones de validación frecuentes; CR formal | Jefe Proyecto |
| R03 | Fallas en infraestructura cloud | Baja | Alto | Medio | Contingencia: plan de recuperación, backups diarios | Líder Backend |
| R04 | Rendimiento insuficiente (tiempos de respuesta > 3 s) | Media | Medio | Medio | Mitigar: pruebas de carga con k6 desde mes 4 | QA |
| R05 | Baja adopción por ciudadanos en el piloto | Media | Medio | Medio | Mitigar: campaña de comunicación y onboarding simple | UX/UI |
| R06 | Deuda técnica acumulada que retrasa entregas | Media | Alto | Alto | Mitigar: revisiones de código en cada sprint, refactoring planificado | Líderes técnicos |
| R07 | Incumplimiento del plazo de 6 meses | Baja | Alto | Alto | Contingencia: reducir alcance de módulo autoridades a MVP | Jefe Proyecto |

### 8.3 Gestión de configuración

- **Repositorio:** GitHub (rama `main` protegida; PRs requeridos).  
- **Estrategia de ramas:** GitFlow (`main`, `develop`, `feature/*`, `hotfix/*`).  
- **Versionado:** Semántico (MAJOR.MINOR.PATCH).  
- **Baseline:** Se establece baseline al cierre de cada fase.  
- **Control de cambios:** Todo cambio a baseline requiere PR aprobado por ≥ 1 revisor.  
- **CCB (Change Control Board):** Jefe de Proyecto + Líder técnico afectado.

### 8.4 Gestión de la información

| Tipo de información | Repositorio | Acceso | Frecuencia de actualización |
|--------------------|-------------|--------|----------------------------|
| Código fuente | GitHub | Equipo | Continuo |
| Documentación técnica | GitHub /docs | Equipo | Por sprint |
| Backlog y tareas | GitHub Projects | Equipo | Semanal |
| Reportes de calidad | Carpeta compartida | Equipo + Docente | Por sprint |
| Comunicaciones formales | Email institucional | Equipo + Docente | Según necesidad |
| Actas de reunión | Notion / carpeta compartida | Equipo | Después de cada reunión |

**Política de retención:** Todos los artefactos del proyecto se conservan en repositorio GitHub por mínimo 2 años después del cierre.

### 8.5 Documentación

Documentos mínimos requeridos:

| Documento | Versión mínima | Responsable |
|-----------|---------------|-------------|
| PMP (este documento) | 1.0 | Jefe de Proyecto |
| Especificación de Requisitos (SRS) | 1.0 | Todo el equipo |
| Documento de Arquitectura | 1.0 | Líderes técnicos |
| Plan de Pruebas | 1.0 | QA |
| Manual de Usuario | 1.0 | UX/UI + QA |
| Informe final de calidad | 1.0 | QA |

---

## Apéndice A – Matriz de trazabilidad de requisitos (extracto)

| ID Req | Descripción | Tipo | Módulo | Prueba asociada |
|--------|-------------|------|--------|-----------------|
| RF-01 | Creación de perfil de ciudadano | Funcional | Ciudadanos | TC-001 |
| RF-02 | Reporte de necesidad de recolección | Funcional | Ciudadanos | TC-002 |
| RF-03 | Notificaciones en tiempo real | Funcional | Ciudadanos | TC-003 |
| RF-04 | Gestión de rutas de recolección | Funcional | Administrador | TC-010 |
| RF-05 | Estadísticas en tiempo real | Funcional | Administrador | TC-011 |
| RF-06 | Panel de análisis histórico | Funcional | Autoridades | TC-020 |
| RNF-01 | Tiempo de carga ≤ 3 s | No funcional (rendimiento) | Transversal | TC-P-001 |
| RNF-02 | Disponibilidad ≥ 99.9 % | No funcional (disponibilidad) | Infraestructura | TC-P-002 |
| RNF-03 | Accesibilidad WCAG 2.1 AA | No funcional (usabilidad) | Transversal | TC-U-001 |
| RNF-04 | Compatibilidad Android ≥ 8.0 e iOS ≥ 13 | No funcional (compatibilidad) | Móvil | TC-C-001 |
| RCA-01 | Respuesta ≤ 2 s para búsqueda y notificación | Calidad | Transversal | TC-P-003 |
| RCA-02 | Satisfacción usabilidad ≥ 85 % | Calidad | Transversal | TC-U-002 |
| RCA-03 | Cobertura pruebas unitarias ≥ 80 % | Calidad | Transversal | Cobertura CI/CD |

---

*Documento elaborado bajo los lineamientos de ISO/IEC/IEEE 16326:2009 para el curso Calidad de Software 2025-2.*  
*Versión 1.0 — Junio 2026*
