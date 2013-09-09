angular-web-portfolio
=====================

This a gallery designed to show up live websites, as a web portfolio.

The angular web portfolio uses iframes to show the website live within the gallery.

Requirements
------------
*AngularJS
*jQuery 1.6.4 or higher

Optional
-------- 
*Bootstrap 3

Bootstrap 3 is already included in the project but can be removed and replaced with
css that was commented out in the style.css.


Data
----
In the data/website.json you'll find a json file. This stores the data of the thumbnails,
and the website that you want for the gallery. You don't have to use full paths like I did.

```
    {
        "website": "http://www.vanitylaser.com",
        "thumb": "http://www.zongservices.com/images/featured4.png"
    }

```

Additional Note:
Not recommended if web pages are constantly changing.
