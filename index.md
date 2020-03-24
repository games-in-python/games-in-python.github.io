Python Gaming Rocks!
====================

People might not realize it, but Python is really good for making games!

Why Use Python?
---------------

Python allows extremely fast game creation compared to many traditional engines. It is particularly good at:

* **Prototyping**: If you just need to experiment or get an idea out, Python will let you do it faster
* **Education**: Python is an excellent language for teaching, and many people started programming by making games
* **Indie**: If you're not a big AAA studio trying to get the best effects and the most FPS out of your game, going Python will make your development easier

Ok, So What's Available?
------------------------

Lots of things! 2D, 3D, and everything in between.

Hardware Layers
---------------

These libraries are less "make a game now" and more "the abstraction you need to make a game engine". These can still be useful, but be prepared to put in a bit more work inventing your universe.

### PyGame

[Website](https://www.pygame.org/) — [PyPI](https://pypi.org/project/pygame/) — [Source](https://github.com/pygame/pygame/) — [Twitter](https://twitter.com/pygame_org)

The venerable, the classic: PyGame. For many people, when they think about making games in Python, they think PyGame. It literally wrote the book on game development in Python (several books, actually).

PyGame is a wrapper around SDL that takes off a few of the rough edges while still keeping fairly thin. It supports 2D and OpenGL, sound, handles input, and most other platform tasks.

### Pyglet

[Website](http://pyglet.org/) — [PyPI](https://pypi.org/project/pyglet/) — [Source](https://github.com/pyglet/pyglet) — [Docs](https://pyglet.readthedocs.io/) — [Discord](https://discord.gg/QXyegWe)

Pyglet is a pure-Python, cross-platform hardware layer, supporting 2D, OpenGL, spatial audio, input,

### PySDL2

[PyPI](https://pypi.org/project/PySDL2/) — [Source](https://github.com/marcusva/py-sdl2) — [Docs](https://pysdl2.readthedocs.io/)

PySDL2 is a direct ctypes-binding to SDL2—you're calling the C functions directly, with all of the rough edges and caveats.

3D Frameworks
-------------

Now the actual game engines! Unlike above, frameworks are more ready to go; you can more quickly get started and spend less time on things like drawing routines or event dispatch.

These are the 3D engines.

### Ursina Engine
[Website](https://www.ursinaengine.org/) — [Source](https://github.com/pokepetter/ursina) — [Docs](https://www.ursinaengine.org/documentation.html) — [Twitter](https://twitter.com/ursinaengine) — [Discord](https://discord.gg/ydXfhyb)

Ursina is a 3D game engine boasting fast development, easy of use, and flexible support.

### Panda3D
[Website](https://www.panda3d.org/) — [Source](https://github.com/panda3d/panda3d) — [Docs](https://www.panda3d.org/manual/) — [Discord](https://discord.gg/UyepRMm) — [Forums](https://discourse.panda3d.org/)

Panda3D is a 3D game engine advertising power and flexibility.

### Gloopy
[Source](https://github.com/tartley/gloopy)

TODO

2D Frameworks
-------------

Like their 3D counterparts, these game engines are ready to go, just rather flatter.

### PursuedPyBear

[Website](https://ppb.dev/) — [PyPI](https://pypi.org/project/ppb/) — [Source](https://github.com/ppb/pursuedpybear) — [Docs](https://ppb.readthedocs.io/en/stable/) — [Discord](https://discord.gg/s7qx493) — [Twitter](https://twitter.com/pursuedpybear)

PPB is an education-targetted sprite-based engine, focusing on ease of use, rapid start, and extensibility.

### Arcade
[Website](https://arcade.academy/) — [PyPI](https://pypi.org/project/arcade/) — [Source](https://github.com/pvcraven/arcade) — [Discord](https://discord.gg/ZjGDqMp) — [Twitter](https://twitter.com/ArcadeLibrary)

Arcade is an easy-to-learn Python library for creating 2D video games. It is ideal for beginning programmers, or programmers who want to create 2D games without learning a complex framework.

### Cocos2d
[Website](http://python.cocos2d.org/) — [PyPI](https://pypi.org/project/cocos2d/) — [Docs](https://github.com/los-cocos/cocos) — [Source](http://python.cocos2d.org/doc.html)

TODO

### PyGame Zero
[Docs](https://pygame-zero.readthedocs.io/) — [PyPI](https://pypi.org/project/pgzero/) — [Source](https://bitbucket.org/lordmauve/pgzero)

PyGame Zero handles the boilerplate of PyGame, making it easy for students to get started.

### pyglet sprites

Pyglet was already discussed, but it is worth mentioning that if you use the [`pyglet.sprite` module](https://pyglet.readthedocs.io/en/latest/modules/sprite.html), pyglet is at about the same level as the other 2D frameworks.

Specialized Engines
-------------------

Unlike everything else on this site, these engines are a lot more opinionated about the kinds of games you can make with them.

### Ren'Py
[Website](https://www.renpy.org/) — [Source](http://www.github.com/renpy/renpy) — [Docs](https://www.renpy.org/doc/html/) — [Discord](https://discord.gg/6ckxWYm)

Ren'Py is a Visual Novel engine, made specifically for that genre. It leans very heavily on its DSL to define stories.
