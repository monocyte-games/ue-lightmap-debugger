# Lightmap Debugger
Easily view the lightmap and lightmap UVs of level actors.

![Lightmap selection](https://monocyte-website-public.s3-eu-west-1.amazonaws.com/images/lightmap_debugger/lightmap_selection.jpg)

This is a light map viewer and debugger that we developed for Unreal Engine and that will should be available on the Unreal Marketplace soon.

The motivation behind this tool is to make it easier to determine where the problem lies if there are what appears to be lighting artifacts on static actors in a scene. We found that there was not really an easy way to quickly find the correct lightmap for an actor in a level, as well as visualize the light map UVs of the actor. This tool allows one to:

  - View the lightmap for the selected actor in a 2D viewport (similar to the texture editor)
  - Pan and scale to fit the lightmap UVs of the actor overlayed on the lightmap texture
  - View the lightmap projected onto the static mesh in a 3D viewport (similar to the static mesh editor)
  - This has really helped us to quickly find and diagnose lightmap / UV issues with our static actors.

Once the plugin is installed and loaded a new context menu entry appears in the level editor viewport:

![Opening the lightmap debugger for a selected level actor](https://monocyte-website-public.s3-eu-west-1.amazonaws.com/images/lightmap_debugger/leveleditor_context_menu.JPG)

Here are some more screenshots of the light map viewer / debugger (mesh selection, lightmap quality selection and LOD selection):

![Mesh selection](https://monocyte-website-public.s3-eu-west-1.amazonaws.com/images/lightmap_debugger/mesh_selection.JPG)

![LOD selection](https://monocyte-website-public.s3-eu-west-1.amazonaws.com/images/lightmap_debugger/lod_selection.jpg)
