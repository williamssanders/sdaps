# sdaps_container
Singularity Container for SDAPS

## Usage:

1. Singularity-Hub:
```
singularity pull shub://williamssanders/sdaps:sdaps
./williamssanders-sdaps-master-sdaps.simg setup /fastscratch/ssander/sdaps/example_2 example.tex
```

2. Build the container:

```
sudo singularity build -c sdaps.simg Singularity.sdaps
./sdaps.simg setup /fastscratch/ssander/sdaps/example_1 example.tex
```
