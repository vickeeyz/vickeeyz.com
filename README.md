vickeeyz.com
============

Responsive Single Page Portfolio Website.

Design By : html5up.net

Instructions
============

	Being a single pager, It should be way simpler to work with than
	some of the heavier stuff I've released in the past. In fact, aside from
	a main page <header> and <footer>, it's pretty much just a stack of "main"
	<section> elements that follow the same basic pattern:

		<section id="foobar" class="main">
			<div class="content container">
				<header>
					<h2>Foobar</h2>
				</header>
				...
			</div>
		</section>

	The section can then be assigned a style class to determine its basic
	look (and, in some cases, its behavior):
	
		style1
			Centered content with an oversized <h2>. Works best when
			paired with a background image or color.
			
		style2 left
			Content in a box, anchored to the left side of the window. Works
			best when paired with a background image or color. If you have
			"useSectionTransitions" turned on in your settings, the box will
			slide into view from the left.
						
		style2 right
			Content in a box, anchored to the right side of the window. Works
			best when paired with a background image or color. If you have
			"useSectionTransitions" turned on in your settings, the box will
			slide into view from the right.
	
		style3 primary
			Used for generic content. Set against the primary background
			color (default is white).
			
		style3 secondary
			Used for generic content. Set against the secondary background
			color (default is a light gray).
		
	Oh, and there are a few (well, two) optional modifier classes you can
	tack on for additional effects:
	
		dark
			Flips the content's color scheme so it shows up better
			against darker background images and colors.
			
		fullscreen
			Makes the section fill the entire window (only if "useFullScreen"
			is enabled in your settings).



Settings
=========

	A handful of settings can be found at the top of js/init.js to tweak
	Big Picture's behavior:

		useFullScreen
			If true, main sections with the "fullscreen" class will be resized to
			fill the window. If false, they'll be left alone. Default is true.
			
			* This defaults to false on mobile devices.

		useSectionTransitions
			If true, section transitions (the stuff that happens when you scroll)
			will be used. If false, no transitions will be used and stuff will
			just kind of .. sit there. Default is true.

			* This defaults to false on touch-enabled devices because they
			  don't trigger the "scroll" event until *after* you lift your finger
			  off the screen. Kind of a problem since scrollwatch/scrollgress rely
			  on that event to do stuff.
			  
			* This *also* defaults to false in IE9 (and lower) since it doesn't
			  support CSS transitions and shit just looks weird without them.

		fadeInSpeed
			Speed at which to fade in the page on load (in ms). Default is 1000.



Other Stuff
===========

	- If you don't like the way images are tinted, either change "images/overlay.png"
	  to something else, or remove all references to it from css/style.css.

	- If you plan to keep support for IE8 (what little there is), don't forget to update
	  css/ie/ie8.css as you change other stuff.
	  
	- skelJS (frame this thing is built on): http://skeljs.org
	
	- Poptrox (powers the lightbox-style gallery): http://github.com/n33/jquery.poptrox



Credits
=======

	Icons
		Font Awesome (http://fortawesome.github.com/Font-Awesome/)

	Other
		jQuery (jquery.com)
		html5shiv.js (@afarkas @jdalton @jon_neal @rem)
		CSS3 PIE (http://css3pie.com/)
		background-size polyfill (https://github.com/louisremi/background-size-polyfill)
		jquery.poptrox, other misc plugins (n33.co)
		skelJS (skeljs.org)
