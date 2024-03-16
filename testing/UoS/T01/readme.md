#### Three humps - Motionless steady state to verify robustness properties

This test is designed to demonstrate the ability of the ACC/FV1/DG2 solvers in preserving the steady state in the presense of wet/dry fronts. It involves a motionless flow over a 75 m × 30 m domain featured with three humps with shapes defined in [Liang and Borthwick (2009)](https://www.sciencedirect.com/science/article/abs/pii/S0045793008000479). The initial free-surface elevation is taken equal to h + z = 0.875 which makes the two smaller humps critically wet (i.e. h = 0 m at the peak) and the big hump partially wet involving wet–dry fronts. After running LISFLOOD-FP with ACC/FV1/DG2 solvers, it is expected that the flow remain motionless after 600 s and beyond, indicating that all the solver are able to robustly handle irregualr terrain with wetting-and-drying. 