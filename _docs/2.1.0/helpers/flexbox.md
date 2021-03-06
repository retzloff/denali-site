---
title: "Flexbox"
permalink: docs/:path
excerpt: 'Flex helpers, based on flexbox, help layout responsive elements within a container.'
---
{::options parse_block_html="true" /}

# {{ page.title }}
{{ page.excerpt }}

> Denali’s flex helpers are based on flexbox. For more information about flexbox Read [this guide](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox) before getting started.

***

<details open >
<summary>
## Flex
</summary>

Helper classes for controlling how flex items both grow and shrink.

| Class         | Properties       |
| ------------- | ---------------- |
| `.flex`       | display: flex;   |
| `.flex-auto`  | flex: auto;      |
| `.flex-1`     | flex: 1;         |
| `.flex-...`   | flex: ...        |
| `.flex-4`     | flex: 4;         |

### Flex
Use `.flex` to set flexbox properties for all items in the container.

```html
<div class="flex">
  <div class="box"> Box 1</div>
  <div class="box"> Box 2</div>
  <div class="box"> Box 3</div>
</div>
```

### Auto
Use `.flex-auto` to set flex items to shrink or grow.

```html
<div class="flex">
  <div class="box w-50">Width 50px</div>
  <div class="box flex-auto">Flex Auto</div>
  <div class="box w-50">Width 50px</div>
</div>
```

### Flex Size
Use `.flex-1` to `.flex-4` to set flex items width depending on other flex items in the same container.

```html
<div class="flex">
  <div class="box flex-1">Flex 1</div>
  <div class="box flex-4">Flex 4</div>
</div>
```
</details>

***

<details open >
<summary>
## Flex Direction
</summary>

Helpers classes for controlling the direction of flex items.

| Class         | Properties       |
| ------------- | ---------------- |
| `.flex-column`         | flex-direction: column;         |
| `.flex-column-reverse` | flex-direction: column-reverse; |
| `.flex-row`            | flex-direction: row;            |
| `.flex-row-reverse`    | flex-direction: row-reverse;    |

### Column
Use `.flex-column` to set flex container to align items vertically in the same direction.

```html
<div class="flex flex-column">
  <div class="box"> Box 1</div>
  <div class="box"> Box 2</div>
  <div class="box"> Box 3</div>
</div>
```

### Column Reversed
Use `.flex-column-reverse` to set flex container to align items vertically in the opposite direction.

```html
<div class="flex flex-column-reverse">
  <div class="box"> Box 1</div>
  <div class="box"> Box 2</div>
  <div class="box"> Box 3</div>
</div>
```

<!-- #### Responsive
```html

``` -->

### Row
Use `.flex-column` to set flex container to align items horizontally in the same direction.

```html
<div class="flex flex-row">
  <div class="box"> Box 1</div>
  <div class="box"> Box 2</div>
  <div class="box"> Box 3</div>
</div>
```

### Row Reversed
Use `.flex-column-reverse` to set flex container to align items horizontally in the opposite direction.

```html
<div class="flex flex-row-reverse">
  <div class="box"> Box 1</div>
  <div class="box"> Box 2</div>
  <div class="box"> Box 3</div>
</div>
```

</details>

***

<details open >
<summary>
## Justify Content
</summary>

Helpers classes for controlling how flex items are positioned.

| Class         | Properties       |
| ------------- | ---------------- |
| `.space-between`              | justify-content: space-between; |
| `.space-around`               | justify-content: space-around;  |
| `.justify-content-center`     | justify-content: center;        |

### Space Between
Use `.space-between` to provide equal space between items in the container on the main axis.

```html
<div class="flex space-between">
  <div class="box"> Box 1</div>
  <div class="box"> Box 2</div>
  <div class="box"> Box 3</div>
</div>
```

<!-- #### Responsive
```html
``` -->

### Space Around
Use `.space-around` to provide equal space around items in the container on the main axis.

```html
<div class="flex space-around">
  <div class="box"> Box 1</div>
  <div class="box"> Box 2</div>
  <div class="box"> Box 3</div>
</div>
```

### Center
Use `.justify-content-center` to center items in the container on the main axis.

```html
<div class="flex justify-content-center">
  <div class="box"> Box 1</div>
  <div class="box"> Box 2</div>
  <div class="box"> Box 3</div>
</div>
```

</details>

***

<details open >
<summary>
## Alignment
</summary>

Helpers classes for controlling how flex items are positioned within a container.

| Class         | Properties       |
| ------------- | ---------------- |
| `.align-items-center`   | align-items: center;   |
| `.align-self-start`     | align-self: start;     |
| `.align-self-center`    | align-self: center;    |
| `.align-content-center` | align-content: center; |

### Align Items Center
Use `.align-items-center` to center items in the container on the cross axis.

```html
<div class="flex align-items-center">
  <div class="box"> Box 1</div>
  <div class="box"> Box 2</div>
  <div class="box"> Box 3</div>
</div>
```

### Align Self Start
Use `.align-self-start` on a flex items to position that item at the start of the container on the cross axis.

```html
<div class="flex">
  <div class="box"> Box 1</div>
  <div class="box align-self-start"> Box 2</div>
  <div class="box"> Box 3</div>
</div>
```

### Align Self Center
Use `.align-self-center` on a flex items to center that item in the container on the cross axis.

```html
<div class="flex">
  <div class="box"> Box 1</div>
  <div class="box align-self-center"> Box 2</div>
  <div class="box"> Box 3</div>
</div>
```

### Align Content Center
Use `.content-center` to center all items in the container to the middle of the cross axis:

```html
<div class="flex content-center">
  <div class="box"> Box 1</div>
  <div class="box"> Box 2</div>
  <div class="box"> Box 3</div>
</div>
```

</details>
