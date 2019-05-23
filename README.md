# Gallery-Manager
stock your photos here
<!DOCTYPE html>
<html>
<head>
	<title>Lab Quiz</title>
	
	<link rel="stylesheet" href="css/bootstrap.min.css">
	<script src="js/jquery.min.js"></script>
	<script src="js/bootstrap.min.js"></script>
	<script src="JAVASCRIPT.js"></script>
    
	
</head>
<body>
	<div class="container">
	<div class="row" style="margin-top: 20px">
		<button type="button" class="btn btn-info" data-toggle="modal" data-target="#myModal">Add Image</button>
    	<button type="button" class="btn btn-primary" onclick="del()">Delete</button>  
	</div>
		<div style="border: solid brown 5px; margin-top: 30px; border-radius: 10px" id="items">
			<center><p style="font-size: 40px" id="itemss" border-radius="">Gallery</p></center>
			<div class="thumbnail" id="kuan">

				<div class="caption">
					<p name="cap" id="p"></p>	
				</div>
		</div>
		</div>
	</div>
	<div id="myModal" class="modal fade" role="dialog">
  <div class="modal-dialog">

    <!-- Modal content-->


    
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal">&times;</button>
        <h4 class="modal-title">Add Image</h4>
      </div>
      <form name="form1">
      <div class="modal-body">
      	<p>Select Image</p>
       <input type="file" name="imagesrc"></input>
       <p>Caption</p>
       <input type="text" name="caption1" id="cp"></input>
      </div>
        <button type="button" class="btn btn-primary" onclick="Add(this.form)" data-dismiss="modal">Add</button>
  </form>
    </div>

  </div>
</div>

</body>
</html>
