<template>
    <div class="hero-wrapper bg-sectionGrey p-28 pb-36">
        <div class="w-3/6 m-auto">
            <h2 class="text-5xl p-12 font-bold">It doesn’t look like you’re there yet.</h2>
            <p class="text-4xl">Airport Name and Hotel Name are nearby, where would you like your food delivered to?</p>
            <Button msg="Choose Location" class="bg-white mt-12" />
        </div>
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
