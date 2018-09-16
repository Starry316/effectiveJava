# 第三章 
## 总览
本章介绍了一些对象通用方法的注意事项
1. equals的通用约定
2. 覆盖equals的注意事项
3. 覆盖toString的必要性
4. 覆盖clone时需要注意的地方
5. Comparable接口的使用

## equals方法的通用约定
  equals方法应实现等价关系，即满足：
  - 自反性 自身等于自身
  - 对称性 x.equals(y) 与 y.equals(x) 返回结果应该相同
  - 传递性 x.equals(y) y.equals(z)都为true时，x.equals(z)也应该为true
  - 一致性 只要对象没有被修改，那么多次比较的结果应该相同