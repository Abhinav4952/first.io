<!doctype html>
<head>
<title>Form 1</title>
<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <style>
hr { 
    display: block;
    margin-top: 0.5em;
    margin-bottom: 0.5em;
    margin-left: auto;
    margin-right: auto;
    border-style: inset;
    border-width: 10px;
}
.button {
    background-color: #4CAF50; /* Green */
    border: none;
    color: white;
    padding: 10px 15px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 10px;
    margin: 4px 2px;
    cursor: pointer;
}
</style>
</head>
<body>

<div class="container">

  <h2>H/w</h2>
		
		

	<div class="form-group">
      <label for="email">Led information</label>
	  <input type="email" class="form-control" id="led" placeholder="LED NO." name="email">
	</div>
	<div class="checkbox">
    <label><input type="checkbox">ck1</label>
	</div>
	<div class="checkbox">
    <label><input type="checkbox">ck2</label>
	</div>
	<div class="checkbox">
    <label><input type="checkbox">ck3</label>
	</div>
	<button class="button" >BTN1</button>


	<button type="submit" class="btn btn-default" color="#008CBA">Btn2</button>
	<table class="table">
  <tr>
    <th>Row1</th>
    <th>Row2</th> 
    <th>Row3</th>
  </tr>
  <tr>
    <td>Row4</td>
    <td>Row5</td> 
    <td>Row6</td>
  </tr>
  <tr>
    <td>Row7</td>
    <td>Row8</td> 
    <td>Row9</td>
  </tr>
</table><hr>
<h2>S/w</h2>
<div class="form-group">
      <label for="email">Software Config</label>
	  <input type="email" class="form-control" id="soft" placeholder="softNO." name="email">
	</div>
	<div class="form-group">
      <label for="email">Software Btn1</label>
	  <input type="email" class="form-control" id="softb" placeholder="softBNO." name="email">
	</div>
	<button type="submit" class="btn btn-default">Software divsion Btn1</button><br/>
	<div class="form-group">
      <label for="email">Software Btn2</label>
	  <input type="email" class="form-control" id="softb2" placeholder="softBNO2." name="email">
	</div>
	<button type="submit" class="btn btn-default">Software divsion Btn2</button><br/>


  
</div>

</body>
</html>
