---
title: "{{ replace .Name "-" " " | title }}" # Title of the blog post.
date: {{ .Date }} # Date of post creation.
description: "Article description." # Description used for search engine.
featured: true # Sets if post is a featured post, making appear on the home page side bar.
draft: true # Sets whether to render this page. Draft of true will not be rendered.
# menu: main
featureImage: "file.jpg" # Sets featured image on blog post. Relative to post folder.
thumbnail: "images/thumbnail.png" # Sets thumbnail image appearing inside card on homepage. Relative to static folder.
shareImage: "images/posts/share.png" # Designate a separate image for social media sharing. Relative to static folder.
codeMaxLines: 10 # Override global value for how many lines within a code block before auto-collapsing.
codeLineNumbers: false # Override global value for showing of line numbers within code block.
figurePositionShow: true # Override global value for showing the figure label.
categories:
  - Technology
tags:
  - Tag_name1
  - Tag_name2
---

**Insert Lead paragraph here.**