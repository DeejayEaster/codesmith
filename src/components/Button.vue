<template>
    <button class="px-4 py-2 mt-8 border-2 border-solid border-black">{{ msg }}</button>
</template>

<script>
export default {
  name: 'Button',
  props: {
      msg: String,
  }
}
</script>