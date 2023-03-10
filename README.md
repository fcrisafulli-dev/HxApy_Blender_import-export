Installation instructions:
- run the zip.py, by typing into a command prompt ```py zip.py```, this generates a .zip archive.
- launch Blender,
Edit->Preferences->Addons->click Testing->Install-> locate the .zip file, press Install
- we can now find the addon in these menus:
<br>```File->Import->"HxA (.hxa)"```
<br>```File->Export->"HxA (.hxa)"```
<br> From there you can import and export HxA files, like you would any other 3D format.</br>

Features supported at the moment(what can be imported and exported alongside a mesh):
- Armature and weight vertexes(if any)
- Shapekeys
- Edge creases
- Custom properties

# This is an experimental fork which has untested code
particular features of this fork:
- Added HXALayer for vertex normals
- Model loading is completely untested and is likely broken
