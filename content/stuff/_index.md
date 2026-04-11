+++
title = "Stuff"
description = "Bookmarks, books, and movies."
template = "prose.html"

[extra]
title = "Stuff"
subtitle = "A little bit of this, a little bit of that, and a whole lot of 'why not?'"
+++

# Bookmarks

{{ collection(file="bookmarks.toml") }}

# Books

{{ collection(file="books.toml") }}

# Movies

{{ collection(file="movies.toml") }}
