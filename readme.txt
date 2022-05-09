1. Font Face example
CSS Part:
@font-face{
	src:url();
    font-family: ;
}

--------------------

2.Common Body Font, Size, Weight, Color Example
CSS Part:
body {
  font-family: ;
  font-size: ;
  font-weight: ;
  color: ;
}

---------------------

3.Button with link to another HTML

HTML part:

<!-- Common Title -->
<section class="bg-dark p-3 my-2">
	<div class="container-fluid">
		<div class="row row-cols-auto justify-content-center">
			<a class="btn btn-lg mx-5 manual " href="Change Here">Write Here</a>
		</div>
	</div>
	</div>
</section>
<!-- Common Title -->

CSS Part:
.manual {
  color: white;
  background: rgba(109, 0, 25, 1);
  background: -moz-linear-gradient(left, rgba(109, 0, 25, 1) 0%, rgba(109, 0, 25, 1) 22%, rgba(169, 3, 41, 1) 47%, rgba(109, 0, 25, 1) 82%, rgba(109, 0, 25, 1) 100%);
  background: -webkit-gradient(left top, right top, color-stop(0%, rgba(109, 0, 25, 1)), color-stop(22%, rgba(109, 0, 25, 1)), color-stop(47%, rgba(169, 3, 41, 1)), color-stop(82%, rgba(109, 0, 25, 1)), color-stop(100%, rgba(109, 0, 25, 1)));
  background: -webkit-linear-gradient(left, rgba(109, 0, 25, 1) 0%, rgba(109, 0, 25, 1) 22%, rgba(169, 3, 41, 1) 47%, rgba(109, 0, 25, 1) 82%, rgba(109, 0, 25, 1) 100%);
  background: -o-linear-gradient(left, rgba(109, 0, 25, 1) 0%, rgba(109, 0, 25, 1) 22%, rgba(169, 3, 41, 1) 47%, rgba(109, 0, 25, 1) 82%, rgba(109, 0, 25, 1) 100%);
  background: -ms-linear-gradient(left, rgba(109, 0, 25, 1) 0%, rgba(109, 0, 25, 1) 22%, rgba(169, 3, 41, 1) 47%, rgba(109, 0, 25, 1) 82%, rgba(109, 0, 25, 1) 100%);
  background: linear-gradient(to right, rgba(109, 0, 25, 1) 0%, rgba(109, 0, 25, 1) 22%, rgba(169, 3, 41, 1) 47%, rgba(109, 0, 25, 1) 82%, rgba(109, 0, 25, 1) 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#6d0019', endColorstr='#6d0019', GradientType=1);

  transition: 1s;
}
.manual:hover {
  background: rgba(255, 255, 255, 1);
  background: -moz-linear-gradient(left, rgba(255, 255, 255, 1) 0%, rgba(246, 246, 246, 1) 47%, rgba(237, 237, 237, 1) 100%);
  background: -webkit-gradient(left top, right top, color-stop(0%, rgba(255, 255, 255, 1)), color-stop(47%, rgba(246, 246, 246, 1)), color-stop(100%, rgba(237, 237, 237, 1)));
  background: -webkit-linear-gradient(left, rgba(255, 255, 255, 1) 0%, rgba(246, 246, 246, 1) 47%, rgba(237, 237, 237, 1) 100%);
  background: -o-linear-gradient(left, rgba(255, 255, 255, 1) 0%, rgba(246, 246, 246, 1) 47%, rgba(237, 237, 237, 1) 100%);
  background: -ms-linear-gradient(left, rgba(255, 255, 255, 1) 0%, rgba(246, 246, 246, 1) 47%, rgba(237, 237, 237, 1) 100%);
  background: linear-gradient(to right, rgba(255, 255, 255, 1) 0%, rgba(246, 246, 246, 1) 47%, rgba(237, 237, 237, 1) 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffffff', endColorstr='#ededed', GradientType=1);
  color: rgba(109, 0, 25, 1);
}
/* Common Header Part End */

-------------------

4.Just a Common Bar

HTML Part:
<!-- Common Title -->
<section class="bg-dark p-3 my-2">
	<div class="container-fluid">
		<div class="row row-cols-auto justify-content-center">
			<a class="btn btn-lg common-bar" href="#"></a>
		</div>
	</div>
	</div>
</section>
<!-- Common Title -->

CSS Part:

/* Common Bar Start */
.common-bar{
  background: rgba(32,124,229,1);
  background: -moz-linear-gradient(left, rgba(32,124,229,1) 0%, rgba(32,124,229,1) 30%, rgba(73,155,234,1) 80%, rgba(73,155,234,1) 100%);
  background: -webkit-gradient(left top, right top, color-stop(0%, rgba(32,124,229,1)), color-stop(30%, rgba(32,124,229,1)), color-stop(80%, rgba(73,155,234,1)), color-stop(100%, rgba(73,155,234,1)));
  background: -webkit-linear-gradient(left, rgba(32,124,229,1) 0%, rgba(32,124,229,1) 30%, rgba(73,155,234,1) 80%, rgba(73,155,234,1) 100%);
  background: -o-linear-gradient(left, rgba(32,124,229,1) 0%, rgba(32,124,229,1) 30%, rgba(73,155,234,1) 80%, rgba(73,155,234,1) 100%);
  background: -ms-linear-gradient(left, rgba(32,124,229,1) 0%, rgba(32,124,229,1) 30%, rgba(73,155,234,1) 80%, rgba(73,155,234,1) 100%);
  background: linear-gradient(to right, rgba(32,124,229,1) 0%, rgba(32,124,229,1) 30%, rgba(73,155,234,1) 80%, rgba(73,155,234,1) 100%);
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#207ce5', endColorstr='#499bea', GradientType=1 );
}
/* Common Bar End */
------------------

5. Font Awesome kit

<script src="https://kit.fontawesome.com/6c4cc7fb29.js" crossorigin="anonymous"></script>

-----------------
