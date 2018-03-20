Window modell web app.

First use Me-Tools load on the document, where you use this code.

and set variable eg. win1.

var win1 = new PlateWindow({..attributes})

Object avail attributes are

1 name            string
2 width           (int) number
3 height          (int) number
4 resizeable      bool
5 move            bool
6 anchor          string (set an link button or element id to activate)

7.configure custom events:

openme,
closeme,
smallme,

this keys are defined as functions that referenced to default control buttons on a window object.

Accessable elements on the win object.

name+[_head] :          id of head DIV element.
name+[_content] :       id of the window body DIV.
name+[_container] :     id of the body container DIV.
