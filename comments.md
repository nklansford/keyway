# Comments

## Prof after Deliverable A

Nice work! Things are in great shape here with overall solid structure, semantic markup and useful classes. Here are a few notes:

- Buttons for call to action on this page could be made as `a` tags with `href` pointing just to `#` unless there is an existing site to point to. You can keep the `.button` on them and even keep them inside `p` tags as well if you want. 
- Not sure if we'll need a specific class on each of your `.picture-list li` so consider pulling them unless you have something in mind for needing them.
- The `.intro` inside the `.picture-list` may actually be headings. Even though styled the same as `.intro` from the first text block might be good to use `h3` here and just mimic the styles.
- I ran `Tools` > `Beautify` to tight up formatting and also found a missing closing `li` on the third `.picture-list` item. Went ahead and fixed it.
- In the nested list in the lower portion note that we typically would wait and close the outer `li` after the inner (contained) list closes. In such a case it sometimes is useful to wrap the preceding paragraph as a `p` as well... see the changes I made there. This leads to some additional default spacing but nothing CSS can't fix later. :)

Great progress. Looking forward to the full build next!