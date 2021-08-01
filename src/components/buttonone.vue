<template>
    <div id="buttonone">
        <button class="btn btn-primary" @click="count += 1"> like : ({{ count }})</button>
    </div>
</template>
<script>
export default {
    name : 'buttonone',
    data: function(){
        return { count:0 }
    }
}


</script>
