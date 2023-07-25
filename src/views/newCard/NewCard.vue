<!-- eslint-disable prettier/prettier -->
<template>
  <div class="newcard">
    <div class="App">
      <body>
        <div class="main">
          <div class="left">
            <div class="text">
              <p>Cadastre seus clientes</p>
            </div>
            <div class="image">
              <img class="imgRocket" src="@/assets/rocket.svg"/>
            </div>
          </div>
          <div class="right">
              <form>
                <div class="form">
                  <div class="inputs">
                    <input class="all" name="name" placeholder="Nome" required/>
                  </div>
                  <div class="inputs">
                    <input class="all" name="cnpj"  placeholder="CNPJ" required/>
                  </div>
                  <div class="inputs">
                    <input class="all" name="email"  placeholder="Email" required/>
                  </div>
                  <div class="inputs">
                    <input class="oneThird" name="DDD" placeholder="DDD" required/>
                    <input class="oneThird" name="phone"  placeholder="Telefone" required/>
                    <input class="oneThird" name="fax"  placeholder="Fax" required/>
                  </div>
                  <div class="inputs">
                    <input class="all" name="representative"  placeholder="Representante" required/>
                  </div>
                  <div class="inputs">
                    <input class="meio" name="date" placeholder="Data Registro" required/>
                    <input class="meio" name="office"  placeholder="Cargo Representante" required/>
                  </div>
                  <div>
                    <div class="inputs">
                      <input class="all" name="address" placeholder="Logradouro" required/>
                    </div>
                    <div class="inputs">
                      <input class="meio" name="number" placeholder="Número" required/>
                      <input class="meio" name="district"  placeholder="Bairro" required/>
                    </div>
                    <div class="inputs">
                      <input class="meio" name="complement" placeholder="Complemento" required/>
                      <input class="meio" name="zipCode"  placeholder="CEP" required/>
                    </div>
                    <div class="inputs">
                      <input class="meio" name="city" placeholder="Cidade" required/>
                      <input class="meio" name="UF"  placeholder="Estado" required/>
                    </div>
                  </div>
                </div>
                <div class="submit">
                  <input class="inputSubmit" type="submit" value="Cadastrar" />
                </div>
              </form>
          </div>
        </div>
      </body>
    </div>
  </div>
</template>
<!-- eslint-disable prettier/prettier -->
<style>
  .newcard {
    min-height: 100vh;
    width: 100%;

    display: flex;
    justify-content: center;
  }

  * {
    padding:0;
    margin:0;
    vertical-align:baseline;
    list-style:none;
    border:0;
  }

  .main {
    display: flex;
    justify-content: center;
    height: 100%;
    width: 100%;
    margin-top: 40px;
  }

  .left {
    width: 45%;
    height: 800px;
    padding: 2rem 4rem 0 4rem;
    background-color: rgba(254, 217, 183, 0.25);

    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-content: center;
  }

  .text{
    font-size: 3.2rem;
    color: #FF8A5C;
    margin-bottom: 1.6rem;
  }

  .imgRocket {
    width: 500px;
  }

  .right {
    width: 55%;
    height: 800px;

    padding:  0 6rem 0 2rem;

    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-content: center;
  }

  .submit {
    display: flex;
    justify-content: center;
    align-content: center;

    margin-top: 2rem;
  }

  .form {
    font-size: 1.2rem;
    color: #535353;
  }

  .inputs {
    display: flex;
    justify-content: space-between;
    width: 100%;
    margin: 1rem;
  }

  .all {
    width:100%;
  }

  .meio {
    width: 48%;
  }

  .oneThird {
    width: 32%;
  }

  .inputSubmit {
    height: 54px;
    position: relative;
    padding: 0px 16px;
    border: none;
    border-radius: 4px;
    font-size: 20px;
    font-weight: 600;
    line-height: normal;
    background-color: #F07167;
    color: #FED9B7;
    outline: none;
    transition: 0.3s background-color ease-in-out, 0.3s box-shadow ease-in-out, 0.1s padding ease-in-out; -webkit-appearance: none;
  }

  .inputSubmit:hover{
    background-color: rgba(255, 255, 255, 0.45);
    box-shadow: 0px 4px 20px 0px rgba(0, 0, 0, 0.05);
  }

  .meio, .all, .oneThird {
    height: 54px;
    position: relative;
    padding: 0px 16px;
    border: none;
    border-radius: 4px;
    font-size: 16px;
    font-weight: 400;
    line-height: normal;
    background-color: transparent;
    color: #282828;
    outline: none;
    box-shadow: 0px 4px 20px 0px #FED9B7;
    transition: 0.3s background-color ease-in-out, 0.3s box-shadow ease-in-out, 0.1s padding ease-in-out; -webkit-appearance: none;
  }

  .all:hover, .meio:hover, .oneThird:hover{
    background-color: #FED9B7;
    color: #F07167;
  }
</style>
