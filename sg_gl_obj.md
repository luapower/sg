---
project: sg
title:   sg_gl_obj
tagline: OpenGL scene graph OBJ meshes
---

## `require'sg_gl_obj'`

Extends [sg_gl](sg_gl.html) to render wavefront OBJ files. Uses [obj_loader](obj_loader.html)
to parse obj files into [sg_gl_mesh mesh objects](sg_gl_mesh.html).

## Wavefront obj objects

~~~{.lua}
<obj_object> = {
  type = 'obj',
  file = {
    path = S,
    use_cache = true | false (false),
  },
}
~~~

----
See also: [sg_gl_mesh](sg_gl_mesh.html), [obj_loader](obj_loader.html)

