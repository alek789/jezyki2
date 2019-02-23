<!DOCTYPE html>
<html>
<head>
<style>
table {
  border-collapse: collapse;
  width: 100%;
}

th, td {
  padding: 8px;
  text-align: left;
  border-bottom: 2px solid #ddd;
}

tr:hover {background-color:#f5f5f5;}

@keyframes example {
  from {background-color: rgba(144,238,144,0.5);}
  to {background-color: rgba(0,128,0,1);}
}

/*Norweski*/
#n1:hover{

   transform: translate(110%,-100%);
   animation-name: example;
   animation-duration: 3s;
}

#n2:hover{

   transform: translate(110%,-200%);
   animation-name: example;
   animation-duration: 3s;
}

#n3:hover{

   transform: translate(110%,0%);
   animation-name: example;
   animation-duration: 3s;
}

#n4:hover{

   transform: translate(110%,300%);
   animation-name: example;
   animation-duration: 3s;
}
/*Norweski*/

/*Łaciński*/
#l1:hover{

   transform: translate(110%,0%);
   animation-name: example;
   animation-duration: 3s;
}

#l2:hover{

   transform: translate(110%,-100%);
   animation-name: example;
   animation-duration: 3s;
}

#l3:hover{

   transform: translate(110%,-100%);
   animation-name: example;
   animation-duration: 3s;
}

#l4:hover{

   transform: translate(110%,200%);
   animation-name: example;
   animation-duration: 3s;
}
/*Łaciński*/

/*Francuski*/
#f1:hover{

   transform: translate(110%,-200%);
   animation-name: example;
   animation-duration: 3s;
}

#f2:hover{

   transform: translate(110%,100%);
   animation-name: example;
   animation-duration: 3s;
}

#f3:hover{

   transform: translate(110%,100%);
   animation-name: example;
   animation-duration: 3s;
}

#f4:hover{

   transform: translate(110%,0%);
   animation-name: example;
   animation-duration: 3s;
}
/*Francuski*/

/*Indonezyjski*/
#i1:hover{

   transform: translate(110%,-300%);
   animation-name: example;
   animation-duration: 3s;
}

#i2:hover{

   transform: translate(110%,100%);
   animation-name: example;
   animation-duration: 3s;
}

#i3:hover{

   transform: translate(110%,0%);
   animation-name: example;
   animation-duration: 3s;
}

#i4:hover{

   transform: translate(110%,200%);
   animation-name: example;
   animation-duration: 3s;
}
/*Indonezyjski*/

/*Hiszpanski*/
#h1:hover{

   transform: translate(110%,0%);
   animation-name: example;
   animation-duration: 3s;
}

#h2:hover{

   transform: translate(110%,-100%);
   animation-name: example;
   animation-duration: 3s;
}

#h3:hover{

   transform: translate(110%,100%);
   animation-name: example;
   animation-duration: 3s;
}

#h4:hover{

   transform: translate(110%,0%);
   animation-name: example;
   animation-duration: 3s;
}
/*Hiszpanski*/

</style>
</head>
<body>

<h2>Norweski-Polski</h2>
<p>liczby</p>

<table>
  <tr>
    <th>Norweski</th>
    <th>Polski</th>
  </tr>
  <tr>
    <td id="n4">fire</td>
    <td>jeden</td>
  </tr>
  <tr>
    <td id="n1">ett</td>
    <td>dwa</td>
  </tr>
  <tr>
    <td id="n3">tre</td>
    <td>trzy</td>
  </tr>
  <tr>
    <td id="n2">to</td>
    <td>cztery</td>
  </tr>
</table>


<h2>Łaciński-Polski</h2>
<p>liczby</p>

<table>
  <tr>
    <th>Łaciński</th>
    <th>Polski</th>
  </tr>
  <tr>
    <td id="l1">unum</td>
    <td>jeden</td>
  </tr>
  <tr>
    <td id="l4">quattuor</td>
    <td>dwa</td>
  </tr>
  <tr>
    <td id="l2">duo</td>
    <td>trzy</td>
  </tr>
  <tr>
    <td id="l3">tribus</td>
    <td>cztery</td>
  </tr>
</table>


<h2>Francuski-Polski</h2>
<p>liczby</p>

<table>
  <tr>
    <th>Francuski</th>
    <th>Polski</th>
  </tr>
  <tr>
    <td id="f2">deux</td>
    <td>jeden</td>
  </tr>
  <tr>
    <td id="f3">trois</td>
    <td>dwa</td>
  </tr>
  <tr>
    <td id="f1">un</td>
    <td>trzy</td>
  </tr>
  <tr>
    <td id="f4">quatre</td>
    <td>cztery</td>
  </tr>
</table>


<h2>Indonezyjski-Polski</h2>
<p>liczby</p>

<table>
  <tr>
    <th>Indonezyjski</th>
    <th>Polski</th>
  </tr>
  <tr>
    <td id="i2">dua</td>
    <td>jeden</td>
  </tr>
  <tr>
    <td id="i4">empat</td>
    <td>dwa</td>
  </tr>
  <tr>
    <td id="i3">tiga</td>
    <td>trzy</td>
  </tr>
  <tr>
    <td id="i1">satu</td>
    <td>cztery</td>
  </tr>
</table>


<h2>Hiszpanski-Polski</h2>
<p>liczby</p>

<table>
  <tr>
    <th>Hiszpanski</th>
    <th>Polski</th>
  </tr>
  <tr>
    <td id="h1">uno</td>
    <td>jeden</td>
  </tr>
  <tr>
    <td id="h3">tres</td>
    <td>dwa</td>
  </tr>
  <tr>
    <td id="h2">dos</td>
    <td>trzy</td>
  </tr>
  <tr>
    <td id="h4">cuatro</td>
    <td>cztery</td>
  </tr>
</table>

</body>
</html>
