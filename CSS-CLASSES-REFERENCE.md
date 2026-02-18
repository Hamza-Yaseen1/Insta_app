# CSS Classes Reference Guide

Quick reference for all available CSS classes in the Modern Instagram Theme.

---

## 🎨 Layout Components

### Cards
```html
<!-- Basic Card -->
<div class="card">Content</div>

<!-- Card with Hover Effect -->
<div class="card hover-lift">Content</div>

<!-- Profile Card -->
<div class="profile-card">
  <img src="avatar.jpg" alt="Profile">
  <div class="name">Name</div>
  <div class="username">@username</div>
  <div class="stats">...</div>
</div>

<!-- Ranking Card -->
<div class="ranking-card">
  <div class="rank">1</div>
  <img src="avatar.jpg" alt="User">
  <div class="info">
    <div class="name">Name</div>
    <div class="score">Points</div>
  </div>
</div>
```

---

## 🔘 Buttons

### Primary Button
```html
<button class="pri_btn">Primary</button>
<input type="submit" class="pri_btn" value="Submit">
```

### Secondary Button
```html
<button class="sec_btn">Secondary</button>
```

### Tertiary Button
```html
<button class="tir_btn">Tertiary</button>
```

### Gradient Button
```html
<button class="gradient_btn">Gradient</button>
```

### Follow/Unfollow
```html
<button class="follow">Follow</button>
<button class="unfollow">Unfollow</button>
```

---

## 📝 Form Elements

### Input Fields
```html
<!-- Text Input -->
<input type="text" placeholder="Enter text">

<!-- Email Input -->
<input type="email" placeholder="Enter email">

<!-- Password Input -->
<input type="password" placeholder="Enter password">

<!-- Textarea -->
<textarea placeholder="Enter message"></textarea>

<!-- Select Dropdown -->
<select>
  <option>Option 1</option>
  <option>Option 2</option>
</select>
```

---

## 🏷️ Badges

### Badge Variants
```html
<span class="badge badge-primary">Primary</span>
<span class="badge badge-success">Success</span>
<span class="badge badge-warning">Warning</span>
<span class="badge badge-error">Error</span>
```

---

## 📊 Progress Bars

### Basic Progress Bar
```html
<div class="progress-bar">
  <div class="progress-bar-fill" style="width: 75%;"></div>
</div>
```

### With Label
```html
<div style="display: flex; justify-content: space-between; margin-bottom: 8px;">
  <span style="font-weight: 600;">JavaScript</span>
  <span style="color: var(--text-secondary);">85%</span>
</div>
<div class="progress-bar">
  <div class="progress-bar-fill" style="width: 85%;"></div>
</div>
```

---

## 🎭 Modals & Overlays

### Modal
```html
<div class="overlay"></div>
<div class="modal">
  <div class="modal_header">
    <span class="title">Modal Title</span>
  </div>
  <div class="modal_middle">
    Content here
  </div>
  <div class="modal_bottom">
    <button class="sec_btn">Cancel</button>
    <button class="pri_btn">Confirm</button>
  </div>
</div>
```

### Large Modal
```html
<div class="modal modal_big">
  <!-- Same structure as above -->
</div>
```

### Overlay Variants
```html
<!-- Standard Overlay -->
<div class="overlay"></div>

<!-- Hidden Overlay (transparent) -->
<div class="hidden_overlay"></div>

<!-- Colored Overlay -->
<div class="colored_overlay"></div>
```

---

## 🎨 Utility Classes

### Shadows
```html
<div class="shadow-sm">Small shadow</div>
<div class="shadow-md">Medium shadow</div>
<div class="shadow-lg">Large shadow</div>
<div class="shadow-xl">Extra large shadow</div>
```

### Hover Effects
```html
<div class="hover-lift">Lifts on hover</div>
<div class="hover-scale">Scales on hover</div>
```

### Text Utilities
```html
<span class="text-gradient">Gradient text</span>
<span class="text-primary">Primary color</span>
<span class="text-muted">Muted color</span>
<span class="text-light">Light color</span>
<span class="bold">Bold text</span>
```

