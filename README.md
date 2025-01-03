# Unexpected Height Calculation with calc() and vh in Media Queries

This repository demonstrates a subtle bug involving the use of `calc()` and the `vh` unit within CSS media queries. The issue highlights the order of operations when calculating heights using `calc()` within responsive design.

## Bug Description

The code attempts to dynamically adjust element height based on viewport height minus a fixed offset, using `calc(100vh - 100px)`. However, in certain responsive layouts, the calculation might produce unexpected results due to how media queries and `calc()` interact, leading to inaccurate height values. 

## Solution

The solution provides a more robust approach that handles the responsiveness more effectively, ensuring accurate height calculations across different viewport sizes.