# Trapping Rain Water – Java Solution
This Java program solves the classic Trapping Rain Water problem using prefix maximum arrays.

## Input
An array of non-negative integers representing elevation heights.

## Output
Total amount of trapped rainwater between bars.

## Sample
*Input:* [4, 2, 0, 6, 3, 2, 5]  
*Output:* 11

## How it works
- Calculates max height on left and right for each index.
- Water at each bar = min(leftMax, rightMax) - current height.
