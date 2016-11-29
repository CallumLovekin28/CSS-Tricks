# Animate.css :page_facing_up: :computer:
### If you click [Here](https://thimbleprojects.org/callumlovekin/141339/) you can see a demo that I created!


This website allows people to download a .CSS sheet which has loads of animations for text and images just using the CSS Stylesheet.

You can either extract the animation you want and put it in your own CSS style sheet or you can just place the Animate.css style sheet within your websites directory and reference it within your HTML document like a normal CSS Style Sheet like seen below.
	
~~~~
<head>
  <link rel="stylesheet" href="animate.min.css">
</head>
~~~~

You can visit the site [here](https://daneden.github.io/animate.css/) and have a look at all the demos they have to offer!

Having a tool like this is incredible, especially if youre new to HTML and CSS and you need some way of spicing up your first websites.

~~~~

@-webkit-keyframes pulse {
  from {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }

  50% {
    -webkit-transform: scale3d(1.05, 1.05, 1.05);
    transform: scale3d(1.05, 1.05, 1.05);
  }

  to {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
}

@keyframes pulse {
  from {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }

  50% {
    -webkit-transform: scale3d(1.05, 1.05, 1.05);
    transform: scale3d(1.05, 1.05, 1.05);
  }

  to {
    -webkit-transform: scale3d(1, 1, 1);
    transform: scale3d(1, 1, 1);
  }
}

.pulse {
  -webkit-animation-name: pulse;
  animation-name: pulse;
}
~~~~
