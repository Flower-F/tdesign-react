:: BASE_DOC ::

## API
### Select Props

name | type | default | description | required
-- | -- | -- | -- | --
className | String | - | 类名 | N
style | Object | - | 样式，Typescript：`React.CSSProperties` | N
autoWidth | Boolean | false | \- | N
borderless | Boolean | false | \- | N
clearable | Boolean | false | \- | N
collapsedItems | TElement | - | Typescript：`TNode<{ value: T[]; collapsedSelectedItems: T[]; count: number }>`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/common.ts) | N
creatable | Boolean | false | \- | N
disabled | Boolean | - | \- | N
empty | TNode | - | Typescript：`string | TNode`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/common.ts) | N
filter | Function | - | Typescript：`(filterWords: string, option: T) => boolean | Promise<boolean>` | N
filterable | Boolean | - | \- | N
inputProps | Object | - | Typescript：`InputProps`，[Input API Documents](./input?tab=api)。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/select/type.ts) | N
inputValue | String / Number | - | input value。Typescript：`InputValue`，[Input API Documents](./input?tab=api)。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/select/type.ts) | N
defaultInputValue | String / Number | - | input value。uncontrolled property。Typescript：`InputValue`，[Input API Documents](./input?tab=api)。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/select/type.ts) | N
keys | Object | - | Typescript：`SelectKeysType` `interface SelectKeysType { value?: string; label?: string }`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/common.ts)。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/select/type.ts) | N
loading | Boolean | false | \- | N
loadingText | TNode | - | Typescript：`string | TNode`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/common.ts) | N
max | Number | 0 | \- | N
minCollapsedNum | Number | 0 | \- | N
multiple | Boolean | false | \- | N
options | Array | [] | Typescript：`Array<T>` | N
panelBottomContent | TNode | - | Typescript：`string | TNode`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/common.ts) | N
panelTopContent | TNode | - | Typescript：`string | TNode`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/common.ts) | N
placeholder | String | undefined | \- | N
popupProps | Object | - | Typescript：`PopupProps`，[Popup API Documents](./popup?tab=api)。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/select/type.ts) | N
popupVisible | Boolean | - | \- | N
defaultPopupVisible | Boolean | - | uncontrolled property | N
prefixIcon | TElement | - | Typescript：`TNode`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/common.ts) | N
readonly | Boolean | false | \- | N
reserveKeyword | Boolean | false | \- | N
scroll | Object | - | lazy load and virtual scroll。Typescript：`TScroll`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/common.ts) | N
selectInputProps | Object | - | Typescript：`SelectInputProps`，[SelectInput API Documents](./select-input?tab=api)。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/select/type.ts) | N
showArrow | Boolean | true | \- | N
size | String | medium | options：small/medium/large。Typescript：`SizeEnum`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/common.ts) | N
status | String | - | options：default/success/warning/error | N
tagInputProps | Object | - | Typescript：`TagInputProps`，[TagInput API Documents](./tag-input?tab=api)。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/select/type.ts) | N
tagProps | Object | - | Typescript：`TagProps`，[Tag API Documents](./tag?tab=api)。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/select/type.ts) | N
tips | TNode | - | Typescript：`string | TNode`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/common.ts) | N
value | String / Number / Object / Array | - | Typescript：`SelectValue` `type SelectValue<T extends SelectOption = SelectOption> = string | number | T | Array<SelectValue<T>>`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/select/type.ts) | N
defaultValue | String / Number / Object / Array | - | uncontrolled property。Typescript：`SelectValue` `type SelectValue<T extends SelectOption = SelectOption> = string | number | T | Array<SelectValue<T>>`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/select/type.ts) | N
valueDisplay | TNode | - | `MouseEvent<SVGElement>`。Typescript：`string | TNode<{ value: SelectValue; onClose: (index: number, item?: any) => void }>`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/common.ts) | N
valueType | String | value | options：value/object | N
onBlur | Function |  | Typescript：`(context: { value: SelectValue; e: FocusEvent | KeyboardEvent }) => void`<br/> | N
onChange | Function |  | Typescript：`(value: SelectValue, context: { option?: T, selectedOptions: T[], trigger: SelectValueChangeTrigger; e?: MouseEvent | KeyboardEvent }) => void`<br/>[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/select/type.ts)。<br/>`type SelectValueChangeTrigger = 'clear' | 'tag-remove' | 'backspace' | 'check' | 'uncheck'`<br/> | N
onClear | Function |  | Typescript：`(context: { e: MouseEvent }) => void`<br/> | N
onCreate | Function |  | Typescript：`(value: string | number) => void`<br/> | N
onEnter | Function |  | Typescript：`(context: { inputValue: string; e: KeyboardEvent; value: SelectValue }) => void`<br/> | N
onFocus | Function |  | Typescript：`(context: { value: SelectValue; e: FocusEvent | KeyboardEvent }) => void`<br/> | N
onInputChange | Function |  | Typescript：`(value: InputValue, context?: SelectInputValueChangeContext) => void`<br/>[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/select/type.ts)。<br/>`import { SelectInputValueChangeContext } from '@SelectInput'`<br/> | N
onPopupVisibleChange | Function |  | Typescript：`(visible: boolean, context: PopupVisibleChangeContext) => void`<br/>[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/select/type.ts)。<br/>`import { PopupVisibleChangeContext } from '@Popup'`<br/> | N
onRemove | Function |  | Typescript：`(options: SelectRemoveContext<T>) => void`<br/>[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/select/type.ts)。<br/>`interface SelectRemoveContext<T> { value: string | number; data: T; e: MouseEvent | KeyboardEvent }`<br/> | N
onSearch | Function |  | Typescript：`(filterWords: string) => void`<br/> | N

### Option Props

name | type | default | description | required
-- | -- | -- | -- | --
className | String | - | 类名 | N
style | Object | - | 样式，Typescript：`React.CSSProperties` | N
checkAll | Boolean | false | check all option, which can be both top of the panel and bottom of the panel | N
children | TNode | - | Typescript：`string | TNode`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/common.ts) | N
content | TNode | - | Typescript：`string | TNode`。[see more ts definition](https://github.com/Tencent/tdesign-react/blob/develop/src/common.ts) | N
disabled | Boolean | false | \- | N
label | String | - | \- | N
value | String / Number | - | \- | N

### OptionGroup Props

name | type | default | description | required
-- | -- | -- | -- | --
className | String | - | 类名 | N
style | Object | - | 样式，Typescript：`React.CSSProperties` | N
divider | Boolean | true | \- | N
label | String | - | \- | N
