gone
====

When leaving my desk, I like to run `gone` from the computer I am using.  It's a
simple little script that executes a forced standby on all of my machines to
conserve power.  This is important because I have 5 of them, not counting
transient laptops.

Your machine may already be configured to enter a state of reduced power
consumption after so many minutes.  However, if you know that you're leaving
immediately it would be prudent to expedite that transition, saving many
minutes a few times a day over the course of a year.

It is an insignificant savings at the individual level, but in aggregate (that
means everyone else that is not me) it is a good thing.

The incentive is to pad `gone` with more features that make it a useful utility
to run when you are leaving your desk, even if just for a few minutes.

# Setup

From wherever you stash your fork:

```
$ git clone http://github.com/ninegrid/gone.git .
$ ln -s ./gone ~/bin/gone
```

Edit the `gone` script and specify your own hostname(s).

# Usage

```
$ gone
```

# Todo

Currently I'm only using DPMS to put the monitors to sleep (I have 5 at my desk),
but the plan is to make this a robust tool for reminding me to perform/confirm
tasks before leaving my desk and to place all systems in modes of minimally
viable power consumption until I return.

# LICENSE

The Unlicense, free and unencumbered released into the public domain.
