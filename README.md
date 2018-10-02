# Colorizer
Colorize gtk and xfwm theme from .Xresources


## Dependencies
- Inkscape (to render assets in gtk theme)

## Usage
<pre>
$ ./colorizer.sh
                                    
 _____     _         _             
|     |___| |___ ___|_|___ ___ ___ 
|   --| . | | . |  _| |- _| -_|  _|
|_____|___|_|___|_| |_|___|___|_|  
                                   


Usage : colorizer [options #optional]

Avaible options
--wal       Generate color from pywal cache
--gtk       Choose gtk theme from list [ fantome ]
--xfwm      Choose xfwm4 theme from list [ pastel | black-paha | one_new | nest1 | diamondo | wendows | tetris | ribbon | just-title-bar ]
--openbox 	Choose openbox theme from list [ pelangi ]
--tint2 	Choose tint2 theme from list [ chromeos | chromeos-tinted | chromeos-pelangi | slim-text-dark | oslim-text-tinted]
--help      Show help
</pre>

To generate gtk theme and xfwm4 theme, use:
<pre>
$ ./colorizer.sh --wal --gtk fantome --xfwm [ pastel | black-paha | one_new | nest1 | diamondo | wendows ]
</pre>
To generate only xfwm4 theme, use:
<pre>
$ ./colorizer.sh --wal --xfwm [ pastel | black-paha | one_new | nest1 | diamondo | wendows ]
</pre>
remember to choose only one xfwm theme, and not using bracket
example:
<pre>
$ ./colorizer.sh --wal --xfwm pastel
</pre>
or

<pre>
$ ./colorizer.sh --wal --xfwm diamondo
</pre>

## Preview
[![change xfwm on the fly](preview/2018-06-14_06-43-02.jpg)](preview/2018-06-14_06-43-02.webm)

## Credits
- inspired by obtgen by [Fikri Omar](https://github.com/fikriomar16/obtgen/)
- xfwm theme from [Faat Fuut](https://github.com/Nztux/fuut-xfwm.xfce-theme-Collections)
- fantome gtk theme from [Adhi Pambudi](https://github.com/addy-dclxvi/gtk-theme-collections/)
- diamondo xfwm theme inspired by [Circela xfwm theme ](https://github.com/addy-dclxvi/xfwm4-theme-collections)
- xfwm theme from [Wotalim](https://github.com/wotalim/sora-aoi)
- openbox theme pelangi by [Adhi Pambudi](https://github.com/addy-dclxvi/openbox-theme-collections)