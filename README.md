# Jr_s_World_3d

## Hi guys.I'll try to make a pretty complete game prototype based on the [SkinnyDev](https://www.youtube.com/@skinnydev) youtube channel's [Chick Wick Game Tutorial](https://www.youtube.com/watch?v=KZ5V9xIwwcE) tutorial video.I'd like to share this process with you in as much detail as possible.Stay Tune!🎮
[SkinnyDev Github](https://github.com/ttayfunylmz)



<table>
  <tr>
    <td style="vertical-align: top; width: 30%;">
     <p>Before we start making our game, we have to make a few preparations.It is useful to install a few packages that we need later on.</p>
      <p>🕹️ Now find the  <b><i>“Package Manager”</i></b>window and start installing the packages I have listed.</p>
      <p>📃<b><i>2D Sprite</i></b> (For UI designs)</p>
      <p>📃<b><i>Cinemachine</i></b> (For easier camera control)</p>
      <p>📃<b><i>DOTween (HOTween v2)</i></b> (Install this from <a href= "https://assetstore.unity.com/packages/tools/animation/dotween-hotween-v2-27676">Unity Asset Store</a>)(This asset will help you with animations :))</p>
      <p>📃<b><i>Chick Wick Starter Pack</i></b><a href= "https://drive.google.com/drive/folders/15DY8UgCzVvaTGZNGiLuNTSS2tC8R18rw"> Drive Link</a> (You can import this package by grabbing into your project or you can click on the <b><i>"Assets" -> "Import Package" -> "Custom Package" and select the package.Now you can use this package in your game :) </i></b>)</p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td>
       <img src="https://github.com/Ozlem-goksun/Jr_s_World_3d/blob/main/Tut/step1.png" alt="step1" style="max-width: 50%; height: auto;">
      <p>🕹️ Don't forget remove Physic / Physic2D modules from DOTween package 'cause we won't need them.</p>
       <img src="https://github.com/Ozlem-goksun/Jr_s_World_3d/blob/main/Tut/step2_DOTween.gif" alt="step2" style="max-width: 50%; height: auto;">
    </td>
  </tr>
</table>

  ## <p><i>So let's get started💥.</i></p> 

  <table>
    <tr>
      <td>
        <p>🕹️ Now drag and add your player from your <b><i>“Project”</i></b> tab to the <b><i>“Hierarchy”</i></b> tab. You can create an empty object in the “Hierarchy” window and place your player under it, your project will be more organized:)</p>
        <p>🕹️ After doing this, click on your prefab model and follow the <b><i>“Prefab”</i></b> -> <b><i>“Unpack Completely”</i></b> steps.</p>
        <p>🕹️ Great! Your model is now a <b><i>GameObject</i></b>.</p>
        <img src = "https://github.com/Ozlem-goksun/Jr_s_World_3d/blob/main/Tut/step3-Add%20player.png" alt = "step3">
        <p><i>"I used my own model for this, but you can use the model from the file you just downloaded.I may use different assets during this project, but don't worry, there will be differences that you can handle.If you get stuck, you can contact me or get information from the video source with the link I shared at the beginning."</i></p>
        <p></p>
        <p>🕹️ Now add a ground to the scene on which your player can stand, for this you can click on the <b><i>"Hierarcy"</i></b> window and go to <b><i>“3D Object”</i></b> -> <b><i>“Plane”</i></b>.</p>
        <p>🕹️ </p>
      </td>
    </tr>
  </table>
