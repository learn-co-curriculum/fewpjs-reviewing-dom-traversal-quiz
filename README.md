# Reviewing the DOM Traversal

Use the following markup to answer the questions below.

```html
<body>
  <section>
    <h1>Best Dinosaurs</h1>
    <ol>
      <li class="carnivore-link"><a href="http://dinosaurpictures.org/Velociraptor-pictures">Velociraptor</a></li>
      <li class="carnivore-link"><a href="http://dinosaurpictures.org/Tyrannosaurus-pictures">Tyrannosaurus</a></li>
      <li class="herbivore-link"><a href="http://dinosaurpictures.org/Diplodocus-pictures">Diplodocus</a></li>
      <li class="herbivore-link"><a href="http://dinosaurpictures.org/Apatosaurus-pictures">Apatosaurus</a></li>
      <li class="herbivore-link"><a href="http://dinosaurpictures.org/Triceratops-pictures">Triceratops</a></li>
    </ul>
  </section>
</body>
```

Q: What does `document.querySelector("li.herbivore-link")` return?
A: The first node with the `herbivore-link` class.

Q: What does `document.querySelectorAll("li.herbivore-link")` return?
A: All of the nodes with the `herbivore-link` class.

Q: What structure does the DOM representation represent?
A: A tree.
