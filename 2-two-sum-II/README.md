<h2><a href="https://leetcode.com/problems/two-sum-ii-input-array-is-sorted">Two Sum II </a></h2> <img src='https://img.shields.io/badge/Difficulty-Medium-orange' alt='Difficulty: Medium' /><hr>
Given a <strong>1-indexed</strong> array of integers <code>numbers</code> that is already <strong>sorted in non-decreasing order</strong>, find two numbers such that they add up to a specific <code>target</code>number. Let these two numbers be <code>numbers[index1]</code> and <code>numbers[index2]</code> where <code>1 <= index1 < index2 < numbers.length.</code>
Return the indices of the two numbers, <code>index1 </code>and <code>index2</code>, <strong>added by one </strong>as an integer array <code>[index1, index2]</code>  of length 2.

The tests are generated such that there is <strong>exactly one solution</strong>. You <strong>may not use </strong>the same element twice.

Your solution must use only constant extra space.

<p>&nbsp;</p>
<p><strong class="example">Example 1:</strong></p>
<pre>
<strong>Input:</strong> numbers = [2,7,11,15], target = 9
<strong>Output:</strong> [1,2]
<strong>Explanation:</strong> The sum of 2 and 7 is 9. Therefore, index1 = 1, index2 = 2. We return [1, 2].
</pre>

<p><strong class="example">Example 2:</strong></p>
<strong>Input:</strong> numbers = [2,3,4], target = 6
<strong>Output:</strong> [1,3]
<strong>Explanation:</strong> The sum of 2 and 4 is 6. Therefore index1 = 1, index2 = 3. We return [1, 3].
</pre>

<p>&nbsp;</p>
<p><strong class="example">Example 3:</strong></p>
<strong>Input:</strong> numbers = [-1,0], target = -1
<strong>Output:</strong> [1,2]
<strong>Explanation:</strong> The sum of -1 and 0 is -1. Therefore index1 = 1, index2 = 2. We return [1, 2].
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>2 <= numbers.length <= 3 * 104</code></li>
	<li><code>-1000 <= numbers[i] <= 1000</code></li>
    <li>numbers is sorted in<strong> non-decreasing order.</strong></li>
    <li><code>-1000 <= target <= 1000</code></li>
    <li>The tests are generated such that there is<strong> exactly one solution</strong></li>
	
</ul>
