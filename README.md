# Lern-Bericht
`Gruppenname`: Dragonfruit

`Mitglieder`: Bytyqi, Gilardoni, Kritzner

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Einleitung
Wir haben eine Website über Fitness und alles was man darüber wissen muss programmiert.


## Was haben wir gelernt?


In diesem Projekt haben wir gelernt, wie man anhand Checkboxen Text verstecken und wieder zeigen kann.
## Beschreibung


Wir wissen nun wie wir mit Hilfe von einer Checkbox, einen Text verstecken können. 
Anhand des Codebeispiel (Siehe unten 👇🏼) kann man den Code sehen, welcher zum Verstecken des Texts verwendet wird.
Man kann auch mehrere Checkboxen verwenden um mehrere Texte zu verstecken.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
`Code Besipiel:`

```html
<input type="checkbox" id="ShowText" checked>
<label for="ShowText">Text anzeigen</label>

<div class="TextHidden">
    <P>
        Dieser Text kann versteckt werden.
    </P>
</div>
```

```css
.TextHidden {
    display: none;
    margin-left: auto;
    margin-right: auto;
    margin-top: 50px;
    padding: 10px;
    background-color: #B5B09F;
    font-size: large;
    text-align: center;
}

#ShowText:checked~.TextHidden {
    display: block;
}
```

`Gif:`


![Design ohne Titel (1)](https://github.com/V4nil/LA-1600/assets/110892683/c14c1911-4607-4ebe-a03b-46990520af4a)


## Verifikation

* `Code Beispiel:` Zeigt eine Checkbox und den Css Code dafür

* `Textbeschreibung:` Die Textbeschreibung dient zur Verständlichkeit des Codes und des Gifs.

* `Gif:` Das Gif dient zur Demonstration der Funktion der Checkbox

# Reflexion zum Arbeitsprozess


Bei unserer Arbeit lief gut, dass wir wenig Probleme mit dem Code hatten und HTML schnell lernen konnten.


Bei unserer Arbeit lief nicht gut, dass wir am Anfang einige Probleme mit der Zusammenarbeit hatten. Jeder hat einfach etwas programmiert und nachher hattten wir mehrere Websites. Nachher konnten wir aber die Zusammenarbeit verbessern.


**VBV**: Ein Verbesserungsvorschlag für uns wäre, dass wir am ende jeder Arbeitssession uns zusammen setzen und den Code zusammen stellen.
