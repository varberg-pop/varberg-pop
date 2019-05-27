---
layout: default
title: Behovet - Värmen
---

<form action="https://formspree.io/hampus.alfredsson@ri.se" method="POST">
  <div class="form-group">
    <label for="formGroupContact">Behovsägare (Vem?)</label>
    <input type="text" class="form-control" id="formGroupContact" name="name" placeholder="Förnamn Efternamn">
  </div>
  <div class="form-group">
    <input type="email" class="form-control" id="formGroupContact" name="_replyto" placeholder="namn@domän.namn">
  </div>
  <div class="form-group">
    <label for="formGroupCategory">Behovskategori (Vad?)</label>
    <textarea class="form-control" id="formGroupCategory" name="category" placeholder="Nyckelord för behovet (ex. <i>transportled</i>, <i>skyttel</i>, <i>leveranshubb</i>)"></textarea>
  </div>
  <div class="form-group">
    <label for="formGroupGoal">Målformulering (Varför?)</label>
    <textarea class="form-control" id="formGroupGoal" name="goal" placeholder="Beskriv kort varför behovet är viktig"></textarea>
  </div>
  <div class="form-group">
    <label for="formGroupEffect">Effektområde (Var?)</label>
    <textarea class="form-control" id="formGroupEffect" name="effect" placeholder="Vilket eller vilka områden är kopplade till behovet"></textarea>
  </div>
  <div class="form-group">
    <input type="submit" value="Send">
  </div>
</form>
