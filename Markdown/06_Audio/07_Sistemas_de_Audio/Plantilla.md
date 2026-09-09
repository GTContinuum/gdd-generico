# Plantilla de sistemas de audio

Describe reglas de reproducción y mezcla que reaccionan al juego. Duplica esta plantilla por sistema musical, ambiental, de combate o voz.

Juego: [Completar] · Versión: [Completar] · Responsable: [Completar] · Fecha: [AAAA-MM-DD] · Estado: [Por definir]

## Entradas y estados

- ¿Qué datos o eventos del juego controla el sistema y qué estados son posibles?
- ¿Qué transición sonora corresponde a cada cambio y cuánto puede tardar sin sentirse desconectada?

Respuesta: [Completar]

## Reglas de reproducción

- ¿Cómo funcionan prioridad, atenuación por distancia, aleatorización, límites de voces y zonas?
- ¿Cuándo se aplica reverberación o ducking —reducción temporal de otros sonidos— y qué debe permanecer audible?

Respuesta: [Completar]

## Casos límite

- ¿Qué ocurre si varios eventos llegan a la vez, se repiten rápido o el jugador cambia de zona bruscamente?
- ¿Cómo vuelve el sistema a un estado válido después de pausa, carga o interrupción?

Respuesta: [Completar]

## Comprobación

- Forzar transiciones rápidas y eventos simultáneos para confirmar que el estado final es correcto.
- Registrar qué regla decide cada sonido audible en una escena problemática.

## Conexiones

- [Implementación de audio](../10_Implementacion/Plantilla.md)
- [QA y mezcla](../11_QA_y_Mezcla/Plantilla.md)
- [Volver al índice general](../../00_Indice_y_Control/01_Indice_General.md)

[Documentos de esta área](../00_README_Audio.md)
