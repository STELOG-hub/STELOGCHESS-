<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>App Name</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(to bottom, #6b4eff, #d48fff);
      color: white;
      text-align: center;
    }
    .header {
      display: flex;
      justify-content: space-between;
      padding: 10px 20px;
    }
    .logo {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      background: white;
      margin: 0 auto;
    }
    .app-name {
      font-size: 32px;
      font-weight: bold;
      margin: 10px 0;
    }
    .info {
      font-size: 24px;
      margin: 5px 0;
    }
    .social-media {
      margin: 10px 0;
    }
    .video-thumbnail {
      margin: 30px auto;
      width: 80%;
      height: 200px;
      background: rgba(255,255,255,0.3);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 24px;
      font-weight: bold;
    }
    .nav {
      position: fixed;
      bottom: 0;
      width: 100%;
      background-color: rgba(255,255,255,0.1);
      display: flex;
      justify-content: space-around;
      padding: 15px 0;
      font-size: 18px;
    }
    .nav div {
      cursor: pointer;
    }
    
    .chess-board { border-spacing: 0; border-collapse: collapse; }
            .chess-board th { padding: .5em; }
            .chess-board td { border: 1px solid; width: 2em; height: 2em; }
            .chess-board .light { background: #eee; }
            .chess-board .dark { background: #000; }
  </style>
</head>
<body>
  <div class="header">
    <div>
     <!-- Inside .header -->
<div>
  <a href="#" id="signInBtn">sign in</a>
</div>

<!-- Sign In Modal -->
<div class="modal" id="signInModal">
  <div class="modal-content">
    <span class="close">&times;</span>
    <h2>Sign In</h2>
    <form>
      <input type="text" placeholder="Username" required>
      <input type="password" placeholder="Password" required>
      <button type="submit">Log In</button>
    </form>
  </div>
</div>
   </div>
    <div></div>
  </div>
   <div class="logo">
   <img src="https://drive.google.com/file/d/1V8zIYT3XJq7duGRxoDkdo8PD77W6Axya/view?usp=drivesdk" alt="WEB LOGO"> </div>
  <div class="app-name">Stelogchess</div>
  <div class="info">Info</div>  <div class="social-media">
    <div>  
    <a href="https://youtube.com/@stemug21?si=K00b_WvBhOJBmyq0">Click here to view my youtube channel </a></div>
    <div>And other logo for social media</div>
  </div>  <div class="video-thumbnail">
    Thumbnail and video space
  </div>  <div class="nav">
    <div>Home</div>
    <div>Opening</div>
    <div>Insights</div>
    <div>Training</div>
  </div>
  
         <style>
            
        </style>
              <table class="chess-board">
            <tbody>
                <tr>
                    <th></th>
                    <th>a</th>
                    <th>b</th>
                    <th>c</th>
                    <th>d</th>
                    <th>e</th>
                    <th>f</th>
                    <th>g</th>
                    <th>h</th>
                </tr>
                <tr>
                    <th>8</th>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                </tr>
                <tr>
                    <th>7</th>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                </tr>
                <tr>
                    <th>6</th>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                </tr>
                <tr>
                    <th>5</th>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                </tr>
                <tr>
                    <th>4</th>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                </tr>
                <tr>
                    <th>3</th>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                </tr>
                <tr>
                    <th>2</th>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                </tr>
                <tr>
                    <th>1</th>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                    <td class="dark"></td>
                    <td class="light"></td>
                </tr>
            </tbody>
        </table>
</body>
</html>