This Rust program illustrates how to divide two 256-bit vectors element-wise using AVX2 SIMD (Single Instruction, Multiple Data) instructions. 
The code divides integer vectors into floating-point numbers and then returns the results as integers.

## Overview
The given code does execute the following operations:
1. Conversion of AVX2 Vectors converts __m256i (256-bit integer vectors) to i64 arrays for convenient usage.
2. Element-wise Division divides each member of one vector by the corresponding element of another vector using floating-point arithmetic.
3. Result Conversion returns the result as a __m256i vector.
4. Example usage demonstrates how to use the function to divide two example vectors and print the results.

   ## Notes
   1. This code employs unsafe Rust to interface with low-level AVX2 instructions and perform type conversions. Make sure you understand the repercussions of employing unsafe code.
   2. The division process is conducted with floating-point precision and subsequently converted to integers, which may result in rounding mistakes.
   3. Consider alternate methodologies or algorithms for more accurate findings.
  
      git clone https://github.com/cypriansakwa/Element_wise_Division_Using_AVX2_SIMD_with_F64_Conversion.git
      cd Element_wise_Division_Using_AVX2_SIMD_with_F64_Conversion
