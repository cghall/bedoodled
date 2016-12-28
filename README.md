# bedoodled
Source code for the [Bedoodled website](bedoodled.co.uk).

Default branch is `gh-pages`.

==============
Making Changes
==============

The following steps apply regardless of the changes made:

- Create a local copy of the repository using git (command line using `git clone [repo-link]`)
- Make your changes (see below for common changes)
- Commit changes locally (via desktop app or command line using `git commit -m '[your message here]'`)
- Push changes to server (via desktop app or command line using `git push origin gh-pages`)

==============
Common Changes
==============

**Adding a new blog post**

This can be done very simply by adding a new markdown file to the `_posts` folder. The easiest way to do this is to copy an existing file and tweak the content - this ensures that the key metadata (e.g. post_author) is automatically included. Remember to follow the existing naming convention for post files `[yyyy]-[mm]-[dd]-[post-title].markdown`.

**Previewing changes**

Sometime you'll want to preview the changes you have made before committing them to the web. If you've got Jekyll installed locally this can easily be done by running `jekyll serve` from the command line and going to your [http://localhost:4000/index.html](http://localhost:4000/index.html).
