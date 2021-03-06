# 注释

| 类型     | 形式              |
| :------- | :---------------- |
| 单行注释 | // 注释内容       |
| 多行注释 | /\* 注释内容 \*/  |
| 文档注释 | /\*\*注释内容 \*/ |

# 标识符

### 规则

- 必须是以字母、下划线\_、美元符号\$开头
- 其他部分可以是字母、下划线\_、美元符号\$和数字的任意组合
- 大小写敏感，长度无限制
- 不可以是 java 关键字

* 不建议使用汉字来定义标识符

### 常用命名规范

| 类型       | 规范                                                       |
| :--------- | :--------------------------------------------------------- |
| 类名       | 每个单词的首字母大写,如 OrderDetail                        |
| 方法、变量 | 驼峰写法。第一个单词首字母小写，从第二个单词开始首字母大写 |

# 变量

| 类型               | 初始化             | 声明位置            | 作用域      | 生命周期                                 |
| :----------------- | :----------------- | :------------------ | :---------- | :--------------------------------------- |
| 局部变量           | 使用前，必须初始化 | 方法/语句块内       | 方法/语句块 | 从声明位置开始，直到方法或语句块执行完毕 |
| 成员变量(实例变量) | 默认初始化         | 类内部，方法外部    | 对象        | 随对象创建而创建，消失而消失             |
| 静态变量(类变量)   | 默认初始化         | 类内部，static 修饰 | 类          | 随类创建而创建，消失而消失               |

# 常量

- 关键字 final 定义

# 数据类型

### 基本数据类型

| 类型     | 占用存储空间 |
| :------- | :----------- |
| 整数类型 |
| byte     | 1 字节       |
| short    | 2 字节       |
| init     | 4 字节       |
| long     | 8 字节       |
| 浮点类型 |
| float    | 4 字节       |
| double   | 8 字节       |
| 字符型   |
| char     | 2 字节       |
| 布尔型   |
| boolean  | 1 个比特位   |

### 引用类型

- 统一为 4 个字节
