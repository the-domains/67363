---
inFeed: true
description: >-
  could be useful for certain sites, just a pity we can’t go full page width..
  but all in css, and no need to upload any javascript file.. just scroll up or
  down…
dateModified: '2018-05-22T13:29:15.261Z'
datePublished: '2018-05-22T13:29:15.953Z'
title: Parallax on the Grid
author: []
publisher: {}
via: {}
hasPage: true
sourcePath: _posts/2017-08-22-parallax-on-the-grid.md
starred: false
datePublishedOriginal: '2017-08-22T15:18:05.306Z'
url: parallax-on-the-grid/index.html
_type: Article

---
# Parallax on the Grid

could be useful for certain sites, just a pity we can't go full page width.. but all in css, and no need to upload any javascript file.. just scroll up or down...

<iframe src="https://the-grid.github.io/ed-userhtml/?g=eJy1Vd1u0zAUvu9THE0CtmlJ2uwHFkqFNkAaYuNi3HB5EjuJmWOH2Fla0CReg9fjSThOUsbaUgbbqjZtfX6_73y2x8bOJJ8M_EQri0LxCr4OAAqceo1gNo_g8GBYTp-3a1UmVARDwNpqt5JSjJdiIeQsAg_LUnLPzIzlxQ4cSaEuTjE5b_-_Ic8dMKiMZ3gl0ueDq0GwDS_u8KL656-PP5y8Pzsf3CUPbAcDwxMrtPILzWrJI4nGekkuJOvJcMC9WFurC8Lvmr8ZAXm4ynOvZ-4uPPXRRnzhEey2CZeql38t3oWPDn5barjIcutyrgJU_jsJrYS4sq17iYwJlXVtrPQusUIpcdq6530zB8O-6xiTi6zStWJeqY1wgRHsDx-5z4K94iVHilW6_7lgR2sxyQvqLIJUTDlbsHfcJPqSV-vazEdtp4mWuoqgymLcDPf3d-D6MfSfbS0wvvesg0ND5t4SyBtzeOrmMNfKf0rF8qn1UIqMyEoIsEPUr5ocmW7c7h3CyM2kRTCkrru3H26tQe914H9jTRSYEcC6kpsbubWliYKgaRo_jgXGJIUiMDoRKIuA8UInOk05H_mfymxjbZ3wPuqEf6-zex91dq_rDF4WnAkEyg6oGGwWtFn6E7Sd91ZbcPWxcVMyYSeOq2X3ctk7HP7Je0m5N-IO-6PgrofTFWFfA729PFZBX9_daH7n3Ed746C_4wbjvgdI6HAzLzbmtM5buVb7xoSCx0xczl1_XY-thWz5aNKJYBzQT-cdkPvEVeuK_Llef07eokY4eUsKFRyOc1QQUamwN5WTJ8dteRAGECSqrCYBg1AgrOEy9X3_yTgo_62zZSbCWzHx-GFJeIWXgsG7mUryRRKOagv8kiviIEYGSV2CTiH5RU3MLZ2CYB1_Ss8NaJ1afTjjDXzU1QXkaCCr6O6ABp1_qqve95543L2lotgD6-mUZ8TEaU1NSTlbZPPkx7fvtIs_18LO4cMJcaIVGSyRCRzNDFhF-45udyhmcIRC8hmZDRhbobvLdiCmqfS5Mm6hNpyB1aRMl65bN1bQkzLanNOXsY4r64bXYJu7LtdR_xNDWHeJ" height="700" style=""></iframe>

code after the break..

---

    <style>
    .container {
      max-width: 960px;
      margin: 0 auto;
      font-family: -apple-system, BlinkMacSystemFont, sans-serif;
    }
    /* ============================================================
      SECTIONS
    ============================================================ */
    section.module:last-child {
      margin-bottom: 0;
    }
    section.module h2 {
      margin-bottom: 40px;
      font-family: -apple-system, BlinkMacSystemFont, sans-serif;
      font-size: 30px;
    }
    section.module p {
      margin-bottom: 40px;
      font-size: 16px;
      font-weight: 300;
    }
    section.module p:last-child {
      margin-bottom: 0;
    }
    section.module.content {
      padding: 40px 0;
    }
    section.module.parallax {
      height: 600px;
      background-position: 50% 50%;
      background-repeat: no-repeat;
      background-attachment: fixed;
      background-size: cover;
    }
    section.module.parallax h1 {
      color: rgba(255, 255, 255, 0.8);
      font-size: 48px;
      line-height: 600px;
      font-weight: 700;
      font-fmily: -apple-system, BlinkMacSystemFont, sans-serif;
      text-align: center;
      text-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    }
    section.module.parallax-1 {
      background-image: url("https://www.bbiab.com/socialm/democoffee1.jpg");
    }
    section.module.parallax-2 {
      background-image: url("https://www.bbiab.com/socialm/democoffee2.jpg");
    }
    section.module.parallax-3 {
      background-image: url("https://www.bbiab.com/socialm/democoffee3.jpg");
    }
    
    @media all and (min-width: 600px) {
      section.module h2 {
        font-size: 42px;
      }
      section.module p {
        font-size: 20px;
      }
      section.module.parallax h1 {
        font-size: 96px;
        font-family: -apple-system, BlinkMacSystemFont, sans-serif;
      }
    }
    @media all and (min-width: 960px) {
      section.module.parallax h1 {
        font-size: 160px;
        font-family: -apple-system, BlinkMacSystemFont, sans-serif;
      }
    }
    </style>
    
    <section class="module parallax parallax-1">
      <div class="container">
        <h1>coffee</h1>
      </div>
    </section>
    
    <section class="module content">
      <div class="container">
        <h2>Jackie Chan :</h2>
        <p>'Coffee is a language in itself...'</p>
      </div>
    </section>
    
    <section class="module parallax parallax-2">
      <div class="container">
        <h1>&</h1>
      </div>
    </section>
    
    <section class="module content">
      <div class="container">
        <h2>David Lynch :</h2>
        <p>'But even a bad cup of coffee is better than no coffee at all. New York has great water for coffee...'</p>
      </div>
    </section>
    
    <section class="module parallax parallax-3">
      <div class="container">
        <h1>code</h1>
      </div>
    </section>
    
    <section class="module content">
      <div class="container">
        <h2>Megan Mullally :</h2>
        <p>'I’ll quit coffee. It won’t be easy drinking my Bailey’s straight, but I’ll get used to it. It’ll still be the best part of waking up...'</p>
      </div>
    </section>