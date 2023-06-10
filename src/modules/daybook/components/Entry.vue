<template>
  <div
    class="entry-container mb-3 pointer p-2"
    @click="$router.push({name: 'entry', params: {id: 10}})"
  >
    <div class="entry-title d-flex">
        <span class="text-success fs-5 fw-bold">15</span>
        <span class="mx-1 fs-5">Julio</span>
        <span class="mx-2 fw-light">2021, jueves </span>
    </div>

    <div class="entry-description">
        Cillum officia nulla reprehenderit quis. Do laboris officia id eu. Voluptate sint proident veniam consectetur ad reprehenderit nostrud aliquip elit laborum sint mollit. Fugiat mollit officia aliqua consequat commodo. Do reprehenderit in qui dolore nisi.
    </div>
  </div>
</template>


<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solod #2c3e50;
    transition: 0.2s all ease-in;

    &:hover{
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;

    } 

    .entry-description{
        font-size: 12px;
    }
}



</style>