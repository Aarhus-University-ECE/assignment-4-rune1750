Pre-requisits: 
- Visual Studio and Visual Studio Code (VSC)
- CMake 
- ..

Within VSC press ctrl+shit+p to open command prompt. Type
```bash
cmake configure 
```
This will configure your build directory. Usually required one-time only.

Then use 
```bash
cmake build
```
to build the files. When you made changes you need to "re-build" to include the changes.

Afterwards to run tests type 
```bash
ctest
```

Submit your solutions via the assignment on brightspace, Week 3. Please make
sure to submit your solutions by next Monday. If an exercise requires you to write C
code, then create a new C file (i.e. do not combine exercises into a single C file).  
