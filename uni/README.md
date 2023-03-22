```
Description: uni
	Juse another basic simulation I am running over a long period of time.
	The main feature of this simulation, is that all interrupts are enabled. And
	assigned to some wacky trap. Here is the interrupt assignments:
		trap1 eat
		trap2 broadcast
		trap3 send-energy
		trap4 send
		trap5 say
		trap6 not used
		trap7 shout

	Each trap handler started out empty.
	The initial seed program was seed_interrupt.kf which is the standard
	seed program with empty slots for the interrupt traps.

		uni.txt.gz					simulation start day 0, march 19, 2023
		uni321.txt.gz				snapshot on mar 21
		uni322.txt.gz				snapshot on mar 22
		uni_strain8.txt.gz			transplants into 8 seperate strains on new universe (from mar 22)
		dna_uni1.kf					the dna sample used to seed 'uni_strain8.txt'
```
