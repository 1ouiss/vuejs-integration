<template>
    <aside>ASIDE {{ title }}</aside>
</template>

<script>
export default{
    name: 'AsideComponent',
    props: {
        title: String
    }
}
</script>