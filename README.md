# multiprocessor
mplementing a simulator, in C language, for a system that includes a main memory structure and 4 independent cores that work in parallel. The cores share a bus to "snoop" the main memory and on
each core. Each core owns a 5 stage pipe: fetch, decode, execute, memory and write back. The memory stage was implemented
according to MSI coherence protocol. The system was tested by
programs in assembly.
The following picture demontrates the aforementioned system:
![multicores_system](https://user-images.githubusercontent.com/70822357/116921418-a3341400-ac5c-11eb-959a-aa62ffab09c3.PNG)
