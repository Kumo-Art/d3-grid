# Grid Notes


## display: grid
- 'display: grid' goes on the parent. direct children become grid items.
- 'grid-template-columns: 1fr 1fr 1fr;' = three equal columns.
- 'fr' = fraction, a share of the space thats left.
- Max units : '200px 1fr 1fr' = one fixed column, two that share the rest.


## repeat()
- 'repeat'(3, 1fr)' = '1fr 1fr 1fr'
- First number = how many, second = what to repeat. 


## Row heights
- 'grid-template-row: 150px 150px' = set two rows height to 150px.
- Rows I didn't list are just as tall as their content.
- 'grid-auto-rows: 150px;' = every row, even the ones Grid makes on its own gets set to 150px.


## Spanning
- 'grid-column: span 2;' = take up two columns.
- 'grid-row: span 2;' = take up two rows.
- In a grid, we say how many columns or rows, not how many pixels.



## Grid lines
-Grid lines are numbered starting at 1. Three columns = four lines (end column + 1).
- 'grid-columns: 1 / 3;' = start at line 1, end at line 3.