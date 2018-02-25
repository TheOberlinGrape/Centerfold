---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
date: {{ .Date }}
formattedDate: "{{ dateFormat "Jan 2" .Date }}, {{ dateFormat "2006" .Date }}"
time: {{ dateFormat "3:04pm" .Date }}
tags: []
issueid: {{ dateFormat "2006-01" .Date }}
draft: true
featured: false
# weight: 1 
section: ""
sectionid: ""
header: "Article 2: Too Many Articles?"
subheader: "The subheader, highlighting some tagline of the article"
header_image: "test-photo.png"
img_info: "This is a test description for the header info."
contributor: nnobody
---

