
# 让页面适应不同尺寸的屏幕

  Responsive 响应式：媒体查询 @media

    1、头部设置

     ```html
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     ```

    2、使用媒体查询规则

      ```css
      @media only screen and (max-width: 500px) {
          body {
              background-color: lightblue;
          }
        }
      ```


    尺寸规则设置：max-width、min-width
    屏幕方向规则设置：orientation: landscape(水平方向)、orientation: portrait（垂直方向）
