# Derby Electronic Dictionary

#### 介绍
An electronic English Chinese dictionary based on the Apache Derby embedded database, with a GUI developed using the Java Swing framework.

基于Apache Derby嵌入式数据库的电子英汉词典，GUI基于Java Swing框架开发。

#### 软件功能
1. 查询单词：输入一个单词，查询得到单词的音标、释义、例句。
2. 词汇表：使用表格展示数据库中的所有单词，可以按字典序对单词进行排序。
3. 随机单词：点击查询按钮随机抽取一个单词，抽取后单词的音标、释义、例句并不会立即展示，用户可以回忆该单词的音标、释义、例句，然后点击展示按钮展示该单词的音标、释义、例句。用户可以使用该功能复习单词。
4. 添加单词：将一个新的单词及其音标、释义、例句写入数据库。
5. 修改单词：修改数据库中某个已存在的单词。修改前需要先读取该单词。
6. 删除单词：删除数据库中某个单词。删除单词前将弹出确认对话框，以防止误操作。
