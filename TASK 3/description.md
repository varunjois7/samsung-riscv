## 1. lui a0, 0x2b
#### Instruction Format: [imm[31:12] | rd[11:7] | opcode[6:0]].
#### imm: 0x0002b.
#### rd: a0 (x10).
#### opcode: 0x37.
#### 32-bit instruction: 0x0002b073.

## 2. addi sp, sp, -48
#### Instruction Format: [imm[11:0] | rs1[19:15] | funct3[14:12] | rd[11:7] | opcode[6:0]].
#### imm: 0xfff.
#### rs1: sp (x2).
#### funct3: 0x0.
#### rd: sp (x2).
#### opcode: 0x13.
#### 32-bit instruction: 0xfff30313.

## 3. sd ra, 40(sp)
#### Instruction Format: [imm[11:5] | rs2[24:20] | rs1[19:15] | funct3[14:12] | opcode[6:0]].
#### imm: 0x00a.
#### rs2: ra (x1).
#### rs1: sp (x2).
#### funct3: 0x2.
#### opcode: 0x23.
#### 32-bit instruction: 0x00a303b3.

## 4. jal ra, 10564 <printf>
#### Instruction Format: [imm[20] | imm[10:1] | imm[11] | imm[19:12] | rd[11:7] | opcode[6:0]].
#### imm: 0x0002d.
#### rd: ra (x1).
#### opcode: 0x6f.
#### 32-bit instruction: 0x0002d06f.

## 5. lw s0, 12(sp)
#### Instruction Format: [imm[11:0] | rs1[19:15] | funct3[14:12] | rd[11:7] | opcode[6:0]].
#### imm: 0x000c.
#### rs1: sp (x2).
#### funct3: 0x2.
#### rd: s0 (x8).
#### opcode: 0x03.
#### 32-bit instruction: 0x0002a003.

## 6. li s1, 0
#### Instruction Format: [imm[11:0] | rd[11:7] | opcode[6:0]].
#### imm: 0x0000.
#### rd: s1 (x9).
#### opcode: 0x13.
#### 32-bit instruction: 0x00030313.

## 7. beqz s0, 10110 <main+0x6>
#### Instruction Format: [imm[12] | imm[10:5] | rs2[24:20] | rs1[19:15] | funct3[14:12] | imm[4:1] | imm[11] | opcode[6:0]].
#### imm: 0x000.
#### rs1: s0 (x8).
#### rs2: zero (x0).
#### funct3: 0x0.
#### opcode: 0x63.
#### 32-bit instruction: 0x00030363.

## 8. mv a0, s0
#### Instruction Format: [funct7[31:25] | rs2[24:20] | rs1[19:15] | funct3[14:12] | rd[11:7] | opcode[6:0]].
#### funct7: 0x00.
#### rs2: s0 (x8).
#### rs1: zero (x0).
#### funct3: 0x0.
#### rd: a0 (x10).
#### opcode: 0x33.
#### 32-bit instruction: 0x00a30333.

## 9. sext.w s0, a0
#### Instruction Format: [funct7[31:25] | rs2[24:20] | rs1[19:15] | funct3[14:12] | rd[11:7] | opcode[6:0]].
#### funct7: 0x00.
#### rs2: a0 (x10).
#### rs1: zero (x0).
#### funct3: 0x0.
#### rd: s0 (x8).
#### opcode: 0x33.
#### 32-bit instruction: 0x0002a033.

## 10. bnez s0, 100e8 <main+0x3>
#### Instruction Format: [imm[12] | imm[10:5] | rs2[24:20] | rs1[19:15] | funct3[14:12] | imm[4:1] | imm[11] | opcode[6:0]].
#### imm: 0x000.
#### rs1: s0 (x8).
#### rs2: zero (x0).
#### funct3: 0x1.
#### opcode: 0x63.
#### 32-bit instruction: 0x0002a023.

## 11. sw zero, 12(sp)
#### Instruction Format: [imm[11:5] | rs2[24:20] | rs1[19:15] | funct3[14:12] | opcode[6:0]].
#### imm: 0x000.
#### rs2: zero (x0).
#### rs1: sp (x2).
#### funct3: 0x2.
#### opcode: 0x23.
#### 32-bit instruction: 0x0002a023.

## 12. ld ra, 40(sp)
#### Instruction Format: [imm[11:0] | rs1[19:15] | funct3[14:12] | rd[11:7] | opcode[6:0]].
#### imm: 0x0028.
#### rs1: sp (x2).
#### funct3: 0x3.
#### rd: ra (x1).
#### opcode: 0x03.
#### 32-bit instruction: 0x0002b033.

## 13. auipc a0, 0x0
#### Instruction Format: [imm[31:12] | rd[11:7] | opcode[6:0]].
#### imm: 0x0000.
#### rd: a0 (x10).
#### opcode: 0x37.
#### 32-bit instruction: 0x00000537.

## 14. sub a2, a2, a0
#### Instruction Format: [funct7[31:25] | rs2[24:20] | rs1[19:15] | funct3[14:12] | rd[11:7] | opcode[6:0]].
#### funct7: 0x00.
#### rs2: a0 (x10).
#### rs1: a2 (x11).
#### funct3: 0x0.
#### rd: a2 (x11).
#### opcode: 0x33.
#### 32-bit instruction: 0x40a302b3.

## 15. li a1, 0
#### Instruction Format: [imm[11:0] | rd[11:7] | opcode[6:0]].
#### imm: 0x0000.
#### rd: a1 (x11).
#### opcode: 0x13.
#### 32-bit instruction: 0x00030313.
