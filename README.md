# Llenador por Histéresis

## Descripción

Sistema de llenado de líquidos basado en control por histéresis. Este proyecto incluye el diseño mecánico completo de un dispositivo automatizado para el llenado preciso de envases mediante un mecanismo de plato giratorio.

## Estructura del Proyecto

El proyecto está compuesto por los siguientes archivos CAD desarrollados en SolidWorks:

| Archivo | Tipo | Descripción |
|---------|------|-------------|
| `PCB.SLDASM` | Ensamblaje | Ensamblaje principal de la placa de circuito impreso |
| `Base PCB.SLDPRT` | Pieza | Base de soporte para la PCB |
| `Base_Estructura.SLDPRT` | Pieza | Base estructural del sistema |
| `Envase_Agua.SLDPRT` | Pieza | Contenedor de agua/líquido |
| `Plato Giratorio.SLDPRT` | Pieza | Plato rotativo para posicionamiento de envases |
| `Plato_Superior.SLDPRT` | Pieza | Plato superior del mecanismo |
| `Vaso.SLDPRT` | Pieza | Recipiente para llenado |

## Componentes del Sistema

### Mecánicos
- Base estructural principal
- Sistema de plato giratorio para indexación de envases
- Soporte para PCB de control

### Electrónicos
- Placa de circuito impreso (PCB) para control por histéresis
- Sensores de nivel
- Actuadores de llenado

## Principio de Funcionamiento

El sistema utiliza control por histéresis para regular el proceso de llenado:

1. El plato giratorio posiciona el envase en la estación de llenado
2. El sensor de nivel detecta el estado del recipiente
3. El controlador activa/desactiva el flujo según los umbrales de histéresis definidos
4. Una vez alcanzado el nivel objetivo, el plato rota para posicionar el siguiente envase

## Requisitos de Software

- SolidWorks 2020 o superior (para visualización y edición de archivos CAD)

## Licencia

Proyecto de portafolio personal.

## Autor

Ing. Karen lesmes
---
