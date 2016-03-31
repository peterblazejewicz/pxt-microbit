# speed button quiz answers

counter that keeps track of how many times button "A" has been pressed #LED #screen #variables #docs #input

This is the answer key for the [speed button quiz](/microbit/lessons/speed-button/quiz).

## 1. What is a variable?

<br/>

A variable that is available throughout your main function.

## 2. If the rectangle below represents the BBC micro:bit, shade the area that shows the value of the variable count.

```blocks
let count = 0
```

![](/static/mb/lessons/speed-button-0.png)

## 3. If the rectangle below represents the BBC micro:bit, shade the areas that will be displayed after two button presses on Button A. Explain why that particular area is shaded.

```blocks
let count_ = 0
input.onButtonPressed(Button.A, () => {
    count_ = count_ + 1
    basic.showNumber(count_, 100)
})
```

<br/>

![](/static/mb/lessons/speed-button-1.png)

After two button presses, **count** will be equal to 2.

## 5. If the rectangle below represents the BBC micro:bit, shade the areas that will be displayed after five button presses on Button A. Explain why that particular area is shaded.

```blocks
count_ = 0
input.onButtonPressed(Button.A, () => {
    count_ = count_ + 1
    basic.showNumber(count_, 100)
})
```

![](/static/mb/lessons/speed-button-2.png)

After five button presses, **count** will be equal to 5.
