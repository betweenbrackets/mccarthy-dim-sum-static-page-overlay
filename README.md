# mccarthy-dim-sum-static-page-overlay
I started here: https://betweenbrackets.github.io/recipe-card-static-page/ and updated that project to this one because I love dim sum! Made for a great weekend!

I updated the palette, the images, and the text.

Issue: the dim sum recipes were longer than the previous recipes and there was no white background, just gray text on the pale yellow background.
I updated the style rules to address this. 

Issue: When I updated the styles so that the recipes' overflows scrolled, I did not like the clunky user-side experience.
I updated to an overlay after searching for what might be available in hover, display: block, and display: none. (I discovered w3schools how to. What a great find!)

Issue: the overlay called only the first recipe.
I updated the id = "overlay", the functions, and the styles to be dish specific.

Issue: the overlay for steamed pork buns exceeded the browser due to the length of the directions.
I added a height to the styles to enable a scroll bar.
