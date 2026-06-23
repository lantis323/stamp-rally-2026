<script>
  const id = new URLSearchParams(location.search).get("id");
  localStorage.setItem(id, "checked");
  document.body.innerHTML = "チェックインしました！";
</script>
