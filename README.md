# Kaihatsusha.com
The "official" Kaihatsu website.

## How-to:
This guide will teach you the basics on how to post on this here website.
This website is built on Jekyll, so remember that and if you have any issues, you can do one of them there fancy google searches to fix it.

1. To post a video, navigate to /_posts/.
2. Create a .md file under the naming convention; yyyy-mm-dd-name-of-post.md.
   * This website uses markdown for it's post format. Google markdown for formatting guidelines.
3. Put this code snippet on the top:
   * This is YAML, which is REQUIRED for Jekyll to process the post as a post.
```
---
layout: post
title: "Theory: The Pokédollar's TRUE VALUE?"
series: "theory"
embed: https://www.youtube.com/embed/DkD23HYXbHE
thumb: "/assets/thumbnails/theory/2_dollar.png"
date: 2017-04-12
---
```
4. Edit this header to represent the new video.
  * LEAVE LAYOUT ALONE!
  * title is the title of the video. Make sure it's surrounded by "".
  * series is the series keyword. examples are culture-bits, the-science-behind, theory, & marxist-march. Please contact Yukon is you need help adding a new series.
  * embed is the embed link to the video. It's in the iframe Youtube gives you when you hit share > embed.
  * thumb is the thumbnail directory to the wanted thumbnail.
  * date is the date the video was released.
5. Write your description under said header, using markdown as formatting.
6. Commit the file, (sync if on desktop) and you should see your post in about 3 minutes.

Any questions? Email hello@yukonw.com for support.