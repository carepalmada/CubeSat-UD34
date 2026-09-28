# CubeSat UD34 - Práctica 3

Repositorio de soporte para la **Práctica 3: Requisitos, especificaciones y arquitectura electrónica del CubeSat UD34**.

El proyecto corresponde al diseño preliminar de la arquitectura electrónica de un CubeSat 1U cuya misión es adquirir imágenes multiespectrales de regiones productoras de café en Colombia y transmitirlas a una estación terrestre de referencia ubicada en Medellín.

## Contenido del repositorio

```text
CubeSat-UD34-Practica3/
├── README.md
├── informe/
│   └── Informe_Practica3.pdf
├── matrices/
│   ├── Matriz_Requisitos.xlsx
│   ├── Especificaciones_Tecnicas.xlsx
│   ├── Distribucion_HW_SW.xlsx
│   ├── Alternativas_Arquitectura.xlsx
│   └── Interfaces_y_Presupuestos.xlsx
├── diagramas/
│   ├── Diagrama_Funcional.*
│   └── Arquitectura_Seleccionada.*
├── calculos/
│   └── Calculos_Soporte.*
├── datasheets/
│   ├── camara/
│   ├── obc/
│   ├── potencia/
│   ├── adcs/
│   └── comunicaciones/
└── referencias/
    └── Fuentes_Tecnicas.md
```

## Documentos principales

- Matriz de requisitos funcionales, no funcionales, ambientales y normativos.
- Especificaciones técnicas y trazabilidad.
- Distribución de funciones entre hardware y software.
- Comparación de alternativas de arquitectura.
- Arquitectura seleccionada y división preliminar en PCBs.
- Definición preliminar de interfaces.
- Presupuestos de potencia, energía, datos, almacenamiento, masa y volumen.
- Diagramas de arquitectura.
- Hojas de datos de los componentes seleccionados.
- Cálculos utilizados para justificar las decisiones de diseño.

## Arquitectura preliminar

La arquitectura seleccionada se divide inicialmente en tres PCBs:

1. **PCB 1 - EPS / Potencia**
   - Gestión de batería.
   - Conversión y distribución de energía.
   - Protecciones y monitoreo eléctrico.

2. **PCB 2 - OBC / Procesamiento**
   - Procesamiento central.
   - Almacenamiento.
   - Interfaz con la cámara.
   - Interfaces y control del ADCS.

3. **PCB 3 - Comunicaciones**
   - Transceptor RF.
   - Etapa de radiofrecuencia.
   - Interfaz con la antena.
   - Comunicación con el OBC.

La cámara multiespectral, los sensores y actuadores del ADCS, la batería, los paneles solares y la antena se consideran módulos conectados a estas tarjetas.

## Estado del proyecto

Este repositorio corresponde a una etapa de **diseño preliminar**. Algunos parámetros permanecen como `TBD` hasta completar la selección de componentes y los cálculos de dimensionamiento.

## Referencias principales

- Proyecto CubeSat UD34 2026-2.
- Guía de la Práctica 3.
- CubeSat Design Specification Rev. 14.1.
- ECSS-E-ST-20C Rev.2.
- ECSS-E-ST-20-07C Rev.2.
- ECSS-Q-ST-70-12C Rev.1.
- NASA State-of-the-Art of Small Spacecraft Technology 2026.

## Autores

Estudiantes de Ingeniería Electrónica  
Universidad de Antioquia  
2026-2
