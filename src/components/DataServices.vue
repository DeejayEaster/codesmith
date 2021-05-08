<template>
    <div class="data-serv-wrapper p-12 mb-8">
        <div class="m-auto w-4/6">
            <div class="data-text-wrapper">
                <p class="text-big font-bold text">Accompany Data Services</p>
                <p class="text-4xl mt-8 mb-12">Useful Information to Protect Passengers!</p>
            </div>
            <div class="data-card-wrapper flex justify-between">
                <div class="data-card w-4/12 flex-col justify-center border-solid border-sectionGrey border-2 p-8">
                    <div class="img-replace w-60 h-60 m-auto mb-4"></div>
                    <p class="text-2xl">Save money by reporting your height & weight to airlines quicker!</p>
                </div>
                <div class="data-card w-4/12 flex-col mx-16 justify-center border-solid border-sectionGrey border-2 p-8">
                    <div class="img-replace w-60 h-60 m-auto mb-4"></div>
                    <p class="text-2xl">Gather information directly from other passengers on possible COVID-19 symptoms!</p>
                </div>
                <div class="data-card w-4/12 flex-col justify-center border-solid border-sectionGrey border-2 p-8">
                    <div class="img-replace w-60 h-60 m-auto mb-4"></div>
                    <p class="text-2xl">We gather your data solely with passenger safety in mind!</p>
                </div>
            </div>
            <Button msg="Submit Your Data!" class="mt-12"/>
        </div>
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
