---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<section class="header--wrapper">
  <img class="header--image" src="https://place-hold.it/300x500" />
  <div class="header--main">
    <h1 class="header--title">Back to Plants</h1>
    <h2 class="header--sub-title">Guidance to vegan happiness</h2>
    <p class="header--paragraph">
      Here is your guidance through a simple vegan kitchen with perfectly balanced recipes and a handful of yumminess
    </p>
  </div>
</section>

<section>
<!-- Begin Mailchimp Signup Form -->
<div id="mc_embed_signup">
<form action="https://back-to-plants.us19.list-manage.com/subscribe/post?u=1048c4e168940952bbda912da&amp;id=8a430c324d" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
    <div id="mc_embed_signup_scroll">

<div class="indicates-required"><span class="asterisk">*</span> indicates required</div>
<div class="mc-field-group">
	<label for="mce-EMAIL">Email Address  <span class="asterisk">*</span>
</label>
	<input type="email" value="" name="EMAIL" class="required email" id="mce-EMAIL">
</div>
<div id="mergeRow-gdpr" class="mergeRow gdpr-mergeRow content__gdprBlock mc-field-group">
    <div class="content__gdpr">
        <label>Marketing Permissions</label>
        <p>Please select all the ways you would like to hear from back to plants:</p>
        <fieldset class="mc_fieldset gdprRequired mc-field-group" name="interestgroup_field">
		<label class="checkbox subfield" for="gdpr_92201"><input type="checkbox" id="gdpr_92201" name="gdpr[92201]" value="Y" class="av-checkbox "><span>Email</span> </label><label class="checkbox subfield" for="gdpr_92205"><input type="checkbox" id="gdpr_92205" name="gdpr[92205]" value="Y" class="av-checkbox "><span>Direct Mail</span> </label><label class="checkbox subfield" for="gdpr_92209"><input type="checkbox" id="gdpr_92209" name="gdpr[92209]" value="Y" class="av-checkbox "><span>Customized Online Advertising</span> </label>
        </fieldset>
        <p>You can unsubscribe at any time by clicking the link in the footer of our emails. For information about our privacy practices, please visit our website.</p>
    </div>
    <div class="content__gdprLegal">
        <p>We use Mailchimp as our marketing platform. By clicking below to subscribe, you acknowledge that your information will be transferred to Mailchimp for processing. <a href="https://mailchimp.com/legal/" target="_blank">Learn more about Mailchimp's privacy practices here.</a></p>
    </div>
</div>
	<div id="mce-responses" class="clear">
		<div class="response" id="mce-error-response" style="display:none"></div>
		<div class="response" id="mce-success-response" style="display:none"></div>
	</div>    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
    <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_1048c4e168940952bbda912da_8a430c324d" tabindex="-1" value=""></div>
    <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
    </div>
</form>
</div>

<!--End mc_embed_signup-->
</section>

<section class="app-section--wrapper">
  <img class="app-section--image" src="https://place-hold.it/300x500" />
  <div class="app-section--item">
    <h2 class="app-section--title">Quick and Simple</h2>
    <p class="app-section--paragraph">
      Access our app without required sign up and Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum.
    </p>
  </div>
  <div class="app-section--item">
    <h2 class="app-section--title">Quick and Simple</h2>
    <p class="app-section--paragraph">
      Access our app without required sign up and Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum.
    </p>
  </div>
  <div class="app-section--item">
    <h2 class="app-section--title">Quick and Simple</h2>
    <p class="app-section--paragraph">
      Access our app without required sign up and Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum.
    </p>
  </div>
  <div class="app-section--item">
    <h2 class="app-section--title">Quick and Simple</h2>
    <p class="app-section--paragraph">
      Access our app without required sign up and Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum.
    </p>
  </div>
</section>

<section class="blog-excerpts--wrapper">
  {% for post in site.posts %}
    <a href="{{ post.url }}" class="blog-excerpts--item">
        <h2 class="blog-excerpts--heading">{{ post.title }}</h2>
        <img src="{{post.teaser_image}}" class="blog-excerpts--image" />
        <div class="blog-excerpts--excerpt">{{ post.excerpt }}</div>
    </a>
  {% endfor %}
</section>
