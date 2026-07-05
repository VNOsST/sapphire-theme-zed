# Sapphire Theme to Zed Theme Mapping Plan

## Color Palette (from opencode Sapphire)

### Base Colors
| Token | Hex | Description |
|-------|-----|-------------|
| bgDark | #080d14 | Very dark blue (main background) |
| bgPanel | #090f18 | Slightly lighter dark blue (panels) |
| bgElement | #0c1420 | Dark blue-gray (elements/cards) |
| fg | #efefef | Near white (main text) |
| fgMuted | #535a6b | Grayish blue (muted text) |
| border | #263040 | Dark blue-gray (borders) |
| primary | #399EF4 | Bright blue (accent/primary) |
| cyan | #21C5C7 | Cyan/teal |
| green | #4EB071 | Muted green |
| yellow | #fff099 | Pale yellow |
| red | #DA6771 | Muted red/pink |
| magenta | #B168DF | Purple |
| gray | #535a6b | Same as fgMuted |

---

## Mapping to Zed Schema Properties

### 1. Background Colors
| Zed Property | Value | Notes |
|--------------|-------|-------|
| background | #080d14 | App background |
| surface.background | #090f18 | Panel/tab surfaces |
| elevated_surface.background | #0c1420 | Context menus, popups |
| editor.background | #080d14 | Editor pane |
| panel.background | #090f18 | Bottom/side panels |
| status_bar.background | #090f18 | Status bar |
| title_bar.background | #090f18 | Window title bar |
| toolbar.background | #090f18 | Toolbar area |
| tab_bar.background | #090f18 | Tab bar |
| tab.active_background | #080d14 | Active tab |
| tab.inactive_background | #090f18 | Inactive tabs |

### 2. Text Colors
| Zed Property | Value | Notes |
|--------------|-------|-------|
| text | #efefef | Default text |
| text.muted | #535a6b | De-emphasized text |
| text.placeholder | #535a6b | Placeholder text in inputs |
| text.accent | #399EF4 | Highlighted/active text |
| text.disabled | #535a6b80 | Disabled text (50% opacity) |

### 3. Border Colors
| Zed Property | Value | Notes |
|--------------|-------|-------|
| border | #263040 | Default borders |
| border.focused | #399EF4 | Focused elements |
| border.selected | #399EF4 | Selected elements |
| border.disabled | #26304080 | Disabled elements |
| border.variant | #263040 | De-emphasized/dividers |
| border.transparent | transparent | Placeholder borders |
| pane_group.border | #263040 | Pane dividers |
| pane.focused_border | #399EF4 | Focused pane border |

### 4. Element States
| Zed Property | Value | Notes |
|--------------|-------|-------|
| element.background | #0c1420 | Element background |
| element.hover | #111a28 | Hovered elements |
| element.active | #080d14 | Active/pressed elements |
| element.selected | #399EF433 | Selected elements (20% opacity) |
| element.disabled | #0c142080 | Disabled elements |
| ghost_element.background | transparent | Ghost element bg |
| ghost_element.hover | #ffffff0a | Ghost hover |
| ghost_element.active | #ffffff14 | Ghost active |
| ghost_element.selected | #399EF433 | Ghost selected |
| ghost_element.disabled | transparent | Ghost disabled |

### 5. Semantic Colors
| Zed Property | Value | Notes |
|--------------|-------|-------|
| error | #DA6771 | Error state |
| error.background | #DA677126 | Error background (15% opacity) |
| error.border | #DA677180 | Error border (50% opacity) |
| warning | #fff099 | Warning state |
| warning.background | #fff09926 | Warning background |
| warning.border | #fff09980 | Warning border |
| success | #4EB071 | Success state |
| success.background | #4EB07126 | Success background |
| success.border | #4EB07180 | Success border |
| info | #399EF4 | Info state |
| info.background | #399EF426 | Info background |
| info.border | #399EF480 | Info border |
| hint | #535a6b | Hint state |
| hint.background | #535a6b26 | Hint background |
| hint.border | #535a6b80 | Hint border |
| conflict | #B168DF | Conflict state |
| conflict.background | #B168DF26 | Conflict background |
| conflict.border | #B168DF80 | Conflict border |
| unreachable | #535a6b | Unreachable code |
| unreachable.background | #535a6b26 | Unreachable bg |
| unreachable.border | #535a6b80 | Unreachable border |

