<template>
  <h1>{{ msg }}</h1>

  <div class="card">

<img src="https://i.pinimg.com/564x/c4/81/c0/c481c067ad2e11fab13ffe39bc0fd975.jpg" alt="Card Image">

<h2>Welcome</h2>

<p>I was tasked with making a card for this class. I decided to keep it simple and nice. I also decided to add my handsome face to it. </p>

<a style=text-decoration: none;href="https://hax.psu.edu">
  <button class="cool-button">DETAILS</button>
</a>
</div>

<button id="duplicate">DUPLICATION MACHINE</button>
<button id="change-color">COLOR CHANGING MACHINE</button>
<button id="change-text">TEXT CHANGING MACHINE</button>
<button class="delete">DELETING MACHINE</button>
  <p>
    Edit
    <code>components/HelloWorld.vue</code> to test hot module replacement.
  </p>
</template>

<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
  msg: String
})

const state = reactive({ count: 0 })
</script>

<style scoped>
a {
  color: #42b983;
}
</style>
