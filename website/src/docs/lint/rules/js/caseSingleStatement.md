---
title: Lint Rule js/caseSingleStatement
layout: layouts/page.njk
description: MISSING DOCUMENTATION
eleventyNavigation: {
	key: lint-rules/js/caseSingleStatement,
	parent: lint-rules,
	title: js/caseSingleStatement
}
---

# js/caseSingleStatement

MISSING DOCUMENTATION

<!-- EVERYTHING BELOW IS AUTOGENERATED. SEE SCRIPTS FOLDER FOR UPDATE SCRIPTS -->


## Examples
## Invalid
```typescript
switch (foo) {
	case true:
	case false:
		let foo = '';
		foo;
}
```
## Valid
```typescript
switch (foo) {
	case true:
	case false:
		'yes';
}
```
```typescript
switch (foo) {
	case true: {
		// empty
	}
}
```
```typescript
switch (foo) {
	case true:
}
```