<template>
    <div>
        <div class="contact-wrapper flex p-24">
            <div class="contact-text-wrapper flex-col text-left pr-40">
                <h3 class="text-5xl font-bold">Let's Get In Touch!</h3>
                <p class="text-4xl">Are there Airports or Hotels you want to see partner with us or are you looking to become a partner?</p>
            </div>
            <Button msg="CONTACT US!" class="w-2/6 whitespace-nowrap max-h-11" />
        </div>
    </div>
</template>


<script>
import Button from './Button';

export default {
  name: 'Contact',
  components: {
    Button,
  }
}
</script>