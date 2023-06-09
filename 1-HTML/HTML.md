# 前言

    本笔记为记录HTML技术的笔记

# 一、Web简介

## HTML简介

    1、文档声明(doctype)
        · 文档声明用来告诉浏览器当前网页的版本
        · html5的文档声明
            <!DOCTYPE html>
            <!doctype html>

    2、五大浏览器：
        Chrome谷歌、IE（EDGE）、Firefox火狐、Safari、欧朋浏览器

    3、Web标准：
        HTML：结构。页面元素和内容
        CSS：表现。网页元素的外观和位置等页面样式（比如颜色、大小等等）
        Javascript：行为。网页模型的定义与页面交互。

# 二、进制

    1、十进制：日常使用

        满十进一
        0 1 2 3 4 5 6 7 8 9 10 11 12 ...

    2、二进制：计算机底层的进制

        满二进一
        0 1 10 11 100 101 110 111

        扩展：
            所有数据在计算机底层都会以二进制的形式保存
            8bit = 1byte(字节)
            1024byte = 1kb(千字节)
            1024kb = 1mb(兆字节)
            1024mb = 1gb(吉字节)
            1024gb = 1tb(特字节)
            1024tb = 1pb

    3、八进制：很少用

        满八进一
        0 1 2 3 4 5 6 7 10 11

    4、十六进制：一般显示一个二进制数字时，都会转换为十六进制

        满十六进一
        0 1 2 3 4 5 6 7 8 9 A B C D E F 10 11 12 13
# 三、字符编码

    所有数据在计算机底层都会以二进制的形式保存，文字也一样
    所以一段文字在存储时，都要转换成二进制编码
    读取时，都要将编码转换为字符，
        编码
            - 将字符转为二进制码的过程
        解码
            - 将二进制码转为字符的过程
        字符集
            - 编码和解码所采用的规则称为字符集
        乱码问题
            - 如果编码和解码所采用的字符集不同就会出现乱码问题
        常见的字符集
            - ASCII 
            - ISO88591
            - GB2312
            - GBK
            - UTF-8（万国码）: The most common character set being used right now.现在最常用的字符集

# 四、Web标准的组成

    1、Web标准三个构成：

        HTML    结构    页面元素和内容
        CSS     表现    网页元素的外观和位置等页面样式
        Javascript 行为 网页模型的定义与页面交互

    2、HTML骨架结构：
        html标签：网页整体
        head标签：网页头部
        body标签：网页身体
        title标签：网页标题

    3、开发工具：VSCode、Webstorm、Sublime、Dreamweaver、Hbuilder等
        其中最常用的是VScode

    4、语法规范：注释、标签的构成、标签的关系
        ·注释：
            作用：帮助开发人员理解代码
                    浏览器解析会忽略所有注释
                    注释要求简单明了
                    注释还可以将一些不希望显示的内容隐藏
                    注释不能嵌套
        ·标签：
            结构图：开始标签 包裹内容 结束标签
                    <strong>  变粗    </strong>
        ·标签关系：
            ·嵌套关系(父子关系)
            ·并列关系(兄弟关系)

