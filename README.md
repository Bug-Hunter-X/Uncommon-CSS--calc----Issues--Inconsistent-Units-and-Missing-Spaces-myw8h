# Uncommon CSS `calc()` Issues
This repository demonstrates two uncommon issues that can arise when using the `calc()` function in CSS.  The first issue is related to inconsistent units within the calculation, which can lead to unpredictable results depending on the screen size or context. The second issue involves forgetting to include spaces around the operators in the `calc()` expression, which can result in parsing errors.

## Issue 1: Inconsistent Units
Using different units (e.g., `%` and `px` or `rem` and `em`) within a single `calc()` expression can lead to unexpected layout behavior. The browser's interpretation of these mixed units may not be consistent across different environments or screen sizes.

## Issue 2: Missing Spaces Around Operators
The `calc()` function requires spaces around the plus (+), minus (-), multiplication (*), and division (/) operators.  Omitting these spaces can cause the calculation to fail and result in the CSS property not being applied correctly.

## Solutions
The provided solution demonstrates the correct usage of `calc()` by ensuring consistent units and including necessary spaces.  Always double-check your units and spacing within `calc()` to avoid unexpected behavior.