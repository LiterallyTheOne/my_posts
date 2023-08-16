# Uptime in linux

## Introduction

`uptime` is a simple command in `linux`, which shows you
how long the system has been running.

In this article, we are going to explain all the
information that `uptime` provides.

![Uptime](media/figures/uptime_linux.png)

`uptime` only has one line which can be divided to
3 parts that we explain all of them.

## Time

![time](media/figures/uptime_part1_time.jpg)

This part shows the current time, status of the system
(up), and how long the system has been running.

In this case, the current time was `15:19:19`, and
system has been running for 2 hours and 48 minutes.

## Users

![users](media/figures/uptime_part2_users.jpg)

This part shows how many users are connected to
the system.

In this case, there are two users connected to
the system, that you can see who are connected by
typing `users` in terminal.

## Load average

![load average](media/figures/uptime_part3_loadaverage.jpg)

`Load average`, shows us the `system load average` in
the past 3 different time periods, 1 minute,
5 minutes and 15 minutes.

`System load average` is calculated by averaging
the number of processes which are using the cpu
or waiting to use the cpu or cannot be interrupted
(waiting for Input/Output access).

If the first number of `load average` (1 minute),
is lower than the other two, means that your load
average is decreasing, and if it is higher than
the other two, it means your load average is
increasing.

If you have **n** `cpu core`s, a `load average`
lower than **n**, considered a good `load average`
and a `load average` higher than **n**, might result
in having a delay.

In this case we have a `load average` of 0.90 in
the last 1 minutes and 1.59 and 1.21 in the last 5
and 15 minutes.
