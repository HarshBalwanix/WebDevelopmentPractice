### CSS FLEXBOX
 -> Layout model of 1 Dimension 
 -> space distribution
 -> Allignment capabilities
  1 Block
  2 Inline
  3 CSS position property

  Flexbox is most useful for positioning

## Flexbox-container Properties
-> Flex direction >Row,Row Reverse,Column,Cloumn-reverse

->Flex-wrap >wrap,nowrap,wrap-reverse

->Flex-flow(short hand notation to write flex direction and flex wrap) 

->Justify-content(align according to main horizontal axis) >flex-start;
             flex-end,center,space-around,space-evenly, space-between

-> align-items apply on cross line(vertical)

-> Align-content TO remove gap from the content
            ->flex-start;
             flex-end,center,space-around,space-evenly, space-between

## Flex items Properties:
-> Order 
       by default it is Zero and can be set to change the order of the content
-> Flex-grow
        takes space by width equally
-> Flex-shrink
        sets shrink speed applied to any content
-> Flex-basis
        same as width just the differene is with flex basis whole content is shown but with width the content overflown is hidden
-> Flex
        short hand of all above properties
        Example- 4 3 2 120px;(order,grow,shrink,basis)
-> Align-self 
       to apply flex properties on itself
       stretch
       flex-end etc.

`Parallex effect is done on next lecture folder`