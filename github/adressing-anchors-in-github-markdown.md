# Adressing Anchors in GitHub Markdown

**This is how you create an anchor to a heading in a github flavored md-file.**

**Heading:**
> `## My Heading!!`

**Anchor:**

Only `[a-z0-9-]` are allowed.

Thus, take heading and:
* make it lower-case,
* change spaces to `-`-characters,
* delete every other character and 
* wrap the value in brackets `()`

Thus, your link should look like this:

> `[Linktext](#my-heading)`

## See also
* https://guides.github.com/features/mastering-markdown/
