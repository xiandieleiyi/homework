# 色彩表示与编码
![](https://upload.wikimedia.org/wikipedia/commons/thumb/2/21/64_365_Color_Macro_%285498808099%29.jpg/1200px-64_365_Color_Macro_%285498808099%29.jpg)
## 什么是颜色？ 
颜色或色彩是通过眼、脑和我们的生活经验所产生的一种对光的视觉效应。人对颜色的感觉不仅仅由光的物理性质所决定，还包含心理等许多因素，比如人类对颜色的感觉往往受到周围颜色的影响。有时人们也将物质产生不同颜色的物理特性直接称为颜色。
## 在计算机中怎样表示颜色
现实世界是一个绚丽多彩、色彩缤纷的世界。为了将这个世界的色彩准确地表达出来，计算机提供了多种颜色模式和颜色调整方法。色彩的理论知识虽然相同，计算机软件使用的颜色与通常手绘色彩使用的颜色却存在很大的差异，使用计算机调配颜色不需要加水、加油，不需要用画笔均匀地搅拌，不需要用户有熟练的目测颜色能力，不受温度与湿度的影响颜色范围更加广阔。它使用各种标准的调色板、颜色混合器及颜色模式来选择和创建颜色，并可随时进行复制。以上这些是计算机与手绘的不同之处。计算机有自己独特的颜色表达方式，也就是颜色编码。
## 颜色编码
### 1.RGB颜色模式(加色模式)
#### RGB颜色模型：添加剂色彩模型其中红色, 绿色和蓝色光以各种方式结合在一起，复制出一系列广泛的颜色。模型的名字来源于这三个字的首字母（添加剂原色红，绿，蓝）。
![](https://upload.wikimedia.org/wikipedia/commons/2/28/RGB_illumination.jpg)
#### 为了形成具有RGB的颜色，必须叠加三个光束（一个红色、一个绿色和一个蓝色）（例如，通过从黑色屏幕发射或通过白色屏幕反射）。三个光束中的每一个被称为该颜色的成分，并且它们中的每一个可以在混合物中具有从完全关闭到完全开启的任意强度。
![](https://upload.wikimedia.org/wikipedia/commons/2/2e/Palette_of_125_main_colors_with_RGB_components_divisible_by_64.gif)
#### RGB颜色模型中的颜色通过指示包括红色、绿色和蓝色的每一个的多少来描述。颜色表示为RGB三重态（R，G，B），其每个分量可以从零变化到定义的最大值。如果所有的分量都在零，结果是黑色；如果所有的都是最大值，则结果是最亮的可表示的白色。
### 2.CMYK颜色模式(减色模式)
#### 通过将青色、品红色和黄色透明染料/墨水混合在白色基材上，可以实现人类所看到的大范围的颜色。这些是减色的原色。通常添加第四油墨，黑色，以改善一些深颜色的再现。这被称为“CMY”或“CMYK”颜色空间。
![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/CMYK_subtractive_color_mixing.svg/600px-CMYK_subtractive_color_mixing.svg.png)
#### 青色油墨吸收红光但透射绿色和蓝色，洋红色油墨吸收绿光但透射红色和蓝色，黄色油墨吸收蓝光但透射红色和绿色。白色衬底反射透射光回到观看者。因为在实践中，适合于印刷的CMY油墨也反射了一点颜色，使得深色和中性黑色是不可能的，所以通常最后印刷的K（黑色油墨）组分需要补偿它们的缺陷。当预期大量黑色内容，例如在文本媒体中时，使用单独的黑色墨水也是经济驱动的，以减少同时使用三种颜色的墨水。传统彩色照相照片和幻灯片中使用的染料更加完美地透明，因此在这些介质中通常不需要或使用K组分。 
![](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/Halftoningcolor.svg/612px-Halftoningcolor.svg.png)
### CIElab颜色模式(有时简称Lab)
![](https://upload.wikimedia.org/wikipedia/commons/thumb/0/06/CIELAB_color_space_top_view.png/932px-CIELAB_color_space_top_view.png)
![](https://upload.wikimedia.org/wikipedia/commons/7/7d/CIELAB_color_space_front_view.png)
#### CIELAB颜色空间（也称为CIE L*a*b*或者有时简称为“实验室”颜色空间）是由国际照明委员会（CIE）在1976年定义的颜色空间。它表示颜色为三个数值，L*表示亮度，a*和b*表示绿色-红色和蓝色-黄色分量。CIELAB被设计为对人类颜色视觉在感知上是一致的，这意味着这些值中的相同数量的数值变化对应于大约相同数量的视觉感知变化。 
#### CIELAB模型最重要的属性之一是，对于给定的白点，它是与设备无关的——它定义与如何创建或显示颜色无关的颜色。当用于打印的图形必须从RGB转换为CMYK时，通常使用CIELAB颜色空间，因为CIELAB色域包括RGB和CMYK颜色模型的色域。
![](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f3/Example_of_LAB_color_enhancement.jpg/1199px-Example_of_LAB_color_enhancement.jpg)
#### 不像RGB和CMYK彩色模特，实验室颜色是为了接近人类的视觉而设计的。它渴望感知的一致性L组件与人类对轻盈的感知紧密匹配，尽管它没有Helmholtz-Kohlrausch效应考虑在内。因此，它可以通过修改输出来进行精确的色彩平衡校正。曲线在.。a和b组件，或使用L组件。在RGB或CMYK空间中，它们模拟物理设备的输出，而不是人类的视觉感知，只有在适当的帮助下才能完成这些转换。混合模式在编辑应用程序中。
s