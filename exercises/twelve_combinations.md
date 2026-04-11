# Exercise Twelve: Combinations

This week's exercise is focused on remixing, combining, and extending the work you've already done. You can use both hand-coded and agentic solutions to making those changes, as covered in this week's video: this might include integrating P5 with Twine and/or Bitsy, building GIF-illustrated hypertexts, adding Tracery to your P5  and beyond. Going back to the basics (such as comics and hypertext) can also be a great way to bring together the components of your making together with material and digital. Leave time for debugging these combinations, as even HTML and JavaScript files can be difficult to combine without errors.

<iframe src="https://openprocessing.org/sketch/2237599/embed/?plusEmbedHash=3f441452&userID=293182&show=sketch" width="600" height="600"></iframe>

The example created in this week's video is available to explore live [on Github Pages](https://anastasiasalter.net/CombinationsCritMaking/), and can be referenced for code samples in [the repository]([https://github.com/AMSUCF/cmportfoliodemo](https://github.com/AMSUCF/CombinationsCritMaking)). You can also fork the examples on OpenProcessing: [the linked escape room](https://openprocessing.org/sketch/2237599) and the [Tracery P5 integration](https://openprocessing.org/sketch/2237590). The escape room is also embedded above, which is an example of dropping an iframe into Markdown, just like we use in the demo. 

Keep in mind the following simple methods for linking and combining materials before you get fancy with Claude Code:

- **iframes** - As shown above, iframes are an excellent way to combine two very different types of material: you can use an iframe to link to another HTML file in your repository and include it in a box inside any other page--for instance, you can display a P5.js sketch or a Bitsy game inside a Twine pages. Here's an example of proper iframe code - just change the html file name to the name of another file in your repository, and adjust the width and height as needed:
```
<iframe src="anotherfile.html" width="600" height="600"></iframe>
```
- **Adding images** - Adding your comic, GIF, selfie, or other image to a HTML file is a two step process. First, upload the image file to the repository where you'll be working: I recommend uploading everything you plan to use before you start. Adding an image to the Twine or as a header above your Bitsy game is fairly straightforward - you can use an image tag, as shown below. For P5.js, reference the code in the linked escape room example:
```
<img src="imagename.jpg">
```
- **Relative links** - If you've uploaded all your html files into the same directory, remember that whichever file you label as index.html will be the default that displays on your GitHub Pages site. If you don't designate one file as index.html, your GitHub Pages site will give a 404 error. Simple links are an easy way to progress from say a Bitsy to a Twine, P5 to a Bitsy game, etc, but you can also use Claude Code to create more complex links from the ending passages or conditions of your interactive pieces, as shown in the demo. Here's the basic link:
```
<a href="otherfile.html">Text of the link.</a>
```

## The Multimodal Prompt

This week's prompt is intentionally flexible to allow you to choose the tools, platforms, and experiments from our previous weeks that you most want to revisit and expand upon. Here's a broad recipe for your multimodal making:

- **Combine at least three ingredients** - Depending on your interests, these might include more visual, procedural, or data-driven components that work well together. For example, Tracery combines well with P5.js, and both might make a fantastic "prelude" to a Twine piece geared towards *Kairos* or *the digital review.* Note the three tools you used and why you selected them in your introduction to your reflection prompt.

- **Convey a coherent theme.** - Approach your multimodal exercise as a coherent whole: rather than showcasing the technologies and making execises from previous iterations as fragmented components, revisit each part and think about how it adds to an overall theme. Revisiting your text will help draw the pieces together. Agentic tools can help with making the works "fit" together technically, but you need to guide the intention of the pieces.

- **Work towards aesthetic unity.** - Think about ways to connect the components of your work visually: can you revisit font choices? Use a shared color palette? Try to avoid drawing attention to the separate pieces of your work - instead, play with strategies to bring the interfaces, and ideas, together.

As always, please share screenshots from your process as well as a link to your new piece on GitHub Pages. 
