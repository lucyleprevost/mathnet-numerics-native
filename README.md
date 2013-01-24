Native Providers for Math.NET Numerics
======================================
To use the native library:
1. Place the native library (i.e. MathNET.Numerics.MKL.dll) in the same directory as your application's executable.*
2. In your application code, set the value of `Control.LinearAlgebraProvider` to the native provider you are using. For example: `Control.LinearAlgebraProvider = new MathNet.Numerics.Algorithms.LinearAlgebra.Mkl.MklLinearAlgebraProvider();`

* The native library can also be placed in your current PATH or in the system PATH. However, it is much easier to just to place it in the same directory as the executable.