# Plantilla de especificaciones técnicas de arte

Registra límites técnicos por categoría de recurso de arte (asset). Duplica esta plantilla cuando personajes, entornos o interfaz necesiten reglas diferentes.

Juego: [Completar] · Versión: [Completar] · Responsable: [Completar] · Fecha: [AAAA-MM-DD] · Estado: [Por definir]

## Contexto de uso

- ¿En qué plataforma, cámara, distancia y cantidad simultánea aparecerá esta categoría?
- ¿Qué calidad visual debe conservarse y qué restricción técnica obliga a priorizar?

Respuesta: [Completar]

## Formato del recurso

- ¿Qué resolución, dimensiones, texturas, materiales, geometría o sprites necesita realmente?
- ¿Qué reglas de coordenadas UV —la forma de ubicar texturas sobre un modelo—, pivote, escala, orientación, colisión y nombres evitan correcciones al importar?

Respuesta: [Completar]

## Variantes de rendimiento

- ¿Cuándo se requieren niveles de detalle (LOD), atlas, compresión o versiones simplificadas?
- ¿Qué señal observable indica que el recurso excede el costo acordado o pierde calidad inaceptable?

Respuesta: [Completar]

## Comprobación

- Importar un recurso representativo y comprobar escala, materiales, colisión y aspecto en una versión ejecutable (build) objetivo.
- Medir la categoría en su escena más exigente antes de declarar válidos los límites.

## Conexiones

- [Pipeline de arte](../08_Pipeline_de_Arte/Plantilla.md)
- [Optimización de arte](../11_Optimizacion/Plantilla.md)
- [Volver al índice general](../../00_Indice_y_Control/01_Indice_General.md)

[Documentos de esta área](../00_README_Arte.md)
