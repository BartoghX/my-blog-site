---
creation date: <% tp.file.creation_date() %>
modification date: <% tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
title: <% tp.file.cursor(1) %>
author: Kim Petersen
date: <% tp.file.creation_date() %>
tags: 
image: /assets/blog/<% tp.file.cursor(2) %>
imageAlt: <% tp.file.cursor(3) %>
description: <% tp.file.cursor(4) %>
---
<% tp.file.cursor(5) %>
