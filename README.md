# Problemario de Autómatas y Lenguajes Formales

Este repositorio/directorio contiene la resolución detallada de una serie de ejercicios prácticos y teóricos sobre Teoría de la Computación, enfocados en el diseño, análisis y simplificación de Autómatas Finitos (AFD y AFN), así como la construcción de Expresiones Regulares.

## 📌 Contenido del Proyecto

El proyecto está compuesto por dos partes principales: el documento formal con el procedimiento matemático y los archivos de simulación gráfica.

* `main.tex`: Código fuente en LaTeX que contiene el razonamiento paso a paso, las conversiones por el método de subconjuntos, ecuaciones de estado y los diagramas generados nativamente con la librería TikZ.
* `Archivos .jff`: Colección de archivos ejecutables en JFLAP correspondientes a cada autómata diseñado en los ejercicios (ej. `157.jff`, `260.jff`, etc.).
* `main.pdf`: (Si se incluye) El documento final compilado listo para su revisión.

## ⚙️ Requisitos y Herramientas

Para visualizar o editar los archivos de este proyecto, se requiere el siguiente software:

1.  **Entorno LaTeX:** Puedes usar un editor local (como TeXstudio o VS Code con LaTeX Workshop) o un entorno en la nube como [Overleaf](https://www.overleaf.com/).
    * *Nota de compilación:* El documento utiliza el paquete `babel` en español. Para evitar conflictos con las flechas de TikZ (`>`), el código ya incluye la opción `es-noquoting` en la importación del paquete.
2.  **JFLAP 7.1:** Herramienta gráfica interactiva para experimentar con lenguajes formales y autómatas. Requiere tener instalado Java (JRE) en tu sistema. Puedes descargarlo desde [jflap.org](http://www.jflap.org/).

## 🚀 Uso de los Archivos JFLAP

Los archivos `.jff` están listos para ser simulados. Para probarlos:
1. Abre JFLAP.
2. Ve a `File > Open` y selecciona el ejercicio que deseas revisar (por ejemplo, `195.jff`).
3. Puedes ingresar cadenas de prueba usando la opción `Input > Step with Closure` o `Input > Multiple Run` para verificar que el autómata acepta los lenguajes detallados en el documento.

## 🎓 Datos Académicos

* **Institución:** Instituto Politécnico Nacional (IPN)
* **Escuela:** Escuela Superior de Cómputo (ESCOM)
* **Programa:** Ingeniería en Sistemas Computacionales
* **Estudiante:** Gonzalez Ortiz Iker Saul
* **Materia:** Teoria de la computacion
  
