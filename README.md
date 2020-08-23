
# Timerperf

I always care about performance when I write code. I also care about 
redability. How to deal with this tradeoff? Sometimes I prefer redability 
if the decrease in performance is not high enough, but it's not comfortable to 
look for the performance of each operation. So I decided to write a suite to 
evaluate the differences between different options, along with a set of handy 
notes sorted by topic.


# Setup

`timeperf` is written to not need more libraries than necessary. If you want to
perform the entire set of tests, you can install the dependencies listed in 
`requirements.txt` file by running:


```
$ pip install -r requirements.txt
```

Or you could create a virtual environment and install them on it:

```
$ mkvirtualenv timeperf
(timeperf) $ pip install -r requirements.txt
```


# Execution

To run the code you need to create one function for each operation that you
want to perform. Then you pass these functions as parameters for the `Runner` 
object to obtain the metrics.


# How is the code structured?

TODO


# Contribuiting

This is an open source project, so you are invited to add the measures you 
consider useful. The idea is to have a unified place to quickly search for the 
best ways to perform different operations.


# TODO

- Divide each measurement based on Python version? 