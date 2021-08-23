# `@askiggy/stardust`

The Iggy frontend component library and styleguide.

## Installation

```
yarn add @askiggy/stardust
```

## Usage

### CSS Modules

Each module can be imported into your project as individual packages:

In CSS modules:
```css
@import '@askiggy/stardust/styles/{module}`
```

In JSX:
```javascript
import '@askiggy/stardust/styles/{module}`
```

####  `global`

The global scss library. This includes all of the modules listed below.

Library | Description
---|---
`fonts` | Font assets definition
`layout` | Global layout styles
`normalize` | Style resets
`typography` | Type system
`utils` | Utility class selectors
`variables` | Global variables definition

Element | Description
---|---
`buttons` | Buttons element styles
`forms` | Form element styles
`links` | Links element styles
`lists` | List element styles
`scrollbars` | Scrollbars

Component | Description
---|---
`system` | System messages
`tooltip` | Tooltip component


## Releasing a new Package

See the [RELEASE.md](RELEASE.md) doc for how to publish releases.