### 6. Git Status Colors
| Zed Property | Value | Notes |
|--------------|-------|-------|
| created | #4EB071 | New files |
| created.background | #4EB07126 | New file bg |
| created.border | #4EB07180 | New file border |
| modified | #fff099 | Modified files |
| modified.background | #fff09926 | Modified file bg |
| modified.border | #fff09980 | Modified file border |
| deleted | #DA6771 | Deleted files |
| deleted.background | #DA677126 | Deleted file bg |
| deleted.border | #DA677180 | Deleted file border |
| renamed | #399EF4 | Renamed files |
| renamed.background | #399EF426 | Renamed bg |
| renamed.border | #399EF480 | Renamed border |
| ignored | #535a6b | Ignored files |
| ignored.background | #535a6b26 | Ignored bg |
| ignored.border | #535a6b80 | Ignored border |
| hidden | #535a6b | Hidden files |
| hidden.background | #535a6b26 | Hidden bg |
| hidden.border | #535a6b80 | Hidden border |
| predictive | #B168DF | AI predictions |
| predictive.background | #B168DF26 | Predictive bg |
| predictive.border | #B168DF80 | Predictive border |

### 7. Editor Elements
| Zed Property | Value | Notes |
|--------------|-------|-------|
| editor.active_line.background | #0c1420 | Current line highlight |
| editor.active_line_number | #efefef | Active line number |
| editor.gutter.background | #080d14 | Line number gutter |
| editor.line_number | #535a6b | Line numbers |
| editor.indent_guide | #26304040 | Indent guides |
| editor.indent_guide_active | #399EF466 | Active indent guide |
| editor.wrap_guide | #26304040 | Wrap guide |
| editor.active_wrap_guide | #399EF466 | Active wrap guide |
| editor.invisible | #535a6b | Invisible chars |
| editor.highlighted_line.background | #399EF414 | Search result line |
| editor.subheader.background | #090f18 | Breadcrumb bar |
| editor.document_highlight.read_background | #399EF414 | Symbol read highlight |
| editor.document_highlight.write_background | #399EF426 | Symbol write highlight |
| editor.document_highlight.bracket_background | #399EF433 | Bracket highlight |
| editor.foreground | #efefef | Editor foreground |

### 8. UI Elements
| Zed Property | Value | Notes |
|--------------|-------|-------|
| icon | #efefef | Default icon color |
| icon.accent | #399EF4 | Accent icon |
| icon.muted | #535a6b | Muted icon |
| icon.disabled | #535a6b80 | Disabled icon |
| icon.placeholder | #535a6b | Placeholder icon |
| link_text.hover | #399EF4 | Link hover color |
| search.match_background | #399EF433 | Search match highlight |
| drop_target.background | #399EF426 | Drop target highlight |

### 9. Scrollbar
| Zed Property | Value | Notes |
|--------------|-------|-------|
| scrollbar.thumb.background | #26304080 | Scrollbar thumb |
| scrollbar.thumb.border | transparent | Thumb border |
| scrollbar.thumb.hover_background | #535a6b80 | Thumb hover |
| scrollbar.track.background | transparent | Track background |
| scrollbar.track.border | transparent | Track border |

### 10. Panel Specific
| Zed Property | Value | Notes |
|--------------|-------|-------|
| panel.indent_guide | #26304040 | Panel indent guide |
| panel.indent_guide_active | #399EF466 | Active panel indent |
| panel.indent_guide_hover | #535a6b40 | Hovered indent guide |
| panel.focused_border | #399EF4 | Focused panel border |

### 11. Terminal ANSI Colors
| Zed Property | Value | Notes |
|--------------|-------|-------|
| terminal.background | #080d14 | Terminal bg |
| terminal.foreground | #efefef | Terminal text |
| terminal.bright_foreground | #ffffff | Bright text |
| terminal.dim_foreground | #535a6b | Dim text |
| terminal.ansi.background | #080d14 | ANSI bg |
| terminal.ansi.black | #080d14 | Black |
| terminal.ansi.bright_black | #535a6b | Bright black |
| terminal.ansi.dim_black | #263040 | Dim black |
| terminal.ansi.red | #DA6771 | Red |
| terminal.ansi.bright_red | #E8828B | Bright red |
| terminal.ansi.dim_red | #A44F57 | Dim red |
| terminal.ansi.green | #4EB071 | Green |
| terminal.ansi.bright_green | #6CC88D | Bright green |
| terminal.ansi.dim_green | #3A8A59 | Dim green |
| terminal.ansi.yellow | #fff099 | Yellow |
| terminal.ansi.bright_yellow | #FFF4B8 | Bright yellow |
| terminal.ansi.dim_yellow | #CCBF7A | Dim yellow |
| terminal.ansi.blue | #399EF4 | Blue |
| terminal.ansi.bright_blue | #6BB8F7 | Bright blue |
| terminal.ansi.dim_blue | #2D7EC4 | Dim blue |
| terminal.ansi.magenta | #B168DF | Magenta |
| terminal.ansi.bright_magenta | #C58EEC | Bright magenta |
| terminal.ansi.dim_magenta | #8E53B3 | Dim magenta |
| terminal.ansi.cyan | #21C5C7 | Cyan |
| terminal.ansi.bright_cyan | #4DD4D6 | Bright cyan |
| terminal.ansi.dim_cyan | #1A9E9F | Dim cyan |
| terminal.ansi.white | #efefef | White |
| terminal.ansi.bright_white | #ffffff | Bright white |
| terminal.ansi.dim_white | #535a6b | Dim white |

