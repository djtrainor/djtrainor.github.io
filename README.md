# How to add a new place visited

1. Drop image of new restaurant visited in the /images folder and name it accordingly (numerically).
1. Add the following to `index.html`, above the line `</section>`:
```
<article>
	<a class="thumbnail" href="images/{THE IMAGE YOU JUST UPLOADED}.jpg"><img class="blurred-image" src="images/{THE IMAGE YOU JUST UPLOADED}.jpg" alt="" /></a>
	<h2><a href="{GOOGLE MAPS LINK TO RESTAURANT}">{NAME OF RESTAURANT}, {RATING FROM 0-5}</a></h2>
	<p>{BRIEF DESCRIPTION OF WEBSITE}</p>
</article>
```
1. Once done, refresh and watch the changes persist to the website in a couple minutes :)

## Is your change being added to the website?
[![pages-build-deployment](https://github.com/djtrainor/djtrainor.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/djtrainor/djtrainor.github.io/actions/workflows/pages/pages-build-deployment)
