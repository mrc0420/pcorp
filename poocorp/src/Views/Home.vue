<template>
  <div id="home">
    <img src="../assets/logo.png" alt="logo" />
    <h1>Kingdom of Poop</h1>
    <ul>
      <li v-for="(product,index) in products" :key="index">product</li>
    </ul>
  </div>
</template>

<script lang="ts">
import {Component, Vue} from 'vue-property-decorator';

@Component
export default class Home extends Vue{
  private products:string[] = [];

}
</script>

