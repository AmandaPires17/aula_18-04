<script>
import MenuLateral from "@/components/MenuLateral.vue";
import HeaderAtividade from "@/components/HeaderAtividade.vue";
import RodapeAtividade from "@/components/RodapeAtividade.vue";
import PrincipalAtividade from "@/components/PrincipalAtividade.vue";
export default {
  components: {
    MenuLateral,
    HeaderAtividade,
    RodapeAtividade,
    PrincipalAtividade,
  },
};
</script>
<template>
  <HeaderAtividade />
  <RodapeAtividade />
  <MenuLateral />
  <PrincipalAtividade />
</template>
