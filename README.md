# Cherry-world
Just another ropository

Oh! Just put the message in the wrong branch. :|
<div>
  <Here are the places I want to visit: <br>
  <ul>Seoul</ul>
  <ul>New York</ul>
  
  </div>
  
  <!-- Na początku link do czcionki "Lobster". -->
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">

<!-- W CSS nie musimy wstawiać "<style></style>" tak jak w HTML, żeby wiedział jak formatować wizualnie. -->
<style>
  <!-- Pozycje, które chcemy zaprogramować zawsze w wąsatych nawiasach. -->
  
  body {
    background-color:pink;
  }
  
  <!-- Przed klasmi (class), które nazywamy i chcemy wizualnie zaprogramować wstawiamy kropkę, a przed istenijącymi rzecami typu:h1, h2, body, p, itd. nie wstawiamy. -->
  
  .box {
    border-style:solid;
    border-color:black;
    border-width:5px;
    text-align:center;
  }
  
  h1 {
    text-align:center;
    font-size:30px;
    font-family:Lobster,Sans-Serif;
    
    <!-- Jeżeli czcionka nie pobierze się, to wtedy po przecinku dodać czcionkę zastępczą. -->
  }
  
  p {
   color:green;
    font-family:Monospace;
    text-align:left;
    
  }
    .thick-border {
    border-color:gray;
    border-width:10px;
    border-style:solid;
  }
  
  <!-- Jeśli checemy zaokrąglone brzegi to robimy to za pomocą [border-radius:10px lub 50%] możemy wpisać do ramki lub do zdjęcia. -->
  
  h4 {
    text-align:center;
  }
  
  h3 {
    text-alignl:left;
    color:red;
  }
  
  .larger-image {
    width:500px;
  }
 <!-- Możemy w CSS programować szerokość wstawianych zdjęć. -->
  
</style>
<!-- Tu kończy się programowanie wizualne, czyli to co w CSS. -->




<div class="container-fluid">

<h1 class="text-primary">Hello World!</h1>
  
<!-- Jeżeli chcemy użyć kilka klas z CSS to wpisujemy je po spacji np.[class="class1 class2"]. -->  
  
  
  <div class="box">
<!-- [<p>] paragraph -->    
<p>Hello, this is the description of the person or people.</p>
    
  <p>Click here for <a href=#>more.</a></p>
 <!-- W miejsce # należy wstawic odnośnik do strony, do której chcemy przekierować.

Aby link był w zdaniu wpisujemy go do zdania i nasz odnośnik-słowo znajduje się pomiędzy <a href=#> a </a> ['a' od anchor]
anlogicznie w przypadku zdjęcia <a href=#> <img src=# alt=#> </a> . -->   
   
    
 <form action="/url/"> 
   <input type="text" placeholder="Add e-mail">
   <button type="submit">submit</button>
   </form>   
 <!-- Moźliwość tworzenia formularza/pola tekstowego dla odpowiedzi od użytkownika
[<input type="text">].
Zanim użytkownik wpisze cokolwiek można wpisać teks zastępszy [<input type="text" placeholder="Tutaj wpisać">]. -->

<!-- Można tworzyć formularze, które rzeczywiście przesyłają dane na serwer i wtedy korzystamy z [<form action="/url-where-you-want-to-submit-form-data"> np.<input type="text> </form>]. -->
    
    <!-- Tworzenie przycisków przesyłania,które przesyłają dane [<button type="submit"> SUBMIT </button>]. -->
    
    
    
    
    
 <h3>Title number 1</h3> 
    
    
   
  <img class="thick-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cat">
 <!-- Dodajemy zdjęcia za pomocą [img] oraz [src="link do zdjęcia"], każde zdjęcie też powinno mieć podpis zdjęcia w [alt="podpis zdjęcia"] na wypadek gdyby się nie załadowało, aby odbiorca wiedział co mniejwięcej się tam znajdowało. -->   
    
    
    
    
    <h3 style="color:purple">This is the truth.</h3>
  <!-- Style tekstu można: 

* ręcznie programować wpisując obok [style="....np.color:blue"] 

*albo wpisywać motywy z CSS ze <style> i wtedy wpisujemy [class= np."red-text" nie wpisując kropki, która jest w CSS]

*albo poprostu zaprogramować od razu w CSS dla określonego np.formatu :
[h2 {
color:blue;
font-family:Arial;
}]
-->
    
    
    
  <p>This is the place, where you will get to know more about K-pop. K-pop is the music genre, also may known as Korean pop music. Right now is hard to tell how many Kpop groups are active at the moment, because each year lots of new groups debuts, but unfortunately also lots of groups disbands. Many people believe Kpop idustry is similar to a manufactury, which is not necessary false, because thinkig of the process of debuting a group or the industry itself is understandable. </p>

 <img class="thick-border" src="https://lh3.googleusercontent.com/BCchbRX5s3WgQ9wdFMOYAHqZ8fyvBD659dwpQQhUPbnnK47kqFd0oVljH3NWwppd3A_i1HHNT7HDzIur4ZoO9IA6EwbSYKNZuRCiJ-356TQra2Sin8Z-YKF8ZRHoErOEuA6Gcleqjg"
   alt="Sky">
    
     <img class="thick-border"  src="https://lh3.googleusercontent.com/ZLY0jjLXkAiisubXvSHdMN5fPilLfVk37_1IDHRHF3Hjd7Rq3PMjgCkK5ZP8-6Y80dQT0Bqk0tFCBaIRr63hqRDwq9Ca8JUIPE17LVWObBYCcHq2fpkRPbQTFaIYyG4nzavVIQuxTw" alt="bridge">
    
  <img class="thick-border"       src="https://lh3.googleusercontent.com/mpxSibEN4wefJMSYoga74WbTWhFAzH6fXNndTz5EvKCu6le3z7LPTsVeXNx9Tx6WQ4cGavXV81EC9JN__RGEcUbqwUhGt3e1AR_vyw-BZMz2hM8hegsOmHxpV8aUnO9yD8R9P5_JBQ" alt="day">
    
    
 
 
    <p>The photos:</p>
    <ul>
      <li>sunset in the city</li>
      <li>sunny day</li>
      <li>sunset bridge</li>
    </ul>
    
<!-- Tworzenie list:
* lista nieuporzątkowana/punktowa (unordered list): 
  <ul>
<li>każdy element</li> 
<li> </li>
  </ul>
* lista uporządkowana/ponumerowana (ordered list):
  <ol>
<li>element</li>
<li> </li>
  </ol>
-->

    <p style="text-align:center">Top 6 most favourite Kpop groups:</p>
    <ol>
      <li>EXO</li>
      <li>NCT</li>
      <li>BTS</li>
      <li>IOI</li>
      <li>SNSD</li>
      <li>Red Velvet</li>
    </ol>
    
    
    
  </div> 
  
  <div>
    
  <h4>"Everything is possible, impossible just need more time."</h4>
    
  </div>
  
</div>

