# FPGA^2
An OSHW (Open-Source Hardware) FPGA (Field-Programmable Gate Array), initially running in its own online circuit simulator.
![](https://github-readme-stats.vercel.app/api?custom_title=FPGA%5e2%27s+GitHub+Stats&username=RobinHodson&repo=FPGA&show_icons=true&title_color=fc0&icon_color=cfc&text_color=8f8&bg_color=000)

This operates under the CERN-OHL-P licence.
The first online presence for this project, is/was [freedom.is/svg](http://freedom.is/svg)

[Main documentation contents](https://robinhodson.github.io/FPGA/), part ofwhich may later merge into this readme.

<details>
<summary>Verilog syntax highlighting test</summary>

```verilog
module Example_counter
#(parameter WIDTH=64,NAME="world")
(input clk,
 output reg [WIDTH-1:0] q);
...
```

(The above code has nothing to do with this project.)
</details>
<details>
<summary>Large-scale RTL plan/explanation of my FPGA design</summary>
(Added 23/5/2023)

![](docs/rtl1c.png)

You can also [download this as a PDF](https://github.com/RobinHodson/FPGA/blob/main/docs/rtl1b.pdf): Click on the download rawfile button.
</details>
