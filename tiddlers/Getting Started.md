Welcome to KodWiki; A hybrid tiddlywiki spin that mixes knowledge management with productivity:
* It features [](#Contextual%20Backlinking)
* It also has [](#A%20Writing%20Inbox) for developing ideas with spaced repition
* It also has some custom [auto completion](#Auto%20Complete) fuctionality
* This will probably be controversial but it has CodeMirror Vim Bindings; you may disable these if you wish by selecting a different option in this dropdown {{$:/core/ui/ControlPanel/Settings/codemirror/keyMap}}
* It has Markdown support by default instead of wikitext [](#Tiddlers%20In%20Markdown)
* It uses Muuri storyview to allow you to rearrange tiddlers in the story river, try dragging around some tiddlers!
* It features a kanban board to manage ongoing projects.[](#Kanban%20Boards)


If you want a blank version of this wiki you can delete all the example tiddlers with 
<$button>
<$list filter="[tag[Example]]">
<$action-sendmessage $message="tm-delete-tiddler" param=<<currentTiddler>>/>
</$list>
DELETE EXAMPLE TIDDLERS
</$button>
Warning; a lot of popups