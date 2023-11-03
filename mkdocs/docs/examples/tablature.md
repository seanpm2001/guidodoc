
	Example of tablatures mixed with regular notation

~~~~~~
{
[
	\title<"Sultan Of Swing">
	\composer<"Words & Music by Dire Straits", dy=5>

	\pageFormat<w=21cm, h=29.7cm, lm=2.5cm, rm=2.5cm, bm=4cm, tm=6cm>
	\clef<"g"> \meter<"4/4", autoMeasuresNum="system"> \accolade<type="none">
	_/2 { g/8, c2 } a1 { g/8, c2 } \noteFormat<style="x"> ({ g1, d })
	\stemsDown	
	\text<"sl", fsize=11pt, dy=13, dx=2, fattrib="i">({ g/8, c2 } \tie( { a1, d2 } { a1/2., d2 }))
	_/2 _/8 g1/8 a \trill<begin="off">(d2/2.) a1/8 f2 d/2  
	d/16 f a/8 c3/4 a2/8
	\trill<begin="off">(f/4.) f/8 
	\text<"H", dy=15, fsize=3,dx =1>(\sl(e f)) e \trill<begin="off", dy=3>( \tie(d
	d/1)) |
]
, 
[
	\clef<"TAB"> \meter<"4/4", hidden="on">
	\staffFormat<style="TAB">
	empty/2 { s4:5:/8, s3:5: } s4:7: { s4:5:/8, s3:5: } { s4:x:/8, s3:x: }
	\text<"sl", fsize=8pt, dy=13, dx=1.5, fattrib="i">({ s4:5:/8, s3:5: }	{ s4:7:/8, s3:7: }) empty/2.
	empty/2 empty/8 s4:5: s4:7: \trill<begin="off">(s3:7:/2.)
	s4:7:/8 s3:10: s3:7:/2
	s3:7:/16 s2:6: s1:5:/8 s1:8:/4 s1:5:/8

	\trill<begin="off">(s2:6:/4.) s2:6:/8 
	\text<"H", dy=13, fsize=2, dx =1> (\sl<curve="up">(s2:5: s2:6:)) s2:5: 
	\trill<begin="off">( s3:7: s3:(7):/1)
	|
]
}
~~~~~~


<button class="try_it" onclick=window.open("https://guidoeditor.grame.fr/?src=https://raw.githubusercontent.com/grame-cncm/guidodoc/master/examples/mkdocs/examples/tablature.gmn")>Try it online</button>

{!GMN/examples/tablature.html!}
