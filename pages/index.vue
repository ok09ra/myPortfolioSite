<template>
<div>
  <div id="TopSection">
    <h1>WELCOME</h1>
    <p id= "backgroundImg">
      <video src="~assets/mp4/head.mp4"  loop autoplay muted></video>
    </p>
  </div>

  <div id="IntroductionSection">
    <p class="ImageLeft">
      <img src="~assets/jpg/myIcon.jpg" data-aos="slide-up" data-aos-delay="300">
    </p>
    <div class="MidBackgroundLeft"></div>
    <div id="SelfIntroduction">
      <h2 id="Myname" data-aos="flip-down" data-aos-delay="300">Sota Okuda</h2>
      <div id="MyPortfolioLink" data-aos="fade" data-aos-delay="800">
        <a href="https://twitter.com/EnOkud"><img src="~assets/svg/twitter.svg"></a>
        <a href="https://www.facebook.com/sotaokudapn"><img src="~assets/svg/facebook.svg"></a>
        <a href="https://github.com/ok09ra"><img src="~assets/svg/github.svg"></a>
      </div>
      <div id="CurrentPositions" data-aos="flip-left" data-aos-delay="300">
        <h4>Current Position</h4>
        <p>早稲田大学 先進理工学部 電気・情報生命工学科 B3<br>合成生物学研究室</p>
        <p>SecHack 365 2021 思索駆動コース トレーニー</p>
        <p>iGEM WASEDA IT TEAM</p>
        <p>COUGER株式会社 QAエンジニア インターン</p>
        <p>LITE株式会社 エンジニア</p>
        <p>Beyond 2020 NEXT project 幹事長補佐</p>
        <p>早稲田大学グローバル科学知融合研究所<br>SDGs教育カリキュラム作成ワーキンググループ<br>学生統括</p>
      </div>
    </div>

  </div>

  <div id="EngineeringSection">
    <p class="ImageRight">
      <img src="~assets/gif/coding.gif">
    </p>
    <div class="MidBackgroundRight"></div>

    <div id="EngineerIntroduction">
      <h2 class="SectionTitleRight" data-aos="flip-down" data-aos-delay="300">Engineering</h2>
      <div id="EngineeringSkills" data-aos="fade-up" data-aos-delay="300">
        <div class="Skill">
          <img  src="~assets/svg/python.svg">
          <h3>Python</h3>
          <p class="SkillRate">★★★★★</p>
          <p class="AddInfo">TensorFlow/Pytorch<br>Django/Flask<br>(業務利用2年)</p>
        </div>

        <div class="Skill">
          <img  src="~assets/svg/nodejs.svg">
          <h3>Node.js</h3>
          <p class="SkillRate">★★★</p>
          <p class="AddInfo">webpack/babel/express<br>外部API,chatbot開発<br>(業務利用１年)</p>
        </div>

        <div class="Skill">
          <img  src="~assets/svg/unity.svg">
          <h3>Unity</h3>
          <p class="SkillRate">★</p>
          <p class="AddInfo">ゲーム開発初心者<br>(業務利用)</p>
        </div>

        <div class="Skill">
          <img  src="~assets/svg/go.svg">
          <h3>Go言語</h3>
          <p class="SkillRate"></p>
          <p class="AddInfo">バックエンド開発<br>スマートコントラクト開発<br>(業務利用これから)</p>
        </div>
        
        <div class="Skill">
          <img  src="~assets/svg/Nginx.svg">
          <h3>Nginx</h3>
          <p class="SkillRate"></p>
          <p class="AddInfo">バックエンド開発<br>(業務利用これから)</p>
        </div>

        <div class="Skill">
        </div>

        <div class="Skill">
          <img  src="~assets/svg/clang.svg">
          <h3>c言語</h3>
          <p class="SkillRate">★★</p>
          <p class="AddInfo">ポインターの意味がわかる<br>簡単なアプリ実装<br>(趣味レベル)</p>
        </div>

        
        <div class="Skill">
          <img  src="~assets/svg/raspberry-pi.svg">
          <h3>Raspberry Pi</h3>
          <p class="SkillRate">★★</p>
          <p class="AddInfo">初めてのMy PC<br>電気回路をデジタル制御<br>(趣味レベル)</p>
        </div>

        <div class="Skill">
          <img  src="~assets/svg/julia.svg">
          <h3>julia</h3>
          <p class="SkillRate">★</p>
          <p class="AddInfo">興味を持って<br>少しドキュメントを読んだ<br>(趣味歴2カ月)</p>
        </div>

        <div class="Skill">
        </div>

        <div class="Skill">
          <img  src="~assets/svg/tensorflow.svg">
        </div>

        <div class="Skill">
          <img  src="~assets/svg/django.svg">
        </div>

        <div class="Skill">
          <img  src="~assets/svg/vue.svg">
        </div>

        <div class="Skill">
          <img  src="~assets/svg/nuxt.svg">
        </div>
      </div>
    </div>

  </div>

  <div id="SocialSection">
    <p class="ImageLeft">
      <img src="~assets/png/asahi-sdgs.png" data-aos="slide-up" data-aos-delay="300">
    </p>
    <div class="MidBackgroundLeft"></div>
    <h2 class="SectionTitleLeft" style="font-size:7vmax" data-aos="flip-down" data-aos-delay="300">Social Contributions</h2>
    <h3>
      早稲田大学グローバル科学知融合研究所で
      <br>SDGs、持続可能な社会についての教材開発、小学生への出前講義により
      <br>次世代人材育成の一端を担う活動に取り組んでいます。
    </h3>
    <h4>★我々の活動を毎日新聞様に取材いただき2021/8/17日付朝刊に掲載されました。<a href="https://mainichi.jp/articles/20210817/ddm/013/040/035000c">[こちら]</a></h4>

  </div>

  <div id="ResearchSection">
    <p class="ImageRight">
      <img src="~assets/jpg/lab.jpg" data-aos="slide-up" data-aos-delay="300">
    </p>
    <div class="MidBackgroundRight" style="background: linear-gradient(to right,rgba(0,0,0,1),rgba(0,0,0,1) 60%, rgba(0,0,0,0));"></div>
    <h2 class="SectionTitleRight" data-aos="flip-down" data-aos-delay="300">Research</h2>
    <h3>研究テーマ構築中　乞うご期待</h3>
  </div>
</div>
</template>
