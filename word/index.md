---
layout: default
title: O'Reilly Word Template
---
# O'Reilly Media Word Template Quickstart Guide

Congratulations on joining the ranks of O'Reilly authors! We know you're anxious to get started writing, so this document has the bare essentials you'll need to begin working right away, including these downloads:

<div class="center">
<ul class="no-bullets">
<li><a href="ORA.dot">Word template</a></li>
<li><a href="ORA_Preface.doc">Sample Preface file</a></li>
<li><a href="Word_Template_Quick_Start_Guide.doc">QuickStart Guide (Word file)</a></li>
</ul>
</div>

<h2 id="table-of-contents-word">Table of Contents</h2>

* <a href="#system-requirements">System Requirements</a>
* <a href="#installing">Installing the Template</a>
  * <a href="#install-windows">Installing on a Windows Machine</a>
  * <a href="#install-mac">Installing on a Mac</a>
* <a href="#menus-toolbars">The O'Reilly Menus and Toolbars</a>
* <a href="#setting-options">Setting a Few Important Options</a>
* <a href="#paragraph-character-styles">Paragraph and Character Styles</a>
  * <a href="#hyperlnks-filenames-techterms">Hyperlinks, Filenames, and Technical Terms</a>
  * <a href="#styles-follow-styles">Styles that Follow Other Styles</a>
* <a href="#lists-notes">Lists and Notes</a>
* <a href="#tables-figures">Tables and Figures</a>
  * <a href="#tables">Tables</a>
  * <a href="#figures">Figures</a>
  * <a href="#moving-stuff">Moving and Deleting Tables and Figures</a>
* <a href="#code-examples">Code Examples</a>
  * <a href="#code-length">Code Length and Spacing Guidelines</a>
  * <a href="#syntax-highlighting">Code Syntax Highlighting</a>
  * <a href="#code-annotation">Code Annotations</a>
* <a href="#xrefs">Cross References</a>
* <a href="#misc">Miscellany</a>
  * <a href="#keyboard-shortcuts">Keyboard Shortcuts</a>
  * <a href="#special-chars">Special characters</a>
  * <a href="#margins">Margins</a>
  * <a href="#tabs-spaces">Tabs and Spaces</a>
  * <a href="#blank-lines">Blank lines</a>
  * <a href="#help">Getting Help</a>


<h2 id="system-requirements">System Requirements</h2>

<p>This template was created using Word 2000 for Windows. Yeah, it’s kind of old. But it still works! There are many different versions of Word out there, so you might encounter some differences in your specific setup compared to what we talk about here.</p>

<div data-type="note">
  <h6>Note</h6>
  <p>Our template is not fully compatible with Microsoft Word 2008 for Mac. The styling buttons work pretty well, but most of the macros aren’t supported in this particular version of Word for Mac.</p>
</div>


<h2 id="installing">Installing the Template</h2>

The template contains numerous customizations and macros (short programs written in Visual Basic for Applications, or VBA). In order for these customizations to work properly, and to be available whenever you're working on your manuscript, you'll need to store this template in a special templates folder on your computer.

<div data-type="note">
  <h6>Note</h6>
  <p>Like we mentioned before, there are a lot of versions of Word out there. You might have to adapt the following, depending on where your templates folder is.</p>
</div>

<h3 id="install-windows">Installing on a Windows Machine</h3>

On most Windows systems, the Word templates folder is:

*C:\Documents and Settings\UserName\Application Data\Microsoft\Templates*

If you can't find this folder, another way to determine where Word stores your templates is to open up a new Word document, then choose **File→Save As**, then select **Document Template** from the pulldown menu at the bottom of the dialog box. This will automatically place you in the templates folder. Just make a note of where on your computer that folder is located. 

Once you've found the templates folder on your computer, move the template file to that folder. To be sure your installation was successful, go to **File→New**, and make sure that "ORA.dot" is listed as one of the choices.

<h3 id="install-mac">Installing on a Mac</h3>

Save the template to your desktop, then double-click to open it. When you open it, the title bar should read "ORA.dot", and not "Document 1". If it doesn't say "ORA.dot", skip to the next section.

If the opened file says "ORA.dot", choose **File→Save**, and choose **Save As Template**. Save the template in your *My Templates* folder. Close the template, then exit and restart Word. The template will now be available from the Project Gallery. You can send the copy on your desktop to the Trash.

#### If the template opens as a document

