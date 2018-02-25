# _Grilled Cheese, All Day..._

#### _A page utilizing CSS skills towards the sale of a grilled cheese sandwich, 11/17/2017_

#### By _**Kevin Boyle**_

## Screenshot:
![GrilledCheese](img/screenshot.png?raw=true)

## Description

This page is styled emphasizing the capabilities of CSS without 3rd party libraries or JavaScript embellishments. It can be found at https://lemurriot.github.io/GrilledCheese/. Several key criteria were met:



| Term                | Description                                                                                                                                                                            | Implementation                                                                                                                                                                                                                                                                                                                                                                                                                     |
|---------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Box-Sizing          | This property tells the browser which parts of the box model should be included in the elements' total width and height.                                                               | I applied the value border-box to all elements by assigning it to the * element. Without using border-box, my 50% width division in places such as the columns "left" and "right" assigned to the "half" class would not have fit on one line, but rather on top of each other.,The border-box tells the browser that regardless of padding & border, the box size is still only 100% of the total width.                          |
| Float               | This property tells the browser to "float" and element to the left or right of other elements, allowing for inline styling of adjacent elements.                                       | Float is used regularly in this project, including in the header icons, in the column structure of the "What is Grilled Cheese" and "Gallery" sections, as well as the grid structure within the Gallery itself. Without float, the browser would display these items in differently structured, block-level ways or without controls over the spacing and styling.                                                                |
| Display: block      | This property takes a group of in-line elements and displays them in block formation (ie, one on top of the other).                                                                    | I utilized this property in the form input fields. They are inline elements by default, by applying "Display: block" they are displayed as if they were block elements.                                                                                                                                                                                                                                                            |
| Display: inline     | This property takes a group of block-elements and displays them in-line.                                                                                                               | I utilized this property at the end of my project, by displaying the divs containing Social Media icons (divs are default block-level) in-line. The end result is a clean row of social media icons.                                                                                                                                                                                                                               |
| Centered-Content    | This property can be achieved in various ways, the end result is that an element is centered on the x-axis, y-axis, or both.                                                           | I utilized this property in my table, which was achieved through Positioning and Transform/Translate to center it along the x-axis in the Container div and approximate centering along the y-axis.                                                                                                                                                                                                                                |
| Pseudo-Elements     | There are several properties considered pseudo-elements, which target specific lines or locations of other elements for custom styling.                                                | In my project, I utilized the pseudo-element ::first-letter on my positioned caption over my image, making the first letter larger than the others.                                                                                                                                                                                                                                                                                |
| Pseudo-classes      | There are also several pseudo-class properties which have various functions, including targeting certain places within an element or added stylistic affects upon hover or click, etc. | I utilized several pseudo-classes, including :hover (ie, the pictures in the galler, or the submit button), :focus (ie, the form input fields), and :nth-child in my table, targeting specific lines for background colors.                                                                                                                                                                                                        |
| Clear-fix           | When using floats, the browser may run into problems where it does not know when the floating stops. Utilizing clear-fix techniques helps to address these problems.                   | In my page I frequently cleared float problems by applying "overflow:auto" to the parent div, ensuring that the div does not collapse on itself in the space left open by the float. I also utilized "clear:both" (ie both left & right floats) after my maincontent "left" and "right" divs, at the Order Here location. This is because a new div, the order section, was not in need of floating as the two previous divs were. |
| Positional Selector | Positional selectors give the programmer control over location and positioning regardless of defaults.                                                                                 | My page utilizes a fixed positional selector for the header, as well as absolute and relative positioning for the maincontent banner image as well as the caption juxtaposed on top of it. Positioning is used frequently throughout the page, often Position:relative, for minor and major adjustments.                                                                                                                           |
| Selector Combinator | Several different items on the styles sheet allow the programmer to target elements very specifically.                                                                                 | This page most often utilizes the space between selectors, ie, ".orderform table" meaning it specifies a child element table of the class orderform. These selectors help override specificity protocol and select items which are otherwise difficult to target.                                                                                                                                                                  |


## Known Bugs

_There are no known bugs_

## Support and contact details

_Contact Kevin Boyle at papershack@gmail.com with any questions or concerns_

## Technologies Used

_This page is created using only CSS and HTML_

### License

*Fair Use License*

Copyright (c) 2017 **_Kevin Boyle_**
