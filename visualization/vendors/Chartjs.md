## Chart.js
Chart.js is a JavaScript library that allows you to draw different types of charts by using the HTML5 canvas element.

One of the cool feature of Chart.js is that the charts are responsive, so they will adapt based on the space available.

### Download
http://www.chartjs.org/

### Example
![chartjs](http://snag.gy/z8L7V.jpg)

``` javascript
var data = [
    {
        value: 300,
        color:"#F7464A",
        highlight: "#FF5A5E",
        label: "Red"
    },
    {
        value: 50,
        color: "#46BFBD",
        highlight: "#5AD3D1",
        label: "Green"
    },
    {
        value: 100,
        color: "#FDB45C",
        highlight: "#FFC870",
        label: "Yellow"
    }
]

// For a pie chart
var myPieChart = new Chart(ctx[0]).Pie(data,options);
// For a doughnut chart
var myDoughnutChart = new Chart(ctx[1]).Doughnut(data,options);
```

**Labs:**

* Pie Chart - vi-chartjs-pie
* Doughnut Chart - vi-chartjs-doughnut
* Bar Chart - vi-chartjs-bar
