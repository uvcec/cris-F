!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="../css/style.css">
    <title>1st sem subjects</title>
</head>
<body>
  <header class="header"><button class="button1" onclick="location.href='../index.html'">
    GPA Generator</button> >> <button class="button1" onclick="location.href='../mech.html'"> Mechanical </button> >> 1st Sem
  </header>
  <br><br><br><br>  
    <table class="center animate">
        <tr id="1">
          <th>Sl. No</th>
          <th>Course Code</th>
          <th>Subjects</th>
          <th>No. of Credits</th>
          <th>CIE</th>
          <th>SEE</th>
          <th>Total(CIE+SEE)</th>
          <th>Grade</th>
          <th>Grade Point</th>
          <th>Credit Point</th>
        </tr>
        <tr id="2">
          <td>1</td>
          <td name="code">18BSEM101</td>
          <td>Engineering Mathematics-1</td>
          <td id="noc0">3</td>
          <td><input type="number" name="cie0" id="cie0" min="20" max="50"></td>
          <td><input type="number" name="see0" id="see0" min="20" max="50"></td>
          <td id="totOfRow0"></td>
          <td id="g0"></td>
          <td id="gp0"></td>
          <td id="cp0"></td>
        </tr>
        <tr id="3">
          <td>2</td>
          <td>18BSCH110</td>
          <td>Engineering Chemistry-Theroy</td>
          <td id="noc1">3</td>
          <td><input type="number" name="cie1" id="cie1" min="20" max="50"></td>
          <td><input type="number" name="see1" id="see1" min="20" max="50"></td>
          <td id="totOfRow1"></td>
          <td id="g1"></td>
          <td id="gp1"></td>
          <td id="cp1"></td>
        </tr>
        <tr id="4">
          <td>3</td>
          <td>18BSCH111</td>
          <td>Engineering Chemistry-Practical</td>
          <td id="noc2">1.5</td>
          <td><input type="number" name="cie2" id="cie2" min="20" max="50"></td>
          <td><input type="number" name="see2" id="see2" min="20" max="50"></td>
          <td id="totOfRow2"></td>
          <td id="g2"></td>
          <td id="gp2"></td>
          <td id="cp2"></td>
        </tr>
        <tr id="5">
          <td>4</td>
          <td>18ESME112</td>
          <td>Engineering Graphics & Design</td>
          <td id="noc3">4</td>
          <td><input type="number" name="cie3" id="cie3" min="20" max="50"></td>
          <td><input type="number" name="see3" id="see3" min="20" max="50"></td>
          <td id="totOfRow3"></td>
          <td id="g3"></td>
          <td id="gp3"></td>
          <td id="cp3"></td>
        </tr>
        <tr id="6">
          <td>5</td>
          <td>18ESCV113</td>
          <td>Engineering Mechanics</td>
          <td id="noc4">3</td>
          <td><input type="number" name="cie4" id="cie4" min="20" max="50"></td>
          <td><input type="number" name="see4" id="see4" min="20" max="50"></td>
          <td id="totOfRow4"></td>
          <td id="g4"></td>
          <td id="gp4"></td>
          <td id="cp4"></td>
        </tr>
        <tr id="7">
          <td>6</td>
          <td>18ESCS114</td>
          <td>Programming for Problem Solving-Theory</td>
          <td id="noc5">3</td>
          <td><input type="number" name="cie5" id="cie5" min="20" max="50"></td>
          <td><input type="number" name="see5" id="see5" min="20" max="50"></td>
          <td id="totOfRow5"></td>
          <td id="g5"></td>
          <td id="gp5"></td>
          <td id="cp5"></td>
        </tr>
        <tr id="8">
          <td>7</td>
          <td>18ESCS115</td>
          <td>Programming for Problem Solving-Practical</td>
          <td id="noc6">1.5</td>
          <td><input type="number" name="cie6" id="cie6" min="20" max="50"></td>
          <td><input type="number" name="see6" id="see6" min="20" max="50"></td>
          <td id="totOfRow6"></td>
          <td id="g6"></td>
          <td id="gp6"></td>
          <td id="cp6"></td>
        </tr>
        <tr id="9">
          <td>8</td>
          <td>18MCKN116</td>
          <td>Kannada</td>
          <td id="noc7">1</td>
          <td><input type="number" name="cie7" id="cie7" min="20" max="50"></td>
          <td id="see7"></td>
          <td id="totOfRow7"></td>
          <td id="g7"></td>
          <td id="gp7"></td>
          <td id="cp7"></td>
        </tr>
        <tr id="10">
            <td>9</td>
            <td>18MCIP109</td>
            <td>Induction Program</td>
            <td id="noc8">1</td>
            <td><input type="number" name="cie8" id="cie8" min="20" max="50"></td>
            <td id="see8"></td>
            <td id="totOfRow8"></td>
            <td id="g8"></td>
            <td id="gp8"></td>
            <td id="cp8"></td>
          </tr>
        <tr id="11">
            <td></td>
            <td></td>
            <td>Totals</td>
            <td id="totOfCol-1"></td>
            <td id="totOfCol0"></td>
            <td id="totOfCol1"></td>
            <td id="totOfCol2"></td>
            <td id="totOfCol3"></td>
            <td id="totOfCol4"></td>
            <td id="totOfCol5"></td>
        </tr>
    </table>
