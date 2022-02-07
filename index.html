{% extends 'layouts/theme.html' %}

{% block pageheader %}
<h2><i class="fa fa-user"></i> <a href="/"> hire fullstack </a><span> Find your next Fullstack developer... </span></h2>
<div class="breadcrumb-wrapper">
	<span class="label">You are here:</span>
	<ol class="breadcrumb">
		<li><a href="/">Home</a></li>
		<li><a href="/interested">Favorites</a></li>
		<li><a href="/developers">Search</a></li>
		{%if req.user._id.toString() == req.params.id %}
		<li class="active">Profile</li>
		{% else %}
		<li><a href="/profile/{{req.user._id.toString()}}">Profile</a></li>
		{% endif %}
	</ol>
</div>
{% endblock %}

{% block content %}
<div class="row" ng-controller="TrackingController" ng-init="startTimer()">
	<!-- Col-sm-3 -->
	<div class="col-sm-3">
		<img src="{{user.linkedin.pictureUrl}}" class="thumbnail img-responsive" alt=""/>
		<div class="mb30"></div>
		<h5 class="subtitle">About</h5>

		<p class="mb30">{{user.linkedin.summary || "Edit your profile to tell employers about yourself!"}} <br><a href="">Show More</a></p>
		<h5 class="subtitle">Connect</h5>
		<ul class="profile-social-list">
			<li><i class="fa fa-twitter"></i> <a href="">twitter.com/eileensideways</a></li>
			<li><i class="fa fa-facebook"></i> <a href="">facebook.com/eileen</a></li>
			<li><i class="fa fa-youtube"></i> <a href="">youtube.com/eileen22</a></li>
			<li><i class="fa fa-linkedin"></i> <a href="">linkedin.com/4ever-eileen</a></li>
			<li><i class="fa fa-pinterest"></i> <a href="">pinterest.com/eileen</a></li>
			<li><i class="fa fa-instagram"></i> <a href="">instagram.com/eiside</a></li>
		</ul>

		<div class="mb30"></div>
		<h5 class="subtitle">Address</h5>
		<address>
			795 Folsom Ave, Suite 600<br>
			San Francisco, CA 94107<br>
			<abbr title="Phone">P:</abbr> (123) 456-7890
		</address>
	</div>
	<!-- end col-sm-3 -->
	<!-- Col-sm-9 -->
	<div class="col-sm-9">

		<!-- Profile Header -->
		<div class="profile-header">
			<h2 class="profile-name">{{user.name}}</h2>
			<div class="profile-location"><i class="fa fa-map-marker"></i> {{user.github.location}}</div>
			<div class="profile-position"><i class="fa fa-briefcase"></i>{{user.linkedin.headline}}</a></div>

			<div class="mb20"></div>

			<a href='/profile/edit' class="btn btn-success mr5"><i class="fa fa-user"></i> I'm Interested</a>
			<button class="btn btn-white"><i class="fa fa-envelope-o"></i> Message</button>
			{% if req.user._id.toString() == req.params.id %}
			<a href='/profile/edit' class="btn btn-info"><i class='fa fa-edit'></i> Edit</a>
			{% endif %}
			<!-- <a href="#myModal" role="button" class="btn btn-info" data-toggle="modal">Demo Modal</a> -->
			<!-- <button class="btn btn-primary" data-toggle="modal" data-target=".modal-header">Launch Modal</button> -->
			<button id="watchVideo" class="btn btn-primary" data-toggle="modal" data-target="#videoModal">Watch My Video</button>
		</div>

		<!-- end profile header -->
<!-- Modal -->

<!-- <div class="modal-header">
	<button aria-hidden="true" data-dismiss="modal" class="close" type="button">×</button>
	<h4 class="modal-title">Static Background</h4>
</div> -->




<div class="modal fade" id="videoModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
	<div class="modal-dialog modal-lg">
		<div class="modal-content">
			<div class="modal-header">
				<button type="button" class="close" data-dismiss="modal" aria-hidden="true">&times;</button>
				<!-- <h4 class="modal-title" id="myModalLabel">Modal title</h4> -->
			</div>
			<div class="modal-body">
				<iframe id="userVid" width="640" height="400" src="//www.youtube.com/embed/HyophYBP_w4" frameborder="0" allowfullscreen></iframe>
			</div>
		</div>
	</div>
</div>

<!-- Modal end -->
		<!-- Nav Tabs -->
		<ul class="nav nav-tabs nav-justified nav-profile">
			<li class="active"><a href="#activities" data-toggle="tab"><strong>Work Experience</strong></a></li>
			<li><a href="#followers" data-toggle="tab"><strong>Education</strong></a></li>
			<li><a href="#following" data-toggle="tab"><strong>Project 1</strong></a></li>
			<li><a href="#events" data-toggle="tab"><strong>Project 2</strong></a></li>
		</ul>
		<!-- end nav tabs -->

		<!-- Tab Panes -->
		<div class="tab-content">

	<!-- Work Experience List -->
	<div class="tab-pane active" id="activities">
<!-- 		{% for key, position in user.linkedin.positions.values %}
			<li>{{position.company.name}}
				<ul>{{position.title}}</ul>
				<ul>{{position.startDate.year}} - {{position.endDate.year}}</ul>
			</li>
		{% endfor %} -->
		<div class="panel-group" id="accordion">
			<div class="panel panel-default">
		{% for key, position in user.linkedin.positions.values %}

				<div class="panel-heading">
					<h4 class="panel-title">
						<a data-toggle="collapse" data-parent="#accordion" href="#collapse{{key}}">
								{{position.company.name}} : {{position.startDate.year}} - {{position.endDate.year}}
						</a>

					</h4>
				</div>
				<div id="collapse{{key}}" class="panel-collapse collapse in" style="height: auto;">
					<div class="panel-body">
					<ul><strong>{{position.title}}</strong></ul>
					{% for key, line in position.summary.split(';') %}
					<ul> {{line}}</ul>
					{% endfor %}
					</div>
				</div>

		{% endfor %}
		</div>
		</div>
	</div>

<!-- end work experience list -->

<!-- Education List -->
<div class="tab-pane" id="followers">
	{% for school in user.linkedin.educations.values %}
		<li>{{school.schoolName}}
			<ul> {{school.fieldOfStudy}} </ul>
			<ul> {{school.degree}} </ul>
		</li>
	{% endfor %}
</div>
<!-- project 1 tab -->
	<div class="tab-pane" id="following">
	</div>
<!-- end project 1 tab -->
<!-- project 1 tab -->
	<div class="tab-pane" id="events">
		<h2>We will add secondary projects or skills here</h2>
	</div>
<!-- end project 1 tab -->
</div>
{% endblock %}

<script type="text/javascript">
jQuery(document).ready(function() {
	$('')
});
</script>
