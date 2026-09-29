# CubeSat UD34 - Práctica 3

Repositorio correspondiente a la **Práctica 3: Requisitos, especificaciones y arquitectura electrónica del CubeSat UD34** de la asignatura Diseño de Productos Electrónicos.

El objetivo de esta práctica es definir una propuesta preliminar de arquitectura electrónica para un CubeSat 1U, partiendo de los requisitos de la misión y considerando procesamiento, almacenamiento, potencia, comunicaciones, control de actitud y carga útil.

## Integrantes

- Emiliano de Jesus Lince
- Angel Santiago Graciano Espitia

## Estructura del repositorio

```text
CubeSat-UD34/
├── README.md
├── informe/
├── diagramas/
└── matrices/
```

### `informe/`

Contiene el informe de la práctica, donde se presentan:

- interpretación del problema y supuestos;
- requisitos y especificaciones;
- distribución de funciones entre hardware y software;
- alternativas de arquitectura;
- arquitectura seleccionada;
- interfaces principales;
- presupuestos preliminares;
- riesgos, limitaciones y referencias.

### `diagramas/`

Contiene los diagramas utilizados para representar el sistema, incluyendo:

- diagrama funcional inicial;
- diagrama de arquitectura electrónica seleccionada.

### `matrices/`

Contiene el libro de trabajo en Excel con la información utilizada durante el desarrollo de la práctica:

- matriz de requisitos;
- especificaciones y trazabilidad;
- funciones HW/SW;
- subsistemas;
- alternativas de arquitectura;
- matriz de selección;
- interfaces;
- presupuestos de potencia, datos, masa y volumen;
- componentes de referencia;
- fuentes técnicas.

## Arquitectura propuesta

La arquitectura preliminar seleccionada está organizada en **tres PCBs principales**:

1. **PCB 1 - Potencia (EPS)**
2. **PCB 2 - Procesamiento, almacenamiento y control**
3. **PCB 3 - Comunicaciones**

Además, el sistema considera como módulos externos la cámara multiespectral, sensores y actuadores del ADCS, paneles solares, batería y antenas.

## Estado del proyecto

Este repositorio corresponde a una etapa de **diseño preliminar**. La Práctica 3 define la arquitectura general y los presupuestos del sistema; el diseño detallado de los circuitos, esquemáticos y PCB se realizará en las siguientes etapas del proyecto.

## Repositorio

https://github.com/carepalmada/CubeSat-UD34
