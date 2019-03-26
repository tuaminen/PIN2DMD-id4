NOTES:
-Replace-moodin ajoitus toimii paremmin animaatioissa?


Testaus:
-Pin2dmd editor: File-> Export project (virt pin) to C:\Visual Pinball\VPinMAME\altcolor\id4
-Starttaa "C:\Visual Pinball\VPinball995.exe"

NEXT:
-"Color conversion PT"

attraction mode loppuun:
	-TODO	in memory of donald












Credit 1 scrollaa alhaalta kun laittaa rahaa




-laita start "independence day" alkuun

leikkaa multiball-flashing score jackpots erilleen

leikkaa 1 more hit.. alien erikseen



-pilko match osiin: anim. ennen numeroita vasemmalla


-pilko red alert osiin
 * red alert countdown alkaa "red alert"-animaatiolla, jossa frame#6 (hash 3100F575) on sama kuin 



Common design:
-4px reunus-teemat
-1px reunus-teemat







-------------------------------------------------------------------------------

Init mode:
OK		SEGA PINBALL ID4
OK		checksum
OK		location id

-------------------------------------------------------------------------------

Attraction mode:
OK		PUSH start (single + anim)
OK		insert coins
OK		replay at
OK		#1..#6 regular
OK		id4 logo
OK		just say no to alien invasion
UGLY	enjoy this game
OK		SEGA logo
OK		best value
OK		20th fox
OK		thanks to
OK		id4 super jackpot
UGLY	special thanks to trendmasters
BUGS	trendmasters id4 toys available
OK		in memory of Milton feldman
TODO	in memory of donald
OK		<score>	
OK		game over

OK	 	BSMT 2000
OK		digital sound system
UGLY	will Smith
UGLY	Bill Pullman
UGLY	Jeff Goldblum
UGLY	Mary McDonnell
UGLY	Judd Hirsch
UGLY	Robert Loggia
UGLY	Randy Quaid
UGLY	Margaret Colin
UGLY	Harvey Fierstein
UGLY	Viveca Fox
UGLY	Brent Spiner
OK? 	id4 credits
?		add 1 coin for 1 credit
? 		CREDIT 1/2
buggy	CREDIT x 
TODO 	CREDIT x 1/2  onko tätä?
TODO 	CREDITS x 1/2

-------------------------------------------------------------------------------

Game mode:

Start:
OK	start planet + "independence day"

Skill shot:
TODO	score anim (during ball start + when nothing happening)
TODO 	skill shot aim
UGLY 	skill shot missed
TODO	skill shot hit explosion anim
UGLY 	skill shot hit 20M

Virus:
OK		initiating computer virus
OK		virus 20% complete
OK		virus 40% complete
OK		virus 60% complete
OK		virus 100% complete
OK?		for 100M shoot right loop (virus complete)

Alien head: (OPTO trigger while alien closed, then Kicker10 under alien)
OK	 	lock 1 lit (contains transient to score in the end!)
OK		lock 1, timing issue
OK	 	lock 2 lit (contains transient to score in the end!)
OK		lock 2, timing issue
OK		multiball ready
OK		multiball (dogfight, "multiball")
TODO 	1 more hit for lock lit (leikkaa alien alusta pois)
cut 	2 more hits for lock lit
-	 	3 more hits for lock lit

Alien scan:
cut 	alien scan ready
cut 	alien scan, multiball
		alien scan, area 51 multiball -same beginning anim as in alien scan multiball?
		alien scan, add bonus X -same beginning anim as in alien scan multiball?
cut		alien frenzy - pops score 1MIL
cut		alien frenzy start anim
OK		X alien Y more for extra ball lit 
OK		X aliens Y more for extra ball lit
		
??
OK	 	alien ship explosion


Alien ships:
cut	10 million ship anim (hit 3 alien ships right to alien head)



Red alert:
OK		5 million, complete ramps for red alert
OK		5 million (large flashing, with borders)
OK		10 million, complete ramps for red alert
cut		10 million, complete this ramp for red alert
OK		10 million (large flashing, with borders)
cut		red alert + 50M flashing ramps countdown
cut		red alert 50M avarded
		
-		20 million, complete this ramp for red alert

F-18 hurry up:
OK		f-18 hurry-up grows
cut		f-18 hurry-up shoot left loop to kill alien ship
cut		f-18 hurry up total (displayed also after ball)
cut		10,000,000 finish bank again for F-18 hurryup

"newstuff"	f18 too late

July:
OK		july 2
OK		july 3
OK		july 4
OK		july 4 (later)
OK		july 5
OK		25 million


Pop bumpers:
OK		pop bumper score


Bonus stuff:
cut 	double jackpot 90M
cut 	double jackpot 40M
cut 	double jackpot 80M
cut		2x jackpot ready 80 million shoot right loop
cut		2x jackpot ready 80 million shoot left loop

-		triple jackpot anim
			120M
			135M

- super jackpot 
		160M
			
			
"newstuff"	jackpot alien

			
-		3x jackpots ready 120 million shoot center ramp / right ramp		

cut		jackpot ready 40 million shoot inside head
cut		2x bonus
cut		4x bonus
cut		8x bonus
cut		10x bonus
cut		ramp complete
		5 million (alien on top of text) 1st 
		5 million (alien on top of text) 2nd, any more??
-		20 million (large flashing)
-		50 million (large flashing)
cut		left loop plane&alien
cut		left loop plane shoots alien

cut 	multiball restart

area 51 multiball:
-		area 51 multiball siren anim
-		area 51 multiball mioni-loop = XXmil
		area 51 bonus
		
		ball added
replay (wh exposion)





Other:
cut		extra ball (white house explodes)
OK		<score>

OK		alien ship left anim
OK		alien ship right anim
TODO	DANGER + TILT


"newstuff"	"highest score" "300000000"


Ball end:
UGLY	bonus / id4 bonus / alien bonus / area 51 / Xx bonus / total bonus
cut		total bonus (animates from center)
OK?		shoot again
OK		ball saved
UGLY	fat lady sings
		
		
		
"new stuff"	"ball added" +  ship right-to-eft
		ball added -animation ('ball' 'added' texts vertically on the side)

TODO	combo / jackpot

TODO 	ramp complete + left ramp





-		extra ball is lit


50 million alien slime

TODO	"special"


TODO	PLAYER x up




TODO	SCORES

BUGS	match


TODO	5 million
TODO	loop combo x million, combo target = y million (skrollaa aina vasemmalta keskelle)


TODO	Instant info (hold right flipper)

-------------------------------------------------------------------------------

POSTGAME
OK		"enter initials"
OK		initials entry


-------------------------------------------------------------------------------

TRANSIENTS:
-red alert total -> spin -> score
-f-18 hurry up total -> spin -> score
-lock 1 lit -> rows -> score
-lock 2 lit -> rows -> score
<score> -> rows -> bonus
f-18 hurry up grows -> rows -> bonus


any -> scroll from bottom -> keep shooting, ball saved 
any -> scroll from bottom -> alien frenzy total
any -> grow from center -> total bonus XXXXXX 


-------------------------------------------------------------------------------

ISSUES:
-alien frenzy total beginning anim cannot be detected from a single row on the bottom

Q: onko 2x / 4x etc. bonukset aina "f-18 hurryup:n perään? ts. voiko ko. animaation aloittaa f-18:n lopputransientista? 
A: ei
