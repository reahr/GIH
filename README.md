# GIH AEM

This README is for those who intend to edit the [GIH](http://as.nyu.edu/irelandhouse.html) site regularly and want an introduction on how to format different components within the site using simple HTML and CSS.

Insert code into a "Generic Content" component, expand editor, and click on the second `</>` button.

Buttons
-------
Change `href` link and `span` text
```html
<p>
        <a class="btn" href="[link of content]" role="button" target="_blank" style="color: rgb(72, 150, 110); text-decoration: none;" onmouseover="this.style.color='#FFF'" onmouseout="this.style.color=' #48966e'; this.style.textDecoration='none'"> 
                <b>[text displayed on button]</b>
        </a>
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

Course Offerings
------------------
````html 
<table style="border: solid 1px; width: 100%;">
    <tbody>
    <!--Change to current semester-->
    <tr>
        <th colspan="3" style="border: solid 1px; padding: 10px;"><b>Graduate Courses for Fall 2018</b></th>
    </tr>
    <!--History Section-->
    <tr>
        <th colspan="3" style="border: solid 1px;"><b>History</b></th>
    </tr>
    <!--First course for history-->
    <tr>
        <td style="border: solid 1px; text-align: center;">IRISH-GA 1416.001 / EURO-GA / HIST-GA</td>
        <td style="border: solid 1px; padding: 10px;"><a
                href="/content/nyu-as/as/research-centers/irelandhouse/courses/history-of-modern-ireland-i-15801800.html"
                target="_blank">History of Modern Ireland I: To 1800</a><br>
            Thomas Truxes<br>
            Wednesdays 3:30-6:00 PM<br>
            Contact Irish Studies for registration code
        </td>
    </tr>
    <!--Second course for history-->
    <tr>
        <td style="border: solid 1px; text-align: center;">IRISH-GA</td>
        <td style="border: solid 1px; padding: 10px;"><a
                href="/content/nyu-as/as/research-centers/irelandhouse/courses/history-of-modern-ireland-i-15801800.html"
                target="_blank">Irish in New York</a><br>
            Marion Casey<br>
            Wednesdays 6:10-8:40 PM<br>
            Contact Irish Studies for registration code
        </td>
    </tr>
    <!--Literature section-->
    <tr>
        <th colspan="3" style="border: solid 1px;"><b>Literature</b></th>
    </tr>
    <!--First course for literature-->
    <tr>
        <td style="border: solid 1px; text-align: center;">IRISH-GA 1085.001</td>
        <td style="border: solid 1px; padding: 10px;"><a
                href="/content/nyu-as/as/research-centers/irelandhouse/courses/topics-in-irish-literature.html"
                target="_blank">Topics in Irish Literature: The Big House Novel</a><br>
            Kelly Sullivan<br>
            Tuesdays 6:10-8:40 PM<br>
            Contact Irish Studies for registration code
        </td>
    </tr>
    <!--Irish Studies / Culture set-->
    <tr>
        <th colspan="3" style="border: solid 1px;"><b>Irish Studies</b></th>
    </tr>
    <!--First course for culture-->
    <tr>
        <td style="border: solid 1px; text-align: center;">IRISH-GA 1001</td>
        <td style="border: solid 1px; padding: 10px;"><a
                href="/content/nyu-as/as/research-centers/irelandhouse/courses/irish-studies-seminar-i.html"
                target="_blank">Irish Studies MA Seminar I</a><br>
            John P. Waters<br>
            Wednesdays 6:10-8:40 PM<br>
            Contact Irish Studies for registration code
        </td>
    </tr>
    <!--Second course for culture-->
    <tr>
        <td style="border: solid 1px; text-align: center;">IRISH-GA 1319</td>
        <td style="border: solid 1px; padding: 10px;">Irish Music in America 1750-Present<br>
            Mick Moloney<br>
            Mondays 6:10-8:40 PM<br>
            Contact Irish Studies for registration code
        </td>
    </tr>
    <!--Section for other-->
    <tr>
        <th colspan="3" style="border: solid 1px;"><b>Other</b></th>
    </tr>
    <!--First course for other-->
    <tr>
        <td style="border: solid 1px; text-align: center;">IRISH-GA 1097</td>
        <td style="border: solid 1px; padding: 10px;"><a
                href="/content/nyu-as/as/research-centers/irelandhouse/courses/independent-study.html" target="_blank">Independent
            Study</a><br>
            Miriam Nyhan Grey<br>
            Contact Irish Studies for registration code
        </td>
    </tr>
    <!--Second course for other-->
    <tr>
        <td style="border: solid 1px; text-align: center;">IRISH-GA 1099</td>
        <td style="border: solid 1px; padding: 10px;"><a
                href="/content/nyu-as/as/research-centers/irelandhouse/courses/guided-research.html" target="_blank">Guided
            Research</a><br>
            Miriam Nyhan Grey<br>
            Contact Irish Studies for registration code
        </td>
    </tr>
    </tbody>
</table>
````
[Example](https://ursa.cms.nyu.edu/content/nyu-as/as/research-centers/irelandhouse/graduate/CourseOfferingsF17.html)

Each section is commented along with each course for the section. If you need to remove a table row, remove the <tr>...</tr> for the extra course offering.

All information is within the <td>...</td>, follow the template for new courses and potentially new sections.


