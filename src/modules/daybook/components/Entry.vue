<template>
  <div
  class="entry-container mb-3 pointer p-2"
  @click="$router.push({ name: 'entry', params: { id: 10 } })"
  >
    <!-- Titulo -->
    <div class="entry title d-flex">
        <span class="text-success fs-5 fw-bold">19</span>
        <span class="mx-1 fs-5">Septiembre</span>
        <span class="mx-2 fw-light">2022</span>
    </div>
    <div class="entry-description">
    Sunt sunt ea nostrud amet commodo proident deserunt et quis exercitation non esse. Duis deserunt officia velit aute dolor eu pariatur sit officia amet nulla. Eu veniam incididunt ipsum est reprehenderit. Cillum sunt ullamco commodo laborum. Irure amet ex veniam ea nisi consequat.
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

    .entry-description{
        font-size: 12;
    }
}

</style>