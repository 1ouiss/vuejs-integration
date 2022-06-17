<template>
  <HeaderComponent></HeaderComponent>
  <router-view/>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
export default{
  name: 'App',
  components: {
    HeaderComponent
  }
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

body,h1,ul{
    margin : 0;
    padding: 0;
    font-family: 'Roboto', sans-serif;
}
header,footer{
    background-color: #f1f1f1;
    width:100%;
    margin : 0;
    text-align: center;
    padding: 50px 0 ;
}

h1,nav{
    padding: 50px;
}

ul{
   list-style: none;
   display: flex;
   justify-content: space-between;
   flex-wrap: wrap;
}

#mainContainer{
    display: flex;
    flex-wrap: wrap;
}
main,aside{
    height: 400px;
    display: flex;
    align-items: center;
    justify-content: center;
}

main{
    background-color:#aaa;
    width: 70%;
}
aside{
    background-color:#ccc;
    width: 30%;
}

@media screen and ( max-width:768px){
    main,aside{
        width: 100%;
    }
}

/* nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
} */
</style>
