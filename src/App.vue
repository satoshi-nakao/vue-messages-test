<template>
  <div>
   <h1>{{ 'Hello Vuejs!' }}</h1>
   <h1>{{ 12 }}</h1>
  <!-- 下記は上記と同じ意味 -->
   <hr>
   <h2>{{ message+'(data関数のmessageで表示)' }}</h2>
   <h3>{{ number+'(data関数のnumberで表示)' }}</h3>
  </div>
</template>

<script>

export default {
  // data() {
  //   return{
  //     message: 'Hello Vuejs!'
  //   }
  //}
  data :function() {
    return{
      message: 'Hello Vuejs',
      number: 12
    }
  }
}
</script>

