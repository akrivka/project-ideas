# Notemap
This app is supposed to utilize the advantages of computers in note-taking, serving probably mainly high school or university students. It is supposed to be **visual**, **non-linear**, **easy-to-use** and **customizable**. At the beginning, it should be very general-purpose and we will see what the users make out of it. Later on, we can limit the app in some ways to be widely deployed, if successful. 

## Basic principle
There will be a basic object called **note** or **node** with these default parameters (user can add more though):
- Name: a suitable short name (e.g. Organic chemistry)
- Etymological meaning of name: knowing the etymological of each term greatly helps with remembering them
- Children: list of children nodes
- Content: actual content of the note in Markdown (supposed to be short, whenever there would be a list, it's better to branch out into more nodes)

Optional parameters could be:
- Name in a different language:
- Color:
- Type: Concept / Fact / Junction / ...
- whatever the user defines...

The app would provide a fast way of editing these notes, adding new nodes and making a system, a map representing the knowledge, how it is saved in your brain (using connections and associations).

## Core features
- The app should only glue notes together and the text itself could be edited in your standard text editor (Word, notepad, Atom, vim, typewriter, ...), while providing a default one as well.
- Beautiful graphical engine that would render the notes in a **notemap** resembling neurons in your brain.
- A quick scratchpad that would allow to quickly write down anything you hear at a lecture or think about, to be processed later and incorporated to your notemap.

## Neat features
- Very easy way of including pictures, drawings and diagrams (possibly draw something on paper, with your phone take a photo of it, that would get instantly inserted into the note). This increases the emphasis on the app being visual.
- Synchronize to cloud, Google Drive or Dropbox.

## Low priority features
- Ability to share notes -- this service is supposed to be solely for yourself, for your expansion of knowledge, therefore sharing notes is not very valuable, although may be desired by some people

## Formal description of the map
- By default, it would be a general graph with different types of connections (implication, equivalence, generalisation, ...)
- However, the desired structure of the graph would be something resembling a tree, going from the most general topics to more concrete ones. 
- There could also be tags, describing for example the subject a note is connected to (e.g. chemistry)
 
## Roadmap
1. Define a data structure for notes.
2. Decide on a library to be used for the graphical engine and app development 
	- React Native / React - svg libraries
	- Flutter
	- ...
	- need to verify whether I can use the same graphical in both frameworks (otherwise development of the mobile and desktop client should be separate)
3. ...
