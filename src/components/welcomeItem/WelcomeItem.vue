<!-- eslint-disable prettier/prettier -->
<template>
  <div class="item">
    <i>
      <slot name="icon"></slot>
    </i>
    <div class="details">
      <h3>
        <slot name="name"></slot>
        <slot name="recordANS"></slot>
      </h3>
      <div class="content">
        <div class="top">
          <p>
            <h7 class="mayor">Nome:</h7>
            <slot name="corporate"></slot>
            <h7 class="mayor">CNPJ:</h7>
            <slot name="cnpj"></slot>
          </p>
        </div>
        <div class="adress">
          <p>
            <h7 class="mayor"> Logradouro: </h7>
            <slot name="public-place"></slot>
            <h7 class="mayor"> Número: </h7>
            <slot name="number"></slot>
            <h7 class="mayor"> Complemento: </h7>
            <slot name="complement"></slot>
            <h7 class="mayor"> Bairro: </h7>
            <slot name="district"></slot>
            <h7 class="mayor"> Cidade: </h7>
            <slot name="city"></slot>
            <h7 class="mayor"> UF: </h7>
            <slot name="state"></slot>
            <h7 class="mayor"> CEP: </h7>
            <slot name="code"></slot>
          </p>
        </div>
        <div class="outers">
          <p>
            <h7 class="mayor"> DDD: </h7>
            <slot name="ddd"></slot>
            <h7 class="mayor"> Telefone: </h7>
            <slot name="telephone"></slot>
            <h7 class="mayor"> Fax: </h7>
            <slot name="fax"></slot>
            <h7 class="mayor"> E-mail: </h7>
            <slot name="e-mail"></slot>
            <h7 class="mayor"> Representante: </h7>
            <slot name="representative"></slot>
            <h7 class="mayor"> Cargo Representante: </h7>
            <slot name="representative-position"></slot>
            <h7 class="mayor"> Data Registro: </h7>
            <slot name="registration-date"></slot>
          </p>
        </div>
        <slot></slot>
      </div>
    </div>
  </div>
</template>
<!-- eslint-disable prettier/prettier -->
<style scoped>
.item {
  margin: 2rem;
  display: flex;
  width: 700px;


}

.details {
  display: 1;
  margin-left: 1rem;
  text-align: justify;
}

.content {
  flex-wrap: wrap;
  margin: 0.5rem;
}

.top {
  flex-wrap: wrap;
  justify-content: center;
  margin: 0.5rem;
}

.adress {
  flex-wrap: wrap;
  justify-content: space-around;
  margin: 0.5rem;
}

.outers {
  flex-wrap: wrap;
  justify-content: space-around;
  margin: 0.5rem;
}

.mayor {
  color: #00bfff;
}

i {
  display: flex;
  place-items: center;
  place-content: center;
  width: 32px;
  height: 32px;

  color: var(--color-text);
}

h3 {
  font-size: 1.2rem;
  font-weight: 500;
  margin-bottom: 0.4rem;
  color: var(--color-heading);
}

@media (min-width: 1024px) {
  .item {
    margin-top: 0;
    padding: 0.4rem 0 1rem calc(var(--section-gap) / 2);
  }

  i {
    top: calc(50% - 25px);
    left: -26px;
    position: absolute;
    border: 1px solid var(--color-border);
    border-radius: 8px;
    width: 50px;
    height: 50px;
  }

  .item:before {
    content: ' ';
    border-left: 1px solid var(--color-border);
    position: absolute;
    left: 0;
    bottom: calc(50% + 25px);
    height: calc(50% - 25px);
  }

  .item:after {
    content: ' ';
    border-left: 1px solid var(--color-border);
    position: absolute;
    left: 0;
    top: calc(50% + 25px);
    height: calc(50% - 25px);
  }

  .item:first-of-type:before {
    display: none;
  }

  .item:last-of-type:after {
    display: none;
  }
}
</style>
