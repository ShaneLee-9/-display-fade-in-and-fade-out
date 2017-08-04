### display实现淡入淡出过渡效果
1. 给img设置display和opacity
1. JS代码**显示效果**中，先执行display:block，再执行opacity，才能实现，所以要给opacity设置setTimeout，让opacity延迟执行，延迟时间尽量设置最小，这样才最自然
1. **隐藏效果**中，跟**显示效果**执行顺序相反，先执行opacity，再延迟执行display:none。
***PS：隐藏效果中，setTimeout延迟时间不能太短，否则会造成隐藏过渡在一半就直接display:none了***
<h1><font color="red">djsfkjdskaf</font></h1>
