[![SVG Banners](https://svg-banners.vercel.app/api?type=typeWriter&text1=RespiCSS%20Framework%20👨‍💻&width=800&height=400)](https://github.com/Akshay090/svg-banners)

## Features

- 📱 Mobile-first approach
- 🔧 Flexible grid system
- 🌈 Customizable via CSS variables
- 🚀 Lightweight and easy to use

## Installation

```html
<link rel="stylesheet" href="flexbox-framework.css">
```

## Basic Usage

### Container
```html
<div class="container">
  <div class="row">
    <div class="col col-sm-6 col-md-4">
      Content
    </div>
  </div>
</div>
```

## Responsive Columns

- `.col`: Full width by default
- `.col-sm-*`: Small screens
- `.col-md-*`: Medium screens
- `.col-lg-*`: Large screens

### Example Breakpoints
- Small (576px): 50% / 33% / 25%
- Medium (768px): 50% / 33% / 25%
- Large (992px): 50% / 33% / 25%

## Customization

Modify CSS variables in `:root`:
```css
:root {
  --color-primary: #007bff;
  --spacing-base: 0.5rem;
  --font-base: system-ui, sans-serif;
}
```

## Demo
https://jsfiddle.net/e1absz3m/

## Browser Support

- Modern browsers
- Flexbox support: IE 11+

## License

MIT License
