# Flexbox Sizing

## `flex` property — applied to flex items
At what proportion should a flex item scale itself up or down to take up additional space.
How is space divided up amongst the children of a flex container? The `flex` property is shorthand for 

* `flex-grow`
	- how much, relative to its siblings should the item take up space available (how much it will grow).
	- default value is `0`
* `flex-shrink`
	- how much, relative to its siblings should the item shrink when there's not enough space.
	- default value is `1`
* `flex-basis`
	- how high or wide should the element be, ideally.
	- default value is `auto` — no specified value.

```css
.item {
	flex: 1;
}
```
Is the same as

```css
.item {
	flex-grow: 1;
	flex-shrink: 1;
	flex-basis: auto
}
```

___





























