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

        uni.txt.gz                  simulation start day 0, march 19, 2023
        uni321.txt.gz               snapshot on mar 21
        uni322.txt.gz               snapshot on mar 22
        uni323.txt.gz               snapshot on mar 23, something changed! population finally spread out.
                                    no massive clumps of population.
        uni323_transplant.txt.gz    small transplant from the march 23 simulation.

        uni324.txt.gz               snapshot on mar 24
        uni325.txt.gz               snapshot on mar 25, boring again
        uni326.txt.gz               snapshot on mar 26, boring still
        uni326_transplant.txt.gz    small transplant from the march 26 simulation,
                                    circle maze, multiple strains.

        uni328.txt.gz               snapshot on mar 28, behavior slighly changed

        transplant_mar328.txt.gz    small transplant from the march 28 simulation, perlin terrain,
                                    nice sim, preditor/prey behavior evident.

        transplant_mar329.txt.gz    small transplant from the march 29 simulation.
                                    Just oval barrier. 1 strain. some pred/prey behaviors

        uni330.txt.gz               snapshot on mar 30, shapes slighly changed instead of this shape:
                                           ###
                                           ###
                                          ####

        uni331.txt.gz               snapshot on mar 31 no change
        uni401.txt.gz               snapshot on apr 1 no change
        uni402.txt.gz               snapshot on apr 2. slightly more population, higher birth rate

        transplant_uni402.txt.gz    small transplant from the april 2 simulation.
                                    Just oval barrier. multiple creatures copied. 60,000 energy

        uni404.txt.gz               snapshot on apr 4. no change. boring
        uni405.txt.gz               snapshot on apr 5. population dropping. slightly interesting again..

        transplant_uni405.txt.gz    small transplant from the april 5 simulation.
                                    Just oval barrier. 500x500, 1 strain. 40,000 units of energy.

        uni406.txt.gz               snapshot on apr 6. boring
        uni407.txt.gz               snapshot on apr 7. population increased again. same

        uni_strain8.txt.gz          transplants into 8 seperate strains on new universe (from mar 22)
        dna_uni1.kf                 the dna sample used to seed 'uni_strain8.txt'
```
