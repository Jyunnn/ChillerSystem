<template>
  <div class="about container">
    <div class="item bar"></div>
    <div class="item chart1">
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
      <p>This is an Home page</p>
    </div>
    <div class="item chart2"></div>
    <div class="item chart3"></div>
    <div class="item chart4"></div>
    <div class="item chart5"></div>
    <div class="main"></div>
    <div class="item water1"></div>
    <div class="item water2"></div>
    <div class="item piechart1"></div>
    <div class="item table1"></div>
    <div class="item chart6"></div>
    <div class="item chart7"></div>
  </div>
</template>

<style>
.container {
  display: grid;
  width: 100vw;
  height: 100vh;
  padding: 1.5em;
  grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
  gap: 1.5em 1.5em;
  grid-auto-flow: row;
  grid-template-areas:
    'chart1 chart1 chart1 bar bar bar bar bar bar piechart1 piechart1 piechart1'
    'chart1 chart1 chart1 main main main main main main piechart1 piechart1 piechart1'
    'chart2 chart2 chart2 main main main main main main table1 table1 table1'
    'chart2 chart2 chart2 main main main main main main table1 table1 table1'
    'chart3 chart3 chart3 main main main main main main table1 table1 table1'
    'chart3 chart3 chart3 main main main main main main table1 table1 table1'
    'chart4 chart4 chart4 water1 water1 water1 water1 water1 water1 chart6 chart6 chart6'
    'chart4 chart4 chart4 water1 water1 water1 water1 water1 water1 chart6 chart6 chart6'
    'chart5 chart5 chart5 water2 water2 water2 water2 water2 water2 chart7 chart7 chart7'
    'chart5 chart5 chart5 water2 water2 water2 water2 water2 water2 chart7 chart7 chart7';
}

.item {
  padding: 0.5em;
  border-radius: 0.5em;
  background-color: #d1d1d136;
}

.chart1 {
  grid-area: chart1;
}

.chart2 {
  grid-area: chart2;
}

.chart3 {
  grid-area: chart3;
}

.chart4 {
  grid-area: chart4;
}

.chart5 {
  grid-area: chart5;
}

.bar {
  grid-area: bar;
}

.main {
  grid-area: main;
}

.water1 {
  grid-area: water1;
}

.water2 {
  grid-area: water2;
}

.piechart1 {
  grid-area: piechart1;
}

.table1 {
  grid-area: table1;
}

.chart6 {
  grid-area: chart6;
}

.chart7 {
  grid-area: chart7;
}
</style>
