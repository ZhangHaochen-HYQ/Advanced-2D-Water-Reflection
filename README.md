# 2D Advanced Water Reflection Asset for Unity
增加了水面反射的复合渲染效果。

在原有水面反射功能的基础上，新增了额外物体渲染与水面合成功能。通过独立的渲染层，可以将指定物体额外渲染并与环境反射共同输入水面 Shader，统一进行水波扰动、折射等水面效果处理。

该功能适用​​于实现水面漂浮物的倒影、水下物体的显示，以及其他需要与水面反射效果进行统一合成的特殊元素，从而获得更加真实且完整的水面表现。

Enhanced composite rendering effects for water surface reflections.
Building upon the existing water surface reflection functionality, a new feature has been added for additional object rendering and water surface compositing. Through a separate rendering layer, specified objects can be rendered separately and input into the water surface shader along with environment reflections, allowing for unified processing of water surface effects such as ripple disturbance and refraction.

This feature is suitable for realizing reflections of floating objects on the water surface, displaying underwater objects, and other special elements that require unified compositing with water surface reflection effects, resulting in a more realistic and complete water surface representation.

# How to use:
为需要参与水面反射合成的物体创建一个新的 Layer，例如 Water Overlay。
将 Advanced Water Reflection 预制体拖入场景，并将其子对象中的  Water Overlay Camera 的 Culling Mask 设置为 Water Overlay Layer。

Create a new layer, such as a Water Overlay, for the objects that need to participate in the water reflection composition.
Drag the Advanced Water Reflection prefab into the scene and set the Culling Mask of the Water Overlay Camera in its child object to the Water Overlay Layer.

# 2D Water Reflection Asset for Unity

Unity 2D water reflection asset, customizable.  
It is possible to put multiple reflection assets in a single scene.


Check the install tuto video:

[<img src="2D Water.PNG"/> ](https://youtu.be/Bc-nRBqHhmg)

# Unity version >= 2020 !
