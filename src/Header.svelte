<script>
  	import { Router, Route, Link } from 'svelte-routing';
</script>
<header>
        <div class="logo">
          <img class="logo-img" src="https://downloader.disk.yandex.ru/preview/316983f474d11db64cba41a46d0e7186f1df1e7f5123595fa35167e1fdfc52f4/656f3584/9zHZpDC65yV6MVCZ3QpCqarClZ0lzo1vJR6jKCU2CDg4jD_lBn06jQiwKCeXBSQhuGS4c74HkWusFC0daZvfTQ%3D%3D?uid=0&filename=LOGO.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=0&tknv=v2&size=1920x931" alt="" />
        </div>
        <div class="button-content">
            <Router>
              <nav> 
                <button><Link to="/Home" >Главная</Link></button>
                <button ><Link to="/login" >Вход</Link></button>
              </nav>
            </Router>
        </div>
</header>
<style>

.logo {
  color: black;
}
.logo-img{
  height: 60px;
  width: auto;
}
header {
  background-color: #004913;
  color: #fff;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
}
.button-content{
    display: flex;
}
button {
  border-radius: 25px;
}

button:hover {
    opacity: 50%;
}

:global(a) {
        text-decoration: none;
        width: 100px;
        display: block;
        
    }

    :global(a:visited) {
      color: black;
    }

    :global(a:hover) {
      color: black;
      text-decoration: none;
    }


@media screen and (max-width: 768px) {
    .button-content {
        flex-direction: column;
        align-items: center;
  }
}
@media screen and (max-width: 768px) {
    header {
    flex-direction: column;
    align-items: flex-start;
    align-items: center;
  }
}


</style>
 