# **Changelog**


  - [v3.0.0:-](#v300-)
  - [v2.0.0:-](#v200-)
  - [v1.1.0:-](#v110-)
  - [v1.0.7:-](#v107-)
  - [v1.0.6:-](#v106-)
  - [v1.0.5:-](#v105-)
  - [v1.0.4:-](#v104-)
  - [v1.0.3:-](#v103-)
  - [v1.0.2:-](#v102-)
  - [v1.0.1:-](#v101-)
## v3.0.0:-

<iframe src="https://www.youtube.com/embed/mukwPJtgNLY?rel=0&cc_load_policy=1" width="560" height="315" frameborder="0"></iframe>

- PolyHaven HDRI Library (ALT+N)
- Advanced 'RT_World' Node for HDRIs
- Fast Cutter mode for P-Cutter
- New Master Pie Menu
- Complete Japanese Translation
- Shortcut Keys under RanTools Preferences
- Option to use Pie menu for Favorite Modifier Presets (Enable Under RanTools Preferences>Modifier Presets )
- Remesh using dice in Edit Mode and limit the effect to only the selected faces
- Option to Adjust Circle segments after the drawing ( Enable under P-Cutter Preferences of RanTools)
- Option to disable the last shape remembering behavior of P-Cutter.
- Ability to change the Font Size of the on-screen UI.
- Added manual for all operators (Press F1 while hovering over an operator)
- New Help Section in N-Panel.
- Option to see the final shape while using snapping(On by default. Return to the old behavior by unchecking show final (snapped) shape while using Snapping' under P-cutter Preferences).
- Ability to select objects with selected material
- Material Library now supports marking downloaded materials as assets
- Setup Materials can now mark all created materials as an asset
- New Edges pie menu in Edit Mode
- ID Map Baking for Bake Tools.
- Ability to bake multiple objects to one single texture
- Much faster baking when baking multiple objects simultaneously.
- Shoot Through the mesh for booleans(Key: F1)
- Faster Boolean Cleanups with auto loop select
- Better Dice Remeshing
- Cloth Remesh and Simulation are split into 2 parts now.
- P-Cutter Grid can be rotated on all axes.(Press '`' to change the axis)
## v2.0.0:-
<iframe src="https://www.youtube.com/embed/OCv2zxD_iJs?rel=0&cc_load_policy=1" width="560" height="315" frameborder="0"></iframe>

- Option to align the grid to any vertex normal
- Ability to mirror a cutter across a face.
- Synchronized modifiers integration.
- Quick Modifier Adjust Panel redesign.
- New RanTools Project Settings to help manage your projects.
- Preferences UI redesign.
- Check for updates in the Preferences.
- Ability to disable/enable any of the panels.
- Auto Save and load of preferences after every install.
- Use custom checker texture for Add UV Grid option.
- Set bake margins for Bake Tools in the preferences(for export to other software like UE)
- Change Boolean Solver in the cutters Recall list.
- Dicing fix for Blender v2.93.5
- Groups can now be named in the lower-left panel right after creating.

## v1.1.0:-
<iframe src="https://www.youtube.com/embed/oDYB8dKUBWQ?rel=0&cc_load_policy=1" width="560" height="315" frameborder="0"></iframe>

- New Material Library.
- New node mix menu.
- Option to add a  new bevel modifier after the boolean in P-Cutter.
- New favorite modifier presets menu.
- Improved modifier adjust modal.
- Backups are now more organized.
- Ability to use other objects (instead of backup versions) for transferring normals and fixing shading artifacts.
- Focus Scroll has been replaced with a much easier-to-use Focus Picker.
- There is now a new button to paste the copied color to all the lights of a group.
- Ability to clear split normals data.

## v1.0.7:-
- Advanced edge alignment
- More Grid customization
- Cutters Recall
- Separation adjustment in the curve modal
## v1.0.6:-
- New curve adjustment modal.
- Ability to add Caps to curves/wires
- Improved UI
- 2 New Modifier Presets
## v1.0.5:-
- Fixed the issue with P-Cutter where aligning to the view without anyactive object led to a crash.
- Extract faces modal now allows the user to select disconnected faces.
- Added a new 'Extract faces from solid objects only' option to preferences.
- Information tooltip now follows the cursor on movement.

## v1.0.4:-
- Fixed P-Cutter's interaction with hidden objects (in local view).
- Added 'Align Normals to Axis' feature.
- Integrated other minor bug fixes and improvements.
## v1.0.3:-
- New 'Extract>Inset>P-Cutter' function that combines Extract Faces, Inset rink, and P-Cutter into a single modal.
- Fixed a typo in the preferences.
- Integrated other minor bug fixes and improvements.

## v1.0.2:-
- Improved the design of the onscreen help, by adding proper alignments and visual cues on key presses.
- You may now hold CTRL to change values faster with larger increments.
- Empties associated with cables are now set to always be in front, so they don't disappear within the cable.
- Added a toggle to change the default behavior of the 'Keep shape'.

## v1.0.1:-
- Changed the add folder hint to a more general "Choose Path".
- P-Cutter now remembers the last shape used for drawing.
- Removed redundant button from the RanTools menu.
- Added a visibility toggle option to the modifier adjust panel for boolean objects.