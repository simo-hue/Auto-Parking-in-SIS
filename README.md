# progetto-sis-ultimo
# progetto-sis-ultimo

https://prod.liveshare.vsengsaas.visualstudio.com/join?133994F0358D2CB1AF518D03665F1B7E22B1

sis> print_stats
FSMD            pi= 5   po= 6   nodes=253       latches=18
lits(sop)=3370

dopo script.rugged

sis> print_stats
FSMD            pi= 5   po= 6   nodes= 77       latches=18
lits(sop)= 386

dopo altri 4 script.rugged 

sis> print_stats
FSMD            pi= 5   po= 6   nodes= 66       latches=18
lits(sop)= 366

dopo 4 sweep, 4 full-simplyfy e 4 fx

sis> print_stats
FSMD            pi= 5   po= 6 nodes=72       latches=18

lits(sop)= 348

dopo mapping tencnologico

sis> print_map_stats
Total Area              = 6608.00
Gate Count              = 184
Buffer Count            = 18
Inverter Count          = 34
Most Negative Slack     = -29.60
Sum of Negative Slacks  = -477.00
Number of Critical PO   = 24

