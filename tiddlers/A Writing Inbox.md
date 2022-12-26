KodWiki uses a spaced reptition based inbox as described in [Andy Matuschak's notes](https://notes.andymatuschak.org/z7iCjRziX6V6unNWL81yc2dJicpRw2Cpp9MfQ) to help you turn interesting concepts into robust tiddlers.

The {{$:/tq/WritingInbox/NewNoteButton}} in the side bar is for creating the individual temporary notes. 
Simply click it; chamge the text field to your liking. And it will be added to the inbox for review.

The {{$:/tq/WritingInbox}} beneath the search bar is the inbox; when there are notes for review; it will change to to a text box and a button. If you change the contents; the button will increase the note's interval; and it will take a longer time for you to see it. If you do modify the contents; the button will reset your interval so that you will see the note tomorrow.

In this way, you will see the notes that inspire the most thought most often, and the notes that you don't have much to say on less often.

When you are ready to add the note to your wiki; you can click the "To Tiddler" button to create a new tiddler from the text of the note; this will also delete the note.

Here's a bit more info on the format of the notes.

The title is simply the current time; and is unimportant to the functionng of the inbox; you may change it if you wish.

The tag is important and you may not remove it; but you may add extra tags if you wish without hampering the functionality of the  inbox.

The fields are as follows:
* due: The date your note will be due in the format YYYY0MM0DD
* interval: the number of days that you will wait to see the note again if you did not modify it
* prev_sha: hash of the text, used to detect modifcation of the inbox

You may add extra fields but you may not remove existing fields.