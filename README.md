# proxy-pattern
代理模式    
"代理模式"：用一个对象来代表另一个对象。
    
例子：    
1. “远程代理” remote proxy: 用本地对象来代表远程对象。RPyC程序库就是一个例子。    
2. “虚代理” virtual proxy: 用轻量级对象来代表复杂对象，只在确有必要时才会真正去创建或操作那个复杂对象。   
3. “保护代理” protection proxy: 根据客户端的访问权限来确定不同的访问级别。    
4. “智能引用” smart reference:  performs additional actions when the obeject is accessed.         (也可通过描述符来实现，例如用@property修饰符，以属性来取代普通对象)  
5. “模拟对象” mock object 单元测试：设置stub来表示缺失的方法。    
