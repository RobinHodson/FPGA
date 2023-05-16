# FPGA
FPGA^2, an OSHW FPGA, initially running in its own online circuit simulator.
![](https://github-readme-stats.vercel.app/api?custom_title=FPGA%5e2%27s+GitHub+Stats&username=RobinHodson&repo=FPGA&show_icons=true&title_color=fc0&icon_color=cfc&text_color=8f8&bg_color=000)

This operates under the CERN-OHL-P licence.
The file is a placeholder, subject to amendment.
The first online presence for this project, is http://freedom.is/svg

There is no Verilog for this FPGA yet; it is purely a parameterised schematic.

The main documentation page is [now online](https://robinhodson.github.io/FPGA/)

A test for Verilog syntax highlighting:

```verilog
module Example_counter
#(parameter WIDTH=64,NAME="world")
(
  input clk,
  input ce,
  input arst_n,
  output reg [WIDTH-1:0] q
);
    
string name="counter";
clock_buffer #(WIDTH) buffer_inst(
.clk(clk),
.ce(ce),
.reset(arst_n)
);

...
```
