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

        uni408.txt.gz               snapshot on apr 8. population increased. increased birth rates
        transplant_uni408.txt.gz    small transplant from the april 8 simulation. 40,000 units of energy
        uni410.txt.gz               snapshot on apr 10. same, boring.

        uni412.txt.gz               snapshot on apr 12. lots of shapes
        transplant_uni412.txt.gz    small transplant from the april 12 simulation. 25,000 units of energy

        uni413.txt.gz               snapshot on apr 13. no change
        uni414.txt.gz               snapshot on apr 14. main mass of creatures to the top,
                                    more patches of moving organisms everywhere.
        transplant_uni414.txt.gz    small transplant from the april 14 simulation. 5 different organisms.
                                    50,000 units of energy. has a 'blob' creature in the mix.

        uni415.txt.gz               snapshot on apr 15. main mass of creatures to the top,
                                    more patches of moving organisms everywhere.
        transplant_uni415.txt.gz    small transplant from the april 15 simulation. 5 different organisms.
                                    80,000 units of energy.

        uni416.txt.gz               snapshot on apr 16.
        uni417.txt.gz               snapshot on apr 17. interesting shapes and behaviors, more motion in center
        uni418.txt.gz               snapshot on apr 18. same
        uni419.txt.gz               snapshot on apr 19. same
        transplant_uni419.txt.gz    small transplant from the april 19 simulation. 10 or so different organisms.
                                    VERY NICE preditor/prey behaviors evident. 30,000 units of energy.
        uni420.txt.gz               snapshot on apr 20. same
        uni424.txt.gz               snapshot on apr 24. more non-moving blobs

        uni425.txt.gz               snapshot on apr 25. more non-moving blobs boring
        uni427.txt.gz               snapshot on apr 27. same
        uni502.txt.gz               snapshot on may 2. same, boring

        uni504.txt.gz               snapshot on may 4. same, boring
        uni505.txt.gz               snapshot on may 5. same, boring
        transplant_uni505.txt.gz    small transplant from the may 5 simulation. 10 or so different organisms.
                                    50,000 units of energy. good prey/predation behaviors.
        uni512.txt.gz               snapshot on may 12. same
        uni515.txt.gz               snapshot on may 15. same
        uni517.txt.gz               snapshot on may 17. something changed, more creatures.
        uni602.txt.gz               snapshot on june 2. same boooooring
        transplant_uni602.txt.gz    small transplant from the june 2 simulation.

        ----- the simulation got super boring, i changed the simuluation properties here ------

        uni609.txt.gz               snapshot on june 9. after a day with the new aggressive eat mode.
                                    also the grow size increased from 10 to 25. more fun to watch!
                                    way more reproduction and behaviors now.

        uni_strain8.txt.gz          transplants into 8 seperate strains on new universe (from mar 22)
        dna_uni1.kf                 the dna sample used to seed 'uni_strain8.txt'
```
