<template>
  <div>
    <MenuLogin />
    <div class="page">
      <img class="capa" src="../../assets/img/cat-background.jpg" alt="">
      <div>
        <div class="form-login">
          <Title title="Cadastre-se" />
          <form>
            <Label class="label" forLabel="name" titleLabel="Nome" />
            <Input type="text" />
            <Label class="label" forLabel="email" titleLabel="email" />
            <Input type="email" />
            <Label class="label" forLabel="password" titleLabel="Senha" />
            <Input type="password" />
            <Button title="Cadastrar"></Button>
          </form>
        </div>
      </div>
    </div>
    <footer>
      <img src="../../assets/img/cat-logo-black.png" alt="logo">
      <p>Cat. Alguns direitos reservados.</p>
    </footer>
  </div>
</template>

<script>
import MenuLogin from '../../components/MenuLogin/MenuLogin.vue';
import Button from '../../components/Button/Button.vue';
import Label from '../../components/Label/Label.vue';
import Input from '../../components/Input/Input.vue';
import Title from '../../components/Title/Title.vue';

export default {
  name: 'Register',
  components: {
    MenuLogin,
    Button,
    Label,
    Input,
    Title,
  }
};
</script>

<style src="./style.css" scoped />
