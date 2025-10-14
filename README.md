# 1st FreeCodeCamp project 
## Responsive Web Design Certification

**Variables explanation:**
- Explicit color names themed around space, void, black holes
- ``--space-xs`` extra small (0.5rem)
- ``--space-sm`` small (1rem)
- ``--space-md`` medium (1.5rem)
- ``--space-lg`` large (2rem)

My font choice is standard with an *"universal"* pile of font for Linux (KDE, Ubuntu, GNOME), macOS, Windows, iOS, Android.

**Use of CSS pseudo-class :**
- ``:hover`` to make an effect with mouse hover
- ``:active`` to make a feedback on clic, gets slightly smaller
- **WIP ongoing** ``:focus`` & ``:focus-visible``


**@keyframes :**
- ``fadeIn`` for a smooth apparition of the whole survey 
- ``slideUp`` to give a pop-up effect
- ``duckFloat`` for a bouncing/floating duck on hover


**@media queries :**
- Desktop > 768px for "standard" sized screens
- Tablet & small laptop ≤ 768px (``titles: 1.5 rem instead of 2rem``, ``smaller duck 20% instead of 15%``) to adapt design to middle size screens
- Mobile & small tablet ≤ 480px (``body {padding: 0.5rem}``, ``titles: 1.3rem & 1.1rem``, ``bigger duck 25%``, ``smaller hover animation 2px instead of 5px``) to optimise lisibility on smaller screens
- ``prefers-reduced-motion: reduce`` for users with accessibility settings to reduce motion

**TODO/WIP :**
- ``:focus`` & ``:focus-visible``
- ``:placeholder-shown`` to apply differences when placeholder is displayed or not *(input empty or filled)* and when filled with an error *(ex: wrong email format)*
- ``:valid`` & ``:invalid`` would work with ``placeholder-shown``
- ``:visited`` for potential links to show if visited or not
- More complex style for ``select {}``
- Pharacter count on ``<textarea>`` with something like ``<small>``
- Pulsing effecting on titles *(color change + slight translates)*
- Better accessibility on checkboxes and radios
- Add in background theme related effects *(particules, small glowing lights, comets, etc.)*
- Add some meanings to checkboxes values
