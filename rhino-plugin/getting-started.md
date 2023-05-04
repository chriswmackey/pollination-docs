# Getting Started in Rhino

There are two interfaces for Pollination in Rhino. You can use the Pollination panel to use buttons to create your analytical model, or you can type Pollination commands in the command line.

## Pollination Panel

To pull up the Pollination panel, type `Pollination` in the command line. Once you hit Enter, the Pollination panel will emerge. You can dock it in your window as you would a native Rhino panel.

{% embed url="https://youtu.be/qJQCc59EdCw" %}

## Pollination Commands

A list of Pollination Commands for Rhino with detailed descriptions is available in this user manual. You can also type "PO\_" in the command line to preview a list of commands in Rhino.

{% content-ref url="pollination-commands/" %}
[pollination-commands](pollination-commands/)
{% endcontent-ref %}

### Native Rhino Command Compatibility

Besides custom Pollination commands, there are several native Rhino commands that can be used to modify custom Pollination RhinoObjects.

|                              ACTION                             | COMMAND LINE |  GUMBALL     | KEYBOARD SHORTCUT |
| :-------------------------------------------------------------: | :----------: | :---: | :---------------: |
|                          Copy / CTRL+C                          |     **✔**    | **✔** |       **✔**       |
|                           Cut / CTRL+X                          |     **✔**    |       |       **✔**       |
|                          Paste / CTRL+V                         |     **✔**    | **✔** |       **✔**       |
|                          Undo / CTRL+Z                          |     **✔**    |       |       **✔**       |
|                          Redo / CTRL+Y                          |     **✔**    |       |       **✔**       |
|                              Delete                             |     **✔**    |       |       **✔**       |
|                         Move / GumballDrag / GumballTransform                              |     **✔**    | **✔** |                   |
|  <p>Move Sub-Geometry</p><p><em>(Hold Shift+Ctrl keys)</em></p> |     **✔**    | **✔** |                   |
|                    Scale / Scale1D / Scale2D                    |     **✔**    | **✔** |                   |
|                    Rotate / Rotate3D                    |     **✔**    | **✔** |                   |
|                      MoveFace / MoveEdge                      |     **✔**    |       |                   |
| <p>Explode</p><p><em>(RoomObject=> OrphanedFaces only)</em></p> |     **✔**    |       |                   |
|       <p>Join</p><p>(OrphanedFaces => RoomObject only)</p>      |     **✔**    |       |                   |
|                      SplitFace / MergeFace                      |     **✔**    |       |                   |
|                             Flip / Dir                            |     **✔**    |       |                   |
|                               Cap                               |     **✔**    |       |                   |
|                           Trim / Untrim / UntrimHoles                           |     **✔**    |       |                   |
|                              Mirror                             |     **✔**    |       |                   |
|                      MergeAllCoplanarFaces                      |     **✔**    |       |                   |

![Undo and Redo Commands](../.gitbook/assets/undoredo.gif)

![Move Face & Move Edge Using Rhino Command line](../.gitbook/assets/moveface\_moveedge\_cmd.gif)

![Move Face & Move Edge Using Gumball](../.gitbook/assets/moveface\_moveedge.gif)
