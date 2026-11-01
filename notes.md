what belongs to the content should be in the html. eg. pics of the subject

what belong to the style should be in the css. eg bg image

add alts to your images. for accessibility and SEO.

dont use br tags just split it into 2 p tags

a tag with a '/' herf with no domain takes you to paths in ur current domain

### attributes classes and ids

what is an attribute?  
it is a way to modify the behaviour of html tags using key value pairs.

### organizing html

use article for containing units of information instead of div. and for larger units use section.

### head and meta tags

## CSS

css consists of rules witch looks like this:

```css
// this is a rule

selector // this is a selector{
  attribute: value; this is a property
}
```

and the browser just matches the html elements that it has and applies the values from the attributes to the elements attributes.

u set colors using names eg(red), hex values (#44443) or rgb ((20,32,45))

and why we have font and text properties ?

Font is like we have multiple fonts so the font- properties messes with the character set. but the text operates on the text itself regarding of the character set it belongs to.

Rules are inherited. So who u select the top div to have blue color. its children will be blue as well

css consists of rules that are selectors and properties

> the parent affects the child = the rules are Inherited

dont style tags use classes.

what is a span ? it is a small container used to style something within a paragraph

### the cascade

when 2 rules conflicts which one wins ?

if they have the same specificity, the last one wins.
