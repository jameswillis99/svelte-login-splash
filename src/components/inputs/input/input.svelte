<script>
  export let value = "";
  export let label = "";
</script>

<div class="inputContainer">
  <label for="input">{label}:</label>
  <input id="input" bind:value />
</div>

<style>
  .inputContainer {
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    background-color: transparent;
    color: white;
  }
  label {
    display: inline-block;
    width: 100px;
    text-align: right;
  }
  input {
    background-color: transparent;
    color: white;
    width: 150px;
    border: none;
    border-bottom: 1px solid rgb(182, 182, 182);
    padding: 5px;
  }
  input:focus {
    outline: none;
  }
</style>
