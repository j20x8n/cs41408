java c
Assignment 2: MIPS Multicycle Processor 
Assignment Outline 
l Assignment 2 accounts for   15% of your overall   mark   in the   EEE339 module.   This   assignment is to test your understanding of the behavioural   specification   of the MIPS-Lite multi-cycle   processor design presented in the   lectures.
l A sample Verilog code is available   at Appendix A.
l You need to write the machine code of your MIPS instructions into the   desired   locations   of the memory   in the   following Verilog code.
l To ensure that it is your   own   work   that   is   being   assessed, Appendix   B   indicates   the   specific tasks for each student.
l The assignment   is to be undertaken   in   a   series of   steps which   you   should   complete   in   order.
1. Sketch the ASM chart of the state   machine.   [   10   Marks]
2. Write a programme to: [50   Marks   in   total   and   10   Marks   each]
a. Load the data stored in locations X   and Y   of the data   memory   into   registers   P   and   Q.
b. Add register P with constant 6   and store   the   result   in   the   register   R.
c.   If the   result in   registers Q and   R   is equal to each   other,   then   branch   to   instruction   a.
d. Store the result   in the register   R   into the   memory   location   24.   e. Jump to   instruction a.
3. Simulate your prog代 写Assignment 2: MIPS Multicycle ProcessorSPSS
代做程序编程语言ram. To test instructions d   and   e,   you   need   to   change   the   data   in   the   data   memory at some stage.   [   10   Marks]
4. Add code to support   R-type   instructions such as AND, OR, sub,   slt,   and   NOR,   and   simulate the instruction specified for each student in   the attached   table.   [20   Marks]
5. Add some extensions to cope with the exceptions when an opcode   not   supported   by this   MIPS-lite   processor is detected or PC goes   into an   address   for   data   memory.   [   10   Marks]
Reports 
Your report should   include the following contents:
1. The ASM chart for the state   machine.
2. The   MIPS code and the corresponding machine   code.
3. Simulation waveforms for the opcode, state, PC,   IR, ALUOut and relevant registers (P,   Q,   R)   must be demonstrated and annotated. You should clearly   indicate why   the simulations show that the operation is correct   or   incorrect.
4.   Description of the   modifications made to implement the additional   instruction or extensions.   Highlight the changes   made in the code.
5.   Lab demonstration for your work   is   not required.
6. The submission deadline is at   11:59 pm on Wednesday   11th December 2024 (Week   13).   A single   pdf file should be submitted to the   Learning   Mall.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
