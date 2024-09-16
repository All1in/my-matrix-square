# Frontend React Test Task

## Overview

This project is a React application built with TypeScript and React Context for managing and visualizing a matrix of data. Users can interact with the matrix by increasing cell values, finding nearest cells by value, viewing percentages, and more. This README provides an overview of the project's functionality, technical requirements, and setup instructions.

## Technical Requirements

- **Technologies Used**: TypeScript, React, React Context
- **Deployment**: The production build was deployed to Vercel

## Features

1. **Matrix Creation**:
    - Create a matrix with `M` rows and `N` columns based on user inputs.
    - Each cell contains a unique `id` and a randomly generated `amount` (three-digit number).

2. **Table View**:
    - Display the matrix in a table format.
    - Include an additional column for row sums.
    - Include an additional row for the 50th percentile value for each column.

3. **Cell Interaction**:
    - Increment the value in a cell by 1 when it is clicked.
    - Recalculate and display updated sums and percentages.

4. **Highlight Nearest Cells**:
    - On hovering over a cell, highlight `X` cells with values closest to the hovered cell's value.

5. **Percentage View**:
    - Hovering over the sum cell in a row displays percentages of each cell's value relative to the row total.
    - Display a heatmap background representing each cell's value as a percentage of the maximum value in the row.

6. **Row Management**:
    - Ability to remove any row with recalculated sums and averages.
    - Ability to add new rows at the end of the table with recalculated sums and averages.

## Limits

- **M (Number of Rows)**: 0 to 100
- **N (Number of Columns)**: 0 to 100
- **X (Number of Nearest Cells to Highlight)**: Calculated based on the values of `M` and `N`.

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/All1in/my-matrix-square.git
