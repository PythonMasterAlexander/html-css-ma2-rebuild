Rebuild of MA2 in html & css course on Noroff front-end Development

Teacher feedback on the original assignment
grade - 8/10

Hi Alexander

Browsers do interpret styles differently. Internet Explorer is typically awful at this, and these days there aren't huge differences 

between Firefox and Chrome. I couldn't spot the issue you were seeing, the background color for 'Home' in the nav is yellow on both 

Firefox and Chrome for me. Instead of the big margins on the sides of the content, you can use a max-width to focus the content into 

the middle of the user's screen like so https://codepen.io/noroff-education/pen/VwYpweQ. The HTML is neat and semantic which is great 

to see. One small thing is the h3 in the footer isn't closed correctly. Roboto Slab doesn't get loaded correctly and defaults to 

Times New Roman. The reason the @font-face isn't working is because the 'src' is pointing to a stylesheet and not a font file. Going 

forward you can use the link Google Fonts provides and it in the head of your HTML file. I'd advise against setting fixed px heights 

on elements as you have for .margin-bottom which on my screen forces the 'Hairdressers' link into the footer. Also I see it's in a UL. 

It's not really a list of links, if it's just one link, so rather don't put it in a list.

Overall, good work.

MJ

1. Fix teachers feedback mistakes.

2. Improve font selection for headers and text.

3. Improve colors and site layout.
