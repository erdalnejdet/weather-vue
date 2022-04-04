<template>
    <div class="weather-wrap">
  <div class="location-box">
    <div class="location">USA</div>
     <div class="date">PAZARTESİ SALI</div>
    </div>
  </div>

<div class="weather-box">
<div class="temp">18 C</div>
<div class="weather">Rain</div>

</div>
</template>


<style>

.search-box{
  width: 100%;
  margin: bottom 30px;
}
.search-box .search-bar{
  display: block;
  width:100%;
  padding: 15px;
  color: #313131;
  font-size: 20px;
  appearance: none;
  border: none;
  outline: none;
  background: none;

  box-shadow: 0px 0px 8px rgba(0,0,0,0.25);
  background-color: rgba(255, 255, 255, 0.5);
  transition: 0.4;
  
}

.search-box .search-bar:focus{
  box-shadow: 0px 0px 16px rgba(0,0,0,0.25);
  background-color: rgba(255, 255, 255, 0.75);
 border-radius: 16px 0px 16px 0px;


}

.location-box .location{
color: white;
font: size 32px;
font-weight: 1000;
text-align: center;
text-shadow: 1px 3px rgba(0,0,0,0.25);
}
.location-box .date {
  color: white;
font: size 50px;
font-weight: 1000;
text-align: center;
font-style : italic;
}

.weather-box {
  text-align: center;
}
.weather-box .temp {
  display: inline-block;
  padding: 10px 25px;
  color : #fff;
  font-size :102px;
  font-weight: 900;
  text-shadow: 3px 6px rgba(0,0,0,0.25);
  background-color: rgba(255, 255, 255, 0.5);
  border-radius: 16px;
  margin : 30px 0px;
  box-shadow:  3px 6px rgba(0,0,0,0.25);

}


.weather-box .weather{
 color: white;
font: size 48px;
font-weight: 700;
text-align: center;
font-style : italic;
text-shadow: 3px 6px rgba(0,0,0,0.25);
}
</style>