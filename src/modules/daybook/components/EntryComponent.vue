<template>
    <div
        class="entry-container mb-3 pointer p-2"
        @click="$router.push({name: 'entry', params: {id: 1}})"
    >
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">15</span>
            <span class="mx-1 fs-5">Julio</span>
            <span class="mx-2 fw-light">2021,jueves</span>
        </div>

        <div class="entry-description">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad quisquam nobis eos perferendis doloribus quo sunt explicabo, illum voluptatum ex! Ex fugiat fugit eos quod, temporibus pariatur illo harum. Quae! Lorem ipsum dolor sit amet, consectetur adipisicing elit. Natus facilis, dolor, odio iure repudiandae expedita asperiores corrupti nisi deserunt veritatis optio, consequuntur vero molestiae repellendus. Dicta sed a ea eveniet?
        </div>
    </div>
</template>

<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover {
        background-color: lighten($color: grey, $amount: 45);
    }
    .entry-description {
        font-size: 12px;
    }
}
</style>