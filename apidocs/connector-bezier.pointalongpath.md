<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@jsplumb/connector-bezier](./connector-bezier.md) &gt; [pointAlongPath](./connector-bezier.pointalongpath.md)

## pointAlongPath() function

finds the point that is 'distance' along the path from 'location'. this method returns both the x,y location of the point and also its 'location' (proportion of travel along the path); the method below - \_pointAlongPathFrom - calls this method and just returns the point.

TODO The compute length functionality was made much faster recently, using a lookup table. is it possible to use that lookup table find a value for the point some distance along the curve from somewhere?

<b>Signature:</b>

```typescript
export declare function pointAlongPath(curve: Curve, location: number, distance: number): PointOnPath;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  curve | [Curve](./connector-bezier.curve.md) |  |
|  location | number |  |
|  distance | number |  |

<b>Returns:</b>

[PointOnPath](./connector-bezier.pointonpath.md)
