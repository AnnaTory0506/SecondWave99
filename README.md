# SecondWave99
<html>
<head>
<meta http-equiv="Content-Script-Type" content="text/javascript">
<title>JavaScript</title>


<style>
   table 
    border-spacing: 1px;
}
   td, th 
{
    background: #800000;
    padding: 5px; 
}

  </style>

</head> 

<BODY style="background-color:EDE8A1;">

 <script type="text/javascript">
   n=prompt("введите начальный предел","");
   n=parseInt(n);
 </script>

 <script type="text/javascript">
   k=prompt("введите конечный предел","");
   k= parseInt(k);
 </script> 

<table class="tbl1"> 
 <tr>
        <th>F</th>
        <th>C</th>
    </tr>

<script type="text/javascript">

for(x=n;x<=k;x+=10){
for(i=k-n;i>=0;i--){
   if((i%2)==0){
      document.write("<style> td{background: #74a4a6;font-size:25px;} </style>");  
  }
   else {
        document.write("<style> td{background: #800000;font-size:25px;} </style>");
         }

      document.write("<tr><td>"+x+"</td><td>"+Math.round((5/9)*(x-32))+"</td></tr>");

}
}

</script>

</table>

</BODY> 

</html> 
