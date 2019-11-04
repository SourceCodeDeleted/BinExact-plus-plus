# BinExact-plus-plus
Binexact++  - This is a plugin for IDA PRO that will product a diff between two functions in assembly. 

This is currently being re written to accomodate more than just one specific project.

In it's current state this works off a memory map. You supply the function name and address and size. This function will be compared with the assembly in the other function.
When you can compare assembly , you can see what is differing from the origional functon and therefore, you can alter your function's code to match the assembly of the origional code. 

Since this is being re written to make it more useable for others. Ultimately , I would like to remove the need for a memory map and have the size


![Image of Binexact++](https://github.com/SourceCodeDeleted/BinExact-plus-plus/blob/master/BinExact%2B%2B.PNG) 