# VR Form Elements
**Issues** around creating form element components for use in VR. Any working code will be linked to in a list of elements below.

## Goals
The goal is to provide functional and re-usable VR equivalents for traditional 2D form elements. For instance, a radio button toggle which is a lever that can move up and down, or two buttons which switch states when one is pressed. There can be more than one way to represent some elements.

We'll first be coming up with ideas around each element (if it has a visual component), then providing working prototypes in separate repositories for Aframe (webvr), Unity, and Unreal Engine. 

Component libraries should be created in a way that form attributes become properties of the component which can be changed in their resepcted engines. For instance adding a radio button to Unity provides an options panel for relevant attributes which can be set by the project owner.

They should also be created in a way that the components are easily added to any project. For instance, a radio button componenet for Aframe could be coded using aframe-react and added to npm for people to install in their Aframe projects, and Unity and UE4 components added to their respective stores for people to find and use in their projects.

As mush as we want to provide re-usable components, this is also largely a study to see what is possible when it comes to replicating traditional input gathering from users. Our BHAG (big hairy audacious goal) would be to re-create something like wufoo.com for Virtual Reality.
