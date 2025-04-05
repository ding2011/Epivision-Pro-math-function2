EpiVision Pro – Mathematical Function Visualization User Manual Version 1.1 | Last Updated: April 5, 2025

I. Introduction EpiVision Pro is an advanced mathematical function visualization tool that supports: ✅ Real-time dynamic rendering ✅ Multi-display modes (Line Chart/Scatter Plot/Area Chart) ✅ High-precision coordinate interaction ✅ Cross-platform compatibility (Desktop/Mobile) ✅ Professional image export

II. Quick Start Guide

Basic Workflow Input Function Expressions
Use JavaScript math syntax in the input field

Examples:

Math.sin(x)*x // Sine wave function x**2 - 4 // Quadratic function Math.log(x)/x // Logarithmic function variant Select Display Mode

Three modes available:

Line Mode: Ideal for continuous functions

Scatter Mode: For discrete data analysis

Area Mode: Visualizes integration concepts

Adjust Coordinate Ranges

Set numerical intervals in X/Y range fields

Supports scientific notation (e.g., 1e-5)

Interactive Controls

Operation Desktop Mobile View Panning Left-click + Drag Single-finger Drag View Zooming Mouse Wheel Pinch Gesture Live Coordinates Hover Display Touch Display III. Core Features

Function Input Specifications Supported Syntax:
Standard operators: + - * / ** %

Math functions: sin/cos/log/pow etc.

Nested expressions: Math.pow(2, Math.sin(x))

Conditional expressions: x > 0 ? x : -x

Error Handling:

Red error prompts for invalid inputs

Automatic NaN filtering

Input debounce (300ms rendering delay)

Advanced View Controls Smart Grid System:
Auto-adjusts grid density based on viewport

Dynamic axis display logic:

Shows axes when origin is visible

Auto-hides when out of view

View Management:

"Reset View" restores last valid range

Double-click canvas for quick centering

Professional Export Image Specifications:
Resolution: 200% of original size

Format: PNG (Transparent background optional)

Metadata: Includes timestamp & coordinate ranges

Annotation: Customizable footer text

Best Practices:

Set target view range

Wait for rendering completion

Click export for HD image

IV. Cross-Platform Optimization

Desktop Enhancements Shortcuts:
Cmd/Ctrl + ← → : Horizontal panning Cmd/Ctrl + ↑ ↓ : Vertical panning Alt + Wheel : Precision zoom 4K/5K display support

Multi-window synchronization

Mobile Optimizations Smart keyboard avoidance
60FPS touch rendering

Low-power mode adaptation

V. Troubleshooting Common Solutions Issue Solution Graph not displayed Check for invalid characters Blurry exports Ensure full rendering completion Unresponsive touch controls Disable browser gestures Axis display issues Adjust Y-range to include zero Performance Tips Use x**3 instead of Math.pow(x,3)

Avoid >5 nested conditionals

Prefer Line Mode for large datasets

VI. Appendices

Supported Functions Category Examples Trigonometric sin/cos/tan Logarithmic log/log10/log2 Power pow/sqrt/cbrt Special abs/sign/exp
Academic Applications Classroom demonstrations
Research parameter analysis

Algorithm validation

Technical Support: EpiVisionPro@outlook.com Version Control: [April 5, 2025]
