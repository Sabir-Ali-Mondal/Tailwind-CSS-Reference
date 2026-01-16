# Tailwind CSS – Complete Practical Reference

## 1. Layout & Display

| Class | Purpose |
| :--- | :--- |
| `block` | Displays element as a block-level element |
| `inline-block` | Displays as inline-level block container |
| `inline` | Displays as an inline element |
| `flex` | Enables flex context for children |
| `grid` | Enables grid context for children |
| `hidden` | Sets display to none (removes from flow) |

## 2. Flexbox

| Category | Classes | Purpose |
| :--- | :--- | :--- |
| **Direction** | `flex-row`, `flex-row-reverse` | Horizontal arrangement |
| | `flex-col`, `flex-col-reverse` | Vertical arrangement |
| **Wrap** | `flex-wrap`, `flex-nowrap` | Controls wrapping behavior |
| **Align Items** | `items-start`, `items-center` | Vertical alignment (in row) |
| | `items-end`, `items-stretch` | Vertical alignment (in row) |
| **Justify** | `justify-start`, `justify-center` | Horizontal alignment (in row) |
| | `justify-between`, `justify-end` | Spacing distribution |
| **Grow/Shrink** | `flex-1` | Allow item to grow and fill space |
| | `flex-none` | Prevent resizing |

## 3. Grid

| Category | Classes | Purpose |
| :--- | :--- | :--- |
| **Columns** | `grid-cols-{n}` | Sets number of columns (1, 2, 3... 12) |
| **Gap** | `gap-{n}` | Sets gutter size between rows and cols |
| | `gap-x-{n}`, `gap-y-{n}` | Specific horizontal or vertical gaps |
| **Span** | `col-span-{n}` | Makes element span n columns |
| | `col-span-full` | Makes element span full width |

## 4. Spacing & Alignment

*Pattern: `{property}{side}-{size}`*
*Properties: `m` (Margin), `p` (Padding). Sides: `t, b, l, r, x, y`.*

| Class | Purpose |
| :--- | :--- |
| `p-4` | Padding on all sides (1rem / 16px) |
| `px-6` | Horizontal padding (1.5rem / 24px) |
| `py-2` | Vertical padding (0.5rem / 8px) |
| `mt-4` | Margin top (1rem / 16px) |
| `-mt-4` | Negative margin (pull element up) |
| `mx-auto` | **Horizontally center block container** |
| `my-auto` | Vertically center (requires flex/grid context) |

## 5. Width & Height

| Category | Classes | Purpose |
| :--- | :--- | :--- |
| **Width** | `w-{n}` | Fixed width scale (e.g., w-4, w-12, w-64) |
| | `w-full` | 100% width |
| | `w-screen` | 100vw width |
| | `w-1/2`, `w-1/3` | Percentage based width |
| | `max-w-screen-lg` | Constrain width on large screens |
| **Height** | `h-{n}` | Fixed height scale |
| | `h-full` | 100% height (of parent) |
| | `h-screen` | 100vh height |
| | `min-h-screen` | Minimum height 100vh (full viewport) |

## 6. Typography

| Category | Classes | Purpose |
| :--- | :--- | :--- |
| **Size** | `text-xs`, `text-sm` | Small text |
| | `text-base` | Default size (16px) |
| | `text-lg`, `text-xl` ... `text-9xl` | Larger headings |
| **Weight** | `font-normal`, `font-medium` | 400, 500 weight |
| | `font-semibold`, `font-bold` | 600, 700 weight |
| **Alignment** | `text-left`, `text-center`, `text-right` | Text alignment |
| **Line Height** | `leading-none`, `leading-tight` | Line spacing/height |
| **Utilities** | `uppercase`, `capitalize` | Text transform |
| | `truncate` | Ellipsis overflow (...) |

## 7. Colors

*Pattern: `{property}-{color}-{shade}` (Shades: 50, 100... 900, 950)*

| Property | Example | Purpose |
| :--- | :--- | :--- |
| **Background** | `bg-blue-500` | Sets background color |
| | `bg-white`, `bg-transparent` | Common utilities |
| **Text** | `text-gray-900` | Sets font color |
| **Border** | `border-red-500` | Sets border color |
| **Opacity Mod** | `bg-black/50` | Sets color with 50% alpha |

## 8. Border & Radius

| Category | Classes | Purpose |
| :--- | :--- | :--- |
| **Width** | `border`, `border-2`, `border-4` | Border thickness |
| | `border-0`, `border-t` | Remove border or specific side |
| **Radius** | `rounded` | Small radius (4px) |
| | `rounded-md`, `rounded-lg` | Medium/Large radius |
| | `rounded-full` | Pill shape or circle |
| **Divide** | `divide-y`, `divide-x` | Adds borders between children |

## 9. Positioning

