---
layout: default
---
<div class="p-5 bg-dark rounded-3 text-light">
	<div class="container-fluid py-5">
		<p class="neno-blurb">NENO is a 100% volunteer-run organization that relies on donors to fund our work.</p>
		<h1 class="display-5 fw-bold">Here's how you can get involved.</h1>
	</div>
</div>

<!-- <div class="col-10 py-2 mx-auto">
	<h3 class="text-secondary col-8 mx-auto text-start my-4 fw-bold">We are a volunteer-run organization that relies on donors to fund our work. </h3>

	<p class="col-8 fs-5 mx-auto"> The best ways to support NENO are to volunteer with us, or to donate to help fund our-day-to-day operations. Your support will directly better the lives of your neighbors in Northeast LA. </p>
</div> -->

{% assign heading-color = "text-secondary" %}
{% assign outer-col-size = "col-12" %}
{% assign inner-col-size = "col-6" %}
{% assign image-size = "col-3" %}
{% capture hrule %}
	<hr class='col-9 mx-auto my-4' />
{% endcapture %}
<div class="{{outer-col-size}} py-2 mx-auto my-4">

	<h3 class="col-9 my-4 m-auto {{heading-color}} text-bold">Volunteer with us!</h3>

	<p class="col-9 fs-5 mx-auto">We are currently seeking new volunteers to help build our organization.</p>

	{{hrule}}
	<div class="row align-items-center justify-content-center">
		<div class="{{inner-col-size}}">
			<h5 class="{{heading-color}} my-4 mx-auto text-bold">Outreach (Eagle Rock or Highland Park)</h5>
			<p class="fs-5 mx-auto"><em>What:</em> Visit our unhoused neighbors to build relationships with them, check in about any services they might need, and distribute supplies such as groceries, tents, and hygeine kits. <em>Volunteers que pueden hablar español encouraged!</em></p>
			<p class="fs-5 mx-auto"><em>When:</em> Sundays, 10:30am-1pm.</p>
			<div class="d-grid col-4 mt-4 me-auto">
	         	<a href="https://docs.google.com/spreadsheets/d/1xK-Z8wKjPXjPZx0GIrriprI-n7hftdmHkWFNtyXH4ms/edit?usp=sharing" role="button" class="btn btn-primary rounded-pill">Outreach Sign-up</a>
	        </div>
		</div>
		<div class="{{image-size}}">
			<img src="assets/img/jack-with-bags.jpg" class="rounded-3 w-100" style="object-position: center; object-fit:cover; height: 20vw;"/>
		</div>
	</div>


	{{hrule}}

	<div class="row align-items-center justify-content-center">
		<div class="{{inner-col-size}}">
			<h5 class="{{heading-color}} my-4 mx-auto text-bold">Bagging</h5>
			<p class="fs-5 mx-auto"><em>What:</em> Help us prepare for weekly outreach by preparing grocery bags for each neighbor on our route, gathering any additional supplies they might need.</p>
			<p class="fs-5 mx-auto"><em>When:</em> Saturdays, 9:30-10:30am.</p>
			<div class="d-grid col-4 mt-4 me-auto">
	         	<a href="https://docs.google.com/spreadsheets/d/1mdtFyk6vPqDmUPC8CLY6b24oUKizMSfkURYSpGFo7Qo/edit?usp=sharing" role="button" class="btn btn-primary rounded-pill">Bagging  Sign-up</a>
	        </div>
		</div>
		<div class="{{image-size}}">
			<img src="assets/img/bagging.jpg" class="rounded-3 w-100" style="object-position: center; object-fit:cover; height: 20vw;"/>
		</div>
	</div>

	{{hrule}}
	<div class="row align-items-center justify-content-center">
		<div class="{{inner-col-size}}">
			<h5 class="{{heading-color}} my-4 mx-auto text-bold">Social Media and Fundraising</h5>
			<p class="fs-5 mx-auto"> We also are seeking a social media coordinator and general help with fundraising! Please email <a href="mailto:info@neno-la.org">info@neno-la.org</a> if you are interested. </p>
		</div>
		<div class="{{image-size}}">
			<img src="assets/img/hpb.jpg" class="rounded-3 w-100" style="object-position: center; object-fit:cover; height: 20vw;"/>
		</div>
	</div>

</div>

{% assign heading-color = "text-dark" %}

<div class="{{outer-col-size}} py-4 card-rounded mx-auto bg-accent">
	<div class="row align-items-center justify-content-center">
		<div class="{{inner-col-size}}">
			<h3 class="my-4 mx-auto {{heading-color}} text-bold">Donate</h3>

			<p class="fs-5 mx-auto">NENO depends on in-kind donations from the community to fund our operations. While we are a 100% volunteer organization, we use our funds to purchase supplies to distribute to our unhoused neighbors, including blankets, tents, hygeine kits, and clothing. </p>

			<p class="fs-5 mx-auto">NENO is a 501(c)(3) non-profit organization, and all donations are tax-deductible. Please consider making a recurrent donation to help fund us on a consistent basis. Your support is appreciated!</p>

			<div class="d-grid col-4 mt-4 mb-4 mx-auto">
	         	<a href="donate" role="button" class="btn btn-primary text-light btn-lg rounded-pill">Donate</a>
	        </div>
       	</div>
       	<div class="col-4">
			<img src="assets/img/rosie-bagging.jpg" class="rounded-3 w-100" style="object-position: center; object-fit:cover; height: 25vw;"/>
		</div>
   	</div>

</div>

{% assign heading-color = "text-secondary" %}

<div class="{{outer-col-size}} mx-auto" >
	<div class="row align-items-center justify-content-center h-100" style="min-height: 30vw;">
		<div class="col-5">
			<h3 class="{{heading-color}} my-4 mx-auto text-bold">Stay up-to-date on NENO's events and current work!</h3>

			<p class=" fs-5 mx-auto">Join our mailing list to stay connected with us and get regular updates.</p>
			<div class="vr"></div>

		</div>

		<div class="vdiv mx-4"></div>

		<div class="col-5">

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
