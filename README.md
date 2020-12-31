<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>Graphs</title>
  
  <!-- HTML -->
  

  <!-- Custom Styles -->
<style>
body {
 font-size: 15px;
 font-family: Courier;
}
.a {
 margin-top: 10px;
} 
.nos {
 margin-left: 20px;
} 
.no {
 transform: rotate(-90deg);
 position: relative;
 right: 170px;
 font-size: 18px;
 top: 10px;
} 
.container {
 display: flex;
 position: relative;
 left: 40px;
 bottom: 280px;
 flex-direction: row;
 width: 280px;
 margin: 10px;
 text-align: center;
 font-size: 15px;
 justify-content: space-evenly;
 background: skyblue;
 border-radius: 20px;
 height: 280px;
} 
.item {
  background-color: lightblue;
  border-radius: 6px;
} 
.ca {
  border: solid 1px lightblue;
  padding: 32px 5px 32px 5px;
  margin: 50px 0px 20px 0px;
} 
.cb {
  border: solid 1px lightblue;
  padding: 12.5px 5px 12.5px 5px;
  margin: 174px 0px 20px 0px;
} 
.cc {
  border: solid 1px lightblue;
  padding: 18px 5px 18px 5px;
  margin: 142px 0px 20px 0px;
} 
.cd {
  border: solid 1px lightblue;
  padding: 19.5px 5px 19.5px 5px;
  margin: 134px 0px 20px 0px;
} 
.co{
  margin: 0px 7px 0px 7px;
  position: relative;
  bottom: 280px;
  left: 70px;
}
.cn {
  position: relative;
  bottom: 294px;
  left: 140px;
  font-size: 20px;
} 
h2 {
  position: relative;
  top: 90px;
} 
h4 {
  position: relative;
  top: 48px;
} 
</style>
</head>

<body>
  <h2>Manipulating Flex Boxes to Make Graphs</h2> <br>
  <h4>Number of Days: 100 to 100,000 Cases</h4> <br>
  <p class="no">No. Of Days</p>
  <div class="nos">
   <p class="a">70</p>
   <p class="a">60</p>
   <p class="a">50</p>  
   <p class="a">40</p>
   <p class="a">30</p>
   <p class="a">20</p>
   <p class="a">10</p>
   <p class="a">0</p>
   </div>
  <div class="container">
   <p class="item ca">64</p>
   <p class="item cb">25</p>
   <p class="item cc">36</p>
   <p class="item cd">39</p>
  </div>
  <span class="co">INDIA</span>
  <span class="co">USA</span>
  <span class="co">ITALY</span>
  <span class="co">FRANCE</span>
  <p class="cn">Country</p>
</body>
</html>
