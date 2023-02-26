*Reading Notes*

*LAB 05 NOTES*

**Alt attributes** enable screen readers to read the information about on-page images for the benefit of a person with complete lack of sight, visually impaired, or who is otherwise unable to view the images on the page. Alt text will be displayed in place of an image if an image file cannot load.
**Ways to create image accessibility**:
- Add alt text and title if you want your images to be conveyed to all users.
- If the picture is purely decorative, provide at least null alt text (alt=””).
- Avoid text in images. If it is impossible, make sure that this text is repeated in alt text.

Use a < figure > element to mark up a photo in a document, and a < figcaption > element to define a caption for the photo:

< figure >
  
  < img src = "pic_trulli.jpg" alt = "Trulli" style = "width:100%" >
  
  < figcaption > Fig.1 - Trulli, Puglia, Italy. < /figcaption >

< /figure >

JPEG image is generally smaller than PNG image of same image. SVG image is generally larger than JPEG image of same image. JPEG images are not editable. SVG images are text based and are easy to edit.

JPEG: This is an ideal image format for all types of photographs. PNG: This format is perfect for screenshots and other types of imagery where there's not a lot of color data. GIF: If you want to show off animated graphics on your site, this is the best image format for you.

Foreground colors(colors which are before background colours) are the colours you see on the screen before the background colours.


You can add space in HTML to any lines of text. You can use the &nbsp; HTML entity to create blank spaces in both paragraph text and text in tables, for example.
