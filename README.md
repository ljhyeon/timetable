# timetable
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>시간표</title>
    <style>     
        a {
            text-decoration: none;
        } 

        a:link {
          color : #DCE2F0;
        }
        a:visited {
          color : #DCE2F0;
        }


        table{
            border: 2px solid #d2d2d2;
            border-collapse: collapse;
            font-size: 0.9em;
            margin: auto;
            text-align: center;
        }

        th, td{
            border: 1px solid #d2d2d2;
            border-collapse: collapse;
        }

        th{
            height: 5px;
        }

        td {
            width: 75px;
            height: 20px;
        }
        #title{
            font-size: 2rem;
            text-align: center; /*텍스트를 중간으로*/
            margin:10px;
        }

        #sub{
            color: #DCE2F0;
            text-align: center;
            
        }
        #time{
            color: black;
        }

        #EngineeringMathematics{
            background-color:	#50586C;
            
        }

        #JAVA{
            background-color:	#50586C;
        }

        #logic{
            background-color:#50586C;
        }

        #auto{
            background-color:#50586C;
        }
        #human{
            background-color:#50586C;
        }
        #structure{
            background-color: #50586C;
        }
        #structure2{
            background-color: #50586C;
        }
        #future{
            background-color: #50586C;
        }
        #room{
            font-size: 0.1rem;
        }
    </style>
</head>

<body>
<table width=400 height="400" style="color: #121212">
<h1 id="title">▶   2학년 1학기  ◀</h1>

<div>
  <tr width=19%>
    <th></th>
    <th>월</th>
    <th>화</th>
    <th>수</th>
    <th>목</th>
    <th>금</th>
  </tr>
  <tbody id="sub">
  <tr>
    <th rowspan="2" id="time">9</th>
    <td></td>
    <td rowspan="8" id="JAVA"><a href="https://lms.knu.ac.kr/ilos/main/main_form.acl">자바프로그래밍</a>
        <div id="room">IT융복합관-224</div>
    </td>
    <td rowspan="3" id="EngineeringMathematics"><a href="https://lms.knu.ac.kr/ilos/main/main_form.acl">공학수학1</a>
        <div id="room">IT융복합관-351</div>
    </td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    
    
    <td></td>
    <td></td>
  </tr>
  <tr>
    <th rowspan="2" id="time">10</th>
    <td></td>
    
    
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="3" id="EngineeringMathematics"><a href="https://lms.knu.ac.kr/ilos/main/main_form.acl">공학수학1</a>
        <div id="room">IT융복합관-351</div>
    </td>
    
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <th rowspan="2" id="time">11</th>
    

    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    

    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <th rowspan="2" id="time">12</th>
    <td></td>
    
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <th rowspan="2" id="time">1</th>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="3"id="structure">자료구조
        <div id="room">IT융복합관-351</div>
    </td>
    <td rowspan="3"id="logic"><a href="https://knu.webex.com/meet/sklee" target="_blank">논리회로</a>
        <div id="room">IT4호관-104</div>
    </td>
    <td rowspan="3"id="structure">자료구조
        <div id="room">IT융복합관-351</div>
    </td>
    <td rowspan="3"id="logic"><a href="https://knu.webex.com/meet/sklee">논리회로</a>
      <div id="room">IT4호관-104</div>
    </td>
    <td></td>
  </tr>
  <tr>
    <th rowspan="2" id="time">2</th>
  
    <td></td>
  </tr>
  <tr>
    
    <td></td>
  </tr>
  <tr>
    <th rowspan="2" id="time">3</th>
    <td rowspan="4"id="structure2">자료구조응용
        <div id="room">IT융복합관-355</div>
    </td>
    <td rowspan="3"id="auto"><a href="https://lms.knu.ac.kr/ilos/main/main_form.acl">오토마타 및 형식언어</a>
        <div id="room">IT4호관-104</div>
    </td>
    <td rowspan="4"id="structure2">자료구조응용
        <div id="room">IT융복합관-355</div>
    </td>
    <td rowspan="3"id="auto"><a href="https://lms.knu.ac.kr/ilos/main/main_form.acl">오토마타 및 형식언어</a>
        <div id="room">IT4호관-104</div>
    </td>
    <td></td>
  </tr>
  <tr>
 
    
    <td></td>
  </tr>
  <tr>
    <th rowspan="2" id="time">4</th>
 
    
    <td></td>
  </tr>
  <tr>
    
    <td rowspan="3"id="human"><a href="https://lms.knu.ac.kr/ilos/main/main_form.acl">인간과 언어</a>
        <div id="room">사회과학대학-352</div>
    </td>
    
    <td rowspan="3"id="human"><a href="https://lms.knu.ac.kr/ilos/main/main_form.acl">인간과 언어</a>
        <div id="room">사회과학대학-352</div>
    </td>
    <td></td>
  </tr>
  <tr>
    <th rowspan="2" id="time">5</th>
    <td></td>
    
    <td></td>
    
    <td  rowspan="6" id="future"><a href="https://lms.knu.ac.kr/ilos/main/main_form.acl">미래산업과 직업선택</a>
        <div id="room">사회과학대학-132</div>
    </td>
  </tr>
  <tr>
    <td></td>
    
    <td></td>
    
    
  </tr>
  <tr>
    <th rowspan="2" id="time">6</th>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    
  </tr>
  <tr>
    <th rowspan="2" id="time">7</th>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    
  </tr>
</tbody>
</table>

</body>
</html>
