
# Tipos de referencias

Hasta ahora siempre nos hemos referido a las celdas como una combinación de una letra y un número, por ejemplo B6. Esta referencia se obtiene por defecto en cualquiera de las hojas de cálculo que estamos tratando, y se denomina referencia relativa de la celda.

Una **referencia relativa** a una celda o rango es aquella que, al copiar la celda donde está escrita y pegarla en otra ubicación, se ajusta automáticamente** **para hacer referencia a otras celdas.

Fíjate en el siguiente ejemplo:

<object data="http://aularagon.catedu.es/materialesaularagon2013/hojacalc/Referencias_absolutas.swf" height="531" style="display: block; margin-left: auto; margin-right: auto;" type="application/x-shockwave-flash" width="1062"><param name="src" value="http://aularagon.catedu.es/materialesaularagon2013/hojacalc/Referencias_absolutas.swf"/></object>
|
|**Referencias absolutas y relativas. Autora: Carmen Tobeña**

Como has podido observar, en algunas ocasiones necesitamos que las celdas permanezcan invariables aunque copiemos la función en otras posiciones. En esos casos se utilizan las llamadas referencias absolutas.

Una **referencia absoluta** a una celda o rango es aquella que, al copiar la celda donde está escrita y pegarla en otra ubicación, **NO** se ajusta y queda bloqueada haciendo referencia siempre a la misma celda.

Para hacer una referencia absoluta a una celda, se deben introducir los símbolos de dólar $ antes de la letra (con eso bloqueamos la columna) y antes del número (y con eso bloqueamos la fila) de una referencia normal. Es decir, una referencia absoluta a la celda B6, sería: $B$6

En muchas ocasiones solamente nos interesará dejar fijo, bien una columna, o bien una fila, utilizando entonces las llamadas referencias mixtas.

Una **referencia mixta** a una celda o rango es aquella que, al copiar la celda donde está escrita y pegarla en otra ubicación, ajusta sólo la letra o sólo el número de la referencia, quedando bloqueado sólo el número o sólo la letra respectivamente.

Por lo tanto, si queremos bloquear una columna, debemos colocar el símbolo de dólar "$" antes de la letra y si queremos bloquear una fila, debemos colocar el símbolo de dólar "$" antes del número. 

# ParaSaberMas

Pulsando sucesivamente la combinación de teclas **Mayúsculas ** + **F4 **  alternamos entre el modo de referencia absoluta, referencia mixta (fijar fila), referencia mixta (fijar columna) o referencia relativa

# Actividad desplegable

Lee y completa

Imagina que quiero copiar la celda C5.

<li>Si necesito copiarla dejando igual la fila y la columna escribiré = 
<label class="sr-av" for="clozeBlank48_32.0">Rellenar huecos (1):</label>
<select id="clozeBlank48_32.0">
<option selected="selected"> </option><option value="$C5">$C5</option><option value="mixta">mixta</option><option value="C$5">C$5</option><option value="$C$5">$C$5</option>
</select>
JXUwMDdjJXUwMDY3JXUwMDY3JXUwMDEx
</li>
<li>Si solamente quiero que cambie la fila escribiré = 
<label class="sr-av" for="clozeBlank48_32.1">Rellenar huecos (2):</label>
<select id="clozeBlank48_32.1">
<option selected="selected"> </option><option value="$C5">$C5</option><option value="mixta">mixta</option><option value="C$5">C$5</option><option value="$C$5">$C$5</option>
</select>
JXUwMDdjJXUwMDY3JXUwMDc2
</li>
<li>Si quiero que solamente la fila permanezca igual escribiré = 
<label class="sr-av" for="clozeBlank48_32.2">Rellenar huecos (3):</label>
<select id="clozeBlank48_32.2">
<option selected="selected"> </option><option value="$C5">$C5</option><option value="mixta">mixta</option><option value="C$5">C$5</option><option value="$C$5">$C$5</option>
</select>
JXUwMDFiJXUwMDY3JXUwMDEx
</li>
<li>Esto último es una referencia 
<label class="sr-av" for="clozeBlank48_32.3">Rellenar huecos (4):</label>
<select id="clozeBlank48_32.3">
<option selected="selected"> </option><option value="$C5">$C5</option><option value="mixta">mixta</option><option value="C$5">C$5</option><option value="$C$5">$C$5</option>
</select>
JXUwMDM1JXUwMDA0JXUwMDExJXUwMDBjJXUwMDE1
 </li>


<input class="button" id="getScore48_32" name="getScore48_32" type="submit" value="Comprobar"/>
<input id="clozeOtras48_32" name="clozeOtras48_32" type="hidden" value=""/>
<input id="clozeFlag48_32.strictMarking" name="clozeFlag48_32.strictMarking" type="hidden" value="false"/>
<input id="clozeFlag48_32.checkCaps" name="clozeFlag48_32.checkCaps" type="hidden" value="false"/>
<input id="clozeFlag48_32.instantMarking" name="clozeFlag48_32.instantMarking" type="hidden" value="false"/>
Habilitar JavaScript


