# 🏥 Sistema de Gestión de Inventario y Abastecimiento — Farmacias Peruanas S.A. - GRUPO 2

> **Curso:** Diseño e Implementación de Arquitectura Empresarial — Sección 22840
> **Universidad:** Universidad Tecnológica del Perú (UTP)
> **Herramienta de Modelado:** Visual Paradigm

---

## 📌 Descripción del Proyecto

Este repositorio documenta el análisis y diseño del **Sistema de Gestión de Inventario y Abastecimiento para Farmacias Peruanas S.A.**, una solución orientada a optimizar el control de stock, el proceso de reabastecimiento y la distribución de productos farmacéuticos a nivel de red de sucursales y centro de distribución.

El sistema aborda problemáticas críticas como los quiebres de stock, la planificación de demanda y la generación de reportes de inventario en tiempo real, alineando los procesos de negocio con una arquitectura empresarial robusta bajo los lineamientos de **RUP**, **TOGAF** y **UML**.

---

## 🎯 Objetivo del Repositorio

Centralizar y versionar todos los **diagramas de análisis y diseño** del sistema, elaborados con la herramienta **Visual Paradigm**, organizados por tipo de diagrama según las fases del proceso de desarrollo basado en RUP.

> ⚠️ **Nota:** Este repositorio contiene exclusivamente los diagramas de análisis y diseño del sistema (modelado del negocio, requerimientos, arquitectura y diseño). No incluye código fuente.

---

## 🛠️ Herramienta Utilizada

| Herramienta | Propósito |
|---|---|
| **Visual Paradigm** | Elaboración de todos los diagramas UML y de negocio |
| **Git + GitHub** | Control de versiones y repositorio central |
| **RUP** | Metodología de desarrollo iterativo e incremental |
| **TOGAF** | Framework de arquitectura empresarial |
| **UML** | Estándar de modelado de sistemas |

---

## 📁 Organización de Carpetas

```
📦 Avance-de-Proyecto
 ┣ 📂 Diagrama_Casos_Uso_Negocio_CUN/
 ┃ ┣ 📂 ACTORES_NEGOCIO/
 ┃ ┣ 📂 CASOS_USO_NEGOCIO/
 ┃ ┗ 📂 Diagrama_Caso_Uso_Negocio/
 ┣ 📂 Diagrama_Actividades/
 ┃ ┣ 📂 CUN-01_Realizar_venta_de_productos/
 ┃ ┣ 📂 CUN-02_Monitorear_stock_de_productos/
 ┃ ┣ 📂 CUN-03_Gestionar_reabastecimiento_de_productos/
 ┃ ┣ 📂 CUN-04_Detectar_quiebres_de_stock/
 ┃ ┣ 📂 CUN-05_Coordinar_distribucion_desde_Centro_Distribucion/
 ┃ ┣ 📂 CUN-06_Generar_reportes_de_inventario/
 ┃ ┗ 📂 CUN-07_Planificar_demanda_de_productos/
 ┣ 📂 Diagrama_Clases/
 ┃ ┗ 📂 Diagrama_Dominio_Negocio/
 ┣ 📂 Diagrama_Casos_Uso_Farmacias_Peruanas/
 ┃ ┗ 📂 Diagrama_Caso_Uso_Sistema_Gestion_Inventario_Abastecimiento/
 ┣ 📂 Diagrama_Contexto/
 ┃ ┗ 📂 Diagrama_Contexto_Farmacias_Peruanas/
 ┣ 📂 Diagrama_Clases_Diseno/
 ┃ ┗ 📂 Diagrama_Clases_Diseno_Farmacias_Peruanas/
 ┗ 📄 README.md
```

---

## 🗺️ Descripción de Diagramas

### 📌 Diagrama de Casos de Uso del Negocio (CUN)
Modela los actores y procesos principales del negocio de Farmacias Peruanas S.A., identificando cómo los distintos roles interactúan con los procesos de inventario y abastecimiento.

| Subcarpeta | Contenido |
|---|---|
| `ACTORES_NEGOCIO/` | Identificación y descripción de los actores del negocio |
| `CASOS_USO_NEGOCIO/` | Especificación de cada caso de uso del negocio |
| `Diagrama_Caso_Uso_Negocio/` | Diagrama UML de casos de uso del negocio |

### 📌 Diagramas de Actividades
Representa el flujo de actividades de cada caso de uso del negocio, mostrando la secuencia lógica de acciones, decisiones y responsables.

