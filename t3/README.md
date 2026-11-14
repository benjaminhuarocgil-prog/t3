# Operación Extracción — FPS 3D

Proyecto T3 realizado con Python, HTML, CSS, JavaScript y Three.js.

## Ejecución

Desde esta carpeta ejecuta:

```bash
python server.py
```

Abre `http://localhost:8000` en el navegador.

## Controles

- `W A S D`: mover al jugador.
- Mouse: orientar la cámara FPS.
- Clic izquierdo: un disparo por clic.
- `1` y `2`: seleccionar cada arma.
- `R`: reiniciar después de perder o ganar.

## Requisitos implementados

- Mundo 3D explorable construido con Three.js.
- Cámara en primera persona y movimiento WASD.
- Dos armas con munición independiente y cambio visual.
- Carga preparada para modelos `.glb` en `assets/weapon-1.glb` y `assets/weapon-2.glb`; si todavía no están los archivos, se muestra una representación 3D de respaldo para que el juego siga siendo ejecutable.
- Cinco zombis, rango de activación configurable de 18 unidades, persecución y dos puntos de resistencia.
- Raycasting para impactos válidos; cada zombi muere exactamente después de dos impactos.
- Cajas de abastecimiento que recuperan munición una sola vez.
- Zona de extracción, victoria y Game Over por contacto.
