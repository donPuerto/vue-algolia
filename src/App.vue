<template>
  <div id="app">
    <h1>Vue Algolia Sandbox</h1>
  </div>
</template>

<script>
// import algoliasearch from 'algoliasearch';
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  mounted () {
    // var client = algoliasearch("CWXDLY1OTX", "4254350ce0d92f61642c728261e9c6a0");
    // var index = client.initIndex('contacts');


    // var objects = [{
    //   objectID: 'myID1',
    //   firstname: 'Jimmie',
    //   lastname: 'Barninger'
    // }, {
    //   objectID: 'myID2',
    //   firstname: 'Warren',
    //   lastname: 'Speach'
    // }];

    // index.addObjects(objects, function(err, content) {
    //   console.log('content',content);
    //   if (err) {
    //     console.error('err', err);
    //   }
    // });

  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
