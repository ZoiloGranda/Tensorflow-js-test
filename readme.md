## Uso
1. `npm install`
2. `npm start` o `npx http-server -p 1234`. `1234` es el puerto, puede ser cualquiera que este libre

## What?
El **index.html** calcula los valores faltantes del arreglo `x2`, recibiendo como entrada los valores de `x1`.

Es una matriz, asi deberia estar completa, el tensor tiene que predecir los valores mas cercanos a  `0.1, 0.3 y 0.5`
```javascript
[0========0],
[0.1====0.1], 
[0.2====0.2],
[0.3====0.3],
[0.4====0.4],
[0.5====0.5]
```

**regresion-lineal.html** calcula una linea media entre todos los puntos del canvas

**ventas.html** calcula las ventas del dia siguiente, en base a las ventas de los dias anteriores

## Source
[Curso TensorFlow js en Español](https://www.youtube.com/watch?v=D00BFU_q2xY&list=PLCTD_CpMeEKSEOKBFyG6PxQOAvQc7HZSB&index=1)