Gunard
=============

Gunard is a simple-but-beautiful responsive grid built on SASS.

Why should you use it?
----------------------

That's a good question.

Installation
------------

### SASS

The easiest way to let Gunard power your site is to place the gunard.scss file in the same folder as the rest of your SASS files.

Once you've done that, including Gunard's responsive grid into your design is a simple as writing the following in your main SASS file:

`@import "gunard";`

It will be compiled with the rest of your styles. That's the beauty of SASS.

### CSS

If you don't know what SASS is, this is what you want.

Put the gunard-min.css file in the same folder as your other CSS files. Then, add the following to the <em>head</em> section of your page:

`&lt;link href="/path-to-CSS-files/gunard.css" media="screen, projection" rel="stylesheet" type="text/css" &#47;&gt;`

When you refresh the page, your site will be Gunard-powered.

You can also copy the contents of gunard-min.css into the top of your main CSS file. Remember that the less HTTP requests you make, the faster your page loads. Hence, this is often the better solution.

"What about the gunard.css file?" you might ask. Don't worry about it too much. It's mostly so that curious viewers can see what the CSS code looks like after it's been processed by SASS. For the sake of keeping file sizes down, try to use the gunard-min.css file whenever possible.

License
-------

I'm using the [GPL](http://www.gnu.org/copyleft/gpl.html) license, which means that this bit of software can be forked to your heart's content. Have at it.