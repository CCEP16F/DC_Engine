# (Delta-Core)(Delta-Cube) Engine
Game Engine Implementation



<H1>PORTABILITY, DEPENDENCY  MODIFICATIONS</H1>
<ul>
  <li>Replace zlib for miniz (Complete) [zlib as compile option]</li>
  <li>Replace SDL2_image with stb_image (Complete)</li>
  <li>Replace SDL2_mixer with miniaudio</li>
</ul>

<H1>GENERAL MODIFICATIONS</H1>
<ul>
  <li>Cmake Support (Complete)</li>
  <li>Multi Window Backend (In Progress)</li>
  <ul>
    <li>SDL Backend (In Progress)</li>
    <li>GLFW Backend</li>
  </ul>
  <li>Multi Window support (In Progress)</li>
  <li>Context Based Inputs (In Progress)</li>
  <ul>
    <li>Button Input (Complete)</li>
    <li>Axis Input (Complete)</li>
    <li>Keyboard Bindigns (Complete)</li>
    <li>Mouse Button Bindings (Complete)</li>
    <li>Mouse Movement Bindings (In Progress)</li>
    <li>Game Controller Bindings (In Progress)</li>
  </ul>

  <li>Game Code as dynamic link module</li>
  <li>Simplify Code</li>
  <li>Entity Rotation vector "liberate attributes from handling rotation"</li>
  <li>Modified Nuklear UI support (In Progress)</li>
  <ul>
    <li>Change nk namespace to ui (In Progress)</li>
    <li>Use Common Vertex library (Complete)</li>
    <li>Use Common Color library (Complete)</li>
    <li>reduce structure names, use typedefs (In Progress)</li>
    <li>local string support (In Progress)</li>
  </ul>
  <li>Bezier surface</li>
  <li>Procedural materials|textures</li>

  <li>Improved directory control</li>
  <ul>
    <li>Home path</li>
    <li>Config path</li>
    <li>Game Data path</li>
    <li>Project path</li>
    <li>Asset Library path</li>
  </ul>
  
  <li>Include Development Documentation</li>
</ul>

<H1>ASSETS MODIFICATIONS</H1>
<ul>
  <li>Fast loading Binary formats</li>
  <ul>
    <li>Model File Format</li>
    <li>Texture File Format</li>
  </ul>
  <li>ID Based Asset loading "sha1(virtual file_path) probably"</li>
  
  <li>Assets Data Base</li>
  <li>Assets Server</li>
  
  <li>LZ4 based pack files</li>
</ul>

<H1>EDITOR MODIFICATIONS</H1>
<ul>
  <li>Include 3D Gismos</li>
  <li>Mesh - Ray cast Select "replace bbox - ray cast"</li>
  <li>Decal selection only if visible</li>
  <li>Selection masks "Lights, mesh, world, etc."</li>
  <li>Layers "Visibility groups"</li>
  <li>UI Entity Editor (In Progress)</li>
  <ul>
    <li>Generic Entity Attribute Editor (Complete)</li>
    <li>Lights entity editor with Color Picker (Complete)</li>
    <li>Mapmodel entity editor (Complete)</li>
    <li>Playerstart entity editor (Complete)</li>
    <li>EnvMap entity editor (Complete)</li>
    <li>Sound entity editor (In Progress)</li>
    <li>Decal entity editor (In Progress)</li>
    <li>Particle entity editor</li>
  </ul>
  <li>UI Vertex editor (In Progress)</li>
  <ul>
    <li>Vertex Color Picker</li>
    <li>Vertex Texture offset</li>
    <li>Vertex Texture scale</li>
    <li>Vertex Texture rotation</li>
    <li>Vertex texture Picker</li>
  </ul>
  <li>Multi selection</li>
  <li>Bezie Surface editor</li>
  <li>Procedural Material editor</li>
  <li>Constructive Solid Geometry editor</li>
  <li>Volumetric sculting</li>
</ul>

<H1>TOOLS</H1>
  <li>Asset Importer tool</li>
  <ul>
    <li>OBJ</li>
    <li>SMD</li>
    <li>IQM</li>
    <li>MD2</li>
    <li>MD3</li>
    <li>MD5</li>
    <li>GLTF2</li>
  </ul>
  <li>Asset Data Base Inspector</li>
  <li>Package tool</li>
<ul>
