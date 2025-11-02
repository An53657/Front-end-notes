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