If the template opens as a document, and not as a template (if it says "Document1" in the title bar, and not "ORA.dot"), close the document without saving changes. Move the ORA.dot file from your desktop to your *My Templates* folder. The template will now be available from the Project Gallery.

<h2 id="menus-toolbars">The O'Reilly Menus and Toolbars</h2>

In addition to the two custom toolbars you should see on your screen (labeled "O'Reilly SmartStyler" and "O'Reilly Toolbar"—if you don't see them, go to **View→Toolbars**, and be sure they're checked), you'll notice two new menus, labeled "ORAStyles" and "ORATools." Among these toolbars and menus, you should be able to find most of the tools you'll need.

<h2 id="setting-options">Setting a Few Important Options</h2>

There are a few Word options that you should set to help yourself work better with the template. These aren't essential, but unless you have a compelling reason to want them off, you should probably turn and leave them on.

1.	Tools→Options→View→Field Shading→Always (note this is different from the check box marked "Field Codes")
2.	Tools→Options→View→Paragraph Marks
3.	Tools→Options→View→Bookmarks

Please also make sure "All Markup" is selected in the Review tab. If that drop-down is set to "No Markup," Track Changes will be present, but hidden.

<h2 id="paragraph-character-styles">Paragraph and Character Styles</h2>

Now that you've arranged your workspace, you're ready to start writing. But first, you need to know that all of your text must have a *Style* applied to it. Every single paragraph needs to have a *Paragraph Style* applied, and if you want certain characters within a paragraph to look different than the rest of that paragraph, such as applying *Italics*, **Bold**, or `Literal`, you'll be using a *Character Style*. 

Styles are just named sets of formatting attributes, used to identify and group structurally identical elements in a document.
Once you've gotten familiar with the keyboard shortcuts and the SmartStyler, you'll find you won't need to spend much time searching for which style to use. But for now, know that you can find all the Paragraph and Character (also known as *Inline*) styles either from the menu labeled "ORAStyles," or on the O'Reilly Toolbar. They are grouped by category. There are a lot of them, for sure, but that's because we need a lot of them. Again, once you've adjusted to the SmartStyler and hopefully picked up a few keyboard shortcuts, you'll find you won't need to spend much time in these menus searching for styles.

There are two buttons on the SmartStyler that you may not recognize. The button marked "C" stands for `Code`, or `Literal`. This is for text that represents computer code or output. The "P" button stands for "Plain", and removes any character formatting from the selected text. We encourage you to experiment with the SmartStyler to become familiar with its results.

<h3 id="hyperlnks-filenames-techterms">Hyperlinks, Filenames, and Technical Terms</h3>

Word kindly formats hyperlinks for you as you type. If you want to denote a hyperlink that Word doesn't recognize, you should use the "Hyperlink" style.

