---
title: Custom Site Search Shortcuts
tags: [Chrome, Documentation, Safari, Site Search]
style: fill
color: db9356
background-color: 
description: Create shortcuts in your browsers for searching documentation
---

![Custom site search](/assets/posts/custom_site_search_shortcuts/custom_site_searh.gif){:class="img-responsive"}

Custom site searches allow you to search a particular url with a search term and this quick guide will show you how to create them for documentation such as Maya, MotionBuilder and Qt in Chrome and Safari.

## Chrome
![Chrome site search setup](/assets/posts/custom_site_search_shortcuts/chrome_site_search_setup.gif){:class="img-responsive"}
1. Navigate to your settings: chrome://settings/searchEngines
2. Add a new entry to the site search section
3. Give your custom site search a name
4. Add a shortcut word or phrase, you can use a non-alphanumeric character at the start to avoid accidentally triggering the custom site search when searching
5. Add the url to use for the custom site search and add %s to the url where you want your search term to be injected into the url

## Safari
![Safari site search setup](/assets/posts/custom_site_search_shortcuts/safari_site_search_setup.gif){:class="img-responsive"}
Out of the box safari does not support custom site searches, so you'll need to install an extension called Keyword search: https://apps.apple.com/gb/app/keyword-search/id1558453954

1. Click the Keyword search extension icon to open the extension.
2. Add a new entry
3. Give your custom site search a name
4. Add a shortcut word or phrase, you can use a non-alphanumeric character at the start to avoid accidentally triggering the custom site search when searching
5. Add the url to use for the custom site search and add @@@ to the url where you want

## Examples

{% capture tab_items %}
Chrome,https://help.autodesk.com/cloudhelp/2023/ENU/Maya-Tech-Docs/CommandsPython/%s.html <br> https://help.autodesk.com/cloudhelp/2023/ENU/Maya-Tech-Docs/Commands/%s.html
Safari,https://help.autodesk.com/cloudhelp/2023/ENU/Maya-Tech-Docs/CommandsPython/@@@.html <br> https://help.autodesk.com/cloudhelp/2023/ENU/Maya-Tech-Docs/Commands/@@@.html
{% endcapture %}
{% include elements/tab.html title="Maya Python and Mel Documentation" active="Chrome" %}
<br>
{% capture tab_items %}
Chrome,https://help.autodesk.com/cloudhelp/2023/ENU/MotionBuilder-SDK/py_ref/class_f_b_%s.html
Safari,https://help.autodesk.com/cloudhelp/2023/ENU/MotionBuilder-SDK/py_ref/class_f_b_@@@.html
{% endcapture %}
{% include elements/tab.html title="MotionBuilder Python Documentation" active="Chrome" %}
<br>

{% capture tab_items %}
Chrome,https://doc.qt.io/qtforpython-5/PySide2/QtCore/%s.html <br>https://doc.qt.io/qtforpython-5/PySide2/QtGui/%s.html <br>https://doc.qt.io/qtforpython-5/PySide2/QtWidgets/%s.html
Safari,https://doc.qt.io/qtforpython-5/PySide2/QtCore/@@@.html <br>https://doc.qt.io/qtforpython-5/PySide2/QtGui/@@@.html <br>https://doc.qt.io/qtforpython-5/PySide2/QtWidgets/@@@.html
{% endcapture %}
{% include elements/tab.html title="PySide2 Documentation" active="Chrome" %}