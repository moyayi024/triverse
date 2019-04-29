<template>
<div id="containerpills" class="container">
  <h2>Welcome Brgy Tibay!</h2>
  <br>
  <!-- Nav pills -->
  <ul class="nav nav-pills" role="tablist">
    <li class="nav-item">
      <a class="nav-link active" data-toggle="pill" href="#home">Home</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" data-toggle="pill" href="#menu1">Reservation</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" data-toggle="pill" href="#menu2">Reports</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" data-toggle="pill" href="#menu3">Records</a>
    </li>
  </ul>

  <!-- Tab panes -->
  <div class="tab-content">
    <div id="home" class="container tab-pane active"><br>
      <h3>Timeline</h3>
      <p>dito sa page nato ilalagay yung mga announcements bale mauuna yung pinakahule</p>
    </div>
    <div id="menu1" class="container tab-pane fade"><br>
      <h3>Reservation</h3>
      <p>court reservation/tent/events(zumba)</p>
    </div>
    <div id="menu2" class="container tab-pane fade"><br>
      <h3>Reports</h3>
      <p>dito ilalagay yung mga incidente ng nakawan blotter na parang bitag</p>
    </div>
    <div id="menu3" class="container tab-pane fade"><br>
      <h3>Records</h3>
      <p>dito yung mga magrerquest ng mga papers/ brgy id / brgy clearance etc.</p>
    </div>
  </div>
</div>

</template>

<script>
export default {

}
</script>

<style>
#containerpills {
  position: relative;
  height: 90%;
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px 20px 30px 20px;
  margin-top: 30px;
}
</style>
