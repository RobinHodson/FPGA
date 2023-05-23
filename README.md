# FPGA^2
FPGA^2, an OSHW (Open-Source Hardware) FPGA (Field-Programmable Gate Array), initially running in its own online circuit simulator.
![](https://github-readme-stats.vercel.app/api?custom_title=FPGA%5e2%27s+GitHub+Stats&username=RobinHodson&repo=FPGA&show_icons=true&title_color=fc0&icon_color=cfc&text_color=8f8&bg_color=000)

This operates under the CERN-OHL-P licence.
The first online presence for this project, is/was [freedom.is/svg](http://freedom.is/svg)

There is no Verilog for this FPGA yet; it is purely a parameterised schematic.

The main documentation page is [now online](https://robinhodson.github.io/FPGA/)

A test of Verilog syntax highlighting:

```verilog
module Example_counter
#(parameter WIDTH=64,NAME="world")
(input clk,
 output reg [WIDTH-1:0] q);
...
```
(The above code has nothing to do with this project.)

Okay, now I have a large-scale RTL plan/explanation of my FPGA design:
![](docs/rtl1c.png)

You can also [download this as a PDF](https://robinhodson.github.io/FPGA/docs/rtl1c.pdf)
