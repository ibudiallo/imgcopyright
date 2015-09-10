# Introducing the copyright img attribute

	<img src="flyingcat.jpg" alt="Flying cat" copyright="cc-by The Cat" />

This is an optional attribute that will complement the image tag. It is not a replacement of stating the copyright info on the page, but it will be a good attempt to notify the browser and web crawlers of the copyright held by this picture. 

The copyright attribute can take the values currently defined by the [creative commons](http://creativecommons.org/licenses/) and then some. 


<table class="mdtable">
	<thead>
		<tr>
			<th>Type</th>
			<th>CC Notation</th>
			<th>Copyright Attribute Notation</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Attribution</td>
			<td>CC BY</td>
			<td>cc-by</td>
		</tr>
		<tr>
			<td>Attribution-NoDerivs</td>
			<td>CC BY-ND</td>
			<td>cc-by-nd</td>
		</tr>
		<tr>
			<td>Attribution-NonCommercial-ShareAlike</td>
			<td>CC BY-NC-SA</td>
			<td>cc-by-nc-sa</td>
		</tr>
		<tr>
			<td>Attribution-ShareAlike</td>
			<td>CC BY-SA</td>
			<td>cc-by-sa</td>
		</tr>
		<tr>
			<td>Attribution-NonCommercial</td>
			<td>CC BY-NC</td>
			<td>cc-by-nc</td>
		</tr>
		<tr>
			<td>Attribution-NonCommercial-NoDerivs</td>
			<td>CC BY-NC-ND</td>
			<td>cc-by-nc-nd</td>
		</tr>
		<tr>
			<td>Public domain</td>
			<td>CC 0</td>
			<td>cc-0</td>
		</tr>
		<tr>
			<td>Non Creative Commons</td>
			<td>©</td>
			<td>c</td>
		</tr>
	</tbody>
</table>

The attribute can also include the year, and additional information. Here is an image correctly tagged with the appropriate copyrights:

<div class="image">
	<img src="http://cdn.idiallo.com/photo/36/ants.jpg" alt="Ants" copyright="cc-by 2015 Ibrahim Diallo idiallo.com/photography" />
	<p>CC BY <i>Ibrahim Diallo idiallo.com/photography 2015</i></p>
</div>

And the html code looks like this:

    <img copyright="cc-by 2015 Ibrahim Diallo idiallo.com/photography" src="http://cdn.idiallo.com/photo/36/ants.jpg" alt="Ants" />

This is an attempt to create a new attribute that will make it much easier to determine the copyright grounds of an image programmatically. If successful, the attribute can be used by other tags including but not limited to audio and video.

This initiative is not to fight piracy, or create a weird behavior on the browser to prevent copying. I find it very hard to determine the license on images on certain sites and the owners never reply to email. So this can extend the work the Creative Commons has already done and get everyone on the same page. 

Under the img tag definition on [w3.org](http://www.w3.org/TR/html5/embedded-content-0.html), we can add a new section to properly define the attribute. The content and functionality of the attribute are in no way final. I am open to suggestions visit the [github repo](https://github.com/ibudiallo/imgcopyright/) to contribute.

Find the original blog post here: [HTML image copyright license attribute initiative](http://idiallo.com/blog/img-copyright-attribute-initiative)

Oh and I am not affiliated with the W3C.
