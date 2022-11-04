<template>
    <h1>Peer Connector</h1>
</template>
  
  <script>
  import {Connector} from '@espruino-tools/peer'
 
  let p = new Connector()

  p.connectData();

  export default {
    name: 'Peer-page',
  }
  </script>
  