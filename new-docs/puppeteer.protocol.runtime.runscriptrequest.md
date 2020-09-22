<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Runtime](./puppeteer.protocol.runtime.md) &gt; [RunScriptRequest](./puppeteer.protocol.runtime.runscriptrequest.md)

## Protocol.Runtime.RunScriptRequest interface

<b>Signature:</b>

```typescript
export interface RunScriptRequest 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [awaitPromise](./puppeteer.protocol.runtime.runscriptrequest.awaitpromise.md) | boolean | Whether execution should <code>await</code> for resulting value and return once awaited promise is resolved. |
|  [executionContextId](./puppeteer.protocol.runtime.runscriptrequest.executioncontextid.md) | [ExecutionContextId](./puppeteer.protocol.runtime.executioncontextid.md) | Specifies in which execution context to perform script run. If the parameter is omitted the evaluation will be performed in the context of the inspected page. |
|  [generatePreview](./puppeteer.protocol.runtime.runscriptrequest.generatepreview.md) | boolean | Whether preview should be generated for the result. |
|  [includeCommandLineAPI](./puppeteer.protocol.runtime.runscriptrequest.includecommandlineapi.md) | boolean | Determines whether Command Line API should be available during the evaluation. |
|  [objectGroup](./puppeteer.protocol.runtime.runscriptrequest.objectgroup.md) | string | Symbolic group name that can be used to release multiple objects. |
|  [returnByValue](./puppeteer.protocol.runtime.runscriptrequest.returnbyvalue.md) | boolean | Whether the result is expected to be a JSON object which should be sent by value. |
|  [scriptId](./puppeteer.protocol.runtime.runscriptrequest.scriptid.md) | [ScriptId](./puppeteer.protocol.runtime.scriptid.md) | Id of the script to run. |
|  [silent](./puppeteer.protocol.runtime.runscriptrequest.silent.md) | boolean | In silent mode exceptions thrown during evaluation are not reported and do not pause execution. Overrides <code>setPauseOnException</code> state. |
