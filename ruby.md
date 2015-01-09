---
layout: page
title: Ruby
permalink: /ruby/
---

This is the start of the Ruby Style Guide.

Background

Much of the Ruby section of this style guide comes from the semi-official
[Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide).  This page
should take priority.

General Editing Guidelines

* Use soft tabs with a two space indent.
* ALWAYS remove trailing white space
* End your file with an empty line.
* Your editor should be set to use unix-style line endings.
    * In Sublime Text, specify a setting as follows:

      ~~~
      "default_line_ending": "unix"
      ~~~

* Prefer lines under 80 characters. Keep all lines under 100.
    * In Sublime Text, rulers are a good way of keeping track.
      Specify a setting:

      ~~~
      "rulers": [80, 100]
      ~~~

### Default Sublime Text Settings

~~~
"default_line_ending": "unix",
"rulers":
[
  80,
  100
],
"tab_size": 2,
"translate_tabs_to_spaces": true,
"trim_trailing_white_space_on_save": true
~~~


