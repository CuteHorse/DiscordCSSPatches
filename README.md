Use at your own risk :3


quick use (12.2025 version):
```css
div[aria-hidden="true"][style*="background:"] {
  background: none !important;
  background-image: none !important;
}

div[class*="interactive"] > div[aria-hidden="true"][class*="fadeIn"] {
  background: none !important;
  background-image: none !important;
  box-shadow: none !important;
  filter: none !important;
}

div[class*="interactive"] > div[aria-hidden="true"][class*="fadeIn"] img {
  display: none !important;
  -webkit-mask-image: none !important;
  mask-image: none !important;
}

div[class*="interactiveSelected"]::before,
div[class*="interactiveSelected"]::after {
  background: none !important;
}

div[class*="nameplated"] > div[aria-hidden="true"][class*="container"] {
  background: none !important;
  background-image: none !important;
  box-shadow: none !important;
}

div[class*="nameplated"] > div[aria-hidden="true"][class*="container"] > img[class*="-img"] {
  display: none !important;
  -webkit-mask-image: none !important;
  mask-image: none !important;
}


[class*="clanTag"],
[class*="clanTagChiplet"],
[class*="tagText"],
[class*="clanBadge"],
[class*="chipletContainerInner"][aria-label*="Server Tag"],
[class*="chipletContainerInline"][aria-label*="Server Tag"] {
  display: none !important;
}
```
