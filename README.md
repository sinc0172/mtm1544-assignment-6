# mtm1544-assignment-6
Week 6 Assignment: Grid Page Layout

## Palette
| Token | Hex | Used For |
| ink | #14202E | Hero and footer background. Headings and body text on light backgrounds 
| paper | #F6F3EE | Page background 
| surface | #FFFFFF | Header background, card background 
| accent | #B4451F | Button fill, card category labels 
| accent-soft | #F0DCD2 | Sidebar note background, hero eyebrow text 
| line | #D8D2C8 | Card borders, header bottom rule, body text on ink 
| muted | #5C6672 | Inactive nav links, card blurb text, sidebar section label 

## Typography
| Role | Size | Line height | Weight | Tracking |
|---|---|---|---|---|
| Hero headline | 40 | 48 | Bold 700 | none |
| Section heading | 28 | 36 | Bold 700 | none |
| Featured card title | 28 | 36 | Semi Bold 600 | none |
| Wordmark | 20 | 28 | Bold 700 | +2% |
| Card title | 20 | 28 | Semi Bold 600 | none |
| Hero lede | 18 | 28 | Regular 400 | none |
| Body, nav, footer, sidebar | 16 | 24 | Regular 400, nav is Medium 500 | none |
| Card blurb | 16 | 26 | Regular 400 | none |
| Eyebrows and labels | 13 | 20 | Semi Bold 600 | +8%, uppercase |

## Spacing scale

Everything is a multiple of 8.

| Step | Value | Typical use |
|---|---|---|
| 8 | 8px | Gap between a label and the text under it, inside cards and footer columns |
| 16 | 16px | Gap between sidebar list items, button vertical padding |
| 24 | 24px | Card internal padding, gallery gutter, hero item gap, sidebar note padding |
| 32 | 32px | Nav link gap, sidebar to main gap, button horizontal padding, main section gap |
| 48 | 48px | Footer vertical padding |
| 64 | 64px | Hero and body vertical padding, footer column gap |

## Layout

| Measurement | Value |
|---|---|
| Frame width | 1440 |
| Page side margin | 120 |
| Content width | 1200 |
| Sidebar width | 256, fixed |
| Column gap | 32 |
| Main column width | 912 |
| Gallery gutter | 24 |
| Card width | 288 |
| Featured card width | 600 |
| Header height | 88, with a 1px bottom rule in `line` |
| Hero padding | 64 top and bottom, 120 left and right |
| Hero lede max width | 720 |
| Body padding | 64 top and bottom, 120 left and right |
| Footer padding | 48 top and bottom, 120 left and right |
| Corner radius | 2, on cards, the button and the sidebar note |
| Card border | 1px, `line` |

## Repeating component

| | |
|---|---|
| Name | Card |
| Appears | 5 times, one of them stretched |
| Width | 288, or 600 for the featured card |
| Internal padding | 24 on all four sides of the text block |
| Internal gap | 8 between category, title and blurb |
| Image block | Full card width, 180 tall, a photograph cropped to fill |
| What varies between instances | Category label, title, blurb, and therefore height |
| What stays fixed | Width, image height, padding, gap, border, radius, all type sizes except the featured title |