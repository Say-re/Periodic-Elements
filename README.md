# Periodic Elements - Constants JSON Collection
## Section 1 - Introduction
Static JSON collection of the elements on the periodic table. Elements are stored sequentially within an array in the JSON file.

*Attributes type description available to each element*
```
{
  atomicMass: number,
  atomicNumber: string,
  boilingPoint: {
    unitOfMeasurement: string,
    value: number,
  },
  category: string,
  commonName: string,
  density: {
    unitOfMeasurement: string,
    value: number,
  },
  discovery: string,
  electronConfiguration: Array<{
    shell: string,
    value: string,
  }>,
  generalState: string,
  group: string,
  meltingPoint: {
    unitOfMeasurement: string,
    value: number,
  },
  period: string,
  symbol: string,
}
```

