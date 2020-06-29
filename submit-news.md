---
layout: default
title: Submit News
---

{% capture today %}{{'now' | date: '%Y-%m-%d'}}{% endcapture %}
{% capture bblogurl %}https://github.com/billyc/glint-of-valor{% endcapture %}

<div>
<a target="_blank"
    href="{{bblogurl}}/new/master/?filename=/_posts/{{today}}-log-entry.md&value=---%0alayout: post%0aauthor: Your Name%0atitle: %22Item Title%22%0asummary: %22A sentence or two that will show up on the front page%22%0a---%0a%0aSo what happened was...%0a%0a- Use regular markdown for the full news item content%0a- The header at the top of the file MUST contain your character name, item title, and a summary%0a">
<div style="float:right; border: 1px solid #7fb98c; padding: 0 0.5rem; border-radius: 5px;"><p>CREATE POST</p></div></a>

</div>

# Submit news of your adventure

Yay! Feel free to post drawings, stories, event announcements -- anything related to our adventure. To submit news, create a new file in the `_posts` folder on our Github site, with the content of your news item in Markdown format. Here's how to do that:

## Instructions for posting news via GitHub

0. You'll need a free account on Github to post items
1. Click the **`CREATE POST`** button above, to draft a new item in the `_posts` directory of our site.
2. Edit the **author**, **title**, and **summary** lines. The summary will be shown on the front page as a "teaser" blurb.
3. Add your remaining content in [standard Markdown format](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
4. Preview your post using the `Preview` pane, and when done...
5. You're ready to create your file!
   - Click **`Commit New File`** button
6. You're done!

It usually takes just a minute or so for the content to go live.

## If this is too complicated

If this is just too much, [send me an email](mailto:sfbilly@gmail.com) and we'll post your item for you.
