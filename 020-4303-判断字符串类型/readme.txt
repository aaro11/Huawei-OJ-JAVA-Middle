
描述:
根据一组规则识别一个特定的字符串是常见的计算机问题.

定义了如下三种字符串类型：

Slump是一串字符，具有如下性质：
    1.以'D'或'E'开始
    2.第一个字符后由1个或多个'F'
    3.之后跟着一个Slump或'G'，至此一个Slump结束。
    4.其他的都不是Slump
例如，DFFEFFFG是Slump
Slimp是一串字符，具有如下性质：
    1.第一个字符是'A'
    2.如果Slimp只有2个字符，则第二个字符是'H'
    3.如果大于2个字符，则可能有2种形式
        a) 'A'后接一个'B'再接一个Slimp再接一个'C'
        b) 'A'后接一个Slump再接一个'C'
    4.其他的都不是Slimp
Slurpy是一个Slimp后接一个Slump组成

请编写程序判断一个字符串是否为Slurpy




知识点:


题目来源:	 西研
维护人:	 d00191780
练习阶段:	 中级