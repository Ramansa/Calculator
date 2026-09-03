# 🧮 Modern Scientific & Basic Web Calculator

A sleek, responsive, and standalone online calculator built with pure HTML5, CSS3, and modern Vanilla JavaScript. It combines standard daily arithmetic with a collapsible scientific function drawer, live calculation previews, customizable theme appearance, and fullscreen mode tailored for mobile and desktop screens.

---

## ✨ Features

- **Dual Mode (Standard & Scientific)**
  - **Basic Operations**: Addition, subtraction, multiplication, division, parentheses, and percentages.
  - **Collapsible Scientific Panel**: Trigonometric functions (`sin`, `cos`, `tan`), logarithmic functions (`ln`, `log`), constants (`π`, `e`), square root (`√`), power (`^`), and factorials (`!`).
  - **Angle Units**: Toggle between Radians (`RAD`) and Degrees (`DEG`).
- **Live Calculation Preview**: View real-time calculated results as you type before finalizing with `=`.
- **Customizable Appearance & Themes**:
  - Modal color picker to configure page background, calculator shell, buttons, text, and accent colors.
  - Supports standard 3- and 6-digit hex values as well as native color picker inputs.
  - One-click default reset button.
- **Mobile-First & Touch-Optimized**:
  - CSS Grid-accordion drawer transition preventing layout clipping on smaller viewports.
  - Safe-area inset support (`viewport-fit=cover`) for notches and modern mobile status bars.
  - Tactile ripple effects and active states on touch.
  - Pull-to-refresh and accidental browser zoom disabled for a native app feel.
- **Fullscreen Mode**: Header action button allowing quick toggling into full-screen view.
- **Full Keyboard & Clipboard Support**:
  - Full numeric keypad mapping with `Enter` to evaluate, `Backspace` to step back, and `Esc` to clear.
  - Direct expression pasting from clipboard (e.g., `(25 * 4) + 10`).
- **Persistent State**: Current inputs, calculation history, angle settings, and custom color themes are retained across sessions via `localStorage`.

---

## 🚀 Getting Started

### Prerequisites

No external libraries, build tools, or package managers (`npm`, `yarn`) are required. The entire application runs within a single standalone file.

### Installation & Launch

1. Clone or download the repository:
   ```bash
   git clone [https://github.com/Ramansa/Calculator.git](https://github.com/Ramansa/Calculator.git)
   cd online-calculator
