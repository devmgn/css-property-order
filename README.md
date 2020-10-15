# CSS Property Order

~~http://www.mozilla.org/css/base/content.css~~

```content.css
/* Suggested order:
 * display
 * list-style
 * position
 * float
 * clear
 * width
 * height
 * margin
 * padding
 * border
 * background
 * color
 * font
 * text-decoration
 * text-align
 * vertical-align
 * white-space
 * other text
 * content
 *
 */
```

## 1. "Visual Formatting Model" properties
- [display](https://developer.mozilla.org/docs/Web/CSS/display)
- [flex](https://developer.mozilla.org/docs/Web/CSS/flex)
    - [flex-grow](https://developer.mozilla.org/docs/Web/CSS/flex-grow)
    - [flex-shrink](https://developer.mozilla.org/docs/Web/CSS/flex-shrink)
    - [flex-basis](https://developer.mozilla.org/docs/Web/CSS/flex-basis)
- [flex-flow](https://developer.mozilla.org/docs/Web/CSS/flex-flow)
    - [flex-direction](https://developer.mozilla.org/docs/Web/CSS/flex-direction)
    - [flex-wrap](https://developer.mozilla.org/docs/Web/CSS/flex-wrap)
- [justify-content](https://developer.mozilla.org/docs/Web/CSS/justify-content)
- [align-content](https://developer.mozilla.org/docs/Web/CSS/align-content)
- [align-items](https://developer.mozilla.org/docs/Web/CSS/align-items)
- [align-self](https://developer.mozilla.org/docs/Web/CSS/align-self)
- [order](https://developer.mozilla.org/docs/Web/CSS/order)
- [visibility](https://developer.mozilla.org/docs/Web/CSS/visibility)
- [opacity](https://developer.mozilla.org/docs/Web/CSS/opacity)
- [clip](https://developer.mozilla.org/docs/Web/CSS/clip) _※Deprecated_
- [clip-path](https://developer.mozilla.org/docs/Web/CSS/clip-path)
- [list-style](https://developer.mozilla.org/docs/Web/CSS/list-style)
    - [list-style-type](https://developer.mozilla.org/docs/Web/CSS/list-style-type)
    - [list-style-position](https://developer.mozilla.org/docs/Web/CSS/list-style-position)
    - [list-style-image](https://developer.mozilla.org/docs/Web/CSS/list-style-image)
- [position](https://developer.mozilla.org/docs/Web/CSS/position)
- [top](https://developer.mozilla.org/docs/Web/CSS/top)
- [right](https://developer.mozilla.org/docs/Web/CSS/right)
- [bottom](https://developer.mozilla.org/docs/Web/CSS/bottom)
- [left](https://developer.mozilla.org/docs/Web/CSS/left)
- [z-index](https://developer.mozilla.org/docs/Web/CSS/z-index)
- [float](https://developer.mozilla.org/docs/Web/CSS/float)
- [clear](https://developer.mozilla.org/docs/Web/CSS/clear)
- [transform](https://developer.mozilla.org/docs/Web/CSS/transform)


## 2. "Box Model" properties
- [width](https://developer.mozilla.org/docs/Web/CSS/width)
- [min-width](https://developer.mozilla.org/docs/Web/CSS/min-width)
- [max-width](https://developer.mozilla.org/docs/Web/CSS/max-width)
- [height](https://developer.mozilla.org/docs/Web/CSS/height)
- [min-height](https://developer.mozilla.org/docs/Web/CSS/min-height)
- [max-height](https://developer.mozilla.org/docs/Web/CSS/max-height)
- [margin](https://developer.mozilla.org/docs/Web/CSS/margin)
    - [margin-top](https://developer.mozilla.org/docs/Web/CSS/margin-top)
    - [margin-right](https://developer.mozilla.org/docs/Web/CSS/margin-right)
    - [margin-bottom](https://developer.mozilla.org/docs/Web/CSS/margin-bottom)
    - [margin-left](https://developer.mozilla.org/docs/Web/CSS/margin-left)
- [padding](https://developer.mozilla.org/docs/Web/CSS/padding)
    - [padding-top](https://developer.mozilla.org/docs/Web/CSS/padding-top)
    - [padding-right](https://developer.mozilla.org/docs/Web/CSS/padding-right)
    - [padding-bottom](https://developer.mozilla.org/docs/Web/CSS/padding-bottom)
    - [padding-left](https://developer.mozilla.org/docs/Web/CSS/padding-left)
- [overflow](https://developer.mozilla.org/docs/Web/CSS/overflow)
    - [overflow-x](https://developer.mozilla.org/docs/Web/CSS/overflow-x)
    - [overflow-y](https://developer.mozilla.org/docs/Web/CSS/overflow-y)
- [border](https://developer.mozilla.org/docs/Web/CSS/border)
    - [border-width](https://developer.mozilla.org/docs/Web/CSS/border-width)
        - [border-top-width](https://developer.mozilla.org/docs/Web/CSS/border-top-width)
        - [border-right-width](https://developer.mozilla.org/docs/Web/CSS/border-right-width)
        - [border-bottom-width](https://developer.mozilla.org/docs/Web/CSS/border-bottom-width)
        - [border-left-width](https://developer.mozilla.org/docs/Web/CSS/border-left-width)
    - [border-style](https://developer.mozilla.org/docs/Web/CSS/border-style)
        - [border-top-style](https://developer.mozilla.org/docs/Web/CSS/border-top-style)
        - [border-right-style](https://developer.mozilla.org/docs/Web/CSS/border-right-style)
        - [border-bottom-style](https://developer.mozilla.org/docs/Web/CSS/border-bottom-style)
        - [border-left-style](https://developer.mozilla.org/docs/Web/CSS/border-left-style)
    - [border-color](https://developer.mozilla.org/docs/Web/CSS/border-color)
        - [border-top-color](https://developer.mozilla.org/docs/Web/CSS/border-top-color)
        - [border-right-color](https://developer.mozilla.org/docs/Web/CSS/border-right-color)
        - [border-bottom-color](https://developer.mozilla.org/docs/Web/CSS/border-bottom-color)
        - [border-left-color](https://developer.mozilla.org/docs/Web/CSS/border-left-color)
    - [border-image](https://developer.mozilla.org/docs/Web/CSS/border-image)
        - [border-image-source](https://developer.mozilla.org/docs/Web/CSS/border-image-source)
        - [border-image-slice](https://developer.mozilla.org/docs/Web/CSS/border-image-slice)
        - [border-image-width](https://developer.mozilla.org/docs/Web/CSS/border-image-width)
        - [border-image-outset](https://developer.mozilla.org/docs/Web/CSS/border-image-outset)
        - [border-image-repeat](https://developer.mozilla.org/docs/Web/CSS/border-image-repeat)
    - [border-radius](https://developer.mozilla.org/docs/Web/CSS/border-radius)
        - [border-top-left-radius](https://developer.mozilla.org/docs/Web/CSS/border-top-left-radius)
        - [border-top-right-radius](https://developer.mozilla.org/docs/Web/CSS/border-top-right-radius)
        - [border-bottom-right-radius](https://developer.mozilla.org/docs/Web/CSS/border-bottom-right-radius)
        - [border-bottom-left-radius](https://developer.mozilla.org/docs/Web/CSS/border-bottom-left-radius)
- [box-sizing](https://developer.mozilla.org/docs/Web/CSS/box-sizing)
- [box-shadow](https://developer.mozilla.org/docs/Web/CSS/box-shadow)

## 3. "Background" properties
- [background](https://developer.mozilla.org/docs/Web/CSS/background)
    - [background-image](https://developer.mozilla.org/docs/Web/CSS/background-image)
    - [background-position](https://developer.mozilla.org/docs/Web/CSS/background-position)
    - [background-size](https://developer.mozilla.org/docs/Web/CSS/background-size)
    - [background-repeat](https://developer.mozilla.org/docs/Web/CSS/background-repeat)
    - [background-origin](https://developer.mozilla.org/docs/Web/CSS/background-origin)
    - [background-clip](https://developer.mozilla.org/docs/Web/CSS/background-clip)
    - [background-attachment](https://developer.mozilla.org/docs/Web/CSS/background-attachment)
    - [background-color](https://developer.mozilla.org/docs/Web/CSS/background-color)

## 4. "Font, Text and Color" properties
- [color](https://developer.mozilla.org/docs/Web/CSS/color)
- [font](https://developer.mozilla.org/docs/Web/CSS/font)
    - [font-style](https://developer.mozilla.org/docs/Web/CSS/font-style)
    - [font-variant](https://developer.mozilla.org/docs/Web/CSS/font-variant)
    - [font-weight](https://developer.mozilla.org/docs/Web/CSS/font-weight)
    - [font-stretch](https://developer.mozilla.org/docs/Web/CSS/font-stretch)
    - [font-size](https://developer.mozilla.org/docs/Web/CSS/font-size)
    - [line-height](https://developer.mozilla.org/docs/Web/CSS/line-height)
    - [font-family](https://developer.mozilla.org/docs/Web/CSS/font-family)
- [letter-spacing](https://developer.mozilla.org/docs/Web/CSS/letter-spacing)
- [text-decoration](https://developer.mozilla.org/docs/Web/CSS/text-decoration)
    - [text-decoration-color](https://developer.mozilla.org/docs/Web/CSS/text-decoration-color)
    - [text-decoration-style](https://developer.mozilla.org/docs/Web/CSS/text-decoration-style)
    - [text-decoration-line](https://developer.mozilla.org/docs/Web/CSS/text-decoration-line)
- [text-align](https://developer.mozilla.org/docs/Web/CSS/text-align)
- [text-indent](https://developer.mozilla.org/docs/Web/CSS/text-indent)
- [text-transform](https://developer.mozilla.org/docs/Web/CSS/text-transform)
- [white-space](https://developer.mozilla.org/docs/Web/CSS/white-space)
- [word-break](https://developer.mozilla.org/docs/Web/CSS/word-break)
- [word-spaciing](https://developer.mozilla.org/docs/Web/CSS/word-spacing)
- [word-wrap](https://developer.mozilla.org/docs/Web/CSS/word-wrap)
- [text-shadow](https://developer.mozilla.org/docs/Web/CSS/text-shadow)

## 5. "Table" properties
- [table-layout](https://developer.mozilla.org/docs/Web/CSS/table-layout)
- [border-collapse](https://developer.mozilla.org/docs/Web/CSS/border-collapse)
- [border-spacing](https://developer.mozilla.org/docs/Web/CSS/border-spacing)
- [empty-cells](https://developer.mozilla.org/docs/Web/CSS/empty-cells)
- [caption-side](https://developer.mozilla.org/docs/Web/CSS/caption-side)
- [vertical-align](https://developer.mozilla.org/docs/Web/CSS/vertical-align)

## 6. "User Interface" properties
- [content](https://developer.mozilla.org/docs/Web/CSS/content)
- [quotes](https://developer.mozilla.org/docs/Web/CSS/quotes)
- [counter-increment](https://developer.mozilla.org/docs/Web/CSS/counter-increment)
- [counter-reset](https://developer.mozilla.org/docs/Web/CSS/counter-reset)
- [outline](https://developer.mozilla.org/docs/Web/CSS/outline)
    - [outline-color](https://developer.mozilla.org/docs/Web/CSS/outline-color)
    - [outline-style](https://developer.mozilla.org/docs/Web/CSS/outline-style)
    - [outline-width](https://developer.mozilla.org/docs/Web/CSS/outline-width)
- [cursor](https://developer.mozilla.org/docs/Web/CSS/cursor)
- [resize](https://developer.mozilla.org/docs/Web/CSS/resize)

## 7. "Animation" properties
- [transition](https://developer.mozilla.org/docs/Web/CSS/transition)
    - [transition-property](https://developer.mozilla.org/docs/Web/CSS/transition-property)
    - [transition-duration](https://developer.mozilla.org/docs/Web/CSS/transition-duration)
    - [transition-timing-function](https://developer.mozilla.org/docs/Web/CSS/transition-timing-function)
    - [transition-delay](https://developer.mozilla.org/docs/Web/CSS/transition-delay)
- [animation](https://developer.mozilla.org/docs/Web/CSS/animation)
    - [animation-name](https://developer.mozilla.org/docs/Web/CSS/animation-name)
    - [animation-duration](https://developer.mozilla.org/docs/Web/CSS/animation-duration)
    - [animation-timing-function](https://developer.mozilla.org/docs/Web/CSS/animation-timing-function)
    - [animation-delay](https://developer.mozilla.org/docs/Web/CSS/animation-delay)
    - [animation-iteration-count](https://developer.mozilla.org/docs/Web/CSS/animation-iteration-count)
    - [animation-direction](https://developer.mozilla.org/docs/Web/CSS/animation-direction)
    - [animation-fill-mode](https://developer.mozilla.org/docs/Web/CSS/animation-fill-mode)
    - [animation-play-state](https://developer.mozilla.org/docs/Web/CSS/animation-play-state)

## 8. Other properties
- [unicode-bidi](https://developer.mozilla.org/docs/Web/CSS/unicode-bidi)
- [direction](https://developer.mozilla.org/docs/Web/CSS/direction)
- [page-break-before](https://developer.mozilla.org/docs/Web/CSS/page-break-before)
- [page-break-after](https://developer.mozilla.org/docs/Web/CSS/page-break-after)
- [page-break-inside](https://developer.mozilla.org/docs/Web/CSS/page-break-inside)
- [widows](https://developer.mozilla.org/docs/Web/CSS/widows)
- [orphans](https://developer.mozilla.org/docs/Web/CSS/orphans)
