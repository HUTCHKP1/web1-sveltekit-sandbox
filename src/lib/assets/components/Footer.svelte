<script>
  let {course = 'ID512 Web Development', year = 2026} = $props();
</script>

<footer>
  <p>{course} &copy; {year}</p>
</footer>

<style>
  footer {
    background-color: black;
    padding: 20px;
    text-align: center;
    border-top: 1px solid #ccc;
  }
</style>
