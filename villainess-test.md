<!DOCTYPE html>
<style>
  @font-face {
    font-family: 'Lora', serif;
    font-optical-sizing: auto;
    src: url('https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400..700;1,400..700&display=swap" rel="stylesheet') format('truetype');
    font-weight: 700;
    font-style: normal;
  }
  
  body {
    background-image: url("https://cdn.discordapp.com/attachments/516160284428337152/1516575134721376277/bg_draft.png?ex=6a332428&is=6a31d2a8&hm=f48a30e9a3d2315de53819a260deba7a935e8bb0a353afe7a92b5ef17a843698");
    background-repeat: no-repeat;
    background-position:center;
    background-attachment: fixed;
  }
  
  p, ul, h1, h2, h3, hr, .titleImage, a {
    color: rgba(190, 160, 30);
  }
  
  a {
    display:block;
    width: 1286px;
    height: 78px;
    line-height:78px;
    text-align:center;
    margin:auto;
    max-height:100%;
    max-width:100%;
  }
  
  a:hover {
    color: rgba(200, 140, 30);
  }
  
  hr {
    background:transparent;
    border: 0.0rem solid #fff;
    border-radius: 0rem;
    width: 20rem;
    opacity: 1.0;
  }
  
  ul {
    list-style: none;
    margin-left: 10px;
    margin-right: 40px;
  }
  
  ul > li {
    background: url("https://cdn.discordapp.com/attachments/516160284428337152/1516546970204901599/check_selected_foreground.png?ex=6a3309ed&is=6a31b86d&hm=6b159bf9653b6c96d08aa079f8113e55e5d37a8affda620f6cdbc50f4f207cb5") no-repeat left center;
    padding-left: 30px;
    padding-top: 7px;
    padding-bottom: 7px;
    margin-left: 30px;
    margin-right: 30px;
  }
  
  .titleImage {
    width: 298px;
    height: 74px;
    line-height:74px;
    background-image: url("https://cdn.discordapp.com/attachments/516160284428337152/1516527466318135427/namebox.png?ex=6a32f7c3&is=6a31a643&hm=769eff208e8d4882af92ae00240ee29e63bbfeaec237ad96a62e0029049afe53&g");
    text-align:center;
    font-size: 40px;
  }
  
  .characterTitle {
    width: 414px;
    height:309px;
    line-height:32px;
    background-image: url("https://cdn.discordapp.com/attachments/516160284428337152/1516867834708230394/title.png?ex=6a3434c1&is=6a32e341&hm=2ddd2cb29b4a3ba6ef58d2ae71e02c286658584ddd308a9c48aebad155819c54&") no-repeat;
    text-align:center;
    font-size:16px;
  }
  
  .characterFrame {
    width: 1500px;
    height:1980px;
    line-height:32px;
    background-image: url("https://cdn.discordapp.com/attachments/516160284428337152/1516619101924098159/avatar_frame_1.png?ex=6a334d1b&is=6a31fb9b&hm=ea89794e7043fbb0c0facb2fcdf2e5aeb259ecb502a6ec25d9b510d7e6989fa6") no-repeat;
    text-align:center;
    font-size:16px;
  }
  
  .testImage {
    width: 298px;
    height:74px;
    line-height:32px;
    background-image: url("https://cdn.discordapp.com/attachments/516160284428337152/1516531569345564843/slot_idle_background.png?ex=6a32fb95&is=6a31aa15&hm=c3733787af3d9fcaeeb23a14984b42aa1bb461b453cc454bc39dccb6ce071f55") no-repeat center;
    text-align:center;
    font-size:16px;
  }
  
  div {
    margin:auto;
  }
  
  .container {
    width:800px;
    margin:auto;
  }
  
  h1, h2, h3 {
    text-align:center;
  }
  
  input {
    max-height:100%;
    max-width:100%;
  }
  
  img {
    display:block;
    margin:auto;
    max-height:100%;
    max-width:100%;
    border:none;
  }
  
  .imageButton {
    margin:20px;
  }
  
  .linkButton {
    width: 684px;
    height: 46px;
    line-height:46px;
    background: url("https://cdn.discordapp.com/attachments/516160284428337152/1516867834976927895/button.png?ex=6a3434c1&is=6a32e341&hm=c7deee57011967a03805851a38f2bc3770af4f453d7a744badface4727571c05&") no-repeat center;
    text-align:center;
    font-size: 20px;
    background-size: contain;
    margin-top:10px;
  }
  
  .linkButton:hover {
    background: url("https://cdn.discordapp.com/attachments/516160284428337152/1516867834439929887/buttonhover.png?ex=6a3434c1&is=6a32e341&hm=1a113f1c8023d5aa0bd6b3c5474c2f7b2a0010d2358a504f69f352caba82afb3&") no-repeat center;
    background-size: contain;
  }
  
  .grid-container {
    display: grid;
    grid-template-columns: 50% 50%;
    margin:auto;
    gap:10px;
    padding-top:30px;
  }
  
  .group {
    background-color: rgba(30, 30, 30);
    padding: 20px;
    margin: 30px;
    border: 2px solid rgba(190, 160, 30);
  }
  
  .screenshot {
    margin-top: 20px;
    border: 2px solid rgba(190, 160, 30);
  }
  
