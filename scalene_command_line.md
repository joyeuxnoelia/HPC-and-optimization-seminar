Here we have an example of a command line using scalene: 
 
scalene --outfile qubits/depth40_qubits31_50reps-01.html  --reduced-profile --cpu-sampling-rate 0.001  qsim.py

A list of usefull commands:

```bash
scalene --cli your_prog.py                       # use the command-line only (no web interface)

scalene --cpu your_prog.py                       # only profile CPU
scalene --cpu --gpu your_prog.py                 # only profile CPU and GPU
scalene --cpu --gpu --memory your_prog.py        # profile everything (same as no options)

scalene --reduced-profile your_prog.py           # only profile lines with significant usage
scalene --profile-interval 5.0 your_prog.py      # output a new profile every five seconds

scalene (Scalene options) --- your_prog.py (...) # use --- to tell Scalene to ignore options after that point
scalene --help                                   # lists all options
```
