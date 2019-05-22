<template>
    <div id="test">
        <head>
            <link rel="stylesheet" href="//fonts.googleapis.com/css?family=Roboto:300,400,500,700,400italic">
            <link rel="stylesheet" href="//fonts.googleapis.com/icon?family=Material+Icons">
            <script src="https://cdnjs.cloudflare.com/ajax/libs/vue/2.4.2/vue.js"></script>
            <script src="https://cdnjs.cloudflare.com/ajax/libs/vue-material/0.7.4/vue-material.js"></script>
        </head>

        <div id="app">
            <md-layout id="container">
                
                <md-layout md-flex-xsmall="100" md-flex-small="100" md-flex-medium="100" md-flex-large="100" md-flex-xlarge="100">
                    1
                </md-layout>
                <md-layout md-flex-xsmall="100" md-flex-small="100" md-flex-medium="50" md-flex-large="50" md-flex-xlarge="50">
                    2
                </md-layout>
                <md-layout md-flex-xsmall="100" md-flex-small="100" md-flex-medium="50" md-flex-large="50" md-flex-xlarge="50">
                    3
                </md-layout>
                <md-layout md-flex-xsmall="50" md-flex-small="50" md-flex-medium="25" md-flex-large="25" md-flex-xlarge="25">
                    4
                </md-layout>
                <md-layout md-flex-xsmall="50" md-flex-small="50" md-flex-medium="25" md-flex-large="25" md-flex-xlarge="25">
                    5
                </md-layout>
                <md-layout md-flex-xsmall="50" md-flex-small="50" md-flex-medium="25" md-flex-large="25" md-flex-xlarge="25">
                    6
                </md-layout>
                <md-layout md-flex-xsmall="50" md-flex-small="50" md-flex-medium="25" md-flex-large="25" md-flex-xlarge="25">
                    7
                </md-layout>
                <md-layout md-flex-xsmall="50" md-flex-small="50" md-flex-medium="66" md-flex-large="66" md-flex-xlarge="66">
                    8
                </md-layout>
                <md-layout md-flex-xsmall="50" md-flex-small="50" md-flex-medium="33" md-flex-large="33" md-flex-xlarge="33">
                    9
                </md-layout>
            </md-layout>
        </div>    
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
@import url('https://cdnjs.cloudflare.com/ajax/libs/vue-material/0.7.4/vue-material.css');


#container > .md-layout {
  background-color: white;
  min-height: 100px;
  border-color: black;
  align-items: center;
  justify-content: center;
  /*border-style: dotted;*/
  border-width: 1px;
  padding: 8px;
}

body {
  background: #eee;
}
</style>

