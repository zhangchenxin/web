## css颜色表示方法
- 英文单词表示颜色
- 16进制来表示
  - 以#开始,有六位值.前两位代表红色,中间两位代表绿色,最后表示蓝色
  - 取值范围是0~9 A~F
  - #000000代表黑色 #000
  - #ffffff代表白色 #fff
- 使用RGB模式来表示
  - 每一个值代表一种颜色(0~255)
- 带透明度RGBA
  - rgba(red, green, blue, alpha) 
  - alpha表示透明度,从0到1
##CSS文本设置
常用的应用文本的css设置
- color 设置字体颜色
- font-size 设置字体大小
- font-family  设置文字的字体
- font-style 字体是否倾斜(font-style:'normal'设置不倾斜)(font-style:'italic'设置倾斜)
- font-weight 加粗 (font-weight:bold;设置加粗)(font-weight:normal;设置不加粗)
- line-height 行高
- text-decoration 设置文字的下划线 text-decoration:none;将下划线取消
- text-indent 设置首行缩进
- text-align 设置文字水平对其方向 text-align:center 设置文字水平居中
##CSS边框属性
- border:宽度,样式,颜色;
- color
- border-style: 边框样式: soild 实线,dotted 点状线,dashed 虚线.
- border-top 单独设置上边框
- border-bottom 单独设置下边框
- border-left 单独设置左侧边框
- border-right 单独设置有边框
- border-radius 设置圆角
  - 只给一个圆角,是四个角都是
  - 给四个值,顺时针来一个一个设置圆角,第一个角是左上角
  - 给两个值,为对角.
  - box-shadow 阴影效果
    - x轴偏移 正右 负左
    - y洲 正上 负下
    - 模糊程度
    - 扩散范围
    - 阴影颜色
    - 是否为内阴影,是贼是insert,不设置默认外.
##背景项目
- background-image:url() 设置背景图片
- background-size :% % 设置图片大小
- background-position 设置图片位置.如果让图片向上或向左移动,都要设置为负值.前面是x坐标,下面为正坐标.
- background-repeat:no repeat 设置图片不重复.
- 背景一般组合写
