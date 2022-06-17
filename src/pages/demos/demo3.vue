<template>
  <body>
  <main>
    <div i-carbon-campsite text-4xl inline-block />
    <p>
      <a rel="noreferrer" href="https://github.com/antfu/vitesse-lite" target="_blank">
        Vitesse Lite
      </a>
    </p>
    <p>
      <em text-sm op75>Opinionated Vite Starter Template</em>
    </p>
    <div py-4 />
  </main>
  <footer>
   <section>
     <h4>服务</h4>
     <li>人工服务</li>
     <li>自动服务</li>
   </section>
    <section><h4>服务</h4>
      <li>人工服务</li>
      <li>自动服务</li></section>
    <section><h4>服务</h4>
      <li>人工服务</li>
      <li>自动服务</li></section>
  </footer>
  </body>
</template>

<style scoped>
body{
  display: flex;
  height: 80vh;
  width: 50vh;
}
main{
  background: beige;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

footer{
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  height: 50px;
  background: #e8e7e7;
  border-top: solid 1px  #70b8f8;
}
footer section{
  flex: 1;
  display: flex;
  flex-direction: column-reverse;
  border-right: solid 1px #70b8f8;
}
footer section :last-child{
  border-right: none;
}
footer section h4 {
  flex: 0 0 50px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: center;
  cursor: pointer;
}
footer section li {
  border-radius :7px;
  margin-bottom: 5px;
  margin: 5px;
  flex: 1 0 50px;
  display: flex;
  flex-direction: column;
  border: solid 1px  #70b8f8;
  text-align: center;
  justify-content: center;
  margin-bottom: 1px;
  cursor: pointer;
}
</style>
