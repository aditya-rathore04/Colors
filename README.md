# Palette Forge

I built this tool because I couldn't find a color palette generator on the internet that worked the way I wanted. Most tools use simple HSL interpolation, which leads to muddy midtones, inconsistent contrast steps, or neon-bright light/dark variants. 

Palette Forge generates perceptually even color ramps using the OKLCH color space. It runs entirely in your browser and helps you create balanced palettes, semantic tokens (success, warning, error, info), and exportable code.

## Why OKLCH?
Unlike standard RGB or HSL, OKLCH matches how human eyes actually perceive color brightness and saturation. This allows us to sweep lightness on a smooth perceptual curve while keeping chroma tapered at the extremes to avoid muddy darks or overly vibrant highlights.

## Features
- **Perceptual Ramps:** Builds balanced neutral, primary, and accent ramps.
- **Auto-Semantic Generation:** Automatically outputs matching states (success, warning, error, info) based on your palette's intensity.
- **Theme Mapping:** Preview how your colors look in dark mode instantly.
- **Multi-Format Export:** Copy or download code directly for CSS variables, Tailwind CSS, Figma JSON, SwiftUI, and Jetpack Compose (Kotlin).
- **Clipboard Friendly:** Copy individual hex codes, copy the generated code blocks, or export a clean palette image to share or paste into design tools.