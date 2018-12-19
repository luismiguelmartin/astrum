Ahora es posible definir las columnas de forma más sencilla, simplemente con la clase `.col` (sin necesidad de añadir ancho definido).

De manera igual que antes, podemos integrarlas en un contenedor fluido de ancho completo (`.container-fluid`) o fijo   filas

<div class="ndpl-component__container" style="margin-bottom:20px;">
<div class="ndpl-component__sample ndpl-c-border" style="padding-bottom:16px; border-radius: 6px 6px 6px 6px !important;">
<pre><code>&lt;!-- columnas --&gt;
&lt;div class="container"&gt;
  &lt;div class="row"&gt;
    &lt;div class="col"&gt;
    Columna 1
    &lt;/div&gt;
    &lt;div class="col"&gt;
    Columna 2
    &lt;/div&gt;
  &lt;/div&gt;&lt;/div&gt;
&lt;!-- /Columnas --&gt;</code></pre>
</div>
</div>

De esta manera, si tenemos 2 columnas dentro de un fila `.row`, estas se ajustarán al 50%. Si hubiera 3, al 33.33%; 4 al 25%; etc.
