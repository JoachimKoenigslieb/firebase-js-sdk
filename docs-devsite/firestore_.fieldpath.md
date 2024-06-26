Project: /docs/reference/js/_project.yaml
Book: /docs/reference/_book.yaml
page_type: reference

{% comment %}
DO NOT EDIT THIS FILE!
This is generated by the JS SDK team, and any local changes will be
overwritten. Changes should be made in the source code at
https://github.com/firebase/firebase-js-sdk
{% endcomment %}

# FieldPath class
A `FieldPath` refers to a field in a document. The path may consist of a single field name (referring to a top-level field in the document), or a list of field names (referring to a nested field in the document).

Create a `FieldPath` by providing field names. If more than one field name is provided, the path will point to a nested field in a document.

<b>Signature:</b>

```typescript
export declare class FieldPath 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(fieldNames)](./firestore_.fieldpath.md#fieldpathconstructor) |  | Creates a <code>FieldPath</code> from the provided field names. If more than one field name is provided, the path will point to a nested field in a document. |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [isEqual(other)](./firestore_.fieldpath.md#fieldpathisequal) |  | Returns true if this <code>FieldPath</code> is equal to the provided one. |

## FieldPath.(constructor)

Creates a `FieldPath` from the provided field names. If more than one field name is provided, the path will point to a nested field in a document.

<b>Signature:</b>

```typescript
constructor(...fieldNames: string[]);
```

#### Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  fieldNames | string\[\] | A list of field names. |

## FieldPath.isEqual()

Returns true if this `FieldPath` is equal to the provided one.

<b>Signature:</b>

```typescript
isEqual(other: FieldPath): boolean;
```

#### Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  other | [FieldPath](./firestore_.fieldpath.md#fieldpath_class) | The <code>FieldPath</code> to compare against. |

<b>Returns:</b>

boolean

true if this `FieldPath` is equal to the provided one.

