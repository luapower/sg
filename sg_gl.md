---
project: sg
title:   sg_gl
tagline: OpenGL scene graph rendering
---

## `local SG = require'sg_gl'`

## `local sg = SG:new([cache])`

Create a new scene graph render to render OpenGL scene graph objects on the currently active OpenGL context.

## OpenGL scene graph objects

~~~{.lua}
<object> = {
	<group> | ...
}

<group> =
	type = 'group', <object>, ...

~~~

## `sg:free()`

Free the render and any associated resources.

## Extensions

  * [sg_gl_mesh]
  * [sg_gl_shape]
  * [sg_gl_obj]
  * [sg_gl_debug]
