# nisc-affine_transformation
A processor to perform affine transformation on a given coordinate. There was an included constraint of minimising the cost function given by:  Cost = number of ALMs (Adaptive Logic Modules) used +max(0,number of embedded multipliers used – 2) +30 X Kbits of RAM used.  The cost of the design (excluding the counter for de-bouncing) was calculated to be 18.88. A custom ALU and control word was created to reduce the cost of the design.
