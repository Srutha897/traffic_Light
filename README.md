# traffic_Light
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div class="bg-color">
        <h1 class="mainheading">Traffic Light</h1>
        <div class="d-flex flex-row justify-content-center m-5">
            <div class="d-flex flex-column">
                <button id="stopButton" class="button" onclick="turnOnRed()">Stop</button>
                <button id="readyButton" class="button" onclick="turnOnYellow()">Ready</button>
                <button id="goButton" class="button" onclick="turnOnGreen()">Go</button>
            </div>
            <div class="traffic-light">
                <div id="stopLight" class="bulb"></div>
                <div id="readyLight" class="bulb"></div>
                <div id="goLight" class="bulb"></div>
            </div>
        </div>
    </div>
</body>

</html>
