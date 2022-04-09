<template>
 <h1>div 요소를 이요한 레이아웃</h1>
 <div id="header">
   <h2>Header 영역</h2>
  </div>
  <div id="nav">
    <h2>NAV 영역</h2>
  </div>
  <div id="section">
    <p>SECTION 영역</p>
  </div>
  <div id="footer">
    <h2>FOOTER 영역</h2>
  </div>


</template>

<script>






</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

#header {
  background-color : lightgrey;
  height: 300px;
}

#nav {
  background-color : #339999;
  color:white;
  width:200px;
  float:left;
}

#section {
  width:200px;
  text-align:left;
  float:left;
  padding:5px;
}

#footer {
  background-color:#FFCC00;
  height:300px;
  clear:both;
}

#header, #nav, #section, #footer { text-align:center; }
#header, #footer { line-height:300px; }
#nav, #section { line-height:2000px; }
</style>
