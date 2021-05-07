<template>
    <div>
        <div class="contact-wrapper flex items-center py-24 w-4/6 m-auto">
            <div class="contact-text-wrapper flex-col text-left pr-40">
                <h3 class="text-5xl font-bold">Let's Get In Touch!</h3>
                <p class="text-4xl pt-4 leading-loose">Are there Airports or Hotels you want to see partner with us or are you looking to become a partner?</p>
            </div>
            <Button msg="CONTACT US!" class="w-2/6 whitespace-nowrap " />
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