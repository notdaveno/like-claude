# Like Claude Theme Showcase

A Typora theme inspired by the Claude documentation site — warm paper tones, serif typography, and careful spacing. 这一段用来展示中英文混排时 Noto Serif 与 Noto Serif SC 的衔接效果。

## Typography & Inline Styles

Body text uses **Noto Serif** for Latin and **Noto Serif SC** for CJK. You can *emphasize* words, mark them as **strong**, insert `inline code`, add ==highlights==, and link to [the theme repository](https://github.com/notdaveno/like-claude).

### A Subsection

> "Good typography is invisible. Great typography is felt."
>
> — Someone who cared about margins

## Code

Fenced blocks get full CodeMirror syntax highlighting:

```python
def greet(name: str) -> str:
    """Return a warm greeting."""
    message = f"Hello, {name}!"
    return message

# Numbers, strings & keywords each get distinct colors
for i in range(3):
    print(greet("Typora"))
```

## Tables & Lists

| Element   | Light Theme | Dark Theme |
| :-------- | :---------: | ---------: |
| Background| `#FAF9F5`   | `#1A1917`  |
| Accent    | `#CC785C`   | `#D2856B`  |
| Body Font | Noto Serif  | Noto Serif |

- Sidebar and file tree are fully styled
- Outline panel matches the writing area
- Code blocks use Maple Mono NF CN

1. Install the CSS files
2. Restart Typora
3. Pick the theme from the menu

***

*Designed for long-form writing — essays, notes, and documentation that deserve a calmer page.*
