# Suttram — Brand Colours

**Version:** 1.0  
**Status:** Approved / frozen  
**Approved:** 25 October 2026  
**Scope:** Suttram app, website and related brand assets

## Approved colour palette

| Colour | Tamil name | Token name | HEX | RGB |
| --- | --- | --- | --- | --- |
| Yellow | மஞ்சள் | `MANJAL` | `#F2AE0A` | `242, 174, 10` |
| Orange | மகிழ்ச்சி | `MAGIZHCHI` | `#F26515` | `242, 101, 21` |
| Crimson | உயிர் | `UYIR` | `#B6072C` | `182, 7, 44` |
| Pink | அன்பு | `ANBU` | `#CF3F5D` | `207, 63, 93` |
| Green | வளர்ச்சி | `VALARCHI` | `#50AF67` | `80, 175, 103` |
| Blue | மழலை | `MAZHALAI` | `#2D7ECA` | `45, 126, 202` |

## CSS variables

```css
:root {
  --suttram-manjal: #f2ae0a;
  --suttram-magizhchi: #f26515;
  --suttram-uyir: #b6072c;
  --suttram-anbu: #cf3f5d;
  --suttram-valarchi: #50af67;
  --suttram-mazhalai: #2d7eca;
}
```

## TypeScript tokens

```ts
export const suttramBrandColors = {
  manjal: '#F2AE0A',
  magizhchi: '#F26515',
  uyir: '#B6072C',
  anbu: '#CF3F5D',
  valarchi: '#50AF67',
  mazhalai: '#2D7ECA',
} as const;
```

## Usage notes

1. These six HEX values are **representative colour samples** from the approved, brighter Suttram icon. The icon uses smooth multi-shade gradients; it is not composed of six flat HEX fills.
2. **Use the approved icon image directly.** Do not regenerate or redraw the logo from these tokens, replace its gradients with flat colours, or add a border.
3. The approved app icon is a **1024 × 1024 transparent PNG**. An actual editable vector master matching this final bitmap has **not** been approved; a PNG embedded in an SVG does not count as a true vector logo.
4. For application UI, these values may be used as accent tokens, but choose text/background combinations based on contrast and accessibility; no colour is automatically approved for body text.
5. `VALARCHI` (வளர்ச்சி) replaces the earlier English token `GROWTH`. Its HEX value is unchanged.

## Approved icon

[Suttram — final transparent PNG](https://chatgpt.com/library?file_id=libfile_dbc36aa734f88191b9b9372c68d07352&account_id=personal)

**Change control:** Do not adjust the frozen icon or palette without a new explicit approval.
