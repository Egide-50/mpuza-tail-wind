# Navigation Menu with Notification Badges

A clean and modern navigation menu built with Tailwind CSS, featuring notification badges and Font Awesome icons.

![Navigation Menu Preview](preview.png)

## Features

- 🎨 **Modern Design** - Clean red theme with cyan notification badges
- 🔔 **Notification Badges** - Dynamic badge indicators for pending items
- 📱 **Responsive Layout** - Works seamlessly across all device sizes
- ✨ **Hover Effects** - Smooth transitions for better user experience
- 🚀 **Easy to Customize** - Built with utility-first Tailwind CSS
- 🎯 **Font Awesome Icons** - Professional icon set included

## Menu Items

The navigation includes four main sections:

1. **My Network** - Shows network connections (10+ notifications)
2. **Courses** - Access to learning materials (2 notifications)
3. **Notifications** - Activity alerts (7 notifications)
4. **Job Alerts** - Employment opportunities

## Technologies Used

- **Tailwind CSS** - Utility-first CSS framework
- **Font Awesome 6** - Icon library
- **HTML5** - Semantic markup

## Installation

### Option 1: CDN (Quick Start)

Simply copy the HTML code and open it in your browser. All dependencies are loaded via CDN.

### Option 2: Local Installation

1. Clone or download this repository
2. Open `index.html` in your web browser

No build process required!

## Usage

### Basic Implementation

```html
<nav class="bg-red-600 text-white">
    <div class="flex items-center justify-around px-4 py-3">
        <!-- Menu items go here -->
    </div>
</nav>
```

### Adding a Menu Item with Badge

```html
<a href="#" class="flex flex-col items-center gap-1 hover:bg-red-700 px-4 py-2 rounded transition">
    <div class="relative">
        <i class="fas fa-bell text-xl"></i>
        <span class="absolute -top-2 -right-3 bg-cyan-400 text-white text-xs font-bold rounded-full min-w-[20px] h-5 flex items-center justify-center px-1.5">7</span>
    </div>
    <span class="text-sm">Notifications</span>
</a>
```

### Adding a Menu Item without Badge

```html
<a href="#" class="flex flex-col items-center gap-1 hover:bg-red-700 px-4 py-2 rounded transition">
    <div class="relative">
        <i class="fas fa-briefcase text-xl"></i>
    </div>
    <span class="text-sm">Job Alerts</span>
</a>
```

## Customization

### Change Colors

**Navigation Background:**
```html
<!-- Change from red to blue -->
<nav class="bg-blue-600 text-white">
```

**Badge Color:**
```html
<!-- Change from cyan to green -->
<span class="bg-green-400 text-white ...">7</span>
```

**Hover Effect:**
```html
<!-- Change hover color -->
<a class="hover:bg-red-700 ...">
```

### Modify Icons

Replace Font Awesome class names with any icon from the [Font Awesome library](https://fontawesome.com/icons):

```html
<i class="fas fa-your-icon-name text-xl"></i>
```

### Adjust Badge Numbers

Simply update the text content:

```html
<span class="...">99+</span>
```

### Responsive Adjustments

For mobile optimization, you can modify spacing:

```html
<div class="flex items-center justify-around px-2 py-2 md:px-4 md:py-3">
```

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## File Structure

```
project/
│
├── index.html          # Main HTML file
├── README.md          # This file
└── preview.png        # Screenshot (optional)
```

## Key CSS Classes Explained

| Class | Purpose |
|-------|---------|
| `bg-red-600` | Red background color |
| `flex flex-col` | Vertical flex layout |
| `items-center` | Center items horizontally |
| `justify-around` | Distribute items evenly |
| `relative` | Position context for badge |
| `absolute` | Position badge absolutely |
| `rounded-full` | Circular badge shape |
| `hover:bg-red-700` | Darker red on hover |
| `transition` | Smooth hover animation |

## Tips

1. **Badge Positioning**: Adjust `-top-2` and `-right-3` to fine-tune badge placement
2. **Badge Size**: Use `min-w-[20px]` for single digits, `min-w-[24px]` for "10+"
3. **Link Targets**: Replace `#` with actual URLs or JavaScript functions
4. **Accessibility**: Add `aria-label` attributes for screen readers

## Example Enhancements

### Add Tooltips
```html
<a href="#" title="View your network connections">
```

### Add Active State
```html
<a class="... bg-red-700" aria-current="page">
```

### Make Badge Pulse
```html
<span class="... animate-pulse">7</span>
```

## License

This project is open source and available for personal and commercial use.

## Credits

- Built with [Tailwind CSS](https://tailwindcss.com/)
- Icons by [Font Awesome](https://fontawesome.com/)

## Support

For issues or questions, please open an issue in the repository.

---
##Screenshoot
<img width="1356" height="712" alt="Screenshot 2026-02-18 120229" src="https://github.com/user-attachments/assets/ca5a7594-9a76-410a-910d-b4c899d0ef71" />


**Made with ❤️ using Tailwind CSS**
