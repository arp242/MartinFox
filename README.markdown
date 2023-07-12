MartinFox is a simple userChrome.css for Firefox 89.

The goal is to have the absolute minimum in there. Honestly I don't really care
how Firefox looks: I usually use the standard for a lot of stuff. But this
"Photon" thing ... yeah nah. I can live with some extra spacing or whatnot, but
it's just impossible to see which tab is active. I don't know how anyone could
possibly think this was a good idea.

A lot of the CSS I found is a complete restyling of Firefox, often with
thousands of lines of CSS. Nice, but that's a bit too much for me. This is just
61 lines.

There's a bunch of other stuff in there as well, it's just a copy of what I like
to put in there. The CSS file is fairly well annotated, so you can
add/remove/modify stuff according to preferences. It should hopefully be fairly
future-compatible too on account being fairly small.


Screenshot
----------
![Screenshot](https://github.com/arp242/MartinFox/blob/master/screenshot.png)


Usage
-----
- Enable `toolkit.legacyUserProfileCustomizations.stylesheets` in about:config
- Open about:support, click on "Profile Directory → Open Directory" (may also be
  named "Folder" instead of "Directory").
- Create a new `chrome` directory and copy `userChrome.css` to there.

[See this post](https://www.reddit.com/r/FirefoxCSS/comments/73dvty/tutorial_how_to_create_and_livedebug_userchromecss/) for some more details.


Notes
-----
- Only tested on my Linux system.

- Needs Firefox 91.

- You need to modify the toolbar colour if you use a dark theme.

- If you set `browser.compactmode.show`  to `true` in about:config you can
  select "density compact". Dunno how long they will keep this around, but it
  works for now.

- Set `widget.non-native-theme.scrollbar.size` if you want a wider scrollbar.

- Set `browser.urlbar.maxRichResults` if you want more results in the URL bar.

License
-------
Do what thou wilt shall be the whole of the license.
