# Gabriel Vieira
Software and Firmware Engineer.

> ___Está vendo? Uma única pessoa pode fazer uma grande diferença, é o que eu acho. - Stan Lee___




<style>
  .doom-fake input { display: none; }
  .doom-fake img { display: none; max-width: 100%; }
  .doom-fake label {
    margin: 5px;
    padding: 10px 20px;
    background: red;
    color: white;
    font-weight: bold;
    cursor: pointer;
    border-radius: 5px;
  }
  #frame1:checked ~ .img1,
  #frame2:checked ~ .img2,
  #frame3:checked ~ .img3 {
    display: block;
  }
</style>

<div class="doom-fake">
  <input type="radio" name="doom" id="frame1" checked>
  <input type="radio" name="doom" id="frame2">
  <input type="radio" name="doom" id="frame3">

  <label for="frame1">👀 Andar</label>
  <label for="frame2">💥 Atirar</label>
  <label for="frame3">☠️ Monstro</label>

  <div>
    <img src="https://i.imgur.com/0p8jtIc.png" class="img1">
    <img src="https://i.imgur.com/jrhIH3S.png" class="img2">
    <img src="https://i.imgur.com/WcvdKgf.png" class="img3">
  </div>
</div>
