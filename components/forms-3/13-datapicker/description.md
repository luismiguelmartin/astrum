Se ha actualizado el componente DataPicker, empleado en otras apps, para que sea compatible con Bootstrap 4.1.3:

<div class="ndpl-component__container" style="margin-bottom:20px;">
<div class="ndpl-component__sample ndpl-c-border" style="padding-bottom:16px; border-radius: 6px 6px 6px 6px !important;">
<iframe src="./components/forms-3/13-datapicker/iframe.html" frameborder="0" scrolling="no" width="100%" height="350"></iframe>
</div>
</div>  


Se incluirían las librerías JS y CSS del plugin [Select2](https://select2.org/).


```
<!-- Se han de incluir las librerías de Datepicker -->

<link href="./assets/bootstrap-datepicker-1.8.0/css/bootstrap-datepicker.standalone.min.css" rel="stylesheet" type="text/css" />
<script src="./assets/bootstrap-datepicker-1.8.0/js/bootstrap-datepicker.js" type="text/javascript"></script>
<script src="./assets/bootstrap-datepicker-1.8.0/locales/bootstrap-datepicker.es.min.js" type="text/javascript"></script>

<!-- Cambiamos todos los .datepicker -->

<script type="text/javascript">
  $('.date').datepicker({
    format: "dd-mm-yyyy",
    todayBtn: "linked",
    language: "es",
    autoclose: "true",
    weekStart: 1
  });
</script>
```

A continuación se indica el código HTML con las que trabajaría el jQuery anterior:
