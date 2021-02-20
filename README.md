# First_Contact_Solidity

## Associate Profit Splitter

This contract accepts Ether and divides it evenly among 3 associate level employees (employee_one, employee_two, and employee_three).  

The contract works by taking the message value and dividing it into three employee accounts, wtih the remainder portion of the value sent back to the sender.  

Contract Address:  0x700a1812cc82895B3597250C4fD9265f433f9AEC


## Tiered Profit Splitter. 

The Tiered Profit Splitter Contract is similar to the Associate profit splitter contract, except instead of splitting the Ether evenly, it divides it among three employees accounting to set percentages.  

The contract works by taking the message value and dividing by a hundred, resulting in one 'point' or percentage of the total value which is then allocated to each employee according to seniority.  The contract transfers a value to each employee's account based on their point allocation.

Contract Address:   0xbB2EF804664a441F820DF957554d78FC47f3f0e3


## Deferred Equity Plan 

The Deferred Equity Plan pays employees shares of an Ether value based on their tenor with the company.  The longer they work for the company, the more shares they receive.  All shares are distributed after 4 years, wtih 25% of the shares distributed each year. 

In order to do an allocation based on time the contract needs to set the current time as 'now', and then has a calculation to distribute 25% of the shares every 365 days, at which time additional shares are unlocked.  The contract requires that the sender be from human resources, otherwise it will not execute the contract and will return an error message.  If the employee stays more than four years, all of the shares are distributed.  

Contract Address:   0x7886d3ebFaFd072Cd6B346E2E2214F3caBc35Ed4


