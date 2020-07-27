# MRTK-StandardShader
Standalone version of MRTK Standard Shader

This repo is a mirror of the bare minimum extracted components to fully utilize the MRTK Standard Shader without needing to include all of MRTK.

# MixedRealityToolkit/Standard shader

The MixedRealityToolkit/Standard shader is a collection of shading techniques for mimicking [**Microsoft's Fluent Design System**](https://fluent.microsoft.com/) within Unity 3D.

The goal of this shader is to have a single, flexible shader that can achieve visuals similar to Unity's Standard Shader, implement Fluent Design System principles, and remain performant on mobile hardware, including standalone mixed reality devices.

## Example scenes

To explore a Unity scene demonstrating materials, open **Scenes\MaterialGallery.unity**.

To compare the Unity Standard shader to the MRTK Standard shader open **Scenes\StandardMaterialComparison.unity**.

For clip primitive examples, open **Scenes\ClippingExamples.unity**.

## Limitations

Only one light source is supported, the directional light (additional light can be achieved using lightmapping).

## Download

Either clone this repo, or download the packages in the Releases section.
