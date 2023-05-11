Leapfrog is a 3D modeling software frequently used for developing conceptual site models at environmental remediation sites.
The data input for leapfrog must contain two duplicate columns for each analyte.
Column A is the result reported by the laboratory and Column B is the value that is used for the leapfrog model visualization.
If an analyte was not detected in Column A, the associated value in Column B must be 10% of the detection limit from column A.

This script takes cross tab formatted data, and transforms it into a format that can be used for the Leapfrog model input.