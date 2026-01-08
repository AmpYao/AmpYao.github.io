---
layout: default
title: Rotated Component Imaging
---

# Rotated Component Imaging

This page demonstrates various techniques for rotating images and components using CSS transforms.

## Basic Image Rotation

### 45 Degree Rotation

<div style="text-align: center; margin: 20px 0;">
  <div style="display: inline-block; width: 200px; height: 200px; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); transform: rotate(45deg); border: 3px solid #333;">
  </div>
</div>

```css
.rotated-45 {
  transform: rotate(45deg);
}
```

### 90 Degree Rotation

<div style="text-align: center; margin: 20px 0;">
  <div style="display: inline-block; width: 200px; height: 200px; background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); transform: rotate(90deg); border: 3px solid #333;">
  </div>
</div>

```css
.rotated-90 {
  transform: rotate(90deg);
}
```

### 180 Degree Rotation

<div style="text-align: center; margin: 20px 0;">
  <div style="display: inline-block; width: 200px; height: 200px; background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%); transform: rotate(180deg); border: 3px solid #333;">
  </div>
</div>

```css
.rotated-180 {
  transform: rotate(180deg);
}
```

## Advanced Rotation Techniques

### 3D Rotation (X-axis)

<div style="text-align: center; margin: 20px 0; perspective: 1000px;">
  <div style="display: inline-block; width: 200px; height: 200px; background: linear-gradient(135deg, #fa709a 0%, #fee140 100%); transform: rotateX(30deg); border: 3px solid #333;">
    <p style="margin: 80px 0; text-align: center; font-weight: bold;">3D Rotated</p>
  </div>
</div>

```css
.rotated-3d-x {
  perspective: 1000px;
  transform: rotateX(30deg);
}
```

### 3D Rotation (Y-axis)

<div style="text-align: center; margin: 20px 0; perspective: 1000px;">
  <div style="display: inline-block; width: 200px; height: 200px; background: linear-gradient(135deg, #30cfd0 0%, #330867 100%); transform: rotateY(30deg); border: 3px solid #333;">
    <p style="margin: 80px 0; text-align: center; font-weight: bold; color: white;">3D Rotated</p>
  </div>
</div>

```css
.rotated-3d-y {
  perspective: 1000px;
  transform: rotateY(30deg);
}
```

### Combined Rotation

<div style="text-align: center; margin: 20px 0; perspective: 1000px;">
  <div style="display: inline-block; width: 200px; height: 200px; background: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%); transform: rotateX(20deg) rotateY(20deg) rotateZ(20deg); border: 3px solid #333;">
    <p style="margin: 80px 0; text-align: center; font-weight: bold;">Combined</p>
  </div>
</div>

```css
.rotated-combined {
  perspective: 1000px;
  transform: rotateX(20deg) rotateY(20deg) rotateZ(20deg);
}
```

## Rotation with Animation

### Continuous Rotation

<style>
@keyframes spin {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}
</style>

<div style="text-align: center; margin: 20px 0;">
  <div style="display: inline-block; width: 200px; height: 200px; background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 100%, #fecfef 100%); animation: spin 4s linear infinite; border: 3px solid #333;">
    <p style="margin: 80px 0; text-align: center; font-weight: bold;">Spinning</p>
  </div>
</div>

```css
@keyframes spin {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}

.rotating-animation {
  animation: spin 4s linear infinite;
}
```

## Practical Use Cases

### 1. **Image Galleries**
Rotated components can create dynamic and engaging image galleries.

### 2. **Loading Spinners**
Continuous rotation is perfect for loading indicators.

### 3. **Artistic Layouts**
Tilted components can add visual interest to layouts.

### 4. **Interactive Elements**
Hover effects with rotation can enhance user experience.

## Browser Compatibility

CSS transforms are well-supported across modern browsers:
- Chrome 36+
- Firefox 16+
- Safari 9+
- Edge 12+
- Opera 23+

## Additional Resources

- [MDN Web Docs: CSS Transforms](https://developer.mozilla.org/en-US/docs/Web/CSS/transform)
- [CSS Tricks: Transform](https://css-tricks.com/almanac/properties/t/transform/)
- [W3C Transform Specification](https://www.w3.org/TR/css-transforms-1/)

---

[Back to Home](/)
