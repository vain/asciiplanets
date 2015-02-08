Having a little bit of fun.

![asciiplanets](/asciiplanets.png?raw=true)

![asciiplanets animated](/asciiplanets-animated.gif?raw=true)

    usage: asciiplanets [-h] [--outer] [--offset OFFSET] [--width WIDTH]
                        [--height HEIGHT] [--font-aspect FONT_ASPECT]
                        [--no-colors]
    
    Show planets in our solar system
    
    optional arguments:
      -h, --help            show this help message and exit
      --outer               Show outer solar system (default: False)
      --offset OFFSET       Time offset in days (default: 0)
      --width WIDTH         Terminal width (default: 80)
      --height HEIGHT       Terminal height (default: 24)
      --font-aspect FONT_ASPECT
                            Aspect ratio of your terminal's font (x / y) (default:
                            0.5)
      --no-colors           Disable colors (default: False)

Dependencies:

*  Python 3
*  [pyephem](http://rhodesmill.org/pyephem/)
