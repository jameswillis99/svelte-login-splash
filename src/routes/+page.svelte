<script>
  import Input from "../components/inputs/input/input.svelte";

  let emailValue = "";
  let passwordValue = "";
</script>

<div class="content">
  <div class="item">
    <h1>Welcome</h1>
    <h5>Please sign in below.</h5>
  </div>
  <!-- <p>{inputValue}</p> -->
  <div class="item">
    <Input bind:value={emailValue} label={'Email'}/>
  </div>
  <div class="item">
    <Input bind:value={passwordValue} label={'Password'}/>
  </div>
</div>

<style>

  .content {
    padding-top: 100px;
    margin: 0;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    color: white;
  }

  .item {
    flex-basis: 100%;
    text-align: center;
  }
</style>
