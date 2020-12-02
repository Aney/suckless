# Mine

These commands are all exectuted by pressing the mod key with another key.

Mod = alt

## dwm, tag controls, layouts

### Layouts

t				= tabbed
f				= fullscreen
m				= magnified
u				= bottomstack
o				= bottomstack vert
f|shift			= floating

### Padding

add padding		= +
reduce padding	= -
reset padding	= =

## spawn controls

e				= lf
z				= htop
n				= newsboat
v				= vim
w				= brave
w|Control		= firefox
r				= display changer (WIP)
g				= gimp
c				= record
c|Shift			= end record
t|shift			= Torrent Client
				= VM Manager

## audio controls

i|shift			= volume up (amixer set Master 5%+)
d|shift			= volume down
m|shift			= toggle mute (amixer -D pulse set Master toggle)

## music controls

p|shift			= pause/play (mpc pause, play, stop?)
]				= skip song (mpv next)_
[				= previous song (mpv prev)
				= skip 5s forward (mpc seek +5)
				= skip 5s backward
i|ctrl			= volume up
d|ctrl			= volume down

## other controls

l				= slock
'				= VPN (restart/start different services)
;				= SSH (list and connect to vpn, or use an alternative IP)
r				= xrandr monitors
/				= dwm scripts menu
y				= youtube-dl (with other dls and dl manager)

## screencaps, screenshots, etc (media making)

c				= screencap
c|shift			= end screencap
s|shift			= screenshot (maim)
s				= sreenshot selection (maim -s)
s|ctrl			= slop screen selection
				= screenkey (show keypresses)
