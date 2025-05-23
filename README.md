# Assignment-9.-Monte-Carlo--simple-sampling-solution

Download Here: [Assignment 9. Monte Carlo -simple sampling solution](https://jarviscodinghub.com/assignment/assignment-9-monte-carlo-simple-sampling-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Problem 1. (3 points)
(a) (pencil and paper) Suppose that you use the Monte Carlo method to estimate the value
of a given quantity A. One simulation run gives you a single numerical value denoted by
Ai and by running the simulation n times you get the set {Ai}
n
i=1
. How can you obtain a
reliable estimate of the true value of A and how can you calculate an estimate of the error?
How is the central limit theorem related to the estimation?
(b) (computer) Write a program that computes an estimate of π using the “hit-or-miss”
Monte Carlo method. The program should also calculate an error estimate σ (as you
described in part (a)) and the absolute deviation from the correct value (π = 3.141592654).
Do this by generating N uniformly distributed random points inside the square defined by
−1 ≤ x ≤ 1 and −1 ≤ y ≤ 1. Calculate the number of points which are inside the circle
x
2 + y
2 = 1
2
. For each value of N, perform n = 1000 independent measurements. The
resulting average value
πest = π¯ =
1
n
n
∑
i=1
πi
is your MC estimate. The absolute error is ∆ = |πest −π|.
Plot your estimate of π, the error estimate log(σ) and the average absolute error log(∆) as
a function of log(N) for N = 1000−30000 (do a series of runs increasing N by 1000 at
each round). If the calculation takes too long for testing purposes, use smaller values of
N for testing. Plot the error and the error estimate in a single figure. What relation does
the error estimate follow? What about the absolute error?
1
Problem 2. (computer) (0 points – do not hand in)
Write a program which uses the “sample-mean” method to compute the integral
I =
Z 2
0
Z 6
3
Z 1
−1
(yx2 +zlny+e
x
)dx
dy
dz
Include the calculation of an error estimate in your program. Show the results as a function of N (number of random points). The correct answer is I ≈ 49.9213.
Problem 3 (computer) (2 points)
(a) Write a program which uses importance sampling to compute the integral
I =
Z 2
1
(2x
8 −1)dx
by using the weight function w(x) = Cx8
. Plot the result as a function of N.
(b) Compute the same integral using the sample mean method. Plot the absolute error
|Iest −I| as a function of N for the results obtained using the sample mean method and for
the results obtained in (a) using importance sampling. Which method is better?
Problem 4. (computer) (0 points – do not hand in)
Write a program which simulates the process of radioactive decay. You are given a sample
of N = 20000 radioactive nuclei each of which decays at a rate p per second. What is the
half-life of the sample if p = 0.4? Calculate the estimate of the half-life ht1/2
i from
m independent measurements and include an estimation of the error in your program.
Increase m until you reach an accuracy of at least 0.005.
