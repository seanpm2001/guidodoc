
# 4 Voices 

This example shows a 4 voices score written on 2 staves.
Tag used: 

- \staff for staff assignment
- \stemsUp \stemsDown for stems directions


~~~~~~
{
	[
		\pageFormat<lm=1cm, tm=1cm, bm=1cm, rm=1cm>
		\meter<"2/4"> \stemsUp
		\beam(g2*1/32 e*1/16 c*3/32) c2*1/8 \beam(a1*1/16 c2 f)
		\beam(g/32 d/16 h1*3/32) d2*1/8 \beam(h1*1/16 d2 g2)
	],
	[	\staff<1> \stemsDown g1*1/8 e \beam(g/16 d f a) a/8 e 
		\beam(a/16 e g h)
	],
	[	\staff<2> \meter<"2/4"> \stemsUp a0*1/4 f h c1 ],
	[	\staff<2> \stemsDown f0*1/4 d g a ]
}
~~~~~~


<button class="try_it" onclick=window.open("https://guidoeditor.grame.fr/?src=https://raw.githubusercontent.com/grame-cncm/guidodoc/master/examples/mkdocs/examples/4voices.gmn")>Try it online</button>

{!GMN/examples/4voices.html!}

