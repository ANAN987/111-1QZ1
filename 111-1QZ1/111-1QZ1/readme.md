# 第1次隨堂題目-隨堂-QZ1
[deadline 2022/10/12 00:00:00](#)
>撰寫前請注意

1. 請[點選](https://github.com/altoliaw3/111-1QZ1.git)該連結連結至題目之倉庫，並對該倉庫進行fork
2. 再藉由上述所提供的連結，把該fork至自己帳號的倉庫clone至本機端，
再進行程式撰寫與文件撰寫

> 正題

請解決下面問題。請於該專案下新增一個Web表單(網頁表單)名稱為Bomb， 根據課堂所述，會產生三個附檔名的檔案，其中一個是.aspx，另兩個是.cs。 請在Bomb.cs的Page_Load事件下，寫下以下功能：
1. 生成一個整數2維陣列變數大小為10* 10，名稱為ia_Map。
2. 生成一個整數1維陣列變數大小為10，名稱為ia_MIndex。
在ia_Map，即10*10的二維陣列中，其索引值從0至99。今有10個地雷儲存於ia_MIndex，其生成點於索引值0至99中，若今有輸入10個，請完成圖中應有的數字。
如：輸入 0 7 13 28 44 62 74 75 87 90  (存於ia_MIndex內，由左至右，由上至下，索引由0開始)
輸出為下面陣列(*為炸彈)
<?xml version="1.0" encoding="UTF-8"?>
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="156pt" height="125pt" viewBox="0 0 156 125" version="1.1">
<defs>
<g>
<symbol overflow="visible" id="glyph0-0">
<path style="stroke:none;" d="M 2.609375 -5.125 C 3.09375 -4.765625 3.84375 -4.203125 3.890625 -4.171875 C 3.953125 -4.140625 3.984375 -4.109375 4.0625 -4.109375 C 4.21875 -4.109375 4.328125 -4.265625 4.328125 -4.390625 C 4.328125 -4.5 4.28125 -4.578125 4.109375 -4.671875 L 2.71875 -5.328125 L 4.09375 -5.984375 C 4.28125 -6.078125 4.328125 -6.140625 4.328125 -6.265625 C 4.328125 -6.390625 4.21875 -6.546875 4.0625 -6.546875 C 3.984375 -6.546875 3.96875 -6.546875 3.703125 -6.34375 L 2.609375 -5.53125 L 2.75 -7.234375 C 2.75 -7.375 2.625 -7.484375 2.5 -7.484375 C 2.328125 -7.484375 2.21875 -7.359375 2.21875 -7.234375 C 2.21875 -7.125 2.359375 -5.75 2.375 -5.53125 L 1.140625 -6.4375 C 1 -6.546875 0.984375 -6.546875 0.921875 -6.546875 C 0.75 -6.546875 0.640625 -6.390625 0.640625 -6.265625 C 0.640625 -6.15625 0.6875 -6.078125 0.859375 -5.984375 L 2.265625 -5.328125 L 0.875 -4.671875 C 0.6875 -4.578125 0.640625 -4.515625 0.640625 -4.390625 C 0.640625 -4.375 0.640625 -4.109375 0.984375 -4.109375 L 2.375 -5.125 L 2.21875 -3.421875 C 2.21875 -3.28125 2.359375 -3.1875 2.484375 -3.1875 C 2.640625 -3.1875 2.75 -3.296875 2.75 -3.421875 C 2.75 -3.53125 2.625 -4.90625 2.609375 -5.125 Z M 2.609375 -5.125 "/>
</symbol>
</g>
</defs>
<g id="surface1">
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.65625 1240 L 1551.875 1240 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.695312 1118.359375 L 7.695312 1237.96875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-0" x="6.74297" y="9.573"/>
</g>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 177.109375 1118.359375 L 177.109375 1237.96875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 296.601562 1118.359375 L 296.601562 1237.96875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 465.976562 1118.359375 L 465.976562 1237.96875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 635.390625 1118.359375 L 635.390625 1237.96875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 804.765625 1118.359375 L 804.765625 1237.96875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 974.140625 1118.359375 L 974.140625 1237.96875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1093.671875 1118.359375 L 1093.671875 1237.96875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-0" x="115.337" y="9.573"/>
</g>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1263.046875 1118.359375 L 1263.046875 1237.96875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1432.421875 1118.359375 L 1432.421875 1237.96875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1551.914062 1118.359375 L 1551.914062 1237.96875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.65625 1116.445312 L 1551.875 1116.445312 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.695312 994.882812 L 7.695312 1114.492188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 177.109375 994.882812 L 177.109375 1114.492188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 296.601562 994.882812 L 296.601562 1114.492188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 465.976562 994.882812 L 465.976562 1114.492188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-0" x="52.5711" y="21.93"/>
</g>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 635.390625 994.882812 L 635.390625 1114.492188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 804.765625 994.882812 L 804.765625 1114.492188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 974.140625 994.882812 L 974.140625 1114.492188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1093.671875 994.882812 L 1093.671875 1114.492188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1263.046875 994.882812 L 1263.046875 1114.492188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1432.421875 994.882812 L 1432.421875 1114.492188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1551.914062 994.882812 L 1551.914062 1114.492188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.65625 992.851562 L 1551.875 992.851562 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.695312 871.328125 L 7.695312 990.9375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 177.109375 871.328125 L 177.109375 990.9375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 296.601562 871.328125 L 296.601562 990.9375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 465.976562 871.328125 L 465.976562 990.9375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 635.390625 871.328125 L 635.390625 990.9375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 804.765625 871.328125 L 804.765625 990.9375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 974.140625 871.328125 L 974.140625 990.9375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1093.671875 871.328125 L 1093.671875 990.9375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1263.046875 871.328125 L 1263.046875 990.9375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-0" x="132.275" y="34.2781"/>
</g>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1432.421875 871.328125 L 1432.421875 990.9375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1551.914062 871.328125 L 1551.914062 990.9375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.65625 869.375 L 1551.875 869.375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.695312 747.734375 L 7.695312 867.34375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 177.109375 747.734375 L 177.109375 867.34375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 296.601562 747.734375 L 296.601562 867.34375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 465.976562 747.734375 L 465.976562 867.34375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 635.390625 747.734375 L 635.390625 867.34375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 804.765625 747.734375 L 804.765625 867.34375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 974.140625 747.734375 L 974.140625 867.34375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1093.671875 747.734375 L 1093.671875 867.34375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1263.046875 747.734375 L 1263.046875 867.34375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1432.421875 747.734375 L 1432.421875 867.34375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1551.914062 747.734375 L 1551.914062 867.34375 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.65625 745.820312 L 1551.875 745.820312 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.695312 624.257812 L 7.695312 743.867188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 177.109375 624.257812 L 177.109375 743.867188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 296.601562 624.257812 L 296.601562 743.867188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 465.976562 624.257812 L 465.976562 743.867188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 635.390625 624.257812 L 635.390625 743.867188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-0" x="69.509" y="58.9918"/>
</g>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 804.765625 624.257812 L 804.765625 743.867188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 974.140625 624.257812 L 974.140625 743.867188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1093.671875 624.257812 L 1093.671875 743.867188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1263.046875 624.257812 L 1263.046875 743.867188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1432.421875 624.257812 L 1432.421875 743.867188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1551.914062 624.257812 L 1551.914062 743.867188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.65625 622.304688 L 1551.875 622.304688 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.695312 500.703125 L 7.695312 620.3125 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 177.109375 500.703125 L 177.109375 620.3125 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 296.601562 500.703125 L 296.601562 620.3125 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 465.976562 500.703125 L 465.976562 620.3125 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 635.390625 500.703125 L 635.390625 620.3125 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 804.765625 500.703125 L 804.765625 620.3125 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 974.140625 500.703125 L 974.140625 620.3125 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1093.671875 500.703125 L 1093.671875 620.3125 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1263.046875 500.703125 L 1263.046875 620.3125 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1432.421875 500.703125 L 1432.421875 620.3125 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1551.914062 500.703125 L 1551.914062 620.3125 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.65625 498.75 L 1551.875 498.75 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.695312 377.226562 L 7.695312 496.835938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 177.109375 377.226562 L 177.109375 496.835938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 296.601562 377.226562 L 296.601562 496.835938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-0" x="35.6422" y="83.6969"/>
</g>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 465.976562 377.226562 L 465.976562 496.835938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 635.390625 377.226562 L 635.390625 496.835938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 804.765625 377.226562 L 804.765625 496.835938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 974.140625 377.226562 L 974.140625 496.835938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1093.671875 377.226562 L 1093.671875 496.835938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1263.046875 377.226562 L 1263.046875 496.835938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1432.421875 377.226562 L 1432.421875 496.835938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1551.914062 377.226562 L 1551.914062 496.835938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.65625 375.195312 L 1551.875 375.195312 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.695312 253.632812 L 7.695312 373.242188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 177.109375 253.632812 L 177.109375 373.242188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 296.601562 253.632812 L 296.601562 373.242188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 465.976562 253.632812 L 465.976562 373.242188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 635.390625 253.632812 L 635.390625 373.242188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-0" x="69.509" y="96.0539"/>
</g>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 804.765625 253.632812 L 804.765625 373.242188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-0" x="86.4469" y="96.0539"/>
</g>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 974.140625 253.632812 L 974.140625 373.242188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1093.671875 253.632812 L 1093.671875 373.242188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1263.046875 253.632812 L 1263.046875 373.242188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1432.421875 253.632812 L 1432.421875 373.242188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1551.914062 253.632812 L 1551.914062 373.242188 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.65625 251.71875 L 1551.875 251.71875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.695312 130.078125 L 7.695312 249.6875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 177.109375 130.078125 L 177.109375 249.6875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 296.601562 130.078125 L 296.601562 249.6875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 465.976562 130.078125 L 465.976562 249.6875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 635.390625 130.078125 L 635.390625 249.6875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 804.765625 130.078125 L 804.765625 249.6875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 974.140625 130.078125 L 974.140625 249.6875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1093.671875 130.078125 L 1093.671875 249.6875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-0" x="115.337" y="108.402"/>
</g>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1263.046875 130.078125 L 1263.046875 249.6875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1432.421875 130.078125 L 1432.421875 249.6875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1551.914062 130.078125 L 1551.914062 249.6875 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.65625 128.125 L 1551.875 128.125 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.695312 6.601562 L 7.695312 126.210938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-0" x="6.74297" y="120.75898"/>
</g>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 177.109375 6.601562 L 177.109375 126.210938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 296.601562 6.601562 L 296.601562 126.210938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 465.976562 6.601562 L 465.976562 126.210938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 635.390625 6.601562 L 635.390625 126.210938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 804.765625 6.601562 L 804.765625 126.210938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 974.140625 6.601562 L 974.140625 126.210938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1093.671875 6.601562 L 1093.671875 126.210938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1263.046875 6.601562 L 1263.046875 126.210938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1432.421875 6.601562 L 1432.421875 126.210938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 1551.914062 6.601562 L 1551.914062 126.210938 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
<path style="fill:none;stroke-width:4.05;stroke-linecap:butt;stroke-linejoin:miter;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 7.65625 4.570312 L 1551.875 4.570312 " transform="matrix(0.1,0,0,-0.1,0,125)"/>
</g>
</svg>


> 補充說明 (以下各項全需滿足，才會進行評分)

1. 請將完成程式後，撰寫書面內容寫於answer.md
2. 將將該answer.md檔藉由markdown editor 顯示部分，按右鍵進行列印成pdf檔案，
檔名需為answer.md.pdf
3. 將answer.md.pdf檔於[CleverPDF](https://www.cleverpdf.com/zh-tw/encrypt-pdf)進行**防拷貝**，
並將防拷貝後的answer.md.pdf放置至專案下並拖入VS community IDE內的「**方案總管**」
4. 將answer.md使用winrar加密打包，請自己記住密碼，
並於VS community IDE內的「**方案總管**」刪除answer.md檔案
5. 將專案執行git add、commit、push至github後，並於
[google sheet(點我)](https://docs.google.com/spreadsheets/d/1x_GfVISrublmnrn1S43wtEt_XPEKV2AqirTlMZPLCK4/edit#gid=345458270)中找尋相對應之試算表，
並於該位同學位置註記同學之倉庫的url

>該次作業完成預計所需時間 (實作與文件撰寫所需要完成時間) 

* 70 mins 以下：專精
* 介於 70 至 100 mins：熟練
* 介於 100 至 180 mins：平均
* 超過 180 mins：不熟，請多花心思在課業上

