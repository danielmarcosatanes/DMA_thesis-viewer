# 🔬 DMA Thesis Viewer

![Status: Thesis Defended](https://img.shields.io/badge/Status-Thesis%20Defended-success?style=flat-square) &nbsp; ![Made with JSmol](https://img.shields.io/badge/Rendered%20with-JSmol-blue?style=flat-square) &nbsp; ![Field: Computational Chemistry](https://img.shields.io/badge/Field-Computational%20Chemistry-orange?style=flat-square)

Este repositorio alberga el visor interactivo 3D desarrollado como complemento para la tesis doctoral de **Daniel Marcos Atanes**:

> **"Ligand-controlled selective C–H borylations using iridium catalysts"**  
> *CiQUS - Universidad de Santiago de Compostela (2025)*

---

## 🌐 Visualización Online

Puedes acceder a la versión interactiva directamente en tu navegador aquí:  
👉 **[danielmarcosatanes.github.io/DMA_thesis-viewer](https://danielmarcosatanes.github.io/DMA_thesis-viewer/)**

---

## 📖 Descripción

Esta herramienta permite a los lectores de la tesis explorar de forma interactiva las estructuras moleculares clave, incluyendo:

*   **Estados de Transición (TS):** Visualización de las geometrías de activación.
*   **Intermedios Catalíticos:** Complejos de Iridio con ligandos modificados.
*   **Interacciones No Covalentes:** Análisis visual de la selectividad.

### 🎮 Instrucciones de Uso

1.  **Selección:** Utiliza el menú lateral para cargar las moléculas.
2.  **Manipulación:** 
    *   `Click Izquierdo + Arrastrar`: Rotar.
    *   `Rueda del Ratón`: Zoom.
    *   `Click Derecho`: Menú avanzado (medir distancias, ángulos).
3.  **Medidas:** Doble clic en dos átomos para medir la distancia de enlace.

---

## 🛠️ Detalles Técnicos

*   **Motor:** [JSmol](http://jsmol.sourceforge.net/) (HTML5/JavaScript).
*   **Datos:** Coordenadas extraídas de cálculos realizados con **Gaussian 16**.
*   **Interfaz:** Diseño minimalista optimizado para visualización científica.

---

## 📂 Estructura

*   `/molecules`: Archivos de coordenadas (.xyz / .pdb).
*   `/j2s`: Core del motor JSmol.
*   `g16_quotes.txt`: Citas de Gaussian 16 integradas en la interfaz.

---

## 🎓 Créditos

**Autor:** Daniel Marcos Atanes  
**Institución:** [CiQUS](https://www.usc.es/ciqus/es) - Centro Singular de Investigación en Química Biolóxica y Materiais Moleculares.
