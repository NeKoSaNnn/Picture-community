简单的按钮实验，初步实现上传图片

testOnly.html
实现点及待完善项：
1. 悬浮框弹出，仅仅以一个按钮示意，之后会和凯子导航栏合并
2. 选择图片并上传，但还没有后端支持，也还没有图片预览，之后会尝试添加
3. 有复选框，必须两个都选才能上传，这个判断后续会加上，目前默认无法提交图片
4. 标签填写，其中第一个为必填项，后面两个可选，同样判断后续会加上
5. 由于上传图片有两个地方需要用到，一个是用户上传图片贡献给图库系统，另一个是用户通过上传图片搜索相似图片，两者有略微不同目前暂时写了第一个。等第一个完善后，再适当修改加第二个并和凯子主页结合！

testOnly_2.html
实现点及待完善项：
1. 实现两个悬浮框，一个是上传图片到图库，另一个上传图片以搜索相似图片
2. 上传图片到图库的页面，进一步完善包括上传的判断（标签1不为空，图片格式为jpg，按钮两个都得选），上传图片有图片预览且当超出页面时会有下拉框
3. 上传图片以搜索相似图片，较简单，只有上传图片的按钮，提交的时候也有判断和上面类似
4. 两个页面都没有后端代码，也还没有和凯子的主页面结合，之后进一步完善！
注：以上两个html都需要配合库文件bootstrap.min.js以及jquery.min.js（具体同凯子发的）才能正常运行！
    后续会将html分开成css,html,js三个文件并尝试合并到原来大项目以及凯子做的主页面中！
