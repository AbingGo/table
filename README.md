# table




border-collapse共有三个值：border-collapse：separate | collapse | inherit

它们各自的含义是:

separate：

默认值。边框会被分开。不会忽略border-spacing 和 empty-cells 属性。

collapse：

如果可能，边框会合并为一个单一的边框。会忽略border-spacing 和 empty-cells 属性。

inherit：

规定应该从父元素继承border-collapse属性的值。

border-collapse的用途

border-collapse属性设置表格的边框是否被合并为一个单一的边框，还是象在标准的 HTML 中那样分开显示

border-collapse:collapse; 表示边框合并在一起。

border-collapse:separate;表示边框之间的间距，间距的大小用border-spacing: px;定义大小。
