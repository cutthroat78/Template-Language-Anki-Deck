# Template-Language-Anki-Deck

# Note Type Code
## Front
```
{{Gender}}
<br>
{{Target Language Word}}
```
## Back
```
{{FrontSide}}
<hr id=answer>
{{Reading}}{{Target Language Audio}}
<br>
{{Source Langauge Word}}
<br>
{{Target Language Sentence}}{{Target Language Sentence Audio}}
<br>
<p>{{Source Language Sentence}}</p>
{{Image}}
```
## Styling
```
.card {
  font-family: arial;
  font-size: 20px;
  text-align: center;
  color: black;
  background-color: white;
}

p {
  font-size: 15px;
}
```
