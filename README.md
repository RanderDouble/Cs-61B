# Cs-61B

## Java语言规范

```
public class Helloworld {  //任何代码都需要放在类中 主类名与文件名相同
    public static void main(String[] args) {  //自带命令行参数
        System.out.println("Hello, World!");  //输出方式不同
    }
}
```

**循环** (增强型for循环)

```
for(a : number)
```

**数组** 

`int[] a={1,2,3}` or `int[] a=new int[3]`  or `int[] a=new int[3]{1,2,3}`

数组自带length属性 `a.length == 3`

数组传递为整个对象

**字符串**

运算符重载`+`可为连接

某字符串`s.contains("horse")` 可查找horse并返回`true`or`false`

**函数**

属于类的函数通常被称为“方法”

