# UvcDDApp
---
初学DirectDraw练手的简单封装  
要使用这个封装请继承UvcDDApp类并实现Draw函数  
默认使用窗口模式，如果想要使用全屏模式在继承构造函数时改变mFullScreenState为true.  
大概流程：  
`try{if(!initialize())return 0; return run())}`  
差不多这样叭，文件是没有写注释的（笑  
有任何问题可以联系，，，但是还是找别人做的更好的叭owo  
e-mail:aaron_jsc@163.com  

# 错误代码及信息：  
- Attach Clipper Failed：关联裁剪器失败，请联系有DirectDraw开发经验的人员。  
- Back Buffer Surface Creat Failed：后备表面创建失败，请联系有DirectDraw开发经验的人员。  
- Blt Failed：Blt执行失败，这个问题只会在窗口模式下出现，如果出现请尝试覆写Update函数禁用Blt或手动Blt。  
- BkBuffer SetClipper failed：后备缓冲裁剪器设置失败，请尝试覆写InitDDraw函数来禁用裁剪器或者联系有DirectX开发经验者寻求帮助。  
- Clipper Attach falied：裁剪器未设置成功，请尝试覆写InitDDraw函数来禁用裁剪器或者联系有DirectX开发经验者寻求帮助。  
- CreateWindow Failed：窗口创建失败，请联系有Windows程序开发经验的开发人员。  
- DD Creat Failed：DirectDraw对象创建失败，请检查SDK文件版本或联系有相关开发经验的开发人员。  
- Flip blocked：交换链交换失败，这个错误只会在全屏模式中出现，造成这个错误的问题未知且开发过程中未遇到此问题。如果出现请尝试启用窗口模式。  
- InitDD Failed：DirectDraw初始化失败，请检查InitDDraw方法是否正常运行。  
- InitWindow Failed：窗口初始化失败，请检查InitMainWindow方法是否正常运行。  
- Null instance：没有实例，请检查程序是否被分配实例句柄或联系有Windows程序开发经验的开发人员。  
- Primary Surface Creat Failed：设主表面创建错误，请联系有DirectDraw开发经验的人员。  
- RegisterClass Failed.：窗口注册失败，请联系有Windows程序开发经验的开发人员。  
- SetClipList Failed：裁剪序列设置出错，请尝试覆写InitDDraw函数来禁用裁剪器或者联系有DirectX开发经验者寻求帮助。  
- Set Coop Level Failed：设置协作等级出错，请联系有DirectDraw开发经验的人员。  
- SetDisplayMode Error：设置显示模式错误，请联系有DirectDraw开发经验的人员。  
- Unlock Falied：DirectDraw表面解锁失败，请检查Update方法是否正常运行。  

