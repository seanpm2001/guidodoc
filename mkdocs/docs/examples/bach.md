
# Bach

Johann Sebastian Bach - Invention 1 - BWV 772

Each line corresponds to a measure.
Note the use of \newPage ; without it, the system tries
to fill all pages and the result is an overcrowded system

Source: [Mutopia project](https://www.mutopiaproject.org/ftp/BachJS/BWV772/bach-invention-01/bach-invention-01-a4.pdf)

~~~~~~
{
	[
		\pageFormat<"A4", tm=6cm>
		\title<"Invention 1">
		\composer<"Johann Sebastian Bach (1685-1750)", dy=9>
		\composer<"BWV 772", dy=2>
		\systemFormat< dx=2cm> \barFormat<"system">
		\clef<"g"> \meter<"C"> 

		_/16 c d e f d e c \beam< dy2=-3>( g/8 c2 \mord(b1) c2 )
		d/16 g1 a b c2 a1 b g  \beam( d2/8 g \mord(f) g )
		e/16 a g f e g f a g f e d c e d f
		e d c b1 a c2 b1 d2 c b1 a g f# a g b
		a/8 d \mord< type="inverted">(c2.) d/16 b1 a g f# e g f# a
		g b a c2 b1 d2 c e d b1/32 c2 d/16 g \mord(b1/8) a/16 g 
		g/8 _ _/4 _/16 g a b c2 a1 b g 
		\mord(f#/8) _ _/4 _/16 a b c2 d b1 c2 a1

		\newPage
		\pageFormat<"A4", tm=2cm>
		b/8 _ _/4 _/16 d2 c b1 a c2 b1 d2 
		c/8 _ _/4 _/16  e d c b1 d2 c# e
		\beam (d/8 c# d e) \beam(f a1 \acc(b) c2)
		\stemsUp \beam (d f#1 g# a) \stemsDown b c2 \tie (d/4
		\stemsUp d/16)  e1 f# g# \stemsAuto a f# g# e e2 d c e d c b1 d2
		\stemsDown c a g# b a e f d g#1 f2 e d c/8 b1/16 a
		a a2g f e g f a \tie(g/2
		g/16) e f g a f g e \tie(f/2
		f/16) g f e d f e g \tie(f/2
		f/16) d e f g e f d \tie(e/2

		\newPage
		e/16) c d e f d e c d e f g a f g e
		f g a b c3 a2 b g c3/8 g2 e d/16 c
		c b&1 a g f a g b& a b c2 e1 d c2 f1 b 
		\fermata< position="above">(c2/1)
	],
	[
		\clef<"f"> \meter<"C"> 

		_/2 _/16 c0 d e f d e c
		g/8 g-1 _/4 _/16 g0 a b c1 a0 b g
		\beam (c1/8 b0 c1 d) \beam (e g0 a b)
		\beam (c1 e0 f# g) a b \tie(c1/4
		c/16) d0 e f# g e f# d \beam(g/8 b-1 c0 d)
		\beam (e f# g e) b-1/8. c0/16 \stemsUp d/8 d-1 \stemsAuto
		_/16 g-1 a b c0 a-1 b g \beam (d0/8 g f# g)
		a/16 d e f# g e f# d \beam(a/8 d1 c d)
		\stemsUp g0/16 \clef<"g"> g1 f e d f e g \beam ( f/8 e f d)
		e/16 a g f e g f a \beam(g/8 f g e)
		f/16 b& a g f a g b& a g f e d f e g
		f e d c b0 d1 c e d c b0 a g# b a c1 \clef<"f"> \stemsAuto
		b0/8 e \mord< type="inverted">(d1/8.) e/16 c b0 a \acc(g) f# a g# b
		a c1 b0 d1 c e d f \beam(e/8 a0 e1 e0)
		a a-1 _/4 _/16 e1 d c b0 d1 c# e 
		\tie(d/2 d/16) a0 b c1 d b0 c1 a0
		\tie(b/2 b/16) d1 c b0 a c1 b0 d1 
		\tie(c/2 c/16) g0 a b& c1 a0 b& g
		\beam(a/8 b& a g) \beam(f d1 c b0)
		\beam(a f1 e d) e/16 d0 e f g e f d
		\beam (e/8 c d e) f/16 d e f g/8 g-1 |
		\space<1cm>	
		\fermata< position="below">(\arpeggio< dy=1>({ c-1/1, c0, \staff<1> e1, g, c2 }))
	]
}
~~~~~~


<button class="try_it" onclick=window.open("https://guidoeditor.grame.fr/?src=https://raw.githubusercontent.com/grame-cncm/guidodoc/master/examples/mkdocs/examples/bach.gmn")>Try it online</button>

{!GMN/examples/bach.html!}

