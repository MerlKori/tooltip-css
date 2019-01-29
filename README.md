# Description

This is a small project to create simple tooltip elements on pure css.

## Usage example

1) Connect file tooltip.css
2) Element for which you need a tooltip, set the class 'tooltip'.
3) Set one of the direction modifier classes: 'tooltip--left', 'tooltip--right', 'tooltip--top', 'tooltip--bottom'.
4) Set attribute 'data-tooltip' and pass it the text that will be displayed in the tooltip.

### Usage example
    ```
    <button
		data-tooltip="tooltip text"
		class="tooltip tooltip--top">
		top
	</button>
    ```
#### Warning!

When you connect the class tooltip, the element will be used pseudo-elements ::before, ::after.
Used css variables, therefore not supported IE!
