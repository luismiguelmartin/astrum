Ahora es posible definir las columnas de forma más sencilla, simplemente con la clase `.col` (sin necesidad de añadir ancho definido).
De manera igual que antes, podemos integrarlas en un contenedor fluido de ancho completo (`.container-fluid`) o fijo según queramos maquetar a ancho completo de la página o contenidos en el _breakpoint_ definido para escritorio 1140px o 1200px de ancho habitualmente.

De esta manera, si tenemos 2 columnas dentro de un fila `.row`, estas se ajustarán al 50%. Si hubiera 3, al 33.33%; 4 al 25%; etc.

<div class="ndpl-component__container" style="margin-bottom:20px;">
<div class="ndpl-component__sample ndpl-c-border" style="padding-bottom:16px; border-radius: 6px 6px 6px 6px !important;">
<pre><code>&lt;!-- 2 columnas --&gt;
&lt;div class="container"&gt;
  &lt;div class="row"&gt;
    &lt;div class="col"&gt;Columna 1&lt;/div&gt;
    &lt;div class="col"&gt;Columna 2&lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
</code></pre>

<pre><code>&lt;!-- 3 columnas --&gt;
&lt;div class="container-fluid"&gt;
  &lt;div class="row"&gt;
    &lt;div class="col"&gt;Columna 1&lt;/div&gt;
    &lt;div class="col"&gt;Columna 2&lt;/div&gt;
    &lt;div class="col"&gt;Columna 3&lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
</code></pre>
</div>
</div>

También podemos combinar estas nuevas columnas _autoajustables_ con columnas de medida "fija". Esto es interesante para pantallas en las que haya información opcional o no y pueda aparecer o no en columnas adicionales pero respestando un espacio fijo para la información principal:

<div class="ndpl-component__container" style="margin-bottom:20px;">
<div class="ndpl-component__sample ndpl-c-border" style="padding-bottom:16px; border-radius: 6px 6px 6px 6px !important;">
<pre><code>
&lt;!-- 3 columnas --&gt;
&lt;div class="container"&gt;
  &lt;div class="row"&gt;
    &lt;div class="col-7"&gt;1 de 3&lt;/div&gt;
    &lt;div class="col"&gt;2 de 3&lt;/div&gt;
    &lt;div class="col"&gt;3 de 3&lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
</code></pre>
</div>
</div>

Todo esto se combina en el siguiente ejemplo:
