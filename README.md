

# Taizyd Korambayil SDGM-560 Blog
## Week 1 - Transition Effect Prototype _09/14/2018_

For the first week as we as a group decided on what the project would be and the kind of effect we are doing. Since we are dealing with 
a transition effect where a car transforms from and old model into another I decided to do a quick prototype shader in UE4 that we could use as a Previs element in out pitch.

![Shader](img/ShaderTest.gif)

The shader is essentially driven by a linear gradient generated from the Forward Vector of a Location Blueprint. The geometry is masked and swapped based on which side of the locator BP it is on.

**Shader Nodes**
![TestShader](img/prototypeshader.png)

The Location of the Blueprint Actor is fed into the shader using a Material Parameter Collection fo Convenience.

**BP Locator Setup**
![LocatorBP](img/locatorBP.png)

For the final effect we intend to make use of Houdini's game sheld tools to bake out Pivot Points and also bring in cached geometry animation from houdini and implement these in Unreal using shaders and Blueprints to drive them in real time.

**FX Reference** <BR>            
![ref01](img/fxref_01.gif) 
![ref02](img/fxref_02.gif)
![ref03](img/fxref_03.gif) 
![ref04](img/fxref_04.gif)
![ref05](img/fxref_05.gif) 
![ref05](img/fxref_06.gif)


