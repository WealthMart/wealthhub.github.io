## Carousel Light

The light carousel is a modified version of Bootstrap's default carousel, using lighter styles on all carousel controls.

{% raw %}
<div id="carousel-example-generic-2" class="carousel carousel-light slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carousel-example-generic-2" data-slide-to="0" class="active"></li>
    <li data-target="#carousel-example-generic-2" data-slide-to="1"></li>
    <li data-target="#carousel-example-generic-2" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner" role="listbox">
    <div class="carousel-item active">
      <img class="d-block img-fluid" src="https://placehold.it/1140x500/fff/333" alt="First slide">
    </div>
    <div class="carousel-item">
      <img class="d-block img-fluid" src="https://placehold.it/1140x500/fff/333" alt="Second slide">
    </div>
    <div class="carousel-item">
      <img class="d-block img-fluid" src="https://placehold.it/1140x500/fff/333" alt="Third slide">
    </div>
  </div>
  <a class="carousel-control-prev" href="#carousel-example-generic-2" role="button" data-slide="prev">
    <span class="icon icon-chevron-thin-left" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carousel-example-generic-2" role="button" data-slide="next">
    <span class="icon icon-chevron-thin-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
{% endraw %}
