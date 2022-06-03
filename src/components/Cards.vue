<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue';
import DocumentationIcon from './icons/IconDocumentation.vue';
import ToolingIcon from './icons/IconTooling.vue';
import EcosystemIcon from './icons/IconEcosystem.vue';
import CommunityIcon from './icons/IconCommunity.vue';
import SupportIcon from './icons/IconSupport.vue';
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #name>E-VIDA </template>
    <template #recordANS>418374</template>
    <template #corporate>
      Caixa de Assistência do Setor de Energia -EVIDA -Assistência é Saúde
    </template>
    <template #cnpj> 11828089000103 </template>

    <template #public-place> Setor de Habitações Coletivas Geminadas</template>
    <template #number> Quadra 704/705 </template>
    <template #complement> Bloco C, Loja 48 </template>
    <template #district> Asa Norte </template>
    <template #city> Brasília </template>
    <template #state> DF </template>
    <template #code> 70730630 </template>

    <template #ddd> 61 </template>
    <template #telephone> 3966-8300 </template>
    <template #fax> 3966-8302 </template>
    <template #e-mail> governanca@evida.org.br </template>
    <template #representative> Eli Pinto de Melo Junior </template>
    <template #representative-position> Presidente </template>
    <template #registration-date> 12/01/2012 </template>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #name> ABBESS </template>
    <template #recordANS>417734</template>
    <template #corporate>
      Administradora de Benefícios
    </template>
    <template #cnpj> 7525246000126 </template>

    <template #public-place> AV Rio Branco </template>
    <template #number> 120 </template>
    <template #complement> Pavimento 4 - Sala 426 </template>
    <template #district> Centro </template>
    <template #city> Rio de Janeiro </template>
    <template #state> RJ </template>
    <template #code> 20040001 </template>

    <template #ddd> 21 </template>
    <template #telephone> 2270-4971 </template>
    <template #fax> none </template>
    <template #e-mail> comercial@abbess.com.br </template>
    <template #representative> Marcelo Brandão Rocha </template>
    <template #representative-position> Presidente e Tesoureiro </template>
    <template #registration-date> 20/12/2010 </template>

  </WelcomeItem>
</template>
