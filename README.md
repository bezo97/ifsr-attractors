# ifsr-attractors

"Attractors" transform pack for [IFSRenderer](https://ifsrenderer.z97.io/).

## Install

- [**Download**](https://github.com/bezo97/ifsr-attractors/archive/refs/heads/main.zip) the zip and extract.
- Copy the `attractors` folder to IFSRenderer's library. You can click the little Folder icon in the editor next to the transforms to see the collection
- Click the Refresh button to load the transforms

## Usage

- Set a very high syntropy value in the render settings
- Search for "attractor" in the editor's transform list and pick something
- Set a self-connecting weight on the node
- Always use `Add = 1` on iterators with an attractor transform

---

I've discovered most of these formulas in [this](https://observablehq.com/@rreusser/strange-attractors-on-the-gpu-part-2) blog post. Feel free to contribute by opening a Pull Request.