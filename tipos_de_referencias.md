
# Tipos de referencias

Hasta ahora siempre nos hemos referido a las celdas como una combinación de una letra y un número, por ejemplo B6. Esta referencia se obtiene por defecto en cualquiera de las hojas de cálculo que estamos tratando, y se denomina referencia relativa de la celda.

Una **referencia relativa** a una celda o rango es aquella que, al copiar la celda donde está escrita y pegarla en otra ubicación, se ajusta automáticamente** **para hacer referencia a otras celdas.

Fíjate en el siguiente ejemplo:

<object data="http://aularagon.catedu.es/materialesaularagon2013/hojacalc/Referencias_absolutas.swf" height="531" style="display: block; margin-left: auto; margin-right: auto;" type="application/x-shockwave-flash" width="1062"><param name="src" value="http://aularagon.catedu.es/materialesaularagon2013/hojacalc/Referencias_absolutas.swf"/></object>

*Referencias absolutas y relativas. Autora: Carmen Tobeña*

Como has podido observar, en algunas ocasiones necesitamos que las celdas permanezcan invariables aunque copiemos la función en otras posiciones. En esos casos se utilizan las llamadas referencias absolutas.

Una **referencia absoluta** a una celda o rango es aquella que, al copiar la celda donde está escrita y pegarla en otra ubicación, **NO** se ajusta y queda bloqueada haciendo referencia siempre a la misma celda.

Para hacer una referencia absoluta a una celda, se deben introducir los símbolos de dólar $ antes de la letra (con eso bloqueamos la columna) y antes del número (y con eso bloqueamos la fila) de una referencia normal. Es decir, una referencia absoluta a la celda B6, sería: $B$6

En muchas ocasiones solamente nos interesará dejar fijo, bien una columna, o bien una fila, utilizando entonces las llamadas referencias mixtas.

Una **referencia mixta** a una celda o rango es aquella que, al copiar la celda donde está escrita y pegarla en otra ubicación, ajusta sólo la letra o sólo el número de la referencia, quedando bloqueado sólo el número o sólo la letra respectivamente.

Por lo tanto, si queremos bloquear una columna, debemos colocar el símbolo de dólar "$" antes de la letra y si queremos bloquear una fila, debemos colocar el símbolo de dólar "$" antes del número. 

> **tip**

># ParaSaberMas

>Pulsando sucesivamente la combinación de teclas **Mayúsculas ** + **F4 **  alternamos entre el modo de referencia absoluta, referencia mixta (fijar fila), referencia mixta (fijar columna) o referencia relativa


# Tarea interactiva

Lee y completa

Imagina que quiero copiar la celda C5.

{%fbq%}
* Si necesito copiarla dejando igual la fila y la columna escribiré $$\$C\$5##.
* Si solamente quiero que cambie la fila escribiré $$\$C5##.
* Si quiero que solamente la fila permanezca igual escribiré $$C\$5##
* Esto último es una referencia $$mixta##.
{%endfbq%}

