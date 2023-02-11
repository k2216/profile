# profile
profile to site
<!DOCTYPE html>
<html>
  <head>
    <title>自己紹介ページ</title>
    <%= csrf_meta_tags %>
    <meta charset="UTF-8">
    <%= stylesheet_link_tag    'application', media: 'all', 'data-turbolinks-track': 'reload' %>
    <%= javascript_include_tag 'application', 'data-turbolinks-track': 'reload' %>
  </head>
<body>
<header>
        <div class="top">
            <%= image_tag("profile.jpg" , :id => "icon") %>
            <span id="myname">迫　裕樹</span>
            <nav>
                <ul>
                    <li><a href="">Home</a></li>
                    <li><a href="https://twitter.com/home" target="_blank">Twitter</a></li>
                    <li><a href="https://www.instagram.com/" target="_blank">Instagram</a></li>
                    <li><a href="https://www.facebook.com/" target="_blank">Facebook</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <div class="container">
        <h2>自己紹介</h2>
        <div class="profile">
            <p>中高生から社会人まで，今まで3000人以上にプログラミングを教えながら, <br>
               フリーランスとして活動する学生エンジニアブロガー．<br>
              月18万回読まれる当ブログ，ロボット・IT雑食日記を運営中．</p>
            <hr>
            <p>1996年8月20日生まれ</p>
            <p>京都府宇治市出身</p>
            <p>立命館大学理工学部ロボティクス学科</p>
        </div>
    </div>
    <footer>
        <p>&copy; Yuki Sako</p>
    </footer>
  </body>
  </html>
