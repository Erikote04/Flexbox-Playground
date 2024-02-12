# Flexbox Playground

## Getting Started

1. Clone the repository: `git clone https://github.com/Erikote04/Flexbox-Playground.git`

2. Open the `index.html` file in a web browser.

3. Follow the steps down below and become a master in Flexbox
   
## Flexbox Properties

### Container
```css
.container {
	flex-direction: row | row-reverse | column | column-reverse; /* direction of the main-axis */
	flex-wrap: nowrap | wrap | wrap-reverse; /* new line? */
	justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly; /* main-axis */
	align-items: stretch | flex-start | flex-end | center | baseline; /* cross-axis */
}
```

### Item
```css
.item {
	align-self: auto | stretch | flex-start | flex-end | center | baseline;
	order: 0 | <integer>;
	flex-grow: 0 | <integer>; /* how much an item can grow */
	flex-shrink: 1 | <integer>; /* how much an item can shrink */
	flex-basis: auto | <length>; /* base width */
}
/* Last 3 properties con be resumed as flex: 0 1 auto */
```

### Roadmap

#### `display: flex`
```css
.container {
    display: flex;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 10.35.09.png>)

#### `flex-direction: row`
```css
.container {
    display: flex;
    flex-direction: row;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 10.35.09.png>)

#### `flex-direction: row-reverse`
```css
.container {
    display: flex;
    flex-direction: row-reverse;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 10.39.28.png>)

#### `flex-direction: column`
```css
.container {
    display: flex;
    flex-direction: column;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 10.41.25.png>)

#### `flex-direction: column-reverse`
```css
.container {
    display: flex;
    flex-direction: column-reverse;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 10.41.55.png>)

#### `justify-content: flex-start`
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 10.52.29.png>)

#### `justify-content: center`
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: center;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 10.44.39.png>)

#### `justify-content: space-between`
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 10.46.30.png>)

#### `justify-content: space-around`
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 10.47.33.png>)

#### `justify-content: space-evenly`
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 10.49.13.png>)

#### `justify-content: flex-end`
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 10.51.06.png>)

#### `align-items: stretch` 
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: stretch;
}

.i3 {
	height: 200px;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 10.59.42.png>)

#### `align-items: center` 
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
}

.i3 {
	height: 200px;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 11.00.43.png>)

#### `align-items: flex-start` 
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: flex-start;
}

.i3 {
	height: 200px;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 11.01.46.png>)

#### `align-items: flex-end` 
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: flex-end;
}

.i3 {
	height: 200px;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 11.02.41.png>)

#### `align-items: baseline` 
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: baseline;
}

.i2 {
	height: 200px;
}

.i4 {
	font-size: 70px;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 11.06.11.png>)

#### `flex-direction: column; justify-content: center; align-items: center;` 
```css
.container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 11.10.59.png>)

#### `align-self: stretch;` 
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

.i2 {
	height: 200px;
}

.i4 {
	align-self: stretch;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.02.34.png>)

#### `align-self: flex-start;` 
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

.i2 {
	height: 200px;
}

.i4 {
	align-self: flex-start;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.00.58.png>)

#### `align-self: flex-end;` 
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

.i2 {
	height: 200px;
}

.i4 {
	align-self: flex-end;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.00.18.png>)

#### `align-self: center;` 
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

.i2 {
	height: 200px;
}

.i4 {
	align-self: center;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.05.14.png>)

#### `align-self: baseline;` 
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

.i2 {
	height: 200px;
}

.i4 {
	align-self: baseline;
	font-size: 70px;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.07.30.png>)

#### `order: -1;` 
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

.i2 {
	height: 200px;
}

.i4 {
	align-self: center;
	order: -1
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.10.03.png>)

#### `order: 1;` 
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

.i2 {
	height: 200px;
}

.i3 {
	order: 1;
}

.i4 {
	align-self: center;
	order: -1
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.12.33.png>)

#### `flex-grow;` 
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

.item {
    flex-grow: 1;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.15.50.png>)

#### `flex-grow;` 
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

.item {
    flex-grow: 1;
}

.i3 {
	flex-grow: 2;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.20.49.png>)

#### `flex-grow;` 
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

.i5 {
	flex-grow: 1;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.22.59.png>)

#### `flex-basis;` 
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

.i3 {
	flex-basis: 40%;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.26.19.png>)

#### `flex-shrink;` 
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

.i3 {
	flex-basis: 300px;
	flex-shrink: 1; /* allows the item to shrink */
	/* flex: 0 1 300px */
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.30.19.png>)

#### `flex-shrink;` 
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

.i3 {
	flex-basis: 300px;
	flex-shrink: 0; /* doesn't allows the item to shrink */
	/* flex: 0 0 300px */
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.31.32.png>)

#### `flex-wrap: nowrap`
```html
<div class="container">
	<div class="item">1</div>
    <div class="item">2</div>
    <div class="item">3</div>
    <div class="item">4</div>
    <div class="item">5</div>
    <div class="item">6</div>
    <div class="item">7</div>
    <div class="item">8</div>
    <div class="item">9</div>
    <div class="item">10</div>
</div>
```

```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    flex-wrap: nowrap;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.40.16.png>)

#### `flex-wrap: wrap`
```css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.41.24.png>)

#### `align-content: flex-start`
```css
.container {
	height: 800px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    align-content: flex-start;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.50.00.png>)

#### `align-content: flex-end`
```css
.container {
	height: 800px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    align-content: flex-end;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.50.46.png>)

#### `align-content: center`
```css
.container {
	height: 800px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    align-content: center;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.52.02.png>)

#### `align-content: space-between`
```css
.container {
	height: 800px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    align-content: space-between;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.52.56.png>)

#### `align-content: space-around`
```css
.container {
	height: 800px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    align-content: space-around;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.53.28.png>)

#### `align-content: space-evenly`
```css
.container {
	height: 800px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    align-content: space-evenly;
}
```

![alt text](<img/Captura de pantalla 2024-02-02 a las 13.54.07.png>)
