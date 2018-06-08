---
inFeed: true
description: >-
  I meant to so a simpler example using the polygon shape, but got sidetracked
  and ended up with this. The difference is we are using 2 images this time,
  floating left and right..
dateModified: '2018-06-08T13:25:23.040Z'
datePublished: '2018-06-08T13:25:23.727Z'
title: Shapes & Words II
author: []
publisher: {}
via: {}
hasPage: true
sourcePath: _posts/2017-08-23-shapes-and-words-ii.md
starred: false
datePublishedOriginal: '2017-08-23T12:44:43.939Z'
url: shapes-and-words-ii/index.html
_type: Article

---
# Shapes & Words II

I meant to so a simpler example using the polygon shape, but got sidetracked and ended up with this. The difference is we are using 2 images this time, floating left and right..

The polygon shape allows us to basically create our own barriers to contain the words...

<iframe src="https://the-grid.github.io/ed-userhtml/?g=eJztVUuP4zYMvudX8BK4BWYcx7GdZCYzQLtogV301kPPik3bamTJkOQ8UEx_e0lFLqZAF9i5LxDENMmPj4-UfHD-pvB1kdZGeyE1_LUAuMjG90-wy7Lx-kzvPcqu909QrIPibbFIXS9GVNj694DiKwCAVhlB7wzg18cLHk_SP4Yoj2byTjb4BKNRt87oH6pqCdnyAar9Ejb03BZLqPhJ-jUbtlsSilmzjy558F2TsGUhJ_CahZKE4Mzh2LQj5w2jdrsl1UjCPiOBTXuClzmbyLkMzgSvsgiv8pii4lxVETXlPvqUrOGAJQWsShIKSrFlTUGlbjlgQQF3-SzMmv2s2VdRWGccMXsnZMsfnxe1kuPjKJjv73x9A19vcVktr-SHtjUgvmFdi-xO_6a8079Z3-nPqQNmjXiGNZebc3FVFPJsFpjrPI9jyIs4BtZsmJH1PrLPQrGZhRCH2Q9xyjiGDQUsi1hMyfAND2bHHK0j-0EIPsR1xSaaMm_E3bTdzVzPgwnsl9TNLkyRCtuxc8U-uyiEefCA99vocx8D_78Xv7bD30n8KIlvi8Mq3t6HRp6hVsK5lyRe5MkrLe57_b83dvJ6kEMHztYvSe_96J5Wq8vlkh6PUhzpOzCsnKmlUMPKWwyIdNRdEo_JSxKOSXI_RfTGp4hCrijV_6YMp-hjOQPkI0n5l_yGHgaEizghTCNovHrwBm5meoBenBFq07aIQB853yMMxmqpOxC6IYxu0JLamqnrg7mW_kbpfM8BLAUgN0IOUuNDwHxOlIIjkmUcb9AaG2AWnQfTwkCqqT5hw6Uo6b1CerSYJvA3fOqFVcZ7hF-sPDln9OFoYfV6_0_-4CZ0KL4xIIBcOaTzU9s-wwUTi6BJR-V0FoWHwHMKhGtkoxMPHVEhoDOmAR3od-AU4sg-jBZzSQ2OVLHDJoVPd3acUWd0IKg56schjNYcFQ6O0xnNEMUh20nNQeppDG19QWtv8DtK3aJq_tPST4MhqpkgPQ1ILDtQ03WyklJRa2zwgtKkaRqnNIgbs0vbzJetJSKFC_mj-2CI6LNQU4DBZw94pZlRvLqnDaLyNDUWJkgXNhXvzVXWwkujn8P8OMioUDheArrxL4HjUVrpCdbLugdJvNc1eVARVJl0tFRn2pPWKPKnko43cKLhRA-ghO4m2gL6NXiUxM0tsPIz6j8FrQ38aoU-KakX97X9B9Ojcbo" height="440" style=""></iframe>

code after the break..

---

    <style>
    .contain {
      width: 800px;
      height: 410px;
    }
    
    .shapeleft {
      width: 400px;
      height: 410px;
      float: left;
      -webkit-shape-outside: polygon(66% 0%, 69% 3%, 74% 6%, 76% 10%, 77% 14%, 76% 19%, 74% 23%, 71% 27%, 72% 31%, 75% 34%, 79% 37%, 84% 39%, 88% 41%, 90% 47%, 91% 52%, 89% 57%, 85% 60%, 79% 62%, 71% 63%, 64% 62%, 59% 60%, 54% 61%, 50% 65%, 48% 71%, 46% 77%, 45% 82%, 45% 87%, 45% 92%, 45% 96%, 45% 100%, 0% 100%, 0% 0%);
    clip-path: polygon(66% 0%, 69% 3%, 74% 6%, 76% 10%, 77% 14%, 76% 19%, 74% 23%, 71% 27%, 72% 31%, 75% 34%, 79% 37%, 84% 39%, 88% 41%, 90% 47%, 91% 52%, 89% 57%, 85% 60%, 79% 62%, 71% 63%, 64% 62%, 59% 60%, 54% 61%, 50% 65%, 48% 71%, 46% 77%, 45% 82%, 45% 87%, 45% 92%, 45% 96%, 45% 100%, 0% 100%, 0% 0%);
    }
    .shaperight {
      width: 400px;
      height: 410px;
      float: right;
      -webkit-shape-outside: polygon(40% 0%, 35% 3%, 31% 6%, 26% 9%, 23% 12%, 20% 16%, 20% 20%, 20% 24%, 22% 27%, 24% 31%, 22% 35%, 19% 39%, 19% 43%, 19% 46%, 21% 50%, 25% 52%, 30% 54%, 35% 55%, 39% 58%, 41% 62%, 41% 64%, 38% 68%, 37% 74%, 41% 78%, 45% 81%, 50% 82%, 56% 83%, 62% 84%, 65% 88%, 65% 92%, 64% 97%, 62% 100%, 100% 100%, 100% 0%);
    clip-path: polygon(40% 0%, 35% 3%, 31% 6%, 26% 9%, 23% 12%, 20% 16%, 20% 20%, 20% 24%, 22% 27%, 24% 31%, 22% 35%, 19% 39%, 19% 43%, 19% 46%, 21% 50%, 25% 52%, 30% 54%, 35% 55%, 39% 58%, 41% 62%, 41% 64%, 38% 68%, 37% 74%, 41% 78%, 45% 81%, 50% 82%, 56% 83%, 62% 84%, 65% 88%, 65% 92%, 64% 97%, 62% 100%, 100% 100%, 100% 0%);
    }
    </style>
    <div class='contain'>
      <div class='shapeleft'><img src='https://www.bbiab.com/socialm/treeleft.png' height='410px' width='400px'></div>
      <div class='shaperight'><img src='https://www.bbiab.com/socialm/treeright.png' height='410px' width='400px'></div>
      
      
    'Let me wake up next to you, have coffee in the morning and wander through the city with your hand in mine, and I'll be happy for the rest of my fucked up little life.' ~ Charlotte Eriksson<br /><br />'We want to do a lot of stuff; we're not in great shape. We didn't get a good night's sleep. We're a little depressed. Coffee solves all these problems in one delightful little cup.' ~ Jerry Seinfeld<br /><br />'Among the numerous luxuries of the table...coffee may be considered as one of the most valuable. It excites cheerfulness without intoxication; and the pleasing flow of spirits which it occasions...is never followed by sadness, languor or debility.' ~ Benjamin Franklin
    </div>