| Carpeta | Proceso modelado |
|---|---|
| `CUN-01` | Realizar venta de productos |
| `CUN-02` | Monitorear stock de productos |
| `CUN-03` | Gestionar reabastecimiento de productos |
| `CUN-04` | Detectar quiebres de stock |
| `CUN-05` | Coordinar distribución desde Centro de Distribución |
| `CUN-06` | Generar reportes de inventario |
| `CUN-07` | Planificar demanda de productos |

### 📌 Diagrama de Clases — Dominio del Negocio
Modelo conceptual de las clases y relaciones del dominio del negocio, identificando las entidades clave del sistema de inventario y abastecimiento.

### 📌 Diagrama de Casos de Uso del Sistema
Especifica los casos de uso del **Sistema de Gestión de Inventario y Abastecimiento**, mostrando las interacciones entre actores del sistema y sus funcionalidades.

### 📌 Diagrama de Contexto
Muestra el sistema como una caja negra, identificando los agentes externos (actores, sistemas) que interactúan con él y los flujos de información.

### 📌 Diagrama de Clases de Diseño
Modelo detallado de las clases del sistema con atributos, métodos y relaciones, representando la arquitectura de software de la solución.

---

## 💻 Comandos Git Bash para Crear la Estructura

Si deseas replicar la estructura localmente, ejecuta los siguientes comandos en **Git Bash**:

```bash
# Crear carpetas del Diagrama de Casos de Uso del Negocio
mkdir -p Diagrama_Casos_Uso_Negocio_CUN/ACTORES_NEGOCIO
mkdir -p Diagrama_Casos_Uso_Negocio_CUN/CASOS_USO_NEGOCIO
mkdir -p Diagrama_Casos_Uso_Negocio_CUN/Diagrama_Caso_Uso_Negocio

# Crear carpetas del Diagrama de Actividades
mkdir -p Diagrama_Actividades/CUN-01_Realizar_venta_de_productos
mkdir -p Diagrama_Actividades/CUN-02_Monitorear_stock_de_productos
mkdir -p Diagrama_Actividades/CUN-03_Gestionar_reabastecimiento_de_productos
mkdir -p Diagrama_Actividades/CUN-04_Detectar_quiebres_de_stock
mkdir -p Diagrama_Actividades/CUN-05_Coordinar_distribucion_desde_Centro_Distribucion
mkdir -p Diagrama_Actividades/CUN-06_Generar_reportes_de_inventario
mkdir -p Diagrama_Actividades/CUN-07_Planificar_demanda_de_productos

# Crear carpetas del Diagrama de Clases
mkdir -p Diagrama_Clases/Diagrama_Dominio_Negocio

# Crear carpetas del Diagrama de Casos de Uso del Sistema
mkdir -p Diagrama_Casos_Uso_Farmacias_Peruanas/Diagrama_Caso_Uso_Sistema_Gestion_Inventario_Abastecimiento

# Crear carpetas del Diagrama de Contexto
mkdir -p Diagrama_Contexto/Diagrama_Contexto_Farmacias_Peruanas

# Crear carpetas del Diagrama de Clases de Diseño
mkdir -p Diagrama_Clases_Diseno/Diagrama_Clases_Diseno_Farmacias_Peruanas

echo "✅ Estructura de carpetas creada exitosamente."
```

---

## 👥 Integrantes del Equipo

| N° | Apellidos y Nombres | Código |
|---|---|---|
| 1 | Tafur Cortez, Claudio Stevenson | U22229800 |
| 2 | Lopez Pacherres, Bryan Armando | U22305277 |
| 3 | Martínez Muñoz, Jeremy Alexander | U22241773 |
| 4 | Chauca Díaz, Juan Carlos | U23243647 |

---

## 📋 Instrucciones para Subir Diagramas

1. Exporta el diagrama desde **Visual Paradigm** en formato `.png` o `.pdf`
2. Nómbralo de forma descriptiva, por ejemplo: `CUN-01_Diagrama_Actividades_v1.png`
3. Colócalo dentro de la carpeta correspondiente según el tipo de diagrama
4. Realiza un commit con un mensaje descriptivo:
   ```bash
   git add .
   git commit -m "feat: agregar diagrama de actividades CUN-01 Realizar venta"
   git push origin main
   ```

---

## 📌 Estado del Proyecto

| Entregable | Descripción | Estado |
|---|---|---|
| **APF1** | Modelado del Negocio + Ingeniería de Requerimientos | PROCESADO |
| **APF2** | Arquitectura del Sistema | ⬜ Pendiente |
| **PROY** | Proyecto Final completo | ⬜ Pendiente |

---

*Repositorio desarrollado para el curso de Diseño e Implementación de Arquitectura Empresarial — UTP, Sección 22840.*
