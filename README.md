# ISW-G9-4K1-2026

## Plan de Gestión de Configuración (SCMP)

Repositorio del **Grupo 9 (Curso 4K1 - Año 2026)** para la organización colaborativa de los contenidos de la materia **Ingeniería y Calidad de Software (UTN-FRC)**.

### Integrantes del Grupo

* **Nombre:** Calderón, Ana Victoria - **Legajo:** 402851 - **Usuario:** viccalderon
* **Nombre:** Díaz, Brisa Abigaíl - **Legajo:** 97287 - **Usuario:** BrisaDiaz
* **Nombre:** Escudero Olivera, Matías Rubén - **Legajo:** 402434  - **Usuario:** escuderomann
* **Nombre:** Fuertes Galera, Emiliano - **Legajo:** 402186 - **Usuario:** emolianito
* **Nombre:** Galetto, Fiorella - **Legajo:** 400305 - **Usuario:** fiorellag26
* **Nombre:** Gorosito, Tamara - **Legajo:** 90740 - **Usuario:** tamaraMG
* **Nombre:** Guevara Lopez, Joaquin - **Legajo:** 300543 - **Usuario:** joaquinsinho
* **Nombre:** Juri Romero, Agustina - **Legajo:** 95317 - **Usuario:** agustinajuri18
* **Nombre:** Linaza, Camila - **Legajo:** 402370 - **Usuario:** camilinaza08
* **Nombre:** Maccio, Tomás Agustín - **Legajo:** 400057 - **Usuario:** maccio-bit
* **Nombre:** Pizarro, José Francisco - **Legajo:** 402123 - **Usuario:**  franpi19
* **Nombre:** Rigonatto, Enzo - **Legajo:** 400629 - **Usuario:** rigonattoenzo 
* **Nombre:** Torrens Valsagna, Francisco - **Legajo:** 401939 - **Usuario:** frantorrens

---

### Estructura del Repositorio

La estructura del repositorio Trunk-Based se rediseña para reflejar físicamente esta taxonomía en el tronco activo de trabajo colaborativo:

```text
/ (Raíz del Repositorio)
├── README.md                           (Producción Propia - Plan de SCM)
├── /Planificacion                      (Espacio de control y planificación del grupo)
│   ├── ISW_Calendario_Estudio.xlsx     (Producción Propia - Cronograma de estudio adaptado)
│   └── ISW_Roles_Responsabilidades.pdf (Producción Propia - Asignación de roles SCM)
├── /Tronco_Activo                      (Entorno colaborativo diario de trabajo)
│   ├── /Material_Catedra               (De Cátedra - Insumos estáticos provistos por docentes)
│   │   ├── ISW_Programa_Asignatura.pdf (De Cátedra - Programa oficial de la asignatura)
│   │   ├── ISW_Cronograma_Oficial.xlsx (De Cátedra - Planificación de clases y fechas clave)
│   │   ├── /Bibliografía               (De Cátedra - Libros y textos de lectura obligatoria)
│   │   │   └── ISW_Bibliografia_U<<NN>>_<<Nombre>>.pdf
│   │   ├── /Presentaciones             (De Cátedra - Diapositivas teóricas de las clases)
│   │   │   └── ISW_PPT_<<Tema>>.pdf
│   │   ├── /Consignas                  (De Cátedra - Enunciados oficiales de trabajos y actividades)
│   │   │   ├── ISW_Consignas_TPs_Evaluables.pdf
│   │   │   ├── ISW_Consignas_TPs_Resueltos.pdf
│   │   │   └── ISW_Consignas_Trabajos_Investigacion.pdf
│   │   └── /Templates                  (De Cátedra - Plantillas estandarizadas para documentos)
│   │       └── ISW_Template_<<Nombre>>.xlsx/docx
│   ├── /Material_Clase                 (De Clase - Dinámicas y notas espontáneas del aula)
│   │   ├── ISW_Notas_<<DDMM>>.pdf       (De Clase - Apuntes y toma de notas tomadas durante la clase)
│   │   └── ISW_Ejercicio<<NN>>_<<Tema>>.pdf (De Clase - Soluciones a TPs no evaluables y prácticas)
│   └── /Produccion_Propia              (De Producción Propia - Entregables consolidados por el grupo)
│       ├── /Resumenes                  (De Producción Propia - Resúmenes teóricos para exámenes)
│       │   └── ISW_Resumen_U<<NN>>_<<Tema>>.pdf
│       ├── /Resoluciones_TPs           (De Producción Propia - Carpetas contenedoras de entregables)
│       │   └── /ISW_TP<<NN>>_<<NombreTP>>
              └── ISW_Resolucion_TP<<NN>>_<<NombreTP>>.pdf
│             └── ISW_MaterialExtra_TP<<NN>>_<<NombreTP>>.zip/rar
│       └── /Trabajos_Investigacion     (De Producción Propia - Informes y presentaciones de investigación)
│           └── ISW_Trabajos_Investigacion<<NN>>_<<Nombre>>.pdf

```

