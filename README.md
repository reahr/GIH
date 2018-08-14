# GIH AEM

This README is for those who intend to edit the [GIH](http://as.nyu.edu/irelandhouse.html) site regularly and want an introduction on how to format different components within the site using simple HTML and CSS.

Insert code into a "Generic Content" component, expand editor, and click on the second `</>` button.

Buttons
-------
Change `href` link and `span` text
```html
<p>
        <a class="btn" href="http://www.publicaffairsbooks.com/book/a-radical-faith/9781568585734" role="button" target="_blank" style="color: rgb(72, 150, 110); text-decoration: none;" onmouseover="this.style.color='#FFF'" onmouseout="this.style.color=' #48966e'; this.style.textDecoration='none'"><b>Buy The Book</b></a>
</p>
```
[Example](http://as.nyu.edu/irelandhouse/about/rental-information/non-nyu-space-rental-information.html)

Events
------
* Change `padding-bottom` to 5px and `padding-right` to 20px
* Change `height` to 250 and `width` to 250
* Change `src`to desired path of image 

```html
<div>
        <p style="float: left; padding-right: 20px; padding-top: 5px;"><img src="asset" alt="9-16-16PatrickOurceau.JPG"></p>
        <div>Fiddle standout Patrick Ourceau - born in Paris, long resident in New York and now living in Toronto - is one of the most accomplished members of Ireland's musical foreign legion. His style is based on that of his musical heroes, old-time fiddle, flute and concertina players from Clare and east Galway. One of those heroes was the late east Galway and New York flute player Jack Coen, whose son Jimmy is one of the few guitarists in Irish traditional music who concentrates on melody rather than accompaniment.</div>
</div>
```
* In order to remove certain paragraphs/text from being formatted alongside an image, add `clear:left` to the `style` attribute
* For any minor information on events page, add `font-size:75%` to the `style` attribute
```
<div style="clear: left; font-size: 75%;">
        <p>Free admission to Members of Glucksman Ireland House and to all students/faculty with a valid NYU I.D. card. For non-members: $15 donation at the door for the Blarney Star Concert Series.</p>
        <p>Tickets at the door only; the Blarney Star Concert Series does not accept reservations.</p>
        <p>All events are supported by members of Glucksman Ireland House.&nbsp;<a href="http://irelandhouse.fas.nyu.edu/page/enroll.html">Become a member</a>.</p>
</div>
```
[Example](https://ursa.cms.nyu.edu/editor.html/content/nyu-as/as/research-centers/irelandhouse/events/spring-2017/BlarneyStarCathalHayden.html)



