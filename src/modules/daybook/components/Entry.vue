<template>
  <div class="entry-container mb-3 pointer p-2"
    @click="$router.push({name: 'entry', params:{ id:10 }})">
      <div class="entry-title d-flex">
          <span class="text-success fs-5 fw-bold">15</span>
          <span class="mx-1 fs-5">Julio</span>
          <span class="mx-2 fw-light">2021, jueves</span>
      </div>
      <div class="entry-description">
          Deserunt qui ad ullamco non laboris magna ullamco proident. Labore enim aliquip dolor est deserunt labore ut excepteur excepteur sunt esse ad. Do in dolor proident ut culpa qui commodo ea est dolore aute velit. Laboris ea et nulla dolor adipisicing dolor non labore occaecat mollit dolor labore occaecat. Velit sint consectetur reprehenderit ut magna voluptate anim laboris enim irure. Excepteur quis duis aliqua commodo do in elit laboris non nisi reprehenderit reprehenderit excepteur. Ea amet magna aute sunt incididunt.
      </div>
  </div>
</template>

<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover {
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }
    .entry-description {
        font-size: 12px;
    }
}
</style>