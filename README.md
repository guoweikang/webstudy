webstudy
========

# Tools
*  code [IntelXDK](https://software.intel.com/en-us/intel-xdk)
*  [W3C validators tools](http://w3c.github.io/developers/tools/)
*  [codepen](https://codepen.io/)
*  [jsbin](http://jsbin.com/degiwagini/edit?html,output)


# HTML
* HTML5 First line <br/>
`<!DOCTYPE html>`
* You should always use the Unicode character encoding UTF-8 for your web pages <br/>
 ` <meta charset="utf-8">` <br/>
 ` <meta http-equiv="Content-Type" content="text/html; charset=utf-8">`
* HTML character references<br/>
<table>
    <tr>
      <th >显示结果</th>
      <th >描述</th>
      <th >实体名称</th>
      <th >实体编号</th>
    </tr>
    <tr>
      <td>&nbsp;</td>
      <td>空格</td>
      <td>&amp;nbsp;</td>
      <td>&amp;#160;</td>
    </tr>
    <tr>
      <td>&#60;</td>
      <td>小于号</td>
      <td>&amp;lt;</td>
      <td>&amp;#60;</td>
    </tr>
    <tr>
      <td>&gt;</td>
      <td>大于号</td>
      <td>&amp;gt;</td>
      <td>&amp;#62;</td>
    </tr>
    <tr>
      <td>&amp;</td>
      <td>和号</td>
      <td>&amp;amp;</td>
      <td>&amp;#38;</td>
    </tr>
    <tr>
      <td>&quot;</td>
      <td>引号</td>
      <td>&amp;quot;</td>
      <td>&amp;#34;</td>
    </tr>
    <tr>
      <td>'</td>
      <td>撇号&nbsp;</td>
      <td>&amp;apos; (IE不支持)</td>
      <td>&amp;#39;</td>
    </tr>
    <tr>
      <td>￠</td>
      <td>分（cent）</td>
      <td>&amp;cent;</td>
      <td>&amp;#162;</td>
    </tr>
    <tr>
      <td>&pound;</td>
      <td>镑（pound）</td>
      <td>&amp;pound;</td>
      <td>&amp;#163;</td>
    </tr>
    <tr>
      <td>&yen;</td>
      <td>元（yen）</td>
      <td>&amp;yen;</td>
      <td>&amp;#165;</td>
    </tr>
    <tr>
      <td>&euro;</td>
      <td>欧元（euro）</td>
      <td>&amp;euro;</td>
      <td>&amp;#8364;</td>
    </tr>
    <tr>
      <td>§</td>
      <td>小节</td>
      <td>&amp;sect;</td>
      <td>&amp;#167;</td>
    </tr>
    <tr>
      <td>&copy;</td>
      <td>版权（copyright）</td>
      <td>&amp;copy;</td>
      <td>&amp;#169;</td>
    </tr>
    <tr>
      <td>&#174;</td>
      <td>注册商标</td>
      <td>&amp;reg;</td>
      <td>&amp;#174;</td>
    </tr>
    <tr>
      <td>&trade;</td>
      <td>商标</td>
      <td>&amp;trade;</td>
      <td>&amp;#8482;</td>
    </tr>
    <tr>
      <td>×</td>
      <td>乘号</td>
      <td>&amp;times;</td>
      <td>&amp;#215;</td>
    </tr>
    <tr>
      <td>÷</td>
      <td>除号</td>
      <td>&amp;divide;</td>
      <td>&amp;#247;</td>
    </tr>
</table>
*  [OTHER chaacter]( https://dev.w3.org/html5/html-author/charref)

* Short quot  or long quote<br/>
&lt;q&gt;nihao &lt;/q&gt; : &quot;nihao&quot;<br/>
&lt;blockquote&gt; nihao&lt;/blockquote&gt; :Begin a new line and add  margin

* list <br/>
&lt;ol&gt;&lt;/ol&gt; <br/>
&lt;ul&gt;&lt;/ul&gt;<br/>
&lt;li&gt;&lt;/li&gt;

* pre <br/>
这是另一个标签，可以帮助您打破空白规则。 PRE代表“PREformatted text”，意思是“我已经按照我想要的方式设置了它，不要混淆它”。 它通常意味着等宽字体，并且不会忽略空格，制表符或回车符。 说明一些程序代码或其他“打字”材料非常方便：

* attribute key value <br/>
属性键值对唯一的例外就是值是boolean，如果添加该属性，表示真，如果没有，表示false

* list ol attribute <br/> 
reversed:序列倒序，如果设置了start 不起作用<br/> 
start: 指定起始序列号 值始终为数字<br/> 
type：1 A a I i 规定序列号格式

* global attributes or non global attributes<br/> 
There is global attribute [here](https://www.w3.org/wiki/HTML/Attributes/_Global)<br/> 
<ol>
 <li> contenteditable:Specifies whether the contents of the element are editable. </li>
 <li> accesskey: 以下元素支持 accesskey 属性：&lt;a&gt;, &lt;area&gt;, &lt;button&gt;, &lt;input&gt;, &lt;label&gt;, &lt;legend&gt;以及 &lt;textarea&gt; </li>
 <li>  lang ：lang 属性在以下标签中无效：&lt;base>, &lt;br&gt;, &lt;frame&gt;, &lt;frameset&gt;, &lt;hr&gt;, &lt;iframe&gt;, &lt;param&gt; 以及 &lt;script&gt;。</li>
  <li>  data-* ：data-* 属性用于存储页面或应用程序的私有自定义数据。<br/>
data-* 属性赋予我们在所有 HTML 元素上嵌入自定义 data 属性的能力。<br/>
存储的（自定义）数据能够被页面的 JavaScript 中利用，以创建更好的用户体验（不进行 Ajax 调用或服务器端数据库查询）。<br/>
data-* 属性包括两部分：<br/>
属性名不应该包含任何大写字母，并且在前缀 "data-" 之后必须有至少一个字符<br/>
属性值可以是任意字符串<br/>
注释：用户代理会完全忽略前缀为 "data-" 的自定义属性。</li>
 <li> dir: 属性规定元素内容的文本方向 ltr rtl<br/>
<b> 提示和注释 </b> <br/>
注释：dir 属性在以下标签中无效：&lt;base&gt;, &lt;br&gt;, &lt;frame&gt;, &lt;frameset&gt;, &lt;hr&gt;, &lt;iframe&gt;, &lt;param&gt; 以及 &lt;script&gt;。 </li>
 <li> draggable ：  属性规定元素是否可拖动。 <br/>
<b>提示</b>：链接和图像默认是可拖动的。<br/>
<b>提示</b>：draggable 属性常用在拖放操作中。请在我们的拖放教程中学习更多内容。<br/>

`` <element draggable="true|false|auto"> `` </li>

<li> hidden： 规定元素是否隐藏 <br/>
hidden 属性也可用于防止用户查看元素，直到匹配某些条件（比如选择了某个复选框）。然后，JavaScript 可以删除 hidden 属性，以使此元素可见。

`` <element hidden> ``
</li>

</ol>



# CSS
hello
# JS
__hello__








