![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg) ![](../../workflows/test/badge.svg) ![](../../workflows/fpga/badge.svg)

# 4 x 4 Multiplexer Design and Implementation

This lab focuses on designing and implementing a 4×4 array multiplier using manual structural design techniques. The objective is to create, in Verilog, a module called arraymultstructural that performs the multiplication of two 4-bit inputs, m and q, to produce an 8-bit output p, representing the product.

The provided test-bench file (arraymulttb.v) contains only the first two test cases, which are predefined. As part of this lab, you are responsible for generating inputs for test cases 3 through 10 to thoroughly validate the multiplier. This includes testing edge cases, such as multiplying by zero and handling maximum possible values.

In addition to designing the multiplier, the final report should include:

Waveform analysis: Show the signals' behavior during multiplication.
Testbench output: Demonstrate the results from the test cases.
Explanation of the "generate" statement: Provide insights into how the "generate" statement was used to streamline the array multiplier design in the second part of the lab, highlighting its role in simplifying repetitive structures.
This project demonstrates proficiency in structural Verilog design, with a focus on optimization and verification through comprehensive testing.

- [Read the documentation for project](docs/info.md)

