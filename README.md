# Free-Code-Cademy
Practicing HTML
#cat-photo-form {
  background-color: green;
}
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p>Click here for <a href="#">cat photos</a>.</p>

<a href="#"><img class="smaller-image thick-green-border" alt="A cute orange cat lying on its back. " src="https://bit.ly/fcc-relaxing-cat"></a>

<div class="silver-background">
<p>Things cats love:</p>
<ul>
  <li>cat nip</li>
  <li>laser pointers</li>
  <li>lasagna</li>
</ul>
<p>Top 3 things cats hate:</p>
<ol>
  <li>flea treatment</li>
  <li>thunder</li>
  <li>other cats</li>
</ol>
</div>

<form action="/submit-cat-photo" id="cat-photo-form">
<label><input type="radio" name="indoor-outdoor" checked> Indoor</label>
<label><input type="radio" name="indoor-outdoor"> Outdoor</label>
<label><input type="checkbox" name="personality" checked> Loving</label>
<label><input type="checkbox" name="personality"> Lazy</label>
<label><input type="checkbox" name="personality"> Energetic</label>
<input type="text" placeholder="cat photo URL" required>
<button type="submit">Submit</button>
</form>
