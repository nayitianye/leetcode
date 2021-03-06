#### 十进制整数的反码/Complement of Base 10 Integer
**难度：** 简单/Easy

**Question：** 

<p>Every non-negative integer <code>N</code>&nbsp;has a binary representation.&nbsp; For example,&nbsp;<code>5</code> can be represented as <code>&quot;101&quot;</code>&nbsp;in binary, <code>11</code> as <code>&quot;1011&quot;</code>&nbsp;in binary, and so on.&nbsp; Note that except for <code>N = 0</code>, there are no leading zeroes in any&nbsp;binary representation.</p>

<p>The <em>complement</em>&nbsp;of a binary representation&nbsp;is the number in binary you get when changing every <code>1</code> to a <code>0</code> and <code>0</code> to a <code>1</code>.&nbsp; For example, the complement of <code>&quot;101&quot;</code> in binary is <code>&quot;010&quot;</code> in binary.</p>

<p>For a given number <code>N</code> in base-10, return the complement of it&#39;s binary representation as a&nbsp;base-10 integer.</p>

<p>&nbsp;</p>

<ol>
</ol>

<div>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-1-1">5</span>
<strong>Output: </strong><span id="example-output-1">2</span>
<strong>Explanation: </strong>5 is &quot;101&quot; in binary, with complement &quot;010&quot; in binary, which is 2 in base-10.
</pre>

<div>
<p><strong>Example 2:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-2-1">7</span>
<strong>Output: </strong><span id="example-output-2">0</span>
<span id="example-output-1"><strong>Explanation: </strong>7 is &quot;111&quot; in binary, with complement &quot;000&quot; in binary, which is 0 in base-10.
</span></pre>

<div>
<p><strong>Example 3:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-3-1">10</span>
<strong>Output: </strong><span id="example-output-3">5</span>
<strong>Explanation: </strong>10 is &quot;1010&quot; in binary, with complement &quot;0101&quot; in binary, which is 5 in base-10.
</pre>

<p>&nbsp;</p>

<p><strong>Note:</strong></p>

<ol>
	<li><code>0 &lt;= N &lt; 10^9</code></li>
</ol>
</div>
</div>
</div>

------

**题目：** 
<p>每个非负整数&nbsp;<code>N</code>&nbsp;都有其二进制表示。例如，&nbsp;<code>5</code>&nbsp;可以被表示为二进制&nbsp;<code>&quot;101&quot;</code>，<code>11</code> 可以用二进制&nbsp;<code>&quot;1011&quot;</code>&nbsp;表示，依此类推。注意，除&nbsp;<code>N = 0</code>&nbsp;外，任何二进制表示中都不含前导零。</p>

<p>二进制的反码表示是将每个&nbsp;<code>1</code>&nbsp;改为&nbsp;<code>0</code>&nbsp;且每个&nbsp;<code>0</code>&nbsp;变为&nbsp;<code>1</code>。例如，二进制数&nbsp;<code>&quot;101&quot;</code>&nbsp;的二进制反码为&nbsp;<code>&quot;010&quot;</code>。</p>

<p>给定十进制数&nbsp;<code>N</code>，返回其二进制表示的反码所对应的十进制整数。</p>

<p>&nbsp;</p>

<ol>
</ol>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>5
<strong>输出：</strong>2
<strong>解释：</strong>5 的二进制表示为 &quot;101&quot;，其二进制反码为 &quot;010&quot;，也就是十进制中的 2 。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>7
<strong>输出：</strong>0
<strong>解释：</strong>7 的二进制表示为 &quot;111&quot;，其二进制反码为 &quot;000&quot;，也就是十进制中的 0 。
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>10
<strong>输出：</strong>5
<strong>解释：</strong>10 的二进制表示为 &quot;1010&quot;，其二进制反码为 &quot;0101&quot;，也就是十进制中的 5 。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>0 &lt;= N &lt; 10^9</code></li>
</ol>

