# react table

tutorial - https://www.youtube.com/watch?v=YwP4NAZGskg&list=PLC3y8-rFHvwgWTSrDiwmUsl4ZvipOw9Cz&ab_channel=Codevolution
github - https://github.com/gopinav/React-Table-Tutorials

## basic table

1. get data you want to display (mockaroo.com)
2. define columns for table

3. create a react-table instance using data and columns (defined in step 1+2)
4. define basic table structure using plain html

5. use table instance (step3) - to bring html (step4) to life
6. include desired css

## Filtering

- global (all columns) - search all columns for matching data (filtering is on client side)
- column filtering - only that column contains search text

## Pagination

- Page Data and implement next/previous
- Jump to a page
- Configure page size

- remove <tfoot>
- replace 'rows' with 'page'
- to page between pages, destruct 'nextPage' and 'previousPage' from useTable
- canNextPage, canPreviousPage
