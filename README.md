<!-- Created By CodingNepal - www.codingnepalweb.com  -->
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale= 1.0">
    <title>mp police 2023 mock test | credit: codenepali</title>
    <meta http-equiv="Content-Type" content="text/html; " />
    <meta name="description" content="recently mp goverment release 7000+ vacency in mp police department ,syllabus, mocktest, mp police pyqs" />
    <meta name="keywords" content="mp police admit card,mp police constable exam date 2023,mp police vacancy 2023 official website, mp police mock test in hindi,MP Police Mock Test 2023 in Hindi" />
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/3.2.2/es5/tex-mml-chtml.min.js"></script>
    <script src="https://cdn.examgoal.net/room-examgoal-com/v2.7/mathjax.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/3.2.2/es5/input/asciimath.js"></script>
    <!-- FontAweome CDN Link for Icons-->
  <!--  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"/>
-->
<style type="text/css">
/* importing google fonts */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700&display=swap');
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
    
}

body{
    background: green;
}

::selection{
    color: #fff;
    background: #007bff;
}

.start_btn,
.info_box,
.quiz_box,
.result_box{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 
                0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

.info_box.activeInfo,
.quiz_box.activeQuiz,
.result_box.activeResult{
    opacity: 1;
    z-index: 5;
    pointer-events: auto;
    transform: translate(-50%, -50%) scale(1);
}

.start_btn button{
    font-size: 25px;
    font-weight: 500;
    color: #007bff;
    padding: 15px 30px;
    outline: none;
    border: none;
    border-radius: 5px;
    background: #fff;
    cursor: pointer;
}

.info_box{
    width: 400px;
    background: #fff;
    border-radius: 5px;
    margin-top: 30vh;
    opacity: 0;
    pointer-events: none;
    transition: all 0.3s ease;
}

.info_box .info-title{
    height: 60px;
    width: 100%;
    border-bottom: 1px solid lightgrey;
    display: flex;
    align-items: center;
    padding: 0 30px;
    border-radius: 5px 5px 0 0;
    font-size: 20px;
    font-weight: 600;
}

.info_box .info-list{
    padding: 15px 30px;
}

.info_box .info-list .info{
    margin: 5px 0;
    font-size: 17px;
}

.info_box .info-list .info span{
    font-weight: 600;
    color: #007bff;
}
.info_box .buttons{
    height: 60px;
    display: flex;
    align-items: center;
    justify-content: flex-end;
    padding: 0 30px;
    border-top: 1px solid lightgrey;
}

.info_box .buttons button{
    margin: 0 5px;
    height: 40px;
    width: 100px;
    font-size: 16px;
    font-weight: 500;
    cursor: pointer;
    border: none;
    outline: none;
    border-radius: 5px;
    border: 1px solid #007bff;
    transition: all 0.3s ease;
}

.quiz_box{
    width: 400px;
    background: #fff;
    margin-top: 30vh;
    border-radius: 5px;
transform: translate(-50%, -50%) scale(0.9);
    opacity: 0;
    pointer-events: none;
    transition: all 0.3s ease;
    overflow: hidden;
   
   
    
}

.quiz_box header{
    position: relative;
    z-index: 2;
    height: 70px;
    padding: 0 30px;
    background: #fff;
    border-radius: 5px 5px 0 0;
    display: flex;
    align-items: center;
    justify-content: space-between;
    box-shadow: 0px 3px 5px 1px rgba(0,0,0,0.1);
}

.quiz_box header .title{
    font-size: 20px;
    font-weight: 600;
    text-shadow: 2px 2px 1.6px #d7d9d7;
}

.quiz_box header .timer{
    color: #004085;
    background: #cce5ff;
    border: 1px solid #b8daff;
    height: 45px;
    padding: 0 8px;
    border-radius: 5px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 145px;
}

.quiz_box header .timer .time_left_txt{
    font-weight: 400;
    font-size: 17px;
    user-select: none;
}

.quiz_box header .timer .timer_sec{
    font-size: 18px;
    font-weight: 500;
    height: 30px;
    width: 45px;
    color: #fff;
    border-radius: 5px;
    line-height: 30px;
    text-align: center;
    background-image: linear-gradient(to right, #681be3, #9a1be3) ;
    border: 1px solid #343a40;
    user-select: none;
}

.quiz_box header .time_line{
    position: absolute;
    bottom: 0px;
    left: 0px;
    height: 5px;
    background-color: #48e81c;
 
}




section{
    padding: 25px 30px 20px 30px;
    background: #fff;
}

section .que_text{
    font-size: 13px;
    font-weight: 600;
}

section .option_list{
    padding: 20px 0px;
    display: block;   
}

section .option_list .option{
    background: aliceblue;
    border: 1px solid #84c5fe;
    border-radius: 5px;
    padding: 8px 15px;
    font-size: 17px;
    margin-bottom: 15px;
    cursor: pointer;
    transition: all 0.3s ease;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

section .option_list .option:last-child{
    margin-bottom: 0px;
}

section .option_list .option:hover{
    color: #004085;
    background: #5bafeb;
    border: 1px solid black;
}

section .option_list .option.correct{
    color: black;
    background: #5fc76f;
    border: 2px solid black;
}

section .option_list .option.incorrect{
    color: white;
    background: #db4848;
    border: 2px solid black;
}

section .option_list .option.disabled{
    pointer-events: none;
}

section .option_list .option .icon{
    height: 26px;
    width: 26px;
    border: 2px solid transparent;
    border-radius: 50%;
    text-align: center;
    font-size: 13px;
    pointer-events: none;
    transition: all 0.3s ease;
    line-height: 24px;
}
.option_list .option .icon.tick{
    color: #23903c;
    border-color: #23903c;
    background: #d4edda;
}

.option_list .option .icon.cross{
    color: #a42834;
    background: #f8d7da;
    border-color: #a42834;
}

footer{
    height: 60px;
    padding: 0 30px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    border-top: 1px solid lightgrey;
}

footer .total_que span{
    display: flex;
    user-select: none;
}

footer .total_que span p{
    font-weight: 500;
    padding: 0 5px;
}

footer .total_que span p:first-child{
    padding-left: 0px;
}

footer button{
    height: 40px;
    padding: 0 13px;
    font-size: 18px;
    font-weight: 400;
    cursor: pointer;
    border: none;
    outline: none;
    color: #fff;
    border-radius: 5px;
    background: #007bff;
    border: 1px solid #007bff;
    line-height: 10px;
    opacity: 0;
    pointer-events: none;
    transform: scale(0.95);
    transition: all 0.3s ease;
}

footer button:hover{
    background: #0263ca;
}

footer button.show{
    opacity: 1;
    pointer-events: auto;
    transform: scale(1);
}

.result_box{
    background: #fff;
    border-radius: 5px;
    display: flex;
    padding: 25px 30px;
    width: 450px;
    align-items: center;
    flex-direction: column;
    justify-content: center;
    transform: translate(-50%, -50%) scale(1.0);
    opacity: 0;
    pointer-events: none;
    transition: all 0.3s ease;
}

.result_box .icon{
    font-size: 100px;
    color: #007bff;
    margin-bottom: 10px;
}

.result_box .complete_text{
    font-size: 20px;
    font-weight: 500;
}

.result_box .score_text span{
    display: flex;
    margin: 10px 0;
    font-size: 18px;
    font-weight: 500;
}

.result_box .score_text span p{
    padding: 0 4px;
    font-weight: 600;
}

.result_box .buttons{
    display: flex;
    margin: 20px 0;
}

.result_box .buttons button{
    margin: 0 10px;
    height: 45px;
    padding: 0 20px;
    font-size: 18px;
    font-weight: 500;
    cursor: pointer;
    border: none;
    outline: none;
    border-radius: 5px;
    border: 1px solid #007bff;
    transition: all 0.3s ease;
}

.buttons button.restart{
    color: #fff;
    background: #007bff;
}

.buttons button.restart:hover{
    background: #0263ca;
}

.buttons button.quit{
    color: #007bff;
    background: #fff;
}

.buttons button.quit:hover{
    color: #fff;
    background: #007bff;
}


.sol_img{
width:100%;
height: auto;
box-shadow: 1px 2px 3px 3px #b7b6b8;
padding: 5px;
border-radius: 5px;
border: 1px solid black;
}

.sol_btn{
width: 130px;
height: 40px;
margin-top: 10px;
background-image: linear-gradient(to right, #138a76, #14b341);
color: white;
font-weight: bold;
border-radius: 8px;
padding: 1px;
margin-left: 30px;
text-shadow: 2px 1px 2px #c9c9c9;
font-size: 23px;
}
.sol_btn:hover{
width: 130px;
height: 40px;
margin-top: 10px;
background-color: white;
color: white;
font-weight: bold;
border-radius: 5px;
padding: 1px;
margin-left: 30px;
text-shadow: 2px 1px 2px black;
font-size: 23px;
}

.back_btn{

width: 130px;
height: 40px;
text-shadow: 2px 1px 2px #c9c9c9;
margin-top: 10px;
background-image: linear-gradient(to right, #16a0db, #1278a3);
color: white;
font-weight: bold;
border-radius: 8px;
padding: 1px;
font-size: 23px;


}
.back_btn:hover{

width: 130px;
height: 40px;
text-shadow: 2px 1px 2px black;
margin-top: 10px;
background-color: white;
color: white;
font-weight: bold;
border-radius: 5px;
border: 2px solid blue;
padding: 1px;
font-size: 23px;


}

body .chap_name_txt{
width: 370px;
height: 50px;
background-color: white;
text-shadow: 2px 2px 2px black;
color: #6f2fd6; 
padding: 5px;
font-weight: bold;
border-radius: 5px;
display: none;
text-align: center;
margin-top: 200px;
margin-left: 80px;
margin-bottom: 70px;
}

body div div .que_menu{
display: block;
width: 400px;
height: 50px ;
}
body div div div .que_menu1{
width: 400px;
height: 50px ;
border: 1px solid black;
border-radius: 2px;
overflow: auto;
position: fixed;
display: flex;
padding: 5px;
box-shadow: 2px 2px 2px 2px #d6d4fa ;

}
body div div div .que_menu_number{
width: 40px;
height: 40px;
text-decoration: none;
font-size: 30px;
text-shadow: 2px 1.5px 1.9px #6f6bf2;
background-color: none;
border: 1px solid white;
box-shadow: 1px 1px 1px 1px black;
border-radius:50%;
margin-left: 30px;
}

</style>






</head>
<body>
    <!-- start Quiz button -->

 <!--   <div class="start_btn"><button>Start Test</button><div class="header-ad-unit">
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-6738179060246081"
    crossorigin="anonymous"></script>
    <ins class="adsbygoogle"
    style="display:block"
    data-ad-format="fluid"
    data-ad-layout-key="-gw-3+1f-3d+2z"
    data-ad-client="ca-pub-6738179060246081"
    data-ad-slot="6850459124"></ins>
    <script>
    (adsbygoogle = window.adsbygoogle || []).push({});
    </script>
    
    </div></div>-->

      <br>
      <br>

    <!-- Info Box -->
    <div class="info_box">
    <div class="header-ad-unit">
    
    
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-6738179060246081"
    crossorigin="anonymous"></script>
    <ins class="adsbygoogle"
    style="display:block"
    data-ad-format="fluid"
    data-ad-layout-key="-gw-3+1f-3d+2z"
    data-ad-client="ca-pub-6738179060246081"
    data-ad-slot="6850459124"></ins>
    <script>
    (adsbygoogle = window.adsbygoogle || []).push({});
    </script>
    
    </div>
    
    
        <div class="info-title"><span>ध्यान दें:</span></div>
        <div class="info-list">
            <div class="info">1. आपके पास प्रत्येक प्रश्न के लिए केवल <span> 1 Minute</span> है.</div>
            <div class="info">2. किसी भी क्वेश्चन का आंसर करने के लिए आपके पास केवल एक मौका है</div>
            <div class="info">3. समय समाप्त होने के बाद आप किसी भी क्वेश्चन को आंसर नहीं कर पाएंगे</div>
            <div class="info">4. एक बार Test Start होने के बाद आप बीच में नहीं छोड़ सकते।</div>
            <div class="info">5. आपके सही उत्तरों के आधार पर हर एक सही उत्तर का 1 पॉइंट मिलेगा</div>
        </div>
        <div class="buttons">
            <button class="quit">Exit Test</button>
            <button class="restart">Continue</button>
        </div>
    </div>

    <!-- Quiz Box -->
    <div class="quiz_box">
      <div class="header-ad-unit">
         <div class="que_menu">
         <div class="que_menu1">
         <h3 style=" font-size: 15px;color:black;">Questions:<br>no. </h3>
         <a class="que_menu_number" onclick="Q1()" href="#" >01</a>
         <a class="que_menu_number" onclick="Q2()" href="#" >02</a>
         <a class="que_menu_number" onclick="Q3()" href="#" >03</a>
         <a class="que_menu_number" onclick="Q4()" href="#" >04</a>
         <a class="que_menu_number" onclick="Q5()" href="#" >05</a>
         <a class="que_menu_number" onclick="Q6()" href="#" >06</a>
         <a class="que_menu_number" onclick="Q7()" href="#" >07</a>
         <a class="que_menu_number" onclick="Q8()" href="#" >08</a>
         <a class="que_menu_number" onclick="Q9()" href="#" >09</a>
         <a class="que_menu_number" onclick="Q10()" href="#" >10</a>
         </div>
         </div>
      
      
         <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-6738179060246081"
         crossorigin="anonymous"></script>
         <ins class="adsbygoogle"
         style="display:block"
         data-ad-format="fluid"
         data-ad-layout-key="-gw-3+1f-3d+2z"
         data-ad-client="ca-pub-6738179060246081"
         data-ad-slot="6850459124"></ins>
         <script>
         (adsbygoogle = window.adsbygoogle || []).push({});
         </script>
    
      
      </div>
      <br>
      
        <header>
            <div class="title">MP POLICE MOCK TEST 2023 </div>
            <div class="timer">
                <div class="time_left_txt">Time Left</div>
                <div class="timer_sec">60</div>
            </div>
            <div class="time_line"></div>
        </header>
        <section>
            <div class="que_text">
                <!-- Here I've inserted question from JavaScript -->
            </div>
            <div class="option_list">
                <!-- Here I've inserted options from JavaScript -->
            </div>
            <div class="solution"> <div style="display:none;" class="sol_img"> </div></div>
          <div style="display: flex;">
             <button style="display: block;" class="back_btn">Back</button>
             
             <button style="display:none;" onclick="showImage()" class="sol_btn"><b> Solution</b></button>
                </div>
        </section>

        <!-- footer of Quiz Box -->
        <footer>
            <div class="total_que">
                <!-- Here I've inserted Question Count Number from JavaScript -->
            </div>
            <button class="next_btn">Skip</button>
        </footer>
    </div>

    <!-- Result Box -->
    <div class="result_box">
        <div class="icon">
            <i class="fas fa-crown"></i>
        </div>
        <div class="complete_text">You've completed the Quiz!</div>
        <div class="score_text">
            <!-- Here I've inserted Score Result from JavaScript -->
        </div>
        <div class="score_textN">
        <!-- Here I've inserted Score Result from JavaScript -->
        </div>
        <div class="skipQue_count">
        <!-- Here I've inserted Score Result from JavaScript -->
        </div>
        
        <div class="buttons">
            <button class="restart">Replay Quiz</button>
            <button class="quit">Quit Quiz</button>
        </div>
    </div>
    
<script >

function showImage() {
  a = document.querySelector(".sol_img");
a.style.display = "block";
}

function showQueNo() {

 showSeries  = document.querySelector(".que_menu");
showSeries.style.display = "block";
}

</script>

   <!--Inside this JavaScript file I've inserted Questions and Options only-->
    
    <script>
    // creating an array and passing the number, questions, options, and answers
    let questions = [
    {
    numb: 1,
    question: "एक दुधवाला शुद्ध दुध के पात्र में से 20% दुध को पानी से बदल देता है और वह एक बार फिर ऐसा करता है। मिश्रण में दुध और पानी का अंतिम अनुपात ज्ञात कीजिये?<br> <span style='color: white; background-color: #15b345; margin-left: 130px; font-size: 12px; padding: 2px; border-radius: 3px;'>mp police 2 Feb 2022 shift-1</span>",
    answer: "a.9:16",
    options: [
    "9:16",
    "6:5",
    "1:6",
    "4:5"
    ],
    solution: "माना उसके पास 100 लीटर दूध है<br> 100 का 20% = 20ली.  <br>उसने पानी से बदल दिया अब 80 लीटर बचा। <br>80 ली. का 20% = 16ली. और पानी मिला दिया<br>  पानी की कुल मात्रा : 36ली.<br> दूध की बची मात्रा : 100-36= 64ली.<br>दूध : पानी = 64:36 = 16:9 "
    },
    
    
    
    
    {
    numb: 2,
    question: "यदि <math xmlns='http://www.w3.org/1998/Math/MathML' display='block'>  <mfrac>    <mrow>      <mn>4</mn>      <mi>a</mi>      <mo>+</mo>      <mn>2</mn>      <mi>b</mi>    </mrow>    <mrow>      <mn>4</mn>      <mi>a</mi>      <mo>&#x2212;</mo>      <mn>3</mn>      <mi>b</mi>    </mrow>  </mfrac>  <mo>=</mo>  <mn>6</mn></math><br> है, तो a:b का मान निम्न में से क्या होगा?<br><span style='color: white; background-color: #15b345; margin-left: 130px; font-size: 12px; padding: 2px; border-radius: 3px;'>mp police 1 Feb 2022 shift-1</span>",
     answer: "a.7:10",
    options: [
    "7:10",
    "3:4",
    "7:8",
    "14:10"
    ],
    solution: "10a = 7b"
    },
    {
    numb: 3,
    question: "निन्नलिखित संख्या-श्रृंखला में प्रश्रचिन्हृ ? के स्थान पर क्या आना चाहिए? <br>68.01% का 1391+37% का 1199.93 - 73% का 3893 =? <br> <span style='color: white; background-color: #15b345; margin-left: 130px; font-size: 12px; padding: 2px; border-radius: 3px;'>mp police 1 Feb 2022 shift-1</span>",
    answer: "d.4243",
    options: [
    "3155",
    "2150",
    "2862",
    "4243"
    ],
    solution: "4243"
    },
   
    {
    numb: 4,
    question: "सरल कीजिए: 60-34+21÷3 <br> <span style='color: white; background-color: #15b345; margin-left: 130px; font-size: 12px; padding: 2px; border-radius: 3px;'>mp police 1 Feb 2022 shift-1</span>",
    answer: "c.33",
    options: [
    "40",
    "54",
    "33",
    "67"
    ],
    solution: "BADMAS rule <br> B → bracket (कोष्टक)<br> D → division (भाग)<br> M→ multiple (गुणा)<br> A →  Addition (जोड़)<br> S → subtraction (घटाना) ",
    },
    {
    numb: 5,
    question: "90 छात्रों की एक कक्षा में, 35 लड़कियों का औसत वजन 40 किलोग्राम है और शेष छात्रों का औसत वजन 45 किलोग्राम है। सभी 90 छात्रों का लगभग औसत वजन (किलो में) क्या होगा?<br> <span style='color: white; background-color: #15b345; margin-left: 130px; font-size: 12px; padding: 2px; border-radius: 3px;'>mp police 1 Feb 2022 shift-2</span>",
    answer: "a.43.05 kg",
    options: [
    "43.05 kg",
    "32.3 kg",
    "35.5 kg",
    " 40.2 kg"
    ],
    solution: '<math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mfrac><mrow><mn>35</mn><mi>×</mi><mn>40</mn><mo>+</mo><mn>55</mn><mi>×</mi><mn>45</mn></mrow><mn>90</mn></mfrac><mo>=</mo><mfrac><mn>3875</mn><mn>90</mn></mfrac><mo>=</mo><mn>43.05</mn><mi>k</mi><mi>g</mi></math>',
    },
    {
    numb: 6,
    question: "निन्नलिखित संख्या-श्रंखला में प्रश्रचिन्ह (? ) के स्थान पर क्या आना चाहिए? <br>1/27 का 3375 + 44%  का 2775 = ? <br> <span style='color: white; background-color: #15b345; margin-left: 130px; font-size: 12px; padding: 2px; border-radius: 3px;'>mp police 2 Feb 2022 shift-1</span>",
    answer: "a.1346",
    options: [
    "1346",
    "1575",
    "1329",
    "1420"
    ],
    solution: 'coming soon!!',
    },
    {
    numb: 7,
    question: 'निन्नलिखित संख्या-श्रंखला में प्रश्रचिन्ह (? ) के स्थान पर क्या आना चाहिए? <math xmlns="http://www.w3.org/1998/Math/MathML" display="block">   <msqrt>     <mn>1090</mn>   </msqrt>   <mo>+</mo>   <mo stretchy="false">(</mo>   <mn>8</mn>   <mn>.04</mn>   <mi>&#xD7;</mi>   <mn>24</mn>   <mo stretchy="false">)</mo>   <mo>+</mo>   <mo stretchy="false">(</mo>   <mn>19</mn>   <mn>.10</mn>   <msup>     <mo stretchy="false">)</mo>     <mrow data-mjx-texclass="ORD">       <mn>2</mn>     </mrow>   </msup>   <mo>=</mo>   <mo>?</mo> </math> <br> <span style="color: white; background-color: #15b345; margin-left: 130px; font-size: 12px; padding: 2px; border-radius: 3px;">mp police 1 Feb 2022 shift 2</span>',
    answer: "b.586",
    options: [
    "324",
    "586",
    "325",
    "987"
    ],
    solution: 'digital sum ',
    },
    {
    numb: 8,
    question: "दो बर्तन A और B हैं । बर्तन A में 95 लीटर शुद्ध दूध है और बर्तन B में 75 लीटर शुद्ध पानी है। बर्तन A से, 5L दूध निकाला जाता है और बर्तन B में डाला जाता है। फिर, बर्तन B से 10L मिश्रण (दूध और पानी) निकाला जाता है और बर्तन A में डाला जाता है। बर्तन A में दूध की मात्रा का अनुपात क्या है?बर्तन B में शुद्ध पानी की मात्रा?<br> <span style='color: white; background-color: #15b345; margin-left: 80px; font-size: 12px; padding: 2px; border-radius: 3px;'>mp police 3Feb 2022 morning shift</span> ",
    answer: "c.29:27",
    options: [
    "33:29",
    "12:17",
    "29:27",
    "5:21"
    ],
    solution: '',
    },
    {
    numb: 9,
    question: 'सरल कीजिए:<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">   <mfrac>     <mn>86</mn>     <mn>17</mn>   </mfrac>   <mo>&#x2212;</mo>   <mo stretchy="false">[</mo>   <mfrac>     <mn>4</mn>     <mn>9</mn>   </mfrac>   <mo>+</mo>   <mo stretchy="false">(</mo>   <mfrac>     <mn>8</mn>     <mn>24</mn>   </mfrac>   <mi>&#xF7;</mi>   <mfrac>     <mn>8</mn>     <mn>48</mn>   </mfrac>   <mo stretchy="false">)</mo>   <mo stretchy="false">]</mo> </math> <br> <span style="color: white; background-color: #15b345; margin-left: 130px; font-size: 12px; padding: 2px; border-radius: 3px;">mp police 6 Feb 2022 shift-1</span>',
    answer: 'b.400/153',
    options: [
    '<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">   <mfrac>     <mn>-356</mn>     <mn>153</mn>   </mfrac> </math>',
    '400/153',
    '<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">   <mfrac>     <mn>432</mn>     <mn>153</mn>   </mfrac> </math>',
    '<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">   <mfrac>     <mn>-400</mn>     <mn>153</mn>   </mfrac> </math>'
    ],
    solution: 'simple calculation <br> try you can',
    },
    {
    numb: 10,
    question: "25 व्यक्ति पार्टी के लिए एक होटल गए। उनमें से 15 ने प्रत्येक ने अपने रात के खाने पर 100 रुपये खर्च किए और शेष ने सभी 25 के औसत खर्च से 5 रुपये अधिक खर्च किए। उनके द्वारा खर्च किएगए कुल रूपये कितने थे? <br> <span style='color: white; background-color: #15b345; margin-left: 130px; font-size: 12px; padding: 2px; border-radius: 3px;'>mp police 2017 Exam(online)</span>",
    answer: "c.2583.25",
    options: [
    "2053",
    "4350",
    "2583.25",
    "2500.8"
    ],
    solution: 'coming soon!!',
    },
   
    
    // you can uncomment the below codes and make duplicate as more as you want to add question
    // but remember you need to give the numb value serialize like 1,2,3,5,6,7,8,9.....
    
    //   {
    //   numb: 6,
    //   question: "Your Question is Here",
    //   answer: "Correct answer of the question is here",
    //   options: [
    //     "Option 1",
    //     "option 2",
    //     "option 3",
    //     "option 4"
    //   ]
    // },
    ];
    
  </script>
    
 <script>

    // Inside this JavaScript file I've coded all Quiz Codes 
  
    //selecting all required elements
    const start_btn = document.querySelector(".start_btn button");
    const info_box = document.querySelector(".info_box");
    const exit_btn = info_box.querySelector(".buttons .quit");
    const continue_btn = info_box.querySelector(".buttons .restart");
    const quiz_box = document.querySelector(".quiz_box");
    const result_box = document.querySelector(".result_box");
    const option_list = document.querySelector(".option_list");
    const time_line = document.querySelector("header .time_line");
    const timeText = document.querySelector(".timer .time_left_txt");
    const timeCount = document.querySelector(".timer .timer_sec");
    
    const chap_name_txt = document.querySelector(".chap_name_txt");
        // if startQuiz button clicked""
    onload = ()=>{
    info_box.classList.add("activeInfo"); //show info box
    chap_name_txt.style.display = "block";
    }
    
    // if exitQuiz button clicked
    exit_btn.onclick = ()=>{
    info_box.classList.remove("activeInfo"); //hide info box
    }
    
    // if continueQuiz button clicked
    continue_btn.onclick = ()=>{
    info_box.classList.remove("activeInfo"); //hide info box
    quiz_box.classList.add("activeQuiz"); //show quiz box
    next_btn.classList.add("show");
    showQuetions(0); //calling showQestions function
    queCounter(1); //passing 1 parameter to queCounter
    startTimer(60); //calling startTimer function
    startTimerLine(0); //calling startTimerLine function
    chap_name_txt.style.display = "none";
    
    
    }
    
    let timeValue =  60;
    let que_count = 0;
    let que_numb = 1;
    let userScore = 0;
    let negativeScore = 0;
    let counter;
    let counterLine;
    let widthValue = 0;
    let skipQue = 0;
    const restart_quiz = result_box.querySelector(".buttons .restart");
    const quit_quiz = result_box.querySelector(".buttons .quit");
    
    // if restartQuiz button clicked
    restart_quiz.onclick = ()=>{
    quiz_box.classList.add("activeQuiz"); //show quiz box
    result_box.classList.remove("activeResult"); //hide result box
    timeValue = 60; 
    que_count = 0;
    que_numb = 1;
    userScore = 0;
    negativeScore = 0;
    skipQue = 0;
    widthValue = 0;
    showQuetions(que_count); //calling showQestions function
    queCounter(que_numb); //passing que_numb value to queCounter
    clearInterval(counter); //clear counter
    clearInterval(counterLine); //clear counterLine
    startTimer(timeValue); //calling startTimer function
    startTimerLine(widthValue); //calling startTimerLine function
    timeText.textContent = "Time Left"; //change the text of timeText to Time Left
   // next_btn.classList.remove("show"); //hide the next button
    }
    
    // if quitQuiz button clicked
    quit_quiz.onclick = ()=>{
    window.location.reload(); //reload the current window
    }
    
    const sol_btn = document.querySelector("section .sol_btn");
    const next_btn = document.querySelector("footer .next_btn");
    const bottom_ques_counter = document.querySelector("footer .total_que");
    
    // if Next Que button clicked
    next_btn.onclick = ()=>{
    if(que_count < questions.length - 1){ //if question count is less than total question length
    que_count++; //increment the que_count value
    que_numb++; //increment the que_numb value
    showQuetions(que_count); //calling showQestions function
    queCounter(que_numb); //passing que_numb value to queCounter
    clearInterval(counter); //clear counter
    clearInterval(counterLine); //clear counterLine
    startTimer(timeValue); //calling startTimer function
    startTimerLine(widthValue); //calling startTimerLine function
    timeText.textContent = "Time Left"; //change the timeText to Time Left
    //next_btn.classList.remove("show"); //hide the next button
    sol_btn.style.display = "none";
    a.style.display = "none";
    back_btn.style.display = "block";
    timeText.style.color = "black";
    time_line.style.background = "#48e81c";
    
    }else{
    back_btn.style.display = "block";
    clearInterval(counter); //clear counter
    clearInterval(counterLine); //clear counterLine
    showResult(); //calling showResult function
    }
  
    }
    
    
    const back_btn = document.querySelector("section .back_btn");
    // if previous Que button clicked
    back_btn.onclick = ()=>{
    if(que_count >  0){ //if question count is less than total question length
    que_count--; //increment the que_count value
    que_numb--; //increment the que_numb value
    showQuetions(que_count); //calling showQestions function
    queCounter(que_numb); //passing que_numb value to queCounter
     clearInterval(counter); //clear counter
     clearInterval(counterLine);//clear counter
     
    back_btn.style.display = "block";
    sol_btn.style.display = "none";
    a.style.display = "none";
    timeText.style.color = "black";
    time_line.style.background = "#48e81c";
    }
    else{
    back_btn.style.display = "block";
    }
    }
    
   
    
    
    
    
    
    // getting questions and options from array
    function showQuetions(index){
    const que_text = document.querySelector(".que_text");
    
    let solutionImage = document.querySelector(".solution .sol_img");
    
    let sol_tag = questions[index].solution;
    solutionImage.innerHTML = sol_tag;
    
    //creating a new span and div tag for question and option and passing the value using array index
    let que_tag = '<span>'+ questions[index].numb + ". " + questions[index].question +'</span>';
    let option_tag = '<div class="option"><a  style="margin-bottom: 0px; align-item: center;font-size:20px; justify-content: center; width:30px;height:30px;border-radius:50%;">a.</a><span>'+ questions[index].options[0] +'</span></div>'
    + '<div  class="option"><a  style=" margin-bottom: 0px; align-item: center;font-size:20px; justify-content: center; width:30px;height:30px;">b.</a><span>'+ questions[index].options[1] +'</span></div>'
    + '<div class="option"><a  style="margin-bottom: 0px; align-item: center;font-size:20px; justify-content: center; width:30px;height:30px;border-radius:50%; ">c.</a><span>'+ questions[index].options[2] +'</span></div>'
    + '<div class="option"><a  style="margin-bottom: 0px; align-item: center;font-size:20px; justify-content: center; width:30px;height:30px;border-radius:50%; ">d.</a><span>'+ questions[index].options[3] +'</span></div>';
    que_text.innerHTML = que_tag; //adding new span tag inside que_tag
    option_list.innerHTML = option_tag; //adding new div tag inside option_tag
    
    const option = option_list.querySelectorAll(".option");
    
    // set onclick attribute to all available options
    for(i=0; i < option.length; i++){
    option[i].setAttribute("onclick", "optionSelected(this)");
    }
    }
    // creating the new div tags which for icons
    let tickIconTag = '<div class="icon tick"><i class="fas fa-check"></i></div>';
    let crossIconTag = '<div class="icon cross"><i class="fas fa-times"></i></div>';
    
    //if user clicked on option
    function optionSelected(answer){
    clearInterval(counter); //clear counter
    clearInterval(counterLine); //clear counterLine
    let userAns = answer.textContent; //getting user selected option
    let correcAns = questions[que_count].answer; //getting correct answer from array
    const allOptions = option_list.children.length; //getting all option items
    
    if(userAns == correcAns){ //if user selected option is equal to array's correct answer
    userScore += 1; //upgrading score value with 1
    answer.classList.add("correct"); //adding green color to correct selected option
    answer.insertAdjacentHTML("beforeend", tickIconTag); //adding tick icon to correct selected option
    console.log("Correct Answer");
    console.log("Your correct answers = " + userScore);
    sol_btn.style.display = "block";
    back_btn.style.display = "block";
    }
    else if(userAns !== correcAns){
    negativeScore += 1;
    back_btn.style.display = "block";
    sol_btn.style.display = "block";
    answer.classList.add("incorrect"); //adding red color to correct selected option
    answer.insertAdjacentHTML("beforeend", crossIconTag); //adding cross icon to correct selected option
    console.log("Wrong Answer");
    
    
    for(i=0; i < allOptions; i++){
    if(option_list.children[i].textContent == correcAns){ //if there is an option which is matched to an array answer 
    option_list.children[i].setAttribute("class", "option correct"); //adding green color to matched option
    option_list.children[i].insertAdjacentHTML("beforeend", tickIconTag); //adding tick icon to matched option
    console.log("Auto selected correct answer.");
    }
    }
    }
    for(i=0; i < allOptions; i++){
    option_list.children[i].classList.add("disabled"); //once user select an option then disabled all options
    }
    next_btn.classList.add("show"); //show the next button if user selected any option
    }
    
    
    function showResult(){
    info_box.classList.remove("activeInfo"); //hide info box
    quiz_box.classList.remove("activeQuiz"); //hide quiz box
    result_box.classList.add("activeResult"); //show result box
    const scoreText = result_box.querySelector(".score_text");
    const scoreTextN = result_box.querySelector(".score_textN");  
    const skip_que = result_box.querySelector(".skipQue_count");
    
/**   if (userScore > 3){ // if user scored more than 3
    //creating a new span tag and passing the user score number and total question number
    let scoreTag = '<span>and congrats! 🎉, You got <p>'+ userScore +'</p> out of <p>'+ questions.length +'</p></span>';
    scoreText.innerHTML = scoreTag;  //adding new span tag inside score_Text
    }
    else if(userScore > 1){ // if user scored more than 1
    let scoreTag = '<span>and nice 😎, You got <p>'+ userScore +'</p> out of <p>'+ questions.length +'</p></span>';
    scoreText.innerHTML = scoreTag;
    }
    else{ // if user scored less than 1
    let scoreTag = '<span>and sorry 😐, You got only <p>'+ userScore  +" out of"  + questions.length +'</p></span>';
    scoreText.innerHTML = scoreTag;
    }**/
    scoreText.innerHTML = "correct : " + userScore;
    scoreTextN.innerHTML = "wrong : " + negativeScore;
  const  skip_que_txt =  (que_count+1) - (userScore + negativeScore);
    skip_que.innerHTML = "skip : " + skip_que_txt;
 
    
    
    }
    
    function startTimer(time){
    counter = setInterval(timer, 1000);
    function timer(){
    timeCount.textContent = time; //changing the value of timeCount with time value
    time--; //decrement the time value
    if(time < 9){ //if timer is less than 9
    let addZero = timeCount.textContent; 
    timeCount.textContent = "0" + addZero; //add a 0 before time value
 
    time_line.style.background = "red";
    }
    if(time < 0){ //if timer is less than 0
    clearInterval(counter); //clear counter
    timeText.textContent = "Time Off"; //change the time text to time off
    const allOptions = option_list.children.length; //getting all option items
    let correcAns = questions[que_count].answer; //getting correct answer from array
    sol_btn.style.display = "block";
    for(i=0; i < allOptions; i++){
    if(option_list.children[i].textContent == correcAns){ //if there is an option which is matched to an array answer
    option_list.children[i].setAttribute("class", "option correct"); //adding green color to matched option
    option_list.children[i].insertAdjacentHTML("beforeend", tickIconTag); //adding tick icon to matched option
    console.log("Time Off: Auto selected correct answer.");
    }
    }
    for(i=0; i < allOptions; i++){
    option_list.children[i].classList.add("disabled"); //once user select an option then disabled all options
    }
    next_btn.classList.add("show"); //show the next button if user selected any option
    }
    }
    }
    
    function startTimerLine(time){
    counterLine = setInterval(timer, 323);
    function timer(){
    time += 2; //upgrading time value with 1
    time_line.style.width = time + "px"; //increasing width of time_line with px by time value
    if(time > 549){ //if time value is greater than 549
    clearInterval(counterLine); //clear counterLine
    }
    }
    }
    
    function queCounter(index){
    //creating a new span tag and passing the question number and total question
    let totalQueCounTag = '<span><p>'+ index +'</p> of <p>'+ questions.length +'</p> Questions</span>';
    bottom_ques_counter.innerHTML = totalQueCounTag;  //adding new span tag inside bottom_ques_counter
    }
   
   
    function Q1(){let que_count = 1 - 1; showQuetions(que_count); }
    function Q2(){let que_count = 2 - 1; showQuetions(que_count); }
    function Q3(){let que_count = 3 - 1; showQuetions(que_count); }
    function Q4(){let que_count = 4 - 1; showQuetions(que_count); }
    function Q5(){let que_count = 5 - 1; showQuetions(que_count); }
    function Q6(){let que_count = 6 - 1; showQuetions(que_count); }
    function Q7(){let que_count = 7 - 1; showQuetions(que_count); }
    function Q8(){let que_count = 8 - 1; showQuetions(que_count); }
    function Q9(){let que_count = 9 - 1; showQuetions(que_count); }
    function Q10(){let que_count = 10 - 1; showQuetions(que_count); }
    
    
    </script>


</script>

</body>
</html