### Background Utilities
```html
<div class="bg-primary">Primary background</div>
<div class="bg-secondary">Secondary background</div>
<div class="bg-dark">Dark background</div>
```

---

## ✨ Special Effects

### Glassmorphism
```html
<div class="glass">
  Glassmorphism effect
</div>
```

### Skeleton Loading
```html
<div class="skeleton" style="width: 100%; height: 20px;"></div>
```

---

## 🎯 Navigation

### Header
```html
<div class="header">
  <div class="logo">
    <a href="/"><img src="logo.png" alt="Logo"></a>
  </div>
  <div class="search_box">
    <input type="text" class="search" placeholder="Search">
    <span class="search_icon"><i class="fas fa-search"></i></span>
  </div>
  <div class="header_right">
    <a href="/"><i class="fas fa-home"></i></a>
    <a href="/notifications" class="notification">
      <span class="notification_span"><i class="fas fa-bell"></i></span>
    </a>
    <a href="/profile">
      <img src="avatar.jpg" alt="Profile">
    </a>
  </div>
</div>
```

### Sidebar
```html
<div class="m_n_wrapper">
  <div class="m_n">
    <ul>
      <li>
        <a href="/" class="sidebar_active">
          <span class="m_n_icon"><i class="fas fa-home"></i></span>
          <span class="m_n_text">Home</span>
        </a>
      </li>
      <li>
        <a href="/explore">
          <span class="m_n_icon"><i class="fas fa-compass"></i></span>
          <span class="m_n_text">Explore</span>
        </a>
      </li>
    </ul>
  </div>
</div>
```

---

## 🎴 Content Cards

### Card with Header
```html
<div class="card">
  <div class="card-header">
    <img src="avatar.jpg" alt="User">
    <div>
      <div class="username">Username</div>
      <div class="timestamp">2 hours ago</div>
    </div>
  </div>
  <p>Card content here...</p>
</div>
```

---

## 🔔 Notifications

### Notification Badge
```html
<a href="/notifications" class="notification">
  <span class="notification_span">
    <i class="fas fa-bell"></i>
  </span>
</a>
```

### Notification Speak (Popup)
```html
<div class="noti_speak">
  <img src="avatar.jpg" alt="User">
  <div class="n_s_sn_div">
    <span class="ns_bold">Username</span> liked your post
  </div>
</div>
```

---

## 📋 Options Menu

### Dropdown Options
```html
<div class="options">
  <ul>
    <li><a href="#">Edit</a></li>
    <li><a href="#">Delete</a></li>
    <li class="o_divider"><hr class="menu_divider"></li>
    <li><a href="#">Report</a></li>
  </ul>
</div>
```

---

## 🎨 Theme Toggle

### Dark Mode Toggle Button
```html
<button class="theme-toggle" id="themeToggle">
  <i class="fas fa-moon" id="themeIcon"></i>
</button>

<script>
  const themeToggle = document.getElementById('themeToggle');
  const themeIcon = document.getElementById('themeIcon');
  const html = document.documentElement;
  
  themeToggle.addEventListener('click', function() {
    const theme = html.getAttribute('data-theme');
    const newTheme = theme === 'light' ? 'dark' : 'light';
    html.setAttribute('data-theme', newTheme);
    localStorage.setItem('theme', newTheme);
    themeIcon.className = newTheme === 'dark' ? 'fas fa-sun' : 'fas fa-moon';
  });
</script>
```

---

## 🎯 Ranking Components

### Rank Badge
```html
<div class="rank">1</div>
<div class="rank top-1">1</div>  <!-- Gold -->
<div class="rank top-2">2</div>  <!-- Silver -->
<div class="rank top-3">3</div>  <!-- Bronze -->
```

---

## 📊 Stats Display

### Profile Stats
```html
<div class="stats">
  <div class="stat">
    <span class="stat-value">1,234</span>
    <span class="stat-label">Points</span>
  </div>
  <div class="stat">
    <span class="stat-value">45</span>
    <span class="stat-label">Courses</span>
  </div>
  <div class="stat">
    <span class="stat-value">892</span>
    <span class="stat-label">Followers</span>
  </div>
</div>
```

