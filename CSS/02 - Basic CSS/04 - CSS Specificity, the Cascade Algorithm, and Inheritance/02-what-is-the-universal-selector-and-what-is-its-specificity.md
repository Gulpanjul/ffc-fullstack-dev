<div align="center">

## What Is the Universal Selector, and What Is Its Specificity?

### Questions

</div>

**1. What is the specificity value of the universal selector (*)?**

- [ ] (1, 0, 0, 0)  
- [ ] (0, 1, 0, 0)  
- [ ] (0, 0, 1, 0)  
- [x] (0, 0, 0, 0)  

**2. What is a common use case for the universal selector?**

- [ ] To apply styles to a specific element.  
- [x] To reset or normalize styles across all elements.  
- [ ] To target elements with a specific class.  
- [ ] To override inline styles.  

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
    .highlight {
      color: green;
    }
    #unique {
      color: purple;
    }
  </style>
</head>
<body>
  <p id="unique" class="highlight">This text</p>
</body>
```

- [ ] blue
- [ ] red
- [ ] green
- [x] purple
