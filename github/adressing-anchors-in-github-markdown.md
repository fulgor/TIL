# Adressing Anchors in GitHub Markdown

This is how you create an anchor to a heading in github flavored md-file.

Example-heading looks like
> `## My Heading`

To create anchor-link:
* make it lower-case,
* change spaces to `-`-characters and 
* wrap the value in brackets `(`#my-heading`)`

Thus, your link should look like this:

> `[Linktext](#my-heading)`

## How about §$%.:&()=?+* ?
Only `[a-z0-9-]` are possible.

Special characters are omitted:

`## How about §$%&()=?+* ?` is `(#how-about--)`

* [See Example for "How about §$%.:&()=?+* ?"](#how-about--)


## See also
* https://guides.github.com/features/mastering-markdown/
