## Kalon

### Getting started

The example below demonstrates a basic implementation of the library

```c#
var delay = TimeSpan.FromMilliseconds(0);
CursorMover.MoveCursor(0, 0, delay);
```

---

### CursorMover Class

Provides the functionality to move the cursor in a human realistic manner

```c#
public static class CursorMover
```

### Methods

Moves the cursor to a set of coordinates in a timespan

```c#
public static void MoveCursor(int, int, TimeSpan);
```