| Category | Classes | Purpose |
| :--- | :--- | :--- |
| **Position** | `relative` | Position relative |
| | `absolute` | Position absolute |
| | `fixed` | Fixed to viewport |
| | `sticky` | Sticky scroll behavior |
| **Placement** | `top-0`, `bottom-0` | Zero offset |
| | `left-0`, `right-0` | Zero offset |
| | `inset-0` | Top, right, bottom, left = 0 |

## 10. Z-Index & Overflow

| Category | Classes | Purpose |
| :--- | :--- | :--- |
| **Z-Index** | `z-0`, `z-10` ... `z-50` | Stack order |
| **Overflow** | `overflow-hidden` | Clip content |
| | `overflow-auto` | Add scrollbars only if needed |
| | `overflow-x-scroll` | Force horizontal scroll |

## 11. Effects

| Class | Purpose |
| :--- | :--- |
| `shadow-sm` | Small box shadow |
| `shadow` | Default box shadow |
| `shadow-lg`, `shadow-xl` | Large elevation shadows |
| `shadow-none` | Remove shadow |
| `opacity-0` ... `opacity-100` | Transparency level |

## 12. Transitions & Transform

| Category | Classes | Purpose |
| :--- | :--- | :--- |
| **Transition** | `transition`, `transition-all` | Enable transition effects |
| **Duration** | `duration-300`, `duration-500` | Speed in ms |
| **Ease** | `ease-in-out` | Timing function |
| **Scale** | `scale-95`, `scale-105` | Zoom size |
| **Rotate** | `rotate-45`, `rotate-180` | Rotation |
| **Translate** | `translate-x-full` | Move element (used for drawers) |

## 13. Cursor & Selection

| Class | Purpose |
| :--- | :--- |
| `cursor-pointer` | Shows pointer (hand) on hover |
| `cursor-not-allowed` | Shows forbidden sign |
| `select-none` | Prevents user from highlighting text |

## 14. Forms & Input Utilities

| Class | Purpose |
| :--- | :--- |
| `appearance-none` | Remove default browser styling |
| `outline-none` | Remove default focus outline |
| `focus:outline-none` | Remove outline on focus (pair with ring) |
| `placeholder-gray-400` | Placeholder text color |

## 15. Ring Utilities (Focus System)

*Modern replacement for borders/outlines on inputs and buttons.*

| Class | Purpose |
| :--- | :--- |
| `ring-1`, `ring-2` | Ring thickness |
| `ring-blue-500` | Ring color |
| `ring-offset-2` | Space between ring and element |
| `focus:ring-2` | Show ring on focus interaction |

## 16. Object Fit & Images

| Class | Purpose |
| :--- | :--- |
| `object-cover` | Fill container without distortion (crop) |
| `object-contain` | Fit entire image within container |
| `object-center` | Center image position |

## 17. Aspect Ratio

| Class | Purpose |
| :--- | :--- |
| `aspect-square` | 1:1 ratio (perfect square) |
| `aspect-video` | 16:9 ratio (video embeds) |

## 18. Lists & Tables

| Class | Purpose |
| :--- | :--- |
| `list-none` | Remove bullets (navbars/menus) |
| `list-disc` | Bullet list |
| `list-decimal` | Numbered list |
| `border-collapse` | Merge table borders |
| `table-auto` | Auto column sizing |

## 19. Responsive System (Mobile-First)

**Rule:** Unprefixed classes are for **mobile**. Prefixed classes apply from that breakpoint **and up**.

| Prefix | Min Width | Usage Example |
| :--- | :--- | :--- |
| `sm:` | 640px | `sm:w-1/2` (50% width on mobile landscape+) |
| `md:` | 768px | `md:flex` (Flexbox on tablets+) |
| `lg:` | 1024px | `lg:grid-cols-3` (3 cols on laptops+) |
| `xl:` | 1280px | `xl:p-8` (Large padding on desktops) |

**Common Pattern:**
`grid-cols-1 md:grid-cols-2 lg:grid-cols-4`
*(1 col mobile -> 2 cols tablet -> 4 cols desktop)*

## 20. State Variants (Interaction)

**Rule:** Apply styles only when specific states are active.

| Prefix | Trigger | Example |
| :--- | :--- | :--- |
| `hover:` | Mouse over | `hover:bg-blue-600` |
| `focus:` | Input/Key focus | `focus:ring-2` |
| `active:` | Click press | `active:scale-95` |
| `disabled:` | Input disabled | `disabled:opacity-50` |

**Group Hover:**
Style a child when the *parent* is hovered.
1. Add `group` to parent.
2. Add `group-hover:{class}` to child.

## 21. Professional Usage Rules

1.  **Structure:** Use `flex`, `grid`, `padding`, `margin` for layout.
2.  **Responsiveness:** Mobile-first always. Don't write `max-width` media queries manually.
3.  **Interaction:** Use `hover:`, `focus:`, `active:` for clear UI feedback.
4.  **Consistency:** Stick to the scale (p-4, p-8, p-12). Don't use arbitrary values (p-[13px]) unless absolutely necessary.
