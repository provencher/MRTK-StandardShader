# MRTK-StandardShader
Standalone version of MRTK Standard Shader

This repo is a mirror of the bare minimum extracted components to fully utilize the MRTK Standard Shader without needing to include all of MRTK.

**Tested setup:** Unity 2019.4 LTS, though it should work with older or newer versions.

# MixedRealityToolkit/Standard shader

The MixedRealityToolkit/Standard shader is a collection of shading techniques for mimicking [**Microsoft's Fluent Design System**](https://fluent.microsoft.com/) within Unity 3D.

The goal of this shader is to have a single, flexible shader that can achieve visuals similar to Unity's Standard Shader, implement Fluent Design System principles, and remain performant on mobile hardware, including standalone mixed reality devices.

## Example scenes

To explore a Unity scene demonstrating materials, open **Scenes\MaterialGallery.unity**.

![StandardShader](https://user-images.githubusercontent.com/7420990/88569823-fb245700-d008-11ea-95eb-a53f656574a6.gif)


To compare the Unity Standard shader to the MRTK Standard shader open **Scenes\StandardMaterialComparison.unity**.

![MaterialComparison](https://user-images.githubusercontent.com/7420990/88569761-e9db4a80-d008-11ea-97c3-aa783dd03f8d.png)


For clip primitive examples, open **Scenes\ClippingExamples.unity**.

**Sphere**

![ClipSphere](https://user-images.githubusercontent.com/7420990/88569731-dd56f200-d008-11ea-8d94-e0b01f2d3307.gif)

**Box**

![ClipBox](https://user-images.githubusercontent.com/7420990/88569738-e0ea7900-d008-11ea-9029-85e74169002c.gif)

**Plane**

![ClipPlane](https://user-images.githubusercontent.com/7420990/88569753-e5169680-d008-11ea-8923-9194d92b1ddd.gif)

## Limitations

Only one light source is supported, the directional light (additional light can be achieved using lightmapping).
If you already using MRTK, then this package is not needed for your project.

Note this shader is designed to work with the default built-in renderer. 
MRTK includes an upgrade script that should allow it to work with URP, though certain features that rely on the depth buffer like stencils and outlines will not work until that is properly supported on URP.

## Download

Either clone this repo, or download the packages in the [Releases](https://github.com/provencher/MRTK-StandardShader/releases) section.
