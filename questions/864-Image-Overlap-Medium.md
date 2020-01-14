#### 图像重叠/Image Overlap
**难度：** 中等/Medium

**Question：** 

<p>Two images <code>A</code> and <code>B</code> are given, represented as&nbsp;binary, square matrices of the same size.&nbsp; (A binary matrix has only 0s and 1s as values.)</p>

<p>We translate one image however we choose (sliding it left, right, up, or down any number of units), and place it on top of the other image.&nbsp; After, the <em>overlap</em> of this translation is the number of positions that have a 1 in both images.</p>

<p>(Note also that a translation does <strong>not</strong> include any kind of rotation.)</p>

<p>What is the largest possible overlap?</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input: </strong>A = [[1,1,0],
            [0,1,0],
&nbsp;           [0,1,0]]
&nbsp;      B = [[0,0,0],
&nbsp;           [0,1,1],
&nbsp;           [0,0,1]]
<strong>Output: </strong>3
<strong>Explanation:</strong> We slide A to right by 1 unit and down by 1 unit.</pre>

<p><strong>Notes:</strong>&nbsp;</p>

<ol>
	<li><code>1 &lt;= A.length = A[0].length = B.length = B[0].length &lt;= 30</code></li>
	<li><code>0 &lt;=&nbsp;A[i][j], B[i][j] &lt;= 1</code></li>
</ol>


------

**题目：** 
<p>给出两个图像 <code>A</code> 和 <code>B</code>&nbsp;，<code>A</code> 和 <code>B</code>&nbsp;为大小相同的二维正方形矩阵。（并且为二进制矩阵，只包含0和1）。</p>

<p>我们转换其中一个图像，向左，右，上，或下滑动任何数量的单位，并把它放在另一个图像的上面。之后，该转换的重叠是指两个图像都具有 1 的位置的数目。</p>

<p>（请注意，转换不包括向任何方向旋转。）</p>

<p>最大可能的重叠是什么？</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入：</strong>A = [[1,1,0],
          [0,1,0],
&nbsp;         [0,1,0]]
&nbsp;    B = [[0,0,0],
&nbsp;         [0,1,1],
&nbsp;         [0,0,1]]
<strong>输出：</strong>3
<strong>解释:</strong> 将 A 向右移动一个单位，然后向下移动一个单位。</pre>

<p><strong>注意:</strong>&nbsp;</p>

<ol>
	<li><code>1 &lt;= A.length = A[0].length = B.length = B[0].length &lt;= 30</code></li>
	<li><code>0 &lt;=&nbsp;A[i][j], B[i][j] &lt;= 1</code></li>
</ol>
