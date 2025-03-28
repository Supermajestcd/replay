[@puppeteer/replay](../README.md) / PuppeteerRunnerOwningBrowserExtension

# Class: PuppeteerRunnerOwningBrowserExtension

## Hierarchy

- [`PuppeteerRunnerExtension`](PuppeteerRunnerExtension.md)

  ↳ **`PuppeteerRunnerOwningBrowserExtension`**

## Table of contents

### Constructors

- [constructor](PuppeteerRunnerOwningBrowserExtension.md#constructor)

### Methods

- [afterAllSteps](PuppeteerRunnerOwningBrowserExtension.md#afterallsteps)
- [afterEachStep](PuppeteerRunnerOwningBrowserExtension.md#aftereachstep)
- [beforeAllSteps](PuppeteerRunnerOwningBrowserExtension.md#beforeallsteps)
- [beforeEachStep](PuppeteerRunnerOwningBrowserExtension.md#beforeeachstep)
- [runStep](PuppeteerRunnerOwningBrowserExtension.md#runstep)

## Constructors

### constructor

• **new PuppeteerRunnerOwningBrowserExtension**(`browser`, `page`, `opts?`)

#### Parameters

| Name            | Type      |
| :-------------- | :-------- |
| `browser`       | `Browser` |
| `page`          | `Page`    |
| `opts?`         | `Object`  |
| `opts.timeout?` | `number`  |

#### Inherited from

[PuppeteerRunnerExtension](PuppeteerRunnerExtension.md).[constructor](PuppeteerRunnerExtension.md#constructor)

#### Defined in

[PuppeteerRunnerExtension.ts:41](https://github.com/puppeteer/replay/blob/main/src/PuppeteerRunnerExtension.ts#L41)

## Methods

### afterAllSteps

▸ **afterAllSteps**(): `Promise`<`void`\>

#### Returns

`Promise`<`void`\>

#### Overrides

[PuppeteerRunnerExtension](PuppeteerRunnerExtension.md).[afterAllSteps](PuppeteerRunnerExtension.md#afterallsteps)

#### Defined in

[PuppeteerRunnerExtension.ts:366](https://github.com/puppeteer/replay/blob/main/src/PuppeteerRunnerExtension.ts#L366)

---

### afterEachStep

▸ `Optional` **afterEachStep**(`step`, `flow?`): `Promise`<`void`\>

#### Parameters

| Name    | Type                                           |
| :------ | :--------------------------------------------- |
| `step`  | [`Step`](../modules/Schema.md#step)            |
| `flow?` | [`UserFlow`](../interfaces/Schema.UserFlow.md) |

#### Returns

`Promise`<`void`\>

#### Inherited from

[PuppeteerRunnerExtension](PuppeteerRunnerExtension.md).[afterEachStep](PuppeteerRunnerExtension.md#aftereachstep)

#### Defined in

[RunnerExtension.ts:24](https://github.com/puppeteer/replay/blob/main/src/RunnerExtension.ts#L24)

---

### beforeAllSteps

▸ `Optional` **beforeAllSteps**(`flow?`): `Promise`<`void`\>

#### Parameters

| Name    | Type                                           |
| :------ | :--------------------------------------------- |
| `flow?` | [`UserFlow`](../interfaces/Schema.UserFlow.md) |

#### Returns

`Promise`<`void`\>

#### Inherited from

[PuppeteerRunnerExtension](PuppeteerRunnerExtension.md).[beforeAllSteps](PuppeteerRunnerExtension.md#beforeallsteps)

#### Defined in

[RunnerExtension.ts:20](https://github.com/puppeteer/replay/blob/main/src/RunnerExtension.ts#L20)

---

### beforeEachStep

▸ `Optional` **beforeEachStep**(`step`, `flow?`): `Promise`<`void`\>

#### Parameters

| Name    | Type                                           |
| :------ | :--------------------------------------------- |
| `step`  | [`Step`](../modules/Schema.md#step)            |
| `flow?` | [`UserFlow`](../interfaces/Schema.UserFlow.md) |

#### Returns

`Promise`<`void`\>

#### Inherited from

[PuppeteerRunnerExtension](PuppeteerRunnerExtension.md).[beforeEachStep](PuppeteerRunnerExtension.md#beforeeachstep)

#### Defined in

[RunnerExtension.ts:22](https://github.com/puppeteer/replay/blob/main/src/RunnerExtension.ts#L22)

---

### runStep

▸ **runStep**(`step`, `flow?`): `Promise`<`void`\>

#### Parameters

| Name    | Type                                           |
| :------ | :--------------------------------------------- |
| `step`  | [`Step`](../modules/Schema.md#step)            |
| `flow?` | [`UserFlow`](../interfaces/Schema.UserFlow.md) |

#### Returns

`Promise`<`void`\>

#### Inherited from

[PuppeteerRunnerExtension](PuppeteerRunnerExtension.md).[runStep](PuppeteerRunnerExtension.md#runstep)

#### Defined in

[PuppeteerRunnerExtension.ts:62](https://github.com/puppeteer/replay/blob/main/src/PuppeteerRunnerExtension.ts#L62)
