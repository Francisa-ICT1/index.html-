<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Title</title>
    <style>
        /* Background color */
        body {
            background-color: purple;
            color: white;
            font-family: Arial, sans-serif;
            text-align: center;
        }

        /* Styling for h1 */
        h1 {
            font-size: 3em;
            margin-top: 50px;
        }

        /* Styling for the paragraph */
        p {
            font-size: 1.2em;
            line-height: 1.6em;
        }

        /* Heart designs */
        .heart {
            position: relative;
            display: inline-block;
            width: 50px;
            height: 50px;
            background-color: red;
            clip-path: polygon(50% 0%, 0% 100%, 100% 100%);
            margin: 10px;
            transform: rotate(-45deg);
            animation: heartPulse 1.5s infinite;
        }

        .heart:before, .heart:after {
            content: "";
            position: absolute;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background-color: red;
            top: -25px;
            left: 0;
        }

        .heart:after {
            left: 25px;
        }

        /* Heart pulsing animation */
        @keyframes heartPulse {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.2);
            }
            100% {
                transform: scale(1);
            }
        }

        /* Green Flag section */
        h2 {
            font-size: 1.5em;
            color: limegreen;
        }

        .hearts-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 30px;
        }
    </style>
</head>
<body>

<h1>MY AKI</h1>
<p>
    Maalaga<br>
    Mapagbigay<br>
    Maalalahanin<br>
    May respeto<br>
    Masayahin<br>
    Supportive<br>
    Marunong makinig<br>
    Hindi madaling magalit (magtampo oo)<br>
    May sense of humor<br>
    Creative sa pagmamahal
</p>

<div class="hearts-container">
    <div class="heart"></div>
    <div class="heart"></div>
    <div class="heart"></div>
    <div class="heart"></div>
    <div class="heart"></div>
</div>

<h2>basta greenflag po ako</h2>
<p> mahal ko. Habang tinitipa ko ang mga salitang ito, hindi ko maiwasang mapangiti at madama ang init ng aking puso. Gusto ko lang sanang iparating sa'yo kung gaano kita kamahal, kung gaano mo ako pinapaligaya araw-araw sa simpleng mga bagay na ginagawa mo.<br>

Sa tuwing ako’y nandiyan sa iyong mga mata, pakiramdam ko’y ako na ang pinakamalaking biyaya sa mundong ito. Ang mga ngiti mo, mga tawa mo, at mga simpleng biro ay nagbibigay ng saya sa aking puso. Hindi ko na kayang isalarawan kung gaano ako kasaya at kuntento sa iyong presensya.<br>

Minsan, iniisip ko kung anong nangyari sa buhay ko na naging ikaw ang dahilan ng aking kaligayahan. Ang bawat sandali na magkasama tayo, ang bawat usapan, ang bawat halakhak—lahat ng ito’y puno ng kahulugan at hindi ko nais palampasin ni isang minuto ng ating pagsasama.<br>

Alam ko, hindi perpekto ang lahat. May mga pagkakataon na magkakaroon tayo ng hindi pagkakaintindihan, pero sana’y malaman mong hindi ako susuko sa atin. Kasi sa kabila ng lahat, ikaw ang dahilan kung bakit matatag pa rin ang puso ko, at ikaw ang aking lakas.<br>

Mahal ko, hindi ko alam kung anong kinabukasan ang naghihintay sa atin, pero kung ikaw ay kasama ko, tiwala akong magiging magaan ang lahat. Ibinubukas mo sa akin ang mga pinto ng bagong pag-asa at pagmamahal, at sa’yo ko nais manatili.<br>

Sana’y mapagtagumpayan natin ang bawat pagsubok na darating, at patuloy tayong maglakbay ng magkasama, magkahawak-kamay, at puno ng pagmamahal.<br>

Mahal kita, higit pa sa salita.<br>

Nagmamahal,
[francisa]</p>

</body>
</html>


