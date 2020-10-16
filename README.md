2020-2021进阶版/项目班分班题目

1.文件操作
* 要求1:能够正常读出一个文件内的内容。
* 要求2:能够向文件内追加内容。
* 要求3:能够以二进制格式读取和保存CPP数据结构（pod类型)

2.虚函数
* 要求1:实现一个抽象类, 并定义多个子类实现纯虚函数。
* 要求2:利用父类指针调用子类的虚函数。


3.模板类
* 要求1: 该类为模板类，内部拿一个数据储存值
* 要求2: 定义默认构造函数, 拷贝构造函数, 析构函数, 赋值函数(重载=)
* 要求3: 实现取值,赋值(非重载),求和
* 要求4：结合虚函数实现类型擦除


4.CMakeLists(git导入库)
* https://github.com/libmozart/mozart
* 要求1:通过git将上述库导入自己的项目
* 要求2:编写CMakeLists.txt使下述代码能通过编译
```cpp
#include <string>
#include <mozart++/format>
using std::string;
int main() {
    auto str = mpp::format("hello {} ", 0.1 + 0.2);
    printf("%s\n", str.c_str());
    return 0;
}
```
    
Ps.  有一些要求不会的可以添加文档,将自己的想法写出来(没有知识点硬性的要求, 有一定的基础,剩下的同学我会花一定的时间来给大家补补缺失的基础,重点要展现出自己现在知识点的掌握情况)
要求3:通过git将上述题目发至我的repo里https://github.com/jin1xiao3long2/zrkc.git

教程: (https://blog.csdn.net/weixin_43851149/article/details/107283174?utm_medium=distribute.pc_aggpage_search_result.none-task-blog-2~all~sobaiduend~default-2-107283174.nonecase&utm_term=%E5%A6%82%E4%BD%95%E6%8F%90%E4%BA%A4%E4%BB%A3%E7%A0%81%E8%87%B3%E5%88%AB%E4%BA%BA%E7%9A%84%E4%BB%93%E5%BA%93&spm=1000.2123.3001.4430)
(如果不会使用git的请发至我的邮箱jola@covariant.cn)
