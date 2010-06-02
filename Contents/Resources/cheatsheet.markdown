Markdown Cheat Sheet
====================



Emphasis
--------

    *italic*   **bold**
    _italic_   __bold__



Links
-----

Inline:

    An [example link to Google](http://google.com/ "Title")

Reference-style labels (titles are optional):

    An [example link to Google][id]. Then, anywhere else in the doc, the link:

    [id]: http://google.com/  "Title"



Images
------

Inline (titles are optional):

    ![alt text](http://www.google.com/intl/en_ALL/images/logo.gif "Title")

Reference-style:

    ![alt text][id]

    [id]: http://www.google.com/intl/en_ALL/images/logo.gif "Title"



Headers
-------

Setext-style:

    Header 1
    ========

    Header 2
    --------

atx-style (closing #'s are optional):

    # Header 1 #

    ## Header 2 ##

    ###### Header 6



Lists
-----

Ordered, without paragraphs:

     1. Foo
     2. Bar

Unordered, with paragraphs:

     * A list item.

       With multiple paragraphs.

     * Bar

You can nest them:

     * Abacus
       * answer
     * Bubbles
       1. bunk
       2. bupkis
          * BELITTLER
       3. burper
     * Cunning



Blockquotes
-----------

    > Email-style angle brackets
    > are used for blockquotes.
    
    > > And, they can be nested.
    
    > #### Headers in blockquotes
    > 
    > * You can quote a list.
    > * Etc.



Code Spans
----------

`<code>` spans are delimited by backticks.

You can include literal backticks
like `` `this` ``.



Preformatted Code Blocks
------------------------

Indent every line of a code block by at least 4 spaces or 1 tab.

    This is a normal paragraph.
    
        This is a preformatted
        code block.



Horizontal Rules
----------------

Three or more dashes or asterisks, optionally separated by spaces:

    ---

    * * *

    - - - - 



Manual Line Breaks
------------------

End a line with two or more spaces:

    Roses are red,  
    Violets are blue.
