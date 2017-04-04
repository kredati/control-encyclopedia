# How to Encyclopedia.

## Navigating to the Wiki
Towards the top of this page, you'll see a bunch of tabs: Code, Issues, Pull Requests, Projecst, and then [Wiki](https://github.com/kredati/control-encyclopedia/wiki). Click on that. (Or, you know, you can click on the link here, too.)

## Adding Your Page to the Wiki
Once you're at the Wiki, towards the top right, there's a big green button: New Page. Add your page.

However, there's a caveat: if you're writing the eponymous entry for your group (e.g. Sexuality), then you need to *edit* the currently existing page. Navigate to that page using the sidebar, or from the landing page. Once you're there, click the "Edit" button next to the "New Page" button.

## Adding Your Text to the Wiki
You should copy-and-paste from your current document, but pay attention: **this will copy the text only**. GitHub uses [markdown](https://guides.github.com/features/mastering-markdown/), which is a way of using plain text to specify formatting. Cutting-and-pasting is what you should do, but much of the formatting won't carry over. This is a pain, and I'm sorry. Fortunately, the GitHub wiki editor helps you out, by giving you buttons and instructions at the top. It's pretty straightforward, but if you run into any markdown issues, see [Getting Help](#getting-help) below.

## Structuring Your Text: Headers
One thing I do ask you to do is use **headers** in your text. Presumably your entry will be separated into multiple sections. Instead of just bolding a bit of text, use markdown headers. For main headings, please use H2 headers (either click the "h2" button at the top left in the editor, or prefix the header with two hahes and a space: ```## header```. For subjeadings, use H3 headers (again, the "h3" button, or ```### header```).

### Helping Users Navigate
If you've structured your text with headers (and please do!), you can (and probably should) include a section towards the top of the entry that lets users navigate directly to all the sections of your text. See [Making Links](#making-links) and especially [Links to Specific Passages](#links-to-specific-passages), below.

## Making Links
The easiest way to make a link is to use the *exact* name of the entry you'd like to link to. Simply enclose the title in two square brackets, like so: ```[[Power]]``` would go to the page named "Power" (but not "power"). If you'd like to have your text read something different from the name of the article you'd like to link to, use a pipe (```|```) between the text and the name of the entry: ```[[Foucault's idea of power|Power]]```.

### Links to Specific Passages
If the article you're linking to has structured text with headers, the name of the header is a specific location in the text. You're not required to at all, but if you'd like to link to another section of your own text or a specific section of somebody else's, it's fairly straighforward. In your own text, simply write: ```[text of link](#section-name)```, where the ```section-name``` is the text of the header, with spaces replaced by hyphens, and all text lower-cased. If you'd like to link to somebody else's specific section, it looks like: ```[text of link](https://github.com/kredati/control-encyclopedia/wiki/Name#section)```, where ```Name``` is the name of the entry, and ```section``` is the text of the header in the same format as above. 

The shortcut to getting the URL for their section is to navigate to their entry and section. Then, hover your mouse over the header. A little gray link icon will show up to the left. Right-click on that little icon, and copy the link address (on a Mac, "Copy Link Address.") Then you can just paste the link address: ```[text of link](paste the URL here)```.

## Embedding Images
If you'd like to pull in an image from teh interwebz, that's easy, and looks similar to a link: ```![description](http://image_url)```. (You can leave the description blank.) If you have an image that you need to host and can't just link to, please contact Scott about it, to make sure we're not falling afoul of any copright laws.

## Claiming Credit for your Work
Please add a byline at the top of your work. If you want your actual name attached, use your actual name. If you don't want it attached, please just use your GitHub handle.

## Getting Help
If you need help managing the technology (and the technology really *isn't* the point here), first ask teh #tech Twine channel, then ask Scott. Please do *not* put this off to the last minute! Nobody wants to be troubleshooting tech at 11:30pm on Monday night.
