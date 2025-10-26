Tailwind CSS is a particular CSS design pattern, which encourages a "utility-first" approach.
Instead of writing separate CSS classes like

```css
.header {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 20px;
}
```

You write inline in your HTML/JSX using small, composable **utility classes**:
```css
<div class="flex justify-center items-center p-5">
  Header
</div>
```

The core ideas:

1. Every class is a single purpose utility (e.g., `p-5` => padding, `text-center` => text alignment)
2. Compose styles by combining utilities instead of creating semantic classes for everything
3. Responsive and state variants are built-in, e.g., `sm:p-10 md:p-20 hover:bg-blue-500`
4. No need to write custom CSS for most layouts; the class strings describe the styling directly.