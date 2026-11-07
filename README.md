# FORM-PC-01: Comparativa de Modelos de Proceso de Requisitos en Escenarios Reales

**Asignatura:** Ingeniería de Requisitos (ISR-401)  
**Institución:** Universidad Técnica Estatal de Quevedo (UTEQ)  
**Facultad:** Facultad de Ciencias de la Computación  
**Carrera:** Ingeniería de Software  
**Código de Actividad:** FORM-PC-01  

---

## Integrantes del Equipo

- **José Ignacio Gilces Carranza**
- **Jostin Gustavo Vélez Vinces**

---

## Descripción del Proyecto

Este repositorio contiene el código fuente en LaTeX y el documento final compilado en formato PDF correspondiente a la práctica en clase **FORM-PC-01: Comparativa de Modelos de Proceso de Requisitos en Escenarios Reales**. 

El trabajo aborda la definición de cinco criterios de evaluación (volatilidad, criticidad, disponibilidad de stakeholders, rigidez contractual y time-to-market), la matriz comparativa de idoneidad entre modelos (Cascada, Iterativo/Incremental y Scrum) frente a cuatro escenarios del entorno profesional, la justificación de la selección y el desglose formal del framework conceptual de Klaus Pohl aplicado a un caso de contratación pública municipal (GAD cantonal).

---

## Estructura del Repositorio

```text
.
├── .gitignore                # Reglas de exclusión de archivos temporales de compilación
├── README.md                 # Documentación e instrucciones del repositorio
├── main.tex                  # Archivo principal fuente en LaTeX
├── referencias.bib           # Bibliografía en formato BibTeX (IEEE / biblatex)
└── main.pdf                  # PDF compilado final

```

---

## Instrucciones de Compilación (Reproducibilidad)

Para garantizar que el documento compile correctamente en cualquier entorno local o de evaluación, siga las instrucciones indicadas a continuación.

### Requisitos del Entorno

* Distribución LaTeX: MiKTeX / TeX Live / MacTeX.
* Compilador: pdflatex
* Procesador bibliográfico: biber (configurado para el paquete biblatex en estilo IEEE).

### Orden Exacto de Comandos de Compilación

Ejecute la siguiente secuencia desde la consola de comandos en la carpeta raíz del repositorio:

```bash
pdflatex -synctex=1 -interaction=nonstopmode main.tex
biber main
pdflatex -synctex=1 -interaction=nonstopmode main.tex
pdflatex -synctex=1 -interaction=nonstopmode main.tex

```

> **Nota para usuarios de TeXstudio:** Asegúrese de tener seleccionado Biber en *Opciones -> Configurar TeXstudio -> Compilación -> Herramienta de bibliografía por defecto*.

---

## Declaración de Uso de Inteligencia Artificial

De conformidad con las normas de evaluación académica de la asignatura:

* Herramientas de IA empleadas: Gemini / ChatGPT.
* Propósito del uso: Apoyo en la corrección de estilo, revisión ortográfica y asistencia en el maquetado en LaTeX.
* Método de verificación humana: Los integrantes del equipo verificaron, validaron y redactaron íntegramente la clasificación de requisitos, los casos de estudio y las referencias bibliográficas oficiales (ISO/IEC/IEEE 29148).

```

```
