# moonphase
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/miguelverissimo/moonphase/master/LICENSE)

Package moonphase provides an API to calculate the phase of Moon, and other related variables.
It's a port of Ivan Menshykov's [goMoonPhase](https://github.com/janczer/goMoonPhase), which is a go port of [php-moon-phase](https://github.com/solarissmoke/php-moon-phase)

## Quick Start

```
time := time.Date(2007, 10, 1, 24, 0, 0, 0, time.UTC)
//time := time.Now()
m := MoonPhase.New(time)
```

## License

MoonPhase is released under the MIT License. It is copyrighted by Miguel Verissimo and the contributors acknowledged below.

## Acknowledgments

This module is a port of Ivan Menshykov's [goMoonPhase](https://github.com/janczer/goMoonPhase) package, which in turn is very closely derived from [php-moon-phase](https://github.com/solarissmoke/php-moon-phase) PHP class for calculating the phase of the Moon created by Samir Shah.
