# architect-iso

Architect ISO source code

## More

The `initialise` script downloads either the [aif](https://github.com/winnie71/aif) or [aif-dev](https://github.com/winnie71/aif-dev) script depending on the user choice.

## TODO

- Fix broken stuff

- Move `aif` and `aif-dev` and `architect-iso` in a single repo

- General improvement

- Full revision with shell coding standards

- Make a Parabola GNU/Linux-libre version which must be in a different repository to avoid including any Arch Linux stuff, or 
  clearly separate and separable
  
- Add an option to load/save a configuration file in order to install/backup a whole system without user interaction. This could 
  be useful for stuff like:
  
  - Programs already installed
  
  - RAID,LUKS,LVM configurations which are difficult to specify during an installation
  
  - Files in the `.config` directory
  
  - Systemd enabled services
  
  - Misc
  
- Detailed documentation

  - Structure
  
  - Building
  
  - Customization
  
  - Misc
  
- Distributing the new ISOs

## Documentation

Possibly coming soon...

## License

Copyright (C) 2016 CarlDuff, 2017 Luciano Boccacciari, 2017 Franco Masotti <franco.masotti@student.unife.it>

architect-iso is free software: you can redistribute it and/or modify it
under the terms of the GNU General Public License as published by the Free
Software Foundation, either version 2 of the License, or (at your option) any
later version.
