---
{"dg-publish":true,"permalink":"/bear-hunt/basic-obsidian-tutorial/","updated":"2025-11-19T15:13:39.240+00:00"}
---

[Obsidian](https://obsidian.md/) is a note-taking app which is somewhat similar to Notion and OneNote, but with many more features. While I never used Notion for a long time, I find Obsidian easier to navigate and with more personalisation.

I do various things with Obsidian — note-taking, essay planning, mind-mapping, planning my day, keeping track of what I need to do, etc. There is an insane amount of things you can do with Obsidian, and it is up to you whether or not you do those things. 

Anyway, let's start with the **very** basics.

You can make a note using the bar on the top left, or use Ctrl+N (or Command/Cmnd, for Macs. If I say Ctrl from now on, assume I also mean Command.)

Most importantly, you can link notes together by using double square brackets - [[]] - like that but with text in the middle.) You can both link to existing notes by typing in a note's title (which automatically searches your vault to show you which notes you could be asking to link to) or create a note by typing in a title and clicking the link.
- ==You know the Wikipedia system? Where there are hyperlinks here there and everywhere linking between articles? **This is that**. Cool, right?==


> [!warning] Types of links
> There are two kinds of links to a note: forwards and backwards. **Forwards** is a link that is in the current note going **outwards** to another note, and **backwards** links are links going **into** the current note from another note. They are, unfortunately, categorised separately when searching your vault using properties. You can see the forwards and backwards links in two of the tabs on the top right hand side — they should look like linked chains with an arrow.

Finally, you need to know the command **Ctrl+P**. This opens the command menu, which is where you can do  anything — creating new notes, bases, canvases, opening certain views, plus any commands from any plugins, etcetera. 

## Typing in notes

You can type in these notes as usual, although there are a few shortcuts that are used in markdown format (the format that these notes are in) to use the base program. 
- You can, of course, use the [Editing Toolbar](https://github.com/PKM-er/obsidian-editing-toolbar) plugin to have a word-esque toolbar to use. I personally find the hotkeys easier, though.

The basic hotkeys are as follows:
1. Ctrl+B / two asterisks on both sides of any text-> **Bold text**
2. Ctrl+I / one asterisk on both sides of any text -> *Italic text*
3. Two equals {=} on both sides of any text -> ==highlighter==
4. using a dash {-} and then space to start a list
	- like this
5. using a number, then period, then space to start an automatic numbered list (see the current example)
6. using {>} to indent text slightly
> Like this
7. using Tab to indent both text and lists
	1. like this
8. Using hashtags plus a space before text to indicate a Header — one hashtag for most important, down to 6 hashtags for least

You can also do all of this by right-clicking and using the menu that appears.

Also in the menu is the table function — i.e. just a normal table, the rule function-

---
-which looks like the line above, and the callout function, which can create cool blocks- 

> [!tip] Cool block
> Like this!

That's about it for inbuilt text features. There are a few plugins that I would recommend, but we'll get onto that in the Plugins section.


> [!info] 
> Note that Obsidian doesn't have an automatic spell-checker. This goes for capital letters at the start of sentences, too! It is, however, very very easy to get a spellchecker — which I will be talking about in the Plugins section.

## Other inbuilt features of Obsidian

### Graph view
Graph view is where linking notes comes into play! It's a fun way of looking at the links between your notes and finding notes.

Here's a screenshot of my current graph view:
![Pasted image 20251119143756.png](/img/user/Images/Pasted%20image%2020251119143756.png)
Every single dot is a note. Every single line is a link. 

There are a few other things you can do with graph view — messing around with the forces, colouring the dots based on properties that the note has — but the know-how gets explained later, so I'll leave it for now.

And by later, I mean now!

### Tags and properties

This is your second way of sorting notes, other than links (and the file repository on the left, but do I really need to explain how to use that?). It's incredibly useful and not complicated at all.

Essentially, each note has a list of properties. You can add to these and change these as you like. These properties include (but are not limited to):
- the file name
- the folder that it is in
- file links (forwards and backwards are separate, remember?)
- created time
- modified time
- file path (how does it link to your 'home note' — i.e. the origin note)
- and tags!

You can change these using the properties view — which is an inbuilt plugin (you only have to turn it on from settings) or for changing tags, you can just type in the tag. It's like, so #cool <-(literally like that.)
> You can also use properties view to change tags. You can find properties view in the 'core plugins' section of settings and then you can find the menu under the info button in the top-right bar.

You can search your notes by using these tags or group notes together by using these tags from graph view, if you just don't want to use links.
> I use it to categorise my notes into major lessons, minor lessons, resources, essay plans, and various other things. It makes it easier to find a specific note if I am looking for it.

This leads well into-

#### Categorizing and searching notes

This is done using the inbuilt plugin 'Bases' — which you can find and activate in the same way as you found Properties View. It should already be enabled, but who knows. 

This is one of my bases:
![Pasted image 20251119145447.png](/img/user/Images/Pasted%20image%2020251119145447.png)

As you can see, bases contain all of your notes and are very searchable and customisable. Everything except the 'file name' property is something I put in through the 'properties' menu which you can see on the top right of the image.

You can search your notes in various ways. You can query by including, excluding, containing, does not contain, and apply these to the file properties. Here, I searched by the 'debates' tag — but if I wanted to only have Politics notes, I can use the 'does not contain' query looking into the 'folder' property and write 'philosophy' to exclude all philosophy notes.

> Although, note that other than searching for categories of notes, it's most useful for editing the properties of categories of notes. You see those tick-boxes under 'dg-publish'? Those are what decides if certain notes go onto my site or not. And I can do it in a single click! No searching through each and every note's properties view! 
>> Yes, I will give a basic explanation of how to publish notes online for free.


> [!important] On graph view
> You remember graph view? Using properties is how I colour the nodes in graph view — you can colour them in the graph view menu using properties and then assigning a colour to nodes with a certain property.

Finally,

### Canvas

Canvas is the final core plugin which needs an explanation. It's essentially just a mindmap.

Here's one I made earlier-
![Pasted image 20251119150832.png](/img/user/Images/Pasted%20image%2020251119150832.png)
It's zoomed out, so you can't see the text, but you see what it is, right? It's quite useful — especially in understanding lines of argument and forcing you to make links between ideas. It's good for redo-ing messy notes from a lesson — it helps in understanding and remembering the content by making you interact with your notes properly.

You won't see it in this website though, because it's an incompatible format, and these were made before I started working on this website. Nowadays, I use (and you will see) the [Excalidraw plugin](https://github.com/zsviczian/obsidian-excalidraw-plugin) which is similar in it's features, but looks quite different — and it's in a compatible format for posting. 


*To be continued...*