Se propone emplear un select múltiple buscable para seleccionar -por ejemplo- múltiples sectores:

<div class="ndpl-component__container" style="margin-bottom:20px;">
<div class="ndpl-component__sample ndpl-c-border" style="padding-bottom:16px; border-radius: 6px 6px 6px 6px !important;">
<iframe src="./components/forms-3/14-select-buscable/iframe.html" frameborder="0" scrolling="no" width="100%" height="350"></iframe>
</div>
</div>  


Se incluirían las librerías JS y CSS del plugin [Select2](https://select2.org/).


```
<!-- Librerías externas -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/select2/4.0.6-rc.0/css/select2.min.css" rel="stylesheet" />
<script src="https://cdnjs.cloudflare.com/ajax/libs/select2/4.0.6-rc.0/js/select2.min.js"></script>

<!-- Librerías locales -->
<link href="./select2/css/select2.css" rel="stylesheet" />
<script src="./select2/js/select2.min.js"></script>

<!-- Cambiamos los .simple-select2 -->

  <script>
    $(document).ready(function() {
      $('.simple-select2').select2({
        placeholder: 'Comienza a escribir o pulsa para seleccionar sectores/CNAE.'
      });
    });
  </script>
```

A continuación se indica el código HTML con las que trabajaría el jQuery anterior:
