# Uninitialized Numeric Field in COBOL

This repository demonstrates a subtle bug in COBOL related to uninitialized numeric fields.  In COBOL, numeric fields are not automatically initialized to zero.  If you attempt to perform arithmetic operations on an uninitialized numeric field, the result will be unpredictable and can lead to errors that are difficult to track down. 

The `bug.cob` file shows the erroneous code. The `bugSolution.cob` file demonstrates the corrected code. 