
## Mesh Diagnostics

```
$ checkMesh -allGeometry -allTopology -writeSurfaces -surfaceFormat vtk -writeSets -setFormat vtk
```

Writes vtk files  into `postProcessing/checkMesh`

## Typical thresholds 


Non-orthogonality
- < 40 : Excellent
- < 60 : Good - 60–70 : Usually acceptable  
- 70 : Investigate 
Skewness - 
- < 2 : Excellent 
- 2–4 : Good 
- 4–8 : Acceptable 
- 8–10 : Marginal 
- > 10 : Investigate
