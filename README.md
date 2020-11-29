# Cache-Simulator
32-bit cache simulator 
uses least recently used replacement 
Usage: %s [-hv] -s <num> -E <num> -b <num> -t <file>\n
Options:
  -h         Print this help message.
  -v         Optional verbose flag.
  -s <num>   Number of s bits for set index.
  -E <num>   Number of lines per set.
  -b <num>   Number of b bits for block offsets.
  -t <file>  Trace file.
  Examples: 
  linux>  %s -s 4 -E 1 -b 4 -t traces/yi.trace
  linux>  %s -v -s 8 -E 2 -b 4 -t traces/yi.trace
