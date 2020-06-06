[Home](README.md)


# Cascading Style Sheets - Notes

- RGB
  - expresses color based on how much red green and blue is present in color 
  - ` rgb(100,100,100)`
- HSL
  - Assigning colors by Hue Saturation and Lightness
  - Hugh is assigned between 0 and 360 degrees
  - Saturation is assigned by percentage
  - Lightness is also expressed as a percentage 0 being white and 100 being black
- Hex codes
 - hex codes express color by their assigned hexidecimal value
 - `#00ff00` green
- Layout

## Anatomy

- Rule - 

- background color assigns a color to the background of the box it is set to.

> be sure to have a decent amount of contrast between your background color and text color

![CSS syntax example](sel.gif) 

### Selectors

- `*{}` is a universal selctor
- type selectors match element names
- class selectors matches an element whos class matches 
  - `.note` will select all emementsof class `.note`
  - `p.note` will select only paragraph of class `.note`
- id selectorws only select element with corresponding ID
  - `#id `
- child selector will select element that are children of specified element
  - `li>a{}`

- Decendant selector matches an element that is a decendant 
  - ` p a {} `
- Adacent sibling selector will target the next sibling
  - ` h1+p {} `
- General sibling collector
  - ` h1~p `