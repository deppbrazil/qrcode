<p align="center">
  <a href="https://jquery.com/" target="_blank">
    <img alt="logo jQuery" src="https://upload.wikimedia.org/wikipedia/en/9/9e/JQuery_logo.svg" width="auto" height="150px"/>
  </a>
</p>

## QR Code com jQuery 

Com essa lib do jquery você informa no campo `text: ""` a url onde você quer levar o usuario, e o jquery desenha dinamicamente essa imagem para o leitor de qrcode.

``` bash
$('#qrcode').qrcode({
	width: 120, 
	height: 120, 
	text: "https://github.com/deppbrazil"
});
```



