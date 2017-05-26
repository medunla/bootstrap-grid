# bootstrap-grid
Bootstrap CSS part only Grid System.
 1. bootstrap-grid.css, bootstrap-grid.min.css *(original css)*
 2. bootstrap-grid-custom.css, bootstrap-grid-custom.min.css - *Change css name style
 3.  bootstrap-grid-mix.css, bootstrap-grid-mix.min.css - *Change css name style and **include original style**

### Change css name style
Original
```css
<div class="container">
	<div class="row">
		<div class="col-lg-8 col-md-6 col-sm-2 col-xs-12">Left</div>
		<div class="col-lg-4 col-md-6 col-sm-10 col-xs-12">Right</div>
	</div>
	<div class="row">
		<div class="col-lg-8 col-lg-push-4">Push</div>
		<div class="col-lg-4 col-md-pull-8">Pull</div>
	</div>
	<div class="row">
		<div class="col-lg-7 col-lg-offset-5">Offset</div>
	</div>
</div>
```
New style
```css
<div class="container">
	<div class="row">
		<div class="col lg-8 md-6 sm-2 xs-12">Left</div>
		<div class="col lg-4 md-6 sm-10 xs-12">Right</div>
	</div>
	<div class="row">
		<div class="col lg-8 lg-push-4">Push</div>
		<div class="col lg-4 md-pull-8">Pull</div>
	</div>
	<div class="row">
		<div class="col lg-7 lg-offset-5">Offset</div>
	</div>
</div>
```
