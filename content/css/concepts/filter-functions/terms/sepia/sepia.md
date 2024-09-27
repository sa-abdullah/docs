---
Title: 'sepia()'
Description: 'Changes the color of an element to sepia.'
Subjects:
  - 'Web Development'
  - 'Web Design'
Tags:
  - 'Images'
  - 'Functions'
  - 'Colors'
CatalogContent:
  - 'learn-css'
  - 'paths/front-end-engineer-career-path'
  - 'paths/full-stack-engineer-career-path'
---

Changes the color of an element to sepia.

## Syntax

```css
filter: sepia(<value>);
```

where a required `<value>` can be one of the following:

- Number value: `0`, `1`
- Percentage value: `10%`, `50%`

**Note:** Value defaults to `1` or `100%` turning the element to sepia. A value of `0` and `0%` will leave element unchanged. Negative values as well as values greater than `1` or `100%` are not allowed.

## Example 1

Set sepia to `100%`:

```css
.banner-image {
  filter: sepia(100%);
}
```
![Output for the above example on sepia()]([media/css-filterfunction-sepia.png](https://github.com/sa-abdullah/docs/blob/954f9125984980adf13c1351a3d342c745cc67a4/media/css-filterfunction-sepia.png))
Here, the first image shows the original sepia filter at sepia(100%), the second image sets the sepia filter at sepia(50%), while the third image sets it at sepia(5%)

