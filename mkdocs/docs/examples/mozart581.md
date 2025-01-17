
# Mozart Clarinet Quintet

This example illustrates the use of title and composer.
It's a short excerpt of Mozart Clarinet Quintet, K. 581 


~~~~~~
{
[ 	% first voice, clarinet in A
	\pageFormat<w=25cm,h=38cm,tm=4cm,lm=2cm,bm=2cm,rm=2cm>
	\title<"Clarinet Quintet"> \composer<"Mozart, K. 581",dy=5mm> 
	\systemFormat<dx=2cm>	 \barFormat<"system">

	\instr<"Clarinet in A",transp="A",autopos="on"> 
	\clef<"g">  \key<"A"> \meter<"3/4">
	\i<"p", dy=-1> \sl( a1/8 c#2 | 
	% measure 1, voice 1 
	e c# a/4 ) \sl( e/8 c# 
	% measure 2, voice 1
	h1 d2 f#/4)   \sl<"up">( d/8 h1
	% measure 3, voice 1
	\bm( a g# c#2 h1 e2 d )  )
	% measure 4, voice 1
	\sl( h#1/4 c#2 )  \sl( a1/8 c#2 | 
	% measure 5, voice 1
	e c# a/4 ) \sl( e/8 c#
	% measure 6, voice 1
	\acc( h1 ) d2 f#/4 ) _
	% measure 7, voice 1
	_*3/4
	% measure 8, voice 1
	_/4 _/4  \slurBegin<dx1=-2hs,dy1=-2hs,dy2=-2hs,r3=0.4,h=-8hs>  h0/12 f# d 
	% measure 9, voice 1
	\bm( f#0/8 \slurEnd \stacc( h d1 f# h d2 ) )
	% measure 10, voice 1
	\sl( \bm( f#2/8 e d c# d h1 ) ) 
	% measure 11, voice 1
	\sl( a/2 c#2/8 h1 ) 
	% measure 12, voice 1
	a/4 _ 	\text<"...", fsize=18pt, dy=-4> |
], 

[ 
	%second voice, violino I
	\instr<"Violino I",autopos="on"> \key<"A"> \meter<"3/4"> 
	_/4 | 
	% measures 1 to 5, voice 2
	_ \i<"p"> a a _ a a _ g# g# _ a a _ a a 
	% measure 6, voice 2
	f# _ \sl( c#2/8 a#1| 
	% measure 7, voice 2
	h d2 f#/4 ) \sl( c#/8 a#1 
	\newSystem
	% measure 8, voice 2
	h d2 f#/4 ) _ 
	% measures 9 to 10, voice 2
	_*3/4  _
	% measure 11, voice 2
	\bm( c#1/8 e c# e d e )
	% measure 12, voice 2
	c#/4 _
],

[ 
	% third voice, violino II
	\instr<"Violino II",autopos="on"> \clef<"g"> \key<"A"> \meter<"3/4">
	_/4 |
	% measures 1 to 5, voice 3
	_ \i<"p"> e e _ f# f# _ d d _ c# c# _ e e
	% measures 6 to 12, voice 3
	d _ \sl<dy1=-2,dy2=-3,r3=0.4,h=-4>( g f#/2 g/4 f#/2) _/4 
	_*3/4 _
	\sl<h=-5>( a0/2 g#/4 ) a/4 _ 
],

[ 
	% fourth voice, viola
	\instr<"Viola",autopos="on"> \clef<"c"> \key<"A"> \meter<"3/4">
	_/4 | 
	_ \i<"p"> c#1/4 c# _ b0 b _ b b _ a a _ c#1 c#
	h0 _ \sl<dy1=2,dy2=3,r3=0.7,h=3>( e1 d/2 e/4 d/2 ) _/4 
	_*3/4 _
	e0/1 _/4 
],

[ 
	% fifth voice, Cello
	\instr<"Cello",autopos="on"> \clef<"f"> \key<"A"> \meter<"3/4"> 
	_/4 |
	\i<"p"> a0/4 _ _ | d _ _ e _ _ f# _ _ c# _ _ d _ _ 
	_*3/4 _ _ _
	\sl( \stacc( e-1/4 e e ) ) a _ 
]
}
~~~~~~


<button class="try_it" onclick=window.open("https://guidoeditor.grame.fr/?src=https://raw.githubusercontent.com/grame-cncm/guidodoc/master/examples/mkdocs/examples/mozart581.gmn")>Try it online</button>

{!GMN/examples/mozart581.html!}

