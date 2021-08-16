<template>
    <div>
        <span>
            {{text}}
        </span>
        <cmp3></cmp3>
    </div>
</template>

<script>
    module.exports = {
        name: "siblingComponent",
        components: {
          cmp3: httpVueLoader('components/treeComponent/treeComponent.vue')
      },
        data() {
            return {
                text: "sibling Component"
            }
        }
    }
</script>
