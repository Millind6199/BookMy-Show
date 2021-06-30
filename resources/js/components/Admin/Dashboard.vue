<template>
<div>
<index/>
    <Sidebar/>
    <Footer/>
</div>
</template>

<script>
import index from '../index';
import Sidebar from "../Sidebar";
import Footer from "../Footer";
export default {
    name: "Dashboard",
    components:{
        index,
        Sidebar,
        Footer
    },
}
</script>

<style scoped>

</style>
