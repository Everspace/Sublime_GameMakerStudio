Sublime_GameMakerStudio
=======================

Game Maker Studio auto-complete and syntax highlighting for SublimeText.

## Cool things

* Autocompletion for **everything**
* Syntax highlighting of GML
* `@` Goto Anything support for tabbed scripts made through `#define`s
* Snippets

## Structure

The `.sublime-completions` are organized in a manner roughly corresponding to the [Game Maker Documentation Reference](http://docs.yoyogames.com/source/dadiospice/002_reference/index.html).

#### Definitely Todo

- [ ] More snippets
  - [ ] All flow control
  - [ ] Some common stuff like move via: arrow keys?
- [ ] .GMX styling (will probably have reorganize)
  - [ ] Possibly pull out magic constants from completions.

#### Maybe Todo

- [ ] Build with asset compiler.

- [ ] Automate Changes
  - [ ] Generate syntax highlighting crazy regex.
  - [ ] Diffing?
    - [ ] At least what things have appeared/dissappeared 

#### Modules to finish

All functions known to GM:S are *autocompleteable*. When a section in the documentation has been sorted through and has the relevant argument info, the box gets to get checked!

##### Core
- [ ] Keywords
- [ ] Builtin
  - [ ] Globals
  - [ ] Instance Locals

##### ~~Real Numbers And Strings (primitives)~~
- [x] ~~Maths~~
  - [x] ~~Real Number Functions~~
  - [x] ~~Vector Functions~~
- [x] ~~Date and Time~~
- [x] ~~Strings~~

##### Game Play
- [ ] Game Assets
  - [ ] Sprites
  - [ ] Backgrounds
  - [ ] Sounds
  - [ ] Fonts
  - [ ] Paths
  - [ ] Timelines
  - [ ] Rooms
- [ ] Objects and Instances
  - [ ] Objects
  - [ ] Instances
- [ ] Movement and Collisions
  - [x] ~~Movement~~
  - [ ] Motion Planning
  - [x] ~~Collisions~~
- [ ] Mouse, Keyboard and Other Controls
  - [ ] Virtual Keys
  - [x] ~~Keyboard Input~~
  - [ ] Mouse Input
  - [ ] Device Input
  - [x] ~~GamePad Input~~
  - [ ] Immersion Haptics

##### Drawing And Display
- [ ] Drawing
  - [ ] colour And Blending
  - [x] ~~Drawing Basic Forms (shapes)~~
  - [x] ~~Drawing Sprites~~
  - [x] ~~Drawing Backgrounds~~
  - [x] ~~Drawing Text~~
  - [ ] Drawing Primitives
  - [ ] Drawing 3D
  - [ ] Drawing Surfaces
  - [ ] Common
- [ ] Surfaces
- [ ] The Display, Windows And Views
  - [ ] The Game Window
  - [ ] Views
- [ ] Shaders
  - [ ] Vertex Formats
  - [ ] Primitive Building
  - [ ] Shader Constants

##### Advanced Functions
- [x] ~~Data Structures~~
  - [x] ~~Stacks~~
  - [x] ~~Queues~~
  - [x] ~~Lists~~
  - [x] ~~Maps~~
  - [x] ~~Priority Queues~~
  - [x] ~~Grids~~
- [ ] Particles
  - [ ] Simple Effects
  - [ ] Particle Systems
  - [ ] Particle Types
  - [ ] Particle Emitters
- [ ] Physics
  - [ ] The Physics World
  - [ ] Forces
  - [ ] Fixtures
  - [x] ~~Joints~~
  - [ ] Physics Variables
- [ ] File Handling
  - [ ] File System Limits

- [ ] Operating System
- [ ] Buffers
- [ ] Networking

##### Platform Specific
- [ ] HTML5
- [ ] Windows8
  - [ ] Windows 8 Phone
- [ ] Advertising and Analytics
- [ ] Social Gaming
  - [ ] Facebook
  - [ ] Achievements and Leaderboards
  - [ ] Local High Scores
- [ ] In App Purchases
- [ ] Asynchronous
- [ ] Push Notifications
- [ ] Cloud Services
- [ ] Steam API

##### Extras
- [ ] Debugging
- [ ] Miscellaneous
- [ ] Obsolete Functions
- [ ] Internal?
  
