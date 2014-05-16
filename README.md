# nemo-drivex


Selenium webdriver extensions for Nemo automation framework. Wraps around node-ppuser (https://github.paypal.com/NodeTestTools/node-ppuser)

## Installation

1. Please install nemo to your project as described here: https://github.paypal.com/NodeTestTools/nemo/blob/master/README.md
2. Add this plugin to your package.json dev dependencies ("nemo-user": "0.0.1")
3. npm install

## API




<h3 class="subsection-title">Methods</h3>

<dl>

<dt>
<h4 class="name" id="allDisabled"><span class="type-signature"></span>allDisabled<span class="signature">(elements)</span><span class="type-signature"> &rarr; {Promise}</span></h4>


</dt>
<dd>


<div class="description">
Determine if all WebElements in elements array are disabled
</div>







<h5>Parameters:</h5>


<table class="params">
<thead>
<tr>

<th>Name</th>


<th>Type</th>





<th class="last">Description</th>
</tr>
</thead>

<tbody>


<tr>

<td class="name"><code>elements</code></td>


<td class="type">


<span class="param-type">Array</span>



</td>





<td class="description last">array of WebElements</td>
</tr>


</tbody>
</table>


<h5>Returns:</h5>


<div class="param-desc">
promise resolves to true or Error
</div>



<dl>
<dt>
Type
</dt>
<dd>

<span class="param-type">Promise</span>


</dd>
</dl>




</dd>



<dt>
<h4 class="name" id="allDisplayed"><span class="type-signature"></span>allDisplayed<span class="signature">(elements)</span><span class="type-signature"> &rarr; {Promise}</span></h4>


</dt>
<dd>


<div class="description">
Determine if all WebElements in elements array are visible
</div>







<h5>Parameters:</h5>


<table class="params">
<thead>
<tr>

<th>Name</th>


<th>Type</th>





<th class="last">Description</th>
</tr>
</thead>

<tbody>


<tr>

<td class="name"><code>elements</code></td>


<td class="type">


<span class="param-type">Array</span>



</td>





<td class="description last">array of WebElements</td>
</tr>


</tbody>
</table>



<h5>Returns:</h5>


<div class="param-desc">
promise resolves to true or Error
</div>



<dl>
<dt>
Type
</dt>
<dd>

<span class="param-type">Promise</span>


</dd>
</dl>




</dd>



<dt>
<h4 class="name" id="allEnabled"><span class="type-signature"></span>allEnabled<span class="signature">(elements)</span><span class="type-signature"> &rarr; {Promise}</span></h4>


</dt>
<dd>


<div class="description">
Determine if all WebElements in elements array are enabled
</div>







<h5>Parameters:</h5>


<table class="params">
<thead>
<tr>

<th>Name</th>


<th>Type</th>





<th class="last">Description</th>
</tr>
</thead>

<tbody>


<tr>

<td class="name"><code>elements</code></td>


<td class="type">


<span class="param-type">Array</span>



</td>





<td class="description last">array of WebElements</td>
</tr>


</tbody>
</table>






<h5>Returns:</h5>


<div class="param-desc">
promise resolves to true or Error
</div>



<dl>
<dt>
Type
</dt>
<dd>

<span class="param-type">Promise</span>


</dd>
</dl>




</dd>



<dt>
<h4 class="name" id="allHidden"><span class="type-signature"></span>allHidden<span class="signature">(elements)</span><span class="type-signature"> &rarr; {Promise}</span></h4>


</dt>
<dd>


<div class="description">
Determine if all WebElements in elements array are hidden
</div>







<h5>Parameters:</h5>


<table class="params">
<thead>
<tr>

<th>Name</th>


<th>Type</th>





<th class="last">Description</th>
</tr>
</thead>

<tbody>


<tr>

<td class="name"><code>elements</code></td>


<td class="type">


<span class="param-type">Array</span>



</td>





<td class="description last">array of WebElements</td>
</tr>


</tbody>
</table>


<h5>Returns:</h5>


<div class="param-desc">
promise resolves to true or Error
</div>



<dl>
<dt>
Type
</dt>
<dd>

<span class="param-type">Promise</span>


</dd>
</dl>




</dd>




<dt>
<h4 class="name" id="find"><span class="type-signature"></span>find<span class="signature">(locator, el)</span><span class="type-signature"> &rarr; {Promise}</span></h4>


</dt>
<dd>


<div class="description">
wraps Selenium WebDriver/WebElement.findElement
</div>







<h5>Parameters:</h5>


<table class="params">
<thead>
<tr>

<th>Name</th>


<th>Type</th>





<th class="last">Description</th>
</tr>
</thead>

<tbody>


<tr>

<td class="name"><code>locator</code></td>


<td class="type">


<span class="param-type"><a href="#LocatorJSON">LocatorJSON</a></span>



</td>





<td class="description last"></td>
</tr>



<tr>

<td class="name"><code>el</code></td>


<td class="type">


<span class="param-type">WebElement</span>



</td>





<td class="description last"></td>
</tr>


</tbody>
</table>



<h5>Returns:</h5>


<div class="param-desc">
resolves to WebElement or rejected
</div>



<dl>
<dt>
Type
</dt>
<dd>

<span class="param-type">Promise</span>


</dd>
</dl>




</dd>



<dt>
<h4 class="name" id="finds"><span class="type-signature"></span>finds<span class="signature">(locator, el)</span><span class="type-signature"> &rarr; {Promise}</span></h4>


</dt>
<dd>


<div class="description">
wraps Selenium WebDriver/WebElement.findElements
</div>







<h5>Parameters:</h5>


<table class="params">
<thead>
<tr>

<th>Name</th>


<th>Type</th>





<th class="last">Description</th>
</tr>
</thead>

<tbody>


<tr>

<td class="name"><code>locator</code></td>


<td class="type">


<span class="param-type"><a href="#LocatorJSON">LocatorJSON</a></span>



</td>





<td class="description last"></td>
</tr>



<tr>

<td class="name"><code>el</code></td>


<td class="type">


<span class="param-type">WebElement</span>



</td>





<td class="description last"></td>
</tr>


</tbody>
</table>


<h5>Returns:</h5>


<div class="param-desc">
resolves to an array of WebElements or rejected
</div>



<dl>
<dt>
Type
</dt>
<dd>

<span class="param-type">Promise</span>


</dd>
</dl>




</dd>



<dt>
<h4 class="name" id="oneDisplayed"><span class="type-signature"></span>oneDisplayed<span class="signature">(elements)</span><span class="type-signature"> &rarr; {Promise}</span></h4>


</dt>
<dd>


<div class="description">
determine if only one of the WebElements in the elements array is visible
</div>







<h5>Parameters:</h5>


<table class="params">
<thead>
<tr>

<th>Name</th>


<th>Type</th>





<th class="last">Description</th>
</tr>
</thead>

<tbody>


<tr>

<td class="name"><code>elements</code></td>


<td class="type">


<span class="param-type">Array</span>



</td>





<td class="description last">array of WebElements</td>
</tr>


</tbody>
</table>









<h5>Returns:</h5>


<div class="param-desc">
promise resolves to single visible element from "elements" or Error
</div>



<dl>
<dt>
Type
</dt>
<dd>

<span class="param-type">Promise</span>


</dd>
</dl>




</dd>



<dt>
<h4 class="name" id="present"><span class="type-signature"></span>present<span class="signature">(locator, el)</span><span class="type-signature"> &rarr; {Promise}</span></h4>


</dt>
<dd>


<div class="description">
wraps Selenium WebDriver/WebElement.isElementPresent
</div>







<h5>Parameters:</h5>


<table class="params">
<thead>
<tr>

<th>Name</th>


<th>Type</th>





<th class="last">Description</th>
</tr>
</thead>

<tbody>


<tr>

<td class="name"><code>locator</code></td>


<td class="type">


<span class="param-type"><a href="#LocatorJSON">LocatorJSON</a></span>



</td>





<td class="description last"></td>
</tr>



<tr>

<td class="name"><code>el</code></td>


<td class="type">


<span class="param-type">WebElement</span>



</td>





<td class="description last"></td>
</tr>


</tbody>
</table>











<h5>Returns:</h5>


<div class="param-desc">
resolves to true or rejected
</div>



<dl>
<dt>
Type
</dt>
<dd>

<span class="param-type">Promise</span>


</dd>
</dl>




</dd>



<dt>
<h4 class="name" id="waitForElement"><span class="type-signature"></span>waitForElement<span class="signature">(locator, timeout)</span><span class="type-signature"> &rarr; {Promise}</span></h4>


</dt>
<dd>


<div class="description">
Wait for timeout milliseconds for the WebElement to be present
</div>







<h5>Parameters:</h5>


<table class="params">
<thead>
<tr>

<th>Name</th>


<th>Type</th>





<th class="last">Description</th>
</tr>
</thead>

<tbody>


<tr>

<td class="name"><code>locator</code></td>


<td class="type">


<span class="param-type"><a href="#LocatorJSON">LocatorJSON</a></span>



</td>





<td class="description last"></td>
</tr>



<tr>

<td class="name"><code>timeout</code></td>


<td class="type">


<span class="param-type">Number</span>



</td>





<td class="description last"></td>
</tr>


</tbody>
</table>



<h5>Returns:</h5>


<div class="param-desc">
resolves to true or rejected
</div>



<dl>
<dt>
Type
</dt>
<dd>

<span class="param-type">Promise</span>


</dd>
</dl>




</dd>

</dl>

<h3 class="subsection-title">Special Objects</h3>
<a name="LocatorJSON"></a>
<dl>

<dt>
<h4 class="name" id="LocatorJSON">LocatorJSON</h4>


</dt>
<dd>



<h5>Type:</h5>
<ul>
<li>

<span class="param-type">object</span>


</li>
</ul>



<dl class="details">


<h5 class="subsection-title">Properties:</h5>

<dl>

<table class="props">
<thead>
<tr>

<th>Name</th>


<th>Type</th>





<th class="last">Description</th>
</tr>
</thead>

<tbody>


<tr>

<td class="name"><code>locator</code></td>


<td class="type">


<span class="param-type">string</span>



</td>





<td class="description last">a locator string, such as "[value='US']" or "#countrySelect"</td>
</tr>



<tr>

<td class="name"><code>type</code></td>


<td class="type">


<span class="param-type">string</span>



</td>





<td class="description last">corresponds to one of the Selenium Locator strategies (id, name, xpath, css)</td>
</tr>


</tbody>
</table></dl>






















</dl>



</dd>

</dl>







