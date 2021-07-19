# PCI_Slave_Device
The slave receives commands from master and starts acting according to it.
The slave can identify if the master is calling its address or not.
The slave can perform read/write operation with different scenarios for each operation
An 8 byte register is used as a memory in the target 
Another 8 byte cache memory as storage in case of overflow in of registers memory.
Slave address is assigned as 32’h111111xxx with the last 3 bits determining which register to perform the operation on.

