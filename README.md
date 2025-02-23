# PHP Silent Array Key Access: Unexpected Null Values

This repository demonstrates a common yet subtle error in PHP: the silent handling of non-existent array keys.  Accessing an array element with a non-existent key results in a null value without an error, potentially leading to unexpected behavior and difficult-to-debug issues. The example shows how to avoid this pitfall by explicitly checking for keys before accessing their values.

## Bug

The `bug.php` file illustrates how accessing a non-existent array key returns null without any warning.

## Solution

The `bugSolution.php` file demonstrates how to address this problem using `isset()` or `array_key_exists()` to check for the key's existence before accessing the value, preventing unexpected null values.