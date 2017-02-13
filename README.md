# CSCI4830
ClassAssignments Accessibility Assesment

The following HTML taken from www.dsrny.com

<!DOCTYPE html>

<html>
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <title>diller scofidio + renfro</title>
  <meta name="description" content="DILLER SCOFIDIO + RENFRO is an interdisciplinary design studio that integrates architecture, the visual arts, and the performing arts. Based in New York City, Diller Scofidio + Renfro is led by three partners who work collaboratively with a staff of 100 architects, artists and administrators.">
  <link rel="stylesheet" href="/lib/css/landing.css" type="text/css" charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
  <meta name="format-detection" content="telephone=no">
  <script type="text/javascript">
  (function(){
    var desktop = window.matchMedia ? matchMedia("only screen and (min-device-width : 1080px)").matches : true,
        isIE = !window.history.replaceState,
        path = window.location.pathname,
        hash = window.location.hash.substr(1)
        isProject = /^\/projects\/[a-z\-]+\/?$/,
        isDept = /^\/(news|about|contact)/;
    if (desktop){
      var href = (isProject.exec(path)) ? path
               : (isDept.exec(path)) ? '/projects/info'
               : (isProject.exec(hash)) ? hash
               : '/';

      if (isIE){
        if (path!='/') location.href = '/#' + href
      }else{
        if (path!=href) location.href = href
      }

    }else{
      if (isProject.exec(hash)) location.href = hash
    }
    window.DSR = {desktop:desktop} // being for the benefit of init.js
  })()
  </script>
  <script type="text/javascript">
    var _gaq = _gaq || [];
    _gaq.push(['_setAccount', 'UA-37716273-1']);
    _gaq.push(['_trackPageview']);

    (function() {
      var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
      ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
      var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
    })();
  </script>
  <!--[if lt IE 9]>
<style>
  #rolodex,#dept,#project,#slideshow,#controls,#search,#menu{display:none;}
  #legacy{display:block;}
