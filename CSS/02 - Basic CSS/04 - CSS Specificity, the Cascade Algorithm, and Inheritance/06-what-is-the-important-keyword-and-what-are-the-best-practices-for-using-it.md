<div align="center">

## What Is the !important Keyword, and What Are the Best Practices for Using It?

### Questions

</div>

**1. What does the `!important` keyword do in CSS?**

- [ ] It increases the specificity value of a selector.  
- [x] It applies a style regardless of other rules' specificity.  
- [ ] It decreases the specificity value of a selector.  
- [ ] It overrides only inline styles.  

**2. When should the `!important` keyword be used?**

- [ ] As the primary method for styling elements.  
- [x] To override third-party styles or as a temporary fix.  
- [ ] In every CSS rule for consistency.  
- [ ] To increase specificity.  

**3. Given the following CSS, what will be the color of the text?**

```html
<head>
  <style>
    p {
      color: blue;
    }
    .highlight {
      color: green !important;
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
- [ ] green
- [ ] purple
- [ ] red
