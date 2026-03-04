<div align="center">
  <h1>🚀 OptimizerStudio v2.0.0</h1>
  <p><b>Herramienta Educativa para la Programación Lineal y Optimización</b></p>

  [![Version](https://img.shields.io/badge/Versión-2.0.0-blue.svg)]()
  [![OS - Windows](https://img.shields.io/badge/OS-Windows-blue?logo=windows)]()
  [![OS - macOS](https://img.shields.io/badge/OS-macOS-black?logo=apple)]()
  [![GitHub issues](https://img.shields.io/github/issues/IsaacDev2024/OptimizerStudio)](https://github.com/IsaacDev2024/OptimizerStudio/issues)

  <p align="center">
    <i>Software desarrollado para facilitar la entrada de datos, el procesamiento de modelos y la interpretación de resultados mediante algoritmos clásicos de la investigación de operaciones.</i>
  </p>
</div>

---

## 📖 ¿Qué es OptimizerStudio?

**OptimizerStudio** es una aplicación de escritorio desarrollada de forma independiente por estudiantes de Ingeniería de Sistemas y Computación. Está diseñada como una herramienta funcional, accesible e intuitiva de apoyo educativo para que cualquier usuario pueda resolver problemas de optimización y programación lineal de forma guiada en pocos pasos, sin necesidad de conocimientos avanzados en programación.

A través de métodos clásicos como el **Simplex**, **Ramificación y Acotación**, el método **Húngaro** y la **Aproximación de Vogel**, se obtienen soluciones óptimas detalladas, fomentando el aprendizaje.

## ✨ Características y Módulos

La interfaz está organizada de forma limpia mediante módulos especializados:

- 🧮 **Programación Lineal (Método Simplex):** Resuelve problemas de maximización y minimización. Incluye detección automática de casos especiales (infactibilidad, solución no acotada, óptimos alternos y degeneración). Soporta variables negativas (libres, con cota superior/inferior).
- 🌳 **Programación Lineal Entera (Ramificación y Acotación):** Soluciona modelos con restricciones de integralidad, permitiendo visualizar la solución candidata, el resumen o todos los tableados generados paso a paso.
- 🚚 **Problemas de Transporte (Vogel + MODI):** Encuentra la distribución óptima desde múltiples orígenes hacia múltiples destinos minimizando costos.
- 🎯 **Problemas de Asignación (Húngaro):** Asignación óptima de trabajadores a tareas (para maximizar beneficios o minimizar costos).
- 📈 **Análisis de Sensibilidad:** Evalúa cómo cambian las soluciones óptimas ante variaciones en la función objetivo o en las restricciones.
- 🔄 **Programación Dual:** Resuelve problemas duales directamente o transforma un problema primal a su respectivo modelo dual automáticamente para luego evaluarlo.

---

## ⚙️ Instalación

La aplicación es un ejecutable autónomo. **No se requiere** instalar Python, librerías externas adicionales ni bases de datos.

**📥 Descarga la última versión:** Todos los archivos de instalación están disponibles en la sección [Releases de nuestro repositorio en GitHub](https://github.com/IsaacDev2024/OptimizerStudio/releases).

### 🍎 macOS

*Requisitos: Procesadores Apple Silicon (M1, ... , M5) y macOS 11 (Big Sur) o superior.*

1. Ve a la página de [Releases](https://github.com/IsaacDev2024/OptimizerStudio/releases) y descarga el archivo `.dmg` más reciente.
2. Ábrelo y arrastra la app a tu carpeta de **Aplicaciones**.
3. Ejecuta la aplicación.

> **⚠️ Solución a "Desarrollador no verificado":**
> Al ser un proyecto estudiantil independiente y sin certificación comercial de Apple, macOS podría bloquear su primera ejecución (indicando que "no puede ser verificado").
> **Solución:** Ve a `Configuración del Sistema > Privacidad y Seguridad` (o Seguridad y Privacidad en versiones anteriores). En la pestaña General, desplázate hacia abajo y haz clic en **Abrir de todos modos** junto al aviso emergente de OptimizerStudio.

### 🪟 Windows

*Requisitos: Windows 10 o superior.*

1. Ve a la página de [Releases](https://github.com/IsaacDev2024/OptimizerStudio/releases) y descarga el archivo ejecutable `OptimizerStudio.exe`.
2. Haz doble clic para abrir la aplicación. ¡Listo!

> **⚠️ Solución a bloqueo por parte de Windows Defender:**
> Ocurre igualmente al no estar firmado por Microsoft. 
> **Solución 1:** Haz clic derecho en el archivo `.exe` > `Propiedades`, selecciona la casilla **"Desbloquear"** en la parte inferior y presiona Aceptar.
> **Solución 2:** Al abrir el programa, si aparece la pantalla de *SmartScreen*, haz clic en **"Más información"** y luego en **"Ejecutar de todas formas"**.
> *Nota: Ejecutar como Administrador y guardarlo en una carpeta sin espacios puede ayudar a evitar otro tipo de problemas.*

---

## 🛠️ ¿Cómo usar OptimizerStudio?

El flujo de trabajo general para todos los módulos es:
1. **Seleccionar el módulo** en la pantalla principal.
2. **Configurar el problema** (Variables de decisión, Restricciones, Orígenes/Destinos, etc.).
3. **Ingresar los datos** correspondientes (Coeficientes, Ofertas, Demandas, Matrices de costos).
4. **Resolver** haciendo clic en el botón de la parte inferior (ej. `🚀 Resolver Problema`).
5. **Observar y analizar** el procedimiento detallado en la **Consola de Salida**.

---

## 📚 Base Teórica

Los algoritmos aquí implementados se fundamentan teóricamente en el libro **“Fundamentos y Aplicaciones de la Programación Lineal”**, obra literaria desarrollada por los propios creadores de este software. Dicho material garantiza la precisión metodológica y sirve como texto complementario para estudiantes y docentes que busquen profundizar en los conceptos matemáticos.

---

## 👥 Créditos y Agradecimientos

**Equipo de Desarrollo y Autores:**
- Isaac David Sánchez Sánchez
- Santiago Andrés Orejuela Cueter
- Luis Mario Díaz Martínez

**Dirección y Apoyo Pedagógico:**
- Prof. Isaac Zúñiga Silgado

**Testing / Control de Calidad:**
- Mariana Buitrago Lara
- María Valentina Serna González

---

## ✉️ Contacto y Soporte

Si deseas reportar un error, hacer una sugerencia de mejora o comunicarte con nosotros, tienes a disposición:
- Un botón dedicado de **Feedback** en la pantalla principal de la aplicación.
- Sección de Issues en nuestro repositorio en GitHub: [IsaacDev2024/OptimizerStudio](https://github.com/IsaacDev2024/OptimizerStudio)

<br/>

<p align="center"><b>Hecho con ❤️ por estudiantes, para estudiantes.</b></p>