</style>
<![endif]-->
</head>
<body>

  <div id="rolodex">
    <div id="environment">
        <ul id="stack" class="site">
          <li class="folder">
            <div class="tab">about</div>
            <div class="face">
              <a href="/projects/info"><img src="/projects/info/card.jpg"></a>
            </div>
            <ul class="filler">
              <li><img src="/lib/img/about-filler.jpg"></li>
            </ul>
          </li>
        
          <li class="folder loading">
            <div class="tab">art</div>
            <div class="face">
              <a href="/categories/art"><img src="/lib/img/blank-face.png"></a>
              <div class="count">
                <h3>58</h3>
                <h4 class="subtitle">Projects</h4>
              </div>
            </div>
            <ul class="filler">
            
              <li><img src="/projects/exit/card.jpg"></li>
            
              <li><img src="/projects/chareau/card.jpg"></li>
            
              <li><img src="/projects/moagb/card.jpg"></li>
            
            </ul>
          </li>
        
          <li class="folder loading">
            <div class="tab">commercial</div>
            <div class="face">
              <a href="/categories/commercial"><img src="/lib/img/blank-face.png"></a>
              <div class="count">
                <h3>18</h3>
                <h4 class="subtitle">Projects</h4>
              </div>
            </div>
            <ul class="filler">
            
              <li><img src="/projects/d-tower/card.jpg"></li>
            
              <li><img src="/projects/burchen-mystik/card.jpg"></li>
            
              <li><img src="/projects/ioc-hq/card.jpg"></li>
            
            </ul>
          </li>
        
          <li class="folder loading">
            <div class="tab">cultural</div>
            <div class="face">
              <a href="/categories/cultural"><img src="/lib/img/blank-face.png"></a>
              <div class="count">
                <h3>44</h3>
                <h4 class="subtitle">Projects</h4>
              </div>
            </div>
            <ul class="filler">
            
              <li><img src="/projects/bampfa/card.jpg"></li>
            
              <li><img src="/projects/columbia-medical-center/card.jpg"></li>
            
              <li><img src="/projects/rio-mis/card.jpg"></li>
            
            </ul>
          </li>
        
          <li class="folder loading">
            <div class="tab">landscape</div>
            <div class="face">
              <a href="/categories/landscape"><img src="/lib/img/blank-face.png"></a>
              <div class="count">
                <h3>23</h3>
                <h4 class="subtitle">Projects</h4>
              </div>
            </div>
            <ul class="filler">
            
              <li><img src="/projects/zaryadye-park/card.jpg"></li>
            
              <li><img src="/projects/high-line-three/card.jpg"></li>
            
              <li><img src="/projects/wishard-pavilion/card.jpg"></li>
            
            </ul>
          </li>
        
          <li class="folder loading">
            <div class="tab">masterplan</div>
            <div class="face">
              <a href="/categories/masterplan"><img src="/lib/img/blank-face.png"></a>
              <div class="count">
                <h3>16</h3>
                <h4 class="subtitle">Projects</h4>
              </div>
            </div>
            <ul class="filler">
            
              <li><img src="/projects/synchronizing-the-city/card.jpg"></li>
            
              <li><img src="/projects/zaryadye-park/card.jpg"></li>
            
              <li><img src="/projects/cooper-hewitt/card.jpg"></li>
            
            </ul>
          </li>
        
          <li class="folder loading">
            <div class="tab">media/tech</div>
            <div class="face">
              <a href="/categories/media+tech"><img src="/lib/img/blank-face.png"></a>
              <div class="count">
                <h3>46</h3>
                <h4 class="subtitle">Projects</h4>
              </div>
            </div>
            <ul class="filler">
            
              <li><img src="/projects/exit/card.jpg"></li>
            
              <li><img src="/projects/chareau/card.jpg"></li>
            
              <li><img src="/projects/synchronizing-the-city/card.jpg"></li>
            
            </ul>
          </li>
        
          <li class="folder loading">
            <div class="tab">objects</div>
            <div class="face">
              <a href="/categories/objects"><img src="/lib/img/blank-face.png"></a>
              <div class="count">
                <h3>12</h3>
                <h4 class="subtitle">Projects</h4>
              </div>
            </div>
            <ul class="filler">
            
              <li><img src="/projects/light-sock/card.jpg"></li>
            
              <li><img src="/projects/meat-dress/card.jpg"></li>
            
              <li><img src="/projects/blur-braincoat/card.jpg"></li>
            
            </ul>
          </li>
        
          <li class="folder loading">
            <div class="tab">performance</div>
            <div class="face">
              <a href="/categories/performance"><img src="/lib/img/blank-face.png"></a>
              <div class="count">
                <h3>10</h3>
                <h4 class="subtitle">Projects</h4>
              </div>
            </div>
            <ul class="filler">
            
              <li><img src="/projects/be-your-self/card.jpg"></li>
            
              <li><img src="/projects/traveling-music/card.jpg"></li>
            
              <li><img src="/projects/whos-your-dada/card.jpg"></li>
            
            </ul>
          </li>
        
          <li class="folder loading">
            <div class="tab">residential</div>
            <div class="face">
              <a href="/categories/residential"><img src="/lib/img/blank-face.png"></a>
              <div class="count">
                <h3>14</h3>
                <h4 class="subtitle">Projects</h4>
              </div>
            </div>
            <ul class="filler">
            
              <li><img src="/projects/d-tower/card.jpg"></li>
            
              <li><img src="/projects/boom-palm-springs/card.jpg"></li>
            
              <li><img src="/projects/mixed-use-towers/card.jpg"></li>
            
            </ul>
          </li>
        
        </ul>
    </div>

    <div id="scroll-proxy">
      <div id="scroller">
        <ul>
          <li>residential</li><li>performance</li><li>objects</li><li>media/tech</li><li>masterplan</li><li>landscape</li><li>cultural</li><li>commercial</li><li>art</li>
          <li>about</li>
        </ul>
      </div>
    </div>
  </div>

  
  <div id="legacy">
    <div class="vimeo">
      <div class="close-box">&times;</div>
      <div class="player"></div>
    </div>
    <div id="flash">
      <div class="getflash"><a href="http://get.adobe.com/flashplayer/"></a></div>
    </div>
  </div>


  
  <nav>
    <div id="controls">
      <div class="menu button"><span>Menu</span></div>
      <div class="search button"></div>
      <div class="query">
        <form action="#">
          <input type="search" autocomplete="off" autocorrect="off" placeholder="Name, location, or year">
        </form>
        <a href="#">Cancel</a>
      </div>
      <div class="logo button">Diller Scofidio <span class="plus">+</span> Renfro</div>
    </div>

    <div id="search">
      <div class="query">
        <form action="#">
          <input type="search" autocomplete="off" autocorrect="off" placeholder="Name, location, or year">
        </form>
        <a href="#">Cancel</a>
      </div>

      <ul class="results"><li data-key="news||2017">
          <a href="/projects/news"><span class="title">NEWS</span><br/>2017</a>
        </li><li data-key="15 hy|new york, ny|2016">
          <a href="/projects/d-tower"><span class="title">15 HY</span><br/>New York, NY, 2016</a>
        </li><li data-key="berkeley art museum / pacific film archive|berkeley, ca|2016">
          <a href="/projects/bampfa"><span class="title">BERKELEY ART MUSEUM / PACIFIC FILM ARCHIVE</span><br/>Berkeley, CA, 2016</a>
        </li><li data-key="columbia university vagelos education center|new york, ny|2016">
          <a href="/projects/columbia-medical-center"><span class="title">COLUMBIA UNIVERSITY VAGELOS EDUCATION CENTER</span><br/>New York, NY, 2016</a>
        </li><li data-key="exit|paris, france|2016">
          <a href="/projects/exit"><span class="title">EXIT</span><br/>Paris, France, 2016</a>
        </li><li data-key="museum of image &amp; sound|rio de janeiro, brazil|2016">
          <a href="/projects/rio-mis"><span class="title">MUSEUM OF IMAGE &amp; SOUND</span><br/>Rio de Janeiro, Brazil, 2016</a>
        </li><li data-key="pierre chareau|new york, ny|2016">
          <a href="/projects/chareau"><span class="title">PIERRE CHAREAU</span><br/>NEW YORK, NY, 2016</a>
        </li><li data-key="south sea pearl eco-island|haikou, china|2016">
          <a href="/projects/eco-island"><span class="title">SOUTH SEA PEARL ECO-ISLAND</span><br/>Haikou, China, 2016</a>
        </li><li data-key="synchronizing the city|london|2016">
          <a href="/projects/synchronizing-the-city"><span class="title">SYNCHRONIZING THE CITY</span><br/>London, 2016</a>
        </li><li data-key="the shed|new york, ny|2016">
          <a href="/projects/the-shed"><span class="title">THE SHED</span><br/>New York, NY, 2016</a>
        </li><li data-key="united states olympic museum|colorado springs, co|2016">
          <a href="/projects/usom"><span class="title">UNITED STATES OLYMPIC MUSEUM</span><br/>Colorado Springs, CO, 2016</a>
        </li><li data-key="zaryadye park|moscow, russia|2016">
          <a href="/projects/zaryadye-park"><span class="title">ZARYADYE PARK</span><br/>Moscow, Russia, 2016</a>
        </li><li data-key="musings on a glass box|paris, france|2015">
          <a href="/projects/moagb"><span class="title">MUSINGS ON A GLASS BOX</span><br/>Paris, France, 2015</a>
        </li><li data-key="stanford art &amp; art history building|palo alto, ca|2015">
          <a href="/projects/stanford-art"><span class="title">STANFORD ART &amp; ART HISTORY BUILDING</span><br/>Palo Alto, CA, 2015</a>
        </li><li data-key="the broad|los angeles, ca|2015">
          <a href="/projects/the-broad"><span class="title">THE BROAD</span><br/>Los Angeles, CA, 2015</a>
        </li><li data-key="charles james: beyond fashion|new york, ny|2014">
          <a href="/projects/charles-james"><span class="title">CHARLES JAMES: BEYOND FASHION</span><br/>New York, NY, 2014</a>
        </li><li data-key="cooper hewitt smithsonian design museum|new york, ny|2014">
          <a href="/projects/cooper-hewitt"><span class="title">COOPER HEWITT SMITHSONIAN DESIGN MUSEUM</span><br/>New York, NY, 2014</a>
        </li><li data-key="high line (phase iii)|new york, ny|2014">
          <a href="/projects/high-line-three"><span class="title">HIGH LINE (PHASE III)</span><br/>New York, NY, 2014</a>
        </li><li data-key="the look|new canaan, ct|2014">
          <a href="/projects/the-look"><span class="title">THE LOOK</span><br/>New Canaan, CT, 2014</a>
        </li><li data-key="wishard pavilion|indianapolis, in|2014">
          <a href="/projects/wishard-pavilion"><span class="title">WISHARD PAVILION</span><br/>Indianapolis, IN, 2014</a>
        </li><li data-key="zaryadye park: augmented atmospheres|venice, italy|2014">
          <a href="/projects/zaryadye-park-augmented-atmospheres"><span class="title">ZARYADYE PARK: AUGMENTED ATMOSPHERES</span><br/>Venice, Italy, 2014</a>
        </li><li data-key="bubble: hirshhorn museum and sculpture garden expansion|washington, dc|2013">
          <a href="/projects/hirshhorn-bubble"><span class="title">BUBBLE: HIRSHHORN MUSEUM AND SCULPTURE GARDEN EXPANSION</span><br/>Washington, DC, 2013</a>
        </li><li data-key="bürchen_mystik |bürchen, switzerland|2013">
          <a href="/projects/burchen-mystik"><span class="title">BÜRCHEN_MYSTIK </span><br/>Bürchen, Switzerland, 2013</a>
        </li><li data-key="international olympic committee hq|lausanne, switzerland|2013">
          <a href="/projects/ioc-hq"><span class="title">INTERNATIONAL OLYMPIC COMMITTEE HQ</span><br/>Lausanne, Switzerland, 2013</a>
        </li><li data-key="køge kulturhus|køge, denmark|2013">
          <a href="/projects/koge-kulturhus"><span class="title">KØGE KULTURHUS</span><br/>Køge, Denmark, 2013</a>
        </li><li data-key="penn station 3.0|new york, ny|2013">
          <a href="/projects/penn-station"><span class="title">PENN STATION 3.0</span><br/>New York, NY, 2013</a>
        </li><li data-key="the art of scent|new york, ny|2013">
          <a href="/projects/art-of-scent"><span class="title">THE ART OF SCENT</span><br/>New York, NY, 2013</a>
        </li><li data-key="west kowloon cultural district park|kowloon, hong kong|2013">
          <a href="/projects/wkcd"><span class="title">WEST KOWLOON CULTURAL DISTRICT PARK</span><br/>Kowloon, Hong Kong, 2013</a>
        </li><li data-key="aberdeen city center|aberdeen, scotland|2012">
          <a href="/projects/aberdeen"><span class="title">ABERDEEN CITY CENTER</span><br/>Aberdeen, Scotland, 2012</a>
        </li><li data-key="lincoln center bridge|new york, ny|2012">
          <a href="/projects/lincoln-center-bridge"><span class="title">LINCOLN CENTER BRIDGE</span><br/>New York, NY, 2012</a>
        </li><li data-key="boom! palm springs|palm springs, ca|2011">
          <a href="/projects/boom-palm-springs"><span class="title">BOOM! PALM SPRINGS</span><br/>Palm Springs, CA, 2011</a>
        </li><li data-key="creative arts center|providence, ri|2011">
          <a href="/projects/creative-arts-center"><span class="title">CREATIVE ARTS CENTER</span><br/>Providence, RI, 2011</a>
        </li><li data-key="high line (phase i &amp; ii)|new york, ny|2011">
          <a href="/projects/high-line-two"><span class="title">HIGH LINE (PHASE I &amp; II)</span><br/>New York, NY, 2011</a>
        </li><li data-key="how wine became modern: design + wine 1976 to now|sfmoma, san francisco, ca|2011">
          <a href="/projects/how-wine-became-modern"><span class="title">HOW WINE BECAME MODERN: DESIGN + WINE 1976 TO NOW</span><br/>SFMOMA, San Francisco, CA, 2011</a>
        </li><li data-key="international convention center|bogota, colombia|2011">
          <a href="/projects/bogota-convention-center"><span class="title">INTERNATIONAL CONVENTION CENTER</span><br/>Bogota, Colombia, 2011</a>
        </li><li data-key="open house|levittown, ny|2011">
          <a href="/projects/open-house"><span class="title">OPEN HOUSE</span><br/>Levittown, NY, 2011</a>
        </li><li data-key="be your self|adelaide, australia|2010">
          <a href="/projects/be-your-self"><span class="title">BE YOUR SELF</span><br/>Adelaide, Australia, 2010</a>
        </li><li data-key="fashion week|new york, ny|2010">
          <a href="/projects/fashion-week"><span class="title">FASHION WEEK</span><br/>New York, NY, 2010</a>
        </li><li data-key="hypar pavilion at lincoln center|new york, ny|2010">
          <a href="/projects/lincoln-center-hypar"><span class="title">HYPAR PAVILION AT LINCOLN CENTER</span><br/>New York, NY, 2010</a>
        </li><li data-key="lincoln center public spaces and infoscape|new york, ny|2010">
          <a href="/projects/lincoln-center-public-spaces"><span class="title">LINCOLN CENTER PUBLIC SPACES AND INFOSCAPE</span><br/>New York, NY, 2010</a>
        </li><li data-key="new dance and music centre|the hague, netherlands|2010">
          <a href="/projects/hague"><span class="title">NEW DANCE AND MUSIC CENTRE</span><br/>The Hague, Netherlands, 2010</a>
        </li><li data-key="public sky|santiago, chile|2010">
          <a href="/projects/public-sky"><span class="title">PUBLIC SKY</span><br/>Santiago, Chile, 2010</a>
        </li><li data-key="alice tully hall|new york, ny|2009">
          <a href="/projects/alice-tully-hall"><span class="title">ALICE TULLY HALL</span><br/>New York, NY, 2009</a>
        </li><li data-key="center for civil and human rights|atlanta, ga|2009">
          <a href="/projects/center-for-civil-and-human"><span class="title">CENTER FOR CIVIL AND HUMAN RIGHTS</span><br/>Atlanta, GA, 2009</a>
        </li><li data-key="governors island park|new york, ny|2009">
          <a href="/projects/governors-island-park"><span class="title">GOVERNORS ISLAND PARK</span><br/>New York, NY, 2009</a>
        </li><li data-key="juilliard school|new york, ny|2009">
          <a href="/projects/juilliard-school"><span class="title">JUILLIARD SCHOOL</span><br/>New York, NY, 2009</a>
        </li><li data-key="light sock|swarovski crystal palace|2009">
          <a href="/projects/light-sock"><span class="title">LIGHT SOCK</span><br/>Swarovski Crystal Palace, 2009</a>
        </li><li data-key="mixed-use towers|middle east|2009">
          <a href="/projects/mixed-use-towers"><span class="title">MIXED-USE TOWERS</span><br/>Middle East, 2009</a>
        </li><li data-key="mott street townhouse|new york, ny|2009">
          <a href="/projects/mott-street-townhouse"><span class="title">MOTT STREET TOWNHOUSE</span><br/>New York, NY, 2009</a>
        </li><li data-key="munch + stenersen museum|oslo, norway|2009">
          <a href="/projects/munch-stenersen"><span class="title">MUNCH + STENERSEN MUSEUM</span><br/>Oslo, Norway, 2009</a>
        </li><li data-key="national museum of african american history and culture|washington, dc|2009">
          <a href="/projects/museum-of-african-american-culture"><span class="title">NATIONAL MUSEUM OF AFRICAN AMERICAN HISTORY AND CULTURE</span><br/>Washington, DC, 2009</a>
        </li><li data-key="national music centre|calgary, canada|2009">
          <a href="/projects/national-music-centre"><span class="title">NATIONAL MUSIC CENTRE</span><br/>Calgary, Canada, 2009</a>
        </li><li data-key="traveling music|bordeaux, france|2009">
          <a href="/projects/traveling-music"><span class="title">TRAVELING MUSIC</span><br/>Bordeaux, France, 2009</a>
        </li><li data-key="action painting|riehen, switzerland|2008">
          <a href="/projects/action-painting"><span class="title">ACTION PAINTING</span><br/>Riehen, Switzerland, 2008</a>
        </li><li data-key="arbores laetae|liverpool, uk|2008">
          <a href="/projects/arbores-laetae"><span class="title">ARBORES LAETAE</span><br/>Liverpool, UK, 2008</a>
        </li><li data-key="boulders resort|scottsdale, az|2008">
          <a href="/projects/boulders-resort"><span class="title">BOULDERS RESORT</span><br/>Scottsdale, AZ, 2008</a>
        </li><li data-key="chain city|venice, italy|2008">
          <a href="/projects/chain-city"><span class="title">CHAIN CITY</span><br/>Venice, Italy, 2008</a>
        </li><li data-key="does the punishment fit the crime?|turin, italy|2008">
          <a href="/projects/does-the-punishment"><span class="title">DOES THE PUNISHMENT FIT THE CRIME?</span><br/>Turin, Italy, 2008</a>
        </li><li data-key="hudson riverfront performing arts center|weehawken, nj|2008">
          <a href="/projects/hudson-riverfront-pac"><span class="title">HUDSON RIVERFRONT PERFORMING ARTS CENTER</span><br/>Weehawken, NJ, 2008</a>
        </li><li data-key="no (no smoking)|amsterdam, the netherlands|2008">
          <a href="/projects/no-no-smoking"><span class="title">NO (NO SMOKING)</span><br/>Amsterdam, The Netherlands, 2008</a>
        </li><li data-key="ph project|venice, italy|2008">
          <a href="/projects/ph-project"><span class="title">PH PROJECT</span><br/>Venice, Italy, 2008</a>
        </li><li data-key="staedel museum expansion|frankfurt, germany|2008">
          <a href="/projects/staedel-museum"><span class="title">STAEDEL MUSEUM EXPANSION</span><br/>Frankfurt, Germany, 2008</a>
        </li><li data-key="stapleton homeport|staten island, ny|2008">
          <a href="/projects/stapleton-homeport"><span class="title">STAPLETON HOMEPORT</span><br/>Staten Island, NY, 2008</a>
        </li><li data-key="taekwondo park|muju, south korea|2008">
          <a href="/projects/taekwondo-park"><span class="title">TAEKWONDO PARK</span><br/>Muju, South Korea, 2008</a>
        </li><li data-key="aros sky space|aarhus, denmark|2007">
          <a href="/projects/aros-sky-space"><span class="title">AROS SKY SPACE</span><br/>Aarhus, Denmark, 2007</a>
        </li><li data-key="hudson railyards|new york, ny|2007">
          <a href="/projects/hudson-rail-yards"><span class="title">HUDSON RAILYARDS</span><br/>New York, NY, 2007</a>
        </li><li data-key="midtown tower|new york, ny|2007">
          <a href="/projects/midtown-tower"><span class="title">MIDTOWN TOWER</span><br/>New York, NY, 2007</a>
        </li><li data-key="phantom house|the new york times magazine|2007">
          <a href="/projects/phantom-house"><span class="title">PHANTOM HOUSE</span><br/>The New York Times Magazine, 2007</a>
        </li><li data-key="russian jewish museum|moscow, russia|2007">
          <a href="/projects/russian-jewish-museum"><span class="title">RUSSIAN JEWISH MUSEUM</span><br/>Moscow, Russia, 2007</a>
        </li><li data-key="school of american ballet|new york, ny|2007">
          <a href="/projects/school-of-american-ballet"><span class="title">SCHOOL OF AMERICAN BALLET</span><br/>New York, NY, 2007</a>
        </li><li data-key="clyfford still museum |denver, co|2006">
          <a href="/projects/clyfford-still-museum"><span class="title">CLYFFORD STILL MUSEUM </span><br/>Denver, CO, 2006</a>
        </li><li data-key="have you ever been mistaken for a...?|lille, france|2006">
          <a href="/projects/have-you-ever-been"><span class="title">HAVE YOU EVER BEEN MISTAKEN FOR A...?</span><br/>Lille, France, 2006</a>
        </li><li data-key="institute of contemporary art|boston, ma|2006">
          <a href="/projects/ica"><span class="title">INSTITUTE OF CONTEMPORARY ART</span><br/>Boston, MA, 2006</a>
        </li><li data-key="meat dress|new york, ny|2006">
          <a href="/projects/meat-dress"><span class="title">MEAT DRESS</span><br/>New York, NY, 2006</a>
        </li><li data-key="who&#39;s your dada?|new york, ny|2006">
          <a href="/projects/whos-your-dada"><span class="title">WHO&#39;S YOUR DADA?</span><br/>New York, NY, 2006</a>
        </li><li data-key="quadrant house|camelback mountain, phoenix, az|2005">
          <a href="/projects/quadrant-house"><span class="title">QUADRANT HOUSE</span><br/>Camelback Mountain, Phoenix, AZ, 2005</a>
        </li><li data-key="eyebeam museum of art and technology|new york, ny|2004">
          <a href="/projects/eyebeam"><span class="title">EYEBEAM MUSEUM OF ART AND TECHNOLOGY</span><br/>New York, NY, 2004</a>
        </li><li data-key="facsimile|san francisco, ca|2004">
          <a href="/projects/facsimile"><span class="title">FACSIMILE</span><br/>San Francisco, CA, 2004</a>
        </li><li data-key="learning center|lausanne, switzerland|2004">
          <a href="/projects/learning-center"><span class="title">LEARNING CENTER</span><br/>Lausanne, Switzerland, 2004</a>
        </li><li data-key="liaunig collection|neuhaus, austria|2004">
          <a href="/projects/liaunig-collection"><span class="title">LIAUNIG COLLECTION</span><br/>Neuhaus, Austria, 2004</a>
        </li><li data-key="living room|london, uk|2004">
          <a href="/projects/living-room"><span class="title">LIVING ROOM</span><br/>London, UK, 2004</a>
        </li><li data-key="pure mix|kemi, finland|2004">
          <a href="/projects/pure-mix"><span class="title">PURE MIX</span><br/>Kemi, Finland, 2004</a>
        </li><li data-key="tivoli gardens|copenhagen, denmark|2004">
          <a href="/projects/tivoli-gardens"><span class="title">TIVOLI GARDENS</span><br/>Copenhagen, Denmark, 2004</a>
        </li><li data-key="biblioteca de mexico jose vasconselos|mexico city, mexico|2003">
          <a href="/projects/biblioteca-de-mexico"><span class="title">BIBLIOTECA DE MEXICO JOSE VASCONSELOS</span><br/>Mexico City, Mexico, 2003</a>
        </li><li data-key="mural|new york, ny|2003">
          <a href="/projects/mural"><span class="title">MURAL</span><br/>New York, NY, 2003</a>
        </li><li data-key="waterfront park|new york, ny|2003">
          <a href="/projects/waterfrontpark"><span class="title">WATERFRONT PARK</span><br/>New York, NY, 2003</a>
        </li><li data-key="blur building|yverdon-les-bains, switzerland|2002">
          <a href="/projects/blur-building"><span class="title">BLUR BUILDING</span><br/>Yverdon-les-Bains, Switzerland, 2002</a>
        </li><li data-key="blur: braincoat|yverdon-les-bains, switzerland|2002">
          <a href="/projects/blur-braincoat"><span class="title">BLUR: BRAINCOAT</span><br/>Yverdon-les-Bains, Switzerland, 2002</a>
        </li><li data-key="wooster group theater|brooklyn, ny|2002">
          <a href="/projects/wooster-group-theater"><span class="title">WOOSTER GROUP THEATER</span><br/>Brooklyn, NY, 2002</a>
        </li><li data-key="brooklyn academy of music|brooklyn, ny|2001">
          <a href="/projects/brooklyn-academy-of-music"><span class="title">BROOKLYN ACADEMY OF MUSIC</span><br/>Brooklyn, NY, 2001</a>
        </li><li data-key="travelogues|new york, ny|2001">
          <a href="/projects/travelogues"><span class="title">TRAVELOGUES</span><br/>New York, NY, 2001</a>
        </li><li data-key="two-way hotel|hong kong|2001">
          <a href="/projects/two-way-hotel"><span class="title">TWO-WAY HOTEL</span><br/>Hong Kong, 2001</a>
        </li><li data-key="viewing platform|new york, ny|2001">
          <a href="/projects/viewing-platform"><span class="title">VIEWING PLATFORM</span><br/>New York, NY, 2001</a>
        </li><li data-key="brasserie|new york, ny|2000">
          <a href="/projects/brasserie"><span class="title">BRASSERIE</span><br/>New York, NY, 2000</a>
        </li><li data-key="rapid growth|philadelphia, pa|2000">
          <a href="/projects/rapid-growth"><span class="title">RAPID GROWTH</span><br/>Philadelphia, PA, 2000</a>
        </li><li data-key="slither housing|gifu, japan|2000">
          <a href="/projects/slither"><span class="title">SLITHER HOUSING</span><br/>Gifu, Japan, 2000</a>
        </li><li data-key="crutch lamp||1999">
          <a href="/projects/crutch-lamp"><span class="title">CRUTCH LAMP</span><br/>1999</a>
        </li><li data-key="master/slave|paris, france|1999">
          <a href="/projects/master-slave"><span class="title">MASTER/SLAVE</span><br/>Paris, France, 1999</a>
        </li><li data-key="american lawn|montreal, canada|1998">
          <a href="/projects/american-lawn"><span class="title">AMERICAN LAWN</span><br/>Montreal, Canada, 1998</a>
        </li><li data-key="ejm i and ii|premiered in lyon, france|1998">
          <a href="/projects/ejm"><span class="title">EJM I AND II</span><br/>Premiered in Lyon, France, 1998</a>
        </li><li data-key="jet lag|premiered in new york, ny|1998">
          <a href="/projects/jet-lag"><span class="title">JET LAG</span><br/>Premiered in New York, NY, 1998</a>
        </li><li data-key="refresh|new york, ny|1998">
          <a href="/projects/refresh"><span class="title">REFRESH</span><br/>New York, NY, 1998</a>
        </li><li data-key="cold war|sunrise, fl|1997">
          <a href="/projects/cold-war"><span class="title">COLD WAR</span><br/>Sunrise, FL, 1997</a>
        </li><li data-key="interclone hotel|istanbul, turkey|1997">
          <a href="/projects/interclone-hotel"><span class="title">INTERCLONE HOTEL</span><br/>Istanbul, Turkey, 1997</a>
        </li><li data-key="no means yes||1997">
          <a href="/projects/no-means-yes"><span class="title">NO MEANS YES</span><br/>1997</a>
        </li><li data-key="vice/virtue|leerdam, the netherlands|1997">
          <a href="/projects/vice-virtue"><span class="title">VICE/VIRTUE</span><br/>Leerdam, The Netherlands, 1997</a>
        </li><li data-key="we interrupt this program...|atlanta, ga|1997">
          <a href="/projects/we-interrupt-this-program"><span class="title">WE INTERRUPT THIS PROGRAM...</span><br/>Atlanta, GA, 1997</a>
        </li><li data-key="x,y|kobe, japan|1997">
          <a href="/projects/xy"><span class="title">X,Y</span><br/>Kobe, Japan, 1997</a>
        </li><li data-key="fourth window|forum 38, nos. 1-2 (may 1995), on pages 25, 53 and 81|1996">
          <a href="/projects/fourth-window"><span class="title">FOURTH WINDOW</span><br/>Forum 38, Nos. 1-2 (May 1995), on pages 25, 53 and 81, 1996</a>
        </li><li data-key="indigestion|brussels, belgium|1996">
          <a href="/projects/indigestion"><span class="title">INDIGESTION</span><br/>Brussels, Belgium, 1996</a>
        </li><li data-key="jump cuts|san jose, ca|1996">
          <a href="/projects/jump-cuts"><span class="title">JUMP CUTS</span><br/>San Jose, CA, 1996</a>
        </li><li data-key="monkey business class|premiered in copenhagen, denmark|1996">
          <a href="/projects/monkey-business-class"><span class="title">MONKEY BUSINESS CLASS</span><br/>Premiered in Copenhagen, Denmark, 1996</a>
        </li><li data-key="moving target|premiered in charleroi, belgium|1996">
          <a href="/projects/moving-target"><span class="title">MOVING TARGET</span><br/>Premiered in Charleroi, Belgium, 1996</a>
        </li><li data-key="pageant|johannesburg, south africa|1996">
          <a href="/projects/pageant"><span class="title">PAGEANT</span><br/>Johannesburg, South Africa, 1996</a>
        </li><li data-key="feed|new york, ny|1995">
          <a href="/projects/feed"><span class="title">FEED</span><br/>New York, NY, 1995</a>
        </li><li data-key="overexposed|los angeles, ca|1995">
          <a href="/projects/overexposed"><span class="title">OVEREXPOSED</span><br/>Los Angeles, CA, 1995</a>
        </li><li data-key="soap bar||1994">
          <a href="/projects/soap-bar"><span class="title">SOAP BAR</span><br/>1994</a>
        </li><li data-key="bad press|san francisco, ca|1993">
          <a href="/projects/bad-press"><span class="title">BAD PRESS</span><br/>San Francisco, CA, 1993</a>
        </li><li data-key="case # 00-17164/003841983|new york, ny|1993">
          <a href="/projects/case"><span class="title">CASE # 00-17164/003841983</span><br/>New York, NY, 1993</a>
        </li><li data-key="his/hers ||1993">
          <a href="/projects/his-hers"><span class="title">HIS/HERS </span><br/>1993</a>
        </li><li data-key="soft sell|new york, ny|1993">
          <a href="/projects/soft-sell"><span class="title">SOFT SELL</span><br/>New York, NY, 1993</a>
        </li><li data-key="battery maritime building|new york, ny|1992">
          <a href="/projects/battery-maritime"><span class="title">BATTERY MARITIME BUILDING</span><br/>New York, NY, 1992</a>
        </li><li data-key="loophole|chicago, il|1992">
          <a href="/projects/loophole"><span class="title">LOOPHOLE</span><br/>Chicago, IL, 1992</a>
        </li><li data-key="pleasure/pain||1991">
          <a href="/projects/pleasure-pain"><span class="title">PLEASURE/PAIN</span><br/>1991</a>
        </li><li data-key="slow house|long island, ny|1991">
          <a href="/projects/slow-house"><span class="title">SLOW HOUSE</span><br/>Long Island, NY, 1991</a>
        </li><li data-key="tourisms: suitcase studies|minneapolis, mn|1991">
          <a href="/projects/tourisms-suitcase-studies"><span class="title">TOURISMS: SUITCASE STUDIES</span><br/>Minneapolis, MN, 1991</a>
        </li><li data-key="para-site|new york, ny|1989">
          <a href="/projects/para-site"><span class="title">PARA-SITE</span><br/>New York, NY, 1989</a>
        </li><li data-key="vanity chair|n/a|1988">
          <a href="/projects/vanity-chair"><span class="title">VANITY CHAIR</span><br/>N/A, 1988</a>
        </li><li data-key="rotary notary and his hot plate|premiered in philadelphia, pa|1987">
          <a href="/projects/rotary-notary"><span class="title">ROTARY NOTARY AND HIS HOT PLATE</span><br/>Premiered in Philadelphia, PA, 1987</a>
        </li><li data-key="memory theater of giulio camillo |premiered in new york, ny|1986">
          <a href="/projects/memory-theater"><span class="title">MEMORY THEATER OF GIULIO CAMILLO </span><br/>Premiered in New York, NY, 1986</a>
        </li><li data-key="withdrawing room|san francisco, ca|1986">
          <a href="/projects/withdrawing-room"><span class="title">WITHDRAWING ROOM</span><br/>San Francisco, CA, 1986</a>
        </li><li data-key="american mysteries|premiered in new york, ny|1984">
          <a href="/projects/american-mysteries"><span class="title">AMERICAN MYSTERIES</span><br/>Premiered in New York, NY, 1984</a>
        </li><li data-key="plywood house|briar cliff manor, ny|1981">
          <a href="/projects/plywood-house"><span class="title">PLYWOOD HOUSE</span><br/>Briar Cliff Manor, NY, 1981</a>
        </li><li data-key="traffic|new york, ny|1981">
          <a href="/projects/traffic"><span class="title">TRAFFIC</span><br/>New York, NY, 1981</a>
        </li><li data-key="nicotine/caffeine table with orbiting ashtray||">
          <a href="/projects/nicotine-caffeine-table"><span class="title">NICOTINE/CAFFEINE TABLE WITH ORBITING ASHTRAY</span><br/></a>
        </li><li class="null-set">No results</li>
      </ul>
    </div>
  </nav>

  <div id="menu">
    <ul class="categories">
      <li><a href="/categories/art">art</a></li><li><a href="/categories/commercial">commercial</a></li><li><a href="/categories/cultural">cultural</a></li><li><a href="/categories/landscape">landscape</a></li><li><a href="/categories/masterplan">masterplan</a></li><li><a href="/categories/media+tech">media/tech</a></li><li><a href="/categories/objects">objects</a></li><li><a href="/categories/performance">performance</a></li><li><a href="/categories/residential">residential</a></li>
    </ul>

    <ul class="boxes">
      <li><a href="/news">News</a></li>
      <li><a href="/projects/info">About</a></li>
    </ul>

    <div class="contact">
      <p>601 W. 26th Street, Suite 1815<br/>New York, NY 10001</p>
      <ul class="boxes">
        <li><a href="/contact">Contact</a></li>
      </ul>
    </div>
  </div>


  

  <script src="/lib/js/dsr.js"></script>

</body>
</html>

