# CSS-Grid
Code for CSS Grid and to begin the repository process for future ref.

PLEASE NOTE: This is just an example 

.container {
display: grid;
grid-template-columns: [col1] 33% [col2] 33% [col3] 33%;
grid-gap: 10px;
grid-template-rows: [row1] 47% [row2] 47%;
text-align: center;
color: #FFF;
}

.grid-cell-1 {
background-color: #658db5;
padding: 25px;
border-radius: 6px;
}

.grid-cell-2 {
background-color: #658db5;
padding: 25px;
border-radius: 6px;
}

.grid-cell-3 {
background-color: #658db5;
padding: 25px;
border-radius: 6px;
}

.grid-cell-4 {
background-color: #658db5;
padding: 25px;
border-radius: 6px;
}

.grid-cell-5 {
background-color: #898989;
grid-column: 3 ;
grid-row: 1 / 3;
padding: 25px;
border-radius: 6px;
}
