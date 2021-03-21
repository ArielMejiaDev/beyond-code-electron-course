<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p class="text-xl font-sembold text-gray-500">Code here</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>
