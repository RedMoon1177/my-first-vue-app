<template>
  <div id="p-app-header">
    <p><span id="p-sitename">MS. FOOD HUB</span><br>
      <span id="p-logo-msg">Eating Around The World</span>
    </p>
    <div id="p-navbar">
      <div><a class="p-navitem" href="#">NEWS</a></div>
      <div><a class="p-navitem" href="#">FOOD & HEALTH</a></div>
      <div><a class="p-navitem" href="#">COOKING TIPS</a></div>
      <div><a class="p-navitem" href="#">Q&A</a></div>
    </div>
  </div>
</template>

<style>
#p-app-header {
  background-color: #E95A14;
  color: whitesmoke;
  font-family: monospace;
  padding-left: 20px;
  padding-top: 2px;
  padding-bottom: 2px;

  display: flex;
  align-items: center;
  column-gap: 10%;
}

#p-sitename {
  font-weight: bold;
  font-size: 30px;
}

#p-logo-msg {
  font-style: italic;
  font-size: 14px;
}

#p-navbar {
  display: flex;
  column-gap: 20px;
}

.p-navitem {
  color: whitesmoke;
  font-weight: bold;
  font-size: 20px;
  text-decoration: none;
}
</style>