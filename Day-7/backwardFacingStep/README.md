# Single processor

```sh
blockMesh
simpleFoam
```

# Multiple processor

```sh
blockMesh
decomposePar
mpirun -np 4 simpleFoam -parallel
reconstructPar
```