<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [yoha](./yoha.md) &gt; [IEngineConfig](./yoha.iengineconfig.md)

## IEngineConfig interface

Engine configuration.

<b>Signature:</b>

```typescript
export interface IEngineConfig 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [flipX?](./yoha.iengineconfig.flipx.md) | boolean | <i>(Optional)</i> If true, mirrors the result coordinates ([IResultEvent.coordinates](./yoha.iresultevent.coordinates.md)<!-- -->) along the y axis. In other words, \[x, y\] becomes \[1 - x, y\]. |
|  [padding?](./yoha.iengineconfig.padding.md) | number | <i>(Optional)</i> Starting from the borders, removes a percentage of the analyzed track source.<!-- -->Example: A video with resolution 640x480 would yield landmark coordinates where \[0, 0\] and \[1, 1\] correspond to pixel values of \[1, 1\] and \[640, 480\] respectively.<!-- -->Setting padding to 0.05 would make \[0, 0\] and \[1, 1\] correspond to pixel values of \[640 \* 0.05, 480 \* 0.05\] and \[640 - 640 \* 0.05, 480 - 480 \* 0.05\] respectively. |
