# Game Boy emulator
<link rel="stylesheet" type="text/css" href="/css/style.css">

First approaching to emulators, reinforcing modularity, low-spec targets and runtime agnostic. 


## Day X: [14/03/2022]

### Testing

- The repo is currently private, however, it has been quite difficult to scalate the software. The byte loads instrucctions are supported by the core. In order to control how the next steps are integrated, avoiding any conflicts, a test suite is necessary.

- The test suite has to be scalable. The required components are: emulator executable, test binary, support scritps (build, run, check, ...) and expected results. 

- At this point the emulator executable requires modifications to produces output data to check the results.

- Any test requires a binary, the rom software, and a expected result. After the any execution the produced results have to be compared to the expected ones. 

- To reinforce the scalability the auto-generation, of any components, has to be considered. 

- The expected results have to include a snapshot of the core at specific time, that snapshot can be splited in registers and memory. 

