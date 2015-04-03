---
title: WAI-ARIA Support
page_title: WAI-ARIA Support | UI for ASP.NET AJAX Documentation
description: WAI-ARIA Support
slug: treelist/accessibility-and-internationalization/wai-aria-support
tags: wai-aria,support
published: True
position: 4
---

# WAI-ARIA Support





## 

The __RadTreeList__ control offers __WAI-ARIA__ support which can be easily enabled by setting the __EnableAriaSupport__ server property to __true__.

RadTreeList ARIA attributes are __lower case__. They are shown in the table below.


>caption  

|  __Control__  |  __Attributes__  |
| ------ | ------ |
| __RadTreeList__ |aria-grabbedaria-dropeffectaria-levelaria-checkedaria-hiddenaria-haspopuprole:button (on pager)Enabled Aria for inner controls (where supported) in column editors etc.|

>note An issue with the use of WAI-ARIA in HTML documents is that they don’t validate. When you run a HTML document containing ARIA attributes through the W3C Validator it shows errors in the results for any ARIA attributes. The DOCTYPE declarations do not include any information about the WAI ARIA attributes and you cannot have a valid document which includes elements, attributes, and attribute values, not detailed in its DTD’s.
>


# See Also

 * [This functionality online](http://demos.telerik.com/aspnet-ajax/treelist/examples/waiariasupport/defaultcs.aspx)

 * [WAI-ARIA basic information](http://www.w3.org/WAI/intro/aria)