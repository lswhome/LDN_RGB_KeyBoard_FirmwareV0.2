﻿李大拿的键盘固件V0.2说明
=====================
LDN_RGB_KeyBoard_FirmwareV0.2-help
=====================
李大拿的键盘固件V0.2的帮助文件，各种设置功能的说明和例子等等，我不懂英文，所以英文的是使用谷歌翻译的，国际友人凑合看吧。<br>
LDN keyboard firmware V0.2 help files, descriptions and examples of various settings functions, etc., I don't know English, so English is to use Google Translate, international friends can make it look.
****
Editor:LDN<br>
[返回主目录](https://github.com/lswhome/LDN_RGB_KeyBoard_FirmwareV0.2-help "点击返回")
****
## 按键灯(轴灯)配置
   * 轴灯背光目前支持14个固定背光（0为关闭，1-14为固定的背光），8个自定义背光（固定背光灯效之后的8个编号为自定义背光，目前编号为15开始的为自定义背光）
   * RGB三个颜色通道独立可调
   * CAPS SCROLL NUM三个指示灯，可以选择任意一颗轴灯或者氛围灯(WS2812/SK6812)作为指示器
   * 可调整灯效的运行速度
   * 个别灯效还可以调整运行参数
   #### 配置界面
   ![](https://github.com/lswhome/LDN_RGB_KeyBoard_FirmwareV0.2-help/blob/master/KeyLedCfg/Bkl_Man.png)
   * 1-> 调整三个颜色通道的电流增益，从而改变亮度和色温，调整完毕点击“应用”后立即生效
   * 2-> 调整轴灯灯效：
     * 灯效切换：一格表示一个灯效，0表示关闭轴灯灯效，调整后点击确定立即生效
     * 灯效速度：用以调整当前灯效的运行速度，每个灯效都可以单独调整，调整后点击确定生效
     * 灯效参数：有的灯效可以调整运行参数，通过调整这个参数可以改变，调整后点击确定生效
     * 上一个灯效，点击立即切换到上一个灯效
     * 下一个灯效，点击立即切换到下一个灯效
   * 3-> 开启：表示启用CAPS指示灯的指示器功能，打勾表示启用
   * 4-> 使用轴灯指示：表示CAPS指示灯使用轴灯来指示状态
   * 5-> 使用WS2812指示：表示CAPS指示灯使用氛围灯（WS2812，SK6812）来指示状态
   * 6-> 应用：设置完毕，最后点击立即生效
   * 7-> 选择指示用的灯珠：如果选择轴灯来指示，点击后会弹出一个键盘的键位布局图，单击某个按键即可选择那个按键的轴灯作为指示器；如果是选择WS2812作为指示器，则会弹出一个窗口，编号从0-31的按钮，点击一个，即可选择那个编号的氛围灯作为指示器；**轴坐标**会指示当前使用哪个灯珠作为指示器
   * 8-> 有4个灯效可选，单击即可选择
   * 9-> 跟随轴灯灯效：如果选择了这个功能，则忽略选择的4种灯效，当状态灯点亮的时候，会自动跟随轴灯点亮和熄灭
   * 10-> 如果选择了指定颜色，则单击这里，可以选择一个颜色作为指示器的颜色
   * **SCROLL NUM**的配置方法相同     
   
   [返回主目录](https://github.com/lswhome/LDN_RGB_KeyBoard_FirmwareV0.2-help "点击返回")
         
         
   
