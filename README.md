# Tutorial02
 
Tutorial02 del texto guía:
Trata sobre el diseño de un sitio web de un club de fitness.
Cuenta con una página principal llamada tss_home.html y otras tres páginas llamadas (tss_bike.html, tss_run_html y tss_swim.html).
1.	Tss_home.html:
Cuenta con un:
a)	Un head: que contiene los caracteres que se van a agregar ,las palabras principales, el título de la pagina ,y los css ,que contienen las estructuras y estilos de la pagina.

b)	Body:
c)	Header:contiene una imagen que viene a ser la cabecera de la pagina y un nombre para la imagen.
d)	Nav:contiene una lista desordenada de navegación entre otras paginas.
e)	Article:contiene un id identificador de el articulo,eqtquetas (h1,h2),una imagen(img),un parrrafo(p) y etiquetas de texto,(strong),listas (ul).
f)	Aside:Contiene etiqueta h1 y blockquote que permite citar un párrafo.
g)	Footer (pie de pagina):el pie de pagina cuenta con una etiqueta de dirección.

<!doctype html>
<html>
<head>
<!--
    New Perspectives on HTML5 and CSS3, 7th Edition
    Tutorial 2
    Tutorial Case
    
    Tri and Succeed Sports
    Author: 
    Date:   

    Filename: tss_home.html
   -->

   <meta charset="utf-8" />
   <meta name="keywords" content="triathlon, running, swimming, cycling" />
   <title>Tri and Succeed Sports</title>
   <link href ="tss_layout.css" rel ="stylesheet"/>
   <link href ="tss_styles_txt.css" rel ="stylesheet" />
</head>

<body>
   <header>
      <img src="tss_logo.png" alt="Tri and Succeed Sports" />
   </header>
   
   <nav>
      <h1>Links</h1>
      <ul>
         <li><a href="tss_home.html">Home</a></li>
         <li><a href="tss_run.html">Running</a></li>
         <li><a href="tss_bike.html">Cycling</a></li>
         <li><a href="tss_swim.html">Swimming</a></li>
         <li class="newgroup"><a href="http://www.active.com/">Active.com</a></li>
         <li><a href="http://www.runnersworld.com/">Runner's World</a></li>
         <li><a href="https://www.endomondo.com/">endomondo.com</a></li>
         <li><a href="http://www.strava.com/">Strava</a></li>
         <li><a href="http://www.bicycling.com/">Bicycling Magazine</a></li>
         <li><a href="http://velonews.competitor.com/">VeloNews</a></li>
         <li><a href="http://bicycletutor.com/">Bicycle Tutor</a></li>
         <li><a href="http://www.swimsmooth.com/">Swim Smooth</a></li>
         <li><a href="http://www.swimmingworldmagazine.com/">Swimming World</a></li>
         <li><a href="http://www.usaswimming.org/">USA Swimming</a></li>
         <li class="newgroup"><a href="http://www.triathlon.org/">triathlon.org</a></li>
         <li><a href="http://www.usatriathlon.org/">usatriathlon.org</a></li>
         <li><a href="http://www.trifind.com/tx.html">Texas Triathlons</a></li>
         <li><a href="http://www.captextri.com/">CapTex Triathlon</a></li>
         <li><a href="http://www.trifind.com/">Triathlon Calendar</a></li>
         <li><a href="http://triathlon.competitor.com/">Triathlete.com</a></li>
         <li><a href="http://www.trifuel.com/">Trifuel.com</a></li>
      </ul>
   </nav>
   
   <article id="about_tss">
      <h1>About TSS </h1>
      <img src="tss_photo1.png" alt="" />
      <p>Since 2002, <strong>Tri and Succeed Sports</strong> has provided Austin 
      with a first class training center for athletes of all abilities and 
      goals. We specialize in helping you reach your full potential. You tell 
      us what you want to do; we work to fulfill your needs.</p>
      <p>Want to swim? Great! Interested in improving your cycling? Fantastic! 
      Want to tackle a triathlon? We're there for you: before, during, and after the 
      race. Or do you just want to get more fit? We are on it. We  customize our 
      instruction to match your goals. And you will finish what you start.</p>
      
      <h2>Classes</h2>
      <p>Winter instruction starts soon. Get a jump on your summer goals by 
      joining us for individual or group instruction in:</p>
      <ul>
         <li><strong>Running</strong>: We start with the basics to help you 
         run faster and farther than you ever thought possible without 
         aches and pains.</li>
         <li><strong>Cycling</strong>: The indoor bike trainers at TSS 
         include everything you need to refine your technique, stamina, and 
         power for improved results on the road.</li>
         <li><strong>Swimming</strong>: The open water swim can be one of 
         the most frightening sports to master. Our classes begin with basic 
         techniques so that your swim can be very enjoyable, and 
         not a chore.</li>
      </ul>
      <p>Contact us to set up individual instruction and assessment.</p>
      
      <h2>Our Philosophy</h2>
      <p>Athletes are the foundation of every successful training program. 
      The best coach is an experienced ‎guide who begins with each athlete's 
      hopes, dreams and desires and then tailors a ‎training plan based on 
      that individuals’s current fitness and lifestyle. Since 2002, TSS ‎has 
      helped hundreds of individuals achieve success in many fitness areas. 
      The winner is not the one who finishes first but anyone who starts 
      the race and perseveres. Join us and begin exploring the possible.</p>
   </article>
   
   <aside>
      <h1>Comments</h1>
      <blockquote> Thank you for all that you have done. I am amazed at 
      my progress. I realize that I have l lofty goals but you have me well 
      on my way.</blockquote>
      <blockquote> Alison kept me focused working toward my dreams. She 
      fosters a supportive and caring environment for growth as an athlete 
      and as a person. Thank you!</blockquote>
      <blockquote> You do it right! Your track record proves it.
      Proud to be a TSS athlete and I'm honored to have you all as my 
      coaches and support team.</blockquote>
      <blockquote> The coaches at TSS treat you with the highest respect: 
      whether you're an individual getting off the couch for the first time 
      or an elite athlete training for the Iron Man. They know 
      their stuff.</blockquote>
      <blockquote> I just completed my first marathon, following your fitness 
      schedule to the letter. Never once did I come close to bonking and 
      two days later I felt ready for another race!</blockquote>
   </aside>
   
   <footer>
      <address>
      Tri and Succeed Sports &#8226; 41 Venture Dr. &#8226; Austin, TX 
      78711 &#8226; 512.555.9917
      </address>
   </footer>
