# El Pergamino del Farol — Plantilla personalizable

Regalo digital interactivo y cinematográfico. Un único archivo index.html autocontenido. 100% offline. Listo para personalizar y vender.

## Características
- 6 escenas + mapa manual
- Sonidos 100% sintetizados con Web Audio API
- Pergamino cifrado con palabra secreta
- Pausa (esquina superior izquierda) y silencio (doble toque superior derecha)
- Optimizado móvil (evita zoom al escribir)
- Se detiene por completo al finalizar
- Sin dependencias externas

## Precio sugerido
S/ 99.00 PEN / .00 USD / €29,00 (Digital Download)

## Personalizar rápido
1. Abre index.html y cambia CONFIG.NOMBRE por el nombre deseado.
2. (Opcional) Cambia CONFIG.PREGUNTA, CONFIG.PISTA, CONFIG.RESPUESTA.
3. Para regenerar el sello cifrado: 
ode tools/cifrar.js y copia el JSON generado al bloque GIFT_JSON de index.html.

## Estructura
- index.html → Entregable al comprador
- 	ools/cifrar.js → Generador del sello cifrado
- README.md, LICENSE

## Licencia
MIT. Uso comercial permitido.


## Nota
Al abrirlo en PC puede verse negro hasta que toques la pantalla. En móvil funciona directo al tocar 'Toca para empezar'.

