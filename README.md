# A-system-for-managing-factory
An LC-3 code that plans a factory managing system.
The factory works every day from 08:00, but no further than 07:00.
The factory has 10 machines that produced: chairs, closets and desks. each machine for prudocing needs to be in a series (4,5,6, but not 0,3,4).
If a machine doesn't work- -1

The following subrotines are implemented:
  1. work hours: getting the closing time hour (0-23) and cheking the validation.
  2. machineAllocator: getting in R0 pointer to the MachineAllocator matrix and fills her according to the input.
  3. DailyProduction: getting from the user the daily production in a table. each row represrent a machine and each col is an hour.
  4. bubbleSort.
  5. Median of production between given hours.
