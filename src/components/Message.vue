<template>
  <div class="box">
    <div class="columns">
      <div class="column is-half">
        <p>
          <slot></slot>
        </p>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  
}
</script>

<style>
  .box{ background: #e3e3e3; padding: 10px; border: 1px solid #c5c5c5; margin-bottom: 1em;}
</style>
