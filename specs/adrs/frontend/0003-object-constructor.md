# determine js object properties for a profile

## Context and Problem Statement

What properties should a profile have?

Naming convention?

## Considered Options

```jsx
Object Product {
	title:
	serialNumber:
	tag:
	expDate:
	notes:
}
```
```jsx
Object Profile {
	title:
	serial_num:
	tag:
	exp_date:
	note:
}
```

## Decision Outcome
Chosen option: Second one.