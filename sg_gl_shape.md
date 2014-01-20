---
project:  sg
title:    sg_gl_shape
tagline:  OpenGL scene graph shapes
---

## `require'sg_gl_shape'`

Extends [sg_gl](sg_gl.html) to render shape objects.

## Shape objects

A shape is a type of OpenGL scene graph object that describes a 3D object in a state-machine kind of language.
Internally, the shape description is converted into a [mesh object](sg_gl_mesh.html) which is then rendered.

~~~{.lua}
<shape_object> = {
	type = 'shape',
	<mode> |
	'color', r, g, b, a |
}

<mode> = see sg_gl_mesh for available modes.
~~~

----
See also: [sg_gl_mesh](sg_gl_mesh.html)
