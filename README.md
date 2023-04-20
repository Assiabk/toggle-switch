# toggle-switch
Interrupteur Bascule (Toggle Switch)
Ce code fournit un exemple de la mise en œuvre d'un interrupteur bascule en utilisant HTML, CSS et JavaScript. L'interrupteur bascule permet de passer d'un état à un autre en cliquant sur un bouton.

Utilisation
Pour utiliser l'interrupteur bascule, vous devez inclure le code HTML, CSS et JavaScript dans votre page web.
HTML
<label class="switch">
  <input type="checkbox" id="toggle-switch">
  <span class="slider round"></span>
</label>
Le code HTML ci-dessus crée un interrupteur bascule avec un bouton et une étiquette.

CSS
Le code CSS fournit des styles pour l'interrupteur bascule, notamment des couleurs pour l'état actif et inactif.
JavaScript
const toggleSwitch = document.getElementById("toggle-switch");
toggleSwitch.addEventListener("change", () => {
  // Code to be executed when the toggle switch is changed
  if (toggleSwitch.checked) {
    console.log("Toggle switch is on");
  } else {
    console.log("Toggle switch is off");
  }
});
Le code JavaScript fournit la logique pour changer l'état de l'interrupteur bascule et exécuter une action lorsque l'état est modifié.

Personnalisation
Vous pouvez personnaliser l'interrupteur bascule en modifiant le code CSS pour changer les couleurs, les styles et la taille de l'interrupteur bascule. Vous pouvez également modifier le code JavaScript pour exécuter une action différente lorsque l'état de l'interrupteur bascule est modifié.
BY[ASSSIA BENKHELIFA].
