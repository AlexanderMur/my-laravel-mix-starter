<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card card-default">
                    <div class="card-header">Example Component</div>

                    <div class="card-body">
                        I'm an example component.31311
                    </div>
                    Clicked: {{i}} times! HOT
                    <button v-on:click="i++">Click me!!!!</button>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        data(){
          return {
              i: 0
          }
        },
        name: 'example-component',
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
