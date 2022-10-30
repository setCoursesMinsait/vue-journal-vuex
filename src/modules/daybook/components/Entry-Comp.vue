<template>
  <div
    class="entry-container mb-3 pointer p-2"
    @click="$router.push({name: 'entry', params: { id: 10 } })"
  >
    <!-- Titulo -->
    <div
      class="entry-title d-flex"
    >
      <span class="text-success fs-5 fw-bold">29</span>
      <span class="mx-1 fs-5">Octubre</span>
      <span class="mx-2 fw-light">2022</span>
    </div>
    <div class="entry-description">
      Reprehenderit culpa eu commodo est velit non laborum incididunt ipsum. Elit est amet ullamco cupidatat qui veniam consequat elit aliquip mollit voluptate id. Ipsum id nisi magna consectetur esse. Velit qui fugiat aliqua incididunt consequat ullamco culpa ex.
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  .entry-container{
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover {
      background-color: lighten($color: grey, $amount: 45);
      transition: 0.2s all ease-in;
    }

    .entry-transition{
      font-size: 12px;
    }
  }
</style>