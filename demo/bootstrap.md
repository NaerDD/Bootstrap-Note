### 容器
  1. 流体容器

  2. 固定容器

      * 大于等于1200 (lg 大屏pc)          width置为1170 (1140+槽宽)

      * 大于992 小于1200(md 中屏pc)       width置为970 (940+槽宽)

      * 小于992 大于768(sm 平板)        width置为750 (720+槽宽)

      * 小于768(xs 移动手机)               width置为auto 

      * auto如果有padding pading在网页内 从auto里面扣

  3. 栅格系统
      1. 固定容器&流体容器的公共样式
          padding-right: 15px;
          padding-left: 15px;
          margin-right: auto;
          margin-left: auto;

      2. 固定容器
        * 顺序不可变
        @media (min-width: @screen-sm-min) {
        width: @container-sm;
        }
        @media (min-width: @screen-md-min) {
          width: @container-md;
        }
        @media (min-width: @screen-lg-min) {
          width: @container-lg;
        }

      3. 行
        margin-right: -15px;
        margin-left: -15px;

      4. 列
        