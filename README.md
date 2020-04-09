# OpenTal

taken from http://www.pkoziol.cal24.pl/opental

One more great chess engine from Paweł Kozioł:

OpenTal is an open source UCI chess engine that emulates weird and wonderful chess of "the wizard of Riga" - Mikhail Tal. It is based on Rodent, and probably plays at 2500-2600 Elo level. The exquisite tuner of chess engines, Brendan J. Norman, transformed all the missing rating points into pure style. OpenTal will sacrifice material, turning the chess board into a world of chaos, and will mount a reletless pressure on its opponent's position.

Against decent engines, OpenTal will overpress and lose. However, it is not meant to play against engines. It is meant to play against you. Install it under Winboard or Arena, and go against one of the greatest attackers of all time. No tweaks, no options, only Tal inside!

OpenTal has a couple of quirks. You can supply it with a modern opening book, but it will consult internal book made out of Tal's games first. Its evaluations are notoriously unrealistic and optimistic. It wants to win and expects it to happen.

Version 1.1 has been released on 2018.01.05. It uses unchanged eval, slightly better search and is capable of conducting a multi-pv search. This means you can actually analyze with Tal!

- - - -

I've only changed one little thing to create android build.
