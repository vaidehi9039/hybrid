<!DOCTYPE html>
<html>
<head>
 	<meta name="viewport" content="width=device-width, initial-scale=1">
  	<link rel="stylesheet" href="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.css">
	<link rel="stylesheet" href="http://code.jquery.com/mobile/1.4.5/jquery.mobile.structure-1.4.5.min.css" />
 	<script src="http://code.jquery.com/jquery-1.11.3.min.js"></script>
  	<script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
	<link rel="stylesheet" type="text/css" href="./css/mystyle.css">

</head>
<body>
 

	<div data-url="panel-fixed-page1" data-role="page" class="ui-page-theme-b"  id="panel-fixed_page1" data-title="panel fixed positioning">
		<div data-role="header" data-position="fixed" data-theme="a" style="overflow:hidden;">
			<ul data-role="listview">
      				<li><a href="#nav-panel" class="ui-btn ui-icon-home ui-btn-icon-left">Travel</a></li>
			</ul>
			
		</div>

	<div data-role="main" class="ui-content jqm-content jqm-fullwidth" >

		<div data-role="navbar" >
			<label for="search-basic"></label>	
    			<input type="search" name="search" id="search-basic" value=""/>
		
  		</div>
    		

   		<div data-role="navbar" >
     			<ul data-role="listview" data-inset="true" >
      				<li><a href="#"	id="navbar1" ><img src="./images/men.jpg">Men</a></li>
      				<li><a href="#"	id="navbar2" ><img src="./images/girl.jpg">Women</a></li>
      				<li><a href="#" id="navbar3" ><img src="./images/kids.jpg">Kids</a></li>
     			</ul>

   			
  		</div>

    		<div class="ui-grid-b ui-responsive">
      			<div class="ui-block-a">
        			<a href="#" class="ui-btn ui-corner-all ui-shadow"  style="background-color:#8aa64e;border:#4b5b2a;text-color:#ffffff;text-shadow:0 1px 0 #444444">First Column Button</a><br>
        			<span>First Column:</span>
      			</div>
      			<div class="ui-block-b">
        			<a href="#" class="ui-btn ui-corner-all ui-shadow" style="background-color:#8aa64e;border:#4b5b2a;text-color:#ffffff;text-shadow:0 1px 0 #444444">Second Column Button</a><br>
        			<span>Second Column: </span>
      			</div>
      			<div class="ui-block-c">
        			<a href="#" class="ui-btn ui-corner-all ui-shadow" style="background-color:#8aa64e;border:#4b5b2a;text-color:#ffffff;text-shadow:0 1px 0 #444444">Third Column Button</a><br>
        			<span>Third Column: </span>
      			</div>
    		</div>

  
	</div>
	<div data-role="footer" data-position="fixed">
	</div>
	<div data-role="panel" data-position-fixed="true" data-display="push" id="nav-panel">
		
		<h2>Home</h2>

		<ul data-role="listview" data-inset="true" id="item">
    				
        					
         		<li><a href="karnataka.html">Karnataka</a></li>
         		<li><a href="#panel-fixed-page2" >Kerala</a></li>
			<li><a href="#panel-fixed-page2" >Tamilnadu</a></li>
		</ul>
   			
		
	</div>
	


  	
  	

  	
</div>

</body>
</html>
