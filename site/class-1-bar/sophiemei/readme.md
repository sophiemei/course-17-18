# Bar chart

In this assignment I learned how charts made with d3 work by inspecting and modifying an existing bar chart.

## Background
I picked a **basic bar chart** from d3’s example gallery, and copied and pasted the code over to my text editor. Then I separated the style and script. At first, the chart did not work. I simply forgot to navigate to localhost:8000. Instead I had opened the file directly from its directory. Whoops.

When I started swapping in new data, I wanted my vertical axes to represent a numeric value. I figured out how to do that by changing the percentage sign in `.ticks(10, "%"` to a number sign`.ticks(10, "#"`.

In order to make the colorful lines more readable, I used comments to communicate the intent of my code. A true lifesaver, since javascript is like Chinese to me. Hopefully this will change soon.

## Data
Each rectangular bar represents a number of steps I took per day over the past two weeks. The data table is stored in a TSV (Tab-separated values) file, in which columns of data are separated by tabs (as you might have guessed).

## Features
Section listing all d3 features used and linking to API docs

## License
MIT (c) Sophie Hoeboer
