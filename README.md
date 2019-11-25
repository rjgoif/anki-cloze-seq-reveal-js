# anki-cloze-seq-reveal-js
javascript headers for anki cloze cards that will sequentially reveal cloze deletions


# purpose
Allows you to sequentially reveal answers with matching cloze numbers:

`cloze deletion {{c1::one}} also known as c{{c1::1}}`

becomes 
> cloze deletion [|||] also known as c[|||]

then 
> cloze deletion one also known as c[|||]

then 
> cloze deletion one also known as c1

as the user clicks on the fields. Also works with arrow keys to sequentially reveal. 

My Anki setup also has fields Hint and Extra, which will be revealed after all the cloze deletions are revealed. 

The main javascript header works with the templates that use note type "cloze". 
There is an offshoot that works with basic note types, but that one is not ported to Anki 2.1 yet. 

This isn't really for public distro as it requires too much expertise to implement and I don't want to support it.
