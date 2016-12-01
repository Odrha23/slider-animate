# slider-animate
Slider with animate

Used :

<div class="container main-container">

	<div id="carousel-example-generic" class="carousel slide">
		<!-- Indicators -->
		<ol class="carousel-indicators">
			<li data-target="#carousel-example-generic" data-slide-to="0" class="active"></li>
			<li data-target="#carousel-example-generic" data-slide-to="1"></li>
			<li data-target="#carousel-example-generic" data-slide-to="2"></li>
		</ol>

		<!-- Wrapper for slides -->
		<div class="carousel-inner" role="listbox">
		
			<!-- First slide -->
			<div class="item active deepskyblue">
				
				<div class="carousel-caption">
					<h3 data-animation="animated bounceInLeft">
						This is the caption for slide 1
					</h3>
					<h3 data-animation="animated bounceInRight">
						This is the caption for slide 1
					</h3>
					<button class="btn btn-primary btn-lg" data-animation="animated zoomInUp">Button</button>
				</div>
			</div> <!-- /.item -->
			
			<!-- Second slide -->
			<div class="item skyblue">
				<div class="carousel-caption">
					<h3 class="icon-container" data-animation="animated bounceInDown">
						<span class="glyphicon glyphicon-heart"></span>
					</h3>
					<h3 data-animation="animated bounceInUp">
						This is the caption for slide 2
					</h3>
					<button class="btn btn-primary btn-lg" data-animation="animated zoomInRight">Button</button>
				</div>
			</div><!-- /.item -->
			
			<!-- Third slide -->
			<div class="item darkerskyblue">
				<div class="carousel-caption">
					<h3 class="icon-container" data-animation="animated zoomInLeft">
						<span class="glyphicon glyphicon-glass"></span>
					</h3>
					<h3 data-animation="animated flipInX">
						This is the caption for slide 3
					</h3>
					<button class="btn btn-primary btn-lg" data-animation="animated lightSpeedIn">Button</button>
				</div>
			</div><!-- /.item -->
		
		</div><!-- /.carousel-inner -->

		<!-- Controls -->
		<a class="left carousel-control" href="#carousel-example-generic" role="button" data-slide="prev">
			<span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
			<span class="sr-only">Previous</span>
		</a>
		<a class="right carousel-control" href="#carousel-example-generic" role="button" data-slide="next">
			<span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
			<span class="sr-only">Next</span>
		</a>
	</div><!-- /.carousel -->

</div><!-- /.container -->
