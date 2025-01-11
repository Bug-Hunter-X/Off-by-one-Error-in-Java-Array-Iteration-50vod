# Off-by-one Error in Java

This repository demonstrates a common off-by-one error in Java when iterating over an array.  The error occurs because the loop condition `i <= array.length` should be `i < array.length`.  This causes an attempt to access an index that is out of bounds, resulting in an `ArrayIndexOutOfBoundsException`. The solution provides the corrected code.