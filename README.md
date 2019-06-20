# Markdown

- **文本**
  - *加粗*  
    使用一对 双\*号 实现对文本内容加粗  
    It's very easy to make some words \*\*bold\*\*.  
    It's very easy to make some words **bold**.  
    
  - *斜体*  
    使用一对 \* 号 实现将文本内容改为斜体  
    It's easy to make other words \*italic\*,too.   
    It's easy to make other words *italic*,too.  
    
  - *划线*  
    使用一对 双~ 号 将需要划线内容括住  
    \~\~Hello,world !\~\~  
    ~~Hello,world !~~    
    
  - *超链接*  
    使用 \[文本\](链接) 的方式构造超链接  
    You can link to \[GitHub\](https://github.com)  
    You can link to [GitHub](https://github.com)  
    
  - *补充*  
    - 换行时，前一行末尾应保留两个空格，否则默认续行  
    - 显示特殊符号时，应使用转义符  
    - 符号与文本之间不要有空格
  
  
- **表单**  
  - *数字表示*  
  - *\* 号表示*  
    \* Hello world !  
    * Hello world !  
    
  - *多层表单*  
    \- How to use Markdown  
       \- Like this  
       \- And this  
     使用效果如此文所示(此文全文使用 Markdown 格式)  
     
  - *表格*  
    Zero | One | Two  
    ---|---|---  
    0 | 1 | 2  

Zero | One | Two  
---|---|---  
0 | 1 | 2  
  
  
- **图像**  
  使用 !\[image\](image_Link) 的方式插入图片  
  !\[皮卡丘\](https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=2820110229,1486209150&fm=27&gp=0.jpg)  
  ![皮卡丘](https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=2820110229,1486209150&fm=27&gp=0.jpg)  
  
  
- **标题 & 引用**  
  - *标题*  
    标题使用 1-6 个 # 号实现 1-6 级标题  
    \# 一级标题  
    \#\#\#\#\#\# 六级标题  
    # 一级标题  
    ###### 六级标题  
    
  - *引用*  
    使用 > 号实现引用的表示  
    \> To do injustice is more disgraceful than to suffer it.  
    \> -- Plato  
    > To do injustice is more disgraceful than to suffer it.
    > -- Plato  
  
  
- **代码块**  
  - *代码部分统一缩进 4 个空格*   
  
        def func(x):  
            if x:  
                return True  
                
  - *使用 三\`号 括住代码区 [位于 Tab 键上方]*  
    \`\`\`  
    def func(x):  
        if x:  
            return True  
    \`\`\`
    ```  
    def func(x):  
        if x:  
            return True  
    ```  
    
  - *若想代码区有语法高亮，则可以在第一行 三\`号 注明编程语言名称*  
    \`\`\`Python  
    def func(x):  
        if x:  
            return True  
    \`\`\`  
    ```Python  
    def func(x):  
        if x:  
            return True  
    ```  
