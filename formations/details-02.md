<h1 align="center">How to make a Video Game - Godot Beginner Tutorial</h1>

<p align="center">
  <b>Formation :</b> Godot University | <b>Dossier source :</b> image_d_02
</p>

---

<table>
  <tr>
    <td width="50%">
      <img src="image_d_02/assets.gif" width="100%" alt="Étape 1">
    </td>
    <td>
      <h3> Les assets : </h3>
      <p>Dans cette partie, on nous apprend les différents types d'assets et ce qu'ils représentent.</p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td>
      <h3> Comment fonctionne Godot ? </h3>
      <p>On nous explique comment fonctionne Godot à partir de Nodes.</p>
    </td>
    <td width="50%">
      <img src="image_d_02/hwg.gif" width="100%" alt="Étape 2">
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%">
      <img src="image_d_02/player1.0.gif" width="100%" alt="Étape 3">
    </td>
    <td>
      <h3> Le joueur 1.0 : </h3>
      <p> On commence la création du jeu. Pour cela, on crée le personnage que le joueur va incarner (on va l'appeler "joueur", c'est plus rapide). On lui ajoute une animation, une hitbox, des mécaniques de saut et de déplacement, et pour l'instant c'est tout ! </p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td>
      <h3> La construction du monde 1.0 :  </h3>
      <p>Ici, on apprend à utiliser la TileMap, très utile pour construire un monde et très ludique. Il suffit d'avoir, pour chaque type de bloc constituant notre monde, une case pour les placer en illimité.</p>
    </td>
    <td width="50%">
      <img src="image_d_02/worldbuilding1.0.gif" width="100%" alt="Étape 4">
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%">
      <img src="image_d_02/plateform.gif" width="100%" alt="Étape 4">
    </td>
    <td>
      <h3> Les plateformes : </h3>
      <p>Les plateformes sont vraiment simples à réaliser et efficaces. Pourquoi ? Parce qu'elles reprennent le système du joueur : c'est une "scène", donc on a plus de liberté que pour la TileMap et on peut y affecter du code pour pouvoir passer par-dessous la plateforme par exemple.</p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td>
      <h3> Les collectibles : </h3>
      <p>Les collectibles sont importants en jeu, surtout ici car c'est le but principal de ce projet. On récupère des pièces, on apprend à les faire disparaître et à augmenter un compteur quand le joueur passe sur l'une d'elles. On apprend aussi à changer leur palier de collision pour ne pas que les plateformes mouvantes "ramassent" aussi les pièces.</p>
    </td>
    <td width="50%">
      <img src="image_d_02/pickups.gif" width="100%" alt="Étape 4">
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%">
      <img src="image_d_02/dying1.0.gif" width="100%" alt="Étape 4">
    </td>
    <td>
      <h3> Mourir 1.0 : </h3>
      <p>La mort est la mécanique principale de presque tous les jeux au monde, il est donc normal qu'on apprenne à en faire une ici aussi, n'est-ce pas ? Pour cela, on va mettre une hitbox sous notre monde. Ainsi, quand le joueur tombera dans un trou, il touchera cette hitbox. On a juste à lui assigner le code pour nous faire réapparaître et réinitialiser le monde, et le tour est joué ! </p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td>
      <h3> La construction du monde 2.0 :  </h3>
      <p>Ici, c'est une petite étape détente : on se sert de ce qu'on a appris pour créer notre propre niveau avec nos scènes, nos scripts et nos TileMaps. MAIS on apprend aussi à faire un arrière-plan, qui se résume à créer une deuxième TileMap que l'on positionne en arrière-plan. Ça peut être pratique si on veut faire des passages secrets ;)</p>
    </td>
    <td width="50%">
      <img src="image_d_02/worldbuilding2.0.gif" width="100%" alt="Étape 4">
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%">
      <img src="image_d_02/ennemy.gif" width="100%" alt="Étape 4">
    </td>
    <td>
      <h3> Les ennemis </h3>
      <p>Avoir des ennemis dans un jeu, c'est important quand même ! Alors on nous apprend à les faire. C'est une scène, comme le joueur ou les plateformes. On lui donne une animation qui fait office d'apparence, on lui code des déplacements, une hitbox, une killzone, et c'est tout ce qu'on fera pour lui dans cette vidéo.</p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td>
      <h3> Mourir 2.0 : </h3>
      <p>On a de base une mort vraiment basique, alors cette partie de la vidéo sert à améliorer cette mécanique. On va ralentir le temps et enlever la hitbox de notre joueur, qu'il meure face à un ennemi ou qu'il tombe dans le vide.</p>
    </td>
    <td width="50%">
      <img src="image_d_02/dying2.0.gif" width="100%" alt="Étape 4">
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%">
      <img src="image_d_02/player2.0.gif" width="100%" alt="Étape 4">
    </td>
      <td>
      <h3> Le joueur 2.0 :  </h3>
      <p>C'est pareil pour notre joueur : il est basique, alors on l'améliore. On lui donne deux autres animations, le saut et la course, et on configure les touches : avancer, sauter, reculer, etc.</p>
    </td>
  </tr>
</table>

<table>
  <tr>
      <td>
      <h3> Ajouter du texte : </h3>
      <p>Pour ajouter de l'histoire, des quêtes ou faire parler des PNJ, il nous faut du texte. On apprend donc à en afficher, à changer la police, la taille, etc.</p>
    </td>
    <td width="50%">
      <img src="image_d_02/text.gif" width="100%" alt="Étape 4">
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%">
      <img src="image_d_02/score.gif" width="100%" alt="Étape 4">
    </td>
      <td>
      <h3> Créer un score : </h3>
      <p>Le texte sert aussi à afficher un score de fin de partie, et c'est à ça que servent les pièces. Ici, on programme notre texte pour qu'il affiche notre compteur de pièces à la fin du niveau.</p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td>
      <h3> Ajouter du son </h3>
      <p>Pour rendre l'expérience de jeu plus intéressante, on ajoute une musique de fond et des bruits de collecte de pièces.</p>
    </td>
    <td width="50%">
      <img src="image_d_02/audio.gif" width="100%" alt="Étape 4">
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%">
      <img src="image_d_02/export.gif" width="100%" alt="Étape 4">
    </td>
    <td>
      <h3>Exporter le projet : </h3>
      <p>Voilà ! On a fini notre mini-jeu !!! Bon, ce ne sera pas le GOTY 2026, mais c'est quand même pas mal, non ?</p>
    </td>
  </tr>
</table>

---
<p align="center"> J'aimerais préciser tout de même que cette vidéo est ici à but démonstratif et qu'en aucun cas elle ne me permet de créer un jeu à moi seul ; je serais bloqué à des mécaniques de 1990. Cette vidéo nous familiarise avec l'utilisation de Godot et nous aide à en comprendre le vocabulaire. En plus, on obtient un petit jeu en récompense à la fin ! : </p>

<p align="center">
<a href="https://qv3ntln.itch.io/how-to-make-a-game-godot-tutorial">
   <img src="image_d_02/images/Capture d’écran 2026-02-10 094403.png" width="300" alt="CLiuqyez pour y jouer ;)">
</a>
</p>
  
<p align="center">
  <a href="../README.md">
    <img src="https://img.shields.io/badge/⬅️_REVENIR_AU_PORTEFOLIO-333333?style=for-the-badge" />
  </a>
</p>
