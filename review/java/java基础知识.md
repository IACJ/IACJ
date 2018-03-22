# Java基础知识

## 第一季 入门知识
### 变量和常量
* 关键字
* 标识符
* 变量
* 数据类型
    * 基本数据类型 (byte、short、int、long、float、double、char、boolean)
    * 引用数据类型
    - 自动类型转换 (向下兼容)
    - 强制类型转换
* 常量 (final、大写)
* 注释 (单行注释、多行注释、文档注释)
### 常见运算符
* 运算符
    * 算数运算符 (+、-、*、/、%、++、--)
    * 赋值运算符 (=、+=、-=、*=、/=、%=)
    * 比较运算符 (>、<、>=、<=、==、!=)
    * 逻辑运算符 (&&、||、!、^)(短路)
    * 条件运算符 (?:)
    - 运算符的优先级
### 流程控制语句
* if...else...
* switch
* while
* do...while...
* for
* break
* continue
### 输入 Scanner
~~~java
Scanner scanner = new Scanner(System.in);
int score = scanner.nextInt();
~~~
### 数组
* 长度 arr.length
* 使用 Arrays 类操作 Java 中的数组
* foreach ( for (int score : scores ) )
* 二维数组
### 方法
* 定义方法
* 参数
* 返回值
* 重载

## 第二季 继承、封装、多态
### 类和对象
* 类
* 对象
* 成员变量和局部变量
* 构造方法
* static
    - 静态变量
    - 静态方法
    - 静态初始化块
### 封装
* 什么是封装
* 包管理
* 访问修饰符
* 内部类
    - 成员内部类
    - 静态内部类
    - 方法内部类 (由于方法内部类不能在外部类的方法以外的地方使用，因此方法内部类不能使用访问控制符和 static 修饰符。)
    - 匿名内部类
### 继承
* Java中的继承
* 方法重写
* 继承初始化顺序 （先父后子）
* final 的使用
* Object 类
    - toString
    - equals
    - hashCode
### 多态
* Java中的多态
    - 引用多态
    - 方法多态
* 多态中的引用类型转换 (instanceof)
* 抽象类 (abstract)
* 接口 (public abstract)
    - 匿名内部类