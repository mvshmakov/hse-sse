# Formal Methods in SE tasks with `wish` and `Spin`

`spin` should be in path.

-   To simulate Spin process: `spin {filename}.pml`.
-   To simulate Spin process in interactive mode: `spin -i {filename}.pml`.
-   To compile and run verification: `spin -search -ltl p3 {filename}.pml`, or: `spin -a {filename}.pml; gcc -o pan pan.c; ./pan -a -N p1`.
-   To compile and run verification with BFS mode: `spin -search -bfs -ltl p3 {filename}.pml`.
