### Grid Area
- `Grid area can replace grid column and grid row`
- # Example-
/* grid-column-start:1;
    grid-column-end: 4;
    grid-row-start: 1;
    grid-row-end: 3; */
- This can be replaced by this- 
    grid-area: 1/1/3/4;

# grid-template-areas
`we can give name to the blocks and define them in different portions`

- Example-
   grid-template-areas: "hd hd hd hd hd hd hd hd"
                         "sd main main main main main main main "
                        "ft ft ft ft ft ft ft ft" 
    #header{
    grid-area: hd;
}

## Advanced Grid Concepts
- `Fr unit` or fraction unit
    example- gtc: 1fr 1fr 1fr;
- `Repeat Function`
example- gtc:repeat(3,1fr);
- `Grid-auto-rows:minmax()`
- > Adds rows automatically(used where we dont know about how many rows we need)

## Grid Properties
- > Justify-Content
                   -> Horizontal axis 
- > Align-Content
- > Justify-items
- > Align-items
                -> vertical axis
- > Justify-self
                -> apply on child or individual
- > Align-self
- > Place-items 
              short hand notation for justify and align items
- > Place-self
              short hand notation for justify and align self

## Blog website layout
## 