# Unity-CameraController
This is a camera controller that can be use for RTS games made in Unity.<br />
It's far from perfect but it does the job pretty well and fast.<br />
Here is the list of what is currently implemented:<br /><br />
<b>Keyboard</b>
<ul>
  <li>W, A, S and D to pan</li>
  <li>Q and E to rotate</li>
  <li>R and F to zoom</li>
</ul>
<b>Mouse</b>
<ul>
  <li>Right click and drag to pan</li>
  <li>Move the mouse to one of the edges of the screen to pan</li>
  <li>Middle mouse button to rotate horizontally and vertically</li>
</ul>
<b>Behaviours</b>
<ul>
  <li>If an object is tagged with <i>Ground</i> layer (this can be anything you want as long as you set it in the inspector in the <i>groundLayer</i> variable to your liking) and <i>AdaptToTerrainHeight</i> is set to true, the camera will automatically go up when it reaches the minimum zoom set in the <i>zoomMin</i> variable</li>
  <li>Turn on Gizmos in the Game tab to see the ray from the camera movement</li>
  <li>Camera is set to smooth it's movement to the desired location, you can turn this on and off with the <i>smoothing</i> variable and set the <i>smoothingFactor</i> variable as well</li>
</ul>

Part of this code is similar to the one found in this video https://www.youtube.com/watch?v=_adEYoaArc4 because that's where I got some ideas for the camera controller.

<b>TODO</b>: <br />
Use the terrain limits to clamp the camera movement.
