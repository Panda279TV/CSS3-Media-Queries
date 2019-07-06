# CSS-Media-Queries-Template By Panda279TV
###### The Best CSS Media Queries Template! Just copy and start!

----------

## Useful Links

https://en.wikipedia.org/wiki/Media_queries

https://www.w3schools.com/cssref/css3_pr_mediaquery.asp

https://www.w3schools.com/css/css_rwd_mediaqueries.asp

https://developer.mozilla.org/de/docs/Web/CSS/Media_Queries/Using_media_queries

https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries

https://developers.google.com/web/fundamentals/design-and-ux/responsive/

https://css-tricks.com/snippets/css/media-queries-for-standard-devices/

https://css-tricks.com/?s=media+queries&orderby=relevance&post_type=post%2Cpage%2Cguide

----------

## Can I Use Media Queries On Browsers

https://caniuse.com/#feat=css-mediaqueries

----------

## Definition and Usage
The @media rule is used in media queries to apply different styles for different media types/devices.

Media queries can be used to check many things, such as:

* width and height of the viewport
* width and height of the device
* orientation (is the tablet/phone in landscape or portrait mode?)
* resolution
* Using media queries are a popular technique for delivering a tailored style sheet (responsive web design) to desktops, laptops, tablets, and mobile phones.

You can also use media queries to specify that certain styles are only for printed documents or for screen readers (mediatype: print, screen, or speech).

In addition to media types, there are also media features. Media features provide more specific details to media queries, by allowing to test for a specific feature of the user agent or display device. For example, you can apply styles to only those screens that are greater, or smaller, than a certain width.

----------

## Media Querie Head Tag

#### The media queries will only work if this line has been included in the head tag of the HTML Structure!

`<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">`


meta name="viewport" | content="width=device-width" sets the width of the screen for mobile devices to the actual resolution in width.

Meta content="viewport" | sets the width to the actual width.

initial-scale | prevents zooming when loading the page.

user-scalable="no" | prevents the user from enlarging or reducing the page.


----------

## Media Queries Tags
#### Media Types
| Value |  | Description |
| ------------- |:--:| ------------- |
| all |  | Default. Used for all media type devices |
| print |  | Used for printers |
| screen |  | Used for computer screens, tablets, smart-phones etc |
| spech |  | Used for screenreaders that "reads" the page out loud |

#### Media Features
| Value |  | Description |
| ------------- |:--:| ------------- |
| any-hover |  | Does any available input mechanism allow the user to hover over elements? (added in Media Queries Level 4) |
| any-pointer |  | Is any available input mechanism a pointing device, and if so, how accurate is it? (added in Media Queries Level 4) |
| aspect-ratio |  | The ratio between the width and the height of the viewport |
| color |  | The number of bits per color component for the output device |
| color-gamut |  | The approximate range of colors that are supported by the user agent and output device (added in Media Queries Level 4) |
| color-index |  | The number of colors the device can display |
| grid |  | Whether the device is a grid or bitmap |
| height |  | The viewport height |
| hover |  | Does the primary input mechanism allow the user to hover over elements? (added in Media Queries Level 4) |
| inverted-colors |  | Is the browser or underlying OS inverting colors? (added in Media Queries Level 4) |
| light-level |  | Current ambient light level (added in Media Queries Level 4) |
| max-aspect-ratio |  | The maximum ratio between the width and the height of the display area |
| max-color |  | The maximum number of bits per color component for the output device |
| max-color-index |  | The maximum number of colors the device can display |
| max-height	 |  | The maximum height of the display area, such as a browser window |
| max-monochrome |  | The maximum number of bits per "color" on a monochrome (greyscale) device |
| max-resolution |  | The maximum resolution of the device, using dpi or dpcm |
| max-width |  | The maximum width of the display area, such as a browser window |
| min-aspect-ratio |  | The minimum ratio between the width and the height of the display area |
| min-color |  | The minimum number of bits per color component for the output device |
| min-color-index |  | The minimum number of colors the device can display |
| min-height |  | The minimum height of the display area, such as a browser window |
| min-monochrome |  | The minimum number of bits per "color" on a monochrome (greyscale) device |
| min-resolution |  | The minimum resolution of the device, using dpi or dpcm |
| min-width |  | The minimum width of the display area, such as a browser window |
| monochrome |  | The number of bits per "color" on a monochrome (greyscale) device |
| orientation |  | 	The orientation of the viewport (landscape or portrait mode) |
| overflow-block |  | How does the output device handle content that overflows the viewport along the block axis (added in Media Queries Level 4) |
| overflow-inline |  | 	Can content that overflows the viewport along the inline axis be scrolled (added in Media Queries Level 4) |
| pointer |  | 	Is the primary input mechanism a pointing device, and if so, how accurate is it? (added in Media Queries Level 4) |
| resolution |  | The resolution of the output device, using dpi or dpcm |
| scan |  | The scanning process of the output device |
| scripting |  | 	Is scripting (e.g. JavaScript) available? (added in Media Queries Level 4) |
| update |  | How quickly can the output device modify the appearance of the content (added in Media Queries Level 4) |
| width |  | The viewport width |

----------