---

## 🎨 Color Classes

### Text Colors
```html
<span style="color: var(--text-primary)">Primary text</span>
<span style="color: var(--text-secondary)">Secondary text</span>
<span style="color: var(--text-tertiary)">Tertiary text</span>
<span style="color: var(--accent-primary)">Accent text</span>
```

### Background Colors
```html
<div style="background: var(--bg-primary)">Primary bg</div>
<div style="background: var(--bg-secondary)">Secondary bg</div>
<div style="background: var(--bg-tertiary)">Tertiary bg</div>
```

---

## 🎭 State Classes

### Disabled States
```html
<button class="pri_btn a_disabled">Disabled</button>
<button class="sec_btn sec_btn_disabled">Disabled</button>
```

### Active States
```html
<a href="#" class="sidebar_active">Active Link</a>
<a href="#" class="ha_active">Active Header Link</a>
```

---

## 📱 Responsive Classes

### Hide on Mobile
```html
<span class="m_n_text">Hidden on mobile</span>
```

---

## 🎨 CSS Variables Reference

### Colors
```css
var(--bg-primary)
var(--bg-secondary)
var(--bg-tertiary)
var(--text-primary)
var(--text-secondary)
var(--text-tertiary)
var(--border-color)
var(--accent-primary)
var(--accent-hover)
var(--success-color)
var(--error-color)
var(--warning-color)
```

### Shadows
```css
var(--shadow-sm)
var(--shadow-md)
var(--shadow-lg)
var(--shadow-xl)
```

### Transitions
```css
var(--transition-fast)    /* 0.15s */
var(--transition-normal)  /* 0.3s */
var(--transition-slow)    /* 0.5s */
```

### Gradients
```css
var(--accent-gradient)  /* Purple gradient */
```

---

## 🎯 Common Patterns

### Card with Image and Action
```html
<div class="card hover-lift">
  <img src="image.jpg" alt="Image" style="width: 100%; border-radius: 12px;">
  <h3 style="margin: 16px 0 8px;">Title</h3>
  <p style="color: var(--text-secondary); margin-bottom: 16px;">
    Description text here
  </p>
  <button class="pri_btn" style="width: 100%;">Action</button>
</div>
```

### User List Item
```html
<div class="ranking-card">
  <img src="avatar.jpg" alt="User">
  <div class="info">
    <div class="name">User Name</div>
    <div class="score">@username</div>
  </div>
  <button class="pri_btn">Follow</button>
</div>
```

### Form Group
```html
<div style="margin-bottom: 16px;">
  <label style="display: block; margin-bottom: 8px; font-weight: 600;">
    Label
  </label>
  <input type="text" placeholder="Placeholder" style="width: 100%;">
</div>
```

---

## 💡 Pro Tips

### Combining Classes
```html
<!-- Card with multiple effects -->
<div class="card hover-lift shadow-md">Content</div>

<!-- Button with gradient and shadow -->
<button class="gradient_btn shadow-lg">Button</button>

<!-- Text with gradient and bold -->
<span class="text-gradient bold">Gradient Bold Text</span>
```

### Custom Styling
```html
<!-- Override with inline styles -->
<button class="pri_btn" style="width: 100%; padding: 16px;">
  Large Button
</button>

<!-- Use CSS variables -->
<div style="background: var(--accent-primary); color: white; padding: 20px;">
  Custom Box
</div>
```

---

## 📚 Quick Reference

### Most Used Classes
```
.card                  - Basic card
.pri_btn              - Primary button
.sec_btn              - Secondary button
.badge badge-primary  - Badge
.hover-lift           - Hover effect
.shadow-md            - Shadow
.text-gradient        - Gradient text
.profile-card         - Profile card
.ranking-card         - Ranking card
.progress-bar         - Progress bar
```

---

**For complete examples, see:** `dist/examples/modern-components.html`

**For full documentation, see:** `UI-ENHANCEMENT-GUIDE.md`
