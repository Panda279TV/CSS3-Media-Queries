# CSS3 Media Queries Template By Panda279TV

###### The Best CSS Media Queries Template! Just Copy and Start!

###### In this ReadMe some text are copied from W3Schools, Thanks! = https://www.w3schools.com/

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

### CSS Grids

https://www.w3schools.com/css/css_grid.asp

https://developer.mozilla.org/de/docs/Web/CSS/CSS_Grid_Layout

https://css-tricks.com/snippets/css/complete-guide-grid/

https://learncssgrid.com/

https://getbootstrap.com/docs/4.0/layout/grid/

https://materializecss.com/grid.html

https://imperavi.com/kube/docs/modules/grid/

https://bulma.io/documentation/columns/

https://milligram.io/grids.html

https://foundation.zurb.com/grid.html

https://blueprintcss.dev/

http://flexboxgrid.com/

https://960.gs/

http://getskeleton.com/

https://webjeda.com/web-grid/

https://daneden.github.io/Toast/

https://purecss.io/grids/

https://beauter.io/docs/grid/

https://jeet.gs/

https://vitalcss.com/components/

http://www.cutegrids.com/

----------

## Can I Use Media Queries On Browsers?

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

## Head Tag

#### The media queries will only work if this line has been included in the head tag of the HTML Structure!

`<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">`


meta name="viewport" | content="width=device-width" sets the width of the screen for mobile devices to the actual resolution in width.

Meta content="viewport" | sets the width to the actual width.

initial-scale | prevents zooming when loading the page.

user-scalable="no" | prevents the user from enlarging or reducing the page.

----------

## Most used Tags

| Value |  | Description |
| :--- |:---:| :--- |
| all |  | Default. Used for all media type devices |
| and |  | The and keyword combines a media feature with a media type or other media features. |
| ,(comma) |  | Commas are used to combine multiple media queries into a single rule. |
| not |  | The not keyword reverts the meaning of an entire media query. |
| only |  | The only keyword prevents older browsers that do not support media queries with media features from applying the specified styles. It has no effect on modern browsers. |
| print |  | Used for printers |
| screen |  | Used for computer screens, tablets, smart-phones etc |
| spech |  | Used for screenreaders that "reads" the page out loud |
| width |  | The viewport width |
| max-width |  | The maximum width of the display area, such as a browser window |
| min-width |  | The minimum width of the display area, such as a browser window |
| device-width |  | The device width |
| min-device-width |  | The min device width |
| max-device-width |  | The max device width |
| resolution |  | The resolution of the output device, using dpi or dpcm |
| orientation |  | 	The orientation of the viewport (landscape or portrait mode) |

----------

## All Tags

#### Media Types
| Value |  | Description |
| :--- |:---:| :--- |
| all |  | Default. Used for all media type devices |
| and |  | The and keyword combines a media feature with a media type or other media features. |
| ,(comma) |  | Commas are used to combine multiple media queries into a single rule. |
| not |  | The not keyword reverts the meaning of an entire media query. |
| only |  | The only keyword prevents older browsers that do not support media queries with media features from applying the specified styles. It has no effect on modern browsers. |
| handheld |  | Used for handheld devices |
| print |  | Used for printers |
| projection |  | Used for projection |
| screen |  | Used for computer screens, tablets, smart-phones etc |
| spech |  | Used for screenreaders that "reads" the page out loud |
| tv |  | Used for tvs devices |

#### Media Features
| Value |  | Description |
| :--- |:---:| :--- |
| any-hover |  | Does any available input mechanism allow the user to hover over elements? (added in Media Queries Level 4) |
| any-pointer |  | Is any available input mechanism a pointing device, and if so, how accurate is it? (added in Media Queries Level 4) |
| aspect-ratio |  | The ratio between the width and the height of the viewport |
| color |  | The number of bits per color component for the output device |
| color-gamut |  | The approximate range of colors that are supported by the user agent and output device (added in Media Queries Level 4) |
| color-index |  | The number of colors the device can display |
| device-width |  | The device width |
| forced-colors |  | 	Detect whether user agent restricts color pallete (added in Media Queries Level 5) |
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
| min-device-width |  | The min device width |
| max-device-width |  | The max device width |
| monochrome |  | The number of bits per "color" on a monochrome (greyscale) device |
| orientation |  | 	The orientation of the viewport (landscape or portrait mode) |
| overflow-block |  | How does the output device handle content that overflows the viewport along the block axis (added in Media Queries Level 4) |
| overflow-inline |  | 	Can content that overflows the viewport along the inline axis be scrolled (added in Media Queries Level 4) |
| pointer |  | 	Is the primary input mechanism a pointing device, and if so, how accurate is it? (added in Media Queries Level 4) |
| prefers-reduced-motion |  | The user prefers less motion on the page (added in Media Queries Level 5) |
| prefers-reduced-transparency |  | The user prefers reduced transparency (added in Media Queries Level 5) |
| prefers-contrast |  | Detects if the user has requested the system increase or decrease the amount of contrast between adjacent colors (added in Media Queries Level 5) |
| prefers-color-scheme |  | 	Detect if the user prefers a light or dark color scheme (added in Media Queries Level 5) |
| resolution |  | The resolution of the output device, using dpi or dpcm |
| scan |  | The scanning process of the output device |
| scripting |  | 	Is scripting (e.g. JavaScript) available? (added in Media Queries Level 4) |
| update |  | How quickly can the output device modify the appearance of the content (added in Media Queries Level 4) |
| width |  | The viewport width |

----------

#### Thank you very much. I hope I could help something with all the media queries.
#### greetings Panda
