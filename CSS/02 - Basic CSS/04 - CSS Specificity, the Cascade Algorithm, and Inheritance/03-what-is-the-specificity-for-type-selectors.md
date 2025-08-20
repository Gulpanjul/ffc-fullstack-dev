<div align="center">

## What Is the Specificity for Type Selectors?

### Questions

</div>

**1. What is the specificity value of a type selector (e.g., div)?**

- [ ] (1, 0, 0, 0)
- [ ] (0, 1, 0, 0)
- [x] (0, 0, 1, 0)
- [ ] (0, 0, 0, 1)

**2. Which of the following has a lower specificity than a type selector?**

- [ ] A class selector.
- [ ] An ID selector.
- [ ] An Inline style.
- [x] A Universal selector.

**3. Given the following CSS, what will be the color of the text?**

```html
<head>
  <style>
    * {
      color: blue;
    }
    p {
      color: red;
    }
  </style>
</head>
<body>
  <p>This text</p>
</body>
```

- [ ] blue
- [x] red
- [ ] green
- [ ] purple
