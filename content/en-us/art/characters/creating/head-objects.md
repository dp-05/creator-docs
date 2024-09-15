---
title: Template Head Structure
description: Each Roblox avatar template contains modular separate pieces.
next: /art/characters/creating/blender-configurations
prev: /art/characters/creating/template-files
---

In each template file, the avatar body includes extra head mesh objects and face armature bones for easier changes.

<Alert severity = 'info'>
  These extra objects and bones must be removed before export to avoid validation errors in the marketplace. We go over this in detail during the cleanup step.
</Alert>

Extra head meshes:
<GridContainer numColumns="2">

  <figure>
   - Head_Geo
   - UpperTeeth_Geo
   - LowerTeeth_Geo
   - Tongue_Geo
   - RightLash_Geo
   - RightEye_Geo
   - LeftLash_Geo
   - LeftEye_Geo
</figure>

  <figure><img
  alt="Head-Related Meshes"
  src="../../../assets/art/blender-ui/Face-Objects.png"
  width="800" /><figcaption>Extra head-related meshes in Blender's Outliner</figcaption></figure>
</GridContainer>

<p />

Extra head bone children (varies between templates):

<GridContainer numColumns="2">

  <figure>
   - Tongue
   - LowerTeeth
   - UpperTeeth
   - LeftEye
   - RightEye
</figure>

  <figure><img
  alt="Head-Related Meshes"
  src="../../../assets/art/blender-ui/Face-Bones.png"
  width="800" /><figcaption>Extra head-related bones in Blender's Outliner</figcaption></figure>
</GridContainer>

