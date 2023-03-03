<template>
    <div class="container">
        <section class="nav-bar">
            <p>Adeyemi</p>
            <ul>
                <li>Home</li>
                <li>About</li>
                <li>Contact</li>
                <li>Projects</li>
            </ul>
        </section>
        <section class="card-list">
            <div> <Card /> </div>
            <div> <Card /> </div>
            <div> <Card /> </div> 
            <div> <Card /> </div>
            <div> <Card /> </div>
            <div> <Card /> </div> 
            <div> <Card /> </div>
            <div> <Card /> </div>
            <div> <Card /> </div>
            <div> <Card /> </div>
            <div> <Card /> </div>
            <div> <Card /> </div>
            <div> <Card /> </div>
            <div> <Card /> </div>
            <div> <Card /> </div>
            <div> <Card /> </div>
            <div> <Card /> </div>
            <div> <Card /> </div>
            <div> <Card /> </div>
            <div> <Card /> </div>
            <div> <Card /> </div>
            <div> <Card /> </div>
            <div> <Card /> </div>
            <div> <Card /> </div>
        </section> 
    </div>
</template>

<script>
import MyCard from './MyCard.vue';


export default {
    name: 'HomePage',
    components: {
        Card: MyCard
    }
}
</script>

<style>
@import '../styles/main.css'
</style>