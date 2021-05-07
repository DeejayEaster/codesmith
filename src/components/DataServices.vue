<template>
    <div class="data-serv-wrapper p-12 mb-12">
        <div class="data-text-wrapper">
            <p class="text-5xl">Accompany Data Services</p>
            <p class="text-4xl mt-8 mb-12">Useful Information to Protect Passengers!</p>
        </div>
        <div class="data-card-wrapper flex justify-between">
            <div class="data-card flex-col justify-center border-solid border-sectionGrey border-2 p-8">
                <div class="img-replace w-3/6 m-auto mb-4"></div>
                <p>Save money by reporting your height & weight to airlines quicker!</p>
            </div>
            <div class="data-card flex-col mx-8 justify-center border-solid border-sectionGrey border-2 p-8">
                <div class="img-replace w-3/6 m-auto mb-4"></div>
                <p>Gather information directly from other passengers on possible COVID-19 symptoms!</p>
            </div>
            <div class="data-card flex-col justify-center border-solid border-sectionGrey border-2 p-8">
                <div class="img-replace w-3/6 m-auto mb-4"></div>
                <p>We gather your data solely with passenger safety in mind!</p>
            </div>
        </div>
        <Button msg="Submit Your Data!" />
    </div>
</template>


<script>
import Button from './Button';

export default {
  name: 'DataServices',
  components: {
    Button,
  }
}
</script>
