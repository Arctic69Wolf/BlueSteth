# BlueSteth 
<html>    
<head>    
    <title>Login Form</title>    
    <link rel="stylesheet" type="text/css" href="style.css">    
</head>    
<body>    
    <h2>Login Page</h2><br>    
    <div class="login">    
    <form id="login" method="get" action="login.php">    
        <label><b>User Name     
        </b>    
        </label>    
        <input type="text" name="Uname" id="Uname" placeholder="Username">    
        <br><br>    
        <label><b>Password     
        </b>    
        </label>    
        <input type="Password" name="Pass" id="Pass" placeholder="Password">    
        <br><br>    
        <input type="button" name="log" id="log" value="Log In Here">       
        <br><br>    
        <input type="checkbox" id="check">    
        <span>Remember me</span>    
        <br><br>    
        Forgot <a href="#">Password</a>    
    </form>     
</div>    
    <meta charset="UTF-8">
<title>Simple Recorder.js demo with record, stop and pause</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<div id="controls">
    <button id="recordButton">Record</button>
    <button id="pauseButton" disabled>Pause</button>
    <button id="stopButton" disabled>Stop</button>
</div>
<h3>Recordings</h3>
<ol id="recordingsList"></ol>
<!-- inserting these scripts at the end to be able to use all the elements in the DOM --> 
<script src="https://cdn.rawgit.com/mattdiamond/Recorderjs/08e7abd9/dist/recorder.js"></script>
<script src="Recorder.js"></script>
</body>    
</html>     
