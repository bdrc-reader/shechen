# དྲ་རྒྱའི་ནང་སྒྲིག་སྟངས་ཀྱི་དཔེ་མཚོན།

![image alt text](https://raw.githubusercontent.com/bdrc-reader/shechen/master/docs/img/Capture.PNG)

<br>
<br>
<br>

# Test


<iframe src="https://library.bdrc.io/scripts/embed-iframe.html?work=bdr:W1ERI0009001&origin=website.com" width="100%" height="100%"></iframe>


<head>
  <title>Demo Viewer</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" type="text/css" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="stylesheet" type="text/css" href="http://library.bdrc.io/scripts/src/lib/mirador/css/mirador-combined.css">
  <link rel="stylesheet" type="text/css" href="http://library.bdrc.io/scripts/src/lib/mirador.css"/>
</head>
<body>
  <div id="viewer" class="demo"></div>
  <script src="http://library.bdrc.io/scripts/src/lib/mirador/mirador.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@dbmdz/mirador-keyboardnavigation@1.1.0/keyboardNavigation.min.js"></script>      
  <script src="https://cdn.jsdelivr.net/npm/lodash@4.17.11/lodash.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/requirejs@2.3.6/require.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/jsewts@1.0.2/src/jsewts.min.js"></script>
  <script type="module" src="http://library.bdrc.io/scripts/src/lib/transliterators.js"></script>
  <script type="module" src="http://library.bdrc.io/scripts/src/lib/miradorSetup.js"></script>
  <script type="module">
    let miradorConfig, miradorSetUI
    async function init() {
       const urlParams = new URLSearchParams(window.location.search);
       const work = urlParams.get('work');
       let data = [
          { "collectionUri" : "http://presentation.bdrc.io/2.1.1/collection/wio:"+work, location:"" }
       ]
       let config = miradorConfig(data);
       window.Mirador( config )
       miradorSetUI();
    }
    let waiter = setInterval( async ()=>{        
       if(_ && window.moduleLoaded &&  window.moduleLoaded.JsEWTS && window.moduleLoaded.Sanscript && window.moduleLoaded.pinyin4js) { {
          clearInterval(waiter);
          miradorConfig = window.miradorConfig
          miradorSetUI  = window.miradorSetUI
          init();
       }
    },100)
  </script>
</body>

[Website Link](https://bdrc-reader.github.io/shechen/)

# རང་དགོན་གྱིས་པར་སྐྱུན་བྱས་པའི་དཔེ་ཆ།
ldfksajfc;lkxjfnx

# དཔེ་ཀློག་སྒེའུ་ཁུང་དྲ་རྒྱའི་ནང་བསྒྲིག་ཚུལ།
ldfksajfc;lkxjfnxz

# དཔེ་ཀློག་སྒེའུ་ཁུང་གསར་དུ་སྒྲིག་ཚུལ།
ldfksajfc;lkxjfnxz

# དཀར་ཆག་བསྐྱར་བཅོས་བྱེད་ཚུལ།
ldfksajfc;lkxjfnxz

# ཡི་གེ་བཏགས་མ་སྣོན་ཚུལ།
ldfksajfc;lkxjfnxz

