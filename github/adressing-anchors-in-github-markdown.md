# Adressing Anchors in GitHub Markdown

## How about §$%&()=?+* ?

This is how you create an anchor to a heading in github flavored md-file.

Example-heading looks like
> `## My Heading`

To create anchor-link:
* make it lower-case,
* change spaces to `-`-characters and 
* wrap the value in brackets `(`#my-heading`)`

Thus, your link should look like this:

> `[Linktext](#my-heading)`

Oh, one more rule: dots are omitted:

`## Python Script bjmd.py` is `(#python-script-bjmdpy)`

## See also
* https://guides.github.com/features/mastering-markdown/