---

### Matriz de Identificación de Ítems de Configuración (SCIs)

Para mantener la trazabilidad e integridad de los contenidos, cada archivo se identifica y clasifica unívocamente según el nuevo criterio:

| Nombre del SCI | Regla de Nombrado Única | Ubicación Física en Repositorio | Clasificación SCM | Propósito / Justificación SCM |
| --- | --- | --- | --- | --- |
| **README principal** | `README.md` | `/` (Raíz) | **De Producción Propia** | Plan de Gestión de Configuración (SCMP) y políticas del grupo. |
| **Calendario de Estudio** | `ISW_Calendario_Estudio.xlsx` | `/Planificacion/` | **De Producción Propia** | Planificación de actividades del grupo basada en hitos académicos. |
| **Matriz de Roles** | `ISW_Roles_Responsabilidades.pdf` | `/Planificacion/` | **De Producción Propia** | Asignación interna de roles SCM y responsabilidades. |
| **Programa Oficial** | `ISW_Programa_Asignatura.pdf` | `/Tronco_Activo/Material_Catedra/` | **De Cátedra** | Documento oficial que define el alcance global de la asignatura. |
| **Cronograma Oficial** | `ISW_Cronograma_Oficial.xlsx` | `/Tronco_Activo/Material_Catedra/` | **De Cátedra** | Planificación oficial de clases, temas y fechas límite. |
| **Bibliografía** | `ISW_Bibliografia_U<<NN>>_<<Nombre>>.pdf` | `/Tronco_Activo/Material_Catedra/Bibliografía/` | **De Cátedra** | Material de lectura obligatoria provisto por la cátedra. |
| **Diapositivas** | `ISW_PPT_<<Tema>>.pdf` | `/Tronco_Activo/Material_Catedra/Presentaciones/` | **De Cátedra** | Presentaciones de clase oficiales de la cátedra. |
| **Consignas TPs Evaluables** | `ISW_Consignas_TPs_Evaluables.pdf` | `/Tronco_Activo/Material_Catedra/Consignas/` | **De Cátedra** | Especificación de requerimientos para TPs evaluables. |
| **Consignas TPs Resueltos** | `ISW_Consignas_TPs_Resueltos.pdf` | `/Tronco_Activo/Material_Catedra/Consignas/` | **De Cátedra** | Enunciados de ejercicios prácticos resueltos en clase. |
| **Consignas Investigación** | `ISW_Consignas_Trabajos_Investigacion.pdf` | `/Tronco_Activo/Material_Catedra/Consignas/` | **De Cátedra** | Enunciados y pautas para los trabajos de investigación. |
| **Plantillas de Cátedra** | `ISW_Template_<<Nombre>>.xlsx/docx` | `/Tronco_Activo/Material_Catedra/Templates/` | **De Cátedra** | Plantillas base estandarizadas para la entrega de trabajos. |
| **Toma de Notas de Clase** | `ISW_Notas_<<DDMM>>.pdf` | `/Tronco_Activo/Material_Clase/` | **De Clase** | Registro dinámico de conceptos teóricos capturados en clase. |
| **Ejercicios de Clase** | `ISW_Ejercicio<<NN>>_<<Tema>>.pdf` | `/Tronco_Activo/Material_Clase/` | **De Clase** | Resolución de trabajos prácticos no evaluables o ejercicios de aula. |
| **Resúmenes Teóricos** | `ISW_Resumen_U<<NN>>_<<Tema>>.pdf` | `/Tronco_Activo/Produccion_Propia/Resumenes/` | **De Producción Propia** | Resúmenes teóricos elaborados para exámenes parciales/finales. |
| **Resolución TPs Evaluables** | `ISW_Resolucion_TP<<NN>>_<<NombreTP>>.pdf` | `/Tronco_Activo/Produccion_Propia/Resoluciones_TPs/ISW_TP<<NN>>_<<NombreTP>>` | **De Producción Propia** | Resolución de Trabajos Prácticos Evaluables |
| **Material Extra TPs Evaluables** | `ISW_MaterialExtra_TP<<NN>>_<<NombreTP>>.rar/zip` | `/Tronco_Activo/Produccion_Propia/Resoluciones_TPs/ISW_TP<<NN>>_<<NombreTP>>` | **De Producción Propia** | Material extra que fue utilizado durante la realización del trabajo práctico. |
| **Trabajos de Investigación** | `ISW_Trabajos_Investigacion<<NN>>_<<Nombre>>.pdf` | `/Tronco_Activo/Produccion_Propia/Trabajos_Investigacion/` | **De Producción Propia** | Informes de investigación técnica elaborados por el equipo. |