<br>
<br>
<br>
<hr class="new animate" align="center">
<p align="center" class="animate">
  <b>Percetage: <span align="center" id="per"></span> % </b>
</p>
<p align="center" class="animate">
  <b>SGPA: <span align="center" id="sgpa"></span> GPA </b>
</p><!--displays the percentage and SGPA-->
  
<div align="center" class="animate"><!--button + animation-->
    <button class="button success" onclick="getOption()"><span> Check </span></button>
</div>
<p id="alert"></p><!--alreats if proper value isnt entered by the user-->

<div id="footer" class="animate">
  <div>
      <p>Developed by Cris F, 2022</p>
  </div>
</div>

</body>
<script>
  function getOption() {
    const nos=7;
    var x=new Array(nos);
    var y=new Array(nos);
    var z=[];
    var a=0;
    var b=[];
    var c=[];
    var d=[];
    var e=[];
    var f=0;
    var totCreds=0;

    for (let i = 0; i < 9; i++) {
        let p="noc";
        totCreds+= parseFloat(document.getElementById(p.concat(i)).innerHTML); 
    }

    document.getElementById("totOfCol-1").innerHTML=totCreds;

    for (let i = 0; i < x.length; i++) {
        let p="cie";
        let q="see";


        x[i]=document.getElementById(p.concat(i)).value;
        y[i]=document.getElementById(q.concat(i)).value;
    }

    x[7]=document.getElementById("cie7").value;
    y[7]=x[7];
    document.getElementById("see7").innerHTML=y[7];
    
    x[8]=document.getElementById("cie8").value;
    y[8]=x[8];
    document.getElementById("see8").innerHTML=y[8];

    for (let i = 0; i < x.length; i++) {
    z[i]=parseFloat(x[i]) + parseFloat(y[i]);
    a=parseFloat(a+z[i]);
    }

    for (let i = 0; i < z.length; i++) {
      if(isNaN(z[i])){
        document.getElementById("demo").innerHTML = alert("Please enter proper values");
      }
      
    }

    for (let i = 0; i < z.length; i++) {
        let p="totOfRow";
        document.getElementById(p.concat(i)).innerHTML=z[i];
        
    }

    /*document.getElementById("totOfRow0").innerHTML=z[0];
    document.getElementById("totOfRow1").innerHTML=z[1];
    document.getElementById("totOfRow2").innerHTML=z[2];
    document.getElementById("totOfRow3").innerHTML=z[3];
    document.getElementById("totOfRow4").innerHTML=z[4];
    document.getElementById("totOfRow5").innerHTML=z[5];
    document.getElementById("totOfRow6").innerHTML=z[6];
    document.getElementById("totOfRow7").innerHTML=z[7];*/
    document.getElementById("totOfCol2").innerHTML=a;

    
    for (let j = 0; j < z.length; j++) {
      if(z[j]>=90){
        b[j]="S";
      }
      else if(z[j]>=75){
        b[j]="A";
      }
      else if(z[j]>=60){
        b[j]="B";
      }
      else if(z[j]>=50){
        b[j]="C";
      }
      else if(z[j]>=45){
        b[j]="D";
      }
      else if(z[j]>=40){
        b[j]="E";
      }
      else if(z[j]>0){
        b[j]="F";
      }
    }

    for (let i = 0; i < z.length; i++) {
        let p="g";
        document.getElementById(p.concat(i)).innerHTML=b[i];
        
    }

    /*document.getElementById("g0").innerHTML=b[0];
    document.getElementById("g1").innerHTML=b[1];
    document.getElementById("g2").innerHTML=b[2];
    document.getElementById("g3").innerHTML=b[3];
    document.getElementById("g4").innerHTML=b[4];
    document.getElementById("g5").innerHTML=b[5];
    document.getElementById("g6").innerHTML=b[6];
    document.getElementById("g7").innerHTML=b[7];*/

    for (let k = 0; k < b.length; k++) {
      if(b[k]=="S")
        c[k]=parseInt(10);
      else if(b[k]=="A")
        c[k]=parseInt(9);
      else if(b[k]=="B")
        c[k]=parseInt(8);
      else if(b[k]=="C")
        c[k]=parseInt(7);
      else if(b[k]=="D")
        c[k]=parseInt(6);
      else if(b[k]=="E")
        c[k]=parseInt(5);
      else if(b[k]=="F")
        c[k]=parseInt(0);

    }

    for (let i = 0; i < z.length; i++) {
        let p="gp";
        let q="noc";
        document.getElementById(p.concat(i)).innerHTML=c[i];
        d[i]=document.getElementById(q.concat(i)).innerHTML;
        
    }
    
    /*document.getElementById("gp0").innerHTML=c[0];
    document.getElementById("gp1").innerHTML=c[1];
    document.getElementById("gp2").innerHTML=c[2];
    document.getElementById("gp3").innerHTML=c[3];
    document.getElementById("gp4").innerHTML=c[4];
    document.getElementById("gp5").innerHTML=c[5];
    document.getElementById("gp6").innerHTML=c[6];
    document.getElementById("gp7").innerHTML=c[7];
    d[0] = document.getElementById("noc0").innerHTML;
    d[1] = document.getElementById("noc1").innerHTML;
    d[2] = document.getElementById("noc2").innerHTML;
    d[3] = document.getElementById("noc3").innerHTML;
    d[4] = document.getElementById("noc4").innerHTML;
    d[5] = document.getElementById("noc5").innerHTML;
    d[6] = document.getElementById("noc6").innerHTML;
    d[7] = document.getElementById("noc7").innerHTML;*/
    
    for (let index = 0; index < d.length; index++) {
      e[index]=d[index]*c[index];
    }

    for (let i = 0; i < e.length; i++) {
      f = f + e[i]; 
    }

    for (let i = 0; i < z.length; i++) {
        let p="cp";
        document.getElementById(p.concat(i)).innerHTML=e[i];
        
    }

    /*document.getElementById("cp0").innerHTML=e[0];
    document.getElementById("cp1").innerHTML=e[1];
    document.getElementById("cp2").innerHTML=e[2];
    document.getElementById("cp3").innerHTML=e[3];
    document.getElementById("cp4").innerHTML=e[4];
    document.getElementById("cp5").innerHTML=e[5];
    document.getElementById("cp6").innerHTML=e[6];
    document.getElementById("cp7").innerHTML=e[7];*/

    document.getElementById("totOfCol5").innerHTML=f;

    var per=0;
    var sgpa=0;
    
    per = parseFloat(a/c.length).toFixed(3);
    sgpa = parseFloat(f/document.getElementById("totOfCol-1").innerHTML).toFixed(3);

    document.getElementById("per").innerHTML=per;
    document.getElementById("sgpa").innerHTML=sgpa;

  }

</script>

</html>
