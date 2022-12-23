## The Web Purist

### Learning CSS

Way back, Tumblr was my only social media. No Snapchat streaks ever for me. No, in middle school I was bootlegging Photoshop and making (actually decent?? I got too into it) fan edits. I will not say about who. Tumblr allowed users to make custom themes for their blogs and some people came up with some crazy stuff. Genuinely I wonder how many teenage girls later got into professional web dev bc of this platform. And who said Tumblr wasn't productive for society?

It was my first introduction to HTML and CSS. I thought it was so cool. After learning <i>actual</i> coding languages, I kinda wrote both off as simple skills. That is until I actually tried to start making my own interfaces. Things got complicated from there :/ 

These are just some notes for me to keep track of best practices. 

#### things to look into
- box model
- display
- position
- float & clear
- grid & flexbox
- units?

#### pseudo-classes

#### Units in CSS
[Reference](https://gist.github.com/basham/2175a16ab7c60ce8e001)
[Font Sizing](https://type-scale.com/)
Recommended use: em (relative to closest font-size definition), rem (relative to font size of root element), % (relative to parent element)
- All relative, meaning they scale with screen size
- <code>font-size</code> should only be applied at the lowest possible child elements
* em inherits size from its immediate parent’s font size. Say, if a parent element has font-size:18px, then 1em will be measured as 18px for all its children.

Borders: px
Media Queries: em




#### Grid + Flexbox
[flexbox guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
[grid guide](https://css-tricks.com/snippets/css/complete-guide-grid/)