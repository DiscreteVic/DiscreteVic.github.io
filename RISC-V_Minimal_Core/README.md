# RISC-V Minimal Core
<link rel="stylesheet" type="text/css" href="/css/style.css">

Page where the development of the RISC-V minmal core based on Computer organization and design RISC-V edition, [(Github project)](https://github.com/DiscreteVic/RISC-V-minimal-core).

## Day 1: [25/11/2024]

### Building a Datapath - Register File

- Following the book mentioned above, the first part is build the data path, in a single cycle mode (the pipeline will come after). And the first part of the Data path is the register file ([commit](https://github.com/DiscreteVic/RISC-V-minimal-core/commit/1b87704ab9d8966ae78004c4da8fd2f958c1b25d)). Just implemented, not tested.


## Day 2: [26/11/2024]

### Building a Datapath - Register File

- Register file tested! ([commit](https://github.com/DiscreteVic/RISC-V-minimal-core/commit/c7f71b39862c3feba26ed59152792a3cb19dd103)).

- First draft of sigle cycle datapath.
![Draft 1 Single cycle datapath](/assets/datapath1.jpg)


## Day 3: [30/11/2024]

### Building a Datapath - ALU

- ALU module created and tested! ([commit](https://github.com/DiscreteVic/RISC-V-minimal-core/commit/18a0a301750d7814b20bb60344f26afe5a4b9452)).



## Day 4: [02/12/2024]

### Building a Datapath - Primitives blocks

- In order to be the most independet as possible of the implementation tools (IDE), the primitives blocks as muxs, adders and shifters, are going to be implemented in VHDL.
- Mux, adder and synchronous register implemented.([commit](https://github.com/DiscreteVic/RISC-V-minimal-core/commit/d351468cd8dd86422986a9e54dcfaef72e810144)).




