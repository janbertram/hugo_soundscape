# Soundscape – a shortcode for Hugo

A shortcode for Hugo that adds a mouseover sound to an image.

## Usage

- Place the `soundscape.html` file in the folder `layouts/shortcodes/` of your Hugo project.
- Create a folder named `soundscapes` in the `static`- folder of the Hugo project, place the image- and sound-files there.
- Images should be present as `.jpg`-files, sounds as `.mp3`-files, the names of these files must match.
- You then should be able too use the soundscape-shortcode like this:

  ```html
  {{< soundscape name_of_file "Alternate text" >}}
  ```

## Known limitations

This is an early version of something I tried to achieve, and I am learning to use Hugo as a static site generator since not very long –  please keep that in mind.

The shortcode will easily break when you place the images or sounds somewhere else. Also, there is a limitation to just one soundscape-image per site (or to the same sound for all the pictures on the same site).

Suggestions, improvements or links to sites that use this shortcode (to feature them here) are welcome!