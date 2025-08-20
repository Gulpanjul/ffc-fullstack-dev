<div align="center">

## What Is the Specificity for Class Selectors?

### Questions

</div>

**1. What is the specificity value of a class selector (e.g., .example)?**

- [ ] (1, 0, 0, 0)
- [x] (0, 1, 0, 0)
- [ ] (0, 0, 1, 0)
- [ ] (0, 0, 0, 1)

**2. Which of the following selectors has a higher specificity than a class selector?**

- [ ] A type selector.
- [x] An ID selector.
- [ ] A universal selector.
- [ ] A pseudo-element.

**3. Given the following CSS, what will be the color of the text?**

```html
<head>
  <style>
    .highlight {
      color: green;
    }
    p {
      color: blue;
    }
    p.highlight {
      color: red;
    }
  </style>
</head>
<body>
  <p class="highlight">This text</p>
</body>
```

- [ ] green
- [ ] blue
- [x] red
- [ ] purple
