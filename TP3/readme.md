<h1>Intergation Numérique</h1>
<h2>Définition des méthodes</h2>
<h3>Méthodes des trapèzes</h3>

Soit N un entier non nul. On consid`ere ici la subdivision xk = a + kh avec h = b−a /N
(le pas de la subdivision) et k = 0, · · · , N. Donc Xk+1 − Xk = h
<br>
![Capture d’écran 2021-12-11 220442](https://user-images.githubusercontent.com/58143316/145691891-02f73345-c353-4289-bfd5-42d0ff92b3a7.png)
<br>l'erreur commise est :<br>
![Capture d’écran 2021-12-11 220502](https://user-images.githubusercontent.com/58143316/145691908-55a13610-5cf4-4b9d-8152-561b45a74972.png)
<br><br>

<h3>Méthodes des Simpson</h3>

Soit N un entier non nul pair. On consid`ere ici la subdivision xk = a + kh avec h = b−a/N (le pas de la subdivision) et k = 0, · · · , N. Donc xk+1 − xk = h. On a x0 = a et xN = b.
<br>
![Capture d’écran 2021-12-11 221806](https://user-images.githubusercontent.com/58143316/145692038-7f815835-b070-4fcd-a529-cdcdb02f93d1.png)
<br>l'erreur commise est :<br>
![simson erruer](https://user-images.githubusercontent.com/58143316/145692042-0756e76c-f334-44aa-a816-15d0e4630007.png)
<br><br>
<h2> Comparaison des méthodes </h2>
On compare les 4 methodes par ces tableaux avec:
<br>a=-3.14 et b=3.14 <br><br>
<li>On fixe N =15 et f(x)=sin(x)</li> <br>


|          | Trapèze                | Rectangle              | Milieur                 | Simpson              |
|----------|------------------------|------------------------|-------------------------|----------------------|
| integral | 9.300982661356355e-17  | 9.300982661356355e-17  | 2.7902947984069064e-16  | -0.08646964366433606 |
| erreur   | -9.300982661356355e-17 | -9.300982661356355e-17 | -2.7902947984069064e-16 | 0.08646964366433606  |
<br>
<li>On fixe N =25 et f(x)=sin(x)</li>

|          | Trapèze                | Rectangle               | Milieur                | Simpson               |
|----------|------------------------|-------------------------|------------------------|-----------------------|
| integral | 3.069324278247595e-16  | 2.7205374284467317e-16  | 4.464471677451047e-16  | -0.031417540527947305 |
| erreur   | -3.069324278247595e-16 | -2.7205374284467317e-16 | -4.464471677451047e-16 | 0.031417540527947305  |
<li>On fixe N =15 et f(x)=x**2+x-1</li>

|          | Trapèze              | Rectangle          | Milieur             | Simpson           |
|----------|----------------------|--------------------|---------------------|-------------------|
| integral | 14.571406711866516   | 13.255459458387932 | 14.295795363597184  | 9.97088108290478  |
| erreur   | -0.18374089884622613 | 1.1322063546323573 | 0.09187044942310507 | 4.416784730115509 |

<li>On fixe N =25 et f(x)=x**2+x-1</li>

|          | Trapèze              | Rectangle          | Milieur            | Simpson            |
|----------|----------------------|--------------------|--------------------|--------------------|
| integral | 14.453812536604932   | 13.66424418451778  | 14.354592451227973 | 11.593653905746976 |
| erreur   | -0.06614672358464269 | 0.7234216285025088 | 0.0330733617923169 | 2.7940119072733136 |

<h2>conclusion</h2>
<li>plus le nombre de subdivision n augmente plus l 'integral diminue et l'erreur commise diminue d'ou plus de precision de calcul</li>

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/najlahamza/ANALYSE_NUMERIQUE/1def7e9ded96b79e7476dd3005411806bd15fa41?urlpath=lab%2Ftree%2FTP3%2FExemple%20TP3.ipynb)


