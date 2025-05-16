# Ginkgo-Weight-Tools
[![Watch the video](https://img.youtube.com/vi/qD_etT5GHTk/0.jpg)](https://www.youtube.com/watch?v=qD_etT5GHTk)

A plugin for blender. 3.0.0 that makes weight painting easy

If this plugin helped you please considering donating some money lol: https://ko-fi.com/themightyginkgo
With this plugin activated, just select the mesh you want to weight paint, and press the Turn on Weight Paint mode button.
When you are done, and want to select another mesh to weight paint, Press the Turn on Object mode button to exit Weight paint mode.
If you can not see your bones in weight paint mode, Press the Toggle Xray Bone button. .
How to Weight Paint Tips and lingo
Weight= How much Influence the bone will have over the mesh.
Ranging from 0.0(Blue)- 1.0(Red) The more Red is painted on the mesh the more influence the bone will have over the mesh.
The more Blue is painted the less influence the bone has over the mesh.
Think of it like heat from those old cartoons, The hotter(redder) something is the more control it has, the Colder or (Bluer) the mesh is the less control the bone has.

Radius =
How big the brush that you're painting with is.
Strength: How strong the Weight comes out of the brush.

Weight transfer=
With this button you have the ability to transfer weight from one mesh object to another.(Warning) The transfer can only transfer weights between meshes that have the same Vertex groups/Bone groups.)
If you are selecting a mesh with no vertex groups it will transfer the bone name and weights from the source to the target.

-How to use-
1-In object mode, select the eye dropper icon and select what item you want to act as the source.

2- while still in object mode select the mesh you want to transfer weight to,(This is known as the target mesh)
Then press the Turn on Weight Paint mode button.
The target mesh will turn blue.
From here you have multiple options.
You can press the following buttons for the following effect

Transfer to all Bones: This button will transfer weights to all the bones in the target from the source.

Transfer to selected bones: This will transfer weight only to the bones that you selected.

Delete all groups: This will delete all the vertex groups out of the selected mesh, making it Unrigged.
Delete selected bone groups: This button will delete the groups/weights from the bones you selected.
Bone visibility
Screenshot_5

These buttons will allow you to choose how the bones work in your project.
Sometimes bones get in the way, with these buttons you'll have the ability to hide them. This is good when a bone is in the way but you cant delete them.

Hide selected bones= Will allow you to hide the bones you select.

When you hide a bone in the project, a menu will pop up that will show you which bone is hidden.

From this menu, you can choose to unhide that individual bone, without unhiding all of the bones.

Show all bones= This will show all the bones that are hidden.

Toggle Xray bones: This button will make the bones in your skeleton show through the mesh, making it easier to select them.
--
Misc Tips

Toggle Gradient tool: This allows you to add gradient of weight across the mesh.

Toggle vertex mask/ Toggle face mask:
These two buttons will allow you to mask off an area you want to use the gradient tool on.
Both Toggle Vertex Mask and Toggle face mask,should only be used in weight paint mode.
Bones CAN NOT be selected when both Vertex and Face mask are toggled on.

Box select and Circle select-
used in Weight Paint mode when the Vertex and face mask buttons are active. These allow you to select the range in which the gradient tool will influence.

