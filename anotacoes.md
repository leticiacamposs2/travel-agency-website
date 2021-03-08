# Travel Agency Website
Acesse: travel-agency-website.vercel.app/

### Dicas:

1. Para definir a paleta de cores pode usar esse site [colors.co](https://coolors.co/palettes/trending)
2. Para definir um template básico HTML 5 pode usar o site [sitepoint](https://www.sitepoint.com/a-basic-html5-template/)
3. Fontes personalizadas usa o [google fonts](https://fonts.google.com/)
4. Para melhorar a visibilidade conforme a scala do site muda é importante definir o [Viewport](https://www.w3schools.com/css/css_rwd_viewport.asp) do site
5. Para definir o preenchimento e a borda na largura e altura total de um emento usa-se o [Box-sizing](https://www.w3schools.com/css/css3_box-sizing.asp)

*O código abaixo garante que todos os elementos sejam dimensionados de forma mais intuitiva.*

```
* {
    box-sizing: border-box;
}
```

*Muitos navegadores já usam box-sizing: border-box;*

*Para muitos elementos de formulário (mas não todos - é por isso que as entradas e as áreas de texto parecem diferentes na largura: 100%;).*

6. Site de imagens gratuitas [Unsplash](https://unsplash.com/)
7. Documentações em inglês são muito ricas, exemplo o de background da [developer.mozilla](https://developer.mozilla.org/en-US/docs/Web/CSS/background) é possível até testar
8. A propriedade `cover` usada no background `no-repeat center/cover url` faz com a imagem se encaixe no tamanho da tela
9. Para consultar as medias queries mais importantes, consulte o forum sobre o assunto no [stackoverflow](https://stackoverflow.com/questions/12045893/which-are-the-most-important-media-queries-to-use-in-creating-mobile-responsive)

```javascript
/* Landscape phones and down */
@media (max-width: 480px) { ... }

/* Landscape phone to portrait tablet */
@media (max-width: 767px) { ... }

/* Portrait tablet to landscape and desktop */
@media (min-width: 768px) and (max-width: 979px) { ... }

/* Large desktop */
@media (min-width: 1200px) { ... }
```

10. Para os ícones o site usado foi [Feathericons](https://feathericons.com/)
11. Para idéias de sites, mockups usamos o site [Balbooa](http://balbooa.com/)
12. Dica de formatador de JS, CSS, HTML só instalar a extensão **JS-CSS-HTML Formatter**
13. Dica para adicionar map ao site pesquise no google por `map integration in html` e o serviço deste projeto foi o da [Google](https://developers.google.com/maps/documentation/javascript/adding-a-google-map)
14. Inserindo animação de smooth no link do menu, busca por `smoth scroll anchor` e no link do [stackoverflow]() vai ter o seguinte código

```javascript
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();

        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});
```
