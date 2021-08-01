<template>
    <div id="buttonthree">
        <button class="btn btn-danger" @click="count += 1"> dislike : ({{ count }})</button>
    </div>
</template>
<script>
export default {
    name : 'buttonthree',
    data: function(){
        return { count:0 }
    }
}


</script>


