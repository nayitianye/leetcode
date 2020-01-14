#### 翻转对/Reverse Pairs
**难度：** 困难/Hard

**Question：** 

<p>Given an array <code>nums</code>, we call <code>(i, j)</code> an <b><i>important reverse pair</i></b> if <code>i &lt; j</code> and <code>nums[i] &gt; 2*nums[j]</code>.</p>

<p>You need to return the number of important reverse pairs in the given array.</p>

<p><b>Example1:</b>
<pre>
<b>Input</b>: [1,3,2,3,1]
<b>Output</b>: 2
</pre></p>

<p><b>Example2:</b>
<pre>
<b>Input</b>: [2,4,3,5,1]
<b>Output</b>: 3
</pre></p>

<p><b>Note:</b><br>
<ol>
<li>The length of the given array will not exceed <code>50,000</code>.</li>
<li>All the numbers in the input array are in the range of 32-bit integer.</li>
</ol>
</p>

------

**题目：** 
<p>给定一个数组&nbsp;<code>nums</code>&nbsp;，如果&nbsp;<code>i &lt; j</code>&nbsp;且&nbsp;<code>nums[i] &gt; 2*nums[j]</code>&nbsp;我们就将&nbsp;<code>(i, j)</code>&nbsp;称作一个<strong><em>重要翻转对</em></strong>。</p>

<p>你需要返回给定数组中的重要翻转对的数量。</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入</strong>: [1,3,2,3,1]
<strong>输出</strong>: 2
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入</strong>: [2,4,3,5,1]
<strong>输出</strong>: 3
</pre>

<p><strong>注意:</strong></p>

<ol>
	<li>给定数组的长度不会超过<code>50000</code>。</li>
	<li>输入数组中的所有数字都在32位整数的表示范围内。</li>
</ol>
