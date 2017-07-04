# Run application
Option 1: Download or clone repository
Option 2: Follow links to the Portfolio site [here](https://ba-batten.github.io/frontend-nanodegree-mobile-portfolio/) and Pizzeria site [here](https://ba-batten.github.io/frontend-nanodegree-mobile-portfolio/views/pizza.html)

# Optimizations to Portfolio site
* Reduce image sizes and compress
* Inline CSS styles
* Add async attribute to `<script>` tags

# Optimizations to Pizzeria site
* Reduce number of background pizzas from 200 to 20
* Separate layout and style changes into separate for loops
* Cache code within loops that require frequent round trips into variables
* Replace document.querySelector with more efficient getElementById or getElemementsByClassName where appropriate
* Reduce image sizes and compress
* Use `<picture>` tag and nested `<source>` tags to load different versions of the pizzeria.jpg image based on viewport size
