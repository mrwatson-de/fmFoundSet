![fmFoundSet Logo](fmStoreFoundSet.png)
# fmFoundSet
[Now where was I again?]

A module for storing and restoring found sets (and later maybe more)


Just with a few extra TOs and layouts, plus a few scripts you can have the ability to store your found set (temporarily), do something else with it, and then restore it back to *exactly* where you were before.

Just download the file and take a look.


# How does it work?

Technically, it is using a relatively unknown feature of the Go to Related Records step where you can go to go to the _current_ table (instead of a related table), but using the extra '*_store' layout of the '*_store' TO instance.

# What do you need?

You need extra **'«to-name»_store' TOs** - to store the found set

- one for each table or found set you want to store
- no relationships needed :)

Each TO needs a **'«to-name»_store' layout as a landing page** for the Go to Related Records step.

**Scripts** to store or restore the required found set.

In the demo file there is a pair of simple scripts, which support a single store per table, plus a slightly more complex pair of scripts to support multiple stores per table.

Enjoy, and contact me if you need any help!

# Thanks!

Thanks to Koji Takeuchi of TonicNote Inc. at [Rome FileMakerWeek 2024](https://romefilemakerweek.com/) for reminding me about this long forgotten solution demo file.

