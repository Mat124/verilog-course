# verilog-course
Intro to SystemVerilog/Verilog for UWCS

# the plan
Overall follow similar structure to es2e3, with added systemverilog. Also include an extra bit about FPGAs/design flow for them

## learning content
- what is a HDL?
- basics of file structure and concept of modules
- wires, input, output
- structural verilog
  - combinational verilog
    - assign statements
    - always block
    - making a halfadder/fulladder
    - conditional assignments
      - logical operators
      - ! and ~
  - multibit signals
    - making a FIFO?
    - concatenation/replication
    - number literals
    - comparator example using bit signals
- behavioural verilog
  - reg
    - reg output
  - always block
    - procedural statements
    - no multiple assignments in different blocks
    - always blocks are concurrent
  - if statement
  - case statements
    - decoder/multiplexor example
- latches & avoiding them
- sequential verilog (or synchronous verilog)
  - SR and D latch examples
  - concept of clocks
  - posedge
    - read just before
    - written just after
  - nonblocking vs blocking
  - counter
    - complex counter with up/down and load in count
  - shift registers
    - multibit signal example
  - serial <-> parallel conversion
- memory
- testbenches
  - bit type
- parameters
- generate
- 4-state logic
  - logic
  - uses
- FPGA design flow
  - what gets synthesised
    - some examples
      - always block
      - assignments
      - modules

## workshops - EDAplayground or coctb
- seven seg display
- complex counter with up/down and load in count
- carry-lookahead adder
- VGA controller
- ALU
- PATP or basic processor