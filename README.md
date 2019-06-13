# zdogXperiments
experiments with zdog

I discovered Zdog in the beginning of june 2019 and I liked it immediately.
It's a really cool project, so I decided to make some experiments with it.
This github repository is the result of those experiments.
It's just the beginning, I have a lot of other ideas to test ;)

Note that for all shapes, it's possible to zoom with arrow keys, to reset the zoom with the escape key, and to "click & drag" to rotate the shape.

To test the algorithms, just download the zip of this repository, unzip it, double-click on "index.html", and follow the links.

The content of the project :

- 3D Cube : cube generated programmatically, with two types of render : "wireframe" and "paint" (for the "paint" mode, colors are generated by Chroma.js)

- 3D shapes : shapes generated programmatically => cube, sphere, icosahedron, pyramid, cylinder and cuboïd

- Load wavefront obj files V1 (*) : cube, dodecahedron, icosahedron, and a lot of other objects, found on this site : http://people.sc.fsu.edu/~jburkardt/data/obj/obj.html

- Load wavefront obj files V2 (*) : V1 with asynchronuous loading of the 3D objects (better practice using the Fetch API)

- Load wavefront obj files V3 (*) : V2 plus a new "paint" mode (the same used for "3D Cube" and "3D shapes")

- Menger Sponge & Flake generators : adaptation of algorithms of Frido Verweij (https://library.fridoverweij.com/codelab/menger_fractals/)

- Tunnel 3D : shape generated using an algorithm of Niklas Knaack, found on this pen : https://codepen.io/NiklasKnaack/pen/WyWqja


(*) Note that the import OBJ algorithm is largely inspired by a similar algorithm found on Phoria.js, of Kevin Roast : http://www.kevs3d.co.uk/dev/phoria/

------------------

The example "3D shapes" is visible on Codepen :
https://codepen.io/gregja/pen/BgodWw

Link to this github repository :
https://github.com/gregja/zdogXperiments

Link to the official site of Zdog :
https://zzz.dog/
