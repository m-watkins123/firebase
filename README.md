# firebase
<!DOCTYPE html>
<html lang="en-us">
<head>
<meta charset="UTF-8">
	<title>Train Schedule</title>
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" integrity="sha384-1q8mTJOASx8j1Au+a5WDVnPi2lkFfwwEAa8hDDdjZlpLegxhjVME1fgjWPGmkzs7" crossorigin="anonymous">
   

    <script src="https://www.gstatic.com/firebasejs/live/3.0/firebase.js"></script>
</head>
<body>
<div class ="container">
<div class="jumbotron">
<h1 class="text-center">Train Time</h1>
</div>
<div class="row">
<div class="col-md-6">
<div class="panel panel-default">
<div class="panel-heading">
<h3 class="text-center""panel-title">Current Train Schedule</h3></div>
<div class="panel-body">
<table class="table table hoover" id="traintable">
<thead>
<tr>
<th>Train Name</th>
<th>Destination</th>
<th>Frequency</th>
<th>Next Arrival</th>
<th>Minutes Away</th>
</tr>
</thead>
<tbody>
<tr>
<td>Train</td>
<td>New York</td>
<td>2</td>
<td>12:00</td>
<td>6 mins</td>
</tr>
<tr>
<td>Train</td>
<td>Paris</td>
<td>6</td>
<td>7:00</td>
<td>20 mins</td>
</tr>
<tr>
<td>Train</td>
<td>Mumbai</td>
<td>10</td>
<td>9:00</td>
<td>60 mins</td>
</tr>
</tbody>
</table>

</div>
</div>
</div>
</div>
</div>
<div class="panel panel-primary">
<div class="panel-heading">
<h3 class="panel-title">
<strong>Add Train</strong>
</h3>
</div>
<div class="panel-body">
<form>
<div class="form-group">
<label for="">Train Name</label>
<input class="form-control" id="TrainNameInput" type="text"/>
</div>
<div class="form-group">
<label for="">Destination</label>
<input class="form-control" id="destinationinput" type="text"/>
<div class="form-group">
<label for="">
First Train Time(HH:mm - miltary time)
</label>
<input class="form-control" id="firstTimeInput" type="text"/>
<div class="form-group">
<label for="">Frequency</label>
<input class="form-control" id="frequencyInput" type="text"/>
</div>
<button class="btn btn-primary" id="addtrainBtn" type="submit"></button>
</div>
</div>
</form>
</div>
</div>

</body>
</html>