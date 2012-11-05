lorem-cn: A ramdom Chinese characters generator
========

Lorem ipsum generator for Chinese language in Javascript.

中文版乱数假文生成器，Javascript实现。

## Usage 使用方法

Include `lorem-cn.js` in your HTML file which is UTF-8 encoded. 在HTML中引入 `lorem-cn.js` 文件。为避免乱码问题，请使用UTF-8编码。

	<meta charset="UTF-8">
	<script src="path/to/lorem-cn.js"></script>

Use `lorem` function with the length of text you wish to genrate as parameter. 使用`lorem`方法生成随即文本，第一个参数为文本长度。

	lorem(100); //return 100 random chinese characters
	lorem(75); //return 75 random chinese characters

If you don't want punctuations in the generated text, set `usePunc` to `false`. 如果你不想让生成的文本包含标点符号，在选项中设置 `usePunc` 为 `false`。

	lorem(20, {usePunc: false}); //20 characters without punctuations