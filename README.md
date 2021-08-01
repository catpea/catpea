- 👋 Hi, I’m @catpea
- 👀 I’m interested in teaching, programming, and writing.
- 🌱 I’m currently learning Music Theory.
- 💞️ I’m looking to collaborate on building real schools that actually educate and enable graduates. A new generation of real schools to replace the memorization charade than currently puts students in fraudulent and predatory debt.
- 📫 https://catpea.com

Take a look at my [source repositories](https://github.com/catpea?tab=repositories&q=&type=source&language=&sort=) and [npm packages](https://www.npmjs.com/~catpea)

## Programming Tips And Tricks
1. Intermediate Data Structures: If you are working with nested or recursive "things", don't execute things instantly. Instead create a huge tree of things that are yet to be executed. This way, you will be able to see what is about to happen. If you just go for the gold without creating an intermediate data structure, you will never see the tree that you are supposed to be working on, and that is just not fair for when you need to debug something. TLDR; the last thing you should be thinking about in a recursive tree, is collapsing nodes, make the tree beautiful and readable first, export it to Cytoscape or Graphviz, give it a name, take it out for a movie, and stare at it for days prior to function execution.
2. If you are going to deal with trees, borrow as much as you can from the Document Object Model (web/HTML) don't try to reinvent the wheel. The Document Object Model is perfect for working with trees.
3. Don't use walk functions, simply use ```this.children.map(node=>node.value()``` in your ```value()``` method, a simple .map will give you full recursion inside out.
4. If your program can run on the command line even if you have to invent something newe like ffmpeg graph notation, don't start by creating a GUI application. Make a command line program first and then consider makeing a GUI for it.

## Digital Audio Player Research (Hardware)

- [peapod]: Deployment repository for the Cat Pea music player. 

### Audio Player Toolkit
- [isir]: Remote control raspberry pi via a bluetooth keyboard or a remote shutter device. 
- [rsend]: Upload local files to remote host via scp and ssh. 
- [sha256sum]: Compute and check SHA256 message digest. 
- [older]: Simple function to check if a file is older, useful for cache related operations. 

### Hardware Research
- [awesome-raspberry-pi]: Awesome Raspberry Pi

## Audio Book Research (Education)

### Publishing Corpus
- [furkies-purrkies]: Furkies Purkies Narrated Content

## Video Book Research (Education)

### Publishing Corpus
- [westland-warrior]: Westland Warrior Video Content

## Text User Interface (TUI) Research (Computation)

### Command Execution
1. [munchhausen]: Automatically wrap operating system commands with duplex streams. (1st Reference Implementation)
2. [bashscript]: A small shell and a very lightweight JavaScript library meant to convert Operating System commands to functions. (2nd Reference Implementation)

### Shell Development
1. [tush]: Tush Shell (1st Reference Implementation)
2. [oosh]: Object Oriented Shell (2nd Reference Implementation)

### Command Line Program Structure Research
- [endir]: Command line utility to virtually place all HTML files in a sub directory by prefixing all the absolute paths specified in a, link, img, and script with a user specified prefix.

## Content Management Research
- [db]: is the main content repository
- [templates]: new record templates
- [themes]: website themes
- bin: utilities

### Sample Content
- [website]: Cat Pea Website
- [warrior]: Westland Warrior Master Repository
- [news]: A tiny twitter for catpea!

### Corpus Processing Implementations
1. [bowel]: Eager Processing Framework (1st Reference Implementation)
2. [eternia]: Synchronous Processing Framework (2nd Reference Implementation)
3. [peacekeeper]: Asynchronous Processing Framework (3rd Reference Implementation)

## Structured Content and Static Text Database Research
- [research]: Markdown source for software development research.
- [fitness]: Markdown source for fitness advice.
- [essays]: Notes about philosophical ideas and concepts.
- [portfolio]: My Portfolio (private)
- [resume]: My Resume (private)







[website]: https://github.com/catpea/website
[news]: https://github.com/catpea/news
[song]: https://github.com/catpea/song
[homepage]: https://github.com/catpea/homepage
[warrior]: https://github.com/catpea/warrior
[poetry]: https://github.com/catpea/poetry
[research]: https://github.com/catpea/research
[fitness]: https://github.com/catpea/fitness
[essays]: https://github.com/catpea/essays
[portfolio]: https://github.com/catpea/portfolio
[resume]: https://github.com/catpea/resume
[server]: https://github.com/catpea/server
[cataclysm]: https://github.com/catpea/cataclysm
[catawampus]: https://github.com/catpea/catawampus
[catkin]: https://github.com/catpea/catkin
[bowel]: https://github.com/catpea/bowel
[baloney]: https://github.com/catpea/baloney
[trop]: https://github.com/catpea/trop
[cosmopolis]: https://github.com/catpea/cosmopolis
[elderflower]: https://github.com/catpea/elderflower
[peacss]: https://github.com/catpea/peacss
[peacekeeper]: https://github.com/catpea/peacekeeper
[peacoat]: https://github.com/catpea/peacoat

[db]: https://github.com/catpea/db
[bin]: https://github.com/catpea/bin
[templates]: https://github.com/catpea/templates
[furkies-purrkies]: https://github.com/catpea/furkies-purrkies
[westland-warrior]: https://github.com/catpea/westland-warrior

[eternia]: https://github.com/catpea/eternia

[bashscript]: https://github.com/catpea/bashscript
[munchhausen]: https://github.com/catpea/munchhausen
[tush]: https://github.com/catpea/tush
[oosh]: https://github.com/catpea/oosh

[endir]: https://github.com/catpea/endir
[themes]: https://github.com/catpea/themes


[peapod]: https://github.com/catpea/peapod
[isir]: https://github.com/catpea/isir
[rsend]: https://github.com/catpea/rsend
[sha256sum]: https://github.com/catpea/sha256sum
[older]: https://github.com/catpea/older
[awesome-raspberry-pi]: https://github.com/catpea/awesome-raspberry-pi