</body>
</html>



2.	Tss_bike.html:
Esta página cuenta con:
a)	head: que contiene los caracteres que se van a agregar ,las palabras principales, el título de la pagina ,y los css ,que contienen las estructuras y estilos de la página.
b)	Body:
c)	Header:contiene una imagen que viene a ser la cabecera de la pagina y un nombre para la imagen.
d)	Nav:contiene una lista desordenada de navegación entre otras paginas.

e)	Article:cuenta con una class para ser usado para dar estilos en la plantilla css,etiqueta de encabezado (h1)(h2),párrafo (p),listas(ol,ul) ,sup que define un fragmento de texto un poco mas pequeño y en una posición distinta al texto normal.
f)	Footer:
El pie de página contiene un una dirección (address).

<!doctype html>
<html>
<head>
<!--
    New Perspectives on HTML5 and CSS3, 7th Edition
    Tutorial 2
    Tutorial Case
    
    TSS Cycling Class
    Author: 
    Date:   

    Filename: tss_bike.html
   -->
   <meta charset="utf-8" />
   <title>TSS Cycling Class</title>
   <link href ="tss_layout.css" rel ="stylesheet" />
   <link href ="tss_styles.css" rel ="stylesheet" />

</head>

<body>
   <header>
      <img src="tss_logo.png" alt="Tri and Succeed Sports" />
   </header>
   
   <nav>
      <ul>
         <li><a href="tss_home.html">Home</a></li>
         <li><a href="tss_run.html">Running</a></li>
         <li><a href="tss_bike.html">Cycling</a></li>
         <li><a href="tss_swim.html">Swimming</a></li>
      </ul>
   </nav>   
   
   <article class="syllabus">
      <h1>Improving your Cycling</h1>
      <p>TSS offers its 10<sup>th</sup> indoor season of cycle training this 
      winter. Bring in your road bike and connect it to our VirtualRoad 
      cycling trainer. VirtualRoad is a fully equipped system with over 
      250 courses providing real-time feedback on power, heart rate, speed, 
      and stroke efficiency. The first weeks will include a lot of low 
      intensity cycling and stroke analysis to build a strong base for later 
      classes. This is a fully coached course led by Alison Palmer, MA, CSCS, 
      USAT Level II and David Young, BS, USAT Level I. Our TSS Coaches will 
      not be working out while you are; they will be focusing on improving 
      your form during your workout for you to get the best results. By the 
      end of the course we will move into workouts of greater intensity and 
      duration to prepare for the upcoming summer.</p>
      <p>The course meets for 90 minutes twice a week. You have the choice 
      among the following morning and evening sessions:</p>
      
      <ul>
         <li>6:00 AM - 7:30 AM (WF)</li>
         <li>5:00 PM - 6:30 PM (TR)</li>
         <li>7:00 PM - 8:30 PM (WF)</li>
      </ul>
      
      <h2>Course Outline</h2>
      <p>Make sure you bring your road bike to all classes. We do not have 
      spare bike for you to use!</p>
      
      <ol>
         <li>Week 1
            <ol>
               <li>Orientation
                  <ol>
                     <li>Bike Fitting</li>
                     <li>Learning about the Trainer</li>
                     <li>Interpreting Biofeedback</li>
                  </ol>
               </li>
               <li>Your Cycling Posture</li>
               <li>Stroke Analysis</li>
               <li>Initial Time Trial</li>
            </ol>
         </li>
         <li>Week 2
            <ol>
               <li>Stroke Analysis</li>
               <li>Proper Pedaling Technique</li>
               <li>Improving your Cadence</li>
            </ol>
         </li>
         <li>Week 3
            <ol>
               <li>Power Analysis</li>
               <li>Lactate Thresholds</li>
            </ol>
         </li>
         <li>Week 4
            <ol>
               <li>Power Intervals Phase 1</li>
               <li>Power Intervals Phase 2</li>
               <li>Hill Climbing</li>
            </ol>
         </li>
         <li>Week 5
            <ol>
               <li>Stroke Analysis</li>
               <li>Efficiency Drills</li>
               <li>Recovery Cycling</li>
            </ol>
         </li>
         <li>Week 6
            <ol>
               <li>Understanding Pace lines</li>
               <li>Aerodynamics</li>
               <li>Power Intervals Phase 3</li>
            </ol>
         </li>
         <li>Week 7
            <ol>
               <li>Endurance Cycling</li>
               <li>Endurance Test 1</li>
               <li>Endurance Test 2</li>
            </ol>
         </li>
         <li>Week 8
            <ol>
               <li>Mastering Sprints</li>
               <li>Time Trial Assessments</li>
               <li>Getting Ready for the Outdoors
                  <ol>
                     <li>Bicycle Maintenance</li>
                     <li>Roadside Repairs</li>
                     <li>Team Cycling</li>
                     <li>Hydration and Nutrition</li>
                  </ol>
               </li>
            </ol>
         </li>
      </ol>
      
   </article>
   
   <footer>
      <address>
      Tri and Succeed Sports &#8226; 41 Venture Dr. &#8226; Austin, 
      TX 78711 &#8226; 512.555.9917
      </address>
   </footer>
