# What's this folder?
**This in HTML Form so we can copy and paste, lol**

This is so we can put the ads in html so they can be used as redirects or external pages.

<script type="text/javascript">
  var imageUrls = [
       "https://zap-hosting.com/interface/download/images.php?type=affiliate&id=191907"
     , "http://ww.mydomain.com/img/newspapers/reforma.png"
     , "http://ww.mydomain.com/img/newspapers/nytimes.png"
     , "http://ww.mydomain.com/img/newspapers/oglobo.png"
     , "http://ww.mydomain.com/img/newspapers/lefigaro.png"
     , "http://ww.mydomain.com/img/newspapers/spiegel.png"
  ];
 var imageLinks = [
       "https://zap-hosting.com/a/eeadb9270ea6a5974134fc69877df21128cab52d"
      , "http://www.reforma.com/"
       , "http://www.nytimes.com/"
      , "https://oglobo.globo.com/"
      , "http://www.lefigaro.fr/international/"
     , "http://www.spiegel.de/international/"
  ];

  function getImageHtmlCode() {
    var dataIndex = Math.floor(Math.random() * imageUrls.length);
    var img = '<a href="' + imageLinks[dataIndex] + '"><img src="';
    img += imageUrls[dataIndex];
    img += '" alt="*cricket noises*"/></a>';
    return img;
  }
</script>
<body bgcolor="white">
<script type="text/javascript">
  document.write(getImageHtmlCode());
