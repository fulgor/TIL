# Adressing Anchors in GitHub Markdown

**This is how you create an anchor to a heading in a github flavored md-file.**

**Heading:**
> `## My Heading!!`

**Anchor:**

Only `[0-9a-zäöü-]` are allowed.

Thus, take the heading and:
* make it lower-case,
* change spaces to `-`-characters,
* delete every other character and 
* wrap the value in brackets `()`
Your link should look like this:

> `[Linktext](#my-heading)`

## See also
* [Link By Reference In GitHub Markdown](https://github.com/fulgor/TIL/blob/master/github/link-by-reference-in-github-markdown.md)
* https://guides.github.com/features/mastering-markdown/
