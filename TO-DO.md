# TODO

[Code For America's style guide](http://codeforamerica.clearleft.com/) is an excellent reference we can look to in generating components for our own site.


## Small Components to Build / Consider

- image & captions
- icons / favicon?

- audio player
- video player
- video subtitles?

- links
  - default
  - :hover
  - :visited
  - :active
  - differentiate external links (icon)?

- lists
  - style bullets differently?

- `table`

- `blockquote`

- `cite`

- `details`

- `figure` / `figcaption`


## Bigger Components to Build

We can develop separate prototypes for this as they will require specific box model properties, flexbox, grid, etc.

- Story Masthead
- Navigation
- Video component (w/text, lightbox)
- Photo galleries (A, B, C)
- Infographics (A, B)
- Text / Story w/images

From this we will determine maximum dimensions for photo / video.


## Not Necessary

- Forms


## Notes: `reset.css`

It was recently discovered the default style sheet for Chrome messes with styles more than it used to previously. For instance, a heading inside a structural element (other than `header`) will be downsized by 0.83em. (WTF?)

`reset.css` is a boilerplate css file which I've been using as a scaffold to presumably eliminate conflicts as I built out the guide. As you add to `style.css`, if the result is not as expected, find the tag name in the first block in `reset.css` and remove it.


## Notes: `fonts.css`

`fonts.css` contains all available fonts we can use in the Roboto and Roboto Slab family. This file should not be edited.

`font-family` names are a little weird, I think because they are hard-coded this way into the font file. So this is just the name we have to use when adding to the `style.css`. Sorry it is clunky. :/

Feel free to adjust the font families in `style.css` if you think a change is warranted or add different weight varieties.


## Contributing

Please feel free to tinker / add to our above needs.

Fork this repo into your own account. Create a new branch for the addition or change you would like to make. Make your changes in that branch, even if it is something simple, like creating a style for just a table. We keep branches separate from 'master' so we don't confuse everything! :)

If you need a quick explanation of branching in Git/GitHub, seek me out. :)

We can review the updates during class or hack hours. 