</body>
</html>



3.	Tss_run.html:
Esta página cuenta con:
a)	Head
que contiene los caracteres que se van a agregar ,las palabras principales, el título de la pagina ,y los css ,que contienen las estructuras y estilos de la página.

b)	Body
c)	Header:contiene una imagen que viene a ser la cabecera de la pagina y un nombre para la imagen.
d)	Nav:contiene una lista desordenada de navegación entre otras paginas.
e)	Article:contiene etiquetas de encabezado(h1,h2),etiqueta para párrafos(p),listas (ul,ol)
f)	Footer:contiene una etiqueta para poner la dirección (address).

<!doctype html>
<html>
<head>
<!--
    New Perspectives on HTML5 and CSS3, 7th Edition
    Tutorial 2
    Tutorial Case
    
    TSS Running Class
    Author: 
    Date:   

    Filename: tss_run.html
   -->
   <meta charset="utf-8" />
   <title>TSS Running Class</title>
   <link href ="tss_layout.css" rel ="stylesheet"/>
   <link href ="tss_styles_txt.css" rel ="stylesheet" />
</head>

<body>
   <header>
      <img src="tss_logo.png" alt="Tri and Succeed Sports" />
   </header>
   
   <nav>
      <ul>
         <li><a href="tss_home.html">Home</a></li>
         <li><a href="tss_run.html">Running</a></li>
         <li><a href="tss_bike.html">Cycling</a></li>
         <li><a href="tss_swim.html">Swimming</a></li>
      </ul>
   </nav>
   
   <article class="syllabus">
      
      <h1>Guided Running and Racing</h1>
      <p>The TSS running program is designed is to guide and motivate 
      runners to a personal best in their  run training and racing.  The 
      training program is heavily coached and has a moderately aggressive 
      approach to achieving your personal best.  We will educate you on 
      proper running form, biomechanics, training, nutrition and mental 
      toughness</p>
      <p>You will work with a TSS coach twice weekly to help you 
      accomplish your goals and you'll have the companionship of others 
      reaching for similar goals. At times, we'll have assistant coaches 
      to decrease the coach to athlete ratio for a higher quality experience. 
      Spend your workouts completing track workouts, hills repeats tempo runs,
      strength/power running, endurance strength training, and more. Each week 
      will challenge you, and be tailored towards your goals from sprint 
      races, 5K runs, or full-distance marathons.</p>
      <p>The course meets for 90 minutes twice a week. You have the choice 
      among the following morning and evening sessions:</p>
      
      <ul>
         <li>11:30 AM - 1:00 PM (MW)</li>
         <li>5:00 PM - 6:30 PM (TR)</li>
      </ul>
      
      <h2>Course Outline</h2>
      <p>The running class will meet at the Falk Running Center, and when 
      weather permits, we'll be outside at the Falk Running Track.</p>
      
      <ol>
         <li>Week 1
            <ol>
               <li>Orientation
                  <ol>
                     <li>Setting a Goal</li>
                     <li>Group Running</li>
                     <li>Clothing and Shoes</li>
                     <li>Danger Zones</li>
                  </ol>
               </li>
               <li>Initial Assessment
                  <ol>
                     <li>Gait Assessment</li>
                     <li>Power Measure</li>
                     <li>Time Trial</li>
                  </ol>
               </li>
               <li>Stretching Techniques</li>
            </ol>
         </li>
         <li>Week 2
            <ol>
               <li>Wind Sprints</li>
               <li>Recovery</li>
               <li>Building your Core</li>
            </ol>
         </li>
         <li>Week 3
            <ol>
               <li>Wind Sprints 2</li>
               <li>Stretching Session</li>
               <li>Yoga and Running</li>
            </ol>
         </li>
         <li>Week 4
            <ol>
               <li>Mid-range Running 1</li>
               <li>Mid-range Running 2</li>
            </ol>
         </li>
         <li>Week 5
            <ol>
               <li>Hill Repeats 1</li>
               <li>Recovery Runs</li>
               <li>Stretching</li>
            </ol>
         </li>
         <li>Week 6
            <ol>
               <li>Weight Training and Running</li>
               <li>Hill Repeats 2</li>
               <li>Building a Base</li>
            </ol>
         </li>
         <li>Week 7
            <ol>
               <li>Preparing for 5K Race</li>
               <li>5K Simulation 1</li>
               <li>5K Simulation 2</li>
            </ol>
         </li>
         <li>Week 8
            <ol>
               <li>Preparing for a Marathon</li>
               <li>Building and Recovering</li>
               <li>Final Assessment</li>
               <li>Final Time Trials</li>
            </ol>
         </li>
      </ol>
      
   </article>
   
   <footer>
      <address>
      Tri and Succeed Sports &#8226; 41 Venture Dr. &#8226; Austin, 
      TX 78711 &#8226; 512.555.9917
      </address>
   </footer>
