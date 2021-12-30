<template>
  <div v-show="show" class="overlay">


    <div class="dialog">

      <div class="dialog__content">
        <h2 class="dialog__title" > Delate</h2>
        <p class="dialog__description" >delating that element will delate all related elements </p>
        are you sure 
      </div>

      <hr />

      <div class="dialog__footer">
        <button  @click="cancel" class="dialog__cancel">Cancel</button>
        <button  @click="confirmRo" class="dialog__confirm">Yes, delete it</button>
      </div>

    </div>

  </div>
</template>

<script>
export default {

      props: ['show', 'cancel','confirm']


}
</script>
