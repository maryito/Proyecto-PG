<template>
  <div class="login">
    <form class="form-signin">
        <div class="text-center mb-4">
            <img class="mb-4" src="../assets/uipa.png" alt="" width="76" height="72">
            <h1 class="h3 mb-3 font-weight-normal">Iniciar Sesión</h1>
            <p>Para usar los servicios de UIP CRAI debe iniciar sesión primero</p>
        </div>

        <div class="form-label-group">
            <input type="cedula" id="inputEmail" class="form-control" placeholder="Cédula" required autofocus>
            <label for="inputEmail">Numero de Cédula</label>
        </div>

        <div class="form-label-group">
            <input type="password" id="inputPassword" class="form-control" placeholder="Contraseña" required>
            <label for="inputPassword">Contraseña</label>
        </div>

        <div class="checkbox mb-3">
            <label>
    <input type="checkbox" value="remember-me"> Mantener la sesión iniciada
  </label>
        </div>
        <button class="btn btn-lg btn-primary btn-block" type="submit">Iniciar Sesión</button>
    </form>
  </div>
</template>
<script>
export default {
    name: "Login"
}
</script>

<style>
.login {
    padding-top: 5%;
    padding-bottom: 5%;
}

.form-signin {
    width: 100%;
    max-width: 420px;
    padding: 45px;
    margin: auto;
    background-color: #f5f5f5;
}

.form-label-group {
    position: relative;
    margin-bottom: 1rem;
}

.form-label-group>input,
.form-label-group>label {
    height: 3.125rem;
    padding: .75rem;
}

.form-label-group>label {
    position: absolute;
    top: 0;
    left: 0;
    display: block;
    width: 100%;
    margin-bottom: 0;
    /* Override default `<label>` margin */
    line-height: 1.5;
    color: #495057;
    pointer-events: none;
    cursor: text;
    /* Match the input under the label */
    border: 1px solid transparent;
    border-radius: .25rem;
    transition: all .1s ease-in-out;
}

.form-label-group input::-webkit-input-placeholder {
    color: transparent;
}

.form-label-group input:-ms-input-placeholder {
    color: transparent;
}

.form-label-group input::-ms-input-placeholder {
    color: transparent;
}

.form-label-group input::-moz-placeholder {
    color: transparent;
}

.form-label-group input::placeholder {
    color: transparent;
}

.form-label-group input:not(:placeholder-shown) {
    padding-top: 1.25rem;
    padding-bottom: .25rem;
}

.form-label-group input:not(:placeholder-shown)~label {
    padding-top: .25rem;
    padding-bottom: .25rem;
    font-size: 12px;
    color: #777;
}

.bd-placeholder-img {
  font-size: 1.125rem;
  text-anchor: middle;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

@media (min-width: 768px) {
  .bd-placeholder-img-lg {
    font-size: 3.5rem;
  }
}
</style>