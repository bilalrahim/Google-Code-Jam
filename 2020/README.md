# Google-Code-Jam 2020<br>
<h2>Vestigium</h2> <br>

<h3>Problem</h3> <br>
<p>Vestigium means "trace" in Latin. In this problem we work with Latin squares and matrix traces. <br>
<br>
The trace of a square matrix is the sum of the values on the main <br>
diagonal (which runs from the upper left to the lower right).<br>
An N-by-N square matrix is a Latin square if each cell contains one of N <br>
different values, and no value is repeated within a row or a column. In this problem, we <br>
will deal only with "natural Latin squares" in which the N values are the integers between 1 and N.<br>
<br>
Given a matrix that contains only integers between 1 and N, we want to compute its trace and check whether it is a natural Latin square. To give some additional information, instead of simply telling us whether the matrix is a natural <br>
Latin square or not, please compute the number <br>
of rows and the number of columns that contain repeated values. <br>
</p>
<h3>Input</h3>
<br>
<p>The first line of the input gives the number of test cases, T. T test cases follow. Each starts with<br> 
a line containing a single integer N: the size of the matrix to explore. Then, N lines follow. The i-th of <br>
these lines contains N integers Mi,1, Mi,2 ..., Mi,N. Mi,j is the integer in the i-th row and j-th <br>
column of the matrix.<br>
<br>
</p>
<h3>Output</h3>
<br>
<p>For each test case, output one line containing Case #x: k r c, where <br>
x is the test case number (starting from 1), k is the trace of the matrix, r is<br> 
the number of rows of the matrix that contain repeated elements, and c is the number of columns of<br> 
the matrix that contain repeated elements.<br>
</p>