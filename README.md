# jessica-anggelina
&lt;html>   &lt;body>     &lt;h1>Hai Cantik!&lt;/h1>     &lt;img src="https://c.tenor.com/Z8ezUHZzcLoAAAAC/love.gif" />     &lt;h1>Maukah kamu menjadi pacarku?&lt;/h1>     &lt;button id="btn_mau" onclick="alert('I LOVE YOU')">Mau&lt;/button>&amp;nbsp;     &lt;button id="btn_gamau" onclick="gamau(this)" style="position: absolute">       Gamau     &lt;/button>   &lt;/body>   &lt;script>     function gamau(id) {       var mau = document.getElementById("btn_mau");       var i = Math.floor(Math.random() * 300) + 1;       var j = Math.floor(Math.random() * 100) + mau.offsetTop;       id.style.left = i + "px";       id.style.top = j + "px";     }   &lt;/script> &lt;/html>
