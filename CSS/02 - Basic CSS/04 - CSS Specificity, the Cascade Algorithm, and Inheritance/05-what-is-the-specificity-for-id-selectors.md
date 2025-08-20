<div align="center">

## What Is the Specificity for ID Selectors?

### Questions

</div>

**1. What is the specificity value of an ID selector (e.g., #example)?**

- [ ] (1, 0, 0, 0)
- [x] (0, 1, 0, 0)
- [ ] (0, 0, 1, 0)
- [ ] (0, 0, 0, 1)

**2. Which of the following has a higher specificity than an ID selector?**

- [ ] A class selector.
- [x] An inline style.
- [ ] An attribute selector.
- [ ] A type selector.

**3. Given the following CSS, what will be the color of the text?**

```html
<head>
  <style>
    #unique {
      color: purple;
    }
    .highlight {
      color: green;
    }
    p {
      color: blue;
    }
  </style>
</head>
<body>
  <p id="unique" class="highlight">This text</p>
</body>
```

- [ ] green
- [ ] blue
- [ ] red
- [x] purple
