## Compute Log — PR 4

==================================================
SYSTEM INFORMATION
==================================================
OS:         Windows 10
Version:    10.0.19045
Machine:    AMD64
Processor:  Intel64 Family 6 Model 142 Stepping 10, GenuineIntel
Python:     3.11.4 (tags/v3.11.4:d2340ef, Jun  7 2023, 05:45:37) [MSC v.1934 64 bit (AMD64)]

Benchmark 1 — sum(range(5,000,000))
  Result:  12,499,997,500,000
  Time:    0.1728 seconds

Benchmark 2 — list comprehension (n=1,000,000)
  First 5: [0, 1, 4, 9, 16]
  Time:    0.0658 seconds

Benchmark 3 — string join (n=100,000)
  Length:  588,889 characters

==================================================
SUMMARY
==================================================
  sum benchmark:    0.1728s
  list benchmark:   0.0658s
  ## RAM
Total RAM: 16 GB