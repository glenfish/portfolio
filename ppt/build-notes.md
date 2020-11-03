# Build Notes

### 1-11-20

My initial design idea is to extend the theme of my LinkedIn profile. It uses a 50's sci-fi theme with a boy and a toy robot. i need to make this a little more professional but I'm considering using the cool factor of retro futuristic design. My concern is that I may not find too many publicly available royalty-free images that meet my needs. For the home page I'd like to go with a hand-drawn blueprint style design of a rocket, with some code superimposed over it, and a 50's toy rocket of the same drawing next to it. This might not work well on a mobile layout so I need to consider the use of space. I'd like the 'above the fold' section of the landing page to have elements of oldschool engineering design, with implied attitude of attention to detail and personal flare.

The index page should have a few distinct sections with scroll links between them,. Use non-horizontal dividers (possibly angled and animated rectangles z-indexed underneath the section divs)

I'd also like some geometric shapes under the menu options to animated in some way of the page to compliment the theme.

The other pages should have a common thread with similar image elements and animations, but different enough to make each page feel fresh.

Color profile: Faded primary colours for accents. Cream for the background. As subtle repeated background motif to extend the desktop version, possibly a wireframe of a 50's robot or similar.

The page width will max out at 1370px with an 1170px main container width for desktop. All desktop space outside of 1370px width will be background.

### 2-11-20

Site header is done for desktop. Still need to adapt for tablet and phone. The 'code' idea wasn't looking good. It feels like a combination of retro and modern design, and the colours I'm really pleased with. It's a cartoonish look with pastel blues, greens, purples and yellows with some red accents. There's a robot and a chalk board that I've separated out as png's and will make them responsive to position based on screen size. Will likely add some subtle animation as well to those elements. The text of my name and the subheader will probably stay part of the image. Since it's a very position critical layout, I'd prefer to have it image based and move the H1 text off the page with css. There's also enough space at the top of the header image to overlay a semi-transparent menu.

The chalk board has been replaced with a smaller robot image. This balances the header much better and doesn't draw the eye unnecessarily. The feel of the banner is now much more pastel, with soothing greens, blues and mauves with accents of faded red on the robot.

The banners for ipad in landscape and portrait modes and the iphone in portrait mode are now done.

```
default uses header.jpg

@media only screen 
and (min-device-width : 375px) 
and (max-device-width : 414px) 
and (orientation : portrait) { /* header-414.jpg */ }

@media only screen 
and (min-device-width : 414px) 
and (max-device-width : 768px) 
and (orientation : landscape) { /* header-768.jpg */}

@media only screen 
and (min-device-width : 768px) { /* header-768.jpg */}

@media only screen 
and (min-device-width : 769px) 
and (max-device-width : 1024px)  { /* header-1024.jpg */}
```
### 3-11-20

Making changes to the media/screen definitions.

I need to create a header image that is 560px wide with the main content (robots and text) occupying a space no wider than 414px in the center. This is for the media size of > 414 and < 561. (update: created image and modified two layouts based on how they looked in Google Developer tools responsive view)

Working grid and flexbox layout in a separate test project until I can get the basis of it working, and then I'll bring it across to the portfolio project. I find that making the sections a unique color and putting dummy text and a headline into each one good for the responsive design. I am yet to do my wireframe design. I feel like I'm doing things the right way. The wireframe will be good for laying out the elements within the responsive framework, once I've got it done.

Grid and flexbox added. The site is now responsive from 355px phones and smaller all the way up to desktops of any size. The max page width is 1370px.
---

## Trello Board

https://trello.com/b/10pDgu2O/portfolio-development

---

## Images

DepositPhotos.com

https://depositphotos.com/2789117/stock-photo-rocket.html

https://www.needpix.com/photo/93757/motherboard-circuit-diagram-circuit-computer-electric-electronic-gadget-green-free-vector-graphics

https://www.publicdomainpictures.net/en/view-image.php?image=241151&picture=dragon-and-bird

<a href="https://www.vecteezy.com/free-vector/futuristic">Futuristic Vectors by Vecteezy attribution</a>





