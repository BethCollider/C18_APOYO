# Modificar sintaxis para compatibilidad en telefonos

### Cambio en `funcion setup(){}`

#### Modificar area de juego a pantalla de dispositivo

 `createCanvas(windownWidth,windowHeight);`

#### Modificar el tamaño del trex

  `trex = createSprite (50,height,20,50);`

#### Modificar tamaño suelo invisible

 `sueloInv = createSprite(width/2,height-10,width,125);`

## Cambios en `function draw (){}`

#### Cambios en la condicional de salto para que detecte la pantalla

`if (touches.length > 0 || keyDown ("space") && trex.y >= heigth -100) {`

​        `trex.velocityY = -10;`

​        `jump.play();`

​        `touches = [];`

​       `}`