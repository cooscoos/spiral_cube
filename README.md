# Spiral to Cube

Rust code to convert spiral coordinates for a hexagon grid to cube coordinates (q,r,s) and vice versa.

Mapping from spiral to cube coordinates makes use of a truncated triangule wave whose amplitude and period grows with each progressive step outwards from the origin.

spiral_to_cube_demo.ipynb shows some of the maths behind this in a visual way.

These may help you write your own scripts in other languages if you're not familiar with Rust.