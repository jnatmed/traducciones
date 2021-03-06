[Volver al Indice](README.md)

### Dimensiones: El Rol del concepto de Herencia

Una jerarquía de conceptos define una secuencia de mapeos desde un conjunto de conceptos de bajo nivel a conceptos de nivel superior y más generales. Considere una jerarquía de conceptos para la dimensión ubicación. Los valores de ciudad para la ubicación incluyen Vancouver, Toronto, Nueva York y Chicago. Sin embargo, cada ciudad se puede asignar a la provincia o estado al que pertenece. Por ejemplo, Vancouver se puede asignar a Columbia Británica y Chicago a Illinois. Las provincias y los estados, a su vez, pueden asignarse al país (por ejemplo, Canadá o Estados Unidos) al que pertenecen. Estos mapeos forman una jerarquía de conceptos para la dimension ubicacion, mapeando un conjunto de conceptos de bajo nivel (por ejemplo ciudades) a alto nivel, hacia conceptos mas generales (por ejemplo paises). Este concepto de herencia esta ilustrado en la figura 4.9.

Muchos conceptos de herencia estan implicitos dentro del esquema de base de datos. Por ejemplo, suponga que la dimension ubicacion esta descripta por los atributos numero, calle, ciudad, provincia o estado, codigo zip, y pais. Estos atributos estan relacionados por un orden total, formando una herencia de conceptos tales como "calle < ciudad < provincia_o_estado < pais". Esta herencia esta mostrada en lla figura 4.10(a). Alternativamente, los atributos de una dimension podrian estar organizados en orden parcial, formando una

![figura 4.9-concepto herencia](img/figura-4.9-concepto-herencia.jpg? "Figura 4.9 - Concepto de Herencia")