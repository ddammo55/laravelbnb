<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Example Component</div>

                    <div class="card-body">
                        <p>{{ greeting }}</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        data:function(){
            return{
                greeting:'Hello'
            }
        },
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>


<style>
p{
    font-size: 2em;
    color: tomato;
    text-align: center;
}
</style>
