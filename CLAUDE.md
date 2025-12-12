# Statistics: How to Be Wrong (Less Often)

## Project Overview
An interactive web-based statistics learning resource. Episodes teach statistical concepts through animated visualizations and carefully paced prose.

## Design System

### Colors
- Background: #0a0a0a (near-black)
- Primary accent: #4ecca3 (teal)
- Text primary: rgba(240, 240, 240, 0.95)
- Text secondary: rgba(240, 240, 240, 0.7)
- Text muted: rgba(240, 240, 240, 0.5)
- Error/negative: #e74c3c
- Warning/caution: #f39c12
- Highlight: #9b59b6

### Typography
- Titles: 'Fraunces', serif (weight 300, often italic)
- Body: 'Crimson Pro', serif (weight 300-400)
- Labels/code: 'IBM Plex Mono', monospace (weight 300-400)

### Animation Principles
- Easing: cubic-bezier easeInOut for most transitions
- Duration: 300-500ms for UI, 1-2s for educational reveals
- Elements should fade/slide in, never pop
- Use smoothstep for visibility thresholds

### Visualization Style
- Dark backgrounds, light strokes
- Teal (#4ecca3) for emphasis, positive, treatment groups
- Red (#e74c3c) for contrast, negative, control groups
- Points: semi-transparent with subtle glow on hover
- Axes: rgba(240,240,240,0.3), minimal, no heavy gridlines
- Animated builds preferred over static images

## Content Philosophy
- Verbose, flowing prose — no bullet points for explanations
- Build intuition before formalism
- Every visualization should animate or respond to interaction
- Concepts connect across episodes; reference earlier material naturally
