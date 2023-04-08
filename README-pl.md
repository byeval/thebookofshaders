<canvas id="custom" class="canvas" data-fragment-url="src/moon/moon.frag" data-textures="src/moon/moon.jpg" width="350px" height="350px"></canvas>

# The Book of Shaders
*autorstwa [Patricio Gonzalez Vivo](http://patriciogonzalezvivo.com/) i [Jen Lowe](http://jenlowe.net/)*

Łagodny, krok po kroku przewodnik przez abstrakcyjny i złożony świat Fragment Shaderów.

<div class="header">
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=B5FSVSHGEATCG" style="float: right;"><img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif" alt=""></a>
</div>

## Spis treści

* [O książce](00/)

* Wprowadzenie
    * [Czym jest shader?](01/)
    * ["Witaj świecie!"](02/)
    * [Uniformy](03/)
	* [Uruchomienie shaderu](04/)

* Rysowanie algorytmiczne
    * [Shaping functions](05/)
    * [Kolory](06/)
    * [Kształty](07/)
    * [Macierze](08/)
    * [Wzorce](09/)

* Design generatywny
    * [Random](10/)
    * [Noise](11/)
    * [Cellular noise](12/)
    * [Fractal Brownian Motion](13/)
    * Fraktale

* Image processing
    * Textures
    * Image operations
    * Kernel convolutions
    * Filters
    * Others effects

* Simulation
    * Pingpong
    * Conway
    * Ripples
    * Water color
    * Reaction diffusion

* 3D graphics
    * Lights
    * Normal-maps
    * Bump-maps
    * Ray marching
    * Environmental-maps (spherical and cube)
    * Reflect and refract

* [Dodatek:](appendix/) Inne sposoby korzystania z tej książki
	* [Jak mogę korzystać z tej książki offline?](appendix/00/)
	* [Jak uruchomić przykłady na Raspberry Pi?](appendix/01/)
	* [Jak wydrukować tę książkę?](appendix/02/)
    * [Jak mogę pomóc?](appendix/03/)
    * [Wprowadzenie dla biegłych w JavaScript](appendix/04/) by [Nicolas Barradeau](http://www.barradeau.com/)

* [Galeria przykładów](examples/)

* [Glosariusz](glossary/)

## O autorach

[Patricio Gonzalez Vivo](http://patriciogonzalezvivo.com/) (1982, Buenos Aires, Argentyna) jest nowojorskim artystą i developerem. Bada granice między organicznym a syntetycznym, analogowym a cyfrowym, indywidualnym i kolektywnym. W swojej pracy używa kodu jako ekspresywnego języka, z intencją rozwijania współpracy międzyludzkiej.

Patricio studiował i praktykował psychoterapię oraz arteterapię. Otrzymał tytuł magistra sztuk pięknych w Design & Technology od Parsons The New School, gdzie aktualnie uczy. Obecnie pracuje jako inżynier graficzny w Mapzen, gdzie tworzy opensource'owe narzędzia do kartografii komputerowej. 

<div class="header"> <a href="http://patriciogonzalezvivo.com/" target="_blank">www</a> - <a href="https://twitter.com/patriciogv" target="_blank">Twitter</a> - <a href="https://github.com/patriciogonzalezvivo" target="_blank">GitHub</a> - <a href="https://vimeo.com/patriciogv" target="_blank">Vimeo</a> - <a href="https://www.flickr.com/photos/106950246@N06/" target="_blank"> Flickr</a></div>

[Jen Lowe](http://jenlowe.net/) jest niezależną data scientist i komunikatorką danych w Datatelling, gdzie łączy ludzi + liczby + słowa. Uczy w ramach programu Design for Social Innovation na SVA, współzałożyła School for Poetic Computation, uczyła matematyki dla artystów w NYU ITP, była badaczką w Spatial Information Design Lab na Uniwersytecie Columbia oraz zgłaszała swoje pomysły do Office of Science and Technology Policy Białego Domu. Przemawiała na SXSW i w Eyeo. Jej pracę opisywały The New York Times i Fast Company. Jej działalność badawcza, pisarska i mównicza eksplorują obietnice oraz implikacje danych i technologii dla społeczeństwa. Obroniła tytuły licencjata matematyki stosowanej oraz magistra informatyki. Często opozycyjna, ale zawsze po stronie miłości.

<div class="header"> <a href="http://jenlowe.net/" target="_blank">www</a> - <a href="https://twitter.com/datatelling" target="_blank">Twitter</a> - <a href="https://github.com/datatelling" target="_blank">GitHub</a></div>

## Podziękowania

Podziękowania dla [Scott Murray](http://alignedleft.com/) za porady i inspriację.

Podziękowania dla [Kenichi Yoneda (Kynd)](https://twitter.com/kyndinfo), [Nicolas Barradeau](https://twitter.com/nicoptere), [Karim Naaji](http://karim.naaji.fr/) za wsparcie, dobre pomysły i kod.

Podziękowania dla [Kenichi Yoneda (Kynd)](https://twitter.com/kyndinfo) i [Sawako](https://twitter.com/sawakohome) za japońskie [tłumaczenie (日本語訳)](?lan=jp)

Podziękowania dla [Tong Li](https://www.facebook.com/tong.lee.9484) i [Yi Zhang](https://www.facebook.com/archer.zetta?pnref=story) za chińskie [tłumaczenie (中文版)](?lan=ch)

Podziękowania dla [Jae Hyun Yoo](https://www.facebook.com/fkkcloud) i [June Kim](https://github.com/rlawns324) za koreańskie [tłumaczenie (한국어)](?lan=kr)

Podziękowania dla Nahuel Coppero (Necsoft) za hiszpańskie [tłumaczenie (español)](?lan=es)

Podziękowania dla [Raphaela Protásio](https://github.com/Rawphs) i [Lucas Mendonça](https://github.com/luuchowl) za portugalskie [tłumaczenie (portugues)](?lan=pt)

Podziękowania dla [Nicolas Barradeau](https://twitter.com/nicoptere) i [Karim Naaji](http://karim.naaji.fr/) za francuskie [tłumaczenie (français)](?lan=fr)

Podziękowania dla [Andrea Rovescalli](https://www.earove.info) za włoskie [tłumaczenie (italiano)](?lan=it)

Podziękowania dla [Michael Tischer](http://www.mitinet.de) za niemieckie [tłumaczenie (deutsch)](?lan=de)

Podziękowania dla [Sergey Karchevsky](https://www.facebook.com/sergey.karchevsky.3) za rosyjskie [tłumaczenie (russian)](?lan=ru)

Podziękowania dla [Vu Phuong Hoang](https://www.facebook.com/vuphuonghoang88) za wietnamskie [tłumaczenie (Tiếng Việt)](?lan=vi)

Podziękowania dla [Andy Stanton](https://andy.stanton.is/) za naprawę i usprawnienie funkcji [eksportu pdf/epub ](https://thebookofshaders.com/appendix/02/)

Podziękowania dla każdego, kto [współtworzy](https://github.com/patriciogonzalezvivo/thebookofshaders/graphs/contributors) ten projekt poprzez swoje rady, korekty lub finansowe wsparcie.

## Zdobądź nowe rozdziały

Zapisz się do newslettera lub obserwuj na [Twitter](https://twitter.com/bookofshaders) / <a rel="me" href="https://mastodon.gamedev.place/@bookofshaders">Mastodon</a> / [Discord](shader.zone)

<div id="fd-form-623359074e5181d777e479f9"></div>
<script>
  window.fd('form', {
    formId: '623359074e5181d777e479f9',
    containerEl: '#fd-form-623359074e5181d777e479f9'
  });
</script>
