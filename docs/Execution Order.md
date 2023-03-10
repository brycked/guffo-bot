Execution Order is something that determines which script is after the current one. In Fancade we follow the execution order *"top to bottom, left to right"* (in other words, the way you read this text).

Thus, a set of scripts arranged in the following order:

```
AB
CD
```

will be executed as A → B → C → D.

[[uploads/gkZWtHD.jpeg]]

That's helpful, but what if you want to modify it? Here comes *Execution Wires*. Those yellow wires at the top and bottom of some scripts named "Before" and "After" are what we call as execution wires. Execution Wires overrides the default execution order.

Once a script executes according to the default execution order, it'll execute all the scripts connected to it via Execution Wires before moving on the next script. A picture is worth a thousand words. So check these out:

[[uploads/e0EYbHB.jpeg]]
[[uploads/qsPi1I0.jpeg]]

Check out some common problems related to execution order [[here|what are some common problems related to execution order?]].