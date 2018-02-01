---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
date: {{ .Date }}
formattedDate: "{{ dateFormat "Jan 2" .Date }}, {{ dateFormat "2006" .Date }}"
time: {{ dateFormat "15:04" .Date }}
tags: []
section:
header: "Article 2: Too Many Articles?"
subheader: "The subheader, highlighting some tagline of the article"
header_image: "test-image.png"
img_info: "This is a test description for the header info."
social: "twitter"
contributor: nnobody
---

