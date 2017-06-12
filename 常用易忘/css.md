* 超出隐藏

  ```css
  .text_hide{
    white-space:nowrap;
    text-overflow:ellipsis;
    overflow:hidden;
  }
  ```

* 多行超出隐藏(只适用于谷歌)

  ```css
  .text2_hide{
    display:-webkit-box;
    -webkit-line-clamp:2;
    -webkit-box-orient:vertical;
    word-wrap:break-word;
    overflow:hidden;
    -webkit-box-pack:center;
  }
  ```

  ```
  .text2_hide{
    	text-overflow: ellipsis;
      display: -webkit-box;
      -webkit-line-clamp: 2;
      -webkit-box-orient: vertical;
      word-break: break-word;
  }
  ```

* 固定宽度内文字右侧对不齐

  ```css
  div{
    text-align: justify;
    text-justify: inter-ideograph;
  }
  ```