### 12. Players (Multi-cursor colors)
| Player | Background | Cursor | Selection |
|--------|------------|--------|-----------|
| Player 1 | #399EF426 | #399EF4 | #399EF433 |
| Player 2 | #21C5C726 | #21C5C7 | #21C5C733 |
| Player 3 | #4EB07126 | #4EB071 | #4EB07133 |
| Player 4 | #fff09926 | #fff099 | #fff09933 |
| Player 5 | #DA677126 | #DA6771 | #DA677133 |
| Player 6 | #B168DF26 | #B168DF | #B168DF33 |

### 13. Syntax Highlighting
| Zed Syntax Node | Opencode Token | Hex | Style |
|-----------------|----------------|-----|-------|
| comment | syntaxComment | #535a6b | italic |
| comment.line | syntaxComment | #535a6b | italic |
| comment.block | syntaxComment | #535a6b | italic |
| keyword | syntaxKeyword | #399EF4 | |
| keyword.control | syntaxKeyword | #399EF4 | |
| keyword.function | syntaxKeyword | #399EF4 | |
| keyword.operator | syntaxOperator | #399EF4 | |
| keyword.storage | syntaxKeyword | #399EF4 | |
| keyword.storage.type | syntaxType | #4EB071 | |
| function | syntaxFunction | #fff099 | |
| function.macro | syntaxFunction | #fff099 | |
| function.method | syntaxFunction | #fff099 | |
| variable | syntaxVariable | #21C5C7 | |
| variable.parameter | syntaxVariable | #21C5C7 | |
| variable.other | syntaxVariable | #21C5C7 | |
| string | syntaxString | #DA6771 | |
| string.regexp | syntaxString | #DA6771 | |
| string.special | syntaxString | #DA6771 | |
| number | syntaxNumber | #DA6771 | |
| number.integer | syntaxNumber | #DA6771 | |
| number.float | syntaxNumber | #DA6771 | |
| type | syntaxType | #4EB071 | |
| type.class | syntaxType | #4EB071 | |
| type.enum | syntaxType | #4EB071 | |
| type.builtin | syntaxType | #4EB071 | |
| operator | syntaxOperator | #399EF4 | |
| operator.special | syntaxOperator | #399EF4 | |
| punctuation | syntaxPunctuation | #efefef | |
| punctuation.bracket | syntaxPunctuation | #efefef | |
| punctuation.delimiter | syntaxPunctuation | #efefef | |
| constant | syntaxNumber | #DA6771 | |
| constant.numeric | syntaxNumber | #DA6771 | |
| constant.language | syntaxKeyword | #399EF4 | |
| constant.character | syntaxString | #DA6771 | |
| tag | syntaxKeyword | #399EF4 | |
| attribute | syntaxVariable | #21C5C7 | |
| namespace | syntaxType | #4EB071 | |
| macro | syntaxFunction | #fff099 | |
| derived | syntaxType | #4EB071 | |
| escape | syntaxString | #B168DF | |
| embed | syntaxVariable | #21C5C7 | |
| link_uri | syntaxVariable | #21C5C7 | |
| link_text | syntaxFunction | #fff099 | |
| emphasis | markdownEmph | #efefef | italic |
| strong | markdownStrong | #efefef | bold |
| heading | markdownHeading | #399EF4 | bold |
| list | markdownListItem | #399EF4 | |
| meta | syntaxKeyword | #399EF4 | |
| title | markdownHeading | #399EF4 | bold |

### 14. Accents Array
```json
["#399EF4", "#21C5C7", "#4EB071", "#fff099", "#DA6771", "#B168DF"]
```

---

## Notes

1. **Opacity Handling**: Many colors use hex with alpha channel (8-digit hex) for semi-transparent effects
2. **Color Variants**: Some properties need lighter/darker variants derived from base colors
3. **Syntax Mapping**: Zed uses Tree-sitter node types for syntax highlighting
4. **Player Colors**: Multi-cursor support requires 6 player color sets
5. **Theme Structure**: Zed requires `author`, `name`, and `themes` array (can contain multiple variants)

## Implementation Strategy

1. Create the base Zed theme JSON structure
2. Map all colors according to the tables above
3. Use 8-digit hex for semi-transparent colors (e.g., #RRGGBBAA)
4. Include comprehensive syntax highlighting
5. Add player colors for multi-cursor support
6. Validate against the Zed schema
