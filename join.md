---
layout: default
---
<div class="p-5 bg-dark rounded-3 text-light">
	<div class="container-fluid py-md-5 py-3">
		<p class="neno-blurb">NENO is a 100% volunteer-run organization that relies on donors to fund our work.</p>
		<h1 class="display-5 fw-bold mb-0">Here's how you can get involved.</h1>
	</div>
</div>

{% assign heading-color = "text-secondary" %}
{% assign outer-col-size = "col-12" %}
{% assign inner-col-size = "col-10 col-md-6 pe-md-5" %}
{% assign image-size = "col-10 col-md-3 my-4" %}
{% capture hrule %}
	<hr class='col-10 mx-auto my-4' />
{% endcapture %}
<div class="{{outer-col-size}} py-2 mx-auto mt-4">

	<h3 class="col-10 my-2 mx-auto {{heading-color}} text-md-center fw-bold">Volunteer with us!</h3>

	<p class="col-10 lead fs-5 mx-auto text-md-center">We are currently seeking new volunteers to help us grow our organization.</p>

	{{hrule}}
	<div class="row align-items-center justify-content-center">
		<div class="{{inner-col-size}}">
			<h4 class="{{heading-color}} my-4 fw-bold mx-auto">Outreach (Eagle Rock or Highland Park)</h4>
			<p class="fs-5 mx-auto"><b>What:</b> Visit our unhoused neighbors to build relationships with them, check in about any services they might need, and distribute supplies such as groceries, tents, and hygiene kits. <em>Volunteers que pueden hablar español encouraged!</em></p>
			<p class="fs-5 mx-auto"><b>When:</b> Sundays, 10:30am-1pm.</p>
			<div class="d-grid col-8 col-lg-6 mt-6 mx-auto ms-lg-0 me-lg-auto">
	         	<a href="mailto:info@neno-la.org" role="button" class="btn btn-primary rounded-pill">Contact Us to Sign Up</a>
	        </div>
		</div>
		<div class="{{image-size}}">
			<img src="assets/img/jack-with-bags.jpg" class="rounded-3 w-100" style="object-position: center; object-fit:cover; height: 20vw; min-height: 250px;"/>
		</div>
	</div>


	{{hrule}}

	<div class="row align-items-center justify-content-center">
		<div class="{{inner-col-size}}">
			<h4 class="{{heading-color}} my-4 fw-bold mx-auto">Bagging</h4>
			<p class="fs-5 mx-auto"><b>What:</b> Help us prepare for weekly outreach by building grocery bags for each neighbor on our route, gathering any additional supplies they might need.</p>
			<p class="fs-5 mx-auto"><b>When:</b> Saturdays, 9:30-10:30am.</p>
			<div class="d-grid col-8 col-lg-6 mt-6 mx-auto ms-lg-0 me-lg-auto">
	         	<a href="mailto:info@neno-la.org" role="button" class="btn btn-primary rounded-pill">Contact Us to Sign Up</a>
	        </div>
		</div>
		<div class="{{image-size}}">
			<img src="assets/img/bagging.jpg" class="rounded-3 w-100" style="object-position: center; object-fit:cover; height: 20vw; min-height: 250px;"/>
		</div>
	</div>

	{{hrule}}
	<div class="row align-items-center justify-content-center">
		<div class="{{inner-col-size}}">
			<h4 class="{{heading-color}} my-4 fw-bold mx-auto">Social Media and Fundraising</h4>
			<p class="fs-5 mx-auto"> We also are seeking a social media coordinator and general help with fundraising! Please email <a href="mailto:info@neno-la.org">info@neno-la.org</a> if you are interested. </p>
		</div>
		<div class="{{image-size}}">
			<img src="assets/img/hpb.jpg" class="rounded-3 w-100" style="object-position: center; object-fit:cover; height: 20vw; min-height: 250px;"/>
		</div>
	</div>

</div>

{% assign heading-color = "text-dark" %}

<div class="{{outer-col-size}} pt-4 pb-2 card-rounded mx-auto bg-accent">
	<div class="row align-items-center justify-content-center">
		<div class="{{inner-col-size}}">
			<h3 class="my-4 mx-auto {{heading-color}} text-bold">Donate</h3>

			<p class="fs-5 mx-auto">NENO depends on in-kind donations from the community to fund our operations. While we are a 100% volunteer organization, we use our funds to purchase supplies to distribute to our unhoused neighbors, including blankets, tents, hygeine kits, and clothing. </p>

			<p class="fs-5 mx-auto">NENO is a 501(c)(3) non-profit organization, and all donations are tax-deductible. Please consider making a recurrent donation to help fund us on a consistent basis. Your support is appreciated!</p>

			<div class="d-grid col-4 mt-4 mb-4 mx-auto">
	         	<a href="donate" role="button" class="btn btn-primary text-light btn-lg rounded-pill">Donate</a>
	        </div>
       	</div>
       	<div class="col-md-4 col-10">
			<img src="assets/img/rosie-bagging.jpg" class="rounded-3 w-100" style="object-position: center; object-fit:cover; height: 25vw; min-height: 250px;"/>
		</div>
   	</div>

</div>

{% assign heading-color = "text-secondary" %}

<div class="{{outer-col-size}} mx-auto" >
	<div class="row align-items-center justify-content-center h-100" style="min-height: 25vw;">
		<div class="col-10 col-md-5 text-center text-md-start">
			<h3 class="{{heading-color}} my-4 mx-auto text-bold">Stay up-to-date on NENO's events and current work!</h3>

			<p class=" fs-5 mx-auto">Join our mailing list to stay connected with us and get regular updates.</p>
			<div class="vr"></div>

		</div>

		<div class="vdiv mx-4 d-none d-md-block"></div>

		<div class="col-10 col-md-5">

			<form method="POST" action="https://api.sheetmonkey.io/form/saj4XFEdD4XTXiU9fCxGuC" id="contact-form">
		  		<div class="form-group my-2">
		    		<input type="name" class="form-control" name="Name" aria-describedby="nameHelp" placeholder="Full name">
		  		</div>
		  		<div class="form-group my-2">
		    		<input type="email" class="form-control" name="Email" aria-describedby="emailHelp" placeholder="Email">
		  		</div>
		  		<button type="submit" class="d-grid btn btn-primary mx-auto my-2">Sign up</button>
			</form>
		</div>
	</div>

</div>
