<template>
  <div class="test1">
    {{ name }}

    <button
      :disabled="btnState"
      @click="changeName">Change Name</button>
  </div>
</template>

<script>
export default {
  namef: 'Skills',
  data () {
    return {
      name: 'timx was hessssssssssrerrv',
      btnState: true
    }
  }
}
</script>

<style scoped>
 .alert {
    background-color: yellow;
    width:100%;
    height: 30px;
  }
</style>
