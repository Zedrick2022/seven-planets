<!DOCTYPE html>
<html lang="en">
<head>
  <style type="text/css">
      body {
  background-color: black;
}

.solar-system {
  width: 400px;
  height: 400px;
  margin: 0 auto;
  position: relative;
  animation: rotate 15s infinite linear;
}

.sun {
  width: 100px;
  height: 100px;
  margin: 0 auto;
  border-radius: 50%;
  background-color: yellow;
}

.planet {
  width: 20px;
  height: 20px;
  border-radius: 50%;
  position: absolute;
}

.mercury {
  top: 20%;
  left: 42%;
  background-color: #d3d3d3;
  animation: rotate 2s infinite linear;
}

.venus {
  top: 25%;
  left: 35%;
  background-color: #e07a57;
  animation: rotate 4s infinite linear;
}

.earth {
  top: 30%;
  left: 28%;
  background-color: #2e86c1;
  animation: rotate 6s infinite linear;
}

.mars {
  top: 35%;
  left: 20%;
  background-color: #d35400;
  animation: rotate 8s infinite linear;
}

.jupiter {
  top: 40%;
  left: 13%;
  background-color: #f8c471;
  animation: rotate 10s infinite linear;
}

.saturn {
  top: 45%;
  left: 6%;
  background-color: #f1c40f;
  animation: rotate 12s infinite linear;
}

.uranus {
  top: 50%;
  left: 6%;
  background-color: #5dade2;
  animation: rotate 14s infinite linear;
}

.neptune {
  top: 55%;
  left: 6%;
  background-color: #7d3c98;
  animation: rotate 16s infinite linear;
}

@keyframes rotate {
  0% {
    transform: rotate(0);
  }
  100% {
    transform: rotate(1turn);
  }
}
  </style>
    <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Planet Animation</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="solar-system">
    <div class="sun"></div>
    <div class="planet mercury">mercury</div>
    <div class="planet venus">venus</div>
    <div class="planet earth">earth</div>
    <div class="planet mars">mars</div>
    <div class="planet jupiter">jupiter</div>
    <div class="planet saturn">saturn</div>
    <div class="planet uranus">uranus</div>
    <div class="planet neptune">neptune</div>
  </div>
</body>
</html>
