# temporal-rvl

## How to Use Temporal RVL in Your Project
- Copy rvl.h and trvl.h inside cpp/src into your project.
- Include those header files in your code.
- Write code using run_trvl() in cpp/src/main.cpp as reference. It has a lot of lines for profiling, so I don't recommend directly copying it.

## How to Run Code in cpp
- Install OpenCV using vcpkg (as a submodule of this repository).
- Put depth stream files inside the data folder. They can be downloaded from https://drive.google.com/open?id=1r1OzFwxAsiOSXbqZhRjX6s_4F2TDfnr3.
- Run CMake using folder cpp.
- Run the code!

## How to Run the RStudio Project (with the data from the above step)
- You can use paper-result.csv from the output folder, which contains the data I used.
- You can also use a csv file you made by yourself. Tweak the filepath of read_csv in temporal-rvl.Rmd.