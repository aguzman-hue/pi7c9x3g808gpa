# pi7c9x3g808gpa

# PCIe Switch PI7C9X3G808GP — Diseño de Esquemático y PCB

## Descripción del proyecto

Proyecto académico desarrollado en **OrCAD X Professional Plus 25.1**, basado en el diseño de referencia del switch PCI Express **PI7C9X3G808GP de Diodes/Pericom**.

El objetivo fue adaptar el circuito original para utilizar una conexión PCIe x4 de entrada y distribuir las señales hacia cuatro puertos de salida destinados a unidades de almacenamiento NVMe.

### Modificaciones realizadas

- Adaptación del esquemático de alta velocidad, eliminando interruptores de señal y conexiones innecesarias.
- Configuración del switch PCIe para una entrada x4 y cuatro salidas x1.
- Actualización de la etapa de alimentación mediante reguladores DC-DC de Texas Instruments.
- Integración de símbolos y footprints personalizados.
- Generación de la netlist y transferencia del diseño a PCB Editor.
- Distribución inicial de componentes sobre la PCB, reutilizando las dimensiones y referencias mecánicas del diseño original.

### Estado del proyecto

Se completaron las modificaciones principales del esquemático y la colocación preliminar de componentes en la PCB.

**Pendiente:** enrutamiento de señales de alta velocidad y potencia, verificación de integridad de señal, revisión térmica y validación final mediante DRC.

### Herramientas utilizadas

- OrCAD X Capture CIS 25.1
- OrCAD X PCB Editor
- Texas Instruments WEBENCH Power Designer
- Librerías de componentes y footprints personalizados

**Proyecto académico — Electrónica 2 y Diseño Electrónico**