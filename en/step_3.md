## Scratch 3!

It appears there's an issue with display Scratch 3 blocks on the same page as Scratch 2 blocks. This is unlikely to ever happen in a real project, so this step shows Scratch 3 in isolation so we can verify it displays correctly in all the different settings it can appear.

### Broken code from Lost in Space project:

```blocks3
forever
end

turn cw (15) degrees

when flag clicked
```

### On its own!

```blocks3
when flag clicked
forever
repeat (10)
	change y by (10)
end
repeat (10)
	change y by (-10)
end
```

### Inside a Task!

--- task ---
```blocks3
when flag clicked
forever
repeat (10)
	change y by (10)
end
repeat (10)
	change y by (-10)
end
```
--- /task ---

### Inside a Hint!

--- hints ---
--- hint ---
It's on the second slide!
--- /hint ---
--- hint ---

```blocks3
when flag clicked
forever
repeat (10)
	change y by (10)
end
repeat (10)
	change y by (-10)
end
```
--- /hint ---
--- /hints ---

### Inside a Hint INSIDE A TASK!

--- task ---
I can't handle this. What could be next?

--- hints ---
--- hint ---
It's on the second slide!
--- /hint ---
--- hint ---

```blocks3
when flag clicked
forever
repeat (10)
	change y by (10)
end
repeat (10)
	change y by (-10)
end
```
--- /hint ---
--- /hints ---
--- /task ---

I think that's it! Let's see how that works!
