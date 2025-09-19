# Design Guidelines: AI Internship Recommender

## Design Approach
**Reference-Based Approach**: Drawing inspiration from accessible government portals and educational platforms like Khan Academy, focusing on simplicity and clarity for users with varying digital literacy levels.

## Core Design Elements

### A. Color Palette
**Primary Colors (Indian Tricolor Theme):**
- Saffron: 25 85% 60% 
- White: 0 0% 98%
- Green: 140 70% 45%
- Dark text: 0 0% 15%
- Light gray: 0 0% 95%

**Dark Mode:**
- Dark background: 0 0% 12%
- Card backgrounds: 0 0% 18% 
- Saffron (adjusted): 25 75% 65%
- Green (adjusted): 140 60% 50%

### B. Typography
- **Primary Font**: Inter (Google Fonts) - excellent multilingual support
- **Headers**: Bold weights (600-700) for clear hierarchy
- **Body**: Regular (400) and medium (500) weights
- **Sizes**: Larger than typical (18px+ body text) for accessibility

### C. Layout System
**Tailwind Spacing**: Consistent use of 4, 6, 8, 12, 16 units
- Forms: p-6, gap-4
- Cards: p-8, m-4
- Sections: py-12, px-6

### D. Component Library

**Core Components:**
- **Large Touch-Friendly Buttons**: Minimum 44px height, rounded corners
- **Simple Form Inputs**: Clear labels, generous padding, high contrast borders
- **Card-Based Layout**: Clean white cards with subtle shadows
- **Language Switcher**: Prominent toggle between English/Hindi/Regional
- **Progress Indicators**: Simple step-by-step visual guidance
- **Icon Integration**: Heroicons for consistent, recognizable symbols

**Accessibility Features:**
- High contrast ratios (4.5:1 minimum)
- Large clickable areas
- Clear focus states with tricolor accent borders
- Simple navigation patterns

## Key Design Principles

1. **Simplicity First**: Minimal cognitive load with clear, single-purpose screens
2. **Cultural Relevance**: Tricolor elements as subtle accents, not overwhelming
3. **Mobile-First**: Optimized for smartphones with touch-friendly interactions
4. **Progressive Disclosure**: Show only essential information at each step
5. **Visual Hierarchy**: Use color and typography to guide users naturally

## Layout Strategy
- Single-column layouts on mobile
- Maximum 2-column on desktop
- Generous whitespace between sections
- Sticky language switcher in header
- Bottom navigation for primary actions

## Interactive Elements
- Form validation with clear, friendly error messages
- Loading states with tricolor progress indicators
- Success animations using green checkmarks
- Gentle hover effects without overwhelming users

## Images
**Hero Section**: Clean illustration of diverse students/professionals (not photograph) representing different backgrounds, placed prominently above the main form. Should be optimistic and inclusive.

**Icon Usage**: Simple line icons throughout for skills, education levels, and location - using Heroicons library for consistency.

This design prioritizes accessibility, cultural sensitivity, and ease of use for the target demographic while maintaining a professional appearance suitable for career development.