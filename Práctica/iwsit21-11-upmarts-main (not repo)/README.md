# 🎨 UPM Arts - Entrega 1: Requisitos y Análisis 🖌️

¡Bienvenido al repositorio de la primera entrega de **UPM Arts**! Este proyecto se desarrolla en el marco de la asignatura de **Fundamentos de Ingeniería del Software (FIS)** del curso 2025-2026.

---

## 👥 Equipo de Desarrollo

| Nombre      | Rol                   |
|-------------|-----------------------|
| `[MANZANARO CARABALLO PABLO]`      | Líder de Requisitos   |
| `[MARTINEZ SEBASTIA NACHO]`        | Líder de Análisis     |
| `[NAUTIYAL BHATT NINAD]`           | Integrante            |
| `[VELISLAVOVA TSEKOVA CRISTIANA]`  | Integrante            |

**Grupo de Prácticas:** `[IWSIT21-11]`

---

## 📂 Estructura del Repositorio

A continuación se detalla la estructura de directorios de esta entrega, siguiendo las directrices del Anexo: Estructura del repositorio.

```
/
├── Entrega 1/
│   ├── Prototipo/                         # Prototipo funcional (Mockup)
│   │   └── Mockup_UPM_Arts.pptx
│   └── Modelado/
│       ├── StarUML/                       # Proyecto fuente de StarUML
│       │   └── UPM_Arts_Analisis.uml
│       ├── Diagramas/
│       │   ├── Casos_de_Uso/              # Diagramas de casos de uso (.png)
│       │   ├── Descripciones_Casos_de_Uso/ # Descripciones extendidas (.pdf)
│       │   └── Diagrama_Clases/           # Diagrama de clases de análisis (.png)
│       └── PDF Recopilatorio/             # Documento único obligatorio
│           └── UPM_Arts_Modelado_Completo.pdf
└── README.md                              # ¡Estás aquí!
```

---

## 🛠️ Especificación de Requisitos

La gestión y especificación detallada de los requisitos se encuentra en la **Wiki de Redmine** del proyecto, siguiendo el estándar `IEEE 830`.

### ✨ Reglas de Negocio Críticas (UPM Arts Logic)

-   **Identificación**: Validación automática mediante UPM Authenticator según el dominio del correo institucional.
-   **Descuentos**:
    -   **Estudiantes UPM**: `25%` fijo.
    -   **Personal UPM**: `25%` base + `3%` por año de antigüedad (máximo `50%`).
    -   **Externos**: Sin descuento.
-   **Seguridad**: Contraseñas de al menos 12 caracteres, incluyendo mayúscula, minúscula y número.
-   **Integridad**: Un usuario no puede tener doble rol (Estudiante y Personal simultáneamente).

---

## 📊 Modelado y Análisis

El análisis del sistema se ha realizado utilizando **UML 2.0** con la herramienta **StarUML™**.

-   **Diagramas de Casos de Uso**: Organizados por subconjuntos funcionales para una mejor comprensión.
-   **Descripciones Extendidas**: Cada miembro del equipo ha detallado un caso de uso, especificando flujos básicos y alternativos.
-   **Diagrama de Clases de Análisis**: Representación conceptual completa que modela las entidades clave del sistema.

---

## 🔗 Enlaces de Interés

| Plataforma      | Enlace                                      |
|-----------------|---------------------------------------------|
| 🔴 **Redmine**  | `[https://fis.etsisi.upm.es/projects/iwsit21-11-upmarts]`               |
| 🔵 **GitLab**   | `[https://gitlab.etsisi.upm.es/wincynin/iwsit21-11-upmarts]`|

---

