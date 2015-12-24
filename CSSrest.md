/* Remove margins, padding, borders and alignments for all elements */
html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* set HTML5 elements block */
article, aside, details, figcaption, figure, footer, header, hgroup, menu, nav, section {
	display: block;
}
/*remove chorme字体小于12px显示问题*/
html,body,form,fieldset,p,div,h1,h2,h3,h4,h5,h6{-webkit-text-size-adjust:none}

/*字体设置顺序*/
html { font-family: 'Microsoft YaHei',"Helvetica Neue", Helvetica, STHeiTi, Arial, sans-serif; -ms-text-size-adjust: 100%; -webkit-text-size-adjust: 100%; font-size: 62.5%; }

.fl{float:left;}.fr{float:right;}.hide{display:none!important;}.show{display: block!important;}

ul,ol,dl{list-style:none;}

/* Blockquote style removal */
blockquote, q {quotes: none;}
blockquote:before, blockquote:after,q:before, q:after {content: '';	content: none;}

/* Remove any table spacing */
table { border-collapse: collapse; border-spacing: 0; }td, th { padding: 0; }

img{vertical-align:middle;border:0;-ms-interpolation-mode:bicubic;}

a { background: transparent; text-decoration: none; -webkit-tap-highlight-color: transparent;}
/*取消文本框缩放*/
textarea{resize:none;}

/*文字两端对齐*/
.justify {text-align:justify;text-justify:distribute-all-lines;/*ie6-8*/text-align-last:justify;/* ie9*/-moz-text-align-last:justify;/*ff*/
-webkit-text-align-last:justify;/*chrome 20+*/
}
/*省略号*/
.ellipsis { white-space:nowrap; text-overflow:ellipsis; overflow:hidden; word-break: keep-all}
/*长单词换行*/
.break { word-break:break-all; word-wrap:break-word}
/* 图片视频等自适应调整 */
img {max-width: 100%; height: auto;width: auto\9; /* ie8 */}
/*清除浮动*/
.clearfix:after{content:"";display:table;height:0;clear:both}.clearfix{*zoom:1}
/*表单元素*/
button, input, optgroup, select, textarea { color: inherit; font: inherit; margin: 0; }
button { overflow: visible; }
button, select { text-transform: none; }
button, html input[type="button"], input[type="reset"], input[type="submit"] { -webkit-appearance: button; cursor: pointer; }
button[disabled], html input[disabled] { cursor: default; }
button::-moz-focus-inner, input::-moz-focus-inner { border: 0; padding: 0; }
input { line-height: normal; }
input[type="checkbox"], input[type="radio"] { box-sizing: border-box; padding: 0; }
input[type="number"]::-webkit-inner-spin-button, input[type="number"]::-webkit-outer-spin-button { height: auto; }
input[type="search"] { -webkit-appearance: textfield; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; box-sizing: border-box; }
input[type="search"]::-webkit-search-cancel-button, input[type="search"]::-webkit-search-decoration { -webkit-appearance: none; }
textarea { overflow: auto; resize: vertical; }
button, input, select, textarea { font-family:'Microsoft YaHei', "Helvetica Neue", Helvetica, STHeiTi, Arial, sans-serif;}
input::-moz-placeholder, textarea::-moz-placeholder { color: #cccccc; }
input:-ms-input-placeholder, textarea:-ms-input-placeholder { color: #cccccc; }
input::-webkit-input-placeholder, textarea::-webkit-input-placeholder { color: #cccccc; }
