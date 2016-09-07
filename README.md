*** This branch is for ISAAC test ***

You should install the isaac first then can run the test case as:

```
  ./build/staging/test-correctness --gtest_filter=*GEMV*:-MultipleQueues*
  ./build/staging/test-correctness --gtest_filter=*GEMM*:-MultipleQueues*
```

