## Introducing CSS

#### CSS is designed for you to style HTML text. 
#### Each part of an html text document is divided into blocks, which can constitute entire paragraphs, headers, and articles, or as little as a word or two within a text box that are to be modified in some way.

#### Basic eleemtns of CSS are the selector (part of html to modify) and delclaration (what the modificaiton is)
#### Each declaration is separted into the property (what specifically is being modified) and value (what the modification actually is)

#### You can use external css files by linking them to your css. Example: <link href="css/styles.css" type="text/css" rel="stylesheet" />
#### You can also use internal files that auto populate on your CSS

## CSS Selectors

#### Universal Selector * {}
#### TYpe Selector h1, h2, h3, {}
#### Class Selector .note {} or p.note {}
#### ID Selector #introduction {}
#### Child Selector li>a {}
#### Descendant Selector p a {}
#### Adjacent Sibling Selector h1+p {}
#### General Sibling Selector h1~p {}

## How CSS Rules Cascade

#### If two or more rules apply to same element, last listed rule will be applied over any rules above it.

#### You can beat this rule by using general rules above (ex: h1 {}) and more specifics below (ex: h1 header {})

## Color

####