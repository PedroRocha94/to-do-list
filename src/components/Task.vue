<template>
  <div class="task">
    <fieldset class="fieldset">
      <legend class="fieldset-title">
        <div class="fieldset-status">
          <div class="fieldset-status-color"> </div>
          <span class="fieldset-status-text">Urgente</span>
        </div>
        <span class="fieldset-title-text"> {{ msg }} </span>
      </legend>
      <p class="fieldset-text">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem rem 
        eligendi eaque doloribus cumque excepturi impedit iusto. Distinctio vero 
        enim magni deserunt sed quae, quos libero corporis in dolorem impedit.
      </p>
    </fieldset>
  </div>
</template>

<script>
export default {
  name: 'Task',
  data() {
    return {
      msg: 'Mandar mensagem para o tio Ben'
    }
  }
}
</script>