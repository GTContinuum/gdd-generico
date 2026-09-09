# Plantilla de guardado, carga y persistencia

Define qué progreso se conserva y cómo se recupera. Úsala para evitar pérdidas, incompatibilidades y estados imposibles.

Juego: [Completar] · Versión: [Completar] · Responsable: [Completar] · Fecha: [AAAA-MM-DD] · Estado: [Por definir]

## Contenido guardado

- ¿Qué datos persisten, cuáles se reconstruyen y cuáles deben reiniciarse en cada sesión?
- ¿En qué momentos se guarda de forma automática o manual y qué señal recibe el jugador?

Respuesta: [Completar]

## Formato y compatibilidad

- ¿Cómo se identifica la versión del guardado y qué cambios futuros exigirían migración?
- ¿Qué reglas mantienen referencias, orden y valores válidos al cargar datos antiguos?

Respuesta: [Completar]

## Fallas y recuperación

- ¿Qué ocurre si el archivo falta, está incompleto, corrupto o no puede escribirse?
- ¿Qué copia, transacción o recuperación evita perder el último estado válido durante una interrupción?

Respuesta: [Completar]

## Comprobación

- Guardar y cargar en estados extremos, cerrar durante escritura y comprobar la recuperación prevista.
- Cargar al menos un guardado de una versión anterior cuando exista una migración.

## Conexiones

- [Datos y configuración](../03_Datos_y_Configuracion/Plantilla.md)
- [QA técnico](../12_QA_Tecnico/Plantilla.md)
- [Volver al índice general](../../00_Indice_y_Control/01_Indice_General.md)

[Documentos de esta área](../00_README_Tecnico.md)
