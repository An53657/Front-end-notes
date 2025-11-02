# Day15-d5-移动web-响应式网页

## 1. 响应式
1. 媒体查询
   - 格式
   ```
   @media (媒体查询){
    选择器 {
        样式
    }
   }
   ```

   - 媒体特征
     - max-width:最大宽度
     - min-width:最小宽度

     ![媒体查询-完整写法](../../imgs/html-css/Day15/01-媒体查询-完整写法.png)
     ![媒体查询-媒体媒体类型](../../imgs/html-css/Day15/02-媒体查询-完整写法-媒体类型.png)
     ![媒体查询-媒体特性](../../imgs/html-css/Day15/0-媒体查询-完整写法-媒体特性.png)
     
2. 书写顺序
    - min-width:(从小到大)
    - max-width:(从大到小)

3. 媒体查询 - 外部css
   - 语法
     ```
     <link rel="stylesheet" media="逻辑符 媒体类型 and (媒体特性)" href="XX.css">
     注意
        - 逻辑符和媒体特性可以不写
     ```

## 2. Bootstrap框架 
4. Bootstrap - 简介
   - Bootstrap框架是由Twitter公司开发维护分前端框架，它提供了大量编好的CSS样式，
     允许开发者结合一定HTML和JavaScript,快速编写功能完善的网页及常见交互效果

5. 使用步骤
   - 引入Bootsteap CSS 文件
   ```
   <link rel="stylesheet" herf="路径">
   ```

   - 调用类名
     ```
     <div class="container">测试</div>
     ```