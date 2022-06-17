<template>
    <main>MAIN {{ title }}</main> 
</template>

<script>
export default{
    name: 'MainComponent',
    props: {
        title: String
    }
}
</script>