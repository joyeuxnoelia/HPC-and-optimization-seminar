Here we have an example of a command line using scalene: 

 ```
scalene --outfile qsim.html  --reduced-profile --cpu-sampling-rate 0.001  qsim.py
```

A list of usefull commands:

```

--cpu                             # profile CPU
--gpu                             # profile GPU
--memory                          # profile memory 
--cpu --gpu --memory              # profile everything (same as no options)

--reduced-profile                 # only profile lines with significant usage
--cpu-sampling-rate 0.001         # specify the sampling rate (for lines that take small times)
--use-virtual-time                #only report time spent in CPU (excluding time spent in I/O or blocking)

--cli                             # use the command-line only (no web interface)
--outfile qsim.txt                # creates an text file with the profiling 
--outfile qsim.html               # creates an html file with the profiling 

--help                            # lists all options

```

You can find exemples and more commands in this [link](https://coderzcolumn.com/tutorials/python/scalene-cpu-and-memory-profiler-for-python-code).
