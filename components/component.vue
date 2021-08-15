<template>
    <div>
        <span>
            {{text}}
        </sapn>
        <hello3></hello3>
    </div>
</template>

<script>
    module.exports = {
        name: "hello",
        components: {
          hello3: httpVueLoader('components/treeComponent/test2.vue')
      },
        data() {
            return {
                text: "hello world"
            }
        }
    }
</script>
