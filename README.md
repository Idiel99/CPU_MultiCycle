#### MODULE NAME
       CPU_MultiCycle

#### DEPENDENCIES
       SameBit,  MUX2,  Flopr_32, Flopenr_32, Flopr, DSwitch, MUX2_5, MUX2_32,
       Four,  SE16_32,  SL2_32,  RF,  Flopenr,  DESwitch,  MUX4_32,   MUX3_32,
       MUX32_32,  MUX32,  Decoder_32, MUX4, MUX3, ALU32, SPLICE_PCJ, ALUBit31,
       ALUBits0To30, OneBitAdder, INC4

#### INPUTS
Name  | Size(Bits)
-------|------------
clk  |     1      
reset |     1      

#### OUTPUTS

#### DESCRIPTION
       Multi-Cycle MIPS CPU

       CTRL operates with an FSM that includes a  four-bit  state  (bits  NS3,
       NS2,  NS1  and  NS0)  and micro-instructions implemented in a MicroROM.
       Mapping from ALUOp bits to ALU inputs is done by ALUCtl.

#### AUTHOR
       Alexander T Pastoriza

#### SEE ALSO
       qms(1), modclone(1)
