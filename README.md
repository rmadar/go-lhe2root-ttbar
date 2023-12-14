# LHE to ROOT file converter for ttbar events

Tool written in go to convert LHE files into ROOT files based on [gohep](https://github.com/go-hep).

### Output structure

The truth information is stored organized in different blocks :
 - initial state : {PID, Pz, helicity} for the 2 incoming particles/partons
 - final state : {pT, Eta, Phi, PID, M} for each of the final state particle (t, b, W, l, v)


### Usage
```
Usage of ./lhe2root:
  -f string
    	Path to the output ROOT file (default "output.root")
  -i string
    	Path to the input LHE file (default "ttbar_0j_parton.lhe")
  -t string
    	Name of the created TTree (default "truth")
  -v	Enable verbose mode
```


