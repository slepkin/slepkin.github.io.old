# To add the LinkedIn button:

1. Ensure that index.html points to the correct stylesheet
2. Replace `.banner-link` with:
```css
    .banner-link {
      display: block;
      position: absolute;
      top:0;
      z-index: 10;
      color: #fff;
      font-weight: 700;
      box-shadow: 0 0 10px rgba(0,0,0,.5);
      border-bottom-left-radius: 2px;
      border-bottom-right-radius: 2px;
    }

    #forkme_banner {
      right: 10px;
      background: url('../images/blacktocat.png') #0090ff no-repeat 95% 50%;
      padding: 10px 50px 10px 10px;
    }

    #linked_banner {
     right: 200px;
     background-color: green;
     padding: 10px;
    }
```
3. Add `<a class="banner-link" id="linked_banner" href="http://www.linkedin.com/pub/simon-lepkin/21/b1/294/">View on LinkedIn</a>` after the forkme banner
4. Add `class="banner-link"` to `#forme-banner`. Note the underscore for class names, and the hyphen for ids.