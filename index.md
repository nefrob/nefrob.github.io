<!-- <link rel="stylesheet" href="/assets/css/style.scss"> -->

<!-- Anchor tags -->

<a name="Home"></a>

<div>
  <ul class="navbar">
    <li class="navbar"><a href="#Projects">Projects</a></li>
    <li class="navbar"><a href="#Work">Work Experience</a></li>
    <li class="navbar"><a href="#Education">Education</a></li>
    <li class="navbar"><a href="#Awards">Awards</a></li>
    <li class="navbar"><a href="#Gym">Gymnastics</a></li>
  </ul>
</div>

<a name="Projects"></a>

<details markdown="1" open>
<summary>
  <h1>Projects</h1>
  <hr class="close">
</summary>

<!--
  Projects to add:
  Parallel: add bfs / spark implementations
  Networking: add 244 final proj
  Databases: add imdb proj
  ML: add human protein atlas proj

  target="_blank" to links to make open in new tab
-->

<img class="side" align="right" src="/assets/img/sandman2.png">

-   **Sandman Swap**  
    September 2021

    <div style="max-width:80%;" markdown="1">
    A [Uniswap V1](https://github.com/Uniswap/uniswap-v1) clone for decentralized ERC20 token exchange via automated market maker on Ethereum. The React frontend uses `web3.js` to interact with smart contracts deployed on a local `ganache` blockchain. The client has basic functionality for providing/removing liquidity and swapping `ETH`/tokens via browser wallet (ex. MetaMask). Unit tests were written for the smart contracts. Styling was achieved using `react-bootstrap` components.
    </div>

    [GitHub Source](https://github.com/nefrob/sandman-swap)

---

<img class="side" align="right" src="/assets/img/rpc.png">

-   **Event-based RPC Server**  
    May 2021

    <div style="max-width:80%;">
    Having worked with multi-threaded blocking-IO server design, this project was completed out of curiosity to try event-based programming. It uses an epoll-based event loop, non-blocking sockets, threading, system calls and protobufs to service simple RPC requests. It is implemented using C++ (and CMake for compilation configuration).
    </div>

    [GitHub Source](https://github.com/nefrob/cpp-rpc)

---

<img class="side" align="right" src="/assets/img/rts/chess.png">

-   **Multiplayer RTS Game**  
    Mar 2021

    <div style="max-width:80%;">
    A multiplayer real-time strategy (RTS) game made with Unity, Mirror and C#. Features implemented include: ranged and melee
    units with NavMesh pathing and attack commands, resource and military buildings with gather points, fog-of-war, object 
    selection, minimap, camera pan/zoom/rotate, and basic menus. Mirror is used to setup a client-server model (not lockstep per older 
    RTS games) along with FizzySteamworks to enable playing with friends via Steam.
    </div>

    [GitHub Source](https://github.com/nefrob/unity-rts)

    <img class="enlarge" src="/assets/img/rts/menu.png">
    <img class="enlarge" src="/assets/img/rts/select.png">
    <img class="enlarge" src="/assets/img/rts/attack.png">

---

<img class="side" align="right" src="/assets/img/key.png">

-   **Double Ratchet Algorithm**  
    May 2020

    <div style="max-width:80%;">
    The DRA allows for two parties to exchange encrypted messages from initial shared secrets (ex. from key agreement protocol like X3HD). Makes use of cryptographic concepts including: KDF-chains, Diffie-Hellman key exchange and authenticated encryption. Both the base and header encryption variant of the algorithm are present. The project was implemented in Python.
    </div>

    [GitHub Source](https://github.com/nefrob/double-ratchet-alg)

---

<!-- <img class="side" align="right" src="/assets/img/bfs.png">

- **OMP BFS, PySpark Page Rank?**
  May 2020

  <div style="max-width:80%;">
  include links to code, simple explanation?
  bfs top down / bottom up explain, bitmap vs vertex set, traverse large graphs, open mp
  pyspark explain how optimize page rank for sparse matrix
  </div>

  [GitHub Source](https://github.com/nefrob/TODO)

___ -->

<img class="side" align="right" src="/assets/img/drt_processed.png">

-   **Offline Signature Verification**  
    Apr 2018

    <div style="max-width:80%;">
    CS231A: "Computer Vision" final project, which verifies the authenticity of handwritten signatures using hybrid DRT-PCA and DCT feature extraction with an SVM classifier. The project was implemented in Python.
    </div>

    [GitHub Source](https://github.com/nbutler1/Signature-Detection) |
    [Paper](assets/docs/offline-signature-verification.pdf)

---

<img class="side" align="right" src="/assets/img/pirates.png">

-   **Pirates vi Asteroids**  
    Mar 2018

    <div style="max-width:80%;">
      Pirates is based on the 1979 arcade multi-directional shooter Asteroids. The player combats various floating sea monsters
      with cannons, slowly splitting them into smaller yet faster threats, where collision marks death. The game features screen
      wrapped thrust-like movement along with various powers ups. There is some flair through "juiced" effects such as: water ripple and
      pixelation shaders, cannon smoke paths, explosion particle effects and a lagging trail on your ship.
    </div>

    <span class="br_small"></span>

    <iframe style="max-width:100%;" width="560" height="315" src="https://www.youtube.com/embed/uH27d8xegdE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

    <!-- [GitHub Source](https://github.com/nefrob/TODO) -->

    <!-- <img class="enlarge" src="/assets/img/pirates.gif"> -->

---

<img class="side" align="right" src="/assets/img/fracture.png">

-   **Voronoi Diagram Procedural Fracture**  
    Dec 2017

    <div style="max-width:80%;">
    CS348C: "Computer Graphics: Animation and Simulation" final project. Uses <a href="https://en.wikipedia.org/wiki/Fortune%27s_algorithm">Fortune's Algorithm</a> & <a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.101.8568&rep=rep1&type=pdf">Jump Flood Algorithm</a> to procedurally generate a fracture mesh for 3D boxes.
    </div>

    [GitHub Source](https://github.com/nefrob/cs348c-final-project) |
    [Demo Video]() |
    [Paper](assets/docs/348c_paper.pdf)

    <iframe style="max-width:100%;" width="560" height="315" src="https://www.youtube.com/embed/KHbrSTrsHwU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

<img class="side" align="right" src="/assets/img/bird.png">

-   **Boids Bird Flocking Simulation**  
    Oct 2017

    <div style="max-width:80%;">
    Boids are directed via forces: cohesion (bring towards center of flock), separation (penalty force for getting too close repels so no collision), and alignment (boids flying in same direction have same velocity). In the bounded box case a penalty force is applied the farther a boid gets from the box bounds, eventually turning it around. This contains the boids within a defined area.
    </div>

    <span class="br_small"></span>

    <div>
      <iframe  style="max-width:100%;" width="300" height="165" src="https://www.youtube.com/embed/eGI3EmDdLDk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

      <iframe  style="max-width:100%;" width="300" height="165" src="https://www.youtube.com/embed/fKotSBdbnb8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>

---

<img class="side" align="right" src="/assets/img/dodgeball.png">

-   **Dodgeball 2020**  
    Nov 2017 - Dec 2017

    <div style="max-width:80%;">
    Dodgeball 2020 is a retro-future arcade-platformer developed with Unity for PC. As lead programmer I did setup/scripting (C#) for character control/movement, dodgeballs, level elements, shaders, UI/menus, audio and scene control. It won awards from showcase industry visitors Niantic Inc. and Improbable.  
    </div>

    [GitHub Source](https://github.com/nefrob/cs146-final-project) |
    [Trailer](https://www.youtube.com/watch?v=2-k-1tsc0lM&feature=emb_logo) |
    [Download](https://stanfordstudentgames.itch.io/dodgeball-2020)

    <iframe style="max-width:100%;" width="560" height="315" src="https://www.youtube.com/embed/2-k-1tsc0lM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

<img class="side" align="right" src="/assets/img/spray_can.png">

-   **Graffiti Run**  
    Mar 2017

    <div style="max-width:80%;">
    Graffiti Run is an endless 2D-sidescroller developed with Unity for Android. It randomly generates terrain, enemies and collectibles for the custom drawn/animated player to navigate around. All scripting was done using C#.
    </div>

    [Gameplay](https://www.youtube.com/watch?v=2XY_Qk79e_o&feature=youtu.be)

    <iframe style="max-width:100%;" width="560" height="315" src="https://www.youtube.com/embed/2XY_Qk79e_o" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

<img class="side" align="right" src="/assets/img/grass.png">

-   **Grass Field Rendering**  
    Aug 2016

    <div style="max-width:80%;">
    In the early days of computer graphics, rendering large fields of high-quality grass in realtime was not feasible. This project uses grass billboard "stars" instead of individual blades, along with instancing to reduce GPU load. Wind animation, texture atlas and lighting (sun, shadow mapping) were implemented improve the naturalness of the scene. Completed from scratch in C++/OpenGL.
    </div>

    [Gallery](https://rneff9.wixsite.com/projects/images) |
    [Development Playlist](https://www.youtube.com/playlist?list=PLbCCTxDYG7TA45nyIgtKwosgFFXQ99m8z) |
    [Project Write-up](https://rneff9.wixsite.com/projects/project)

    <img class="enlarge" src="/assets/img/billboards.png">
    <img class="enlarge" src="/assets/img/shadowmap.png">
    <img class="enlarge" src="/assets/img/day.png">
    <img class="enlarge" src="/assets/img/sunset.png">

---

<img class="side" align="right" src="/assets/img/eye.png">

-   **Illusions**  
    Nov 2016

    <div style="max-width:80%;">
    Some fun illusion projects made for a psychology class using Python and OpenGL. The first, "Random Dot Stereogram", takes an image and creates a color-shifted plot to simulate a 3D image (if wearing red-blue glasses). The second, "Looming Luminance Square", simulates change in depth and illusory motion, without changing the focus or any actual motion.
    </div>

    <img class="enlarge" src="/assets/img/batman.png">
    <img class="enlarge" src="/assets/img/3d.png">

    <iframe style="max-width:100%;" width="392" height="220" src="https://www.youtube.com/embed/jmHdH4CEVaQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

</details>
<span class="br_med"></span>

<a name="Work"></a>

<details markdown="1" open>
<summary>
  <h1>Work Experience</h1>
  <hr class="close">
</summary>

<img class="side" align="right" src="/assets/img/tilt_logo.jpeg">

-   **Software Engineer, Tilt**  
    Full stack engineer (Django and React)  
    Nov 2021 - Present

<img class="side" align="right" src="/assets/img/cc_logo.jpeg">

-   **Student Mentor, Curious Cardinals**  
    Computer science project mentor/tutor for K-12 students  
    Feb 2021 - May 2022

---

<img class="side" align="right" src="/assets/img/stanford_logo.jpeg">

-   **Course Assistant, Stanford University**  
    CS 146: Introduction to Game Design and Development  
    Sep 2018 - Dec 2018

---

<img class="side" align="right" src="/assets/img/niantic_logo.jpeg">

-   **Software Engineer Intern, Niantic Inc.**  
    Client-side engineer (Unity/C#) for Pokémon Go and Ingress Prime  
    Jun 2018 - Sep 2018

</details>
<span class="br_med"></span>

<a name="Education"></a>

<details markdown="1" open>
<summary>
  <h1>Education</h1>
  <hr class="close">
</summary>

<img class="side" align="right" src="/assets/img/stanford_logo.jpeg">

-   **Stanford University**  
    Master of Science - MS, Computer Science  
    2018-2019

    <div style="max-width:80%;">
    Focus in Computer & Network Security; coursework included systems, networking, cryptography and machine learning.
    </div>

---

<img class="side" align="right" src="/assets/img/stanford_logo.jpeg">

-   **Stanford University**  
    Bachelor of Science - BS, Computer Science  
    2014-2018

    <div style="max-width:80%;">
    Focus in Graphics; coursework included systems, algorithms, computer vision, linear algebra and games. Minor in German Studies.
    </div>

</details>
<span class="br_med"></span>

<a name="Awards"></a>

<details markdown="1" open>
<summary>
  <h1>Awards</h1>
  <hr class="close">
</summary>

<img class="side" align="right" src="/assets/img/ncaa.png">

-   **NCAA Post Graduate Scholarship Recipient**  
    2018

-   **Nissen-Emery Award Finalist, NCAA Men's Gymnastics**  
    2018

<img class="side" align="right" src="/assets/img/cga.png">

-   **CGA First Team All-America Scholar-Athlete**  
    2016, 2017, 2018

-   **CGA Second Team All-America Scholar-Athlete**  
    2015

-   **CoSIDA Academic All-America Second Team (at-large)**  
    2018

<img class="side" align="right" src="/assets/img/mpsf.png">

-   **MPSF All-Academic Scholar-Athlete**  
    2016, 2017, 2018

<!--
<img class="side" style="height:60px; margin-top:0em" align="right" src="/assets/img/german.gif">  -->

-   **Delta Phi Alpha National German Honor Society Member**  
    2018

</details>
<span class="br_med"></span>

<a name="Gym"></a>

<details markdown="1" open>
<summary>
  <h1>Gymnastics</h1>
  <hr class="close">
</summary>

<img class="side" align="right" src="/assets/img/usag_logo.jpeg">

-   **USA Gymnastics**
    2011-2022

    <div style="max-width:80%;">
    I was a member of the USA Junior and Senior National teams through 2022, and spent three years training at the Olympic & Paralympic Training Center (OPTC) in Colorado Springs. Most recently I represented Team USA at the World Univeristy Games in Taiwan (2017), Calgary International Cup in Canada (2019), Pan American Games in Lima (2019) and Olympic Trials in St. Louis (2021).
    </div>

    [USAG Profile](https://usagym.org/pages/athletes/athleteListDetail.html?id=91339) |
    [YouTube](https://www.youtube.com/user/RobertNeffGym/featured)

    <iframe style="max-width:100%;" width="560" height="315" src="https://www.youtube.com/embed/46rrIqqoCnc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

    <div style="max-width:80%;">
      <img class="enlarge" src="/assets/img/usag/panams7.jpg">
      <img class="enlarge" src="/assets/img/usag/panams4.jpg">
      <img class="enlarge" src="/assets/img/usag/panams6.jpg">
      <img class="enlarge" src="/assets/img/usag/panams3.jpg">
      <img class="enlarge" src="/assets/img/usag/panams2.jpg">
      <img class="enlarge" src="/assets/img/usag/horse.jpg">
      <img class="enlarge" src="/assets/img/usag/cross.jpg">
      <img class="enlarge" src="/assets/img/usag/hbar.jpg">
    </div>

    Photos from USAG.

---

<img class="side" align="right" src="/assets/img/stanford_logo.jpeg">

-   **Stanford Men's Gymnastics**  
    2014-2018

    <div style="max-width:80%;">
    I competed on Stanford's Div. I Men's Gymnastics Team as an undergraduate, doing all six events (all-around). During my time on the team we brought home two 2nd place finishes at NCAA Championships, I was NCAA High Bar Champion in 2017 and 2018, and a six-time NCAA All-American.
    </div>

    [2017-18 Roster Profile](https://gostanford.com/sports/mens-gymnastics/roster/robert-neff/12509)

    <div style="max-width:80%;">
      <img class="enlarge" src="/assets/img/stanford/1.png">
      <img class="enlarge" src="/assets/img/stanford/2.jpg">
      <img class="enlarge" src="/assets/img/stanford/team_old.jpg">
      <img class="enlarge" src="/assets/img/stanford/hbar.jpg">
    </div>

    Photos from Stanford Athletics.

</details>

<!-- Leave Space at bottom  -->

<span class="br_large"></span>

<!-- Old page: [http://rneff9.wixsite.com/projects](http://rneff9.wixsite.com/projects). -->
