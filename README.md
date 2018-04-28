# Notebook
#  1）实现用户注册和登录界面，用户注册信息存储在SQLite数据库中
#  2）支持用户新增、修改和删除日记，日记为纯文本，日记的内容存储在SQLite数据库中，数据库表应该至少包含创建日记的用户、日记标题，日记内容，日记的创建时间等信息。
#  3）以ListView的形式显示当前用户的日记列表，点击某一条记录，可以打开一个新的界面供用户查看、编辑日记。
#  4）在登录界面中，增加“记住密码”复选框，记住的用户密码存储在SharedPreferences中，若用户取消了“记住密码”复选框的选择，需要从SharedPreferences       中清除记录的用户名和密码
#  5）允许用户添加照片到日记中，方法是允许用户读取系统相册的内容，并将选中的照片拷贝到日记本应用程序的内部存储目录下，将照片文件名保存入数据库中       与对应的日记记录关联在一起。用户查看日记时也显示日记中包含的照片
