{{target:partial-label-desc}}

图形上的文本标签，课用于说明图形的一些数据信息，比如值，名称等，`label`选项在 ECharts 2.x 中放置于`itemStyle.normal`下，在 ECharts 3 中为了让整个配置项结构更扁平合理，`label`被拿出来跟 `itemStyle` 平级，并且跟 `itemStyle` 一样拥有 `normal`, `emphasis` 两个状态。当然老的写法也依旧是兼容的


{{target:partial-label}}

#${prefix} textStyle

标签的字体样式

{{ use:partial-text-style(prefix=${prefix} + '#') }}

{{target:partial-optional-label-position}}

可选：
+ [percentage, percentage]

    通过百分比表示标签相对于图形包围盒左上角的位置。

+ "top"
+ "left"
+ "right"
+ "bottom"
+ 'inside'
+ 'insideLeft'
+ 'insideRight'
+ 'insideTop'
+ 'insideBottom'
+ 'insideLeftTop'
+ 'insideLeftBottom'
+ 'insideRightTop'
+ 'insideRightBottom'