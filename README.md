<script>
  function init() {
   var world = "World!";
   return function () {
      alert("Hello " + world);
   };
}

window.onload = init();
</script>