</body>
</html>




4.	Tss_swim.html:
Esta página cuenta con:
a)	head: que contiene los caracteres que se van a agregar ,las palabras principales, el título de la pagina ,y los css ,que contienen las estructuras y estilos de la página.
b)	Body:
c)	Header:contiene una imagen que viene a ser la cabecera de la pagina y un nombre para la imagen.
d)	Nav:contiene una lista desordenada de navegación entre otras paginas.
e)	Article:Contiene una clase “syllabus” que sirve para identificar o asignarle estilos a esa parte de la pagina.
              Etiquetas de encabezado h1,h2
              Etiquetas de párrafo (p).
              Etiqueta de listas (ul,ol).
f)	Footer :En el pie de pagina esta la etiqueta de dirección (address)

<!doctype html>
<html>
<head>
<!--
    New Perspectives on HTML5 and CSS3, 7th Edition
    Tutorial 2
    Tutorial Case
    
    TSS Swimming Class
    Author: 
    Date:   

    Filename: tss_swim.html
   -->
   <meta charset="utf-8" />
   <title>TSS Swimming Class</title>
   
</head>

<body>
   <header>
      <img src="tss_logo.png" alt="Tri and Succeed Sports" />
   </header>
   
   <nav>
      <ul>
         <li><a href="tss_home.html">Home</a></li>
         <li><a href="tss_run.html">Running</a></li>
         <li><a href="tss_bike.html">Cycling</a></li>
         <li><a href="tss_swim.html">Swimming</a></li>
      </ul>
   </nav>   
   
   <article class="syllabus">    
      <h1>Swim for Fitness</h1>
      <p>TSS coaches take a scientific approach to swimming. We believe in 
      providing knowledge, motivation, confidence and support for any 
      athlete who want to improve his or her swimming abilities. The secret 
      of swimming lies in proper technique and efficiency to move through 
      the water with speed and efficiency. We keep our class sizes low so 
      our coaches can maximize the time spent on one-to-one instruction.</p>
      <p>We offer three instruction times this winter:</p>
      
      <ul>
         <li>6:00 AM - 7:00 AM (TR)</li>
         <li>5:00 PM - 6:00 PM (MW)</li>
         <li>5:00 PM - 6:00 PM (TR)</li>
      </ul>
      
      <h2>Course Outline</h2>
      <p>Arrive at the Tollaf Natatorium 10 minutes before class to ensure 
      that swim instruction begins on schedule.</p>
      
      <ol>
         <li>Week 1
            <ol>
               <li>Swim Evaluation
                  <ol>
                     <li>Posture</li>
                     <li>Stroke Assessment</li>
                     <li>Endurance Measure</li>
                  </ol>
               </li>
               <li>Stretching Exercises</li>
               <li>Body Position Drills</li>
            </ol>
         </li>
         <li>Week 2
            <ol>
               <li>Sculling Drills</li>
               <li>Body Rotation Drills</li>
               <li>Arm Position Drills</li>
            </ol>
         </li>
         <li>Week 3
            <ol>
               <li>Breathing Techniques</li>
               <li>Kick board Workouts</li>
               <li>Sculling Drills</li>
               <li>Mid-class Assessment</li>
            </ol>
         </li>
         <li>Week 4
            <ol>
               <li>Endurance Drills</li>
               <li>Body Position Drills</li>
               <li>Kick board Workouts</li>
               <li>Sculling Drills 2</li>
            </ol>
         </li>
         <li>Week 5
            <ol>
               <li>Sprint Techniques</li>
               <li>Body Rotation Drills</li>
               <li>Relay Races</li>
            </ol>
         </li>
         <li>Week 6
            <ol>
               <li>Endurance Swim</li>
               <li>Final Assessment
                  <ol>
                     <li>Posture</li>
                     <li>Stroke Assessment</li>
                     <li>Endurance Measure</li>
                  </ol>
               </li>
            </ol>
         </li>
      </ol>
      
   </article>
   
   <footer>
      <address>
      Tri and Succeed Sports &#8226; 41 Venture Dr. &#8226; Austin, 
      TX 78711 &#8226; 512.555.9917
      </address>
   </footer>
</body>
</html>

