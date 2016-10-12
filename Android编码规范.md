# Android 编码规范 #
## 基本要求 ##
1. 除了注释与strings.xml，代码中不允许出现中文。
2. 每个类上写上必要的注释：类的说明、作者、联系方式。

##  控件变量命名 ##
 - 小驼峰；
- 控件缩写+逻辑名称，例如：`tvPostTitle`、`etUserName`；
- 对应的控件的 id 的命名控件缩写_逻辑名称，单词均小写，用下划线连接，例如：`tv_post_title`、`et_user_name`；
- 控件缩写：
    
    控件 | 缩写
    ----- | ----
    Linearlayout | ll
    RelativeLayout | rl
    TextView | tv
    EditText | ed
    Button | btn
    ImageView | iv
    Spinner | spn
    RecyclerView | rv
    
## 布局资源文件(layout文件夹下)

全部小写，采用下划线命名法.

下面是一些比较常见的命名风格和含义

|布局类型| 命名风格 |
|-------|----------|
|Activity的xml布局|activity_+XX功能，如主页面activity_home|
|Fragment的xml布局|fragment_+XX功能，如联系人模块fragment_contacts|
|Dialog的xml布局|dialog_+XX功能，如选择日期dialog_select_date|
|抽取出来复用的xml布局（include）|include_+XX功能，如底部tab栏include_bottom_tabs|
|ListView或者RecyclerView的item xml布局|XX功能+_list_item，如联系人的contact_info_list_item|
|GridView的item xml布局|XX功能+_grid_item，如相册的album_grid_item|

    

    

