### Cubic Extension
This directory contains a reference GPU implementation of 
[Cubic Extension](https://codaprotocol.github.io/snark-challenge/problem-03-Cubic%20extension%20arithmetic.html). 


### Build
``` bash
./build.sh
```

### Generate Inputs
``` bash
./generate_inputs
```

### Run
For interpreting inputs in montgomery representation:
``` bash
./main compute inputs outputs
```

### Check results
``` bash
shasum outputs
```