---

### Criterios de Línea Base Académica

La **Línea Base (Baseline)** se establece en hitos de evaluación formal y consolida exclusivamente ítems de **Producción Propia** que han superado las auditorías de configuración. Se formalizará de la siguiente manera:

#### 1. Formato Estándar del Baseline Tag

El etiquetado formal de las líneas base en Git sigue la siguiente sintaxis:

```text
LB_<<NN>>_<<HITO>>_v<<X.Y>>

```

* **`LB`**: Prefijo fijo que identifica una Línea Base aprobada.
* **`<<NN>>`**: Número de secuencia del hito de evaluación (ej. `01`, `02`).
* **`<<HITO>>`**: Nombre descriptivo en Mayúsculas del hito académico (ej. `PARCIAL1`).
* **`v<<X.Y>>`**: Versión del entregable. `X` representa la versión mayor aprobada (comienza en `1.0`), e `Y` incrementa si se realiza un re-entregable o corrección post-auditoría docentes (ej. `v1.1`).

**Ejemplos de Tags Válidos:**

* `LB_01_PARCIAL1_v1.0`
* `LB_02_PARCIAL2_v1.0`
* `LB_03_CIERRE_MATERIA_v1.0`

---

#### 2. Hitos de Línea Base

| Identificador | Nombre del Hito | Descripción del Contenido | Criterio 
| :--- | :--- | :--- | :--- |
| **LB_01** | `PARCIAL1` | Versión aprobada de resúmenes U01-U03, resoluciones de TPs evaluables de la primera etapa y guías prácticas complementarias. | Al finalizar la rendición del 1er Parcial.
| **LB_02** | `PARCIAL2` | Versión aprobada de resúmenes U02-U04, resoluciones de TPs evaluables y guías prácticas complementarias.| Al finalizar la rendición del 2do Parcial.
| **LB_03** | `CIERRE_MATERIA` |  Entregables finales de los Trabajos de Investigación Grupal y portafolio grupal final consolidado. | Al completarse las exposiciones de los TIGs, previo al cierre definitivo del ciclo lectivo. 

---

#### 3. Procedimiento de Formalización

1. **Auditoría Previa**: Al alcanzar la fecha límite del hito, el Administrador de Configuración efectúa la auditoría física (PCA) y funcional (FCA) sobre el tronco de trabajo.
2. **Creación del Tag Anotado**: Se genera la etiqueta anotada en Git haciendo referencia al commit auditado y firmado:
```bash
git tag -a LB_01_PARCIAL1_v1.0 -m "Línea Base LB_01: Consolida entrega de Primer Parcial y TPs evaluables 01 a 04."
```


3. **Publicación**: Se sincroniza el tag con el servidor remoto para congelar formalmente el estado de la entrega:
```bash
git push origin LB_01_PARCIAL1_v1.0

```



---

### Flujo de Control de Cambios Ágil

Para evitar la burocracia innecesaria de un comité tradicional de control de cambios, el grupo aplica políticas explícitas en el tablero Kanban:

* **Clase 1 (Menor - Auto-aprobado)**: Corrección de erratas, formato u ortografía en apuntes teóricos individuales. Push directo al tronco.
* **Clase 2 (Medio - Revisión por Par)**: Adición de contenido relevante o cambios estructurales a resúmenes teóricos compartidos. Requiere un *Pull Request* revisado y aprobado por otro integrante antes de integrarse.
* **Clase 3 (Mayor - Consenso Grupal)**: Consolidación final de Trabajos Prácticos y definición de Líneas Base oficiales. Requiere consenso unánime del equipo.

---

### Auditorías de Configuración para Aseguramiento de la Calidad

* **PCA (Auditoría Física de Configuración)**: El Administrador de Configuración del grupo valida periódicamente que los archivos estén en las carpetas correctas del repositorio, que el nombrado sea consistente con la Matriz de Identificación de Ítems de Configuración (SCIs) y que el contenido del repositorio coincida exactamente con el contenido estipulado para dicha Línea Base.
* **FCA (Auditoría Funcional de Configuración)**: Un integrante diferente al autor de un TP realiza una verificación funcional (auditoría del entregable) controlando el contenido versus el enunciado oficial de la cátedra para asegurar que cubra el 100% de los requisitos y criterios de evaluación antes de congelar la entrega.
