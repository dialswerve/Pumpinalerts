# Meme Coin Alert App Design Guidelines

## Design Approach
**System-Based Approach**: Given the utility-focused nature of this crypto trading tool, I'm selecting a **Fluent Design System** approach for its excellent handling of data-dense interfaces and productivity applications. This ensures optimal usability for traders who need quick, accurate information access.

## Core Design Elements

### Color Palette
**Dark Mode Primary** (crypto trading standard):
- Background: 220 15% 8%
- Surface: 220 15% 12%
- Primary accent: 45 100% 60% (golden yellow for alerts/notifications)
- Success: 120 60% 50% (price gains)
- Danger: 0 70% 55% (price drops)
- Text primary: 0 0% 95%
- Text secondary: 0 0% 70%

**Light Mode** (optional):
- Background: 0 0% 98%
- Surface: 0 0% 100%
- Primary accent: 45 90% 45%

### Typography
- **Primary**: Inter (Google Fonts) - excellent for data readability
- **Monospace**: JetBrains Mono (Google Fonts) - for addresses and numerical values
- Sizes: text-xs, text-sm, text-base, text-lg, text-xl for hierarchy

### Layout System
**Tailwind Spacing Units**: Consistent use of 2, 4, 6, 8, 12, 16 units
- Micro spacing: p-2, m-2
- Standard spacing: p-4, gap-4
- Section spacing: p-6, mb-8
- Container spacing: p-8, max-w-4xl

### Component Library

**Input Components**:
- Contract address input with Solana address validation styling
- Price alert input with SOL currency indicator
- Volume slider with percentage display
- Dropdown with crypto-themed styling

**Data Display**:
- Horizontal table with alternating row backgrounds
- Monospace font for addresses, prices, and numerical data
- Color-coded price changes (green/red)
- Token age with relative time formatting

**Audio Controls**:
- Minimal player with rounded controls
- Play/stop buttons with crypto-themed icons
- Volume slider with gradient fill
- Alert frequency radio buttons with clear visual states

**Alert System**:
- Toast notifications for price alerts
- Visual indicators for active monitoring
- Status badges for alert states

### Layout Structure
1. **Header**: App title with pump.fun branding reference
2. **Input Section**: Contract address field with validation
3. **Token Info Table**: Horizontal layout displaying key metrics
4. **Alert Configuration**: Price input, sound selection, and frequency options
5. **Audio Preview**: Mini player with volume controls

### Visual Hierarchy
- Use card-based layouts with subtle shadows
- Clear section dividers
- Prominent CTA styling for "Set Alert" button
- Consistent icon usage from Heroicons
- Responsive grid system for mobile optimization

### No Images Required
This utility app focuses on data display and functionality rather than visual marketing elements. No hero images or decorative graphics needed.

### Key UX Principles
- **Speed**: Instant feedback for all interactions
- **Clarity**: Clear visual states for monitoring status
- **Accessibility**: High contrast ratios for trading environments
- **Responsiveness**: Mobile-first design for on-the-go trading