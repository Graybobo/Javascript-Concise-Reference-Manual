## java.* 属性

表示 java.* 包层级的 JavaPackage

### 语法:

  ```javascript
  java
  ```

### 说明:

在包含了 LiveConnect 或其他用于脚本化 Java 的技术的 JavaScript 实现中，全局 java 属性就是一个 JavaPackage 对象，它表示 java.* 包层级。这个属性的存在意味着像 java.util 这样的一个 JavaScript 表示式引用的是 java.util 包。对于不符合 java.* 层级的 Java 包，请参阅全局 Packages 属性。
