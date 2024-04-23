# Hackernews Simple Dark Mode Inversion

# Description
The hacker news dark mode via simple inversion setting with OS Dark Mode detection. 
Inspired by: https://news.ycombinator.com/item?id=32800642

# Boost URL
https://arc.net/boost/C1124BC3-3472-4384-9690-ECC6866882B0

# Domain
news.ycombinator.com

# CSS

```
@media (prefers-color-scheme: dark) {
    html { filter:invert(90%) hue-rotate(180deg) }
    body { background: white }
}
```