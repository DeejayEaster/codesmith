<template>
    <div class="hero-wrapper bg-sectionGrey p-28">
        <h2 class="text-5xl p-12">Dynamic Title Information</h2>
        <p class="text-4xl">Dynamic location and airport names with default text</p>
        <Button msg="Choose Location" />
    </div>
</template>


<script>
import Button from './Button';

export default {
  name: 'Hero',
  components: {
    Button,
  }
}
</script>
