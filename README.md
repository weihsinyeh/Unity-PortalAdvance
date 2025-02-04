# Portals

Little test of portals in Unity.
Note: in the two worlds scene, you'll need to have Blender installed to view some of the models.

[Watch video](https://www.youtube.com/watch?v=cWpFZbjtSQg)

![Portals](https://raw.githubusercontent.com/SebLague/Images/master/Portals.png)

```
Matrix4x4 m = red.localToworldMatrix & blue.worldToLocalMatrix * playerCam.localToworldMatrix;
portalCam.SetPositionAndRotate (m.GetColumn(3), m.rotation);
```
open-project-1
install in my unity: https://youtu.be/RbSrx0QoTG4
install the license of the unity github project : https://support.unity.com/hc/en-us/articles/4402520309908-How-do-I-add-a-version-of-Unity-that-does-not-appear-in-the-Hub-installs-window-
Download Archive : https://unity.com/releases/editor/archive

#### Physics
After enter space they will produce a cube
![image](https://user-images.githubusercontent.com/90430653/211163642-9e4fb8fb-02a6-42f8-ad7d-37b8acee9ca7.png)
![image](https://user-images.githubusercontent.com/90430653/211163663-d589de1c-1d7c-479c-9a1c-b144a0a132fa.png)

After enter sapce then it can jump and up arrow it will move forward.
![image](https://user-images.githubusercontent.com/90430653/211163906-d524c6cb-99aa-4fbe-8b15-e41bef2c59fe.png)

Slice object by portal
![image](https://user-images.githubusercontent.com/90430653/211163931-4e6261dd-4969-4876-8002-b95c2d2bca2e.png)

See another world by portal
![image](https://user-images.githubusercontent.com/90430653/211163970-304749f5-d403-40f1-8e29-c8d94e65791a.png)

#### Reference
[Blog](http://tomhulton.blogspot.com/2015/08/portal-rendering-with-offscreen-render.html)

[The Perspective and Orthographic Projection Matrix](https://www.scratchapixel.com/lessons/3d-basic-rendering/perspective-and-orthographic-projection-matrix/projection-matrix-introduction.html)

[Computing the Pixel Coordinates of a 3D Point](https://www.scratchapixel.com/lessons/3d-basic-rendering/computing-pixel-coordinates-of-3d-point/mathematics-computing-2d-coordinates-of-3d-points.html)

[The Perspective and Orthographic Projection Matrix](https://www.scratchapixel.com/lessons/3d-basic-rendering/perspective-and-orthographic-projection-matrix/projection-matrix-GPU-rendering-pipeline-clipping.html)

[The Cg Tutorial](https://developer.download.nvidia.com/CgTutorial/cg_tutorial_chapter04.html)

[OpenGL](http://ogldev.atspace.co.uk/www/tutorial12/tutorial12.html)

http://fabiensanglard.net/polygon_codec/

[[Shader筆記] 連你阿罵都能看得懂的Shader介紹](https://medium.com/ericzhan-publication/shader%E7%AD%86%E8%A8%98-shader-development-using-unity-01-b1cde1f23adf)

[猫都能学会的Unity3D Shader入门指南（一)](https://onevcat.com/2013/07/shader-tutorial-1/)

[3D图形学基础](https://zhuanlan.zhihu.com/p/27846162)
