<h1>Aula 13</h1>

Esta clase consiste en comprender 

<h2>Encoder</h2>

Es un dispositivo que permite medir una posición o velocidad lineal (encoder lineales) o angular (encoder rotativos) a través de información digital a partir de un movimiento. Son desarrollados mediante tecnología óptica, mecánica o magnética.

![Encoder](image.png)

Fuente: https://como-funciona.co/un-encoder/

<h3>Optoacoplador</h3>

![Optoacoplador](image-1.png)

Fuente: https://www.ingmecafenix.com/electronica/optoacoplador/

<h3>Encoder absoluto</h3>

El encoder absoluto permite conocer la posición y la velocidad angular del eje mediante la decodificación de un conjunto de bits

![Encoder absoluto](image-2.png)

$$𝑅𝑒𝑠𝑜𝑙𝑢𝑐𝑖ó𝑛=\frac{360°}{2^𝑛}$$

$$Á𝑛𝑔𝑢𝑙𝑜=\frac{𝑑𝑒𝑐𝑖𝑚𝑎𝑙\dot360°}{2^𝑛}$$

![ROUNDSS RDE58S](image-3.png)

![Tabla ROUNDSS RDE58S](image-5.png)

![ALLEN BRADLEY 842A](image-4.png)

![Tabla ALLEN BRADLEY 842A](image-6.png)

<h3>Encoder incremental</h3>

El encoder incremental o relativo permite conocer la posición angular y la variación de desplazamiento angular (velocidad angular), mediante el conteo de pulsos por vuelta. El desfase entre las señales permite determinar la dirección de la rotación

![Encoder incremental](image-7.png)

Fuente: https://tecmaf.com.br/o-que-e-encoder-e-qual-sua-funcao/

![Encoder incremental 2](image-8.png)

Fuente: https://www.packworld.com/home/article/21134849/encoder-selection-tips

$$𝑅𝑒𝑠𝑜𝑙𝑢𝑐𝑖ó𝑛=\frac{360°}{𝑝𝑝𝑟}$$

$$Á𝑛𝑔𝑢𝑙𝑜=\frac{𝑝𝑢𝑙𝑠𝑜𝑠\cdot360°}{𝑝𝑝𝑟}$$

$$𝜔=\frac{\frac{1}{𝑇}\cdot60}{𝑝𝑝𝑟}$$

![OMRON E6B2](image-9.png)

![Tabla OMRON E6B2](image-11.png)

![Herradura Arduino](image-10.png)

![Tabla Herradura Arduino](image-12.png)

![Flancos encoder](Encoder.png)

<h3>Ejercicio 1</h3>

Cuál es la posición angular de dos encoder absolutos de 10 y 16 bits?, si el valor decimal es 980.

<h3>Ejercicio 2</h3>

Cuál es el valor decimal de dos encoder absolutos de 10 y 16 bits?, si la posición angular es 58.62°

<h3>Ejercicio 3</h3>

Cuál es la posición angular de dos encoder incrementales de 250 y 30 ppr?, si el valor de pulsos es 481.

<h3>Ejercicio 4</h3>

Cuál es el valor de los pulsos de dos encoder incrementales de 250 y 30 ppr?, si la posición angular es 45.21°