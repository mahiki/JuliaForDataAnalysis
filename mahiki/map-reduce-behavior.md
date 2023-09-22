# Map and Reduce in Julia
kaminski book p 251

>what is the difference?

```jl
# docstrings are a great help
# reduce is dimension reducing
# map is elementwise operations of a single argument function

reduce(*, [2,3,4])
# 24

map(*, [2,3,4])
# 3-element Vector{Int64}:
#  2
#  3
#  4

    # its more clear with a single argument transformation:
map(isodd,[2,3,4])
# 3-element Vector{Bool}:
#  0
#  1
#  0



```