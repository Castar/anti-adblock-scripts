# Introduction #

Include this code show Adblock Users a message.


# Details #

**Insert the following code right before `</body>`:
```
        <script type="text/javascript">
            //<![CDATA[
            var adservice = true;
            //]]>
        </script>
```
  * Include the adscript.js file from the downloads folder by following tag after the code above:
```
<script type="text/javascript" src="http://anti-adblock-scripts.googlecode.com/files/adscript.js"></script>
```
  * Finally you add this code:
```

        <script type="text/javascript">
            //<![CDATA[
            if(adservice) {
             alert('Please disable your Adblock Software to support this site.')
            }
            //]]>
        </script> 
```** You can replace the alert statement by other measures. I use the snippet on my free file hoster. The download button disappears and instead displays an advisory message.

Other measures will follow soon:)