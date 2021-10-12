# Palatinate-Flavored-Yin-and-Yang

Palatinate in its current iteration is a green fork of the [Yin & Yang theme](https://github.com/chetachiezikeuzor/Yin-and-Yang-Theme) that supports my personal preferred features and workflows. I am not a particularly talented front-end developer, but often when I showcase my notes people ask what CSS I’m using, so it was easiest to provide it as a package. Chetatchi did 90% of the work, I just added some frills that I personally find useful. If you also find it useful, please visit her [Buy Me A Coffee](https://www.buymeacoffee.com/chetachi) page and give her dollars, because she’s worked hard to make using Obsidian a beautiful and clean experience!

You can download its ![previous incarnation](og-palatinate.jpg) at [palatinate.css](palatinate.css).

Features:

- supports the `<cite>` tag, intended to be used in a Markdown friendly way at the end of a blockquote for ease of attribution. (See Also: this [stack overflow](https://stackoverflow.com/questions/2002120/citing-the-author-of-a-blockquote-using-markdown-syntax) discussion). Note: For wikilinks to work inside the cite tag, you might need a blank `>` blockquote line before the `> <cite> [[wikilink]]</cite>`.
- disables ligatures in edit mode so that `<!-- html comments -->` doesn’t look unbalanced.
- uses a monospaced font for `%% comments %%`
- adds a cssclass for `longform` writing that enforces readable line width and a serif font.
- adds a cssclass for `dailynote` that aligns the heading to the right instead of the left.
- supports the `<aside>` tag, intended to allow text to flow around it instead of the tag being in the gutter. If you prefer your `<aside>` boxes to be in the gutter, you’ll need to change the numbers yourself.
- adds a minor tweak to “fix” the alignment of the top bar.
- includes fancier blockquotes
- provides icons for files and folders
- prettifies the colors of the graph
- improves upon the native `<hr>` bar.
- provides visually distinct headers that differentiate between levels 1-6 using shades of green.
- includes relationship lines for files and bullets.
- adds support for additional checklist blocks like `- [?]` and `- [>]`
- adds background color to differentiate between dataview table rows

![sourcenote](sourcenote.png)

![table+charsheet](\table+charsheet.PNG)

![sample-note](\sample-note.png)

## Credits

Thanks @death_au, @silver, @foreveryone, @slrvb, @chetachi, @klaas and everyone else in the Obsidian Discord who helped me put this together either directly or by providing code for me to build off of over the last few months!
