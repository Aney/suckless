# Mine

These commands are all exectuted by pressing the mod key with another key.

Mod = alt

## dwm, tag controls, layouts

### Layouts

t				= tabbed
f|shift			= fullscreen
m				= magnified
u				= bottomstack
o				= bottomstack vert
f				= floating

### Padding

add padding		= +
reduce padding	= -
reset padding	= =

## spawn controls

e				= lf
z				= htop
z|shift			= neofetch
n				= newsboat
v				= vim
w				= brave
w|Control		= firefox
g				= gimp
t|control		= Torrent Client
v|control		= VM Manager
m|control		= Music (ncmpcpp)
e|control		= email (neomutt/thunderbird)

## audio controls

i|shift			= volume up (amixer set Master 5%+)
d|shift			= volume down
m|shift			= toggle mute (amixer -D pulse set Master toggle)

## music controls

p|shift			= pause/play (mpc toggle)
]				= skip song (mpv next)_
[				= previous song (mpv prev)
]|shift			= skip 5s forward (mpc seek +5)
[|shift			= skip 5s backward
i|ctrl			= volume up
d|ctrl			= volume down

## screencaps, screenshots, etc (media making)

c				= screencap
c|shift			= end screencap
s|shift			= screenshot (maim)
s				= sreenshot selection (maim -s)
k|ctrl			= screenkey (show keypresses)

## other controls

l|ctrl			= slock
'				= VPN (restart/start different services)
;				= SSH (list and connect to vpn, or use an alternative IP)
/				= dwm scripts menu
y				= youtube-dl (with other dls and dl manager)
r				= display changer (WIP)
q				= kill client
