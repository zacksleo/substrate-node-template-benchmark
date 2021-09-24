# Substrate Node Template Benchmark

```bash
./target/release/node-template benchmark --chain dev --execution=wasm --wasm-execution=compiled --pallet pallet_template --extrinsic do_something --steps 50 --repeat 20
```

## Benchmark Results

```bah
Pallet: "pallet_template", Extrinsic: "do_something", Lowest values: [], Highest values: [], Steps: [50], Repeat: 20
Median Slopes Analysis
========
-- Extrinsic Time --

Model:
Time ~=    21.65
    + s        0
              µs

Reads = 0 + (0 * s)
Writes = 1 + (0 * s)
Min Squares Analysis
========
-- Extrinsic Time --

Data points distribution:
    s   mean µs  sigma µs       %
    0     22.02     0.151    0.6%
    2     21.58     0.081    0.3%
    4      21.7     0.094    0.4%
    6     21.63     0.077    0.3%
    8     21.69     0.087    0.4%
   10     21.57     0.097    0.4%
   12     21.74     0.126    0.5%
   14     21.62     0.125    0.5%
   16     21.68     0.089    0.4%
   18     21.63     0.059    0.2%
   20     21.67     0.065    0.2%
   22     21.66     0.143    0.6%
   24     21.61     0.067    0.3%
   26     21.69     0.089    0.4%
   28     21.59     0.081    0.3%
   30     21.68      0.07    0.3%
   32     21.62     0.053    0.2%
   34     21.69     0.094    0.4%
   36     21.66      0.11    0.5%
   38     21.62     0.055    0.2%
   40     21.68     0.064    0.2%
   42     21.59     0.092    0.4%
   44     21.56     0.123    0.5%
   46     21.62     0.112    0.5%
   48     21.54     0.041    0.1%
   50     21.62      0.12    0.5%
   52     21.59     0.142    0.6%
   54     21.65     0.074    0.3%
   56     21.59     0.049    0.2%
   58     21.65     0.118    0.5%
   60     21.84      0.09    0.4%
   62     21.64     0.067    0.3%
   64     21.64     0.058    0.2%
   66     21.82     0.102    0.4%
   68     21.72     0.086    0.3%
   70     21.68     0.094    0.4%
   72     21.65     0.096    0.4%
   74     21.72     0.047    0.2%
   76      21.7     0.114    0.5%
   78     21.72     0.063    0.2%
   80     21.75     0.059    0.2%
   82     21.73     0.085    0.3%
   84      21.7     0.055    0.2%
   86      21.6     0.047    0.2%
   88     21.72     0.062    0.2%
   90     21.71     0.068    0.3%
   92     21.53     0.054    0.2%
   94     21.66     0.117    0.5%
   96     21.65     0.054    0.2%
   98      21.6     0.052    0.2%
  100     21.79     0.084    0.3%

Quality and confidence:
param     error
s             0

Model:
Time ~=    21.66
    + s        0
              µs

Reads = 0 + (0 * s)
Writes = 1 + (0 * s)
```
