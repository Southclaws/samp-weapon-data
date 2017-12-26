# weapon-data.inc

With this library you can finely tune weapon damage based on distance. Using min/max range values, a weapon's damage varies depending on the distance between the shooter and the target.

The values below for damage and magsize are NOT real game data values but custom values based on feedback about weapon balancing from the Scavenge and Survive community. All other data is factual.

## Installation

Simply install to your project:

```bash
sampctl package install Southclaws/samp-weapon-data
```

Include in your code and begin using the library:

```pawn
#include <weapon-data>
```

## Usage

Check source for documentation, all functions are commented.

## Testing

To test, simply run the package:

```bash
sampctl package run
```

And connect to `localhost:7777` to test.
