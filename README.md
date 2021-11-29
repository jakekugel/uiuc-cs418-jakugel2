# Web Molecule

Web Molecule - Jake Kugel, 2021

This page displays 3-dimensional ball and stick models of various molecules.  It
is developed using WebGL, and it uses the following 3D graphics techniques:

* **smooth per-pixel lighting** - shapes in scene show diffuse and specular
   lighting on per-pixel basis.
* **shadow mapping** - spheres and cylinders cast shadows onto each other.
* **bump mapping** - raised ridges visible in sphere when close-up.
* **texture mapping** - chemical symbols displayed on spheres.
* **sphere mapping** - a reflection of the UIUC football stadium is seen in objects.
* **instancing** - a WebGL technique used to draw multiple instances of the same
    triangle mesh in a scene.
* **grid-based texture mapping** - storing multiple texture maps in a grid, and
    referencing different regions of grid on per-instance basis.

This page was developed by Jake Kugel as the final project for class CS-418 at
the University of Illinois at Urbana-Champaign, taught by Professor John Hart,
as part of the Online MCS program.

## Credits
Most concepts that were used to build this visualization came from UIUC CS-418
and Prof. Hart.  This is an excellent class to learn modern interactive
3D graphics.

This page also uses several WebGL2 techniques described in the very useful
website https://webgl2fundamentals.org/.

Thanks to my dad, Prof. Roger Kugel, for a conversation about covalent bonds and
how to determine where bonds exist given a molecular 3D structure.

Thanks to my son, Eric Kugel, for a conversation about JavaScript best practices
used in this page (or lack thereof).

## License (MIT)
Copyright 2021 Jake Kugel

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Third-party code and resources
This page was developed using third-party code and other resources.  A
description of all third-party code and assets is listed here.  The above
copyright and license does not apply to these assets.

**Boilerplate project cs418-fa21-project** - this repository began as a fork of
    an example project provided by Prof. Hart (https://github.com/jch-uiuc/cs418-fa21-project).
    Although I am not aware of any fragments of the original boilerplate
    index.html that remain in the current code, the sphere map
    'stadium sphere.jpg' comes from this boilerplate project.  Also, the block
    'I' logo in bumpmap.png was a modified version of the block 'I' in
    'illinois512.png' in the boilerplate project.

**gl-matrix-min.js** - this open source linear algebra library was developed
    by a third party.  See the script for authors and copyright.

**webgl-debug.js** - this third-party library enables debugging console messages
    for webgl.  This script is a copyright of the The Khronos Group Inc.  A copy
    of this script was included in the source repository and the copyright and
    license are embedded in the script.

**webgl-lint.js** - this very useful third-party script checks for many common
    WebGL2 usage errors that would otherwise be difficult to catch.  This is
    copyright Gregg Tavares, and the license can be found here:
    https://github.com/greggman/webgl-lint/blob/master/LICENSE.md.

**uiuc-compsci-2.jpg** - this image is a modified version of the image used for
    the Illinois CS Twitter account.

**caffeine geometry** - National Center for Biotechnology Information.
    "PubChem Compound Summary for CID 2519, Caffeine" PubChem,
    https://pubchem.ncbi.nlm.nih.gov/compound/Caffeine.
    Accessed 22 November, 2021.

**hydrocortisone geometry** - National Center for Biotechnology Information.
    "PubChem Compound Summary for CID 5754, Hydrocortisone" PubChem,
    https://pubchem.ncbi.nlm.nih.gov/compound/Hydrocortisone.
    Accessed 22 November, 2021.

**nanotube geometry** - University of Delaware TubeGen Online
      https://turin.nss.udel.edu/research/tubegenonline.html

**DNA geometry** - World of Molecules
      https://www.worldofmolecules.com/3D/dna_3d.htm

**Bond lengths** - Chemistry: The Molecular Nature of Matter and Change, 8th Ed.
      Authors: Martin Silberberg, Patricia Amateis
      Publisher: McGraw Hill Education, New York.
      Copyright: 2018.