</style>

<body>
  <div class="container">
    <div class="group">
      <img src="https://cdn.discordapp.com/attachments/516160284428337152/1516531569345564843/slot_idle_background.png?ex=6a32fb95&is=6a31aa15&hm=c3733787af3d9fcaeeb23a14984b42aa1bb461b453cc454bc39dccb6ce071f55"/>
      <div class="titleImage">Tagline</div>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam eget sapien sapien. Curabitur in metus urna. In hac habitasse platea dictumst. Phasellus eu sem sapien, sed vestibulum velit. Nam purus nibh, lacinia non faucibus et, pharetra in dolor. Sed iaculis posuere diam ut cursus.</p>
      <hr>
      <div>
        <h3 class="h2">Features</h3>
        <ul>
          <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam eget sapien sapien.</li>
          <li>Curabitur in metus urna.</li>
        </ul>
      </div>
    </div>
    <div class="group">
      <div class="titleImage">Characters</div>
      <div class="grid-container">
        <div>
          <img src="https://cdn.discordapp.com/attachments/516160284428337152/1516867834708230394/title.png?ex=6a3434c1&is=6a32e341&hm=2ddd2cb29b4a3ba6ef58d2ae71e02c286658584ddd308a9c48aebad155819c54&"/>
          <img src="https://cdn.discordapp.com/attachments/516160284428337152/1516619101924098159/avatar_frame_1.png?ex=6a334d1b&is=6a31fb9b&hm=ea89794e7043fbb0c0facb2fcdf2e5aeb259ecb502a6ec25d9b510d7e6989fa6"/>
        </div>
        <div>
          <img src="https://cdn.discordapp.com/attachments/516160284428337152/1516867834708230394/title.png?ex=6a3434c1&is=6a32e341&hm=2ddd2cb29b4a3ba6ef58d2ae71e02c286658584ddd308a9c48aebad155819c54&"/>
          <img src="https://cdn.discordapp.com/attachments/516160284428337152/1516619101924098159/avatar_frame_1.png?ex=6a334d1b&is=6a31fb9b&hm=ea89794e7043fbb0c0facb2fcdf2e5aeb259ecb502a6ec25d9b510d7e6989fa6"/>
        </div>
      </div>
    </div>
    <div class="group">
      <div class="titleImage">Screenshots</div>
      <div>
        <img class="screenshot" src="https://cdn.discordapp.com/attachments/516160284428337152/1516558035441680584/Screenshot_2026-06-16_151830.png?ex=6a33143b&is=6a31c2bb&hm=e50ab964f09f44533f32247bc3c0915a723ccbaf24dd1805c53e831f4852c8e7">
        <img class="screenshot" src="https://cdn.discordapp.com/attachments/516160284428337152/1516558035441680584/Screenshot_2026-06-16_151830.png?ex=6a33143b&is=6a31c2bb&hm=e50ab964f09f44533f32247bc3c0915a723ccbaf24dd1805c53e831f4852c8e7">
        <img class="screenshot" src="https://cdn.discordapp.com/attachments/516160284428337152/1516558035441680584/Screenshot_2026-06-16_151830.png?ex=6a33143b&is=6a31c2bb&hm=e50ab964f09f44533f32247bc3c0915a723ccbaf24dd1805c53e831f4852c8e7">
      </div>
    </div>
    <div class="group">
      <div class="titleImage">Links</div>
      <a class="linkButton" href="https://www.w3schools.com/html">
      HTML
      </a>
      <a class="linkButton" href="https://www.w3schools.com/css">
      CSS
      </a>
      <a class="linkButton" href="https://www.w3schools.com/javascript">
      Javascript
      </a>
    </div>
  </div>
</body>
