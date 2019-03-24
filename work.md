---
layout: default
title: Work. Made by Activ.
---

<section id="portfolio" class="portfolio archive">
	<ul class="portfolio_wrapper">
		{% for post in site.posts %}
			<li class="portfolio_item {{ post.class }}">
				<div class="grid_cont grid_align_center">
					<div class="portfolio_img_wrapper grid_cont_50perc">
						<img src="/img/{{ post.image }}" class="portfolio_img">
					</div>
					<div class="portfolio_desc grid_cont_50perc">
						<div class="portfolio_desc_heading">
							<span class="portfolio_name">{{ post.client }}</span>
							<h3>{{ post.title }}</h3>
						</div>
						<p>
							{{ post.excerpt }}
						</p>
						<!-- <a href="{{ post.url }}" class="btn"> -->
							<!-- Read the case study
							{% include_relative svg/arrow.svg %} -->
						<!-- </a> -->
					</div>
				</div>
			</li>
		{% endfor %}
	</ul>
</section>
