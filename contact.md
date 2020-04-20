---
layout: default
title: Contact. Say hi to Activ.
---

<section id="contact">
		<div class="grid_cont portfolio grid_align_center">
			<div class="portfolio_img_wrapper grid_cont_50perc">
				<img src="/img/contact-img.jpg" class="portfolio_img">
			</div>
			<div class="portfolio_desc grid_cont_50perc">
				<div class="portfolio_desc_heading">
					<h3>Tell us about your dream.</h3>
				</div>
                <div>
                    <p>
                        We will love to hear about your exciting project. We are open to new businesses and innovative partnerships.
                    </p>
                    <!-- <form id="contact-form" action="https://getform.io/f/87c1f35e-a425-44b5-85f7-a2c51e967ed5" method="POST">
                        <input type="text" name="name">
                        <input type="email" name="email">
                        <input type="tel" name="tel">
                        <button type="submit">Send</button>
                    </form> -->
                </div>
				<form id="contact-form" action="https://getform.io/f/87c1f35e-a425-44b5-85f7-a2c51e967ed5" method="POST">
					<div class="input input--nao">
						<input class="input__field input__field--nao" type="text" id="input-1" name="name" placeholder="John Doe" />
						<label class="input__label input__label--nao" for="input-1">
							<span class="input__label-content input__label-content--nao">Name</span>
						</label>
						{% include_relative svg/input.svg %}
					</div>
					<div class="input input--nao">
						<input class="input__field input__field--nao" type="email" id="input-2"  name="email" placeholder="johndoe@youremail.com"/>
						<label class="input__label input__label--nao" for="input-1">
							<span class="input__label-content input__label-content--nao">Email Address</span>
						</label>
						{% include_relative svg/input.svg %}
					</div>
					<div class="input input--nao">
						<input class="input__field input__field--nao" type="tel" id="input-3" name="tel" placeholder="+234 8012345678"/>
						<label class="input__label input__label--nao" for="input-1">
							<span class="input__label-content input__label-content--nao">Mobile Number</span>
						</label>
						{% include_relative svg/input.svg %}
					</div>
					<button class="btn">
						Submit
						{% include_relative svg/arrow.svg %}
					</button>
				</form>
			</div>
		</div>
	</section>
