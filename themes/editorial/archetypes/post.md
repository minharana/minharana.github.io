+++
date = "{{ .Date }}"
draft = true
title = "{{ replace .File.ContentBaseName "-" " " | title }}"
image = "images/your-image.jpg"
+++

Write your post content here. This is a starter template for new posts created with:

hugo new posts/{{ .File.BaseFileName }}.md

Add more content below.
