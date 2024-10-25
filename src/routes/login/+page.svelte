<script>
  import Logo from "$lib/components/logo.svelte";
  import Checkbox from "$lib/components/ui/checkbox/checkbox.svelte";
  import Input from "$lib/components/ui/input/input.svelte";
  import Label from "$lib/components/ui/label/label.svelte";

</script>
<div class="max-w-5xl m-auto">
  <Logo />
  <form>
    <Label for="login">Логин</Label>
    <Input id="login" />
    <Label for="password">Пароль</Label>
    <Input id="password" />
    <div>
      <Checkbox id="remeber-me" />
      <Label for="remeber-me">Запомнить меня</Label>
    </div>
  </form>
</div>