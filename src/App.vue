<script>

import {defineComponent} from "vue";
import IconDocumentation from "@/components/icons/IconDocumentation.vue";

export default defineComponent({
  components: {IconDocumentation}

})


</script>

<template>
  <header class="cabeçalho">
    <img id="icon_menu" src="https://cdn-icons-png.flaticon.com/512/1243/1243926.png?w=740&t=st=1673358784~exp=1673359384~hmac=fda79b37e4d733221221de79d9f947768508a5e6cebfa6353ac6bf8e6cb4216f">
      <div id="escrita">

        <div id="portal">Portal </div>
        <span id="solar">Solar</span>
        <img id="logo_cabeçalho" src="https://s3.amazonaws.com/gupy5/production/companies/39836/career/89638/images/2022-09-05_13-27_logo.png">

      </div>
    </header>
    <main>
      <div id="base_ft">
        <div class="fundo_titulo">
          Usina - EHF9B78EAI4127 - Lucas Monari dos Santos
        </div>

        <div id="espaço_usina">
          <img id="usina" src="https://s2.glbimg.com/WdsHmILtyeubAxY6jSOD5OZNBVI=/0x0:1500x999/924x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_59edd422c0c84a879bd37670ae4f538a/internal_photos/bs/2021/N/k/B1pS8mTgCUBgKLYcrrTQ/energia-solar-em-casa.jpg">
        </div>

        <div id="info_energia">
          <div id="ene_dia">Energia do dia:</div>

          <div id="qnt_energia_num"><spam id="num_energ">50,7</spam>khw</div>
        <div id="qnt_energia">
          <img id="icon_energia" src="https://cdn-icons-png.flaticon.com/512/4515/4515788.png">
        </div>
        </div>
        <div id="pos_info">
          <table id="tabela_ela">
            <tr>
              <td>Potencia ativa:  <span class="tabe_info">5,0</span>kW  <p>instantâneos</p></td>
              <td>Árvores plantadas: <span class="tabe_info">234</span><p>desde o inicio</p></td>
            </tr>
            <tr>
              <td>Energia gerada: <span class="tabe_info">158,6</span>kWh <p>no mês</p></td>
              <td>Energia Total: <span class="tabe_info">17,2</span>MWh <p>gerada</p></td>
            </tr>

          </table>
        </div>
        <div id="info_energia2">
          <div id="ene_dia">Equivalente a:</div>

          <div id="qnt_energia_num"><spam id="num_energ">848,5</spam>km </div>
          <div id="qnt_energia">
            <img id="icon_energia" src="https://cdn-icons-png.flaticon.com/512/3444/3444036.png">
          </div>
        </div>
      </div>



  </main>
</template>