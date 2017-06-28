# Napp
## A cross-platform note taking app


**Napp** is an app to take notes with Markdown format, that allows to add classify each note (either by tags, categories or notebooks), provides real-time inline Markdown support, and a easy-to-use interface to support different export format and services. It also includes support for customizing the theme.


# Motivation
As I was writing a post about chatbots, I thought it would be really cool that my note app could publish directly to Medium. Sadly, the app was proprietary, so there was no way I could contribute with an extension to the code. It's also a way to contribute to the Open Source community as I learn front-end related stuff to extend my skillset.


## Inspiration
The apps that I'm taking inspiration from are:


### [Bear](http://bear-writer.com)
asdf
![Image](http://www.bear-writer.com/static/images/header-mac-screenshot@2x.png)
### [MedleyText](https://medleytext.net)
Make programming notes that matter. Get MedleyText and take coding notes with style. 
![Image](https://medleytext.net/images/feature-1.png)
### [Abricotine](http://abricotine.brrd.fr)
Markdown editor with inline preview. (The best Open Source option I reviewed)
![Image](http://abricotine.brrd.fr/img/window-preview.png)
## Real-time inline markdown
The RTIM provides formatting for text written in Markdown notation as is being written, and displayed withtin the same text area (as seen in Abricotine). In my opinion, that is some of the best UX I **personally** have seen, it makes it feel more natural.


-------------
# Minimum Viable Product (MVP)
This is a list of the features required for the editor to be the MVP (regardless of the implementation):
- [ ] RTIM Support
- [ ] Key shortcuts to add the stylings (bold, italics, code blocks, etc…)
- [ ] Sidebar with list of notes
- [ ] Export/Save notes to `.md` files
- [ ] Integration with Medium


## Technology stack proposal
### React + Electron
The idea is to develop a Web App that can be used both in-browser, as well as natively supported by Electron.


The reason to use Electron is that it provides cross-platform support out of the box. There's no need to install external UI tools (I'm looking at you, GTK). Even though Electron has a bad reputation because of the performance issues, we're gonna look for a way to optimize the performance.


