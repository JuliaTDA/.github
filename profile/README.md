# JuliaTDA: Topological Data Analysis in Julia

> Topologists of the world, unite!

JuliaTDA is an organization that aims to reunite many packages related to Topological Data Analysis.

## Why Julia?

Why choose Julia over more popular languages like R and Python? Some reasons can be find [here](https://juliadatascience.io/programmers), but in short: 
it is easy to write math in Julia, it solves the "2 language problem" and we can write very performant code with little effort. 
Besides that, Julia packages can easily be used by R and Python using R's [JuliaCall](https://github.com/Non-Contradiction/JuliaCall) and 
Python's [juliacall](https://pypi.org/project/juliacall/).

## Packages

For datasets usual in topology:
- [GeometricDatasets.jl](https://github.com/JuliaTDA/GeometricDatasets.jl)

For clustering and graph-reducing algorithms, we have 
- [TDAmapper.jl](https://github.com/JuliaTDA/TDAmapper.jl): Mapper-like algorithms for clustering and graph-reducing high-dimensional data;
- [ToMATo.jl](https://github.com/JuliaTDA/ToMATo.jl) [to do]: the ToMATo clustering algorithm from [reference].

For persistent homology, there are 
- [Ripserer.jl](https://github.com/mtsch/Ripserer.jl): calculate the Vietoris-Rips filtration and homology, among other things;
- [PersistenceDiagrams.jl](https://github.com/mtsch/PersistenceDiagrams.jl): create persistence images from persistence diagrams.

Very useful packages to deal with distances, balls, clustering, proximity, etc.:

- [Distances.jl](https://github.com/JuliaStats/Distances.jl)
- [NearestNeighbors.jl](https://github.com/KristofferC/NearestNeighbors.jl)
- [Clustering.jl](https://github.com/JuliaStats/Clustering.jl)
