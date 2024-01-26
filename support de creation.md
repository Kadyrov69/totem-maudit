---
title: "Support de création"
order: 2
in_menu: true
---
# Le Support de Création

> ## <ins>***Alchemy*** : An open drawing project<ins>

![Logo d'Alchemy]({% link images/CaptureALCHEMY.PNG %})


> ***Récemment j’ai découvert un logiciel libre qui en premier lieu me paraissait exotique, depuis je ne peux plus m’en passer tellement qu’il est inspirant.***


- ***Alchemy***  

Il s’agit d’un outil de dessin / croquis expérimental qui offre une approche différente de la création artistique. Le logiciel vise à encourager la créativité en proposant des fonctionnalités uniques telles que des formes aléatoires, des symétries et des pinceaux dynamiques permettant aux artistes de créer des motifs complexes et des compositions équilibrées.

- Ce logiciel se distingue par son approche non conventionnelle du dessin. Il aide les utilisateurs à explorer de nouvelles idées et à générer des formes de manière spontanée.

- L'interface est minimaliste, mettant l’accent sur la simplicité pour favoriser l'imagination sans interface complexe.

- Le logiciel propose des outils permettant de générer des formes aléatoires, ce qui peut offrir beaucoup de possibilités.


- ***Alchemy*** est distribué en tant que projet open source, ce qui signifie que son code source est accessible au public. 

>  ***Voici le lien :***
<https://al.chemy.org/> 

## <ins> ***Stable Diffusion*** <ins>


> ***Après avoir esquissé un dessin sur notre fameux programme "Alchemy", je le soumets à l’IA nommée Stable Diffusion pour qu’elle l’interprète et génère des variantes créatives, enrichissant ainsi les possibilités artistiques de ma création initiale.***

> ***Voici le lien :***
<https://www.stable-diffusion-france.fr/> 

![Logo de Stable Diffusion]({% link images/stableIA.jpg %}) 


<div class="scene">
  <div class="lava-lamp" style="--height: 400; --width: 150">
    <div class="lava-lamp__main">
      <div class="lava-lamp__glass">
          <div class="lava-lamp__lava">
            <svg>
              <ellipse class="blob blob--top" cx="35" cy="0" rx="35" ry="10"></ellipse>
              <ellipse class="blob blob--bottom" cx="75" cy="270" rx="75" ry="10"></ellipse>
              <circle class="blob" r="15" cx="0" cy="400" style="--skewX: -1; --skewY: 0; --height: 30; --speed: 41; --delay: -8; --direction: alternate;"></circle>
              <circle class="blob" r="36" cx="107" cy="400" style="--skewX: -4; --skewY: -2; --height: 72; --speed: 19; --delay: -7; --direction: alternate-reverse;"></circle>
              <circle class="blob" r="37.5" cx="96" cy="400" style="--skewX: 2; --skewY: 4; --height: 75; --speed: 34; --delay: -7; --direction: alternate;"></circle>
            </svg>
          </div>
          <div class="lava-lamp__lava">
            <svg>
              <ellipse class="blob blob--top" cx="35" cy="0" rx="35" ry="10"></ellipse>
              <ellipse class="blob blob--bottom" cx="75" cy="270" rx="75" ry="10"></ellipse>
              <circle class="blob" r="27.5" cx="33" cy="400" style="--skewX: 0; --skewY: -2; --height: 55; --speed: 22; --delay: -4; --direction: alternate-reverse;"></circle>
              <circle class="blob" r="34" cx="97" cy="400" style="--skewX: 5; --skewY: 0; --height: 68; --speed: 46; --delay: 0; --direction: alternate-reverse;"></circle>
              <circle class="blob" r="42.5" cx="93" cy="400" style="--skewX: -3; --skewY: -2; --height: 85; --speed: 21; --delay: 0; --direction: alternate;"></circle>
              <circle class="blob" r="25.5" cx="19" cy="400" style="--skewX: -3; --skewY: -4; --height: 51; --speed: 45; --delay: -8; --direction: alternate;"></circle>
            </svg>
          </div>
          <div class="lava-lamp__lava">
            <svg>
              <ellipse class="blob blob--top" cx="35" cy="0" rx="35" ry="10"></ellipse>
              <ellipse class="blob blob--bottom" cx="75" cy="270" rx="75" ry="10"></ellipse>
              <circle class="blob" r="32" cx="10" cy="400" style="--skewX: 1; --skewY: -2; --height: 64; --speed: 37; --delay: -7; --direction: alternate;"></circle>
              <circle class="blob" r="25" cx="88" cy="400" style="--skewX: 2; --skewY: 2; --height: 50; --speed: 30; --delay: -10; --direction: alternate;"></circle>
            </svg>
          </div>
          <div class="lava-lamp__lava">
            <svg>
              <ellipse class="blob blob--top" cx="35" cy="0" rx="35" ry="10"></ellipse>
              <ellipse class="blob blob--bottom" cx="75" cy="270" rx="75" ry="10"></ellipse>
              <circle class="blob" r="33" cx="138" cy="400" style="--skewX: -1; --skewY: 0; --height: 66; --speed: 48; --delay: -5; --direction: alternate-reverse;"></circle>
            </svg>
          </div>
      </div>
    </div>
    <div class="lava-lamp__base"></div>
  </div>
  <svg style="position: absolute; left: 100%">
    <defs>
      <filter id="goo">
        <feGaussianBlur in="SourceGraphic" stdDeviation="10" result="BLUR"></feGaussianBlur>
        <feColorMatrix in="BLUR" mode="matrix" values="1 0 0 0 0  0 1 0 0 0  0 0 1 0 0  0 0 0 18 -7" result="GOO"></feColorMatrix>
        <feBlend in="SourceGraphic" in2="goo"></feBlend>
      </filter>
    </defs>
  </svg>
</div> 