# The title of your library here, either `library.inc` or `My Cool Library`

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

> Write your code documentation or examples here. If your library is documented in the source code, direct users there. If not, list your API and describe it well in this section.
> If your library is passive and has no API, simply omit this section.

## Testing

To test, simply run the package:

```bash
sampctl package run
```

And connect to `localhost:7777` to test.
