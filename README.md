impress.js
=========

修订版
----------------
项目需要，添加了 step-enter 和 step-leave 两个 Callback 加载点

使用示例
----------------
直接添加属性 step-enter 或 step-leave，页面加载时会触发 step-enter 中的脚本，页面跳出前加载 step-leave

    <div id="ing" class="step" data-x="3500" data-y="-850" data-rotate="270" data-scale="6" step-enter="alert('in');" step-leave="alert('out')">
        <p>by <b class="positioning">positioning</b>, <b class="rotating">rotating</b> and <b class="scaling">scaling</b> them on an infinite canvas</p>
    </div>

LICENSE
---------

Copyright 2011-2012 Bartek Szopka

Released under the MIT and GPL Licenses.


