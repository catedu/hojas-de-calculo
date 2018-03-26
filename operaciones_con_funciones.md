
# Operaciones con funciones

Muchas veces, al manejar grandes cantidades de información, la adición de fórmulas se convierte en un hecho reiterativo. En el ejemplo que has realizado en la página anterior, has tenido que escribir una fórmula prácticamente igual varias veces.

Para evitar tener que escribir la misma fórmula una vez tras otra, existe la posibilidad de copiar y pegar las funciones.

Al igual que ocurre con los datos, las funciones también se comportan de igual manera al copiarlas en otras ubicaciones, ya que se actualizan a la nueva posición, pudiendo aprovechar la definición de una función en otras estructuras similares que se construyan.

Para **copiar y pegar fórmulas** en otros lugares de la hoja de cálculo, independientemente del programa que utilicemos, tenemos varias posibilidades:

- Seleccionar la celda que contiene la fórmula que deseamos copiar y desde el menú Edición (o Editar) elegir Copiar (o desde el teclado CTRL+C). A continuación situar el cursor en la celda donde queremos tener la nueva fórmula y desde el menú Edición (o Editar) elegir Pegar (o desde el teclado CTRL+V).

- En los casos en que queramos copiar a celdas adyacentes puede utilizarse otro método: Seleccionar la celda que contenga la fórmula. Pulsar en la parte inferior derecha en el marco destacado que rodea la celda y mantener pulsado el botón del ratón. El puntero del ratón se convierte en un retículo. Mantener pulsado el botón del ratón y tirar hacia abajo o hacia la derecha sobre las celdas en las que desee copiar la fórmula. Soltar el botón del ratón. La fórmula se copiará en las celdas y se adaptará automáticamente, como se observa en la siguiente animación:

<object data="http://aularagon.catedu.es/materialesaularagon2013/hojacalc/CURSO/ZIPs/Modulo_2/suma.swf" height="315" type="application/x-shockwave-flash" width="420"><param name="src" value="http://aularagon.catedu.es/materialesaularagon2013/hojacalc/CURSO/ZIPs/Modulo_2/suma.swf"/></object>

*Pegado de funciones en una hoja de cálculo. Autora: Carmen Tobeña*

Como has podido observar al copiar y pegar una fórmula automáticamente la función se ajusta a la nueva celda. Si te fijas en la barra de fórmulas del ejemplo anterior, la función inicial **=A1+B1** se transforma en **=A2+B2** al copiar en la segunda fila, y así sucesivamente hasta que al pegarla en la quinta fila aparece automáticamente **=A5+B5**.

En algunas ocasiones necesitamos pegar solamente una parte de toda la información que contiene la celda (formato, fórmulas, números...).

En estos casos utilizamos un tipo específico de pegado que se conoce como **pegado especial**, al que se accede debajo de la opción de pegado explicada anteriormente.

Todos los programas nos ofrecen varias posibilidades comunes a la hora de pegar funciones.

# Rellenar huecos

Lea el párrafo que aparece abajo y complete las palabras que faltan.

{%fbq%}
Si queremos que en una celda se pegue la fórmula pero sin el formato de la celda, utilizaremos un tipo de pegado especial que se llama pegar $$fórmulas##.

Si por el contrario queremos pegar las celdas pero intercambiando filas por columnas, utilizaremos la opción $$transponer##.

Cuando queremos evitar pegar las celdas de origen que estaban vacías, podemos utilizar el pegado especial $$saltar blancos## en Excel o $$ignorar celdas vacías## en Calc.
{%endfbq%}