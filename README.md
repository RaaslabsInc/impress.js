impress.js
=========
修订版
----------------
项目需要，添加了 onenter 和 onleave 两个 Callback 加载点

使用示例
----------------
直接添加属性 onenter 或 onleave，页面加载时会触发 step-enter 中的脚本，页面跳出前加载 step-leave

    <div class="step" onenter="alert('in');" step-leave="alert('out')">
        <p>by <b class="positioning">positioning</b>, <b class="rotating">rotating</b> and <b class="scaling">scaling</b> them on an infinite canvas</p>
    </div>

LICENSE
---------

Copyright 2011-2012 Bartek Szopka

Released under the MIT and GPL Licenses.


