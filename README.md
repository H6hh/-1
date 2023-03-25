# -1
对比度拉伸、阈值处理  
第二部分，灰度图片分段线性变换  
分段线性变换函数来增强图像对比度的方法实际是增强原图各部分的反差，即增强输入图像中感兴趣的灰度区域，相对抑制那些不感兴趣的灰度区域。  ![U2YBM{1YIGT~}~E2NU2NJ1P](https://user-images.githubusercontent.com/98206033/227700011-0a26cdf0-5f12-4c0b-ad84-144734b75729.png)
  小狗，对比度拉伸不明显![XPPG_Z9DPB)LZ`DJ6} PHSA](https://user-images.githubusercontent.com/98206033/227700039-4e0e43a3-1534-4b69-8b2c-3a1f43b6d651.png)  
  对花粉的原图和经过对比度拉伸后的图像对比
![M7%{ {91 GCK)K$9H9@RO@6](https://user-images.githubusercontent.com/98206033/227700082-8c91d76c-6389-477e-9091-81b2071a1ee7.png)  
经阈值处理后的狗狗图像和花粉图像如图所示  ![image](https://user-images.githubusercontent.com/98206033/227700254-afe0ddc4-52a9-4cb8-818a-0ef70fcaa605.png)
似乎区分度更大...
