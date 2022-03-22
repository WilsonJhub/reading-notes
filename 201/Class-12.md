# Char.js, Canvas

--------------------------------

## ANIMATED CHARTS WITH CHART.JS

Chart.js is a JavaScript plugin that uses HTML5's canvas eleent to draw the graph onto the page. 

### Drawing a line chart
  1. Create a new html page and import the following:
      Ex: 
          <!DOCTYPE html>
          <html lang="en">
              <head>
                  <meta charset="utf-8" />
                  <title>Chart.js demo</title>
                  <script src='Chart.min.js'></script>
              </head>
              <body>
              </body>
          </html>

  2. Create a canvas element in html so that "Chart.js" can draw our chart. 

      Ex: 
          <canvas id="buyers" width="600" height="400">`</canvas>`

  3. Use a script that will retrieve the context of the canvas and add it to the foot of your body elemnt. See below:

      Ex:
          <script>
              var buyers = document.getElementById('buyers').getContext('2d');
              new Chart(buyers).Line(buyerData);
          </script>


          