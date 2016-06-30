<!DOCTYPE html>
<html ng-app="fatser">
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.2/jquery.min.js"></script>
  <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
<script src="http://ajax.googleapis.com/ajax/libs/angularjs/1.4.8/angular.min.js"></script>

</head>
<body ng-controller="fatsercon">
<h1> The sample </h1>


<div class="container">

	<button type="button" class="btn" data-toggle="modal" data-target="#mymodal" ng-hide="hider">Open Modal</button>
	<div class="modal fade" id="mymodal" role="dialog" ng-hide="showme" >
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" >&times;</button>
<h4><span class="glyphicon glyphicon-lock"</span> LOGIN</h4>
</div>
<div class="modal-body">
<form role="form">
<div class="form-group">
<label for="user"> <span class="glyphicon glyphicon-user" ></span>Username</label>
<input type="text" class="form-control" id="user" ng-model="username"></input>
</div>

<div class="form-group">
<label for="pwd"> <span class="glyphicon glyphicon-eye" ></span>Password</label>
<input type="text" class="form-control" id="pwd" ng-model="password"></input>
</div>

<div class="form-group">
<button type="button" class="login" ng-click="hider=true" data-dismiss="modal">Login</button>
</div>
</form>
</div>
</div>
</div>
</div>



{{5*5}}



<script >

var app= angular.module('fatser',[]);
app.controller('fatsercon',function($scope){


    });


</script>
</div>
</body>
</html>
