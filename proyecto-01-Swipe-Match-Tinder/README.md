<h1>Swipe Match Tinder</h1>

<p>Proyecto donde se busca recrear el match que tiene la app Tinder.
<br> Se trabajo con una estructura simple en HTML y usando imagenes para elementos secundarios.</p>

<h2>Imagen de muestra del proyecto</h2>
<img src="/proyecto-01-Swipe-Match-Tinder/img/Tinder.jpg">

<h1>Nuevos conocimientos aplicados</h1>

<h2>Utilización de article en el HTML para las card</h2>

```ruby
<article>
    <img src="./img/2.webp" alt="Alex, 25 years old"/>
    <h2>Alex <span>25</span></h2>
    <div class="choice nope">NOPE</div>
    <div class="choice like">LIKE</div>
</article>
```

<h2>Utilización de '&' en el CSS</h2>

```
header {
    display: flex;
    justify-content: center;

    & img {
        width: 24px;
        height: 24px;
    }
}
```


<h2>Utilización de 'Match y classList' en JAVASCRIPT</h2>


```
// saber si el usuario tomo una decision

        const decisionMade = Math.abs(pullDeltaX) >= DECISION_THRESHOLD

        if (decisionMade) {
            const goRight = pullDeltaX >= 0
            
            // add class acording to the decision
            actualCard.classList.add(goRight ? 'go-right' : 'go-left')
            actualCard.addEventListener('transitionend', () => {
                actualCard.remove()
            })
        } else {
            actualCard.classList.add('reset')
            actualCard.classList.remove('go-right', 'go-left')
            actualCard.querySelectorAll('.choice').forEach(el => {el.style.
            opacity = 0})
        }
```
<h3>Conclusión:</h3>

<p>Fue un excelente proyecto para poner en práctica todo lo aprendido anteriormente.<br>
Saludos!</p>
