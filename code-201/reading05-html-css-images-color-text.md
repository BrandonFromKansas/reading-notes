# Images, Color, and Text

Ensuring that as many people as possible have access to the things we build and design is 100% part of our jobs. As developers, we should automatically want to make sure that the websites we work on, have high accessibility scores. It makes no sense to me to work and build something only to allow a select group of people to have access to it. As creators, we should want to share the work we do with as many people as possible. Not for recognition purposes but because building a web that is accessible by any and everyone should be the end goal, in my opinion.

## HTML Media
[Using Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
[Common Image Types](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types)
[Choosing Image Formats](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#choosing_an_image_format)

#### 1. What is a real world use case for the `alt` attribute being used in a website?
- It is meant to be a textual description of the image being displayed. 
- It is used for instances when the image cannot be seen/displayed or if the image is taking longer to render due to a slower internet connection. 
- `alt` text is useful for a number of reasons:
  * A user is visually impaired and uses a screen reader. `alt` text is available to describe the image to these users. 
  * Allows developers to include text for search engines to utilize. Which can hopefully lead to more site traffic.
  * Some users turn images off in order to reduce data transfer volume and distractions (i.e. mobile phone users or in countries with limited or expensive bandwidth).

#### 2. How can you improve accessibility of images in an HTML document?
- A developer should keep in mind that captions and `alt` text have very distinct roles.
- Captions benefit users who can see the image.
- `alt` text provides the same funtionality as a broken/absent image. It should describe exactly what the image is of.
- Captions and `alt` text should never just say the same thing.

#### 3. Provide an example of when the `figure` element would be useful in an HTML document.
- When a developer wants to add a caption to an image.
- The `<figure>` and `<figcaption>` elements can be used to provide a semantic container for figures, and to clearly link the figure to the caption.
- Assistive technology can also be used with the `<figure>` and `<figcaption>` elements.

#### 4. Describe the difference between a `gif` image and an `svg` image, pretend you are explaining to an elder in your community.
- A `gif` is like our generation's version of a flipbook. A bunch of images stacked on top of each other that give the illusion of motion by cycling through them over and over again. Ta-da!
- A `svg` image is like a box that contains the recipe for how an image is supposed to be put together. Once the computer follows the recipe, the image is generated.

#### 5. What image type would you use to display a screenshot on your website and why?
- PNG because it has a more precise reproduction of the source images.
- Even though WebP/AVIF provide better compression and reproduction but their browswer support is more limited at this time.


## Learn CSS
[Using Color in CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color)
[Styling HTML Text Elements](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)

#### 1. Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.
- A background color would be the color that you see "behind" the text on a page.
- "The `color` property sets the color of the foreground content of the selected elements, which is usually the text, but can also include a couple of other things, such as an underline or overline placed on text using the `text-decoration` property." - According to [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)

#### 2. Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?
- I would go over with him what kind of color palette or scheme he was looking for - making sure we picked colors that will allow any and all users to access and read his site.
- Then I am creating a css stylesheet and would begin adding the colors we talked about until the site was colored the way he wanted it.

#### 3. What should you consider when choosing fonts for an HTML document?
- Availability. There are only a certain number of fonts that are widely available across all systems. These are the so-called **web safe fonts**

#### 4. What do `font-size`, `font-weight`, and `font-style` do to HTML text elements?
- `font-size`: sets the size of the font. Changing the font size also updates the sizes of the font size-relative `<length>` units, such as `em` and `ex`.
- `font-weight`: determines the boldness of the text.
- `font-style`: sets whether a font should be styled with a normal, italic, or oblique face from its `font-family`.

#### 5. Describe two ways you could add spacing around the characters displayed in an `h1` element.
- A developer could use either the `letter-spacing` property to affect the space between each letter.
- Or they could use the `word-spacing` property and affect the space between each word.


## Things I Want to Know More About
- [Color Blindness and Web Design](https://www.usability.gov/get-involved/blog/2010/02/color-blindness.html)
- [Medline Plus: Color Blindness](https://medlineplus.gov/colorblindness.html)


