#这里是我的实验报告
####19302010084-程茜
##Github 地址和 Github Pages 地址
Github地址：[https://github.com/cx418y/Project1.git](https://github.com/cx418y/Project1.git)
Github Pages地址：[]()
##项目完成情况
整个pj主要参考了助教给出的网页实例截图，利用纯css进行排版，只有在浏览页国家与城市的二级联动和上传界面上传部分用了js。

- #####首页：
    - 导航栏：导航栏条目显示正确、点击导航栏条目跳转到对应页面、鼠标移动到导航条目上会出现样式变化、个人中心实现下拉菜单，菜单条目可点击可跳转、鼠标移动到下拉菜单的条目上显示高亮，下拉菜单的条目内容前需要有合适的图标、在不同的页面中导航栏显示相同，并且当前页面条目高亮
    - 图片展示：图片布局合理，每张图片都带有图片标题和图片描述的缩略版、点击图片后，跳转到相应图片的详情页
    - 页脚：展示版权信息以及喜好内容
    - 辅助图标：按钮随着页面的滑动始终固定在页面右下角、回到页面顶部按钮功能完成，图片刷新按钮有响应
- #####浏览页：
   - 搜索栏：能正确输入文字，点击搜索按钮有响应
   - 快速浏览栏：显示热门国家和热门城市，点击条目有响应
   - 筛选栏：点击筛选栏，出现下拉菜单，可以选择筛选条件、国家与城市筛选实现二级联动
   - 图片展示：图片布局合理，保证大小一致、点击图片后，跳转到相应图片的详情页
- #####搜索页：
   - 筛选栏：两个搜索按钮可以选择其中一个进行搜索、能正确输入文字，点击搜索按钮有响应
   - 图片展示：每一项结果的左边是缩略图，右边是标题和描述，标题与描述有区分、搜索结果排布整齐，正确
描述文字中，多行文字溢出显示省略号、点击图片后，跳转到相应图片的详情页
- #####上传界面：
   - 上传部分：可以从本地选择图片进行上传、未上传图片时显示提示文字，上传完成后在页面内显示图片
   - 输入部分：用户可以输入图片标题、图片描述、拍摄国家、拍摄城、用户点击下方的提交按钮有响应，提交成功后跳转到我的照片界面
- #####我的照片：
   - 图片展示：图片展示部分与搜索页的四条要求相同、修改按钮和删除按钮布局合理并且有响应
- #####我的收藏：
   - 图片展示：图片展示部分与搜索页的四条要求相同、删除按钮布局合理并且有响应
- #####图片详情页：
   - 图片展示：该页面需要展示图片、图片标题、拍摄者、图片描述、主题、拍摄国家、拍摄城市、布局合理，展示美观、展示该照片已被收藏的数量，并有一个收藏按钮，点击有响应。
- #####登录注册界面：
   - 图片展示：注册表单中可以填写用户名、邮箱、密码、确认密码、登录表单中可以填写用户名、密码、密码和确认密码部分不得显示明文，点击登录 / 注册能够跳转到 主页 / 登陆界面、登陆界面有引导注册提示信息并可以正常跳转

##Bonus完成情况
- 图片裁剪：
   - 完成情况：所有界面中均使用的normal文件夹中的照片自由排版
   - 解决办法：先在**图片外部加一个div**，设置div的大小（相对于外部框或者相对于可视窗口的大小），在将图片的宽和高设置为该div宽和高的**百分比**，之后在css中将img的**objice-fit**属性设置为**cover**，将图片的内容在保持其宽高比的同时填充元素的整个内容框。如果对象的宽高比与内容框不相匹配，该对象将被剪裁以适应内容框。并将overflow属性设置为hidden。

- 响应式布局：
   - 解决办法：在网页代码头部加上viewport元标签；所有的框结构都是用的相对大小，没有使用绝对大小；字体也设置的相对大小
   
