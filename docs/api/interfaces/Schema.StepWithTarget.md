[@puppeteer/replay](../README.md) / [Schema](../modules/Schema.md) / StepWithTarget

# Interface: StepWithTarget

[Schema](../modules/Schema.md).StepWithTarget

## Hierarchy

- [`BaseStep`](Schema.BaseStep.md)

  ↳ **`StepWithTarget`**

  ↳↳ [`StepWithFrame`](Schema.StepWithFrame.md)

  ↳↳ [`EmulateNetworkConditionsStep`](Schema.EmulateNetworkConditionsStep.md)

  ↳↳ [`KeyDownStep`](Schema.KeyDownStep.md)

  ↳↳ [`KeyUpStep`](Schema.KeyUpStep.md)

  ↳↳ [`CloseStep`](Schema.CloseStep.md)

  ↳↳ [`SetViewportStep`](Schema.SetViewportStep.md)

  ↳↳ [`NavigateStep`](Schema.NavigateStep.md)

  ↳↳ [`StepWithFrame`](StepWithFrame.md)

  ↳↳ [`EmulateNetworkConditionsStep`](EmulateNetworkConditionsStep.md)

  ↳↳ [`KeyDownStep`](KeyDownStep.md)

  ↳↳ [`KeyUpStep`](KeyUpStep.md)

  ↳↳ [`CloseStep`](CloseStep.md)

  ↳↳ [`SetViewportStep`](SetViewportStep.md)

  ↳↳ [`NavigateStep`](NavigateStep.md)

## Table of contents

### Properties

- [assertedEvents](Schema.StepWithTarget.md#assertedevents)
- [target](Schema.StepWithTarget.md#target)
- [timeout](Schema.StepWithTarget.md#timeout)
- [type](Schema.StepWithTarget.md#type)

## Properties

### assertedEvents

• `Optional` **assertedEvents**: [`NavigationEvent`](Schema.NavigationEvent.md)[]

#### Inherited from

[BaseStep](Schema.BaseStep.md).[assertedEvents](Schema.BaseStep.md#assertedevents)

#### Defined in

[Schema.ts:61](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L61)

---

### target

• `Optional` **target**: `string`

Defaults to main

#### Defined in

[Schema.ts:68](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L68)

---

### timeout

• `Optional` **timeout**: `number`

#### Inherited from

[BaseStep](Schema.BaseStep.md).[timeout](Schema.BaseStep.md#timeout)

#### Defined in

[Schema.ts:60](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L60)

---

### type

• **type**: [`StepType`](../enums/Schema.StepType.md)

#### Inherited from

[BaseStep](Schema.BaseStep.md).[type](Schema.BaseStep.md#type)

#### Defined in

[Schema.ts:59](https://github.com/puppeteer/replay/blob/main/src/Schema.ts#L59)
