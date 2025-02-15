```js server
/* START - Rocket auto generated - do not touch */
export const sourceRelativeFilePath = 'components/dile-button.rocket.md';
import { layout } from '../recursive.data.js';
export { layout };
/* END - Rocket auto generated - do not touch */

export const title = "dile-button";

```

```js script
import { html, css, LitElement } from 'lit'; 
import '@mdjs/mdjs-story/define';
import '@mdjs/mdjs-preview/define';
import '../../../packages/dile-button/dile-button.js'
import "../../../packages/dile-menu-hamburger/dile-menu-hamburger.js";
import "../../../packages/dile-selector/dile-selector.js";
import "../../../packages/dile-selector/dile-selector-item.js";
```

# dile-button

Web Component to create a customized button.

## Installation

```bash
npm i @dile/dile-button
```

## Usage

Import the dile-button component.

```javascript
import '@dile/dile-button/dile-button.js';
```

Use the component.

```html
<dile-button>Button Label</dile-button>
```

### Properties

- **disabled**: Boolean, mark button as disabled.
- **name**: The name of the button

### CSS Custom Properties

You can customize it using CSS Custom Properties.

Custom property | Description | Default
----------------|-------------|---------
--dile-button-padding-y | Vertical padding | 0.5rem
--dile-button-padding-x | Horizontal padding | 0.8rem
--dile-button-border-radius | Button border radius | 2rem
--dile-button-border-width | Button border width | 3px
--dile-button-border-color | Button border color | #07193b
--dile-button-background-color | Background color | #7BB93D
--dile-button-text-color | Text color | #fff
--dile-button-font-size | Font size | 1rem
--dile-button-font-weight | Font weight | bold
--dile-button-hover-background-color | Hover background color | #f3f3ae
--dile-button-hover-text-color | Hover text color | #303030
--dile-button-hover-border-color | Hover border color | #666666
--dile-button-ring-color | Ring color on focus state | #12c9e9
--dile-button-ring-offset-width | Ring width on focus state | 3px
--dile-button-disabled-background-color | Disabled background color | #b1ecf7
--dile-button-disabled-border-color | Disabled border color | #bbb
--dile-button-disabled-text-color | Disabled text color | #999

## dile-button demos

### Regular button

```html preview-story
<dile-button>Click here!</dile-button>
```

### Styled button

```html preview-story
<style>
  .styled {
    --dile-button-border-color: #666;
    --dile-button-hover-border-color: #ff910f;
    --dile-button-background-color: #491449;
    --dile-button-hover-background-color: #f3c6f3;
    --dile-button-text-color:  #fff; 
    --dile-button-hover-text-color:  #000; 
    --dile-button-font-weight: bold;
    --dile-button-ring-color: #cc5099;
    --dile-button-ring-offset-width: 2px;
    --dile-button-border-radius: 4px;
    --dile-button-text-transform: uppercase;
  }
</style>
<dile-button class="styled">Click here!</dile-button>
```

### Disabled button

```html preview-story
  <dile-button name="disabeldbutton" disabled id="disabeldbutton">Disabled button</dile-button>
```