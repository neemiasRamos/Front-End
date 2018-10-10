## Hover
Estado do input, quando o cursor do mouse esta sob o elemtento
```
.caixa-pesquisa:hover > .texto-pesquisa{
	width: 240px;
	padding: 0 6px;
}

```
*Note que o width estácom 240 pixels
![Hover on](https://github.com/neemiasRamos/Front-End/blob/master/caixa%20de%20pesquisa/hover-on.png)

## Normal
Estado do input, quando o cursor do mouse NÃO esta sob o elemtento
```
.texto-pesquisa{
	border: none;
	background: none;
	outline: none;
	float: left;
	padding: 0;
	color: white;
	font-size: 16px;
	transition: 0.4s;
	line-height: 40px;
	width:0px;
}

```

*Note que o width está com 0 pixels

![Hover on](https://github.com/neemiasRamos/Front-End/blob/master/caixa%20de%20pesquisa/hover-out.png)
