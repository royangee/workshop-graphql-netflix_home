```
mutation movies_scifi {
 #TEST MESSAGE
 fifthElement: insertmovies_by_genre(
    value: { 
      genre:"Sci-Fi", 
      year:1997,
      title:"The Fifth Element",
      synopsis:"In the colorful future, a cab driver unwittingly becomes the central figure in the search for a legendary cosmic weapon to keep Evil and Mr. Zorg at bay.",
      duration:126,
      thumbnail:"https://i.imgur.com/FO4iY2r.mp4"}) {
    value{title}
   }
}   
```