For richer hyperlinks, in which the text being linked isn't a URL, again use the "Hyperlink" style. Then associate the link with the appropriate URL by highlighting the Hyperlink-styled text, selecting the command **Insert→Hyperlink**, and entering the URL in the Insert Hyperlink dialog. Here's an example of such a hyperlink to [O'Reilly's website](http://www.oreilly.com). To see the associated URL after it's inserted, mouse over the hyperlink text, and the URL will appear in a yellow tooltip.

For filenames and directory paths, use the "Filename" style. For technical terms that you may want to emphasize when first introduced, use the "Technical Italic" style, which is also available from the keyboard shortcut "Ctrl+Shift+I." The only difference between "Technical Italic" and the "emphasis" style is that terms styled with "Technical Italic" don't appear in Word's spell check if you use the SmartStyler.

<h3 id="styles-follow-styles">Styles that Follow Other Styles</h3>

As an added convenience, many of the Paragraph styles in the template have been set up so that pressing `Enter` at the end of the paragraph automatically makes the *next* paragraph the style that is most likely to follow it. Press `Enter` after a heading, and you're in *Body Text* style. Press `Enter` at the end of a *Sidebar Title*, and you're automatically placed in the *Sidebar Body* text style.

Of course, sometimes you'll want to use a style other than the default "next" style, but most of the time you'll find it a convenient timesaver.

<h2 id="lists-notes">Lists and Notes</h2>

You'll soon find the need to convey information using a list, or perhaps include a Note or a Warning to accompany a topic. Though there are several types of lists (there are more than two dozen paragraph styles for lists alone), the SmartStyler will take care of remembering which style to use, even for lists within Notes.

There are four types of lists you can use in your document:

* **Simple List:** This is a list of several short items, usually one or a few words each.
* **Bulleted List:** A list. With Bullets.
* **Numbered List:** Numbers instead of Bullets.
* **Variable List:** Usually made of a pair of items, a *term* and a *definition*.
 
Except for the "Simple List", all of the list types are available via buttons on the SmartStyler. You may nest lists, but only lists that aren't within another formatting element, such as Note or Sidebar. To create a nested list, use the "Increase Indent" button on the SmartStyler.

If you need to "continue" a list item, maybe if a bullet point needs more than one paragraph and you don't want a new bullet yet, you should press `Enter` at the end of the first paragraph in your list item, then press the "List Continue" button on the SmartStyler.

There are two types of Notes: *Notes* and *NoteWarnings*. There is a paragraph style for each. You can use the SmartStyler to create a list within a Note, or to insert a code snippet within a Note. If you're typing a paragraph in a Note or a Warning, then press `Enter`, pressing any of the List buttons on the SmartStyler will apply the correct list style.

<h2 id="tables-figures">Tables and Figures</h2>

Headings and body text are fine for introductory information, but once you get into the meat of your subject, you'll probably be using some tables and figures. These can seem complicated at first, but the template will take care of most of the hard work for you. Here's a quick introduction to putting these important elements into your document.

<h3 id="tables">Tables</h3>

There are two main types of tables: *Captioned* and *Uncaptioned*. If your table requires a description, or if you expect to refer to it later elsewhere in the text, you probably want a Captioned table.

A Caption is different from a Heading row. A caption describes the entire table, while a heading row usually contains information about each column. Your Captioned tables might not have heading rows, and your Uncaptioned tables could still have heading rows. Don't worry, once you've seen a couple, it'll become much clearer.

To insert a table, click **Insert Table** on the O'Reilly toolbar. From there, choose whether or not you want a Caption, then whether or not you want a Heading row. The **Insert Table** dialog will come up on your screen. Fill in the number of rows and columns, and click "OK". If you've chosen a Captioned table, an auto-numbered caption will be inserted above the table, and filled in with dummy placeholder text, which you can then replace.

If you later decide you don't want a caption, simply delete it. If you decide another table needs a caption, just put a blank paragraph above it, put your cursor in it, then on the O'Reilly Toolbar click **Insert Caption→Table Caption**. In either case, the numbering will be adjusted automatically.

<div data-type="note">
  <h6>Note</h6>
  <p>Some of these commands are also available in other menus, such as the Table menu and the ORATools menu.</p>
</div>

<h3 id="figures">Figures</h3>

Your figures will probably have captions, and most often, you'll be putting the caption in at the same time you put in the figure. 

To put a figure in your text, put your cursor in a blank paragraph, and on the O'Reilly Toolbar, click "Insert Figure with Caption". The "Insert Picture" dialog will come up; find the appropriate image, and click "Insert". Your Figure captions will include the auto-numbered prefix.

<h3 id="moving-stuff">Moving and Deleting Tables and Figures</h3>

When you insert a new Figure or Table, the numbering for all the other Figures and Tables updates automatically. But if you delete a Figure or Table, or just move one around, the numbering won't update until the next time you save the document, or the next time you insert a caption or cross reference. You can choose to update the numbering manually, by clicking "Insert Caption" on the O'Reilly Toolbar, and choosing "Update Caption Numbering."

<h2 id="code-examples">Code Examples</h2>

In addition to Tables and Figures, most O'Reilly books rely heavily on Code Examples to illustrate topics and provide examples and exercises. Sometimes your code will just be in two- or three-line snippets, but much of the time your examples will be larger blocks of code that you'll want to label and provide a caption for.

The captions for code examples go above the code itself, so to create a new code example, you'll probably first want to create the caption. Put your cursor in a blank paragraph, then on the O'Reilly Toolbar, go to **Insert Caption→Example Caption**.

<div data-type="note">
  <h6>Note</h6>
  <p>If you have text selected when you insert any type of caption, the selected text becomes the text of the caption, and the dummy text is not inserted.</p>
</div>

When you've finished the caption, pressing `Enter` puts you into the proper "Code" style. When formatting Code examples, you should use the SmartStyler. For example, if you want one of the lines in your example to stand out in bold, just highlight the entire line, and press the "Bold" button. Also, the "Increase Indent" and "Decrease Indent" buttons will add or subtract leading spaces to selected Code paragraphs, in a default increment of 4 spaces.

<div data-type="note">
  <h6>Note</h6>
  <p>Since many of you write your code examples in a text editor or IDE, you'll probably want to cut and paste at least some code in from another application. If you do, you can use the menu option labeled "Paste As Code" under <strong>ORATools→Insert</strong>. This will ensure the text is stripped of any residual formatting from the other application (such as keyword coloring), and that any tabs are converted to the appropriate number of spaces.</p>
</div>

<h3 id="code-length">Code Length and Spacing Guidelines</h3>

Maximum line length for code varies slightly between book formats. For standard Animal books, the maximum line length for code is 80 characters, with 84 characters available in captioned examples. In small Animal books (6x9), standard line length for code is 63 characters, with 67 characters available in captioned examples. Pocket references have even smaller code line length—check with your editor for this information. 

Please make sure your code lines do not exceed these restrictions so that code lines don't run into the right margin when files are converted from Microsoft Word and prepared for typesetting. Indent using spaces, not tabs.

<h3 id="syntax-highlighting">Code Syntax Highlighting</h3>

O'Reilly's ebook toolchain now supports syntax highlighting via Pygments. For each block of code that you want to have syntax highlighted, indicate the programming language in brackets, styled as a "Comment" that immediately precedes the block of code. For example, you'd indicate that the following code is in Java like so:

[java]

~~~
int radius = 40;
float x = 110;
float speed = 0.5;
int direction = 1;
~~~

As a result, that block of code will ultimately render in the ebook as shown in the image below.

![syntax highlighting example](http://oreillymedia.github.io/production-resources/word/syntax-highlighting-example.png)

Pygments supports a wide variety of languages; please see the [full list here](http://pygments.org/docs/lexers/). Ebook reading systems that do not have color screens will still display the highlighting, but in more subtle shades of gray.

If you would like to do something in a language that's not supported, please write to us at [toolsreq@oreilly.com](mailto:toolsreq@oreilly.com) and we'll try to work with you on incorporating it.

<h3 id="code-annotation">Code Annotations</h3>

Authors who are interested in annotating code blocks or examples have a few different options to consider.

#### Line annotation

Line annotations are short descriptions that are inserted inline within the code. They are distinguished from the code by their font formatting. Annotations are set in standard body font (not `monospace`) in *italics* and a slightly smaller point size. If you'd like to insert line annotations, please use the character style "XRefColor", and insert a note at the first occurrence so that the O'Reilly Tools team will convert it correctly:

Production: Using XRefColor to indicate line annotations. 

#### Callouts

See [Bob Stayton's definition of callouts](http://www.sagehill.net/docbookxsl/AnnotateListing.html#Callouts) along with an example. Callouts are a useful and powerful way of annotating your code because they have the advantage of acting as clickable cross-references in online and mobile formats of your book. In the PDF of your book, the callouts will be clickable in the same way that is demonstrated in Stayton's example. Note that you can click back and forth between the callout and its description in the callout list, which is handy when the code and the callout list straddle pages. 

Creating callouts in the O'Reilly Word template is a bit of a hack, but certainly doable. The following example shows you how. Include a note to production at the first occurrence to ensure that the callouts are processed correctly.

Production: Using !!CO1!!, !!CO2!!, etc. to indicate callouts throughout. Match the callouts with the list that follows.

~~~
Code example 12345 example code  !!CO1!!
   more code
      yet more code 12345 !!CO2!!
~~~

1.	Description of first callout.
2.	Description of second callout.

Note that the code block is followed immediately by a numbered list, which will act as the callout list once the book is typeset for print.

#### Numbered code

Numbered code is built into the O'Reilly Word template and can be inserted using the "CodeNum" style:

~~~
1	Example of CodeNum style
2	This is a dangerous format to use
~~~

We strongly discourage authors from using numbered code lines for two main reasons:

* The line numbers end up hardcoded in typeset and/or downstream versions, making them difficult to maintain, correct, and update. Any references in the body text to the line numbers will also be hardcoded in, and if the code changes, the in-text references will also have to be changed. This maintenance may not sound like a big deal when you are authoring your book, but keep in mind that code may also need to be revised when fixing errata for reprints, and when writing future editions of the book. Numbered code makes the revision process that much more error-prone and cumbersome.
* 
* When your readers copy and paste code lines from the digital editions of your book, each line will start with extraneous text (i.e., the line number plus any punctuation and whitespace), thus rendering it unrunnable as code. Most readers will probably access your book through Safari Books Online, PDF, and other digital formats. By adding hardcoded line numbers to your code, you're potentially making it more difficult for readers to actually use it.

<h2 id="xrefs">Cross References</h2>

Now that you have a document with a few sections of text, and probably some Figures, Tables, and Examples, you'll likely find the need to refer to these elsewhere in the text.

<div data-type="warning">
  <h6>Disclaimer</h6>
  <p>This template's Cross Reference Engine, specifically with regards to cross references to external files, does some rather unnatural things that Word wasn't really meant to do, or at least do reliably or accurately. We've had our way with Word, and sometimes Word won't stand for it. Most errors are benign, and a simple close-reopen will resolve them, but occasionally bad things happen to good documents. If you're trying to use the cross references, and you're having trouble, please don't hesitate to contact the O'Reilly Tools group.</p>
</div>

In general, you can create a cross reference to any paragraph in your document, as well as to any paragraph in any other open file that is based on this template and is in the same folder as your document. In most cases, the entire text of the paragraph is inserted, and if it's in a different file, the chapter number is also inserted. In the case of captions, only the caption type and number are included.

To create a cross reference, go to the O'Reilly Toolbar, and click on **Cross References→Insert XRef**.

By default, the dialog lists every paragraph style in your document. To only view the most frequently used ones, click the button marked **Show only common styles**.

Once you choose a paragraph style, the dialog lists every paragraph that has that style applied. Choose the one you want to reference, and press "Insert". Your new cross reference should appear in quotations marks, and with a grey background (to indicate a Field Code). If the reference is to a paragraph in the same document, the reference will also function as a hyperlink. Any changes you make to the source paragraph will be reflected in the cross reference as well.

<div data-type="warning">
  <h6>Warning</h6>
  <p>If you need to modify the content of a paragraph that has been cross referenced, be very careful to retain the "Bookmarks" that have been inserted around that paragraph (they appear as large, black brackets). If you just start typing at the end of the paragraph, the bookmarks do not expand; instead, fill in the new text in the middle, then delete spurious text at the end, taking care not to delete the bookmark itself. We know it stinks, but there's not much we can do about it, it's a documented “feature” in Word.</p>
</div>

Since cross references tend to be a bit fragile, we suggest waiting until your content is reasonably stable before inserting them, particularly references to headings. You can feel free to create references to captions as soon as you've inserted the caption, but hold off on referencing a heading until you're fairly sure it won't move much.

<h2 id="misc">Miscellany</h2>

A few final items to feed the impatient mind.

<h3 id="keyboard-shortcuts">Keyboard Shortcuts</h3>

Most of the commonly used styles, and most of the SmartStyler commands, have keyboard shortcuts associated with them. To get a list of all the keyboard shortcuts, choose **ORATools→Reports→List Keyboard Shortcuts**.

<div data-type="note">
  <h6>Note</h6>
  <p>Any keyboard shortcut that starts with <code>Alt</code> can also be invoked with <code>Ctrl-Alt</code>. Some Mac users may find that certain commands that start with <code>Alt</code> (such as <code>Alt-N</code>, <code>O</code> to apply the <em>Note</em> style) don't work. In that case, use <code>Ctrl</code> as well, as in <code>Ctrl-Alt-N</code>, <code>O</code>).</p>
</div>

<h3 id="special-chars">Special characters</h3>

You've probably noticed the use of the "→" character in this text. That's the character you'll use to signify a menu hierarchy. You can find it on the O'Reilly Toolbar, under the ORATools menu, and often by right-clicking within text (it depends on the type of text you're in). The same goes for the em-dash "—", which is neither a dash nor a hyphen, and shouldn't have any spaces around it.

<h3 id="margins">Margins</h3>
This template is set to *roughly approximate* the size of a standard O'Reilly book. Please use the page count only as a *rough estimate*. In the event you're working on a Pocket Reference, to make your estimate a little less rough, go to File→Properties→Custom, change the value of the *BookSeries* property to "Pocket", and then go to ORATools→Configure→Reconfigure according to series.

<h3 id="tabs-spaces">Tabs and Spaces</h3>

Please don't use tabs, except when navigating in a table. And single spaces after periods, please. If you absolutely *must* use tabs in your code examples, please change them to spaces before submitting your manuscript for production. You can change them globally from ORATools→Repair→Replace Code Tabs with Spaces.

<h3 id="blank-lines">Blank lines</h3>

Except in Code Examples, there should be no blank or empty paragraphs in your document.

<h3 id="help">Getting Help</h3>

If you're having any trouble with the template, or just have a question, and you're unable to find the answer in the documentation, please send an email to [toolsreq@oreilly.com](mailto:toolsreq@oreilly.com). Congratulations again, and good luck!















