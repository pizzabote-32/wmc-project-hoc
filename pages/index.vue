<template>
    <div>
        <Navbar />
        <AddPostLink />
        <PostContainer />
    </div>
</template>
<script>/*
<p>Paul hat das geschrieben: {{ text }}</p>


export default {
    data(){
        return {
            text: ''
        }
    },
  mounted(){
    fetch('http://127.0.0.1:8055/items/Kommentar').then(data => data.json()).then(data => {
        this.text = data.data[0].Titel
    });
  }
}*/

import AddPostLink from '~/components/AddPostLink.vue';
</script>