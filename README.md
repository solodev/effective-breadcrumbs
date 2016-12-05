# effective-breadcrumbs
In this tutorial, [Solodev](https://www.solodev.com/) explains the need for effective breadcrumbs within your site. Whether we recognize it or not, breadcrumbs play an essential part in your site’s navigation and user experience. Their integration throughout a site helps ground individual sections within the overall hierarchy and provides needed navigational choices for your users. 

## Tutorial

For detailed instructions, view Solodev's [Adding Breadcrumbs for Effective Navigation](https://www.solodev.com/blog/web-design/adding-breadcrumbs-for-effective-navigation.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/fy1xfnzd/).

## HTML

A page with a breadcrumb section is created with the following HTML:

```
<nav class="navbar navbar-default">
  <div class="container">
	<div class="navbar-header">
	  <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
		<span class="sr-only">Toggle navigation</span>
		<span class="icon-bar"></span>
		<span class="icon-bar"></span>
		<span class="icon-bar"></span>
	  </button>
	  <a class="navbar-brand" href="#"> <img src="https://www.solodev.com/assets/email/logo.png" alt="Logo Solodev"></a>
	</div>
	<div id="navbar" class="collapse navbar-collapse">
	  <ul class="nav navbar-nav">
		<li><a href="#">Home</a></li>
		<li><a href="#about">About</a></li>
		<li><a href="#contact">Contact</a></li>
		<li class="dropdown">
		  <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
		  <ul class="dropdown-menu">
			<li><a href="#">Action</a></li>
			<li><a href="#">Another action</a></li>
			<li><a href="#">Something else here</a></li>
			<li role="separator" class="divider"></li>
			<li class="dropdown-header">Nav header</li>
			<li><a href="#">Separated link</a></li>
			<li><a href="#">One more separated link</a></li>
		  </ul>
		</li>
	  </ul>
	</div><!--/.nav-collapse -->
  </div>
</nav>

<div class="container">
	<h1>Using Breadcrumbs Effectively</h1>
	
	<div class="content-crumb-div">
		<a class="fileTrail" href="#">Home</a> <i class="fa fa-arrow-right"></i> <a class="fileTrail" href="#">Blog</a> <i class="fa fa-arrow-right"></i> <a class="fileTrail" href="#">Web Design</a> <i class="fa fa-arrow-right"></i> <span class="fileTrailCurrent">Using Breadcrumbs Effectively</span>
	</div>
	
	<p>The use of breadcrumbs can make your user experience more effective while not necessarily impacting your design.</p>
	
	<hr />

	<p>Solodev is the world’s first enterprise web experience platform available on-demand and created by developers for developers. It allows organizations to create amazing websites with unparalleled levels of security, scalability and total design freedom.</p>

	<p>Fully optimized for the Amazon Web Services (AWS) Cloud, Solodev provides you with unparalleled scalability, security, and accessibility and total design freedom without the need to compromise on design and functionality.</p>

	<p>Trusted by nationally recognized brands, Solodev is used to build and host engaging websites that drive meaningful results. Available for instant online purchase, Solodev empowers designers and developers to create dynamic, award-winning websites without compromise.</p>
</div>
```

## CSS

All required CSS is in effective-breadcrumbs.css


## External Includes

This tutorial contains the following third party resources.

```
<link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">

<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script type="text/javascript" src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
