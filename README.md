## Vectors:<br/>
#### 3D Creation: Vector3(x, y, z);<br/>
#### 2D Creation: Vector2(x, y);<br/>
#### Usage: vec:function();<br/>
  
2D, 3D	vec:string() -- Obtains a string of vector values.  
2D, 3D	vec:print() -- Prints the current values of a vector.  
2D, 3D	vec:clear() -- Clears a vector's values.  
2D, 3D	vec:unpack() -- Returns each subsequent vector value.  
3D    	vec:length2D() -- Length of the x and y axis. c^2 = a^2 + b^2  
3D, 2D	vec:length() -- Length of the x, y, and z axis. d^2 = a^2 + b^2 + c^2  
3D, 2D	vec:dot(Vector) -- Dot product from two vectors.  
3D    	vec:cross(Vector) -- Cross product from two vectors.  
3D, 2D	vec:distTo(Vector) -- Distance between two vectors.  
3D, 2D	vec:isZero(Tolerance) -- True if the vector values are within the tolerance.  
3D, 2D	vec:normalize() -- Normalizes vector values and returns length.  
  
  
  
## Vector Functions:<br/>
#### Usage: Vector.function(vars);<br/>
  
**Vector.eq(Vector3, Vector3)** -- Equal 3D Vectors.  
**Vector2D.eq(Vector2, Vector2)** -- Equal 2D Vectors.  
**Vector.um(Vector3)** -- Unary Minus of 3D Vector.  
**Vector2D.um(Vector2)** -- Unary Minus of 2D Vector.  
**Vector.add(Vector3, Vector3)** -- Add two 3D Vectors.  
**Vector2D.add(Vector2, Vector2)** -- Add two 2D Vectors.  
**Vector.sub(Vector3, Vector3)** -- Subtract two 3D Vectors.  
**Vector2D.sub(Vector2, Vector2)** -- Subtract two 2D Vectors.  
**Vector.mul(Vector3, Vector3)** -- Multiply two 3D Vectors.  
**Vector2D.mul(Vector2, Vector2)** -- Multiply two 2D Vectors.  
**Vector.div(Vector3, Vector3)** -- Divide two 3D Vectors.  
**Vector2D.div(Vector2, Vector2)** -- Divide two 2D Vectors.  
  
  
  
## Colors:<br/>
#### Creation: Color(r, g, b, a);<br/>
#### Usage: col:function();<br/>
  
**col:get()** -- Returns all color values in subsequent order.  
**col:r()** -- Returns the color's red value.  
**col:g()** -- Returns the color's green value.  
**col:b()** -- Returns the color's blue value.  
**col:a()** -- Returns the color's alpha value.  
**col:string()** -- Returns a string of all color values.  
**col:print()** -- Prints a string of all color values.  
  
  
  
## Misc:<br/>
#### Usage: function(vars);<br/>
  
> Returns fraction (number), endHit (number -Entity Index), endVector (Vector3), hit (bool)  
**trace(Vector3, Vector3, entity)** -- Trace with more information.  
  
> Returns radian (number)  
**degreesToRadians(degree)** -- Return Radians from degrees.  
  
> Returns angle (number)  
**fromAngle(angleX, angleY)** -- Get degrees from angle values.  
  
> Returns position (Vector2), origin (Vector3)   
**getAimTrace()** -- Gets vector location of crosshair trace.  
  
> No Returns  
**draw3DCircle(origin, radius, radius2, color, percent, outline, rotation)** -- Render a custom 3D circle ingame.  
