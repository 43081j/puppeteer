<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [ExecutionContext](./puppeteer.executioncontext.md) &gt; [frame](./puppeteer.executioncontext.frame.md)

## ExecutionContext.frame() method

<b>Signature:</b>

```typescript
frame(): Frame | null;
```
<b>Returns:</b>

[Frame](./puppeteer.frame.md) \| null

The frame associated with this execution context.

## Remarks

Not every execution context is associated with a frame. For example, workers and extensions have execution contexts that are not associated with frames.
