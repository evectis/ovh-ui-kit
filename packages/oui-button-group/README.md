# oui-input-group

<component-status cx-design="partial" ux="prototype"></component-status>

oui-button-group is a package which provide styles to group buttons together.

## Installation

```less
  @import 'oui-button-group/button-group';
```

## Usage

```html:preview
<button class="oui-button oui-button_icon-left oui-button_secondary">
  <i class="oui-icon oui-icon-chevron-left" aria-hidden="true"></i>
</button>
<button class="oui-button oui-button_icon-right oui-button_secondary">
  <i class="oui-icon oui-icon-chevron-right" aria-hidden="true"></i>
</button>
<div class="oui-button-group">
  <button class="oui-button oui-button_secondary">1</button>
  <button class="oui-button oui-button_secondary">2</button>
  <button class="oui-button oui-button_secondary">3</button>
  <button class="oui-button oui-button_secondary">4</button>
  <button class="oui-button oui-button_secondary">5</button>
</div>

<div class="oui-button-group">
  <button class="oui-button oui-button_primary">Button 1</button>
  <button class="oui-button oui-button_secondary">Button 2</button>
</div>

<div class="oui-button-group">
  <button class="oui-button oui-button_secondary">Button 1</button>
  <button class="oui-button oui-button_primary">Button 2</button>
</div>
```

## Mixins

```less
  @import 'oui-button-group/_mixins';
```

### .button-group-base

Define the base styles for an input-group.

```less
#oui > .button-group-base(
  @oui-button-selector
);
```