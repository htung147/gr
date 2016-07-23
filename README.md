# gr


<!DOCTYPE html>
<html>
  <head>
    <style type="text/css">
      body {
        font-family: "HelveticaNeue", "Helvetica Neue", "HelveticaNeueRoman", "HelveticaNeue-Roman", "Helvetica Neue Roman", 'TeXGyreHerosRegular', "Helvetica", "Tahoma", "Geneva", "Arial", sans-serif;
        color: #666;
        width: 660px;
        margin: 70px auto;
        text-align: center;
      }
      h1 {
        font-size: 26px;
        color: #333;
        margin: 24px auto 12px;
      }
      h2 {
        font-size: 18px;
        margin: 16px 0 24px;
      }
      p {
        font-size: 16px;
        line-height: 18px;
        margin-bottom: 28px;
      }
    </style>
  </head>
  <body>
    <h1>We're sorry.</h1>
    <p>
      Something went wrong. We've received a notification and will be looking into it.
    </p>
    <p>
      <h2>In the meantime, here's a cat video for your trouble:</h2>
      <iframe id="video-frame" src="https://www.youtube.com/embed/Vw4KVoEVcr0?rel=0"
              width="360" height="218" frameborder="0" allowfullscreen>
      </iframe>
    </p>
    <script type="text/javascript">
      var videoHashes = [
            'https://www.youtube.com/watch?v=MHOf-KRpd3Q?rel=0',
            'https://www.youtube.com/watch?v=bBey36TfTkA?rel=0',
            'https://www.youtube.com/watch?v=OyACWS4FteU?rel=0',
            'https://www.youtube.com/watch?v=rd4gaUwxE14?rel=0',
            'https://www.youtube.com/watch?v=dWSw13KAbxs?rel=0',
            'https://www.youtube.com/watch?v=PN8zH1pchpc?rel=0',
            'https://www.youtube.com/watch?v=TzRkmq0OpSc?rel=0'];
      document.getElementById('video-frame').src =
        videoHashes[Math.floor(Math.random() * videoHashes.length)];
    </script>
  </body>
</html>
