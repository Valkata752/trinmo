---
title: Автобуси - търсачка
description: 
published: true
date: 2023-08-15T12:08:31.596Z
tags: 
editor: markdown
dateCreated: 2023-08-15T11:45:45.401Z
---

<head>
  <title></title>
  <link rel="stylesheet" type="text/css" href="main.css">
</head>

<body>
  <input type="text" id="name-search" onkeyup="nameSearch()" placeholder="Name.." class="table-search-filters">
  <input type="text" id="age-search" onkeyup="ageSearch()" placeholder="Age.." class="table-search-filters">
  <input type="text" id="city-search" onkeyup="citySearch()" placeholder="City.." class="table-search-filters">
  <table id="custom-table">
    <thead>
  <tr>
    <th>1</th>
    <th>2</th>
    <th>3</th>
    <th>4</th>
    <th>5</th>
    <th>6</th>
    <th>7</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>01.2023</td>
    <td>28.04.2023</td>
    <td></td>
    <td>LKLA6L1A4NA777428</td>
    <td>5061</td>
    <td>ЕА 3397 AA</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>01.2023</td>
    <td>28.04.2023</td>
    <td></td>
    <td>LKLA6L1A6NA777429</td>
    <td>5062</td>
    <td>ЕА 3551 AA</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>01.2023</td>
    <td>09.05.2023</td>
    <td></td>
    <td>LKLA6L1A2NA777430</td>
    <td>5063</td>
    <td>ЕА 3552 AA</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>01.2023</td>
    <td>09.05.2023</td>
    <td></td>
    <td>LKLA6L1A4NA777431</td>
    <td>5064</td>
    <td>ЕА 3398 AA</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro M</td>
    <td>2015</td>
    <td>05.2023</td>
    <td></td>
    <td>WEB63372313268830</td>
    <td>1316</td>
    <td>CB 6168 XA</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro M</td>
    <td>2015</td>
    <td>05.2023</td>
    <td></td>
    <td>WEB63372313268831</td>
    <td>1317</td>
    <td>CB 6108 XA</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro M</td>
    <td>2015</td>
    <td>05.2023</td>
    <td></td>
    <td>WEB63372313270606</td>
    <td>1318</td>
    <td>CB 6176 XA</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro M</td>
    <td>2015</td>
    <td>05.2023</td>
    <td></td>
    <td>WEB63372313268826</td>
    <td>1319</td>
    <td>CB 6107 XA</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro M</td>
    <td>2015</td>
    <td>05.2023</td>
    <td></td>
    <td>WEB63372313268829</td>
    <td>1320</td>
    <td>CB 6104 XA</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro M</td>
    <td>2015</td>
    <td>05.2023</td>
    <td></td>
    <td>WEB63372313268828</td>
    <td>1321</td>
    <td>CB 6173 XA</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D4NA774903</td>
    <td>2811</td>
    <td>CB 6443 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D6NA774904</td>
    <td>2812</td>
    <td>CB 6463 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D8NA774905</td>
    <td>2813</td>
    <td>CB 6461 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1DXNA774906</td>
    <td>2814</td>
    <td>CB 6470 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D1NA774907</td>
    <td>2815</td>
    <td>CB 6457 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D3NA774908</td>
    <td>2816</td>
    <td>CB 6486 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D5NA774909</td>
    <td>2817</td>
    <td>CB 6484 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D1NA774910</td>
    <td>2818</td>
    <td>CB 6478 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D3NA774911</td>
    <td>2819</td>
    <td>CB 6473 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D5NA774912</td>
    <td>2820</td>
    <td>CB 6489 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D7NA774913</td>
    <td>2821</td>
    <td>CB 6496 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D9NA774914</td>
    <td>2822</td>
    <td>CB 6507 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D0NA774915</td>
    <td>2823</td>
    <td>CB 6493 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D2NA774916</td>
    <td>2824</td>
    <td>CB 6499 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D4NA774917</td>
    <td>2825</td>
    <td>CB 6465 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D6NA774918</td>
    <td>2826</td>
    <td>CB 6514 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D8NA774919</td>
    <td>2827</td>
    <td>CB 6456 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D4NA774920</td>
    <td>2828</td>
    <td>CB 6512 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D6NA774921</td>
    <td>2829</td>
    <td>CB 6510 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D8NA774922</td>
    <td>2830</td>
    <td>CB 6508 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1DXNA774923</td>
    <td>2831</td>
    <td>CB 6448 TC</td>
  </tr>
  <tr>
    <td>Higer KLQ6832GEV</td>
    <td>2022</td>
    <td>03.04.2023</td>
    <td></td>
    <td>LKLA6D1D1NA774924</td>
    <td>2832</td>
    <td>CB 6490 TC</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td>12.05.2023</td>
    <td></td>
    <td>NLNC2EMLA10008789</td>
    <td>2503</td>
    <td>CB 1040 TC</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td>12.05.2023</td>
    <td></td>
    <td>NLNC2EMLA10008790</td>
    <td>2502</td>
    <td>CB 1037 TC</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td>12.05.2023</td>
    <td></td>
    <td>NLNC2EMLA10008791</td>
    <td>2501</td>
    <td>CB 1035 TC</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td>12.05.2023</td>
    <td></td>
    <td>NLNC2EMLA10008792</td>
    <td>2505</td>
    <td>CB 1074 TC</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td>12.05.2023</td>
    <td></td>
    <td>NLNC2EMLA10008793</td>
    <td>2504</td>
    <td>CB 1043 TC</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td>20.04.2023</td>
    <td></td>
    <td>NLNC2EMLA10008794</td>
    <td>1010</td>
    <td>EA 1096 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008795</td>
    <td></td>
    <td>EA 1092 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008796</td>
    <td></td>
    <td>EA 1091 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td>20.04.2023</td>
    <td></td>
    <td>NLNC2EMLA10008797</td>
    <td>1013</td>
    <td>EA 1090 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td>20.04.2023</td>
    <td></td>
    <td>NLNC2EMLA10008798</td>
    <td>1014</td>
    <td>EA 1089 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008799</td>
    <td></td>
    <td>EA 1088 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008800</td>
    <td></td>
    <td>EA 1087 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008801</td>
    <td></td>
    <td>EA 1086 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008802</td>
    <td></td>
    <td>EA 1085 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008803</td>
    <td></td>
    <td>EA 1093 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008822</td>
    <td></td>
    <td>EA 1094 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008823</td>
    <td></td>
    <td>EA 1084 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td>20.04.2023</td>
    <td></td>
    <td>NLNC2EMLA10008824</td>
    <td>1022</td>
    <td>EA 1083 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008825</td>
    <td></td>
    <td>EA 1082 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008826</td>
    <td></td>
    <td>EA 1081 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008827</td>
    <td></td>
    <td>EA 1072 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td>20.04.2023</td>
    <td></td>
    <td>NLNC2EMLA10008828</td>
    <td>1025</td>
    <td>EA 1073 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008829</td>
    <td></td>
    <td>EA 1094 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008830</td>
    <td></td>
    <td>EA 1074 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008831</td>
    <td></td>
    <td>EA 1075 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008832</td>
    <td></td>
    <td>EA 1076 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td>20.04.2023</td>
    <td></td>
    <td>NLNC2EMLA10008833</td>
    <td>1034</td>
    <td>EA 1077 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td>20.04.2023</td>
    <td></td>
    <td>NLNC2EMLA10008834</td>
    <td>1027</td>
    <td>EA 1078 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008835</td>
    <td></td>
    <td>EA 1079 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008836</td>
    <td></td>
    <td>EA 1080 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008837</td>
    <td></td>
    <td>EA 1070 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008838</td>
    <td></td>
    <td>EA 1069 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008839</td>
    <td></td>
    <td>EA 1068 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td>20.04.2023</td>
    <td></td>
    <td>NLNC2EMLA10008840</td>
    <td>1038</td>
    <td>EA 1071 AA</td>
  </tr>
  <tr>
    <td>Karsan Jest Electric</td>
    <td>2022</td>
    <td></td>
    <td></td>
    <td>NLNC2EMLA10008841</td>
    <td></td>
    <td>EA 1067 AA</td>
  </tr>
  <tr>
    <td>Higer KLQ6186GEV</td>
    <td>2021</td>
    <td>16.05.2022</td>
    <td></td>
    <td>LKLA6N7W8MA768034</td>
    <td>1704</td>
    <td>СВ 9689 ТЕ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>17.11.2021</td>
    <td></td>
    <td>LKLA6L1A9MA760770</td>
    <td>5060</td>
    <td>СВ 2869 СТ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>17.11.2021</td>
    <td></td>
    <td>LKLA6L1A2MA760769</td>
    <td>5059</td>
    <td>СВ 2871 СТ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>17.11.2021</td>
    <td></td>
    <td>LKLA6L1A0MA760768</td>
    <td>5058</td>
    <td>СВ 2874 СТ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>17.11.2021</td>
    <td></td>
    <td>LKLA6L1A9MA760767</td>
    <td>5057</td>
    <td>СВ 2876 СТ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>17.11.2021</td>
    <td></td>
    <td>LKLA6L1A7MA760766</td>
    <td>5056</td>
    <td>СВ 2883 СТ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>17.11.2021</td>
    <td></td>
    <td>LKLA6L1A5MA760765</td>
    <td>5055</td>
    <td>СВ 2884 СТ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>17.11.2021</td>
    <td></td>
    <td>LKLA6L1A3MA760764</td>
    <td>5054</td>
    <td>СВ 2872 СТ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>17.11.2021</td>
    <td></td>
    <td>LKLA6L1A1MA760763</td>
    <td>5053</td>
    <td>СВ 2897 СТ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>17.11.2021</td>
    <td></td>
    <td>LKLA6L1AXMA760762</td>
    <td>5052</td>
    <td>СВ 2910 СТ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>17.11.2021</td>
    <td></td>
    <td>LKLA6L1A8MA760761</td>
    <td>5051</td>
    <td>СВ 2911 СТ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>17.11.2021</td>
    <td></td>
    <td>LKLA6L1A6MA760760</td>
    <td>5050</td>
    <td>СВ 2902 СТ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>18.10.2021</td>
    <td></td>
    <td>LKLA6L1AXMA760759</td>
    <td>5049</td>
    <td>СВ 6373 СС</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>18.10.2021</td>
    <td></td>
    <td>LKLA6L1A8MA760758</td>
    <td>5048</td>
    <td>СВ 2907 СТ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>17.11.2021</td>
    <td></td>
    <td>LKLA6L1A6MA760757</td>
    <td>5047</td>
    <td>СВ 2887 СТ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>18.10.2021</td>
    <td></td>
    <td>LKLA6L1A4MA760756</td>
    <td>5046</td>
    <td>СВ 6408 СС</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>17.11.2021</td>
    <td></td>
    <td>LKLA6L1A2MA760755</td>
    <td>5045</td>
    <td>СВ 2892 СТ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>18.10.2021</td>
    <td></td>
    <td>LKLA6L1A0MA760754</td>
    <td>5044</td>
    <td>СВ 2895 СТ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>18.10.2021</td>
    <td></td>
    <td>LKLA6L1A9MA760753</td>
    <td>5043</td>
    <td>СВ 6402 СС</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>18.10.2021</td>
    <td></td>
    <td>LKLA6L1A7MA760752</td>
    <td>5042</td>
    <td>СВ 6411 СС</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>17.11.2021</td>
    <td></td>
    <td>LKLA6L1A5MA760751</td>
    <td>5041</td>
    <td>СВ 6375 СС</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>18.10.2021</td>
    <td></td>
    <td>LKLA6L1A3MA760750</td>
    <td>5040</td>
    <td>СВ 6378 СС</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>03.10.2021</td>
    <td></td>
    <td>LKLA6L1A7MA760749</td>
    <td>5039</td>
    <td>СВ 6380 СС</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>01.10.2021</td>
    <td></td>
    <td>LKLA6L1A5MA760748</td>
    <td>5038</td>
    <td>СВ 6384 СС</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>18.10.2021</td>
    <td></td>
    <td>LKLA6L1A3MA760747</td>
    <td>5037</td>
    <td>СВ 6388 СС</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>01.10.2021</td>
    <td></td>
    <td>LKLA6L1A1MA760746</td>
    <td>5036</td>
    <td>СВ 6391 СС</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>30.09.2021</td>
    <td></td>
    <td>LKLA6L1AXMA760745</td>
    <td>5035</td>
    <td>СВ 6394 СС</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>18.10.2021</td>
    <td></td>
    <td>LKLA6L1A8MA760744</td>
    <td>5034</td>
    <td>СВ 6397 СС</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>18.10.2021</td>
    <td></td>
    <td>LKLA6L1A6MA760743</td>
    <td>5033</td>
    <td>СВ 6412 СС</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>18.10.2021</td>
    <td></td>
    <td>LKLA6L1A4MA760742</td>
    <td>5032</td>
    <td>СВ 6405 СС</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2021</td>
    <td>18.10.2021</td>
    <td></td>
    <td>LKLA6L1A1MA760741</td>
    <td>5031</td>
    <td>СВ 6409 СС</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2020</td>
    <td>24.09.2020</td>
    <td></td>
    <td>NMC320LGBLB900013</td>
    <td>7165</td>
    <td>СВ 9414 РТ</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2020</td>
    <td>24.09.2020</td>
    <td></td>
    <td>NMC320LGBLB900014</td>
    <td>7167</td>
    <td>СВ 9415 РТ</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2020</td>
    <td>24.09.2020</td>
    <td></td>
    <td>NMC320LGBLB900015</td>
    <td>7169</td>
    <td>СВ 9409 РТ</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2020</td>
    <td>24.09.2020</td>
    <td></td>
    <td>NMC320LGBLB900016</td>
    <td>7171</td>
    <td>СВ 9412 РТ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2019</td>
    <td>02.01.2020</td>
    <td></td>
    <td>LKLA6L1A1KA747329</td>
    <td>5001</td>
    <td>СВ 7953 РВ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2019</td>
    <td>13.02.2020</td>
    <td></td>
    <td>LKLA6L1A1KA747330</td>
    <td>5002</td>
    <td>СВ 0460 РМ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2019</td>
    <td>14.02.2020</td>
    <td></td>
    <td>LKLA6L1A1KA747331</td>
    <td>5003</td>
    <td>СВ 0457 РМ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2019</td>
    <td>15.03.2020</td>
    <td></td>
    <td>LKLA6L1A1KA747332</td>
    <td>5004</td>
    <td>СВ 0458 РМ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2019</td>
    <td>07.01.2020</td>
    <td></td>
    <td>LKLA6L1A1KA747333</td>
    <td>5005</td>
    <td>СВ 0455 РМ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2019</td>
    <td>15.03.2020</td>
    <td></td>
    <td>LKLA6L1A1KA747334</td>
    <td>5006</td>
    <td>СВ 0454 РМ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2019</td>
    <td>13.01.2020</td>
    <td></td>
    <td>LKLA6L1A7KA747335</td>
    <td>5007</td>
    <td>СВ 0451 РМ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2019</td>
    <td>19.04.2020</td>
    <td></td>
    <td>LKLA6L1A1KA747336</td>
    <td>5008</td>
    <td>СВ 0452 РМ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2019</td>
    <td>23.05.2020</td>
    <td></td>
    <td>LKLA6L1A1KA747337</td>
    <td>5009</td>
    <td>СВ 0459 РМ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2019</td>
    <td>15.01.2020</td>
    <td></td>
    <td>LKLA6L1A1KA747338</td>
    <td>5010</td>
    <td>СВ 5927 РН</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2019</td>
    <td>17.01.2020</td>
    <td></td>
    <td>LKLA6L1A1KA747339</td>
    <td>5011</td>
    <td>СВ 0456 РМ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2019</td>
    <td>19.04.2020</td>
    <td></td>
    <td>LKLA6L1A1KA747340</td>
    <td>5012</td>
    <td>СВ 0453 РМ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2019</td>
    <td>14.01.2020</td>
    <td></td>
    <td>LKLA6L1A1KA747341</td>
    <td>5013</td>
    <td>СВ 0450 РМ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2019</td>
    <td>14.01.2020</td>
    <td></td>
    <td>LKLA6L1A1KA747342</td>
    <td>5014</td>
    <td>СВ 0449 РМ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2019</td>
    <td>29.04.2020</td>
    <td></td>
    <td>LKLA6L1A1KA747343</td>
    <td>5015</td>
    <td>СВ 0448 РМ</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2016</td>
    <td></td>
    <td></td>
    <td>LKLA6L125GA708971</td>
    <td>8-&gt;1703</td>
    <td>EA 1160 AA</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2016</td>
    <td></td>
    <td></td>
    <td>LKLA6L123GA708970</td>
    <td>7-&gt;1702</td>
    <td>CB 7913 TH</td>
  </tr>
  <tr>
    <td>Higer KLQ6125GEV3</td>
    <td>2014</td>
    <td>20.04.2014</td>
    <td></td>
    <td> LKLA6L194DC631796</td>
    <td>1701</td>
    <td>СА 6498 АН</td>
  </tr>
  <tr>
    <td>Ford Transit</td>
    <td>2018</td>
    <td>12.06.2021</td>
    <td></td>
    <td>WFOHXXTTGHJYC3818</td>
    <td></td>
    <td>СВ 6523 МК</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ8KT030482</td>
    <td>3159</td>
    <td>CB 5716 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ9KT030474</td>
    <td>3158</td>
    <td>CB 5708 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZXKT030466</td>
    <td>3157</td>
    <td>CB 5719 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ9KT030460</td>
    <td>3156</td>
    <td>CB 5724 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ1KT030453</td>
    <td>3155</td>
    <td>CB 5721 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ6KT030447</td>
    <td>3154</td>
    <td>CB 5710 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ5KT030441</td>
    <td>3153</td>
    <td>CB 5713 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ8KT030434</td>
    <td>3152</td>
    <td>CB 5711 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ2KT030428</td>
    <td>3151</td>
    <td>CB 5697 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ1KT030422</td>
    <td>3150</td>
    <td>CB 5699 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ6KT030416</td>
    <td>3149</td>
    <td>CB 5707 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ5KT030410</td>
    <td>3148</td>
    <td>CB 5705 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ6KT030402</td>
    <td>3147</td>
    <td>CB 5702 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ4KT030396</td>
    <td>3146</td>
    <td>CB 5709 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ5KT030388</td>
    <td>3145</td>
    <td>CB 5696 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ6KT030383</td>
    <td>3144</td>
    <td>CB 5695 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ2KT030378</td>
    <td>3143</td>
    <td>CB 5693 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ1KT030372</td>
    <td>3142</td>
    <td>CB 5725 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ4KT030365</td>
    <td>3141</td>
    <td>CB 5698 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>WMAA23ZZ9KT030359</td>
    <td>3140</td>
    <td>CB 5723 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZ8KT030353</td>
    <td>2319</td>
    <td>CB 5720 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZ2KT030347</td>
    <td>2318</td>
    <td>CB 5717 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZXKT030340</td>
    <td>2317</td>
    <td>CB 5712 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZ4KT030334</td>
    <td>2316</td>
    <td>CB 5715 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZ9KT030328</td>
    <td>2315</td>
    <td>CB 5701 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZ6KT030321</td>
    <td>2314</td>
    <td>CB 5706 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZ9KT030314</td>
    <td>2313</td>
    <td>CB 5700 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZ3KT030308</td>
    <td>2312</td>
    <td>CB 5704 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZ4KT030186</td>
    <td>2311</td>
    <td>CB 5694 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZ3KT030177</td>
    <td>2310</td>
    <td>CB 5703 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZ4KT030169</td>
    <td>2309</td>
    <td>CB 4945 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZXKT030161</td>
    <td>2308</td>
    <td>CB 4966 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZXKT030158</td>
    <td>2307</td>
    <td>CB 4963 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZ9KT030152</td>
    <td>2306</td>
    <td>CB 4951 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZ5KT030147</td>
    <td>2305</td>
    <td>CB 4956 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZ6KT030142</td>
    <td>2304</td>
    <td>CB 4964 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZ6KT030139</td>
    <td>2303</td>
    <td>CB 4967 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZ0KT029973</td>
    <td>2302</td>
    <td>CB 4961 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZ5KT029970</td>
    <td>2301</td>
    <td>CB 4955 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>10.06.2019</td>
    <td></td>
    <td>WMAA23ZZXKT029964</td>
    <td>2300</td>
    <td>CB 4954 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>16.05.2019</td>
    <td></td>
    <td>WMAA23ZZ4KT029961</td>
    <td>1620</td>
    <td>CB 4940 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>16.05.2019</td>
    <td></td>
    <td>WMAA23ZZ5KT029953</td>
    <td>1619</td>
    <td>CB 4932 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>16.05.2019</td>
    <td></td>
    <td>WMAA23ZZ3KT029949</td>
    <td>1618</td>
    <td>CB 4928 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>17.05.2019</td>
    <td></td>
    <td>WMAA23ZZ2KT029943</td>
    <td>1617</td>
    <td>CB 4930 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>16.05.2019</td>
    <td></td>
    <td>WMAA23ZZ0KT029939</td>
    <td>1616</td>
    <td>CB 4923 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>16.05.2019</td>
    <td></td>
    <td>WMAA23ZZ1KT029934</td>
    <td>1615</td>
    <td>CB 4924 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>16.05.2019</td>
    <td></td>
    <td>WMAA23ZZ8KT029929</td>
    <td>1614</td>
    <td>CB 4925 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>16.05.2019</td>
    <td></td>
    <td>WMAA23ZZ9KT029924</td>
    <td>1613</td>
    <td>CB 4938 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>16.05.2019</td>
    <td></td>
    <td>WMAA23ZZXKT029916</td>
    <td>1612</td>
    <td>CB 4960 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>16.05.2019</td>
    <td></td>
    <td>WMAA23ZZ4KT029913</td>
    <td>1611</td>
    <td>CB 4958 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>16.05.2019</td>
    <td></td>
    <td>WMAA23ZZ0KT029908</td>
    <td>1610</td>
    <td>CB 4927 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>16.05.2019</td>
    <td></td>
    <td>WMAA23ZZ5KT029905</td>
    <td>1609</td>
    <td>CB 4926 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>16.05.2019</td>
    <td></td>
    <td>WMAA23ZZ3KT029899</td>
    <td>1608</td>
    <td>CB 4929 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>16.05.2019</td>
    <td></td>
    <td>WMAA23ZZ6KT029895</td>
    <td>1607</td>
    <td>CB 4934 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>16.05.2019</td>
    <td></td>
    <td>WMAA23ZZ0KT029892</td>
    <td>1606</td>
    <td>CB 4931 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>16.05.2019</td>
    <td></td>
    <td>WMAA23ZZXKT029883</td>
    <td>1605</td>
    <td>CB 4936 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>17.05.2019</td>
    <td></td>
    <td>WMAA23ZZ6KT029881</td>
    <td>1604</td>
    <td>CB 4947 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>16.05.2019</td>
    <td></td>
    <td>WMAA23ZZ7KT029873</td>
    <td>1603</td>
    <td>CB 4953 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>16.05.2019</td>
    <td></td>
    <td>WMAA23ZZ9KT029857</td>
    <td>1602</td>
    <td>CB 4943 HM</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2018</td>
    <td>16.05.2019</td>
    <td></td>
    <td>WMAA23ZZ3KT029790</td>
    <td>1601</td>
    <td>CB 4942 HM</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF7J1024870</td>
    <td>3650</td>
    <td>СВ 4931 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF7J1039417</td>
    <td>3651</td>
    <td>СВ 4943 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF9J1039418</td>
    <td>3652</td>
    <td>СВ 4932 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF0J1039419</td>
    <td>3653</td>
    <td>СВ 4935 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF7J1039420</td>
    <td>3654</td>
    <td>СВ 4947 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF9J1039421</td>
    <td>3655</td>
    <td>СВ 4945 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF0J1039422</td>
    <td>3656</td>
    <td>СВ 4946 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF2J1039423</td>
    <td>3657</td>
    <td>СВ 4944 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF4J1039424</td>
    <td>3658</td>
    <td>СВ 4942 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF6J1039425</td>
    <td>3659</td>
    <td>СВ 4941 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF8J1039426</td>
    <td>3660</td>
    <td>СВ 4930 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEFXJ1039427</td>
    <td>3661</td>
    <td>СВ 4936 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF1J1039428</td>
    <td>3662</td>
    <td>СВ 4933 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF3J1039429</td>
    <td>3663</td>
    <td>СВ 4951 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEFXJ1039430</td>
    <td>3664</td>
    <td>СВ 4937 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF1J1039431</td>
    <td>3665</td>
    <td>СВ 4940 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF3J1039432</td>
    <td>3666</td>
    <td>СВ 4938 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF5J1039433</td>
    <td>3667</td>
    <td>СВ 4948 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF7J1039434</td>
    <td>3668</td>
    <td>СВ 4934 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF9J1039435</td>
    <td>3669</td>
    <td>СВ 4950 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF2J1039436</td>
    <td>3670</td>
    <td>СВ 4939 НВ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA CNG</td>
    <td>2018</td>
    <td>01.05.2019</td>
    <td></td>
    <td>LZYTMGEF2J1039437</td>
    <td>3671</td>
    <td>СВ 0906 НК</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTAGEW2J1026177</td>
    <td>3019</td>
    <td>CB 9604 MX</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTAGEW0J1026176</td>
    <td>3018</td>
    <td>CB 9606 MX</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTAGEW9J1026175</td>
    <td>3017</td>
    <td>CB 9607 MX</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTAGEW7J1026174</td>
    <td>3016</td>
    <td>CB 9609 MX</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTAGEW5J1026173</td>
    <td>3015</td>
    <td>CB 9473 MX</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTAGEW3J1026172</td>
    <td>3014</td>
    <td>CB 9610 MX</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTAGEW1J1026171</td>
    <td>3013</td>
    <td>CB 9611 MX</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTMGEW2J1019849</td>
    <td>3012</td>
    <td>CB 9624 MX</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTMGEW8J1015076</td>
    <td>3011</td>
    <td>CB 9612 MX</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTMGEW5J1006626</td>
    <td>2810</td>
    <td>CB 9476 MX</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTAGEW5J1026187</td>
    <td>2809</td>
    <td>CB 9621 MX</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTAGEW3J1026186</td>
    <td>2808</td>
    <td>CB 9618 MX</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTAGEW1J1026185</td>
    <td>2807</td>
    <td>CB 9617 MX</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTAGEWXJ1026184</td>
    <td>2806</td>
    <td>CB 9615 MX</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTAGEW8J1026183</td>
    <td>2805</td>
    <td> CB 9613 MX </td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTAGEW6J1026182</td>
    <td>2804</td>
    <td>CB 9481 MX</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTAGEW4J1026181</td>
    <td>2803</td>
    <td>CB 9486 MX</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTAGEW2J1026180</td>
    <td>2802</td>
    <td>CB 9490 MX</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTAGEW6J1026179</td>
    <td>2801</td>
    <td>CB 9498 MX</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2018</td>
    <td>12.12.2018</td>
    <td></td>
    <td>LZYTAGEW4J1026178</td>
    <td>2800</td>
    <td>CB 9499 MX</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>NMC320LGBLB600124</td>
    <td>3411</td>
    <td>CB 5181 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>01.07.2019</td>
    <td></td>
    <td>NMC320LGBLB600123</td>
    <td>3410</td>
    <td>CB 5157 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600122</td>
    <td>3409</td>
    <td>CB 5160 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600121</td>
    <td>3408</td>
    <td>CB 5178 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600120</td>
    <td>3407</td>
    <td>CB 5189 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600119</td>
    <td>3406</td>
    <td>CB 5397 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600118</td>
    <td>3405</td>
    <td>CB 5175 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600117</td>
    <td>3404</td>
    <td>CB 5502 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600116</td>
    <td>3403</td>
    <td>CB 5193 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600115</td>
    <td>3402</td>
    <td>CB 5171 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600114</td>
    <td>3401</td>
    <td>CB 5168 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600113</td>
    <td>3400</td>
    <td>CB 5162 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600112</td>
    <td>2519</td>
    <td>CB 5166 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600111</td>
    <td>2518</td>
    <td>CB 5393 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600110</td>
    <td>2517</td>
    <td>CB 5391 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600109</td>
    <td>2516</td>
    <td>CB 5412 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600108</td>
    <td>2515</td>
    <td>CB 5332 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600107</td>
    <td>2514</td>
    <td>CB 5415 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600106</td>
    <td>2513</td>
    <td>CB 5164 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600105</td>
    <td>2512</td>
    <td>CB 5417 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600104</td>
    <td>2511</td>
    <td>CB 5413 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600103</td>
    <td>2510</td>
    <td>CB 5356 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600102</td>
    <td>2509</td>
    <td>CB 5359 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600101</td>
    <td>2508</td>
    <td>CB 5364 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600100</td>
    <td>2507</td>
    <td>CB 5370 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600099</td>
    <td>2506</td>
    <td>CB 5330 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600098</td>
    <td>2505</td>
    <td>CB 5430 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600097</td>
    <td>2504</td>
    <td>CB 5152 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600096</td>
    <td>2503</td>
    <td>CB 5318 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600095</td>
    <td>2502</td>
    <td>CB 5372 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600094</td>
    <td>2501</td>
    <td>CB 5187 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>17.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600093</td>
    <td>2500</td>
    <td>CB 5197 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>29.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600092</td>
    <td>1428</td>
    <td>CB 5436 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>28.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600091</td>
    <td>1427</td>
    <td>CB 5404 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>30.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600090</td>
    <td>1426</td>
    <td>CB 5406 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>31.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600089</td>
    <td>1425</td>
    <td>CB 5420 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>31.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600088</td>
    <td>1424</td>
    <td>CB 5439 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>28.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600087</td>
    <td>1423</td>
    <td>CB 5185 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>06.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600086</td>
    <td>1422</td>
    <td>CB 5176 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>30.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600085</td>
    <td>1421</td>
    <td>CB 5322 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>28.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600084</td>
    <td>1420</td>
    <td>CB 5409 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>29.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600083</td>
    <td>1419</td>
    <td>CB 5403 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>29.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600082</td>
    <td>1418</td>
    <td>CB 5173 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>02.01.2019</td>
    <td></td>
    <td>NMC320LGBLB600081</td>
    <td>1417</td>
    <td>CB 5326 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>28.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600080</td>
    <td>1416</td>
    <td> CB 5183 HA </td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>29.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600079</td>
    <td>1415</td>
    <td>CB 5170 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>29.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600078</td>
    <td>1414</td>
    <td>CB 5163 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>29.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600077</td>
    <td>1413</td>
    <td>CB 5158 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>28.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600076</td>
    <td>1412</td>
    <td>CB 5411 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>29.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600075</td>
    <td>1411</td>
    <td>CB 5156 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>29.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600074</td>
    <td>1410</td>
    <td>CB 5339 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>29.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600073</td>
    <td>1409</td>
    <td>CB 5349 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>28.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600072</td>
    <td>1408</td>
    <td>CB 5433 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>30.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600071</td>
    <td>1407</td>
    <td>CB 5311 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>29.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600070</td>
    <td>1406</td>
    <td>CB 5419 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>29.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600069</td>
    <td>1405</td>
    <td>CB 5382 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>29.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600068</td>
    <td>1404</td>
    <td>CB 5301 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>31.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600067</td>
    <td>1403</td>
    <td>CB 5180 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>29.12.2018</td>
    <td></td>
    <td>NMC320LGBLB600066</td>
    <td>1402</td>
    <td>CB 5425 HA</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>06.02.2019</td>
    <td></td>
    <td>NMC320LGBLB600065</td>
    <td>1401</td>
    <td> CB 5386 HA </td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>09.09.2018</td>
    <td></td>
    <td>NMC320LGBLB600003</td>
    <td>7163</td>
    <td>CВ 5684 МТ</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2018</td>
    <td>09.09.2018</td>
    <td></td>
    <td>NMC320LGBLB600002</td>
    <td>7161</td>
    <td>CВ 5683 МТ</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500090</td>
    <td>7159</td>
    <td>CВ 5857 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500089</td>
    <td>7157</td>
    <td>CВ 5859 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500088</td>
    <td>7155</td>
    <td>CВ 5860 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500087</td>
    <td>7153</td>
    <td>CВ 5862 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500086</td>
    <td>7151</td>
    <td>CВ 5809 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500085</td>
    <td>7149</td>
    <td>CВ 5810 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500084</td>
    <td>7147</td>
    <td>CВ 5811 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500083</td>
    <td>7145</td>
    <td>CВ 5812 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500082</td>
    <td>7143</td>
    <td>CВ 5813 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500081</td>
    <td>7141</td>
    <td>CВ 5814 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500080</td>
    <td>7139</td>
    <td>CВ 5815 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500079</td>
    <td>7137</td>
    <td>CВ 6492 СВ</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500078</td>
    <td>7135</td>
    <td>CВ 5819 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500077</td>
    <td>7133</td>
    <td>CВ 5821 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500076</td>
    <td>7131</td>
    <td>CВ 5823 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500075</td>
    <td>7129</td>
    <td>CВ 5826 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500074</td>
    <td>7127</td>
    <td>CВ 5829 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500073</td>
    <td>7125</td>
    <td>CВ 5831 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500072</td>
    <td>7123</td>
    <td>CВ 5807 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500071</td>
    <td>7121</td>
    <td>СВ 5798 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500070</td>
    <td>7119</td>
    <td>CВ 6499 СВ</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500069</td>
    <td>7117</td>
    <td>СВ 5795 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500068</td>
    <td>7115</td>
    <td>CВ 5782 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500067</td>
    <td>7113</td>
    <td>СВ 5784 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500066</td>
    <td>7111</td>
    <td>CВ 5788 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500065</td>
    <td>7109</td>
    <td>СВ 5776 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500064</td>
    <td>7107</td>
    <td>CВ 5780 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500063</td>
    <td>7105</td>
    <td>СВ 5771 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500062</td>
    <td>7103</td>
    <td>CВ 5765 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500061</td>
    <td>7101</td>
    <td>СВ 5763 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500060</td>
    <td>7099</td>
    <td>CВ 5769 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500059</td>
    <td>7097</td>
    <td>СВ 5735 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500058</td>
    <td>7095</td>
    <td>CВ 5756 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500057</td>
    <td>7093</td>
    <td>СВ 5753 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500056</td>
    <td>7091</td>
    <td>CВ 5750 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500055</td>
    <td>7089</td>
    <td>СВ 5746 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500054</td>
    <td>7087</td>
    <td>CВ 5743 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500053</td>
    <td>7085</td>
    <td>СВ 6497 СВ</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>26.07.2017</td>
    <td></td>
    <td>NMC320LGBLB500052</td>
    <td>7083</td>
    <td>CВ 4123 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>26.07.2017</td>
    <td></td>
    <td>NMC320LGBLB500051</td>
    <td>7081</td>
    <td>СВ 4104 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500050</td>
    <td>7079</td>
    <td>CВ 5729 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500049</td>
    <td>7077</td>
    <td>СВ 4108 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500048</td>
    <td>7075</td>
    <td>CВ 4112 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500047</td>
    <td>7073</td>
    <td>СВ 4116 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>26.07.2017</td>
    <td></td>
    <td>NMC320LGBLB500046</td>
    <td>7071</td>
    <td>CВ 4117 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>26.07.2017</td>
    <td></td>
    <td>NMC320LGBLB500045</td>
    <td>7069</td>
    <td>СВ 4118 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>26.07.2017</td>
    <td></td>
    <td>NMC320LGBLB500044</td>
    <td>7067</td>
    <td>CВ 4124 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>26.07.2017</td>
    <td></td>
    <td>NMC320LGBLB500043</td>
    <td>7065</td>
    <td>СВ 4120 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>26.07.2017</td>
    <td></td>
    <td>NMC320LGBLB500042</td>
    <td>7063</td>
    <td>CВ 4119 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>26.07.2017</td>
    <td></td>
    <td>NMC320LGBLB500041</td>
    <td>7061</td>
    <td>СВ 4027 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>26.07.2017</td>
    <td></td>
    <td>NMC320LGBLB500040</td>
    <td>7059</td>
    <td>CВ 4037 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>26.07.2017</td>
    <td></td>
    <td>NMC320LGBLB500039</td>
    <td>7057</td>
    <td>СВ 4035 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>26.07.2017</td>
    <td></td>
    <td>NMC320LGBLB500038</td>
    <td>7055</td>
    <td>CВ 4033 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>26.07.2017</td>
    <td></td>
    <td>NMC320LGBLB500037</td>
    <td>7053</td>
    <td>СВ 4031 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>26.07.2017</td>
    <td></td>
    <td>NMC320LGBLB500036</td>
    <td>7051</td>
    <td>CВ 4036 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>26.07.2017</td>
    <td></td>
    <td>NMC320LGBLB500035</td>
    <td>7049</td>
    <td>СВ 4034 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>26.07.2017</td>
    <td></td>
    <td>NMC320LGBLB500034</td>
    <td>7047</td>
    <td>CВ 4032 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>26.07.2017</td>
    <td></td>
    <td>NMC320LGBLB500033</td>
    <td>7045</td>
    <td>СВ 4028 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>26.07.2017</td>
    <td></td>
    <td>NMC320LGBLB500032</td>
    <td>7043</td>
    <td>CВ 4029 КР</td>
  </tr>
  <tr>
    <td>BMC Procity 12 CNG</td>
    <td>2017</td>
    <td>02.08.2017</td>
    <td></td>
    <td>NMC320LGBLB500031</td>
    <td>7041</td>
    <td>CВ 5854 КР</td>
  </tr>
  <tr>
    <td>Solaris Urbino 12 Hybrid</td>
    <td>2017</td>
    <td>03.07.2018</td>
    <td></td>
    <td>SUU241163HB017494</td>
    <td>1640</td>
    <td>PZ 109PY</td>
  </tr>
  <tr>
    <td>Karsan Jest</td>
    <td>2016</td>
    <td>04.12.2017</td>
    <td></td>
    <td>NLNC2ELLA10005433</td>
    <td>1640</td>
    <td>В 3326 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE60G1026355</td>
    <td>1201</td>
    <td>CВ 0466 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE6XG1019199</td>
    <td>1202</td>
    <td>СВ 0464 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE60G1026422</td>
    <td>1203</td>
    <td>CВ 0461 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE62G1026423</td>
    <td>1204</td>
    <td>CВ 0459 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE66G1026425</td>
    <td>1205</td>
    <td>СВ 0456 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE66G1026427</td>
    <td>1206</td>
    <td>CВ 0455 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE62G1026356</td>
    <td>1207</td>
    <td>CВ 0453 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE64G1026357</td>
    <td>1208</td>
    <td>СВ 0450 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE66G1026358</td>
    <td>1209</td>
    <td>CВ 0447 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE68G1026359</td>
    <td>1210</td>
    <td>CВ 0445 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE64G1026360</td>
    <td>1211</td>
    <td>СВ 0441 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE66G1026361</td>
    <td>1212</td>
    <td>CВ 0485 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE68G1026362</td>
    <td>1213</td>
    <td>CВ 0439 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE6XG1026363</td>
    <td>1214</td>
    <td>СВ 0437 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE61G1026364</td>
    <td>1215</td>
    <td>CВ 0557 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE63G1026365</td>
    <td>1216</td>
    <td>CВ 0556 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE65G1026366</td>
    <td>1217</td>
    <td>СВ 0554 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE63G1008304</td>
    <td>1218</td>
    <td>CВ 0583 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE69G1026354</td>
    <td>1219</td>
    <td>СВ 0587 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE61G1026400</td>
    <td>1220</td>
    <td>СВ 2606 СТ</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE69G1026421</td>
    <td>1221</td>
    <td>CВ 0592 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE64G1026424</td>
    <td>1222</td>
    <td>СВ 0596 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE68G1026426</td>
    <td>1223</td>
    <td>CВ 0602 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE61G1026428</td>
    <td>1224</td>
    <td>CВ 0605 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE63G1026429</td>
    <td>1225</td>
    <td>СВ 0610 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE6XG1026430</td>
    <td>1226</td>
    <td>CВ 0615 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE61G1026431</td>
    <td>1227</td>
    <td>CВ 0617 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE67G1026367</td>
    <td>2046</td>
    <td>CВ 0553 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE69G1026368</td>
    <td>2047</td>
    <td>СВ 0552 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE60G1026369</td>
    <td>2048</td>
    <td>CВ 0551 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE67G1026370</td>
    <td>2049</td>
    <td>CВ 0548 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE69G1026371</td>
    <td>2050</td>
    <td>CВ 0546 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE60G1026372</td>
    <td>2051</td>
    <td>СВ 0543 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE62G1026373</td>
    <td>2052</td>
    <td>CВ 0537 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE64G1026374</td>
    <td>2053</td>
    <td>CВ 0535 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE66G1026375</td>
    <td>2054</td>
    <td>СВ 0533 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE68G1026376</td>
    <td>2055</td>
    <td>СВ 0545 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE6XG1026377</td>
    <td>2056</td>
    <td>CВ 0542 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE61G1026378</td>
    <td>2057</td>
    <td>СВ 0549 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE63G1026379</td>
    <td>2058</td>
    <td>CВ 0547 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE6XG1026380</td>
    <td>2059</td>
    <td>СВ 0544 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE61G1026381</td>
    <td>2060</td>
    <td>СВ 0541 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE63G1026382</td>
    <td>2061</td>
    <td>CВ 0538 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE65G1026383</td>
    <td>2062</td>
    <td>СВ 0530 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE67G1026384</td>
    <td>2063</td>
    <td>CВ 0526 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE69G1026385</td>
    <td>2064</td>
    <td>СВ 0522 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE60G1026386</td>
    <td>2065</td>
    <td>CВ 0539 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE62G1026387</td>
    <td>2066</td>
    <td>CВ 0536 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE64G1026388</td>
    <td>2067</td>
    <td>СВ 0532 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE66G1026389</td>
    <td>2068</td>
    <td>СВ 0529 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE62G1026390</td>
    <td>2069</td>
    <td>СВ 0527 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE64G1026391</td>
    <td>2070</td>
    <td>СВ 0525 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE66G1026392</td>
    <td>2071</td>
    <td>CВ 0521 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE68G1026393</td>
    <td>2072</td>
    <td>CВ 0519 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE6XG1026394</td>
    <td>2073</td>
    <td>СВ 0518 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE63G1026432</td>
    <td>2074</td>
    <td>CВ 0539 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE65G1026433</td>
    <td>2075</td>
    <td>СВ 0542 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE67G1026434</td>
    <td>2076</td>
    <td> CВ 0545 ВС </td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE69G1026435</td>
    <td>2077</td>
    <td> CВ 0534 ВС </td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE60G1026436</td>
    <td>2078</td>
    <td> СВ 0536 ВС </td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE62G1026437</td>
    <td>2079</td>
    <td>СВ 0530 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE64G1026438</td>
    <td>2080</td>
    <td> CВ 0547 ВС </td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE66G1026439</td>
    <td>2081</td>
    <td>СВ 0548 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE62G1026440</td>
    <td>2082</td>
    <td>CВ 0549 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE64G1026441</td>
    <td>2083</td>
    <td>CВ 0551 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE66G1026442</td>
    <td>2084</td>
    <td>CВ 0554 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE68G1026443</td>
    <td>2085</td>
    <td>СВ 0558 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE6XG1026444</td>
    <td>2086</td>
    <td>CВ 0568 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE61G1026445</td>
    <td>2087</td>
    <td>CВ 0570 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE63G1026446</td>
    <td>2088</td>
    <td>СВ 0572 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE65G1026447</td>
    <td>2089</td>
    <td>CВ 0574 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE67G1026448</td>
    <td>2090</td>
    <td>CВ 0577 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE61G1026395</td>
    <td>3600</td>
    <td>СВ 0517 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE63G1026396</td>
    <td>3601</td>
    <td>СВ 0516 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE65G1026397</td>
    <td>3602-&gt;1228</td>
    <td>CВ 0515 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE67G1026398</td>
    <td>3603</td>
    <td>СВ 0514 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE69G1026399</td>
    <td>3604-&gt;1229</td>
    <td>CВ 0513 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE63G1026401</td>
    <td>3605</td>
    <td>CВ 0512 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE65G1026402</td>
    <td>3606</td>
    <td>CВ 0481 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE67G1026403</td>
    <td>3607</td>
    <td>СВ 0483 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE69G1026404</td>
    <td>3608</td>
    <td>СВ 0484 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE60G1026405</td>
    <td>3609</td>
    <td>СВ 0488 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE62G1026406</td>
    <td>3610</td>
    <td>CВ 0490 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE64G1026407</td>
    <td>3611</td>
    <td>CВ 0493 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE66G1026408</td>
    <td>3612</td>
    <td>CВ 0496 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE68G1026409</td>
    <td>3613</td>
    <td>CВ 0499 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE64G1026410</td>
    <td>3614</td>
    <td>СВ 0502 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE66G1026411</td>
    <td>3615</td>
    <td>CВ 0509 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE68G1026412</td>
    <td>3616</td>
    <td>CВ 0507 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE6XG1026413</td>
    <td>3617</td>
    <td>СВ 0511 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE61G1026414</td>
    <td>3618</td>
    <td>CВ 0478 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE63G1026415</td>
    <td>3619-&gt;1230</td>
    <td>CВ 0476 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE65G1026416</td>
    <td>3620</td>
    <td>CВ 0473 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE67G1026417</td>
    <td>3621</td>
    <td>СВ 0472 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE69G1026418</td>
    <td>3622</td>
    <td>CВ 0469 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE60G1026419</td>
    <td>3623</td>
    <td>СВ 0534 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>01.09.2016</td>
    <td></td>
    <td>LZYTMGE67G1026420</td>
    <td>3624-&gt;1231</td>
    <td> CВ 0467 ВР</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE69G1026449</td>
    <td>3625</td>
    <td>CВ 0580 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE65G1026450</td>
    <td>3626</td>
    <td> СВ 0640 ВС </td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE67G1026451</td>
    <td>3627</td>
    <td>CВ 0642 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE69G1026452</td>
    <td>3628</td>
    <td> CВ 0644 ВС </td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE60G1026453</td>
    <td>3629</td>
    <td>СВ 0646 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE62G1026454</td>
    <td>3630</td>
    <td>CВ 0631 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE64G1026455</td>
    <td>3631</td>
    <td>CВ 0635 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE66G1026456</td>
    <td>3632</td>
    <td>CB 0619 BC</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE68G1026457</td>
    <td>3633</td>
    <td>CВ 0624 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE6XG1026458</td>
    <td>3634</td>
    <td> CВ 0627 ВС </td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE61G1026459</td>
    <td>3635-&gt;1232</td>
    <td>CВ 0630 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE68G1026460</td>
    <td>3636</td>
    <td>CВ 0802 ВС</td>
  </tr>
  <tr>
    <td>Yutong ZK6126HGA</td>
    <td>2016</td>
    <td>26.09.2016.</td>
    <td></td>
    <td>LZYTMGE6XG1026461</td>
    <td>3637</td>
    <td>CВ 0635 ВС</td>
  </tr>
  <tr>
    <td>SOR EBN 11.1</td>
    <td>2016</td>
    <td>23.03.2017</td>
    <td>28.04.2017</td>
    <td>TK9N4EXX4GLSL5012</td>
    <td>3639</td>
    <td>5E6 6529</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro ME</td>
    <td>2015</td>
    <td>05.09.2020</td>
    <td></td>
    <td>WEB63372013270508</td>
    <td>1311</td>
    <td>СВ 2469 РТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro ME</td>
    <td>2015</td>
    <td>05.09.2020</td>
    <td></td>
    <td>WEB63372013270513</td>
    <td>1312</td>
    <td>СВ 2465 РТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro ME</td>
    <td>2015</td>
    <td>05.09.2020</td>
    <td></td>
    <td>WEB63372013270515</td>
    <td>1313</td>
    <td>СВ 2461 РТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro ME</td>
    <td>2015</td>
    <td>05.09.2020</td>
    <td></td>
    <td>WEB63372013270517</td>
    <td>1314</td>
    <td>СВ 2459 РТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro ME</td>
    <td>2015</td>
    <td>05.09.2020</td>
    <td></td>
    <td>WEB63372013270518</td>
    <td>1315</td>
    <td>СВ 2470 РТ</td>
  </tr>
  <tr>
    <td>Solaris Urbino IV 12 Electric</td>
    <td>2015</td>
    <td>23.08.2017</td>
    <td>22.09.2017</td>
    <td>SUU24116EFB015043</td>
    <td>1702-&gt;2702</td>
    <td>PZ 076MG</td>
  </tr>
  <tr>
    <td>Yutong E12LF</td>
    <td>2015</td>
    <td>15.01.2017</td>
    <td>30.06.2017</td>
    <td>LZYTAGBW0F1019613</td>
    <td>3638</td>
    <td>СВ 3049 КА</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ2FR014894</td>
    <td>1185</td>
    <td>CВ 7107 АС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ4FR014895</td>
    <td>1186</td>
    <td>CВ 7108 АС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ6FR014896</td>
    <td>2027</td>
    <td>CВ 7101 АС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ8FR014897</td>
    <td>2028</td>
    <td>CВ 7103 АС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ1FR014899</td>
    <td>2029</td>
    <td>CВ 7112 АС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ6FR014901</td>
    <td>2030</td>
    <td>CВ 7098 АС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZXFR014903</td>
    <td>3124</td>
    <td>CВ 7074 АC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ5FR014906</td>
    <td>3125</td>
    <td> CВ 7081 АC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ0FR014909</td>
    <td>3126</td>
    <td>CВ 7084 АC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ9FR014911</td>
    <td>3127</td>
    <td>CВ 7082 АC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ0FR014912</td>
    <td>3128</td>
    <td>CВ 7087 АC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ2FR014913</td>
    <td>3129</td>
    <td>CВ 7092 АC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ8FR014916</td>
    <td>3130</td>
    <td>CВ 7096 АC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZXFR014917</td>
    <td>3131</td>
    <td> CВ 7095 АC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ3FR014919</td>
    <td>3132</td>
    <td> CВ 7062 АC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZXFR014920</td>
    <td>3133</td>
    <td>CВ 7064 АC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ1FR014921</td>
    <td>3134</td>
    <td> CВ 7099 АC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ3FR014922</td>
    <td>3135</td>
    <td>CВ 7065 АC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ7FR014924</td>
    <td>3136</td>
    <td>CВ 7068 АC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ9FR014925</td>
    <td>3137</td>
    <td> CВ 7072 АC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ2FR014930</td>
    <td>2031</td>
    <td> CВ 7052 АС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ4FR014931</td>
    <td>2032</td>
    <td> CВ 6949 AC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ6FR014932</td>
    <td>2033</td>
    <td> CВ 7058 АС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ8FR014933</td>
    <td>2034</td>
    <td> CВ 7054 АС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZXFR014934</td>
    <td>2035</td>
    <td> CB 7055 AC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ1FR014935</td>
    <td>2036</td>
    <td> CВ 6947 АС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ7FR014938</td>
    <td>2037</td>
    <td> CВ 6944 АС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ9FR014939</td>
    <td>2038</td>
    <td>CВ 6942 АС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>04.05.2015</td>
    <td></td>
    <td>WMAA23ZZ7FR014941</td>
    <td>2039</td>
    <td> CВ 7059 АС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>01.06.2015</td>
    <td></td>
    <td>WMAA23ZZ2FR014944</td>
    <td>1187</td>
    <td> CВ 4348 АК </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>01.06.2015</td>
    <td></td>
    <td>WMAA23ZZ3FR014970</td>
    <td>1188</td>
    <td> CВ 4364 АК </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>01.06.2015</td>
    <td></td>
    <td>WMAA23ZZ0FR014974</td>
    <td>1189</td>
    <td>CВ 4361 АК </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>01.06.2015</td>
    <td></td>
    <td>WMAA23ZZ4FR014976</td>
    <td>2040</td>
    <td>CВ 4363 АК </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>01.06.2015</td>
    <td></td>
    <td>WMAA23ZZ6FR014977</td>
    <td>2041</td>
    <td> CВ 4357 АК </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>01.06.2015</td>
    <td></td>
    <td>WMAA23ZZ6FR015045</td>
    <td>2042</td>
    <td> CВ 4368 АК </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>01.06.2015</td>
    <td></td>
    <td>WMAA23ZZ1FR015051</td>
    <td>2043</td>
    <td>CВ 4351 АК </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>01.06.2015</td>
    <td></td>
    <td>WMAA23ZZ4FR015058</td>
    <td>2044</td>
    <td>CВ 4355 АК </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>01.06.2015</td>
    <td></td>
    <td>WMAA23ZZ3FR015066</td>
    <td>2045</td>
    <td> CВ 4353 АК </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>01.06.2015</td>
    <td></td>
    <td>WMAA23ZZ7FR015071</td>
    <td>3138</td>
    <td> CВ 4359 АК </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>01.06.2015</td>
    <td></td>
    <td>WMAA23ZZ4FR015075</td>
    <td>3139</td>
    <td> CВ 4366 АК </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>28.03.2015</td>
    <td></td>
    <td>WMAA23ZZ8FR014236</td>
    <td>1175</td>
    <td>СВ 1752 AС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>28.03.2015</td>
    <td></td>
    <td>WMAA23ZZXFR014237</td>
    <td>1176</td>
    <td>СВ 1756 AС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>28.03.2015</td>
    <td></td>
    <td>WMAA23ZZXFR014240</td>
    <td>1177</td>
    <td>СВ 1757 AС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>28.03.2015</td>
    <td></td>
    <td>WMAA23ZZ1FR014241</td>
    <td>1178</td>
    <td>СВ 1767 AС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>28.03.2015</td>
    <td></td>
    <td>WMAA23ZZ7FR014843</td>
    <td>1179</td>
    <td>СВ 1770 AС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>28.03.2015</td>
    <td></td>
    <td>WMAA23ZZ9FR014844</td>
    <td>1180</td>
    <td>СВ 1781 AС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>28.03.2015</td>
    <td></td>
    <td>WMAA23ZZ0FR014862</td>
    <td>1181</td>
    <td>СВ 1784 AС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>28.03.2015</td>
    <td></td>
    <td>WMAA23ZZ2FR014863</td>
    <td>1182</td>
    <td>СВ 1785 AС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>28.03.2015</td>
    <td></td>
    <td>WMAA23ZZ4FR014864</td>
    <td>1183</td>
    <td>СВ 1808 AС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>28.03.2015</td>
    <td></td>
    <td>WMAA23ZZ0FR014876</td>
    <td>1184</td>
    <td>СВ 1807 AС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>30.03.2015</td>
    <td></td>
    <td>WMAA23ZZ2FR014877</td>
    <td>2017</td>
    <td>СВ 1806 AС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>30.03.2015</td>
    <td></td>
    <td>WMAA23ZZ4FR014878</td>
    <td>2018</td>
    <td>СВ 1805 AС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>30.03.2015</td>
    <td></td>
    <td>WMAA23ZZXFR014884</td>
    <td>2019</td>
    <td>СВ 1804 AС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>30.03.2015</td>
    <td></td>
    <td>WMAA23ZZ1FR014885</td>
    <td>2020</td>
    <td>СВ 1803 AС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>30.03.2015</td>
    <td></td>
    <td>WMAA23ZZ3FR014886</td>
    <td>2021</td>
    <td>СВ 1786 AС</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>30.03.2015</td>
    <td></td>
    <td>WMAA23ZZ7FR014888</td>
    <td>2022</td>
    <td>СВ 4743 PH </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>30.03.2015</td>
    <td></td>
    <td>WMAA23ZZ9FR014889</td>
    <td>2023</td>
    <td>СВ 1768 AС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>30.03.2015</td>
    <td></td>
    <td>WMAA23ZZ5FR014890</td>
    <td>2024</td>
    <td>СВ 1754 AС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>30.03.2015</td>
    <td></td>
    <td>WMAA23ZZ7FR014891</td>
    <td>2025</td>
    <td>СВ 1753 AС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>30.03.2015</td>
    <td></td>
    <td>WMAA23ZZ0FR014893</td>
    <td>2026</td>
    <td>СВ 1748 AС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ3ER014174</td>
    <td>3107</td>
    <td> СА 9102 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ9ER014163</td>
    <td>3106</td>
    <td> CА 9101 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ5ER014158</td>
    <td>3105</td>
    <td> СА 9093 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ1ER014156</td>
    <td>3104</td>
    <td>CА 9077 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ8ER014154</td>
    <td>3103</td>
    <td>CА 9090 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ0ER014147</td>
    <td>3102</td>
    <td> CА 9091 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZXER014138</td>
    <td>3101</td>
    <td> СА 9076 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ2ER014134</td>
    <td>3100</td>
    <td> СА 9089 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ7ER014131</td>
    <td>2015</td>
    <td> СА 9078 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ5ER014130</td>
    <td>2014</td>
    <td> СА 9079 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZXER014124</td>
    <td>2013</td>
    <td>СА 9080 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ5ER014113</td>
    <td>2012</td>
    <td> СА 9081 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ3ER014109</td>
    <td>2011</td>
    <td> CА 9082 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZXER014107</td>
    <td>2010</td>
    <td> СА 9083 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ8ER014106</td>
    <td>2009</td>
    <td> СА 9094 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ4ER014104</td>
    <td>2008</td>
    <td>СА 9095 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ2ER014098</td>
    <td>2007</td>
    <td> СА 9096 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ1ER014092</td>
    <td>2006</td>
    <td> CА 9097 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ1ER014089</td>
    <td>2005</td>
    <td> СА 9084 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ8ER014087</td>
    <td>2004</td>
    <td> СА 9085 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ5ER014080</td>
    <td>2003</td>
    <td> CА 9086 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ8ER014073</td>
    <td>2002</td>
    <td> СА 9087 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ7ER014078</td>
    <td>2001</td>
    <td> CА 9088 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ6ER014072</td>
    <td>2000</td>
    <td> СА 9100 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>01.02.2015</td>
    <td></td>
    <td>WMAA23ZZ0ER014182</td>
    <td>1174</td>
    <td> СB 8977 AA </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>01.02.2015</td>
    <td></td>
    <td>WMAA23ZZ2ER014179</td>
    <td>1173</td>
    <td>СB 8980 AA </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>01.02.2015</td>
    <td></td>
    <td>WMAA23ZZ0ER014178</td>
    <td>1172</td>
    <td> СВ 8976 AA </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ4ER014071</td>
    <td>1171</td>
    <td> СА 9099 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>29.09.2014</td>
    <td></td>
    <td>WMAA23ZZ6ER014069</td>
    <td>1170</td>
    <td> СА 9098 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ9ER014048</td>
    <td>1169</td>
    <td> СА 1068 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ5ER014032</td>
    <td>1168</td>
    <td> CA 1067 XC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ1ER014044</td>
    <td>1167</td>
    <td>CA 1066 XC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ3ER014059</td>
    <td>1166</td>
    <td> CA 1065 XC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ8ER014039</td>
    <td>1165</td>
    <td> CA 1064 XC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ3ER014062</td>
    <td>1164</td>
    <td> CA 1063 XC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ7ER014064</td>
    <td>1163</td>
    <td> CA 1062 XC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ6ER014038</td>
    <td>1162</td>
    <td> CA 1061 XC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ6ER014024</td>
    <td>1161</td>
    <td>СА 1104 ХС </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ7ER014033</td>
    <td>1160</td>
    <td> CA 1099 XC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ8ER014056</td>
    <td>1159</td>
    <td> CA 1098 XC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ6ER014055</td>
    <td>1158</td>
    <td> CA 1096 XC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ4ER013955</td>
    <td>1157</td>
    <td>CA 1091 XC</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ2ER014067</td>
    <td>1156</td>
    <td> CA 1090 XC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ8ER014045</td>
    <td>1155</td>
    <td> CA 1088 XC</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>09.03.2015</td>
    <td></td>
    <td>WMAA23ZZ4FR014184</td>
    <td>2016</td>
    <td> СВ 6064 AB </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>09.03.2015</td>
    <td></td>
    <td>WMAA23ZZ6FR014185</td>
    <td>3108</td>
    <td> СВ 6067 AB </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>09.03.2015</td>
    <td></td>
    <td>WMAA23ZZ3FR014189</td>
    <td>3109</td>
    <td> СВ 6059 AB </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>09.03.2015</td>
    <td></td>
    <td>WMAA23ZZ3FR014192</td>
    <td>3110</td>
    <td> СВ 6057 AB </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>09.03.2015</td>
    <td></td>
    <td>WMAA23ZZ7FR014194</td>
    <td>3111</td>
    <td> СВ 6052 АB </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>09.03.2015</td>
    <td></td>
    <td>WMAA23ZZ0FR014196</td>
    <td>3112</td>
    <td> СВ 6049 AB </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>09.03.2015</td>
    <td></td>
    <td>WMAA23ZZ9FR014200</td>
    <td>3113</td>
    <td> СВ 6063 AB </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>09.03.2015</td>
    <td></td>
    <td>WMAA23ZZ6FR014204</td>
    <td>3114</td>
    <td> СВ 6062 AB </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>09.03.2015</td>
    <td></td>
    <td>WMAA23ZZ3FR014208</td>
    <td>3115</td>
    <td> СВ 6058 AB </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>09.03.2015</td>
    <td></td>
    <td>WMAA23ZZ1FR014210</td>
    <td>3116</td>
    <td> СВ 6055 AB </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>09.03.2015</td>
    <td></td>
    <td>WMAA23ZZ3FR014211</td>
    <td>3117</td>
    <td> СВ 6051 AB </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>09.03.2015</td>
    <td></td>
    <td>WMAA23ZZ0FR014215</td>
    <td>3118</td>
    <td> СВ 6056 AB </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>09.03.2015</td>
    <td></td>
    <td>WMAA23ZZ4FR014217</td>
    <td>3119</td>
    <td> СВ 6053 AB </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>09.03.2015</td>
    <td></td>
    <td>WMAA23ZZ8FR014222</td>
    <td>3120</td>
    <td> СВ 6046 AB </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>09.03.2015</td>
    <td></td>
    <td>WMAA23ZZ1FR014224</td>
    <td>3121</td>
    <td> СВ 6068 АB </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>09.03.2015</td>
    <td></td>
    <td>WMAA23ZZ9FR014228</td>
    <td>3122</td>
    <td> СВ 6065 AB </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>09.03.2015</td>
    <td></td>
    <td>WMAA23ZZ2FR014233</td>
    <td>3123</td>
    <td> СВ 6054 AB </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ8ER014053</td>
    <td>1154</td>
    <td> CA 1087 XC</td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ8ER014042</td>
    <td>1153</td>
    <td>CA 1072 XC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZXER014043</td>
    <td>1152</td>
    <td> CA 1071 XC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ9ER014051</td>
    <td>1151</td>
    <td> CA 1070 XC </td>
  </tr>
  <tr>
    <td>MAN A23 Lion's City G NG313 CNG</td>
    <td>2014</td>
    <td>27.08.2014</td>
    <td></td>
    <td>WMAA23ZZ5ER014029</td>
    <td>1150</td>
    <td>CA 1069 XC </td>
  </tr>
  <tr>
    <td>SOR EBN 8</td>
    <td>2013</td>
    <td>02.05.2017</td>
    <td>21.08.2017</td>
    <td>TK9N5EXXSDLSL5002</td>
    <td>3640</td>
    <td>5E4 8103</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro M</td>
    <td>2012</td>
    <td>01.01.2019</td>
    <td></td>
    <td>WEB63325113253476</td>
    <td>1307</td>
    <td>СВ 6520 НВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro M</td>
    <td>2012</td>
    <td>01.01.2019</td>
    <td></td>
    <td>WEB63325213260432</td>
    <td>1309</td>
    <td>СВ 6506 НВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro M</td>
    <td>2012</td>
    <td>10.01.2019</td>
    <td></td>
    <td>WEB63325213260433</td>
    <td>1310</td>
    <td>СВ 6510 НВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro M</td>
    <td>2011</td>
    <td>22.12.2018</td>
    <td></td>
    <td>WEB63325213256084</td>
    <td>1301</td>
    <td>СВ 0735 НВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro M</td>
    <td>2011</td>
    <td>22.12.2018</td>
    <td></td>
    <td>WEB63325213256087</td>
    <td>1302</td>
    <td>СВ 0737 НВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro M</td>
    <td>2011</td>
    <td>22.12.2018</td>
    <td></td>
    <td>WEB63325213257038</td>
    <td>1303</td>
    <td>СВ 0437 НВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro M</td>
    <td>2011</td>
    <td>22.12.2018</td>
    <td></td>
    <td>WEB63325213257039</td>
    <td>1304</td>
    <td>СВ 0411 НВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro M</td>
    <td>2011</td>
    <td>22.12.2018</td>
    <td></td>
    <td>WEB63325213257040</td>
    <td>1305</td>
    <td>СВ 0739 НВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro M</td>
    <td>2011</td>
    <td>22.12.2018</td>
    <td></td>
    <td>WEB63325213257045</td>
    <td>1306</td>
    <td>СВ 0432 НВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O560 Intouro M</td>
    <td>2011</td>
    <td>05.01.2019</td>
    <td></td>
    <td>WEB63325213257960</td>
    <td>1308</td>
    <td>СВ 6518 НВ</td>
  </tr>
  <tr>
    <td>Tezeller Tezauto LF 280</td>
    <td>2010</td>
    <td>06.02.2011</td>
    <td></td>
    <td>NLZT32L31BH237012</td>
    <td>5002</td>
    <td>СА 0478 РХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O530 Citaro CNG II</td>
    <td>2009</td>
    <td></td>
    <td></td>
    <td>WEB62802013117336</td>
    <td>60-&gt;7641-&gt;5018</td>
    <td>CB 2271 CM</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O530 Citaro CNG II</td>
    <td>2009</td>
    <td>15.04.2021</td>
    <td></td>
    <td>WEB62802013117334</td>
    <td>58-&gt;7639-&gt;5001</td>
    <td>СВ 2275 СМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O530 Citaro CNG II</td>
    <td>2009</td>
    <td>16.04.2021</td>
    <td></td>
    <td>WEB62802013117333</td>
    <td>57-&gt;7640-&gt;5017</td>
    <td>СВ 2273 СМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013249005</td>
    <td>9108</td>
    <td>CА 3083 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013249006</td>
    <td>9102</td>
    <td>CА 3094 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013249007</td>
    <td>9113</td>
    <td>CА 3095 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013249008</td>
    <td>9107</td>
    <td>CА 3085 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013249009</td>
    <td>9104</td>
    <td>CА 3096 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF G</td>
    <td>2009</td>
    <td>01.07.2009</td>
    <td>05.2013</td>
    <td>WEB62832013246326</td>
    <td>9060-&gt;7944-&gt;37</td>
    <td><a href="http://s1.busphoto.eu/photo/02/72/80/272800.jpg">SK 717FX</a></td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013249010</td>
    <td>9111</td>
    <td>CА 3086 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013249012</td>
    <td>9106</td>
    <td>CА 3091 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013249013</td>
    <td>9103</td>
    <td>CА 3092 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013249014</td>
    <td>9109</td>
    <td>CА 3090 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013249015</td>
    <td>9110</td>
    <td>CА 3087 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013249017</td>
    <td>9112</td>
    <td>CА 3088 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013249018</td>
    <td>9105</td>
    <td>CА 3089 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013249019</td>
    <td>9114</td>
    <td>CА 3084 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013249020</td>
    <td>9101</td>
    <td>CА 3093 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013249226</td>
    <td>9058</td>
    <td>CА 9558 НТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF G</td>
    <td>2009</td>
    <td>10.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62832013249238</td>
    <td>9071</td>
    <td>CА 1671 НХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF G</td>
    <td>2009</td>
    <td>10.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62832013249239</td>
    <td>9072</td>
    <td>CА 1672 НХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF G</td>
    <td>2009</td>
    <td>10.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62832013249240</td>
    <td>9073</td>
    <td>CА 1673 НХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF G</td>
    <td>2009</td>
    <td>10.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62832013249236</td>
    <td>9074</td>
    <td>CА 1669 НХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF G</td>
    <td>2009</td>
    <td>10.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62832013249237</td>
    <td>9075</td>
    <td>CА 1670 НХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF G</td>
    <td>2009</td>
    <td>10.07.2009</td>
    <td>05.2013</td>
    <td>WEB62832013249241</td>
    <td>9076-&gt;7942-&gt;36</td>
    <td><a href="https://s20.flog.pl/media/foto/11282738_mercedes-conecto-g-lf-36.jpg">SK 716FX</a></td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF G</td>
    <td>2009</td>
    <td>10.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62832013249242</td>
    <td>9077</td>
    <td>CА 1667 НХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF G</td>
    <td>2009</td>
    <td>10.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62832013249243</td>
    <td>9078</td>
    <td>CА 1668 НХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.07.2009</td>
    <td>27.01.2017</td>
    <td>WEB62831013249227</td>
    <td>9070</td>
    <td>CА 9400 НТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013249228</td>
    <td>9059</td>
    <td>CА 9551 НТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013249229</td>
    <td>9068</td>
    <td>CА 9552 НТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013249230</td>
    <td>9069</td>
    <td>CА 9553 НТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013249231</td>
    <td>9067</td>
    <td>CА 9567 НТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013249232</td>
    <td>9066</td>
    <td>CА 9566 НТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013249234</td>
    <td>9065</td>
    <td>CА 9565 НТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013249235</td>
    <td>9064</td>
    <td>CА 9564 НТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013249243</td>
    <td>9057</td>
    <td>CА 9557 НТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013249894</td>
    <td>9063</td>
    <td>CА 9563 НТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013249895</td>
    <td>9062</td>
    <td>CА 9562 НТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013249896</td>
    <td>9056</td>
    <td>CА 9556 НТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013249897</td>
    <td>9055</td>
    <td>CА 9554 НТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.07.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013249898</td>
    <td>9061</td>
    <td>CА 9561 НТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>26.09.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013251927</td>
    <td>9096</td>
    <td>CА 3846 РА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>26.09.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013251928</td>
    <td>9084</td>
    <td>CА 4113 РА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>26.09.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013251929</td>
    <td>9094</td>
    <td>CА 4116 РА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>26.09.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013251930</td>
    <td>9098</td>
    <td>CА 3847 РА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>26.09.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013251931</td>
    <td>9080</td>
    <td>CА 3848 РА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>26.09.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013251932</td>
    <td>9100</td>
    <td>CА 4118 РА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>26.09.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013251933</td>
    <td>9088</td>
    <td>CА 3849 РА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>26.09.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013251934</td>
    <td>9097</td>
    <td>CА 3850 РА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>26.09.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013251935</td>
    <td>9085</td>
    <td>CА 4117 РА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>26.09.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013251936</td>
    <td>9087</td>
    <td>CА 3851 РА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>26.09.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013251937</td>
    <td>9079</td>
    <td>CА 3852 РА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013251938</td>
    <td>9083</td>
    <td>CА 3481 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>26.09.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013251939</td>
    <td>9093</td>
    <td>CА 3853 РА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>26.09.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013251940</td>
    <td>9099</td>
    <td>CА 4115 РА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>26.09.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013251941</td>
    <td>9086</td>
    <td>CА 4112 РА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>26.09.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013251942</td>
    <td>9081</td>
    <td>CА 3855 РА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>26.09.2009</td>
    <td>26.09.2019</td>
    <td>WEB62831013251943</td>
    <td>9090</td>
    <td>CА 3854 РА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013251944</td>
    <td>9092</td>
    <td>CА 3482 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013251945</td>
    <td>9091</td>
    <td>CА 3485 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013251946</td>
    <td>9089</td>
    <td>CА 3484 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>26.09.2019</td>
    <td>WEB62831013251947</td>
    <td>9082</td>
    <td>CА 3469 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2009</td>
    <td>01.02.2010</td>
    <td>01.06.2018</td>
    <td>WEB62831013251948</td>
    <td>9095</td>
    <td>CА 3483 РК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>01.07.2008</td>
    <td>26.09.2019</td>
    <td>WEB62831013246983</td>
    <td>9051</td>
    <td>CА 3851 MT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>01.07.2008</td>
    <td>26.09.2019</td>
    <td>WEB62831013246984</td>
    <td>9050</td>
    <td>CА 3850 MT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>01.07.2008</td>
    <td>26.09.2019</td>
    <td>WEB62831013246985</td>
    <td>9054</td>
    <td>CА 3854 MT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>01.07.2008</td>
    <td>26.09.2019</td>
    <td>WEB62831013246986</td>
    <td>9053</td>
    <td>CА 3853 MT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>01.07.2008</td>
    <td>26.09.2019</td>
    <td>WEB62831013246987</td>
    <td>9052</td>
    <td>CА 3852 MT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>01.07.2008</td>
    <td>26.09.2019</td>
    <td>WEB62831013246988</td>
    <td>9049</td>
    <td>CА 3849 MT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248299</td>
    <td>1867</td>
    <td>CА 4673 НА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248298</td>
    <td>1865</td>
    <td>CА 2933 НА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248297</td>
    <td>1871</td>
    <td>CА 4674 НА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248296</td>
    <td>1869</td>
    <td>CА 2934 НА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248295</td>
    <td>1863</td>
    <td>CА 2936 НА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248294</td>
    <td>1861</td>
    <td>CА 2401 НА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248293</td>
    <td>1859</td>
    <td>CА 2404 НА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248292</td>
    <td>1857</td>
    <td>CА 2403 НА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248291</td>
    <td>1853</td>
    <td>CА 2398 НА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248035</td>
    <td>1847</td>
    <td>CА 4762 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248034</td>
    <td>1843</td>
    <td>CА 4759 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248033</td>
    <td>1851</td>
    <td>CА 4764 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248032</td>
    <td>1849</td>
    <td>CА 4754 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248031</td>
    <td>1837</td>
    <td>CА 3853 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248030</td>
    <td>1845</td>
    <td>CА 4760 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248029</td>
    <td>1841</td>
    <td>CА 2237 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248028</td>
    <td>1835</td>
    <td>CА 3855 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248027</td>
    <td>1823</td>
    <td>CА 1151 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248026</td>
    <td>1821</td>
    <td>CА 1150 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248025</td>
    <td>1839</td>
    <td>CА 3848 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248024</td>
    <td>1819</td>
    <td>CА 1154 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248023</td>
    <td>1833</td>
    <td>CА 2239 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248022</td>
    <td>1831</td>
    <td>CА 3850 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248021</td>
    <td>1817</td>
    <td>CА 1161 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248020</td>
    <td>1855</td>
    <td>CА 2238 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248019</td>
    <td>1815</td>
    <td>CА 1159 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248018</td>
    <td>1827</td>
    <td>CА 1148 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248017</td>
    <td>1829</td>
    <td>CА 2241 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248016</td>
    <td>1825</td>
    <td>CА 1153 МX</td>
  </tr>
  <tr>
    <td>Tedom C12G</td>
    <td>2008</td>
    <td>21.04.2008</td>
    <td>16.08.2012</td>
    <td>TM9K23GA007TE6003</td>
    <td>3901</td>
    <td>СА 1558 МР</td>
  </tr>
  <tr>
    <td>Tedom C12G</td>
    <td>2008</td>
    <td>21.04.2008</td>
    <td>24.02.2019</td>
    <td>&nbsp;&nbsp;TM9K23GA008TE6001 </td>
    <td>3902</td>
    <td>СА 1565 МР</td>
  </tr>
  <tr>
    <td>Tedom C12G</td>
    <td>2008</td>
    <td>21.04.2008</td>
    <td>24.02.2019</td>
    <td>TM9K23GA008TE6002</td>
    <td>3903</td>
    <td>СА 1560 МР</td>
  </tr>
  <tr>
    <td>Tedom C12G</td>
    <td>2008</td>
    <td>21.04.2008</td>
    <td>24.02.2019</td>
    <td>TM9K23GA008TE6003</td>
    <td>3904</td>
    <td>СА 7284 МP</td>
  </tr>
  <tr>
    <td>Tedom C12G</td>
    <td>2008</td>
    <td>21.04.2008</td>
    <td>24.02.2019</td>
    <td>TM9K23GA008TE6004</td>
    <td>3905</td>
    <td>СА 7282 МP</td>
  </tr>
  <tr>
    <td>Tedom C12G</td>
    <td>2008</td>
    <td>21.04.2008</td>
    <td>24.02.2019</td>
    <td>TM9K23GA008TE6005</td>
    <td>3906</td>
    <td>СА 7285 МP</td>
  </tr>
  <tr>
    <td>Tedom C12G</td>
    <td>2008</td>
    <td>21.04.2008</td>
    <td>24.02.2019</td>
    <td>TM9K23GA008TE6006</td>
    <td>3907</td>
    <td>СА 7280 МP</td>
  </tr>
  <tr>
    <td>Tedom C12G</td>
    <td>2008</td>
    <td>21.04.2008</td>
    <td>24.02.2019</td>
    <td>TM9K23GA008TE6007</td>
    <td>3908</td>
    <td>СА 7283 МP</td>
  </tr>
  <tr>
    <td>Tedom C12G</td>
    <td>2008</td>
    <td>21.04.2008</td>
    <td>09.06.2017</td>
    <td>TM9K23GA008TE6008</td>
    <td>3909</td>
    <td>СА 7279 МP</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>01.04.2008</td>
    <td>01.12.2016</td>
    <td>NP9GD02728B011054</td>
    <td>6101</td>
    <td>CA 9904 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>01.04.2008</td>
    <td>01.12.2016</td>
    <td>NP9GD02728B011051</td>
    <td>6102</td>
    <td>CA 9901 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>01.04.2008</td>
    <td>01.09.2018</td>
    <td>NP9GD02728B011052</td>
    <td>6103</td>
    <td>CA 9902 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>01.04.2008</td>
    <td>01.09.2018</td>
    <td>NP9GD02728B011053</td>
    <td>6104</td>
    <td>CA 9903 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>01.04.2008</td>
    <td>01.12.2016</td>
    <td>NP9GD02728B011055</td>
    <td>6105</td>
    <td>CA 9905 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.09.2018</td>
    <td>NP9GD02728B011063</td>
    <td>6113</td>
    <td>CA 9913 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.12.2016</td>
    <td>NP9GD02728B011064</td>
    <td>6114</td>
    <td>CA 9914 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.02.2018</td>
    <td>NP9GD02728B011066</td>
    <td>6116</td>
    <td>CA 9916 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.12.2016</td>
    <td>NP9GD02728B011067</td>
    <td>6117</td>
    <td>CA 9917 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.12.2016</td>
    <td>NP9GD02728B011068</td>
    <td>6118</td>
    <td>CA 9918 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.09.2018</td>
    <td>NP9GD02728B011069</td>
    <td>6119</td>
    <td>CA 9919 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.12.2016</td>
    <td>NP9GD02728B011070</td>
    <td>6120</td>
    <td>CA 9920 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.12.2016</td>
    <td>NP9GD02728B011071</td>
    <td>6121</td>
    <td>CA 9921 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.09.2018</td>
    <td>NP9GD02728B011074</td>
    <td>6122</td>
    <td>CA 9922 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.09.2018</td>
    <td>NP9GD02728B011073</td>
    <td>6123</td>
    <td>CA 9923 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.12.2016</td>
    <td>NP9GD02728B011072</td>
    <td>6124</td>
    <td>CA 9924 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.09.2018</td>
    <td>NP9GD02728B011075</td>
    <td>6125</td>
    <td>CA 9925 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.09.2018</td>
    <td>NP9GD02728B011076</td>
    <td>6126</td>
    <td>CA 9926 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.09.2018</td>
    <td>NP9GD02728B011057</td>
    <td>6127</td>
    <td>CA 9907 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.09.2018</td>
    <td>NP9GD02728B011059</td>
    <td>6128</td>
    <td>CA 9909 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.09.2018</td>
    <td>NP9GD02728B011080</td>
    <td>6129</td>
    <td>CA 9930 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.12.2016</td>
    <td>NP9GD02728B011056</td>
    <td>6130</td>
    <td>CA 9906 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.09.2018</td>
    <td>NP9GD02728B011061</td>
    <td>6131</td>
    <td>CA 9911 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.09.2018</td>
    <td>NP9GD02728B011060</td>
    <td>6132</td>
    <td>CA 9910 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.12.2016</td>
    <td>NP9GD02728B011058</td>
    <td>6133</td>
    <td>CA 9908 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.12.2016</td>
    <td>NP9GD02728B011062</td>
    <td>6134</td>
    <td>CA 9912 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.09.2018</td>
    <td>NP9GD02728B011065</td>
    <td>6135</td>
    <td>CA 9915 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.09.2018</td>
    <td>NP9GD02728B011077</td>
    <td>6136</td>
    <td>CA 9927 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.12.2016</td>
    <td>NP9GD02728B011078</td>
    <td>6137</td>
    <td>CA 9928 MA</td>
  </tr>
  <tr>
    <td>Güleryüz Cobra GD 272</td>
    <td>2008</td>
    <td>23.05.2008</td>
    <td>01.09.2018</td>
    <td>NP9GD02728B011079</td>
    <td>6138</td>
    <td>CA 9929 MA</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>22.04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200113</td>
    <td>8004</td>
    <td>CA 9080 MP</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>22.04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200114</td>
    <td>8002</td>
    <td>CA 9076 MP</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>22.04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200115</td>
    <td>8006</td>
    <td>CA 9084 MP</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>22.04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200116</td>
    <td>8005</td>
    <td>CA 9082 MP</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>22.04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200117</td>
    <td>8003</td>
    <td>CA 9078 MP</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>22.04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200118</td>
    <td>8007</td>
    <td>CA 9098 MP</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>22.04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200119</td>
    <td>8001</td>
    <td>CA 9074 MP</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200140</td>
    <td>7037-&gt;8008</td>
    <td>CA 0842 MX</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200141</td>
    <td>7039-&gt;8009</td>
    <td>CA 0848 MX</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200142</td>
    <td>7041-&gt;8010</td>
    <td>CA 0850 MX</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200143</td>
    <td>7051-&gt;8015</td>
    <td>CA 0143 HA</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200144</td>
    <td>7061-&gt;8020</td>
    <td>CA 0142 HA</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200145</td>
    <td>7057-&gt;8018</td>
    <td>CA 0150 HA</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200146</td>
    <td>7049-&gt;8014</td>
    <td>CA 0138 HA</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200147</td>
    <td>7047-&gt;8013</td>
    <td>CA 0017 HA</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200148</td>
    <td>7043-&gt;8011</td>
    <td>CA 0155 HA</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200149</td>
    <td>7059-&gt;8019</td>
    <td>CA 0151 HA</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200150</td>
    <td>7063-&gt;8021</td>
    <td>CA 0140 HA</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200151</td>
    <td>7055-&gt;8017</td>
    <td>CA 0146 HA</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200152</td>
    <td>7065-&gt;8022</td>
    <td>CA 0147 HA</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200153</td>
    <td>7053-&gt;8016</td>
    <td>CA 0145 HA</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200154</td>
    <td>7045-&gt;8012</td>
    <td>CA 0154 HA</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200155</td>
    <td>7071-&gt;8025</td>
    <td>CA 4020 HA</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200156</td>
    <td>7067-&gt;8023</td>
    <td>CA 4019 HA</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200157</td>
    <td>7073-&gt;8026</td>
    <td>CA 4021 HA</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2008</td>
    <td>04.2008</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB200158</td>
    <td>7069-&gt;8024</td>
    <td>CA 4018 HA</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248015</td>
    <td>1811</td>
    <td>CА 1157 МX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248014</td>
    <td>1807</td>
    <td>CА 6198 МТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248013</td>
    <td>1803</td>
    <td>CА 4347 МТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248012</td>
    <td>1801</td>
    <td>CА 4345 МТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248011</td>
    <td>1809</td>
    <td>CА 4348 МТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2008</td>
    <td>07.2008</td>
    <td></td>
    <td>WEB62831013248010</td>
    <td>1805</td>
    <td>CА 4346 МТ</td>
  </tr>
  <tr>
    <td>VDL-Berkhof Heerenveen Ambassador 200</td>
    <td>2008</td>
    <td></td>
    <td></td>
    <td>XMGDE02FS0H017441</td>
    <td>4196-&gt;1175-&gt;</td>
    <td><a href="https://flic.kr/p/2k1NxLU">CB 5368 HA</a></td>
  </tr>
  <tr>
    <td>VDL-Berkhof Heerenveen Ambassador 200</td>
    <td>2008</td>
    <td></td>
    <td></td>
    <td>XMGDE02FS0H017442</td>
    <td>4197-&gt;1172-&gt;</td>
    <td><a href="https://flic.kr/p/2k1JNiV">CB 1399 HK</a></td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2007</td>
    <td>05.2007</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB100002</td>
    <td>7031</td>
    <td>СА 3211 КХ</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2007</td>
    <td>05.2007</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB100003</td>
    <td>7021</td>
    <td>СА 3142 КХ</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2007</td>
    <td>05.2007</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB100004</td>
    <td>7025</td>
    <td>СА 3145 КХ</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2007</td>
    <td>05.2007</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB100005</td>
    <td>7023</td>
    <td>ВА 118675</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2007</td>
    <td>05.2007</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB100006</td>
    <td>7027</td>
    <td>СА 3147 КХ</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2007</td>
    <td>05.2007</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB100007</td>
    <td>7029</td>
    <td>ВА 118???</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2007</td>
    <td>05.2007</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB100008</td>
    <td>7019</td>
    <td>СА 5589 MA</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2007</td>
    <td>05.2007</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB100009</td>
    <td>7035</td>
    <td>BA 118452</td>
  </tr>
  <tr>
    <td>BMC Belde 250-SLF</td>
    <td>2007</td>
    <td>05.2007</td>
    <td>26.09.2016</td>
    <td>NMC250LKBLB100010</td>
    <td>7033</td>
    <td>СА 3139 KX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O530 Citaro</td>
    <td>2007</td>
    <td>10.2007</td>
    <td>26.09.2019</td>
    <td>WEB62808510601104</td>
    <td>9011</td>
    <td>CА 9770 KT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O530 Citaro</td>
    <td>2007</td>
    <td>10.2007</td>
    <td>26.09.2019</td>
    <td>WEB62808510601105</td>
    <td>9015</td>
    <td>CА 9785 KT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O530 Citaro</td>
    <td>2007</td>
    <td>10.2007</td>
    <td>26.09.2019</td>
    <td>WEB62808510601106</td>
    <td>9014</td>
    <td>CА 9783 KT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O530 Citaro</td>
    <td>2007</td>
    <td>10.2007</td>
    <td>26.09.2019</td>
    <td>WEB62808510601107</td>
    <td>9012</td>
    <td>CА 9776 KT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O530 Citaro</td>
    <td>2007</td>
    <td>10.2007</td>
    <td>08.11.2016</td>
    <td>WEB62808510601108</td>
    <td>9010</td>
    <td>CА 9768 KT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O530 Citaro</td>
    <td>2007</td>
    <td>10.2007</td>
    <td>26.09.2019</td>
    <td>WEB62808510601109</td>
    <td>9013</td>
    <td>CА 9781 KT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.10.2007</td>
    <td>26.09.2019</td>
    <td>NMB62831013244988</td>
    <td>9002</td>
    <td>СА 5382 СН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.10.2007</td>
    <td>26.09.2019</td>
    <td>NMB62831013244989</td>
    <td>9003</td>
    <td>CА 9941 КТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.10.2007</td>
    <td>26.09.2019</td>
    <td>NMB62831013244990</td>
    <td>9008</td>
    <td>CА 9936 КТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.10.2007</td>
    <td>26.09.2019</td>
    <td>NMB62831013244991</td>
    <td>9004</td>
    <td>CА 9942 КТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.10.2007</td>
    <td>26.09.2019</td>
    <td>NMB62831013245471</td>
    <td>9034</td>
    <td>CА 9961 КТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.10.2007</td>
    <td>26.09.2019</td>
    <td>NMB62831013245472</td>
    <td>9019</td>
    <td>CА 9959 КТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.10.2007</td>
    <td>26.09.2019</td>
    <td>NMB62831013245473</td>
    <td>9005</td>
    <td>CА 9964 КТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.10.2007</td>
    <td>26.09.2019</td>
    <td>NMB62831013245474</td>
    <td>9001</td>
    <td>CА 9937 КТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.10.2007</td>
    <td>26.09.2019</td>
    <td>NMB62831013245475</td>
    <td>9006</td>
    <td>CА 9968 КТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.10.2007</td>
    <td>26.09.2019</td>
    <td>NMB62831013245478</td>
    <td>9007</td>
    <td>CА 9934 КТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.10.2007</td>
    <td>26.09.2019</td>
    <td>NMB62831013245479</td>
    <td>9018</td>
    <td>CА 9954 КТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.10.2007</td>
    <td>26.09.2019</td>
    <td>NMB62831013245480</td>
    <td>9017</td>
    <td>CА 9951 КТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.10.2007</td>
    <td>26.09.2019</td>
    <td>NMB62831013245481</td>
    <td>9009</td>
    <td>CА 9939 КТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.11.2007</td>
    <td>26.09.2019</td>
    <td>WEB62831013245609</td>
    <td>9041</td>
    <td>CА 1721 КХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.11.2007</td>
    <td>26.09.2019</td>
    <td>WEB62831013245610</td>
    <td>9043</td>
    <td>CА 1755 КХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.11.2007</td>
    <td>26.09.2019</td>
    <td>WEB62831013245611</td>
    <td>9045</td>
    <td>CА 1758 КХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.11.2007</td>
    <td>26.09.2019</td>
    <td>WEB62831013245612</td>
    <td>9044</td>
    <td>CА 1756 КХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.11.2007</td>
    <td>26.09.2019</td>
    <td>WEB62831013245614</td>
    <td>9039</td>
    <td>CА 1715 КХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.11.2007</td>
    <td>26.09.2019</td>
    <td>WEB62831013245615</td>
    <td>9042</td>
    <td>CА 1722 КХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.11.2007</td>
    <td>26.09.2019</td>
    <td>WEB62831013245616</td>
    <td>9038</td>
    <td>CА 1712 КХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.11.2007</td>
    <td>26.09.2019</td>
    <td>WEB62831013245617</td>
    <td>9037</td>
    <td>CА 1710 КХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz Conecto LF</td>
    <td>2007</td>
    <td>01.11.2007</td>
    <td>26.09.2019</td>
    <td>NMB62831013241213</td>
    <td>9035</td>
    <td>CА 5584 МА</td>
  </tr>
  <tr>
    <td>LAZ A183 CityLAZ</td>
    <td>2007</td>
    <td>2007</td>
    <td>22.04.2015</td>
    <td>Y8AA183N160000171</td>
    <td>5032</td>
    <td>СА 0577 КС</td>
  </tr>
  <tr>
    <td>Tedom C12G</td>
    <td>2006</td>
    <td>01.08.2007</td>
    <td>31.08.2007</td>
    <td>ZA9C23FGV6TB09006</td>
    <td>7579</td>
    <td>2J77579</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O530 Citaro</td>
    <td>2006</td>
    <td>02.2021</td>
    <td></td>
    <td>WEB62808513111194</td>
    <td>5006</td>
    <td>СВ 9987 СВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O530 Citaro</td>
    <td>2006</td>
    <td>02.2021</td>
    <td></td>
    <td>WEB62808513111193</td>
    <td>5013</td>
    <td>СВ 3356 СК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O530 Citaro</td>
    <td>2005</td>
    <td>06.2020</td>
    <td></td>
    <td>WEB62801013107209</td>
    <td>5008</td>
    <td>СВ 4495 РР</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>29.07.2005</td>
    <td></td>
    <td>NMC220LKBLB100001</td>
    <td>3810-&gt;2747</td>
    <td>C 2161 XX</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100002</td>
    <td>1963-&gt;3714-&gt;2740</td>
    <td>C 9028 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100003</td>
    <td>3702-&gt;2734</td>
    <td>C 9031 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100004</td>
    <td>1971-&gt;3814-&gt;2743</td>
    <td>C 9025 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100005</td>
    <td>3713-&gt;2739</td>
    <td>C 9021 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100006</td>
    <td>3706</td>
    <td>C 9023 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100007</td>
    <td>1965-&gt;3813-&gt;2742</td>
    <td>C 9017 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100008</td>
    <td>3705-&gt;2735</td>
    <td>C 9015 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100009</td>
    <td>3701</td>
    <td>C 9014 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td>10.2019</td>
    <td>NMC220LKBLB100010</td>
    <td>3710</td>
    <td>C 8995 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100011</td>
    <td>3704</td>
    <td>C 8997 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100012</td>
    <td>3711-&gt;2738</td>
    <td>C 8994 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td>01.06.2019</td>
    <td>NMC220LKBLB100013</td>
    <td>1967-&gt;3718</td>
    <td>C 8975 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100014</td>
    <td>3708-&gt;2736</td>
    <td>C 8980 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td>29.05.2020</td>
    <td>NMC220LKBLB100015</td>
    <td>3700</td>
    <td>C 8973 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td>01.06.2019</td>
    <td>NMC220LKBLB100016</td>
    <td>1961-&gt;3719</td>
    <td>C 9027 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100017</td>
    <td>3709-&gt;2737</td>
    <td>C 8971 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td>01.06.2019</td>
    <td>NMC220LKBLB100018</td>
    <td>1969-&gt;3720</td>
    <td>C 8970 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100019</td>
    <td>3712</td>
    <td>C 8968 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td>29.05.2020</td>
    <td>NMC220LKBLB100020</td>
    <td>3707</td>
    <td>C 8966 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>08.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100021</td>
    <td>3703</td>
    <td>C 8961 XC</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td>29.05.2020</td>
    <td>NMC220LKBLB100022</td>
    <td>1977-&gt;3716</td>
    <td>C 3244 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td>01.06.2019</td>
    <td>NMC220LKBLB100023</td>
    <td>1975-&gt;3721</td>
    <td>C 3265 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td>07.2021</td>
    <td>NMC220LKBLB100024</td>
    <td>1985-&gt;3717</td>
    <td>C 3263 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td>01.06.2019</td>
    <td>NMC220LKBLB100025</td>
    <td>1979-&gt;3722</td>
    <td>C 3240 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td>01.06.2019</td>
    <td>NMC220LKBLB100026</td>
    <td>1981-&gt;3723</td>
    <td>C 3267 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100027</td>
    <td>2730</td>
    <td>C 3260 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100028</td>
    <td>2720</td>
    <td>C 3356 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td>09.09.2019</td>
    <td>NMC220LKBLB100029</td>
    <td>1973-&gt;3724-&gt;2749</td>
    <td>C 3257 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100030</td>
    <td>2731</td>
    <td>C 3252 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100031</td>
    <td>1983-&gt;3725-&gt;2750</td>
    <td>C 3246 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100032</td>
    <td>2732</td>
    <td>C 3269 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100033</td>
    <td>2721</td>
    <td>C 3351 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100034</td>
    <td>2722</td>
    <td>C 3364 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100035</td>
    <td>2723</td>
    <td>C 3379 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td>20.10.2021</td>
    <td>NMC220LKBLB100036</td>
    <td>2724</td>
    <td>C 3382 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100037</td>
    <td>2725</td>
    <td>C 3386 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100038</td>
    <td>2726</td>
    <td>C 3390 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100039</td>
    <td>2727</td>
    <td>C 3392 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100040</td>
    <td>2728</td>
    <td>C 3396 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>29.07.2005</td>
    <td>01.06.2019</td>
    <td>NMC220LKBLB100041</td>
    <td>1563-&gt;3726</td>
    <td>C 2166 XX</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>24.06.2005</td>
    <td></td>
    <td>NMC220LKBLB100042</td>
    <td>2729</td>
    <td>C 3401 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>09.07.2005</td>
    <td></td>
    <td>NMC220LKBLB100043</td>
    <td>3801-&gt;2744</td>
    <td>C 6652 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>09.07.2005</td>
    <td></td>
    <td>NMC220LKBLB100044</td>
    <td>3802-&gt;2745</td>
    <td>C 6673 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>09.07.2005</td>
    <td></td>
    <td>NMC220LKBLB100045</td>
    <td>3806</td>
    <td>C 6679 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>09.07.2005</td>
    <td></td>
    <td>NMC220LKBLB100046</td>
    <td>3805</td>
    <td>С 6683 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>09.07.2005</td>
    <td></td>
    <td>NMC220LKBLB100047</td>
    <td>3807-&gt;2746</td>
    <td>C 6703 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>09.07.2005</td>
    <td></td>
    <td>NMC220LKBLB100048</td>
    <td>3809-&gt;2752</td>
    <td>C 6705 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>09.07.2005</td>
    <td>07.2021</td>
    <td>NMC220LKBLB100049</td>
    <td>3800</td>
    <td>C 6711 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>09.07.2005</td>
    <td>07.2021</td>
    <td>NMC220LKBLB100050</td>
    <td>3804</td>
    <td>C 6741 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>09.07.2005</td>
    <td></td>
    <td>NMC220LKBLB100051</td>
    <td>3808-&gt;2741</td>
    <td>C 6744 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>09.07.2005</td>
    <td>07.2021</td>
    <td>NMC220LKBLB100052</td>
    <td>3803</td>
    <td>C 6648 XT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>29.07.2005</td>
    <td>01.06.2019</td>
    <td>NMC220LKBLB100053</td>
    <td>1553-&gt;3727</td>
    <td>C 2153 XX</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>29.07.2005</td>
    <td></td>
    <td>NMC220LKBLB100054</td>
    <td>3812</td>
    <td>C 2155 XX</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>29.07.2005</td>
    <td></td>
    <td>NMC220LKBLB100055</td>
    <td>1555-&gt;3728-&gt;2751</td>
    <td>C 2163 XX</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>29.07.2005</td>
    <td></td>
    <td>NMC220LKBLB100056</td>
    <td>1559-&gt;3715</td>
    <td>C 2159 XX</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>29.07.2005</td>
    <td>04.2015</td>
    <td>NMC220LKBLB100057</td>
    <td>1557-&gt;3731</td>
    <td>C 2152 XX</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>29.07.2005</td>
    <td>16.02.2022</td>
    <td>NMC220LKBLB100058</td>
    <td>3811-&gt;2748</td>
    <td>C 2164 XX</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>29.07.2005</td>
    <td></td>
    <td>NMC220LKBLB100059</td>
    <td>2733</td>
    <td>C 2149 XX</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>29.07.2005</td>
    <td>01.06.2019</td>
    <td>NMC220LKBLB100060</td>
    <td>1561-&gt;3729</td>
    <td>C 2154 XX</td>
  </tr>
  <tr>
    <td>BMC Belde 220-SLF</td>
    <td>2005</td>
    <td>29.07.2005</td>
    <td>01.06.2019</td>
    <td>NMC220LKBLB100061</td>
    <td>1551-&gt;3730</td>
    <td>C 2147 XX</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>01.07.2003</td>
    <td>08.2014</td>
    <td>NMC220CCBLB900020</td>
    <td>5023</td>
    <td>CO 9154 CB</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>01.07.2003</td>
    <td>08.2013</td>
    <td>NMC220CCBLB900019</td>
    <td>5024</td>
    <td>CO 9072 CB</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>01.07.2003</td>
    <td>04.2015</td>
    <td>NMC220CCBLB900018</td>
    <td>5025</td>
    <td>CO 9153 CB</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>01.07.2003</td>
    <td>04.2015</td>
    <td>NMC220CCBLB900017</td>
    <td>5026</td>
    <td>CO 9123 CB</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>01.07.2003</td>
    <td>08.2014</td>
    <td>NMC220CCBLB900022</td>
    <td>5027</td>
    <td>CO 9124 CB</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>01.07.2003</td>
    <td>08.2013</td>
    <td>NMC220CCBLB900021</td>
    <td>5028</td>
    <td>CO 9071 CB</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>20.05.2003</td>
    <td>01.09.2018</td>
    <td>NMC220CCBLB900016</td>
    <td>6006</td>
    <td>C 2520 MT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>20.05.2003</td>
    <td>01.09.2018</td>
    <td>NMC220CCBLB900001</td>
    <td>6007</td>
    <td>C 2444 MT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>20.05.2003</td>
    <td>01.09.2018</td>
    <td>NMC220CCBLB900008</td>
    <td>6008</td>
    <td>C 2524 MT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>20.05.2003</td>
    <td>01.09.2018</td>
    <td>NMC220CCBLB900004</td>
    <td>6009</td>
    <td>C 2518 MT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>20.05.2003</td>
    <td>01.09.2018</td>
    <td>NMC220CCBLB900012</td>
    <td>6010</td>
    <td>C 2457 MT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>20.05.2003</td>
    <td>01.09.2018</td>
    <td>NMC220CCBLB900007</td>
    <td>6011</td>
    <td>C 2488 MT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>20.05.2003</td>
    <td>01.09.2018</td>
    <td>NMC220CCBLB900006</td>
    <td>6012</td>
    <td>C 2491 MT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>20.05.2003</td>
    <td>01.09.2018</td>
    <td>NMC220CCBLB900010</td>
    <td>6014</td>
    <td>C 2481 MT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>20.05.2003</td>
    <td>01.09.2018</td>
    <td>NMC220CCBLB900013</td>
    <td>6015</td>
    <td>C 2490 MT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>20.05.2003</td>
    <td>01.09.2018</td>
    <td>NMC220CCBLB900011</td>
    <td>6016</td>
    <td>C 2471 MT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>20.05.2003</td>
    <td>01.09.2018</td>
    <td>NMC220CCBLB900002</td>
    <td>6017</td>
    <td>C 2498 MT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>20.05.2003</td>
    <td>01.09.2018</td>
    <td>NMC220CCBLB900009</td>
    <td>6018</td>
    <td>C 2508 MT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>20.05.2003</td>
    <td>01.09.2018</td>
    <td>NMC220CCBLB900005</td>
    <td>6019</td>
    <td>C 2485 MT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>20.05.2003</td>
    <td>01.09.2018</td>
    <td>NMC220CCBLB900003</td>
    <td>6020</td>
    <td>C 2472 MT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>20.05.2003</td>
    <td>01.09.2018</td>
    <td>NMC220CCBLB900015</td>
    <td>6021</td>
    <td>C 2501 MT</td>
  </tr>
  <tr>
    <td>BMC Belde 220-CB</td>
    <td>2003</td>
    <td>20.05.2003</td>
    <td>01.09.2018</td>
    <td>NMC220CCBLB900014</td>
    <td>6022</td>
    <td>CA 6081 KA</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>12.2003</td>
    <td></td>
    <td>NMB67133213236606</td>
    <td>1101-&gt;3307</td>
    <td>C 3526 HC</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>12.2003</td>
    <td></td>
    <td>NMB67133213236607</td>
    <td>1111-&gt;3305</td>
    <td>C 3566 HC</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>12.2003</td>
    <td></td>
    <td>NMB67133213236608</td>
    <td>1106-&gt;3311</td>
    <td>C 5954 HC</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>12.2003</td>
    <td></td>
    <td>NMB67133213236609</td>
    <td>1105-&gt;3300</td>
    <td>CB 1190 MT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>12.2003</td>
    <td></td>
    <td>NMB67133213236610</td>
    <td>1109-&gt;3308</td>
    <td>C 8328 HC</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>12.2003</td>
    <td></td>
    <td>NMB67133213236611</td>
    <td>1107-&gt;3304-&gt;1107-&gt;3304</td>
    <td>C 8364 HC</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>12.2003</td>
    <td></td>
    <td>NMB67133213236612</td>
    <td>1103-&gt;3310</td>
    <td>C 5994 HC</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>12.2003</td>
    <td></td>
    <td>NMB67133213236613</td>
    <td>1104-&gt;3315</td>
    <td> C 5975 HC </td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>12.2003</td>
    <td></td>
    <td>NMB67133213236614</td>
    <td>1108-&gt;3303</td>
    <td>C 8378 HC</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>12.2003</td>
    <td></td>
    <td>NMB67133213236615</td>
    <td>1112-&gt;3314</td>
    <td>C 8385 HC</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>12.2003</td>
    <td></td>
    <td>NMB67133213236616</td>
    <td>1110</td>
    <td>C 8279 HC</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>12.2003</td>
    <td></td>
    <td>NMB67133213236617</td>
    <td>1114</td>
    <td>C 8373 HC</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>12.2003</td>
    <td></td>
    <td>NMB67133213236618</td>
    <td>1102-&gt;3316</td>
    <td>C 8381 HC</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>12.2003</td>
    <td></td>
    <td>NMB67133213236619</td>
    <td>1113-&gt;3317</td>
    <td>C 8217 HC</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>12.2003</td>
    <td></td>
    <td>NMB67133213236620</td>
    <td>1115</td>
    <td>C 8387 HC</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236632</td>
    <td>2162</td>
    <td>C 5212 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236633</td>
    <td>2163</td>
    <td>C 5208 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236634</td>
    <td>2164</td>
    <td>C 5211 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236635</td>
    <td>2165</td>
    <td>C 5206 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236636</td>
    <td>2166</td>
    <td>C 5214 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236637</td>
    <td>2167</td>
    <td>C 5207 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236638</td>
    <td>2168</td>
    <td>C 5215 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236639</td>
    <td>2169</td>
    <td>C 5210 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td>10.01.2020</td>
    <td>NMB67133213236640</td>
    <td>2170</td>
    <td>C 5213 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236641</td>
    <td>2161</td>
    <td>C 5209 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236642</td>
    <td>1130</td>
    <td>C 4751 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236643</td>
    <td>1133-&gt;3312-&gt;1133-&gt;3312</td>
    <td>C 4758 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236644</td>
    <td>1129-&gt;3318</td>
    <td>C 4764 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236645</td>
    <td>1132-&gt;3302</td>
    <td>C 4760 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236646</td>
    <td>1131</td>
    <td>C 4763 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236647</td>
    <td>1126</td>
    <td>C 4752 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236648</td>
    <td>1127</td>
    <td>С 4761 НТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236649</td>
    <td>1128</td>
    <td>C 4759 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236650</td>
    <td>1125</td>
    <td>C 4755 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236651</td>
    <td>1134-&gt;3301</td>
    <td>C 4762 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236652</td>
    <td>1135</td>
    <td>C 4756 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236653</td>
    <td>1116-&gt;3313</td>
    <td>C 4753 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236654</td>
    <td>1139-&gt;3319</td>
    <td>С 4768 НТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236655</td>
    <td>1141-&gt;3320</td>
    <td>C 4765 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236656</td>
    <td>1140-&gt;3321</td>
    <td>C 4766 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236657</td>
    <td>1138</td>
    <td>C 4767 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236658</td>
    <td>1117</td>
    <td>C 4754 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236659</td>
    <td>1118</td>
    <td>C 1077 HX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236660</td>
    <td>1137</td>
    <td>C 4769 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236661</td>
    <td>1136</td>
    <td>C 4770 HT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236662</td>
    <td>1122</td>
    <td>C 1078 HX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236663</td>
    <td>1121</td>
    <td>C 1079 HX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236664</td>
    <td>1123-&gt;3309</td>
    <td>C 1083 HX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236665</td>
    <td>1119-&gt;3306</td>
    <td>C 1082 HX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto G</td>
    <td>2003</td>
    <td>01.2004</td>
    <td></td>
    <td>NMB67133213236666</td>
    <td>1120-&gt;3322</td>
    <td>C 1081 HX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233042</td>
    <td>1909</td>
    <td>C 0275 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233043</td>
    <td>1905</td>
    <td>C 0280 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233044</td>
    <td>1911</td>
    <td>C 0276 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233045</td>
    <td>1901</td>
    <td>C 4746 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233046</td>
    <td>1915</td>
    <td>C 3498 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233047</td>
    <td>1953</td>
    <td>C 7139 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233048</td>
    <td>1917</td>
    <td>C 4742 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233049</td>
    <td>1925</td>
    <td>C 8108 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233050</td>
    <td>1919</td>
    <td>C 4743 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233051</td>
    <td>1903</td>
    <td>C 0283 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233052</td>
    <td>1907</td>
    <td>C 0272 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233053</td>
    <td>1933</td>
    <td>C 7140 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233054</td>
    <td>1913</td>
    <td>C 0282 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233055</td>
    <td>1941</td>
    <td>C 8107 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233056</td>
    <td>1935</td>
    <td>C 8106 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233057</td>
    <td>1937</td>
    <td>C 0596 BX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233058</td>
    <td>1929</td>
    <td>C 0594 BX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td>11.02.2022</td>
    <td>NMB67101013233059</td>
    <td>1931</td>
    <td>C 0592 BX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233060</td>
    <td>1927</td>
    <td>C 0588 BX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233061</td>
    <td>1939</td>
    <td>C 8683 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233062</td>
    <td>1923</td>
    <td>C 6796 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233063</td>
    <td>1955</td>
    <td>C 1416 BX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233064</td>
    <td>1921</td>
    <td>C 5633 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233065</td>
    <td>1945</td>
    <td>C 8773 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233066</td>
    <td>1951</td>
    <td>C 8775 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233067</td>
    <td>1957</td>
    <td>C 0542 BX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233068</td>
    <td>1947</td>
    <td>C 1061 BX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233069</td>
    <td>1943</td>
    <td>C 5256 BX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233070</td>
    <td>1959</td>
    <td>C 5263 BX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>01.2002</td>
    <td></td>
    <td>NMB67101013233071</td>
    <td>1949</td>
    <td>C 5264 BX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>02.2002</td>
    <td>2005</td>
    <td>NMB67101013232740</td>
    <td>6004</td>
    <td>C 5136 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>02.2002</td>
    <td></td>
    <td>NMB67101013232741</td>
    <td>6005</td>
    <td>С 5139 ВР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>02.2002</td>
    <td></td>
    <td>NMB67101013232742</td>
    <td>6001</td>
    <td>C 5133 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>02.2002</td>
    <td></td>
    <td>NMB67101013232743</td>
    <td>6002</td>
    <td>C 5134 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>02.2002</td>
    <td></td>
    <td>NMB67101013232744</td>
    <td>6003</td>
    <td>C 5135 BP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>05.2002</td>
    <td></td>
    <td>NMB67101013232745</td>
    <td>9020</td>
    <td>С 5712 МА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>05.2002</td>
    <td></td>
    <td>NMB67101013232746</td>
    <td>9024</td>
    <td>С 0049 МА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>05.2002</td>
    <td></td>
    <td>NMB67101013232747</td>
    <td>9030</td>
    <td>	С 0045 МА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>05.2002</td>
    <td></td>
    <td>NMB67101013232748</td>
    <td>9028</td>
    <td>С 5715 МА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>05.2002</td>
    <td></td>
    <td>NMB67101013232749</td>
    <td>9029</td>
    <td>С 0043 МА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>05.2002</td>
    <td></td>
    <td>NMB67101013232750</td>
    <td>9027</td>
    <td>С 5714 МА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>05.2002</td>
    <td></td>
    <td>NMB67101013232751</td>
    <td>9023</td>
    <td>С 5713 МА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>05.2002</td>
    <td></td>
    <td>NMB67101013232752</td>
    <td>9022</td>
    <td>С 5716 МА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O530 Citaro</td>
    <td>2001</td>
    <td>05.2014</td>
    <td></td>
    <td>WEB62800013099080</td>
    <td>5005</td>
    <td>СА 5097 ХН</td>
  </tr>
  <tr>
    <td>BMC Belde 220-17C</td>
    <td>2001</td>
    <td>01.12.2001</td>
    <td>07.2008</td>
    <td>NMC220CCBLB600511</td>
    <td>7001</td>
    <td>Р 0604 АК</td>
  </tr>
  <tr>
    <td>BMC Belde 220-17C</td>
    <td>2001</td>
    <td>01.12.2001</td>
    <td>2016</td>
    <td>NMC220CCBLB600466</td>
    <td>7003-&gt;5024</td>
    <td>С 9713 ВХ</td>
  </tr>
  <tr>
    <td>BMC Belde 220-17C</td>
    <td>2001</td>
    <td>01.12.2001</td>
    <td>2016</td>
    <td>NMC220CCBLB600517</td>
    <td>7005-&gt;5028</td>
    <td> С 9703 ВХ </td>
  </tr>
  <tr>
    <td>BMC Belde 220-17C</td>
    <td>2001</td>
    <td>01.12.2001</td>
    <td>07.2008</td>
    <td>NMC220CCBLB600467</td>
    <td>7007</td>
    <td>С 9709 ВХ</td>
  </tr>
  <tr>
    <td>BMC Belde 220-17C</td>
    <td>2001</td>
    <td>01.12.2001</td>
    <td>07.2008</td>
    <td>NMC220CCBLB600508</td>
    <td>7009</td>
    <td>C 9707 BX</td>
  </tr>
  <tr>
    <td>BMC Belde 220-17C</td>
    <td>2001</td>
    <td>01.12.2001</td>
    <td>07.2008</td>
    <td>NMC220CCBLB600465</td>
    <td>7011</td>
    <td>ЕВ 0405 АХ</td>
  </tr>
  <tr>
    <td>BMC Belde 220-17C</td>
    <td>2001</td>
    <td>01.12.2001</td>
    <td>07.2008</td>
    <td>NMC220CCBLB600513</td>
    <td>7013</td>
    <td>ЕВ 0809 АХ </td>
  </tr>
  <tr>
    <td>BMC Belde 220-17C</td>
    <td>2001</td>
    <td>01.12.2001</td>
    <td>07.2008</td>
    <td>NMC220CCBLB600509</td>
    <td>7015</td>
    <td>C 9715 BX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O530 Citaro</td>
    <td>2001</td>
    <td>06.2019</td>
    <td></td>
    <td>WEB62804513100321</td>
    <td>5016</td>
    <td>СВ 7809 НР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O530 Citaro</td>
    <td>2001</td>
    <td>02.2020</td>
    <td></td>
    <td>WEB62800013099266</td>
    <td>5014</td>
    <td>СВ 6418 РМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O530 Citaro</td>
    <td>2001</td>
    <td>26.03.2019</td>
    <td></td>
    <td>WEB62804513100045</td>
    <td>5011</td>
    <td>СВ 8201 НМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>12.2001</td>
    <td></td>
    <td>NMB67101013232085</td>
    <td>9021</td>
    <td>	С 9021 ВС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>12.2001</td>
    <td></td>
    <td>NMB67101013232086</td>
    <td>9026</td>
    <td>С 9026 ВС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>12.2001</td>
    <td></td>
    <td>NMB67101013232087</td>
    <td>9025</td>
    <td>С 9025 ВС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>12.2001</td>
    <td></td>
    <td>NMB67101013232113</td>
    <td>9016</td>
    <td>С 9016 ВС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>12.2001</td>
    <td></td>
    <td>NMB67101013232114</td>
    <td>9036</td>
    <td>С 9036 ВС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>12.2001</td>
    <td></td>
    <td>NMB67101013232164</td>
    <td>9040</td>
    <td>С 9040 ВС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345 Conecto</td>
    <td>2001</td>
    <td>12.2001</td>
    <td></td>
    <td>NMB67101013232199</td>
    <td>9031</td>
    <td>	С 9031 ВС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345</td>
    <td>2000</td>
    <td>10.2000</td>
    <td></td>
    <td>NMB67101013228244</td>
    <td>1767</td>
    <td>С 5623 КР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345</td>
    <td>2000</td>
    <td>2002</td>
    <td></td>
    <td>NMB67101013228242</td>
    <td>9033</td>
    <td>С 0933 ВР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345</td>
    <td>2000</td>
    <td>10.2000</td>
    <td>14.05.2019</td>
    <td>NMB67101013228241</td>
    <td>1763</td>
    <td>С 5602 КР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345</td>
    <td>2000</td>
    <td>10.2000</td>
    <td></td>
    <td>NMB67101013228240</td>
    <td>1769</td>
    <td>	С 5546 КР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345</td>
    <td>2000</td>
    <td>10.2000</td>
    <td></td>
    <td>NMB67101013228239</td>
    <td>1761</td>
    <td>С 5737 КР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345</td>
    <td>2000</td>
    <td>04.2000</td>
    <td>	27.09.2017</td>
    <td>NMB67101013228238</td>
    <td>787-&gt;3775-&gt;1771</td>
    <td>	С 1092 КВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345</td>
    <td>2000</td>
    <td>10.2000</td>
    <td>14.05.2019</td>
    <td>NMB67101013228237</td>
    <td>1765</td>
    <td>	С 5621 КР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405N</td>
    <td>2000</td>
    <td>05.2015</td>
    <td></td>
    <td>WEB61241213098113</td>
    <td>5012</td>
    <td>СВ 0843 АМ</td>
  </tr>
  <tr>
    <td>Temsa Gity Prestij</td>
    <td>2000</td>
    <td>03.2000</td>
    <td>09.2000</td>
    <td></td>
    <td>3900</td>
    <td></td>
  </tr>
  <tr>
    <td>Temsa Gity Prestij</td>
    <td>2000</td>
    <td>03.2000</td>
    <td>09.2000</td>
    <td></td>
    <td>3990</td>
    <td>Р 5075 АН</td>
  </tr>
  <tr>
    <td>MAN A21 NL263</td>
    <td>2000</td>
    <td></td>
    <td></td>
    <td>WMAA21ZZZYB019985</td>
    <td>8027</td>
    <td>СВ 5057 АМ</td>
  </tr>
  <tr>
    <td>MAN A21 NL263</td>
    <td>2000</td>
    <td></td>
    <td>26.09.2016</td>
    <td>WMAA21ZZZYB019687</td>
    <td>8028</td>
    <td>СВ 5046 АМ</td>
  </tr>
  <tr>
    <td>MAN A21 NL263</td>
    <td>1999</td>
    <td></td>
    <td></td>
    <td>WMAA210344B018611</td>
    <td>8029</td>
    <td>СВ 0625 АН</td>
  </tr>
  <tr>
    <td>MAN A21 NL263</td>
    <td>1999</td>
    <td></td>
    <td></td>
    <td>WMAA210346B018613</td>
    <td>8030</td>
    <td><a href="https://flic.kr/p/2mdzFdP">Р 4219 КМ</a></td>
  </tr>
  <tr>
    <td>MAN A21 NL263</td>
    <td>1999</td>
    <td></td>
    <td>26.09.2016</td>
    <td>WMAA210359B018626</td>
    <td>8031</td>
    <td>СВ 0317 АР</td>
  </tr>
  <tr>
    <td>MAN A21 NL263</td>
    <td>1999</td>
    <td></td>
    <td></td>
    <td>WMAA210350B018617</td>
    <td>8032</td>
    <td>СВ 0307 АР</td>
  </tr>
  <tr>
    <td>MAN A21 NL263</td>
    <td>1999</td>
    <td></td>
    <td></td>
    <td>WMAA21ZZZYB020219</td>
    <td>8033</td>
    <td>СВ 7507 АТ</td>
  </tr>
  <tr>
    <td>MAN A21 NL263</td>
    <td>1999</td>
    <td></td>
    <td></td>
    <td>WMAA210301B018586</td>
    <td>8034</td>
    <td>СВ 4077 АТ</td>
  </tr>
  <tr>
    <td>MAN A10 NL222</td>
    <td>1999</td>
    <td></td>
    <td>2017</td>
    <td>WMAA21ZZZYB020216</td>
    <td>8035</td>
    <td>СА 7511 АТ</td>
  </tr>
  <tr>
    <td>MAN A21 NL263</td>
    <td>1999</td>
    <td></td>
    <td></td>
    <td>WMAA103173B015707</td>
    <td>8036</td>
    <td>CB 7509 AT</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>20.02.1999</td>
    <td>09.10.2021</td>
    <td>WMAA610030T001295</td>
    <td>2131</td>
    <td>СА 1562 АМ</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>20.02.1999</td>
    <td>28.06.2019</td>
    <td>WMAA610034T001299</td>
    <td>2132</td>
    <td>СА 1553 АМ</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>20.02.1999</td>
    <td></td>
    <td>WMAA610035T001300</td>
    <td>2133</td>
    <td>CA 7605 BM</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>20.02.1999</td>
    <td></td>
    <td>WMAA610033T001298</td>
    <td>2134</td>
    <td>СА 2042 АМ</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>20.02.1999</td>
    <td></td>
    <td>WMAA610029T001294</td>
    <td>2135</td>
    <td>СА 2027 АМ</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>20.02.1999</td>
    <td>30.11.2019 </td>
    <td>WMAA610036T001301</td>
    <td>2136</td>
    <td>СА 1570 АМ</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>20.02.1999</td>
    <td></td>
    <td>WMAA610038T001303</td>
    <td>2137</td>
    <td>CA 1560 AM</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>20.02.1999</td>
    <td></td>
    <td>WMAA610037T001302</td>
    <td>2138</td>
    <td>СА 7706 АХ</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>20.02.1999</td>
    <td></td>
    <td>WMAA610032T001297</td>
    <td>2139</td>
    <td>CA 1549 AM</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>20.02.1999</td>
    <td></td>
    <td>WMAA610031T001296</td>
    <td>2140</td>
    <td>CA 6285 BA</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>10.05.1999</td>
    <td></td>
    <td>WMAA610043T001340</td>
    <td>2141</td>
    <td>CA 2025 AM</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>10.05.1999</td>
    <td></td>
    <td>WMAA610046T001343</td>
    <td>2142</td>
    <td>CA 5450 AM</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>10.05.1999</td>
    <td></td>
    <td>WMAA610044T001341</td>
    <td>2143</td>
    <td>CA 5447 AM</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>10.05.1999</td>
    <td></td>
    <td>WMAA610045T001342</td>
    <td>2144</td>
    <td>CA 8367 AM</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>10.05.1999</td>
    <td></td>
    <td>WMAA610047T001344</td>
    <td>2145</td>
    <td>CA 8358 AM</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>10.05.1999</td>
    <td>14.02.2020</td>
    <td>WMAA610042T001339</td>
    <td>2146</td>
    <td>CA 1546 AM</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>10.05.1999</td>
    <td></td>
    <td>WMAA610049T001346</td>
    <td>2147</td>
    <td>CA 1572 AM</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>10.05.1999</td>
    <td></td>
    <td>WMAA610048T001345</td>
    <td>2148</td>
    <td>CA 2046 AM</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>10.05.1999</td>
    <td></td>
    <td>WMAA610041T001338</td>
    <td>2149</td>
    <td>СА 7074 ХР</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>10.05.1999</td>
    <td></td>
    <td>WMAA610050T001347</td>
    <td>2150</td>
    <td>CA 8378 AM</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>20.07.1999</td>
    <td>28.03.2022</td>
    <td>WMAA610057T001453</td>
    <td>2151</td>
    <td>CA 5448 AM</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>20.07.1999</td>
    <td></td>
    <td>WMAA610056T001452</td>
    <td>2152</td>
    <td>CA 1550 AM</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>20.07.1999</td>
    <td></td>
    <td>WMAA610055T001451</td>
    <td>2153</td>
    <td>СА 1566 АМ</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>20.07.1999</td>
    <td></td>
    <td>WMA0610054T001450</td>
    <td>2154</td>
    <td>СА 8371 АМ</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>10.08.1999</td>
    <td></td>
    <td>WMAA610058T001467</td>
    <td>2155</td>
    <td>СА 1569 АМ</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>10.08.1999</td>
    <td>21.06.2019</td>
    <td>WMAA610059T001468</td>
    <td>2156</td>
    <td>СА 1567 АМ</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>10.08.1999</td>
    <td></td>
    <td>WMAA610060T001469</td>
    <td>2157</td>
    <td>CA 2037 AM</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>10.08.1999</td>
    <td></td>
    <td>WMAA610061T001470</td>
    <td>2158</td>
    <td>СА 1564 АМ</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>10.08.1999</td>
    <td></td>
    <td>WMAA610062T001471</td>
    <td>2159</td>
    <td>CA 1542 AM</td>
  </tr>
  <tr>
    <td>MAN A61 SG262</td>
    <td>1999</td>
    <td>10.08.1999</td>
    <td></td>
    <td>WMAA610063T001472</td>
    <td>2160</td>
    <td>CA 8375 AM</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405N2</td>
    <td>1999</td>
    <td>02.2015</td>
    <td></td>
    <td>WEB61240213092703</td>
    <td>5004</td>
    <td>СВ 3318 АК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405N</td>
    <td>1999</td>
    <td>02.2015</td>
    <td></td>
    <td>WEB61240213092702</td>
    <td>5010</td>
    <td>СВ 5298 АК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O520 Cito</td>
    <td>1999</td>
    <td>23.05.2008</td>
    <td>2017</td>
    <td>WEB66600013090031</td>
    <td>9046</td>
    <td>CА 1320 MP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O520 Cito</td>
    <td>1999</td>
    <td>23.05.2008</td>
    <td>2017</td>
    <td>WEB66600013090032</td>
    <td>9047</td>
    <td>CА 1330 MP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O520 Cito</td>
    <td>1999</td>
    <td>23.05.2008</td>
    <td>2017</td>
    <td>WEB66600013090033</td>
    <td>9048</td>
    <td>CА 1335 MP</td>
  </tr>
  <tr>
    <td>DAF SB250 LPG / Berkhof Premier</td>
    <td>1999</td>
    <td>2009</td>
    <td>2016</td>
    <td>XMGDE02RC0H007390</td>
    <td>2255-&gt;2347-&gt;5001</td>
    <td>CA 8962 HX</td>
  </tr>
  <tr>
    <td>DAF SB250 LPG / Berkhof Premier</td>
    <td>1999</td>
    <td>2009</td>
    <td>2016</td>
    <td>XMGDE02RC0H007389</td>
    <td>2254-&gt;2346-&gt;5011</td>
    <td>	CA 8960 HX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O530 Citaro</td>
    <td>1998</td>
    <td>09.2012</td>
    <td></td>
    <td>WEB62800013091763</td>
    <td>5003</td>
    <td>СА 8085 ТВ</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td></td>
    <td>NMAA600577T000767</td>
    <td>2901-&gt;3820-&gt;3008</td>
    <td>CA 5455 AM</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td>21.12.2018</td>
    <td>NMAA600578T000768</td>
    <td>2902</td>
    <td>ЕВ 7061 ВК</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td>01.10.2018</td>
    <td>NMAA600651T000882</td>
    <td>2903</td>
    <td>CA 1552 AM</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td>03.09.2018</td>
    <td>NMAA600652T000883</td>
    <td>2904-&gt;3821</td>
    <td>CA 5464 AM</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td>21.12.2018</td>
    <td>NMAA600653T000884</td>
    <td>2905</td>
    <td>ЕВ 7180 ВК</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td></td>
    <td>NMAA600654T000885</td>
    <td>2906</td>
    <td>CA 5463 AM</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td>24.05.2018</td>
    <td>NMAA600655T000886</td>
    <td>2907</td>
    <td>CA 5453 AM</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td>21.12.2018</td>
    <td>NMAA600656T000887</td>
    <td>2908</td>
    <td>ЕВ 7060 ВК</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td>21.12.2018</td>
    <td>NMAA600657T000888</td>
    <td>2909</td>
    <td>ЕВ 7063 ВК</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td>20.01.2018</td>
    <td>NMAA600658T000889</td>
    <td>2910</td>
    <td>CA 1547 AM</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td>21.12.2018</td>
    <td>NMAA600659T000890</td>
    <td>2911</td>
    <td>ЕВ 7062 ВК</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td>21.12.2018</td>
    <td>NMAA600660T000891</td>
    <td>2912</td>
    <td>ЕВ 7179 ВК</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td>21.12.2018</td>
    <td>NMAA600661T000892</td>
    <td>2913</td>
    <td>ЕВ 7057 ВК</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td>21.12.2018</td>
    <td>NMAA600662T000893</td>
    <td>2914</td>
    <td>ЕВ 7178 ВК</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td>22.05.2018</td>
    <td>NMAA600663T000894</td>
    <td>2915</td>
    <td>CA 5452 AM</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td></td>
    <td>NMAA600664T000895</td>
    <td>2916-&gt;3822</td>
    <td>СВ 5537 РН</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td>03.09.2018</td>
    <td>NMAA600665T000896</td>
    <td>2917-&gt;3823</td>
    <td>CA 5468 AM</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td>03.09.2018</td>
    <td>NMAA600666T000897</td>
    <td>2918-&gt;3824</td>
    <td>CA 5459 AM</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td>21.12.2018</td>
    <td>NMAA600667T000898</td>
    <td>2919</td>
    <td>ЕВ 7058 ВК</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1998</td>
    <td>05.12.1998</td>
    <td>14.09.2017</td>
    <td>NMAA600668T000899</td>
    <td>2920-&gt;3825</td>
    <td>CA 2040 AM</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>30.08.2018</td>
    <td>NMB67132713226421</td>
    <td>3587-&gt;2266-&gt;3587</td>
    <td>СА 0587 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>01.07.2019</td>
    <td>NMB67132713226420</td>
    <td>3582</td>
    <td>СА 2692 AP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>12.06.2019</td>
    <td>NMB67132713226418</td>
    <td>3599-&gt;2270-&gt;3599</td>
    <td>СА 0583 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>25.02.2018</td>
    <td>NMB67132713226417</td>
    <td>3596-&gt;2268-&gt;3596</td>
    <td>СА 0602 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td></td>
    <td>NMB67132713226415</td>
    <td>3592</td>
    <td>СА 2779 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td></td>
    <td>NMB67132713226413</td>
    <td>3585</td>
    <td>СА 2796 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>12.06.2019</td>
    <td>NMB67132713226411</td>
    <td>3598-&gt;2269-&gt;3598</td>
    <td>СА 0597 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>08.06.2014</td>
    <td>NMB67132713226410</td>
    <td>3589</td>
    <td>СА 2774 AH </td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>10.01.2019</td>
    <td>NMB67132713226408</td>
    <td>3586-&gt;2259-&gt;3586</td>
    <td>СА 2693 AP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td></td>
    <td>NMB67132713226407</td>
    <td>3584-&gt;3277</td>
    <td>СА 2686 AP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>23.02.2019</td>
    <td>NMB67132713226406</td>
    <td>3581-&gt;2252-&gt;3581</td>
    <td>СА 2750 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td></td>
    <td>NMB67132713226405</td>
    <td>3588</td>
    <td>СА 2713 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>07.06.2019</td>
    <td>NMB67132713226404</td>
    <td>3580-&gt;2251-&gt;3580</td>
    <td>СА 0598 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td></td>
    <td>NMB67132713226403</td>
    <td>1625-&gt;3291</td>
    <td>СА 2743 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>01.07.2019</td>
    <td>NMB67132713226401</td>
    <td>1643-&gt;3286-&gt;2254-&gt;3286</td>
    <td>СА 2742 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td></td>
    <td>NMB67132713226400</td>
    <td>1619-&gt;3288</td>
    <td>СА 2751 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>26.03.2019</td>
    <td>NMB67132713226399</td>
    <td>1623-&gt;3284-&gt;3577-&gt;2264-&gt;3577</td>
    <td>СА 2800 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>12.06.2019</td>
    <td>NMB67132713226398</td>
    <td>1621-&gt;3294-&gt;2263-&gt;3294</td>
    <td>СА 7643 АC</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td></td>
    <td>NMB67132713226397</td>
    <td>1635-&gt;3287</td>
    <td>СА 2790 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>03.2016</td>
    <td>NMB67132713226396</td>
    <td>3295-&gt;3578-&gt;2265-&gt;3578</td>
    <td>СА 2799 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td></td>
    <td>NMB67132713226228</td>
    <td>3595</td>
    <td>СА 0595 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>23.02.2019</td>
    <td>NMB67132713226227</td>
    <td>3594-&gt;2258-&gt;3594</td>
    <td>СА 0591 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td></td>
    <td>NMB67132713226226</td>
    <td>3593</td>
    <td>СА 2746 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td></td>
    <td>NMB67132713226225</td>
    <td>1613-&gt;3292</td>
    <td>СА 2793 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>27.10.2018</td>
    <td>NMB67132713226224</td>
    <td>3583-&gt;2253-&gt;3583</td>
    <td>СА 2761 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td></td>
    <td>NMB67132713226003</td>
    <td>1637-&gt;3290</td>
    <td>СА 0589 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td></td>
    <td>NMB67132713226002</td>
    <td>1611-&gt;3285</td>
    <td>СА 0599 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>12.06.2019</td>
    <td>NMB67132713226001</td>
    <td>1645-&gt;3298-&gt;2261-&gt;3298</td>
    <td>СА 2759 АН </td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>10.11.2018</td>
    <td>NMB67132713226000</td>
    <td>1605-&gt;3297-&gt;2255-&gt;3297</td>
    <td>СА 0580 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>15.04.2019</td>
    <td>NMB67132713225840</td>
    <td>1629-&gt;3299-&gt;2262-&gt;3299</td>
    <td>СА 0590 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td></td>
    <td>NMB67132713225839</td>
    <td>3591</td>
    <td>СА 2798 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>12.06.2019</td>
    <td>NMB67132713225838</td>
    <td>1609-&gt;3293-&gt;2257-&gt;3293</td>
    <td>СА 2745 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td></td>
    <td>NMB67132713225837</td>
    <td>1649-&gt;3283</td>
    <td>СА 2745 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>12.06.2019</td>
    <td>NMB67132713225836</td>
    <td>1639-&gt;3296-&gt;2256-&gt;3296</td>
    <td>СА 2744 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>18.09.2017</td>
    <td>NMB67132713225834</td>
    <td>3590-&gt;2267-&gt;3590</td>
    <td>СА 9194 AP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td></td>
    <td>NMB67132713225833</td>
    <td>315-&gt;3281</td>
    <td>СА 2780 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td>17.12.2018</td>
    <td>NMB67132713225831</td>
    <td>1647-&gt;3289-&gt;2260-&gt;3289</td>
    <td>СА 0584 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td></td>
    <td>NMB67132713225830</td>
    <td>313-&gt;3282</td>
    <td>СА 0594 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td></td>
    <td>NMB67132713225829</td>
    <td>3597</td>
    <td>СА 2682 AP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1998</td>
    <td>10.12.1998</td>
    <td></td>
    <td>NMB67132713225828</td>
    <td>311-&gt;3280</td>
    <td>СА 2748 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O345G</td>
    <td>1997</td>
    <td>16.12.1998</td>
    <td>01.07.2019</td>
    <td>NMB67131213222243</td>
    <td>3579-&gt;3278</td>
    <td>СА 0281 ВС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405N2</td>
    <td>1997</td>
    <td>05.2014</td>
    <td></td>
    <td>WEB61240213086862</td>
    <td>1295009</td>
    <td>СА 5099 ХН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405N</td>
    <td>1997</td>
    <td>05.2014</td>
    <td>03.2020</td>
    <td>WEB61240213086863</td>
    <td>5008</td>
    <td>СА 5098 ХН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405N</td>
    <td>1997</td>
    <td>05.2014</td>
    <td></td>
    <td>WEB61240213086850</td>
    <td>5007</td>
    <td>СА 5093 ХН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405N</td>
    <td>1997</td>
    <td>05.2014</td>
    <td></td>
    <td>WEB61240213086836</td>
    <td>5006</td>
    <td>СА 5096 ХН</td>
  </tr>
  <tr>
    <td>MAN A60 SL232 MANAS</td>
    <td>1997</td>
    <td>05.01.1998</td>
    <td>21.12.2018</td>
    <td>NMAA600390T000609</td>
    <td>2882</td>
    <td>ЕВ 7181 ВК</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B96</td>
    <td>1997</td>
    <td>2006</td>
    <td>2017</td>
    <td>XL996ABFLW1042268</td>
    <td>5031</td>
    <td>CA 1942 BC</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405N</td>
    <td>1996</td>
    <td>02.2015</td>
    <td>02.2021</td>
    <td>WEB35742413083984</td>
    <td>5001</td>
    <td>СВ 3297 АК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405N</td>
    <td>1996</td>
    <td>06.2015</td>
    <td></td>
    <td>WEB61240213085497</td>
    <td>5015</td>
    <td>СВ 5795 АН</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1996</td>
    <td>03.1996</td>
    <td>08.2007</td>
    <td>960121335</td>
    <td>2627</td>
    <td>СА 5474 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1996</td>
    <td>03.1996</td>
    <td>02.07.2015</td>
    <td>960121334</td>
    <td>2630</td>
    <td>СА 2028 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1996</td>
    <td>03.1996</td>
    <td>01.2008</td>
    <td>960121333</td>
    <td>2629</td>
    <td>СА 2029 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1996</td>
    <td>03.1996</td>
    <td>05.2008</td>
    <td>960121332</td>
    <td>2628</td>
    <td>СА 5532 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1996</td>
    <td>03.1996</td>
    <td>02.2009</td>
    <td>960121331</td>
    <td>2625</td>
    <td>СА 0942 МК</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1996</td>
    <td>03.1996</td>
    <td>10.02.2007</td>
    <td>960121330</td>
    <td>2624</td>
    <td>СА 5476 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1996</td>
    <td>03.1996</td>
    <td>09.2009</td>
    <td>960121329</td>
    <td>2623</td>
    <td>СА 5492 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1996</td>
    <td>03.1996</td>
    <td>17.08.2005</td>
    <td>960121328</td>
    <td>2631</td>
    <td>С 2907 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1996</td>
    <td>03.1996</td>
    <td>01.2008</td>
    <td>960121327</td>
    <td>2626</td>
    <td>СА 2024 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1996</td>
    <td>03.1996</td>
    <td>09.05.2015</td>
    <td>960121326</td>
    <td>2622</td>
    <td>СА 5505 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1996</td>
    <td>03.1996</td>
    <td>02.07.2015</td>
    <td>960121325</td>
    <td>2621</td>
    <td>СА 5501 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1996</td>
    <td>03.1996</td>
    <td>06.05.2015</td>
    <td>960121324</td>
    <td>2620</td>
    <td>СА 5830 ХН</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1996</td>
    <td>03.1996</td>
    <td>02.2011</td>
    <td>960121323</td>
    <td>2619</td>
    <td>СА 5470 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1996</td>
    <td>03.1996</td>
    <td>10.2005</td>
    <td>960121322</td>
    <td>2618</td>
    <td>С 2905 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1996</td>
    <td>03.1996</td>
    <td>02.03.2015</td>
    <td>960121321</td>
    <td>2616</td>
    <td>СА 5498 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1995</td>
    <td>03.1996</td>
    <td>02.07.2015</td>
    <td>951221320</td>
    <td>2612</td>
    <td>СА 2031 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1995</td>
    <td>03.1996</td>
    <td>06.05.2015</td>
    <td>951221319</td>
    <td>2617</td>
    <td>СА 1537 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1995</td>
    <td>03.1996</td>
    <td>08.02.2010</td>
    <td>951221318</td>
    <td>2615</td>
    <td>СА 5475 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1995</td>
    <td>03.1996</td>
    <td>02.10.2014</td>
    <td>951221317</td>
    <td>2613</td>
    <td>СА 2034 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1995</td>
    <td>03.1996</td>
    <td>05.2013</td>
    <td>951221316</td>
    <td>2614</td>
    <td>СА 5494 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1995</td>
    <td>01.1996</td>
    <td>02.2011</td>
    <td>951221315</td>
    <td>2603</td>
    <td>СА 5491 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1995</td>
    <td>01.1996</td>
    <td>25.03.2015</td>
    <td>951221314</td>
    <td>2608</td>
    <td>СА 5466 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1995</td>
    <td>01.1996</td>
    <td>05.2013</td>
    <td>951221313</td>
    <td>2605</td>
    <td>СА 5489 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1995</td>
    <td>01.1996</td>
    <td>02.03.2015</td>
    <td>951221312</td>
    <td>2606</td>
    <td>СА 2038 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1995</td>
    <td>01.1996</td>
    <td>03.09.2014</td>
    <td>951221311</td>
    <td>2611</td>
    <td>СА 5482 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1995</td>
    <td>01.1996</td>
    <td>08.07.2010</td>
    <td>951221310</td>
    <td>2610</td>
    <td>СА 7875 МХ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1995</td>
    <td>01.1996</td>
    <td>08.07.2010</td>
    <td>951221309</td>
    <td>2609</td>
    <td>СА 5496 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1995</td>
    <td>01.1996</td>
    <td>06.06.2015</td>
    <td>951221308</td>
    <td>2607</td>
    <td>СА 2030 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1995</td>
    <td>01.1996</td>
    <td>08.07.2010</td>
    <td>951221307</td>
    <td>2602</td>
    <td>СА 5473 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1995</td>
    <td>01.1996</td>
    <td>01.2012</td>
    <td>951221306</td>
    <td>2604</td>
    <td>СА 5484 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405N</td>
    <td>1995</td>
    <td>05.2015</td>
    <td>2016</td>
    <td>WDB61242013079275</td>
    <td>5013</td>
    <td>СВ 1236 АМ</td>
  </tr>
  <tr>
    <td>IVECO Bredabus 2001.10</td>
    <td>1995</td>
    <td>05.2007</td>
    <td>23.10.2007</td>
    <td>&nbsp;&nbsp;ZCZBB200110000132</td>
    <td>8016-&gt;8593</td>
    <td>РА 8593 ВА</td>
  </tr>
  <tr>
    <td>IVECO Bredabus 2001.10</td>
    <td>1995</td>
    <td>05.2007</td>
    <td>23.10.2007</td>
    <td>ZCZBB200110000030</td>
    <td>8017-&gt;8594</td>
    <td>РА 8594 ВА</td>
  </tr>
  <tr>
    <td>IVECO Bredabus 2001.10</td>
    <td>1995</td>
    <td>05.2007</td>
    <td>23.10.2007</td>
    <td>ZCZBB200110000126</td>
    <td>8018-&gt;8575</td>
    <td>РА 8575 ВА</td>
  </tr>
  <tr>
    <td>Чавдар 130</td>
    <td>1994</td>
    <td></td>
    <td></td>
    <td>9403011015</td>
    <td>4303-&gt;2811-&gt;4576-&gt;б/н 2</td>
    <td>СВ 4149 РТ</td>
  </tr>
  <tr>
    <td>Чавдар 130</td>
    <td>1994</td>
    <td></td>
    <td></td>
    <td>9403011014</td>
    <td>7982-&gt;4574-&gt;б/н 3</td>
    <td></td>
  </tr>
  <tr>
    <td>MAN A10 NL202</td>
    <td>1994</td>
    <td>05.2002</td>
    <td>23.10.2007</td>
    <td>WMAA101580B013056</td>
    <td>002-&gt;8002-&gt;7511-&gt;8713</td>
    <td>PB 8713 BH</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>08.2007</td>
    <td>02.2015</td>
    <td></td>
    <td>5019</td>
    <td>СО 4361 МВ</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2003</td>
    <td>04.2006</td>
    <td>XL9BAACB0P0030442</td>
    <td>5020</td>
    <td>СО 3087 СВ</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>06.2006</td>
    <td>07.2011</td>
    <td></td>
    <td>5020</td>
    <td>СО 3087 СВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405N</td>
    <td>1993</td>
    <td>06.2015</td>
    <td>05.2019</td>
    <td>VJ0R1G1N0849179A</td>
    <td>5014</td>
    <td>СА 1283 МС</td>
  </tr>
  <tr>
    <td>Setra S215 SL</td>
    <td>1993</td>
    <td>2005</td>
    <td></td>
    <td>WKK12900001020552</td>
    <td>6024</td>
    <td>С 3083 НК</td>
  </tr>
  <tr>
    <td>Setra S215 SL</td>
    <td>1993</td>
    <td>09.06.2006</td>
    <td></td>
    <td>WKK12900001020556</td>
    <td>6025</td>
    <td>С 3085 НК</td>
  </tr>
  <tr>
    <td>Scania CN113ALB</td>
    <td>1993</td>
    <td>09.1993</td>
    <td>01.1994</td>
    <td>YS4NL6X2B01821787</td>
    <td>38020-&gt;48020-&gt;PE090</td>
    <td>KR 3671 H</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405G</td>
    <td>1993</td>
    <td>09.1993</td>
    <td>01.1994</td>
    <td></td>
    <td>944</td>
    <td>WTZ 944</td>
  </tr>
  <tr>
    <td>Ikarus 280.33</td>
    <td>1993</td>
    <td>09.1993</td>
    <td>01.1994</td>
    <td></td>
    <td>б/н 1</td>
    <td>146 Т 460</td>
  </tr>
  <tr>
    <td>Sanos S200GNR</td>
    <td>1993</td>
    <td>09.1993</td>
    <td>01.1994</td>
    <td></td>
    <td>б/н 2</td>
    <td>146 Т 462</td>
  </tr>
  <tr>
    <td>FIAT IVECO</td>
    <td>1993</td>
    <td>09.1993</td>
    <td>01.1994</td>
    <td></td>
    <td>2974</td>
    <td>146 Т 463</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1993</td>
    <td>1993</td>
    <td>30.04.2003</td>
    <td></td>
    <td>2929-&gt;4474</td>
    <td>С 3300 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1993</td>
    <td>1993</td>
    <td>03.2009</td>
    <td></td>
    <td>2715-&gt;1071</td>
    <td>СА 2259 АН</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1993</td>
    <td>05.1996</td>
    <td>05.2010</td>
    <td></td>
    <td>4412-&gt;1019</td>
    <td>С 1679 РМ</td>
  </tr>
  <tr>
    <td>Чавдар 141</td>
    <td>1993</td>
    <td>11.1993</td>
    <td>02.1994</td>
    <td>931011301</td>
    <td>3655-&gt;2257-&gt;3342</td>
    <td>А 3342 ВВ</td>
  </tr>
  <tr>
    <td>MAN 895 NL202</td>
    <td>1993</td>
    <td>05.2002</td>
    <td>23.10.2007</td>
    <td>WMAA100804B011646</td>
    <td>18-1-&gt;010-&gt;8010-&gt;8021</td>
    <td>C 4572 MA</td>
  </tr>
  <tr>
    <td>MAN 895 NL202</td>
    <td>1993</td>
    <td>05.2002</td>
    <td>01.2005</td>
    <td>WMAA100914B012094</td>
    <td>16</td>
    <td>C 8933 BX</td>
  </tr>
  <tr>
    <td>MAN 895 NL202</td>
    <td>1993</td>
    <td>05.2002</td>
    <td>23.10.2007</td>
    <td>WMAA100927B011649</td>
    <td>06-1-&gt;009-&gt;8009</td>
    <td>C 4571 MA</td>
  </tr>
  <tr>
    <td>MAN 895 NL202</td>
    <td>1993</td>
    <td>05.2002</td>
    <td>23.10.2007</td>
    <td>WMAA100999B011942</td>
    <td>32-8203-&gt;31-8203-&gt;001-&gt;8001</td>
    <td>C 4558 MA</td>
  </tr>
  <tr>
    <td>MAN 895 NL202</td>
    <td>1993</td>
    <td>05.2002</td>
    <td>23.10.2007</td>
    <td>WMAA101085B012359</td>
    <td>012-&gt;8012</td>
    <td>C 8922 BX</td>
  </tr>
  <tr>
    <td>MAN A10 NL202</td>
    <td>1993</td>
    <td>05.2002</td>
    <td>23.10.2007</td>
    <td>WMAA101089B012149</td>
    <td>007-&gt;8007-&gt;7504</td>
    <td>PA 7504 BA</td>
  </tr>
  <tr>
    <td>MAN A10 NL202</td>
    <td>1993</td>
    <td>05.2002</td>
    <td>23.10.2007</td>
    <td>WMAA101115B012446</td>
    <td>006-&gt;8006-&gt;8019-&gt;8378</td>
    <td>PA 8378 BA</td>
  </tr>
  <tr>
    <td>MAN 895 NL202</td>
    <td>1993</td>
    <td>05.2002</td>
    <td>04.2004</td>
    <td>WMAA101479B012449</td>
    <td>15</td>
    <td>C 8931 BX</td>
  </tr>
  <tr>
    <td>MAN A10 NL202</td>
    <td>1993</td>
    <td>05.2002</td>
    <td>23.10.2007</td>
    <td>WMAA101528B012234</td>
    <td>124-&gt;014-&gt;8014-&gt;7503</td>
    <td>PA 7503 BA</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL9CAAFG0P0030557</td>
    <td>1235005</td>
    <td>CO 8913 MA</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL9CAAFG0P0030556</td>
    <td>1225011</td>
    <td>CO 9072 MA</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL9CAAFG0P0030554</td>
    <td>1205103</td>
    <td>	C 2811 MA</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL9CAAFG0P0030553</td>
    <td>1195012</td>
    <td>CO 9195 MA</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL9CAAFG0P0030551</td>
    <td>1175104</td>
    <td>	С 2812 МА</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL9CAAFG0P0030550</td>
    <td>1165009</td>
    <td>СО 8966 МА</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL9CAAFG0P0030549</td>
    <td>1155101</td>
    <td>C 2809 MA</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL9CAAFG0P0030548</td>
    <td>1145006</td>
    <td>CO 8912 MA</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL9CAAFG0P0030547</td>
    <td>1135013</td>
    <td>CO 9196 MA</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL9CAAFG0P0030544</td>
    <td>1105016</td>
    <td>CO 3401 CB</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL9CAAFG0P0030542</td>
    <td>1085010</td>
    <td>СО 9071 МА</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL9CAAFG0P0030541</td>
    <td>1075014</td>
    <td>CO 3402 CB</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL9CAAFG0P0030539</td>
    <td>1055102</td>
    <td>С 2810 МА</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL9CAAFG0P0030538</td>
    <td>1045007</td>
    <td>СО 9197 МА</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL9CAAFG0P0030537</td>
    <td>1035008</td>
    <td>CO 8965 MA</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL9CAAFG0P0030535</td>
    <td>1015015</td>
    <td>СО 3403 СВ</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL990AEGLS0042850</td>
    <td>151-&gt;018-&gt;8018</td>
    <td>C 7190 HC </td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1993</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL990AEGLS0042833</td>
    <td>133-&gt;020-&gt;8020</td>
    <td>C 7216 HC</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1992</td>
    <td>2001</td>
    <td>2005</td>
    <td>XL9BAACB0P0030448</td>
    <td>5001</td>
    <td>СО 5940 МА</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1992</td>
    <td>2001</td>
    <td>2008</td>
    <td>XL9BAACB0P0030439</td>
    <td>5002</td>
    <td>СО 5942 МА</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1992</td>
    <td>2001</td>
    <td>01.04.2006</td>
    <td>XL9BAACB0P0030440</td>
    <td>5003</td>
    <td>СО 5941 МА</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1992</td>
    <td>2001</td>
    <td>04.2003</td>
    <td>XL9BAACB0P0030449</td>
    <td>5004</td>
    <td>СО 5943 МА</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1992</td>
    <td>2003</td>
    <td>04.2006</td>
    <td></td>
    <td>5019</td>
    <td>СО 4361 МВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td><a href="https://drive.google.com/file/d/1vPhghoqzZCuniVQAUK4BLe1Gh1oeFAkb/view?usp=sharing">28.08.1992</a></td>
    <td>03.08.2017</td>
    <td>37316310218014</td>
    <td>4545-&gt;1545</td>
    <td>CA 2167 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>26.02.2018</td>
    <td>37316310218013</td>
    <td>4501-&gt;1501</td>
    <td>CA 1127 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>17.01.2019</td>
    <td>37316310218012</td>
    <td>4541-&gt;1541</td>
    <td>CA 2176 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>06.2015</td>
    <td>37316310218011</td>
    <td>4533-&gt;1533</td>
    <td>CA 8831 AM</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>17.01.2019</td>
    <td>37316310218010</td>
    <td>4547-&gt;1547</td>
    <td>CA 9534 AM</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>06.2015</td>
    <td>37316310218009</td>
    <td>4535-&gt;1535</td>
    <td>CA 1137 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>17.08.2016</td>
    <td>37316310218008</td>
    <td>4519-&gt;1519</td>
    <td>CA 8791 AM</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>04.01.2019</td>
    <td>37316310218007</td>
    <td>4511-&gt;1511</td>
    <td>CA 9533 AM</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>17.01.2019</td>
    <td>37316310218006</td>
    <td>4543-&gt;1543</td>
    <td>СВ 9842 КВ	</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>06.01.2017	</td>
    <td>37316310218005</td>
    <td>4549-&gt;1549</td>
    <td>CA 8830 AM</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>04.01.2019</td>
    <td>37316310218004</td>
    <td>4523-&gt;1523</td>
    <td>CA 9558 AM</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>26.06.2018</td>
    <td>37316310218003</td>
    <td>4521-&gt;1521</td>
    <td>CA 1129 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>26.02.2019</td>
    <td>37316310218002</td>
    <td>4509-&gt;1509</td>
    <td>CA 9565 AM</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>17.01.2019</td>
    <td>37316310218001</td>
    <td>4515-&gt;1515</td>
    <td>CA 3306 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>18.01.2019</td>
    <td>37316310218000</td>
    <td>4505-&gt;1505</td>
    <td>CA 8804 AM</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>06.2015</td>
    <td>37316310217999</td>
    <td>4527-&gt;1527</td>
    <td>CA 2168 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>13.12.2018</td>
    <td>37316310217998</td>
    <td>4525-&gt;1525</td>
    <td>CA 1140 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>06.2015</td>
    <td>37316310217997</td>
    <td>4507-&gt;1507</td>
    <td>CA 9536 AM</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>06.2015</td>
    <td>37316310217996</td>
    <td>4529-&gt;1529</td>
    <td>CA 3357 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>07.03.2019</td>
    <td>37316310217995</td>
    <td>4517-&gt;1517</td>
    <td>CA 8825 AM</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>09.06.2019</td>
    <td>37316310217994</td>
    <td>4531-&gt;1531</td>
    <td>CA 9549 AM</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>17.01.2019</td>
    <td>37316310217993</td>
    <td>4539-&gt;1539</td>
    <td>СА 8829 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>13.12.2018</td>
    <td>37316310217992</td>
    <td>4513-&gt;1513</td>
    <td>CA 9538 AM</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>06.2014</td>
    <td>37316310217991</td>
    <td>4503-&gt;1503</td>
    <td>CA 1125 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O302T</td>
    <td>1992</td>
    <td>28.08.1992</td>
    <td>10.04.2019</td>
    <td>37316310217990</td>
    <td>4537-&gt;1537</td>
    <td>CA 2169 AH</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1992</td>
    <td>1995</td>
    <td>2004</td>
    <td></td>
    <td>4413-&gt;1413</td>
    <td>С 2916 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1992</td>
    <td>1995</td>
    <td>09.2002</td>
    <td></td>
    <td>4415-&gt;1415</td>
    <td>АД 9653</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1992</td>
    <td>1992</td>
    <td>06.08.2001</td>
    <td></td>
    <td>2984-&gt;2785</td>
    <td>С 3454 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1992</td>
    <td>1992</td>
    <td>06.08.2001</td>
    <td></td>
    <td>2985-&gt;2786</td>
    <td>С 3456 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1992</td>
    <td>1992</td>
    <td>2004</td>
    <td></td>
    <td>4459-&gt;1459</td>
    <td>С 3509 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1992</td>
    <td>1992</td>
    <td>2004</td>
    <td></td>
    <td>4457-&gt;1457</td>
    <td>С 3510 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1992</td>
    <td>1992</td>
    <td>08.08.2001</td>
    <td></td>
    <td>3805-&gt;3957</td>
    <td>С 3519 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1992</td>
    <td>1992</td>
    <td>2004</td>
    <td></td>
    <td>2828-&gt;4497-&gt;1497</td>
    <td>С 6487 СН</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1992</td>
    <td>1992</td>
    <td>01.07.2001</td>
    <td></td>
    <td>207-&gt;4481-&gt;1481</td>
    <td>С 3564 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1992</td>
    <td>1992</td>
    <td>09.2002</td>
    <td></td>
    <td>151-&gt;4621-&gt;2817</td>
    <td>С 3566 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1992</td>
    <td>1992</td>
    <td>04.2014</td>
    <td></td>
    <td>217-&gt;1991</td>
    <td>СА 3317 АН</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1992</td>
    <td>1992</td>
    <td>09.2002</td>
    <td></td>
    <td>213-&gt;4613-&gt;2814</td>
    <td>С 3570 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1992</td>
    <td>1992</td>
    <td>01.07.2001</td>
    <td></td>
    <td>2796</td>
    <td>С 5695 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1992</td>
    <td>1992</td>
    <td>01.07.2001</td>
    <td></td>
    <td>2797</td>
    <td>С 3344 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1992</td>
    <td>1992</td>
    <td>30.04.2003</td>
    <td></td>
    <td>4449</td>
    <td>С 3437 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1992</td>
    <td>1992</td>
    <td>25.12.2005</td>
    <td></td>
    <td>4451-&gt;1029</td>
    <td>С 3439 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>10.1991</td>
    <td>1992</td>
    <td>05.2008</td>
    <td>24361091</td>
    <td>4453-&gt;1033</td>
    <td>С 5506 КТ</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1992</td>
    <td>1992</td>
    <td>05.2010</td>
    <td></td>
    <td>4455-&gt;1045</td>
    <td>С 2172 АТ</td>
  </tr>
  <tr>
    <td>MAN 895 NL202</td>
    <td>1992</td>
    <td>05.2002</td>
    <td>23.10.2007</td>
    <td>WMAA100198B010708</td>
    <td>011-&gt;8011-&gt;8003</td>
    <td>PA 0863 BB</td>
  </tr>
  <tr>
    <td>MAN A10 NL202</td>
    <td>1992</td>
    <td>05.2002</td>
    <td>23.10.2007</td>
    <td>WMAA100388B010597</td>
    <td>004-&gt;8004</td>
    <td>C 4562 MA</td>
  </tr>
  <tr>
    <td>MAN A10 NL202</td>
    <td>1992</td>
    <td>05.2002</td>
    <td>23.10.2007</td>
    <td>WMAA100389B010598</td>
    <td>005-&gt;8005-&gt;8001-&gt;6955</td>
    <td>PA 6955 BA</td>
  </tr>
  <tr>
    <td>MAN A10 NL202</td>
    <td>1992</td>
    <td>05.2002</td>
    <td>23.10.2007</td>
    <td>WMAA100434B011148</td>
    <td>003-&gt;8003-&gt;7510-&gt;8720</td>
    <td>PB 8720 BH</td>
  </tr>
  <tr>
    <td>MAN A10 NL202</td>
    <td>1992</td>
    <td>05.2002</td>
    <td>23.10.2007</td>
    <td>WMAA100436B011150</td>
    <td>008-&gt;8008-&gt;7502</td>
    <td>PA 7502 BA</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1991</td>
    <td>1991</td>
    <td>2011</td>
    <td></td>
    <td>2738-&gt;2731-&gt;3966-&gt;3996</td>
    <td>С 5367 НМ</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1991</td>
    <td>1991</td>
    <td>30.04.2003</td>
    <td></td>
    <td>2756-&gt;4438</td>
    <td>С 9831 ВА</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1991</td>
    <td>1991</td>
    <td>30.04.2003</td>
    <td></td>
    <td>2963-&gt;3852-&gt;3967-&gt;4456</td>
    <td>С 3257 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1991</td>
    <td>1991</td>
    <td>30.04.2003</td>
    <td></td>
    <td>2965-&gt;3858-&gt;3972-&gt;4450</td>
    <td>С 3249 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1991</td>
    <td>1991</td>
    <td>2004</td>
    <td></td>
    <td>4427-&gt;1427</td>
    <td>С 3183 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1991</td>
    <td>1991</td>
    <td>2004</td>
    <td></td>
    <td>4429-&gt;1429</td>
    <td>С 1365 РС</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1991</td>
    <td>1991</td>
    <td>2004</td>
    <td></td>
    <td>4431-&gt;1431</td>
    <td>С 3196 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1991</td>
    <td>1991</td>
    <td>01.07.2001</td>
    <td></td>
    <td>4433-&gt;1433</td>
    <td>С 3193 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1991</td>
    <td>1991</td>
    <td>2004</td>
    <td></td>
    <td>4435-&gt;1435</td>
    <td>С 3194 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1991</td>
    <td>1991</td>
    <td>2004</td>
    <td></td>
    <td>4437-&gt;1437</td>
    <td>С 3192 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1991</td>
    <td>1991</td>
    <td>2004</td>
    <td></td>
    <td>4439-&gt;1439</td>
    <td>С 3195 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1991</td>
    <td>1991</td>
    <td>25.07.2001</td>
    <td></td>
    <td>2741-&gt;2842</td>
    <td>С 3178 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1991</td>
    <td>1991</td>
    <td>25.07.2001</td>
    <td></td>
    <td>2763-&gt;2841</td>
    <td>С 3176 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1991</td>
    <td>1991</td>
    <td>25.07.2001</td>
    <td></td>
    <td>2991</td>
    <td>С 3103 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1991</td>
    <td>1991</td>
    <td>11.1996</td>
    <td></td>
    <td>1809-&gt;1287</td>
    <td>С 3433 ПБ</td>
  </tr>
  <tr>
    <td>MAN 895 NL202</td>
    <td>1991</td>
    <td>05.2002</td>
    <td>23.10.2007</td>
    <td>WMA8990136B012420</td>
    <td>013-&gt;8013-&gt;8379</td>
    <td>PA 8379 BA</td>
  </tr>
  <tr>
    <td>MAN 895 NL202</td>
    <td>1991</td>
    <td>05.2002</td>
    <td>23.10.2007</td>
    <td>WMA8990137B012421</td>
    <td>017-&gt;8017-&gt;8381</td>
    <td>PA 8381 BA</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>04.1991</td>
    <td>05.1980</td>
    <td>06.2008</td>
    <td>2365(0491)</td>
    <td>807</td>
    <td>СА 4684 ВА</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>09.1990</td>
    <td>1990</td>
    <td>08.2015</td>
    <td>2286(0990)<br></td>
    <td>2733-&gt;2736-&gt;4430-&gt;1023</td>
    <td>С 1858 РХ</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>09.1990</td>
    <td>05.1980</td>
    <td>08.2008</td>
    <td>2276(0990)</td>
    <td>821</td>
    <td>СА 1156 АН</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>04.1990</td>
    <td>05.1990</td>
    <td>08.2007</td>
    <td>2217(0490)</td>
    <td>867</td>
    <td>СА 1154 АН</td>
  </tr>
  <tr>
    <td>Neoplan N 409 L</td>
    <td>1990</td>
    <td></td>
    <td></td>
    <td></td>
    <td>5021</td>
    <td>СО 5693 СВ</td>
  </tr>
  <tr>
    <td>Neoplan N 409 L</td>
    <td>1990</td>
    <td></td>
    <td></td>
    <td></td>
    <td>5022</td>
    <td>СО 5761 СВ</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1990</td>
    <td>06.2006</td>
    <td>04.2008</td>
    <td></td>
    <td>5003</td>
    <td>СО 5941 МА</td>
  </tr>
  <tr>
    <td>Den Oudsten Alliance City B90</td>
    <td>1990</td>
    <td>06.2006</td>
    <td>03.08.2007</td>
    <td></td>
    <td>5019</td>
    <td>СО 4361 МВ</td>
  </tr>
  <tr>
    <td>Чавдар LC 51</td>
    <td>1990</td>
    <td>1991</td>
    <td>01.07.2001</td>
    <td></td>
    <td>2957-&gt;4476</td>
    <td>С 3073 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар LC 51</td>
    <td>1990</td>
    <td>1991</td>
    <td>2008</td>
    <td></td>
    <td>2958-&gt;4488-&gt;1057</td>
    <td>СА 1162 АН</td>
  </tr>
  <tr>
    <td>Чавдар LC 51</td>
    <td>1990</td>
    <td>1991</td>
    <td>2008</td>
    <td></td>
    <td>2960-&gt;4490-&gt;1059</td>
    <td>СА 1159 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O309D / Irankhodro</td>
    <td>1990</td>
    <td>11.1990</td>
    <td>2008</td>
    <td></td>
    <td>1885-&gt;4482-&gt;1011</td>
    <td>СА 2076 АТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O309D / Irankhodro</td>
    <td>1990</td>
    <td>11.1990</td>
    <td>2003</td>
    <td></td>
    <td>1887-&gt;4487-&gt;1015</td>
    <td>С 3292 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O309D / Irankhodro</td>
    <td>1990</td>
    <td>11.1990</td>
    <td>2020</td>
    <td></td>
    <td>1889-&gt;4484-&gt;1013</td>
    <td>СА 2075 АТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O309D / Irankhodro</td>
    <td>1990</td>
    <td>11.1990</td>
    <td>2008</td>
    <td></td>
    <td>1891-&gt;4432-&gt;1001</td>
    <td>СА 1149 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O309D / Irankhodro</td>
    <td>1990</td>
    <td>11.1990</td>
    <td>2008</td>
    <td></td>
    <td>1893-&gt;4464-&gt;1005</td>
    <td>СА 1153 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O309D / Irankhodro</td>
    <td>1990</td>
    <td>11.1990</td>
    <td>2008</td>
    <td></td>
    <td>1895-&gt;4486-&gt;1007</td>
    <td>СА 9560 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O309D / Irankhodro</td>
    <td>1990</td>
    <td>11.1990</td>
    <td></td>
    <td></td>
    <td>1897-&gt;4480-&gt;1003</td>
    <td>СА 1163 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O309D / Irankhodro</td>
    <td>1990</td>
    <td>11.1990</td>
    <td>2008</td>
    <td></td>
    <td>1899-&gt;4489-&gt;1009</td>
    <td>СА 1152 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405</td>
    <td>1990</td>
    <td>10.2005</td>
    <td></td>
    <td>WDB35700013058406</td>
    <td>9032</td>
    <td>C 4689 ХХ </td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405</td>
    <td>1990</td>
    <td>08.2002</td>
    <td>12.2016</td>
    <td>WDB35700013059991</td>
    <td>7017</td>
    <td>C 9841 МA</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>01.1992</td>
    <td>09.2002</td>
    <td></td>
    <td>203</td>
    <td>С 3269 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1989</td>
    <td></td>
    <td></td>
    <td></td>
    <td>б/н 1</td>
    <td></td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1989</td>
    <td>09.1990</td>
    <td>1997</td>
    <td></td>
    <td>3270-&gt;4397</td>
    <td>С 3270 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1989</td>
    <td>07.1990</td>
    <td>1995</td>
    <td></td>
    <td>4381</td>
    <td>С 3056 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1989</td>
    <td>07.1990</td>
    <td>1995</td>
    <td></td>
    <td>4425-&gt;4185</td>
    <td>С 3057 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1989</td>
    <td>07.1990</td>
    <td>1995</td>
    <td></td>
    <td>4179</td>
    <td>С 3058 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1989</td>
    <td>07.1990</td>
    <td>1995</td>
    <td></td>
    <td>4177</td>
    <td>С 3059 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1989</td>
    <td>07.1990</td>
    <td>1995</td>
    <td></td>
    <td>4175</td>
    <td>С 3061 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1989</td>
    <td>07.1990</td>
    <td>1995</td>
    <td></td>
    <td>4271</td>
    <td>С 3062 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1989</td>
    <td>07.1990</td>
    <td>1995</td>
    <td></td>
    <td>4385</td>
    <td>С 3063 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1989</td>
    <td>07.1990</td>
    <td>1995</td>
    <td></td>
    <td>4273</td>
    <td>С 3064 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1989</td>
    <td>07.1990</td>
    <td>1995</td>
    <td></td>
    <td>4383</td>
    <td>С 3065 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1989</td>
    <td>07.1990</td>
    <td>1995</td>
    <td></td>
    <td>4269</td>
    <td>С 3793 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1989</td>
    <td>1990</td>
    <td>1992</td>
    <td></td>
    <td>1276</td>
    <td>С 1276 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1989</td>
    <td>1990</td>
    <td>1992</td>
    <td></td>
    <td>1277</td>
    <td>С 1277 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>08.1990</td>
    <td>06.2014</td>
    <td></td>
    <td>225-&gt;А-1999</td>
    <td>СА 3312 АН</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>08.1990</td>
    <td>2004</td>
    <td></td>
    <td>259</td>
    <td>С 3002 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>08.1990</td>
    <td>2003</td>
    <td></td>
    <td>249</td>
    <td>С 3004 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>08.1990</td>
    <td>2003</td>
    <td></td>
    <td>211</td>
    <td>С 3005 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>08.1990</td>
    <td>25.07.2001</td>
    <td></td>
    <td>253</td>
    <td>С 3792 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>08.1990</td>
    <td>04.2008</td>
    <td></td>
    <td>269</td>
    <td>СА 2071 АТ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>08.1990</td>
    <td>2003</td>
    <td></td>
    <td>247</td>
    <td>С 2930 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>08.1990</td>
    <td>25.07.2001</td>
    <td></td>
    <td>265</td>
    <td>С 3013 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>08.1990</td>
    <td>13.01.2003</td>
    <td></td>
    <td>3-&gt;4603-&gt;2811</td>
    <td>С 3014 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>08.1990</td>
    <td>25.07.2001</td>
    <td></td>
    <td>277</td>
    <td>С 3015 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>08.1990</td>
    <td>25.07.2001</td>
    <td></td>
    <td>273</td>
    <td>С 3016 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1989</td>
    <td>08.1990</td>
    <td>2004</td>
    <td></td>
    <td>991</td>
    <td>С 3029 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>2001</td>
    <td></td>
    <td>2767-&gt;2867</td>
    <td>С 3007 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>2000</td>
    <td></td>
    <td>2811</td>
    <td>С 3017 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>2001</td>
    <td></td>
    <td>2753-&gt;2853</td>
    <td>С 3018 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>2001</td>
    <td></td>
    <td>2756-&gt;2852</td>
    <td>С 3020 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>2000</td>
    <td></td>
    <td>2810</td>
    <td>С 3021 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>2001</td>
    <td></td>
    <td>2758-&gt;2858</td>
    <td>С 3022 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>2001</td>
    <td></td>
    <td>2754-&gt;2854</td>
    <td>С 3023 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>2001</td>
    <td></td>
    <td>2755-&gt;2855</td>
    <td>С 3024 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>2004</td>
    <td></td>
    <td>2726-&gt;4495-&gt;1495</td>
    <td>С 6433 СН</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>23.04.2007</td>
    <td></td>
    <td>2762-&gt;2862-&gt;А-15</td>
    <td>С 3032 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>2001</td>
    <td></td>
    <td>2759-&gt;2859</td>
    <td>С 3034 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>04.06.2002</td>
    <td></td>
    <td>3036-&gt;3804-&gt;3901-&gt;3956</td>
    <td>С 3036 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>13.01.2003</td>
    <td></td>
    <td>3037-&gt;3951</td>
    <td>С 3037 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>13.01.2003</td>
    <td></td>
    <td>3038-&gt;3826-&gt;3959</td>
    <td>С 3038 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>12.2001</td>
    <td></td>
    <td>3039-&gt;3805-&gt;3705-&gt;3917</td>
    <td>С 3039 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>07.2008</td>
    <td></td>
    <td>3040-&gt;3905-&gt;1405</td>
    <td>СА 3389 АН</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>13.01.2003</td>
    <td></td>
    <td>3051-&gt;3702-&gt;3930</td>
    <td>С 3051 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>13.01.2003</td>
    <td></td>
    <td>3052-&gt;3703-&gt;3908</td>
    <td>С 3052 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>13.01.2003</td>
    <td></td>
    <td>3053-&gt;3906-&gt;2801</td>
    <td>С 3053 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>21.01.2001</td>
    <td></td>
    <td>3054-&gt;3907-&gt;3960</td>
    <td>С 3054 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1990</td>
    <td>07.1990</td>
    <td>11.2009</td>
    <td></td>
    <td>-&gt;3055-&gt;3908-&gt;3808-&gt;3708-&gt;3922-&gt;1403</td>
    <td>СА 3349 АН</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>09.1989</td>
    <td>2003</td>
    <td></td>
    <td>209</td>
    <td>С 1995 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>09.1989</td>
    <td>09.2002</td>
    <td></td>
    <td>229</td>
    <td>С 1996 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>09.1989</td>
    <td>2004</td>
    <td></td>
    <td>255</td>
    <td>С 1997 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>09.1989</td>
    <td>2003</td>
    <td></td>
    <td>2863</td>
    <td>С 1969 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>09.1989</td>
    <td>1999</td>
    <td></td>
    <td>2832</td>
    <td>С 1877 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>09.1989</td>
    <td>13.01.2003</td>
    <td></td>
    <td>3912-&gt;3711-&gt;3931-&gt;2822</td>
    <td>С 1763 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>09.1989</td>
    <td>2003</td>
    <td></td>
    <td>2803-&gt;2702</td>
    <td>С 1751 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>09.1989</td>
    <td>2003</td>
    <td></td>
    <td>2809</td>
    <td>С 1752 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>09.1989</td>
    <td>2000</td>
    <td></td>
    <td>2808</td>
    <td>С 1753 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>09.1989</td>
    <td>2017</td>
    <td></td>
    <td>2734-&gt;А-18-&gt;А-2018</td>
    <td>СА 4991 АТ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>09.1989</td>
    <td>2003</td>
    <td></td>
    <td>2919-&gt;2779</td>
    <td>С 1728 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>09.1989</td>
    <td>15.03.2000</td>
    <td></td>
    <td>2806-&gt;2721</td>
    <td>С 1729 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>09.1989</td>
    <td>2000</td>
    <td></td>
    <td>2915-&gt;2851</td>
    <td>С 1730 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>09.1989</td>
    <td>2000</td>
    <td></td>
    <td>2805</td>
    <td>С 1731 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>09.1989</td>
    <td>2003</td>
    <td></td>
    <td>2710-&gt;4424-&gt;1424</td>
    <td>С 1741 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>09.1989</td>
    <td>2003</td>
    <td></td>
    <td>2907-&gt;2773</td>
    <td>С 1746 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1989</td>
    <td>09.1989</td>
    <td>09.2002</td>
    <td></td>
    <td>2755</td>
    <td>С 1678 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>2020</td>
    <td></td>
    <td>У-22-&gt;АТМ 2664</td>
    <td>С 2664 ВН</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>2004</td>
    <td></td>
    <td>У-32-&gt;4461-&gt;1461</td>
    <td>С 1587 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>2004</td>
    <td></td>
    <td>У-24-&gt;4463-&gt;1463</td>
    <td>С 1588 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>2004</td>
    <td></td>
    <td>У-26-&gt;4465-&gt;1465</td>
    <td>С 1589 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>2004</td>
    <td></td>
    <td>У-28-&gt;4422-&gt;1422</td>
    <td>С 0819 ТН</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>2004</td>
    <td></td>
    <td>У-30-&gt;4467-&gt;1467</td>
    <td>С 1591 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>09.2002</td>
    <td></td>
    <td>31-&gt;4601-&gt;2810</td>
    <td>С 1514 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>1999</td>
    <td></td>
    <td>2727</td>
    <td>С 1527 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>25.07.2001</td>
    <td></td>
    <td>33</td>
    <td>С 1521 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>1998</td>
    <td></td>
    <td>2903</td>
    <td>С 1498 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>06.2011</td>
    <td></td>
    <td>2705-&gt;2818-&gt;3842-&gt;3914-&gt;А-3006</td>
    <td>СА 7652 АК</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>1999</td>
    <td></td>
    <td>2658</td>
    <td>С 1411 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>2004</td>
    <td></td>
    <td>2704-&gt;4487-&gt;1487</td>
    <td>С 1412 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>1999</td>
    <td></td>
    <td>2829</td>
    <td>С 1421 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>2000</td>
    <td></td>
    <td>2827</td>
    <td>С 1432 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>2000</td>
    <td></td>
    <td>2757-&gt;2857</td>
    <td>С 1433 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>2000</td>
    <td></td>
    <td>2707</td>
    <td>С 1434 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>1997</td>
    <td></td>
    <td>2701-&gt;А-12</td>
    <td>С 1435 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>15.03.2000</td>
    <td></td>
    <td>2665-&gt;2745</td>
    <td>С 1454 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>26.07.2007</td>
    <td></td>
    <td>51</td>
    <td>С 1167 НА</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>09.2002</td>
    <td></td>
    <td>205</td>
    <td>С 1459 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>09.2002</td>
    <td></td>
    <td>67</td>
    <td>С 1460 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>1989</td>
    <td>25.07.2001</td>
    <td></td>
    <td>15</td>
    <td>С 1246 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>1989</td>
    <td>25.07.2001</td>
    <td></td>
    <td>17</td>
    <td>С 1247 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>1989</td>
    <td>2009</td>
    <td></td>
    <td>13-&gt;4401-&gt;1401</td>
    <td>С 0655 КМ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>1989</td>
    <td>2003</td>
    <td></td>
    <td>221</td>
    <td>С 1249 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>1989</td>
    <td>25.07.2001</td>
    <td></td>
    <td>261</td>
    <td>С 1250 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>1989</td>
    <td>25.07.2001</td>
    <td></td>
    <td>275</td>
    <td>С 1251 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>1989</td>
    <td>09.2002</td>
    <td></td>
    <td>227</td>
    <td>С 1252 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>1989</td>
    <td>25.07.2001</td>
    <td></td>
    <td>279</td>
    <td>С 1253 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>1989</td>
    <td>01.07.2001</td>
    <td></td>
    <td>1104-&gt;4407-&gt;1407</td>
    <td>С 1104 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>1989</td>
    <td>09.2002</td>
    <td></td>
    <td>1105-&gt;4409-&gt;1409</td>
    <td>С 1105 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>1989</td>
    <td>12.01.2001</td>
    <td></td>
    <td>1106-&gt;3745</td>
    <td>С 1106 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1989</td>
    <td>1989</td>
    <td>2002</td>
    <td></td>
    <td>251</td>
    <td>С 1114 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405</td>
    <td>1989</td>
    <td>08.2002</td>
    <td>27.07.2017</td>
    <td>WDB35700413057388</td>
    <td>2850</td>
    <td>C 8840 МВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405</td>
    <td>1989</td>
    <td>08.2002</td>
    <td>29.03.2017</td>
    <td>WDB35700413057437</td>
    <td>2851</td>
    <td>C 8911 МВ </td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405</td>
    <td>1989</td>
    <td>08.2002</td>
    <td>27.07.2017</td>
    <td>WDB35700413057425</td>
    <td>2852</td>
    <td>C 8917 МВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405</td>
    <td>1989</td>
    <td>08.2002</td>
    <td>27.07.2017</td>
    <td>WDB35700413057466</td>
    <td>2853</td>
    <td>C 1431 МK</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405</td>
    <td>1989</td>
    <td>09.2002</td>
    <td>27.07.2017</td>
    <td>WDB35700413057481</td>
    <td>2854</td>
    <td>ВА 118416</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405</td>
    <td>1989</td>
    <td>09.2002</td>
    <td>27.07.2017</td>
    <td>WDB35700413057399</td>
    <td>2856</td>
    <td>C 5871 MK</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405</td>
    <td>1989</td>
    <td>10.2002</td>
    <td>27.07.2017</td>
    <td>WDB35700413057453</td>
    <td>2857</td>
    <td>C 3148 MH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405</td>
    <td>1989</td>
    <td>10.2002</td>
    <td>27.07.2017</td>
    <td>WDB35700413057411</td>
    <td>2858</td>
    <td>C 3221 MH </td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405</td>
    <td>1989</td>
    <td>11.2002</td>
    <td>24.07.2017</td>
    <td>WDB35700413057550</td>
    <td>2859</td>
    <td> C 5878 MH</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1989</td>
    <td>07.1989</td>
    <td>30.04.2003</td>
    <td></td>
    <td>2653-&gt;2753-&gt;4442</td>
    <td>С 1471 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1989</td>
    <td>1991</td>
    <td>30.04.2003</td>
    <td></td>
    <td>2732-&gt;4494</td>
    <td>С 1632 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1989</td>
    <td>10.1989</td>
    <td>05.2010</td>
    <td></td>
    <td>2737-&gt;4498-&gt;1043</td>
    <td>С 9684 ВА</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1989</td>
    <td>10.1989</td>
    <td>2005</td>
    <td></td>
    <td>2752-&gt;3992-&gt;1063</td>
    <td>С 1749 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1989</td>
    <td>05.1996</td>
    <td>30.04.2003</td>
    <td></td>
    <td>4418</td>
    <td>С 1374 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 250.67</td>
    <td>1989</td>
    <td>07.1991</td>
    <td>04.2008</td>
    <td>250.67.1989.0545</td>
    <td>4443-&gt;1051</td>
    <td>СА 0786 АА</td>
  </tr>
  <tr>
    <td>Ikarus 250.67</td>
    <td>1989</td>
    <td>07.1991</td>
    <td>2005</td>
    <td>250.67.1989.05??</td>
    <td>4445-&gt;1053</td>
    <td>С 2137 КХ</td>
  </tr>
  <tr>
    <td>Ikarus 250.67</td>
    <td>1989</td>
    <td>07.1991</td>
    <td>2009</td>
    <td>250.67.1989.0529</td>
    <td>4447-&gt;1055</td>
    <td>С 8100 КХ</td>
  </tr>
  <tr>
    <td>Neoplan N 4009 NF</td>
    <td>1988</td>
    <td>07.2005</td>
    <td></td>
    <td></td>
    <td>5029</td>
    <td>CO 0762 XA</td>
  </tr>
  <tr>
    <td>Neoplan N 4009 NF</td>
    <td>1988</td>
    <td>08.11.2001</td>
    <td></td>
    <td>WAG240096PPN20422</td>
    <td>5018</td>
    <td>СО 9941 МА</td>
  </tr>
  <tr>
    <td>Neoplan N 4009 NF</td>
    <td>1988</td>
    <td>08.11.2001</td>
    <td></td>
    <td>WAG240096PPN20419</td>
    <td>5017</td>
    <td>СО 9942 МА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405</td>
    <td>1988</td>
    <td>09.2002</td>
    <td>14.09.2016</td>
    <td>WDB35700413056623</td>
    <td>2855</td>
    <td>C 5268 MK</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1988</td>
    <td>08.1994</td>
    <td>03.1996</td>
    <td></td>
    <td>1126-&gt;4339</td>
    <td>С 1126 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>15.03.2000</td>
    <td></td>
    <td>2665-&gt;2705</td>
    <td>С 7973 НН</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>16.03.2001</td>
    <td></td>
    <td>1063-&gt;3741</td>
    <td>С 1063 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>2004</td>
    <td></td>
    <td>1064-&gt;3806-&gt;4469-&gt;1469</td>
    <td>С 1064 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>12.02.2001</td>
    <td></td>
    <td>1065-&gt;3742</td>
    <td>С 1065 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>11.2002</td>
    <td></td>
    <td>1067-&gt;3743-&gt;3913-&gt;3755-&gt;3920-&gt;3712-&gt;3932</td>
    <td>С 1067 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>12.02.2001</td>
    <td></td>
    <td>1068-&gt;3744</td>
    <td>С 1068 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>09.2002</td>
    <td></td>
    <td>5-&gt;4615-&gt;2815</td>
    <td>С 1071 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>25.07.2001</td>
    <td></td>
    <td>23</td>
    <td>С 1072 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>25.07.2001</td>
    <td></td>
    <td>7</td>
    <td>С 1073 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>25.07.2001</td>
    <td></td>
    <td>1907-&gt;У-25-&gt;25</td>
    <td>С 1074 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>25.07.2001</td>
    <td></td>
    <td>237</td>
    <td>С 1075 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>1999</td>
    <td></td>
    <td>9-&gt;4629</td>
    <td>С 1076 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>25.07.2001</td>
    <td></td>
    <td>21</td>
    <td>С 1077 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>09.2002</td>
    <td></td>
    <td>233</td>
    <td>С 1079 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>15.03.2000</td>
    <td></td>
    <td>2801-&gt;2719</td>
    <td>С 1081 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>16.03.2001</td>
    <td></td>
    <td>2837-&gt;3756-&gt;3921</td>
    <td>С 1082 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>1999</td>
    <td></td>
    <td>2718</td>
    <td>С 1083 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>1999</td>
    <td></td>
    <td>2802</td>
    <td>С 1084 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>05.10.2008</td>
    <td></td>
    <td>2720-&gt;4420-&gt;1420</td>
    <td>С 1986 РС</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>1999</td>
    <td></td>
    <td>2776-&gt;2876</td>
    <td>С 1087 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1988</td>
    <td>1988</td>
    <td>1999</td>
    <td></td>
    <td>2659</td>
    <td>С 0876 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1988</td>
    <td>10.1988</td>
    <td>1999</td>
    <td></td>
    <td>855</td>
    <td>С 1157 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>17.08.2005</td>
    <td></td>
    <td>457-&gt;4107-&gt;2204</td>
    <td>С 0186 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>2003</td>
    <td></td>
    <td>455-&gt;4313-&gt;1801</td>
    <td>С 0187 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>09.2008</td>
    <td>280.59.1419.88</td>
    <td>1271</td>
    <td>СА 2671 ВХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>02.2008</td>
    <td>280.59.1397.88</td>
    <td>1269</td>
    <td>СА 1618 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>17.08.2005</td>
    <td></td>
    <td>1233-&gt;4421-&gt;4181-&gt;2218</td>
    <td>С 0190 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>09.2009</td>
    <td>280.59.1409.88</td>
    <td>-&gt;0191-&gt;3539-&gt;3403-&gt;3506-&gt;3817-&gt;3463</td>
    <td>СА 1410 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>15.05.2005</td>
    <td></td>
    <td>0192-&gt;3390-&gt;3356</td>
    <td>С 0192 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>16.06.2015</td>
    <td>280.59.1408.88</td>
    <td>0193-&gt;3620-&gt;3252-&gt;3408-&gt;2426</td>
    <td>СА 1459 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>16.06.2015</td>
    <td>280.59.1417.88</td>
    <td>0194-&gt;3540-&gt;3404-&gt;3507-&gt;3857-&gt;3457-&gt;2420</td>
    <td>СА 1130 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>01.2010</td>
    <td>280.59.1430.88</td>
    <td>0195-&gt;3667-&gt;4199-&gt;2222</td>
    <td>СА 0799 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>2004</td>
    <td></td>
    <td>2222-&gt;2162-&gt;2124-&gt;627</td>
    <td>С 0196 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>1999</td>
    <td></td>
    <td>2110</td>
    <td>С 0197 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>05.10.2014</td>
    <td>280.59.1423.88</td>
    <td>2497-&gt;2137-&gt;2415</td>
    <td>СА 0923 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>2003</td>
    <td></td>
    <td>2393-&gt;2093</td>
    <td>С 0199 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>2000</td>
    <td></td>
    <td>2498-&gt;2140-&gt;2121-&gt;613</td>
    <td>С 0200 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>05.2008</td>
    <td>280.59.1393.88</td>
    <td>1247</td>
    <td>С 0487 КХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>06.08.2001</td>
    <td></td>
    <td>1267-&gt;1251</td>
    <td>С 0431 КХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>31.08.2005</td>
    <td></td>
    <td>401-&gt;4201-&gt;2258</td>
    <td>С 2003 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>31.08.2005</td>
    <td></td>
    <td>411-&gt;4105-&gt;2202</td>
    <td>С 2004 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>16.06.2015</td>
    <td>280.59.1389.88</td>
    <td>429-&gt;4303-&gt;2242</td>
    <td>СА 0931 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>01.2004</td>
    <td></td>
    <td>433-&gt;4213-&gt;1823</td>
    <td>С 3510 КХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>2002</td>
    <td></td>
    <td>441-&gt;4217-&gt;1825</td>
    <td>С 2007 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>2004</td>
    <td></td>
    <td>605</td>
    <td>С 2008 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>2002</td>
    <td></td>
    <td>611</td>
    <td>С 2009 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>2000</td>
    <td></td>
    <td>613-&gt;1219-&gt;1299</td>
    <td>АП 2483</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>23.06.2005</td>
    <td></td>
    <td>617</td>
    <td>С 2011 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>02.08.2007</td>
    <td></td>
    <td>633-&gt;2133-&gt;1295-&gt;3328</td>
    <td>СА 1085 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>01.2004</td>
    <td></td>
    <td>635-&gt;3329-&gt;3333-&gt;3833-&gt;3333</td>
    <td>С 2013 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>2004</td>
    <td></td>
    <td>643</td>
    <td>С 0688 КА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>03.08.2005</td>
    <td></td>
    <td>673-&gt;629-&gt;3320</td>
    <td>С 9230 ВВ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>05.2008</td>
    <td>280.59.1388.88</td>
    <td>675</td>
    <td>СА 1617 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>2004</td>
    <td></td>
    <td>1725-&gt;1335</td>
    <td>С 2017 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>2004</td>
    <td></td>
    <td>1635-&gt;1333</td>
    <td>С 2018 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>02.2009</td>
    <td></td>
    <td>1755-&gt;1209-&gt;3686-&gt;3114-&gt;2426</td>
    <td>СА 1564 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>1999</td>
    <td></td>
    <td>1605-&gt;1379</td>
    <td>С 2020 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>09.11.2005</td>
    <td></td>
    <td>2021-&gt;3109</td>
    <td>С 2021 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>09.11.2005</td>
    <td></td>
    <td>2022-&gt;3110</td>
    <td>С 2022 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>09.11.2005</td>
    <td></td>
    <td>2023-&gt;3111</td>
    <td>С 2023 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>19.08.2005</td>
    <td>280.59.1455.88</td>
    <td>2024-&gt;3112</td>
    <td>С 2024 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>09.11.2005</td>
    <td></td>
    <td>2025-&gt;3113</td>
    <td>С 2025 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>09.11.2005</td>
    <td></td>
    <td>2026-&gt;3153</td>
    <td>С 2026 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>01.2004</td>
    <td></td>
    <td>2027-&gt;3202-&gt;3116</td>
    <td>С 2027 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>01.2004</td>
    <td></td>
    <td>2028-&gt;3203-&gt;3117</td>
    <td>С 2028 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>09.2009</td>
    <td>280.59.1405.88</td>
    <td>2029-&gt;3245-&gt;3536-&gt;3861-&gt;3461</td>
    <td>СА 1132 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>01.2010</td>
    <td>280.59.1444.88</td>
    <td>2030-&gt;3246-&gt;3537-&gt;3862-&gt;3462</td>
    <td>СА 1509 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>16.06.2015</td>
    <td>280.59.1441.88</td>
    <td>2112-&gt;2412</td>
    <td>СВ 4067 РА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>2004</td>
    <td></td>
    <td>2114-&gt;625</td>
    <td>С 2032 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>02.08.2007</td>
    <td>280.59.1446.88</td>
    <td>2116-&gt;1311-&gt;1321-&gt;3329</td>
    <td>СА 1409 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>31.10.2012</td>
    <td>280.59.1426.88</td>
    <td>2117</td>
    <td>СА 0804 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>16.06.2015</td>
    <td></td>
    <td>2224-&gt;2424</td>
    <td>СА 0792 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>23.07.2011</td>
    <td>280.59.1429.88</td>
    <td>2225-&gt;2400</td>
    <td>СА 0795 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>13.04.2015</td>
    <td></td>
    <td>2392</td>
    <td>С 5974 КХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>03.05.2015</td>
    <td>280.59.1436.88</td>
    <td>2417</td>
    <td>СА 0932 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>2003</td>
    <td></td>
    <td>2257-&gt;2425</td>
    <td>С 2039 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>03.2010</td>
    <td></td>
    <td>2255-&gt;2422</td>
    <td>С 7432 РС</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>01.2000</td>
    <td></td>
    <td>2111</td>
    <td>С 2041 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>08.2008</td>
    <td>280.59.1451.88</td>
    <td>2113-&gt;1345</td>
    <td>С 2069 КХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>04.2011</td>
    <td>280.59.1431.88</td>
    <td>2115</td>
    <td>СА 0929 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>14.05.2015</td>
    <td>280.59.1434.88</td>
    <td>2229-&gt;2401</td>
    <td>СА 0802 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>19.09.2015</td>
    <td>280.59.1452.88</td>
    <td>2226-&gt;2444</td>
    <td>СА 0791 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>	24.02.2010</td>
    <td>280.59.1422.88</td>
    <td>2232-&gt;2132-&gt;2404</td>
    <td>СА 5871 ВХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>19.06.2015</td>
    <td>280.59.1412.88</td>
    <td>2394-&gt;2454</td>
    <td>СА 1480 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>19.06.2015</td>
    <td>280.59.1425.88</td>
    <td>2395-&gt;2499</td>
    <td>СА 0796 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>16.06.2015</td>
    <td>280.59.1415.88</td>
    <td>2496</td>
    <td>СА 0797 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>05.2004</td>
    <td></td>
    <td>2418-&gt;2102-&gt;2119</td>
    <td>С 2050 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>2009</td>
    <td>280.59.1454.88</td>
    <td>2051-&gt;3311-&gt;3811-&gt;3311</td>
    <td>СА 1518 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>15.05.2005</td>
    <td></td>
    <td>2052-&gt;3392</td>
    <td>С 2052 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>11.2010</td>
    <td>280.59.1438.88</td>
    <td>2053-&gt;3393-&gt;3504-&gt;3856-&gt;3456</td>
    <td>СА 1506 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>	15.06.2005</td>
    <td></td>
    <td>2054-&gt;3394-&gt;3350</td>
    <td> С 2054 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>2009</td>
    <td>280.59.1395.88</td>
    <td>2055-&gt;3395-&gt;3413</td>
    <td>СА 1566 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>12.2003</td>
    <td></td>
    <td>2056-&gt;3396</td>
    <td>С 2056 ПБ </td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>2009</td>
    <td>280.59.1448.88</td>
    <td>2057-&gt;3443-&gt;3343</td>
    <td>СА 1416 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>	15.06.2005</td>
    <td></td>
    <td>2058-&gt;3444-&gt;3344</td>
    <td>С 2058 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>15.06.2005</td>
    <td></td>
    <td>2059-&gt;3445-&gt;3345</td>
    <td>С 2059 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.59</td>
    <td>1988</td>
    <td>12.1988</td>
    <td>	15.06.2005</td>
    <td></td>
    <td>2100-&gt;3446-&gt;3346</td>
    <td>С 2100 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>1999</td>
    <td></td>
    <td>35-&gt;4635</td>
    <td>С 0524 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>25.07.2001</td>
    <td></td>
    <td>41</td>
    <td>С 0526 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>09.2002</td>
    <td></td>
    <td>43-&gt;4631-&gt;2819</td>
    <td>С 0527 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>09.2002</td>
    <td></td>
    <td>39-&gt;4483-&gt;1483</td>
    <td>С 0529 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>09.2002</td>
    <td></td>
    <td>219-&gt;4619-&gt;2816</td>
    <td>С 0530 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>09.2002</td>
    <td></td>
    <td>223</td>
    <td>С 2928 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>01.07.2001</td>
    <td></td>
    <td>239-&gt;4403-&gt;1403</td>
    <td>С 0532 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>2003</td>
    <td></td>
    <td>231</td>
    <td>С 0533 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>1999</td>
    <td></td>
    <td>11</td>
    <td>С 0534 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>01.07.2001</td>
    <td></td>
    <td>241-&gt;4405-&gt;1405</td>
    <td>С 0536 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>09.2002</td>
    <td></td>
    <td>1839-&gt;127</td>
    <td>С 0537 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>25.07.2001</td>
    <td></td>
    <td>29</td>
    <td>С 0539 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>2004</td>
    <td></td>
    <td>37</td>
    <td>С 0541 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>25.07.2001</td>
    <td></td>
    <td>45</td>
    <td>С 0542 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>25.07.2001</td>
    <td></td>
    <td>47</td>
    <td>С 0543 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>09.2002</td>
    <td></td>
    <td>243-&gt;4623-&gt;2818</td>
    <td>С 0546 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>25.07.2001</td>
    <td></td>
    <td>49</td>
    <td>С 0547 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>06.2014</td>
    <td></td>
    <td>267-&gt;999</td>
    <td>С 6481 ВТ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>12.01.2001</td>
    <td></td>
    <td>0562-&gt;3900-&gt;3812-&gt;3909</td>
    <td>С 0562 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>12.01.2001</td>
    <td></td>
    <td>0563-&gt;3901-&gt;3840-&gt;3913</td>
    <td>С 0563 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>09.1999</td>
    <td></td>
    <td>0564-&gt;3945</td>
    <td>С 0564 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>12.2000</td>
    <td></td>
    <td>0565-&gt;3902-&gt;3841-&gt;3964</td>
    <td>С 0565 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>28.03.2007</td>
    <td></td>
    <td>0566-&gt;3946-&gt;1407</td>
    <td>СА 3342 АН</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>13.01.2003</td>
    <td></td>
    <td>0648-&gt;3800-&gt;3952</td>
    <td>С 0648 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>1996</td>
    <td></td>
    <td>0649-&gt;3903</td>
    <td>С 0649 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>1996</td>
    <td></td>
    <td>0650-&gt;3801</td>
    <td>С 0650 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>13.01.2003</td>
    <td></td>
    <td>-&gt;0651-&gt;3838-&gt;3962-&gt;3715-&gt;3902-&gt;2821</td>
    <td>С 0651 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2009</td>
    <td></td>
    <td>0652-&gt;3740-&gt;3918-&gt;1409</td>
    <td>СА 3321 АН</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>01.07.2001</td>
    <td></td>
    <td>1919-&gt;У-18-&gt;4473-&gt;1473</td>
    <td>С 0214 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>2013</td>
    <td></td>
    <td>1905-&gt;4419-&gt;А-14</td>
    <td>СА 7824 АС</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>09.2009</td>
    <td>280.04.1963.87</td>
    <td>0008-&gt;3101</td>
    <td>СА 9394 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>14.02.2000</td>
    <td></td>
    <td>0009-&gt;3300-&gt;3800</td>
    <td>С 0009 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>05.2004</td>
    <td></td>
    <td>0010-&gt;3430-&gt;3339-&gt;3448</td>
    <td>С 0010 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>14.02.2000</td>
    <td></td>
    <td>0011-&gt;3190-&gt;3407-&gt;3264-&gt;3844</td>
    <td>С 0011 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>11.2010</td>
    <td>280.04.4181.87</td>
    <td>-&gt;0012-&gt;3380-&gt;3266-&gt;3513-&gt;3859-&gt;3459</td>
    <td>СА 2320 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>28.05.2005</td>
    <td></td>
    <td>0013-&gt;3431-&gt;3331</td>
    <td>С 0013 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>05.2004</td>
    <td></td>
    <td>0014-&gt;3102-&gt;3415</td>
    <td>С 0014 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>14.02.2000</td>
    <td></td>
    <td>0015-&gt;3610-&gt;3242-&gt;3610</td>
    <td>С 0015 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>05.2004</td>
    <td></td>
    <td>0016-&gt;3240-&gt;3531-&gt;3259-&gt;3426</td>
    <td>С 0016 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>	31.08.2005</td>
    <td></td>
    <td>445-&gt;4307-&gt;2243</td>
    <td>С 0018 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>26.08.2004</td>
    <td>280.04.1978.87</td>
    <td>1461-&gt;4265-&gt;2228</td>
    <td>СА 0789 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>01.2004</td>
    <td></td>
    <td>1475-&gt;4169-&gt;2215</td>
    <td>С 0020 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>2005</td>
    <td></td>
    <td>461-&gt;4111-&gt;4379-&gt;1853</td>
    <td>С 0021 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>06.08.2001</td>
    <td></td>
    <td>1729-&gt;1225-&gt;1359</td>
    <td>АП 9169</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>06.08.2001</td>
    <td></td>
    <td>1727-&gt;1223</td>
    <td>С 0023 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>2009</td>
    <td>280.04.1975.87</td>
    <td>749</td>
    <td>СА 1147 АН</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>2009</td>
    <td>280.04.1962.87</td>
    <td>773</td>
    <td>СА 9557 АМ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>1998</td>
    <td></td>
    <td>739-&gt;1219</td>
    <td>С 0026 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>06.04.2015</td>
    <td>280.04.1966.87</td>
    <td>615-&gt;4193-&gt;2221</td>
    <td>СА 0812 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>06.08.2001</td>
    <td></td>
    <td>1731-&gt;1227</td>
    <td>С 0028 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>02.2010</td>
    <td></td>
    <td>0029-&gt;3191-&gt;2432</td>
    <td>СА 2960 ВХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>19.06.2015</td>
    <td></td>
    <td>0030-&gt;3103-&gt;2430</td>
    <td>СА 1520 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>05.2004</td>
    <td></td>
    <td>0031-&gt;3301-&gt;3801-&gt;3447</td>
    <td>С 0031 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>15.06.2005</td>
    <td></td>
    <td>0032-&gt;3432-&gt;3332</td>
    <td>С 0032 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>09.2009</td>
    <td>280.04.1941.87</td>
    <td>0033-&gt;3381-&gt;3262-&gt;3411</td>
    <td>СА 1436 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>09.2009</td>
    <td></td>
    <td>0034-&gt;3302</td>
    <td>СА 0974 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>14.02.2000</td>
    <td></td>
    <td>0035-&gt;3303-&gt;3803</td>
    <td>С 0035 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>05.2004</td>
    <td></td>
    <td>0036-&gt;3433-&gt;3349-&gt;3436</td>
    <td>С 0036 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>11.1988</td>
    <td></td>
    <td>37</td>
    <td>С 0037 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>04.2004</td>
    <td></td>
    <td>0038-&gt;3104</td>
    <td>С 0038 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>09.2009</td>
    <td></td>
    <td>0039-&gt;3105</td>
    <td>СА 0978 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>06.08.2001</td>
    <td></td>
    <td>1283-&gt;1243</td>
    <td>С 5816 РТ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>08.2009</td>
    <td>280.04.1995.87</td>
    <td>779-&gt;1313</td>
    <td>С 1194 КХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>06.1998</td>
    <td></td>
    <td>1619-&gt;1349</td>
    <td>С 0042 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>1999</td>
    <td></td>
    <td>719</td>
    <td>С 0043 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>1999</td>
    <td></td>
    <td>629-&gt;2400-&gt;629-&gt;1297</td>
    <td>С 0044 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>04.06.2015</td>
    <td>280.04.1999.87</td>
    <td>1477-&gt;4171-&gt;2216</td>
    <td>СА 0938 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>2003</td>
    <td></td>
    <td>1481-&gt;4173-&gt;1815</td>
    <td>С 0046 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>2004</td>
    <td></td>
    <td>1469-&gt;4267-&gt;1827</td>
    <td>С 0047 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>04.2004</td>
    <td></td>
    <td>1457-&gt;4263-&gt;2229</td>
    <td>С 0048 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>17.08.2005</td>
    <td></td>
    <td>1453-&gt;4165-&gt;2213</td>
    <td>С 0049 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>01.2004</td>
    <td></td>
    <td>1445-&gt;4365-&gt;1843</td>
    <td>С 3542 КХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>16.06.2015</td>
    <td>280.04.1992.87</td>
    <td>463-&gt;4113-&gt;2205</td>
    <td>СА 0945 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>06.2004</td>
    <td></td>
    <td>0052-&gt;3434-&gt;3334-&gt;3433</td>
    <td>С 0052 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>14.02.2000</td>
    <td></td>
    <td>0053-&gt;3382-&gt;3882</td>
    <td>С 0053 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>05.2004</td>
    <td></td>
    <td>0054-&gt;3383-&gt;3421</td>
    <td>С 0054 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>16.06.2015</td>
    <td></td>
    <td>0055-&gt;3106-&gt;2425</td>
    <td>СА 1129 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>02.2010</td>
    <td>280.04.1960.87</td>
    <td>0056-&gt;3611-&gt;3243-&gt;3405</td>
    <td>СА 1563 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>08.2009</td>
    <td>280.04.1967.87</td>
    <td>1613-&gt;1307</td>
    <td>С 9348 КХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>01.2004</td>
    <td></td>
    <td>1451-&gt;4371-&gt;1849</td>
    <td>С 0058 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>05.2004</td>
    <td></td>
    <td>0061-&gt;3192-&gt;3418</td>
    <td>С 0061 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>09.2009</td>
    <td>280.04.3592.87</td>
    <td>0062-&gt;3241-&gt;3532-&gt;3260-&gt;3410</td>
    <td>СА 2961 ВХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>09.2009</td>
    <td>280.04.3566.87</td>
    <td>0063-&gt;3145</td>
    <td>СА 1902 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>04.06.2002</td>
    <td></td>
    <td>0064-&gt;3193-&gt;3419</td>
    <td>С 0064 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>09.2009</td>
    <td></td>
    <td>-&gt;0065-&gt;3194-&gt;3408-&gt;3670-&gt;3255-&gt;3119</td>
    <td>СА 1508 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>02.2010</td>
    <td>280.04.3612.87</td>
    <td>0066-&gt;3146-&gt;3402</td>
    <td>СА 1395 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>05.2004</td>
    <td></td>
    <td>0067-&gt;3242-&gt;3533-&gt;3261-&gt;3427</td>
    <td>С 0067 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>12.07.2005</td>
    <td></td>
    <td>0068-&gt;3384-&gt;3501-&gt;3115</td>
    <td>С 0068 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>09.2009</td>
    <td>280.04.3587.87</td>
    <td>0069-&gt;3304-&gt;3804-&gt;3452</td>
    <td>СА 1413 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>17.04.2015</td>
    <td></td>
    <td>0070-&gt;3385-&gt;3431-&gt;3361-&gt;2244</td>
    <td>СА 0935 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>10.11.2005</td>
    <td></td>
    <td>-&gt;0071-&gt;3660-&gt;1291-&gt;1863-&gt;1205-&gt;1371</td>
    <td>С 4196 РТ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>04.06.2002</td>
    <td></td>
    <td>0072-&gt;3531-&gt;3635-&gt;3827-&gt;3445</td>
    <td>С 0072 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>14.02.2000</td>
    <td></td>
    <td>0073-&gt;3532-&gt;3678-&gt;3330-&gt;3830</td>
    <td>С 0073 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>02.2010</td>
    <td>280.04.3606.87</td>
    <td>0074-&gt;3612-&gt;3244-&gt;3406</td>
    <td>СА 1519 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>16.06.2015</td>
    <td>280.04.3619.87</td>
    <td>-&gt;0075-&gt;3533-&gt;3636-&gt;2333-&gt;2033-&gt;2247</td>
    <td>СА 0801 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>14.02.2000</td>
    <td></td>
    <td>0076-&gt;3534-&gt;3637-&gt;3500-&gt;3815</td>
    <td>С 0076 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>06.08.2001</td>
    <td></td>
    <td>0077-&gt;3535-&gt;3679-&gt;3410-&gt;3508-&gt;3858-&gt;3446</td>
    <td>С 0077 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>1998</td>
    <td></td>
    <td>0078-&gt;3661</td>
    <td>С 0078 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>04.2006</td>
    <td></td>
    <td>0079-&gt;3107-&gt;3440-&gt;3360</td>
    <td>С 0079 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>10.09.2005</td>
    <td></td>
    <td>0080-&gt;3613-&gt;3245-&gt;3422-&gt;3122-&gt;3422-&gt;3362</td>
    <td>С 0080 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>15.05.2005</td>
    <td></td>
    <td>0081-&gt;3536-&gt;3215-&gt;3429-&gt;3366</td>
    <td>С 0081 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>05.2004</td>
    <td></td>
    <td>0082-&gt;3614-&gt;3246-&gt;3401</td>
    <td>С 0082 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>05.2004</td>
    <td></td>
    <td>0083-&gt;3537-&gt;3405-&gt;3263-&gt;3439</td>
    <td>С 0083 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>07.2001</td>
    <td></td>
    <td>0084-&gt;3662-&gt;631-&gt;635</td>
    <td>С 0109 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>2004</td>
    <td></td>
    <td>949-&gt;1263</td>
    <td>С 0085 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>2004</td>
    <td></td>
    <td>741-&gt;1341</td>
    <td>С 0086 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>17.08.2005</td>
    <td></td>
    <td>1467-&gt;4377-&gt;2254</td>
    <td>С 0087 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>15.05.2005</td>
    <td></td>
    <td>669-&gt;3326</td>
    <td>С 1408 НВ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>06.08.2001</td>
    <td></td>
    <td>1719</td>
    <td>С 0089 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>1999</td>
    <td></td>
    <td>1623-&gt;3642-&gt;3254-&gt;3642</td>
    <td>С 0090 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>2004</td>
    <td></td>
    <td>951-&gt;1265</td>
    <td>С 1852 КХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>27.02.2007</td>
    <td></td>
    <td>1603-&gt;1259</td>
    <td>СА 1615 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>1999</td>
    <td></td>
    <td>1865-&gt;1261</td>
    <td>С 0093 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>17.08.2005</td>
    <td></td>
    <td>465-&gt;4115-&gt;2206</td>
    <td>С 0094 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>2000</td>
    <td></td>
    <td>1699-&gt;1691</td>
    <td>АП 9173</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>2004</td>
    <td></td>
    <td>1733-&gt;1229</td>
    <td>С 0096 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>15.05.2005</td>
    <td></td>
    <td>667-&gt;1211-&gt;3327</td>
    <td>С 0097 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>01.2004</td>
    <td></td>
    <td>1465-&gt;4375-&gt;1851</td>
    <td>С 0098 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>14.01.2002</td>
    <td></td>
    <td>1443-&gt;4363-&gt;1887</td>
    <td>С 0099 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>12.2001</td>
    <td></td>
    <td>1449-&gt;4369-&gt;1847-&gt;645</td>
    <td>С 0100 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>14.01.2002</td>
    <td></td>
    <td>1463-&gt;4373-&gt;1889</td>
    <td>С 0101 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2005</td>
    <td></td>
    <td>1447-&gt;4367-&gt;1845</td>
    <td>С 0102 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>14.01.2002</td>
    <td></td>
    <td>1697-&gt;1281</td>
    <td>С 2876 ТМ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>1998</td>
    <td></td>
    <td>729</td>
    <td>С 9228 ВВ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>04.02.2002</td>
    <td></td>
    <td>1201-&gt;601-&gt;1207</td>
    <td>С 9585 КН</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2004</td>
    <td></td>
    <td>1735-&gt;1231</td>
    <td>С 0106 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>28.05.2005</td>
    <td></td>
    <td>405-&gt;4103-&gt;1803</td>
    <td>С 0107 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>17.06.2005</td>
    <td></td>
    <td>1695-&gt;1273</td>
    <td>С 6185 РА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2000</td>
    <td></td>
    <td>631-&gt;2401-&gt;635-&gt;631</td>
    <td>С 0084 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2005</td>
    <td></td>
    <td>505-&gt;4207-&gt;1821</td>
    <td>С 0112 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>01.2004</td>
    <td></td>
    <td>529-&gt;4331-&gt;1833</td>
    <td>С 0113 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>04.2004</td>
    <td></td>
    <td>503-&gt;4301-&gt;4325-&gt;2248</td>
    <td>С 2918 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2003</td>
    <td></td>
    <td>443-&gt;4305-&gt;1877</td>
    <td>С 0115 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>02.2010</td>
    <td></td>
    <td>449-&gt;4309-&gt;2244-&gt;3361</td>
    <td>СА 0972 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>17.08.2005</td>
    <td></td>
    <td>513-&gt;4123-&gt;2208</td>
    <td>С 0117 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2004</td>
    <td></td>
    <td>515-&gt;4125-&gt;1805</td>
    <td>С 0118 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>14.01.2002</td>
    <td></td>
    <td>607</td>
    <td>С 5818 РТ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>1998</td>
    <td></td>
    <td>649</td>
    <td>С 0120 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2004</td>
    <td></td>
    <td>1279-&gt;1343</td>
    <td>С 6478 ВС</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2000</td>
    <td></td>
    <td>653-&gt;1353</td>
    <td>С 0122 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>28.07.2005</td>
    <td></td>
    <td>671</td>
    <td>С 0123 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2001</td>
    <td></td>
    <td>701-&gt;1331</td>
    <td>С 0124 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>1999</td>
    <td></td>
    <td>713</td>
    <td>С 0614 НВ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>06.08.2001</td>
    <td></td>
    <td>771</td>
    <td>С 0125 НВ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>1998</td>
    <td></td>
    <td>1609-&gt;1309</td>
    <td>С 0127 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>06.08.2001</td>
    <td></td>
    <td>1625-&gt;1325</td>
    <td>С 0128 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>02.2009</td>
    <td>280.04.4173.87</td>
    <td>1661-&gt;3685-&gt;3867-&gt;3467</td>
    <td>СА 1517 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2004</td>
    <td></td>
    <td>1673-&gt;2109-&gt;1673</td>
    <td>С 0130 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>09.2009</td>
    <td>280.04.4187.87</td>
    <td>0131-&gt;3147-&gt;3403</td>
    <td>СА 1274 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>	11.11.2002</td>
    <td></td>
    <td>0132-&gt;3148-&gt;3417</td>
    <td>С 0132 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>05.07.2005</td>
    <td></td>
    <td>0133-&gt;3305</td>
    <td>С 0133 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>21.06.2015</td>
    <td></td>
    <td>-&gt;0134-&gt;3243-&gt;3534-&gt;3834-&gt;3468-&gt;2427</td>
    <td>СА 1272 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2004</td>
    <td></td>
    <td>0135-&gt;3538-&gt;3680-&gt;4395-&gt;1855</td>
    <td>С 0135 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>05.2004</td>
    <td></td>
    <td>0136-&gt;3615-&gt;3247-&gt;3423</td>
    <td>С 0136 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>02.2010</td>
    <td>280.04.4171.87</td>
    <td>0137-&gt;3663-&gt;3865-&gt;3465</td>
    <td>С 2499 КХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>07.12.2009</td>
    <td>280.04.4161.87</td>
    <td>0138-&gt;3306-&gt;3806-&gt;3453</td>
    <td>СА 0975 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>02.2009</td>
    <td>280.04.4157.87</td>
    <td>0139-&gt;3616-&gt;3248-&gt;3407</td>
    <td>СА 1567 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>09.11.2005</td>
    <td></td>
    <td>0140-&gt;3195</td>
    <td>С 0140 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>16.06.2015</td>
    <td></td>
    <td>0141-&gt;3149-&gt;2431</td>
    <td>СА 0971 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>05.2004</td>
    <td></td>
    <td>0142-&gt;3150-&gt;3444-&gt;3144-&gt;3444</td>
    <td>С 0142 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>03.05.2015</td>
    <td></td>
    <td>0143-&gt;3617-&gt;3249-&gt;3118-&gt;2429</td>
    <td>СА 3794 ВХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>05.1999</td>
    <td></td>
    <td>0144-&gt;3386-&gt;3502-&gt;3816</td>
    <td>С 0144 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>02.2009</td>
    <td>280.04.4174.87</td>
    <td>0145-&gt;3435-&gt;3335-&gt;3434-&gt;3364</td>
    <td>СА 1415 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>02.2009</td>
    <td>280.04.4167.87</td>
    <td>0146-&gt;3387-&gt;3503-&gt;3855-&gt;3455</td>
    <td>СА 1276 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2002</td>
    <td></td>
    <td>0147-&gt;3664-&gt;4393-&gt;2255</td>
    <td>С 0147 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>15.06.2005</td>
    <td></td>
    <td>0148-&gt;3436-&gt;3336</td>
    <td>С 0148 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>02.2009</td>
    <td>280.04.4154.87</td>
    <td>0149-&gt;3437-&gt;3337</td>
    <td>СА 1084 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>07.2007</td>
    <td></td>
    <td>0150-&gt;3388-&gt;3432-&gt;3363</td>
    <td>СА 1514 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>28.05.2005</td>
    <td></td>
    <td>407-&gt;4203-&gt;1817</td>
    <td>С 0151 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>09.2005</td>
    <td></td>
    <td>409-&gt;4205-&gt;1819</td>
    <td>С 0152 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2004</td>
    <td></td>
    <td>451-&gt;4311-&gt;2245</td>
    <td>С 0153 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2002</td>
    <td></td>
    <td>473-&gt;4315-&gt;2246</td>
    <td>С 0154 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2004</td>
    <td></td>
    <td>609-&gt;1237</td>
    <td>С 0155 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>06.08.2001</td>
    <td></td>
    <td>621</td>
    <td>С 0156 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>06.08.2001</td>
    <td></td>
    <td>735-&gt;1327-&gt;1357</td>
    <td>АП 2194</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>11.2003</td>
    <td>280.04.4191.87</td>
    <td>1653-&gt;3218-&gt;3400-&gt;3218-&gt;3889</td>
    <td>СА 0973 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>09.2008</td>
    <td></td>
    <td>1257</td>
    <td>СА 1134 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>1999</td>
    <td></td>
    <td>1253</td>
    <td>С 0160 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>23.07.2007</td>
    <td>280.04.3618.87</td>
    <td>0161-&gt;3196-&gt;3360</td>
    <td>СА 1412 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>21.04.2008</td>
    <td>280.04.1961.87</td>
    <td>0162-&gt;3197-&gt;3671-&gt;3256-&gt;3120</td>
    <td>СА 2321 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>11.2010</td>
    <td>280.04.4177.87</td>
    <td>0163-&gt;3198-&gt;3515-&gt;3860-&gt;3460</td>
    <td>СА 1904 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>16.06.2015</td>
    <td>280.04.4189.87</td>
    <td>0164-&gt;3151-&gt;3404-&gt;2097-&gt;2248</td>
    <td>СА 1565 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>09.2009</td>
    <td></td>
    <td>0165-&gt;3244-&gt;3535-&gt;3258-&gt;3409</td>
    <td>СА 1437 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>04.2006</td>
    <td>280.04.4192.87</td>
    <td>0166-&gt;3199-&gt;3666-&gt;3866-&gt;3888</td>
    <td>СА 1510 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>09.2009</td>
    <td></td>
    <td>-&gt;0167-&gt;3618-&gt;3250-&gt;3424-&gt;3824-&gt;3466</td>
    <td>СА 1346 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>1999</td>
    <td></td>
    <td>0168-&gt;3200-&gt;4287</td>
    <td>С 0168 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>11.11.2002</td>
    <td></td>
    <td>0169-&gt;3619-&gt;3251-&gt;3425</td>
    <td>С 0169 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>09.2009</td>
    <td></td>
    <td>-&gt;0170-&gt;3665-&gt;3415-&gt;3314-&gt;3814-&gt;3458</td>
    <td>СА 1513 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>06.08.2001</td>
    <td></td>
    <td>0171-&gt;3666-&gt;615</td>
    <td>С 0685 КА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>21.03.2008</td>
    <td>280.04.4210.87</td>
    <td>0172-&gt;3389</td>
    <td>СА 1598 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>11.2010</td>
    <td></td>
    <td>0173-&gt;3438-&gt;3338-&gt;3838-&gt;3469</td>
    <td>СА 0980 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>09.2009</td>
    <td>280.04.4206.87</td>
    <td>-&gt;0174-&gt;3307-&gt;3807-&gt;3146-&gt;3846-&gt;3470</td>
    <td>СА 1597 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>09.2009</td>
    <td></td>
    <td>-&gt;0175-&gt;3201-&gt;3409-&gt;3511-&gt;3820-&gt;3464</td>
    <td>СА 1408 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2003</td>
    <td></td>
    <td>517-&gt;4127-&gt;2210</td>
    <td>С 0176 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2000</td>
    <td>280.04.4320.87</td>
    <td>0177-&gt;Балканкар-&gt;4071</td>
    <td>Е 4071 АН</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>17.08.2005</td>
    <td></td>
    <td>2139-&gt;2239-&gt;2306</td>
    <td>АП 2139</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>2004</td>
    <td></td>
    <td>2143-&gt;4302-&gt;1829</td>
    <td>С 2919 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>09.2002</td>
    <td></td>
    <td>2152-&gt;2128</td>
    <td>АП 2152</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>1999</td>
    <td></td>
    <td>2155</td>
    <td>АП 2155</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>06.08.2001</td>
    <td></td>
    <td>2157-&gt;2123-&gt;623</td>
    <td>АП 2157</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>16.06.2015</td>
    <td>280.04.3582.87</td>
    <td>2167-&gt;2129</td>
    <td>СА 0813 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>06.08.2001</td>
    <td></td>
    <td>2173-&gt;2130-&gt;1355-&gt;1385</td>
    <td>С 5817 РТ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>11.2013</td>
    <td>280.04.1950.87</td>
    <td>2175-&gt;3413-&gt;3509-&gt;3818-&gt;3887</td>
    <td>СА 1505 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>2004</td>
    <td></td>
    <td>2176-&gt;639</td>
    <td>АП 2176</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>1999</td>
    <td></td>
    <td>2193</td>
    <td>АП 2193</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>2000</td>
    <td></td>
    <td>2194-&gt;2126-&gt;1357-&gt;1327</td>
    <td>С 0157 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>09.2002</td>
    <td></td>
    <td>2195-&gt;2127</td>
    <td>АП 2195</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>17.08.2005</td>
    <td></td>
    <td>2196-&gt;2431-&gt;2310</td>
    <td>АП 2196</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>1999</td>
    <td></td>
    <td>2197</td>
    <td>АП 2197</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>25.04.2015</td>
    <td>280.04.3596.87</td>
    <td>2198-&gt;2398-&gt;2098-&gt;2249</td>
    <td>СА 0798 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>03.2005</td>
    <td></td>
    <td>2199-&gt;2432-&gt;2311</td>
    <td>С 2915 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>06.08.2001</td>
    <td></td>
    <td>2218-&gt;2118-&gt;1383-&gt;1315</td>
    <td>АП 5602</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>25.06.2011</td>
    <td></td>
    <td>2230-&gt;2445</td>
    <td>СА 0950 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>1999</td>
    <td></td>
    <td>2242-&gt;2413</td>
    <td>АП 2242</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>16.06.2015</td>
    <td></td>
    <td>2243-&gt;2442</td>
    <td>СА 0927 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>01.04.2011</td>
    <td>280.04.4198.87</td>
    <td>2289-&gt;2410</td>
    <td>СА 0816 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>2003</td>
    <td></td>
    <td>2321-&gt;2021</td>
    <td>АП 2321</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>2003</td>
    <td></td>
    <td>2343-&gt;2043</td>
    <td>АП 2343</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>12.2010</td>
    <td>280.04.1940.87</td>
    <td>2360</td>
    <td>СА 0944 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>2004</td>
    <td></td>
    <td>2361-&gt;2261-&gt;2307</td>
    <td>АП 2361</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>17.08.2005</td>
    <td></td>
    <td>2367-&gt;2468</td>
    <td>АП 2367</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>16.06.2015</td>
    <td>280.04.3564.87</td>
    <td>2368-&gt;2268-&gt;2308</td>
    <td>СА 6837 ВХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>03.2011</td>
    <td>280.04.3586.87</td>
    <td>2369-&gt;2069</td>
    <td>СА 1482 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>09.2002</td>
    <td></td>
    <td>2370</td>
    <td>АП 2370</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>2003</td>
    <td></td>
    <td>2371-&gt;2071</td>
    <td>АП 2371</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>19.09.2014</td>
    <td>280.04.4148.87</td>
    <td>2373</td>
    <td>СА 0925 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2004</td>
    <td></td>
    <td>2374-&gt;2074-&gt;2319</td>
    <td>АП 2374</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>17.04.2015</td>
    <td>280.04.4132.87</td>
    <td>2375-&gt;2475</td>
    <td>С 2904 КС</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>19.09.2014</td>
    <td>280.04.4128.87</td>
    <td>2376</td>
    <td>С 6915 КХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2003</td>
    <td></td>
    <td>2377</td>
    <td>АП 2377</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>09.2002</td>
    <td></td>
    <td>2378-&gt;2315</td>
    <td>АП 2378</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>26.09.2014</td>
    <td>280.04.4122.87</td>
    <td>2379-&gt;2451</td>
    <td>СА 5358 ВХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>07.2011</td>
    <td>280.04.4143.87</td>
    <td>2380-&gt;2480</td>
    <td>СА 0935 МК</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>03.2002</td>
    <td></td>
    <td>2381-&gt;2316</td>
    <td>АП 2381</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>19.06.2015</td>
    <td>280.04.4193.87</td>
    <td>2382</td>
    <td>СА 0936 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>20.03.2015</td>
    <td>280.04.1946.87</td>
    <td>2412-&gt;2256-&gt;2433</td>
    <td>СА 0086 СТ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>2001</td>
    <td></td>
    <td>2425-&gt;2104-&gt;2004</td>
    <td>АП 2425</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>1999</td>
    <td></td>
    <td>2453</td>
    <td>АП 2453</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>11.2004</td>
    <td></td>
    <td>2455-&gt;2301-&gt;2001</td>
    <td>АП 2455</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>2003</td>
    <td></td>
    <td>2467</td>
    <td>АП 2467</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>2003</td>
    <td></td>
    <td>2468-&gt;2107-&gt;2307-&gt;2007</td>
    <td>АП 2468</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>2003</td>
    <td></td>
    <td>2469</td>
    <td>АП 2469</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>09.2009</td>
    <td>280.04.1984.87</td>
    <td>-&gt;2473-&gt;2124-&gt;3412-&gt;3312-&gt;3812-&gt;3454</td>
    <td>СА 1083 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>03.05.2015</td>
    <td>280.04.1993.87</td>
    <td>2474-&gt;2125-&gt;2101-&gt;2201-&gt;2301</td>
    <td>СА 0946 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>16.06.2015</td>
    <td>280.04.3591.87</td>
    <td>2475-&gt;2126-&gt;2326-&gt;2026-&gt;2245</td>
    <td>СА 9952 ВХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>2003</td>
    <td></td>
    <td>2476-&gt;2261-&gt;2426</td>
    <td>АП 2476</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>17.08.2005</td>
    <td></td>
    <td>2477-&gt;2314</td>
    <td>АП 2477</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>01.2004</td>
    <td></td>
    <td>2478-&gt;2127-&gt;2227-&gt;2304</td>
    <td>АП 2478</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>06.1987</td>
    <td>19.03.2015</td>
    <td>280.04.4146.87</td>
    <td>2479-&gt;2271-&gt;2427-&gt;2027-&gt;2246</td>
    <td>СА 0926 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>16.06.2015</td>
    <td></td>
    <td>2480-&gt;2128-&gt;2328</td>
    <td>СА 0922 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>2003</td>
    <td></td>
    <td>2481-&gt;4208-&gt;2260</td>
    <td>АП 2481</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>17.08.2005</td>
    <td></td>
    <td>2482-&gt;2129-&gt;2329</td>
    <td>АП 2482</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>14.01.2002</td>
    <td></td>
    <td>2483-&gt;1299-&gt;1219</td>
    <td>С 2010 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>09.2013</td>
    <td>280.04.4131.87</td>
    <td>2484</td>
    <td>СА 0794 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>17.04.2015</td>
    <td>280.04.4195.87</td>
    <td>2485</td>
    <td>СА 1150 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>16.06.2015</td>
    <td>280.04.4124.87</td>
    <td>2486-&gt;2272-&gt;2428</td>
    <td>СА 1485 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>10.1987</td>
    <td>19.09.2014</td>
    <td>280.04.4121.87</td>
    <td>2487-&gt;2135-&gt;2414</td>
    <td>СА 1941 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>2000</td>
    <td></td>
    <td>2490</td>
    <td>С 2746 НН</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>09.2002</td>
    <td></td>
    <td>2491-&gt;2317</td>
    <td>АП 2491</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>20.05.2015</td>
    <td>280.04.3576.87</td>
    <td>2492</td>
    <td>СА 0941 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>09.2002</td>
    <td></td>
    <td>2493</td>
    <td>АП 2493</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>06.2011</td>
    <td>280.04.3555.87</td>
    <td>2494</td>
    <td>СА 0806 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>09.1987</td>
    <td>17.08.2005</td>
    <td></td>
    <td>2495-&gt;2318</td>
    <td>АП 2495</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2000</td>
    <td></td>
    <td>2600-&gt;2174-&gt;2125</td>
    <td>АП 2600</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>1997</td>
    <td></td>
    <td>2602-&gt;2109</td>
    <td>АП 2602</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>10.01.1997</td>
    <td></td>
    <td>2603-&gt;2120</td>
    <td>АП 2603</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>09.2009</td>
    <td>280.04.2007.87</td>
    <td>2615-&gt;2184-&gt;2109-&gt;2209-&gt;2303</td>
    <td>СА 1481 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>19.06.2015</td>
    <td>280.04.1994.87</td>
    <td>2616-&gt;2146-&gt;2419</td>
    <td>СА 0790 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>14.01.2002</td>
    <td></td>
    <td>2617-&gt;2147-&gt;2122-&gt;609</td>
    <td>АП 2617</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1987</td>
    <td>11.1987</td>
    <td>2003</td>
    <td></td>
    <td>2619-&gt;2119-&gt;2403</td>
    <td>АП 2619</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1986</td>
    <td>1991</td>
    <td>05.2010</td>
    <td></td>
    <td>2956-&gt;3856-&gt;3970-&gt;4466-&gt;1047</td>
    <td>СА 1101 МВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O402</td>
    <td>1986</td>
    <td></td>
    <td></td>
    <td>WDB69705611950081</td>
    <td>5030</td>
    <td>СО 1704 ХА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405 Hispano</td>
    <td>1986</td>
    <td>2004</td>
    <td>23.10.2007</td>
    <td>WDB35700111050194</td>
    <td>019-&gt;8019-&gt;8005</td>
    <td>РВ 3810 ХН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405 Hispano</td>
    <td>1986</td>
    <td>2004</td>
    <td>23.10.2007</td>
    <td>WDB35700111049384</td>
    <td>021-&gt;8021-&gt;8007</td>
    <td> РВ 1623 ХМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O405 Hispano</td>
    <td>1986</td>
    <td>2004</td>
    <td>23.10.2007</td>
    <td>WDB35700111050193</td>
    <td>022-&gt;8022</td>
    <td>РВ 1609 ХМ</td>
  </tr>
  <tr>
    <td>Volvo B10M / Wiima K202</td>
    <td>1985</td>
    <td>05.2007</td>
    <td>23.10.2007</td>
    <td>YV31MEC14FA010769</td>
    <td>8008</td>
    <td>РВ 5244 КК</td>
  </tr>
  <tr>
    <td>Volvo B10M / Wiima K202</td>
    <td>1986</td>
    <td>05.2007</td>
    <td>23.10.2007</td>
    <td>YV31MGC17GA013002</td>
    <td>8009</td>
    <td>РВ 5243 КК</td>
  </tr>
  <tr>
    <td>Volvo B10M / Wiima K202</td>
    <td>1986</td>
    <td>05.2007</td>
    <td>23.10.2007</td>
    <td>YV31MGC13GA012977</td>
    <td>8010</td>
    <td>РB 5260 KK</td>
  </tr>
  <tr>
    <td>Volvo B10M / Wiima K202</td>
    <td>1986</td>
    <td>05.2007</td>
    <td>23.10.2007</td>
    <td>YV31MGC1XGA012989</td>
    <td>8011</td>
    <td>РВ 5249 КК</td>
  </tr>
  <tr>
    <td>Volvo B10M / Wiima K202</td>
    <td>1986</td>
    <td>05.2007</td>
    <td>23.10.2007</td>
    <td></td>
    <td>8012</td>
    <td>РВ 5246 КК</td>
  </tr>
  <tr>
    <td>Volvo B10M / Wiima K202</td>
    <td>1986</td>
    <td>05.2007</td>
    <td>23.10.2007</td>
    <td>YV31MGC18GA012974</td>
    <td>8013</td>
    <td>РВ 5247 КК</td>
  </tr>
  <tr>
    <td>Volvo B10M / Wiima K202</td>
    <td>1986</td>
    <td>05.2007</td>
    <td>23.10.2007</td>
    <td>YV31MGC1XGA012975</td>
    <td>8014</td>
    <td>PB 5250 KK</td>
  </tr>
  <tr>
    <td>Volvo B10M / Wiima K202</td>
    <td>1986</td>
    <td>05.2007</td>
    <td>23.10.2007</td>
    <td>YV31MGC18GA012988</td>
    <td>8015-&gt;3289</td>
    <td>РА 3289 ВА</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>1997</td>
    <td></td>
    <td>0691-&gt;3700-&gt;3902</td>
    <td>СТГ 0691</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>12.01.2001</td>
    <td></td>
    <td>0692-&gt;3701-&gt;3903-&gt;3710-&gt;3945</td>
    <td>СТГ 0692</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>12.01.2001</td>
    <td></td>
    <td>0693-&gt;3947</td>
    <td>СТГ 0693</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>12.01.2001</td>
    <td></td>
    <td>0694-&gt;3802-&gt;3954</td>
    <td>СТГ 0694</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>18.02.1998</td>
    <td></td>
    <td>0695-&gt;3948-&gt;А-3011</td>
    <td>СТГ 0695</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>1996</td>
    <td></td>
    <td>0697-&gt;3949</td>
    <td>СТГ 0697</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>1996</td>
    <td></td>
    <td>0698-&gt;3904</td>
    <td>СТГ 0698</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>29.06.2011</td>
    <td></td>
    <td>0701-&gt;3950-&gt;3713-&gt;3933-&gt;А-3001</td>
    <td>С 5389 НР</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>13.01.2003</td>
    <td></td>
    <td>1519-&gt;3845-&gt;3978</td>
    <td>СТГ 1519</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>13.01.2003</td>
    <td></td>
    <td>1520-&gt;3846-&gt;3979</td>
    <td>СТГ 1520</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>1995</td>
    <td></td>
    <td>2818</td>
    <td>СТГ 0608</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>1995</td>
    <td></td>
    <td>2667</td>
    <td>СТГ 0703</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>2013</td>
    <td></td>
    <td>2911-&gt;2774-&gt;А-15</td>
    <td>СА 7875 АС</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>1996</td>
    <td></td>
    <td>2823</td>
    <td>СТГ 0721</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>04.2004</td>
    <td></td>
    <td>943</td>
    <td>СТГ 1054</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>1999</td>
    <td></td>
    <td>893</td>
    <td>СТГ 1055</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>04.2004</td>
    <td></td>
    <td>1861-&gt;913-&gt;861</td>
    <td>СТГ 1058</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>2004</td>
    <td></td>
    <td>941</td>
    <td>СТГ 1059</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>04.2004</td>
    <td></td>
    <td>1843-&gt;843</td>
    <td>СТГ 1060</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>25.07.2001</td>
    <td></td>
    <td>921</td>
    <td>С 4080 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>10.2000</td>
    <td></td>
    <td>109-&gt;993</td>
    <td>СТГ 1062</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>2004</td>
    <td></td>
    <td>955</td>
    <td>СТГ 1063</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>25.07.2001</td>
    <td></td>
    <td>837</td>
    <td>СТГ 1503</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>1999</td>
    <td></td>
    <td>93</td>
    <td>СТГ 1504</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>1999</td>
    <td></td>
    <td>91</td>
    <td>СТГ 1506</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>06.2008</td>
    <td></td>
    <td>833-&gt;101-&gt;95</td>
    <td>С 3850 РМ</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>2004</td>
    <td></td>
    <td>841</td>
    <td>СТГ 1508</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>2004</td>
    <td></td>
    <td>869</td>
    <td>СТГ 1509</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>2000</td>
    <td></td>
    <td>845</td>
    <td>СТГ 1510</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>1999</td>
    <td></td>
    <td>889</td>
    <td>СТГ 1560</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1986</td>
    <td>10.1986</td>
    <td>09.07.2001</td>
    <td></td>
    <td>1917-&gt;У-16-&gt;4471-&gt;1471</td>
    <td>СТГ 1910</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1986</td>
    <td>1986</td>
    <td>2006</td>
    <td></td>
    <td>2650-&gt;2750-&gt;3965-&gt;3995-&gt;1069</td>
    <td>АП 2650</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1986</td>
    <td>1991</td>
    <td>05.2010</td>
    <td></td>
    <td>2955-&gt;3855-&gt;4446-&gt;1027</td>
    <td>С 7153 ВР</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>07.1985</td>
    <td>1991</td>
    <td>05.2010</td>
    <td>8970785</td>
    <td>2962-&gt;3857-&gt;3971-&gt;4462-&gt;1041</td>
    <td>СА 1189 АН</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>14.02.2000</td>
    <td></td>
    <td>1075-&gt;3308-&gt;3808</td>
    <td>СТГ 1075</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>04.1997</td>
    <td></td>
    <td>1079-&gt;3439</td>
    <td>СТГ 1079</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>11.2013</td>
    <td></td>
    <td>1089-&gt;3309-&gt;3625-&gt;3826-&gt;3886</td>
    <td>СА 1438 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>02.2009</td>
    <td></td>
    <td>1090-&gt;3440-&gt;3340-&gt;3435-&gt;3365</td>
    <td>СА 1596 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>15.06.2005</td>
    <td></td>
    <td>1091-&gt;3441-&gt;3341</td>
    <td>СТГ 1091</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>05.2002</td>
    <td></td>
    <td>1093-&gt;3108-&gt;3441</td>
    <td>СТГ 1093</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>10.05.1999</td>
    <td></td>
    <td>1102-&gt;3442-&gt;3342-&gt;3842</td>
    <td>СТГ 1102</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>10.05.1999</td>
    <td></td>
    <td>1103-&gt;3391</td>
    <td>СТГ 1103</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>10.05.1999</td>
    <td></td>
    <td>1104-&gt;3152</td>
    <td>СТГ 1104</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>14.02.2000</td>
    <td></td>
    <td>1105-&gt;3310-&gt;3810</td>
    <td>СТГ 1105</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>1999</td>
    <td></td>
    <td>775-&gt;1347-&gt;1211</td>
    <td>АМ 5381</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>2004</td>
    <td></td>
    <td>645-&gt;1847</td>
    <td>С 0100 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>01.2004</td>
    <td></td>
    <td>1407-&gt;4155-&gt;2212</td>
    <td>СТГ 1161</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>01.2004</td>
    <td></td>
    <td>1405-&gt;4151-&gt;2232</td>
    <td>СТГ 1162</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>31.08.2005</td>
    <td></td>
    <td>547-&gt;4253-&gt;2263</td>
    <td>СТГ 1163</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>2003</td>
    <td></td>
    <td>1441-&gt;4261-&gt;2230</td>
    <td>СТГ 1164</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>17.08.2005</td>
    <td></td>
    <td>1455-&gt;4167-&gt;2214</td>
    <td>СТГ 1165</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>1998</td>
    <td></td>
    <td>737</td>
    <td>СТГ 1167</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>1998</td>
    <td></td>
    <td>731</td>
    <td>СТГ 1168</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1986</td>
    <td>11.1986</td>
    <td>2004</td>
    <td></td>
    <td>1725-&gt;У-20-&gt;603</td>
    <td>СТГ 1371</td>
  </tr>
  <tr>
    <td>MAN 895 NL202</td>
    <td>1986</td>
    <td>2004</td>
    <td>06.2006</td>
    <td></td>
    <td>6023</td>
    <td>С 9855 НХ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>29.04.1999</td>
    <td></td>
    <td>3297-&gt;3803-&gt;3900</td>
    <td>АМ 3297</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>1996</td>
    <td></td>
    <td>3298-&gt;3828</td>
    <td>АМ 3298</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1985</td>
    <td>1991</td>
    <td>08.2010</td>
    <td></td>
    <td>2733-&gt;4444-&gt;1025</td>
    <td>С 7047 КМ</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1985</td>
    <td>1985</td>
    <td>30.04.2003</td>
    <td></td>
    <td>2742-&gt;4478</td>
    <td>АП 2742</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1985</td>
    <td>1985</td>
    <td>2005</td>
    <td></td>
    <td>2743-&gt;3991-&gt;811</td>
    <td>АП 2743</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1985</td>
    <td>1985</td>
    <td>2005</td>
    <td></td>
    <td>2744-&gt;3993-&gt;1067</td>
    <td>АП 2744</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>12.1984</td>
    <td>1985</td>
    <td>05.2010</td>
    <td>6711284</td>
    <td>3477-&gt;3853-&gt;3968-&gt;4458-&gt;1039</td>
    <td>СА 2174 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1985</td>
    <td>11.2000</td>
    <td>06.2014</td>
    <td>30710013046127</td>
    <td>359</td>
    <td>C 6904 КP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1985</td>
    <td>11.2000</td>
    <td>06.2014</td>
    <td>30710013046095</td>
    <td>365</td>
    <td>C 0035 КT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1985</td>
    <td>11.2000</td>
    <td>04.2017</td>
    <td>30710013045867</td>
    <td>357</td>
    <td>СВ 1428 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1985</td>
    <td>03.2001</td>
    <td>06.2014</td>
    <td>30710013045830</td>
    <td>375</td>
    <td>C 8314 PX</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>1990</td>
    <td></td>
    <td>3484</td>
    <td>АМ 3484</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>1990</td>
    <td></td>
    <td>3485</td>
    <td>АМ 3485</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>29.04.1999</td>
    <td></td>
    <td>3486-&gt;3811-&gt;3904</td>
    <td>АМ 3486</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>1996</td>
    <td></td>
    <td>3487-&gt;3911</td>
    <td>АМ 3487</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1985</td>
    <td>1985</td>
    <td>13.01.2003</td>
    <td></td>
    <td>3488-&gt;3847-&gt;3980</td>
    <td>АМ 3488</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1985</td>
    <td>1985</td>
    <td>13.01.2003</td>
    <td></td>
    <td>3489-&gt;3848-&gt;3754-&gt;3849-&gt;3981</td>
    <td>АМ 3489</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2780</td>
    <td>АП 2780</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2781</td>
    <td>АП 2781</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2782</td>
    <td>АП 2782</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2783</td>
    <td>АП 2783</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2784</td>
    <td>АП 2784</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2785</td>
    <td>АП 2785</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2786</td>
    <td>АП 2786</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2787</td>
    <td>АП 2787</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2788</td>
    <td>АП 2788</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2789</td>
    <td>АП 2789</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2790</td>
    <td>АП 2790</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2791</td>
    <td>АП 2791</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2792</td>
    <td>АП 2792</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2793</td>
    <td>АП 2793</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2794</td>
    <td>АП 2794</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2795</td>
    <td>АП 2795</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2796</td>
    <td>АП 2796</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2797</td>
    <td>АП 2797</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2798</td>
    <td>АП 2798</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2799</td>
    <td>АП 2799</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2870</td>
    <td>АП 2870</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2871</td>
    <td>АП 2871</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2872</td>
    <td>АП 2872</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2873</td>
    <td>АП 2873</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2874</td>
    <td>АП 2874</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>11.2017</td>
    <td></td>
    <td>2875-&gt;А-11</td>
    <td>СА 7831 АС</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2876</td>
    <td>АП 2876</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>06.08.2001</td>
    <td></td>
    <td>2877</td>
    <td>АП 2877</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2878</td>
    <td>АП 2878</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>07.09.2000</td>
    <td></td>
    <td>2879-&gt;3843-&gt;3915</td>
    <td>АП 2879</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2880-&gt;2794</td>
    <td>АП 2880</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2940</td>
    <td>АП 2940</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2941</td>
    <td>АП 2941</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2942</td>
    <td>АП 2942</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2943</td>
    <td>АП 2943</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2944</td>
    <td>АП 2944</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2945</td>
    <td>АП 2945</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2946</td>
    <td>АП 2946</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2947</td>
    <td>АП 2947</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>2948</td>
    <td>АП 2948</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>1999</td>
    <td></td>
    <td>2949-&gt;2784</td>
    <td>АП 2949</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>1996</td>
    <td></td>
    <td>305-&gt;4625</td>
    <td>АП 9130</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>09.2002</td>
    <td></td>
    <td>307-&gt;4607-&gt;2813</td>
    <td>АП 9149</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>01.07.2001</td>
    <td></td>
    <td>327-&gt;4411</td>
    <td>С 8858 НН</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>1990</td>
    <td></td>
    <td>1923</td>
    <td>АП 9152</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>06.2014</td>
    <td></td>
    <td>329-&gt;А-1919-&gt;А-1997</td>
    <td>СА 3324 АН</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>1998</td>
    <td></td>
    <td>165-&gt;А-999</td>
    <td>АП 9154</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>1998</td>
    <td></td>
    <td>235-&gt;А-1991</td>
    <td>АП 9155</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>1997</td>
    <td></td>
    <td>321-&gt;4611</td>
    <td>С 3565 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>1998</td>
    <td></td>
    <td>263</td>
    <td>АП 9157</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>1997</td>
    <td></td>
    <td>311</td>
    <td>АП 9158</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>1997</td>
    <td></td>
    <td>309-&gt;4609</td>
    <td>АП 9159</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>11.1985</td>
    <td>06.2008</td>
    <td></td>
    <td>191-&gt;97</td>
    <td>С 8929 РС</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1985</td>
    <td>11.1985</td>
    <td>25.07.2001</td>
    <td></td>
    <td>971</td>
    <td>АМ 6785</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1985</td>
    <td>11.1985</td>
    <td>25.07.2001</td>
    <td></td>
    <td>957</td>
    <td>АМ 6791</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1985</td>
    <td>11.1985</td>
    <td>25.07.2001</td>
    <td></td>
    <td>835-&gt;89</td>
    <td>АМ 6793</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1985</td>
    <td>11.1985</td>
    <td>25.07.2001</td>
    <td></td>
    <td>887</td>
    <td>С 8612 ТМ</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1985</td>
    <td>11.1985</td>
    <td>2004</td>
    <td></td>
    <td>909</td>
    <td>С 1032 НВ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>11.1985</td>
    <td>25.07.2001</td>
    <td></td>
    <td>115</td>
    <td>АМ 6847</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1985</td>
    <td>11.1985</td>
    <td>06.2008</td>
    <td></td>
    <td>71-&gt;91</td>
    <td>С 6324 КС</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>11.1985</td>
    <td>07.2008</td>
    <td></td>
    <td>1913-&gt;У-10-&gt;4475-&gt;1475</td>
    <td>С 1988 РС</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>11.1985</td>
    <td>1999</td>
    <td></td>
    <td>57</td>
    <td>АМ 6796</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>09.2002</td>
    <td></td>
    <td>-&gt;1915-&gt;У-14-&gt;4477-&gt;4491-&gt;4477-&gt;1477</td>
    <td>АМ 6982</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>05.2008</td>
    <td></td>
    <td>365-&gt;4425-&gt;1425</td>
    <td>С 1163 НА</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>09.2002</td>
    <td></td>
    <td>351-&gt;4637-&gt;2820</td>
    <td>АП 5532</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>01.08.2007</td>
    <td></td>
    <td>157-&gt;4639-&gt;А-13</td>
    <td>СА 7830 АС</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1985</td>
    <td>1985</td>
    <td>1999</td>
    <td></td>
    <td>159</td>
    <td>С 3784 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1985</td>
    <td>03.2001</td>
    <td>31.08.2018</td>
    <td>30710013045772</td>
    <td>373-&gt;1373</td>
    <td>С 8315 РХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1985</td>
    <td>03.2001</td>
    <td>06.2014</td>
    <td>30710013045675</td>
    <td>377</td>
    <td>C 8335 PX</td>
  </tr>
  <tr>
    <td>Ikarus 250.67</td>
    <td>1985</td>
    <td>1986</td>
    <td>2003</td>
    <td></td>
    <td>2211</td>
    <td>АП 9651</td>
  </tr>
  <tr>
    <td>Ikarus 280.33</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>07.1997</td>
    <td></td>
    <td>3277-&gt;3450</td>
    <td>АМ 3277</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>18.02.1998</td>
    <td></td>
    <td>3280-&gt;3210</td>
    <td>АМ 3280</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>01.2006</td>
    <td></td>
    <td>3281-&gt;3254-&gt;3545-&gt;3821-&gt;3885</td>
    <td>АМ 3281</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3282-&gt;3255-&gt;3546-&gt;3822</td>
    <td>АМ 3282</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>14.02.2000</td>
    <td></td>
    <td>3283-&gt;3256-&gt;3547-&gt;3823</td>
    <td>АМ 3283</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>02.1999</td>
    <td></td>
    <td>3284-&gt;3257-&gt;3548</td>
    <td>АМ 3284</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>06.08.2001</td>
    <td></td>
    <td>3285-&gt;3258-&gt;3549-&gt;3836-&gt;3414</td>
    <td>АМ 3285</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>07.2008</td>
    <td></td>
    <td>3286-&gt;3211-&gt;1275</td>
    <td>СА 2313 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3287-&gt;3212</td>
    <td>АМ 3287</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3288-&gt;3213</td>
    <td>АМ 3288</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3289-&gt;3214</td>
    <td>АМ 3289</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>05.2004</td>
    <td></td>
    <td>3290-&gt;3117-&gt;3416</td>
    <td>АМ 3290</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3291-&gt;3157-&gt;3802</td>
    <td>АМ 3291</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1987</td>
    <td></td>
    <td>3292</td>
    <td>АМ 3292</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2009</td>
    <td></td>
    <td>3293-&gt;3451-&gt;3351-&gt;3412</td>
    <td>СА 1439 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1994</td>
    <td></td>
    <td>3294-&gt;3401</td>
    <td>АМ 3294</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3295-&gt;3452-&gt;3352-&gt;3852</td>
    <td>АМ 3295</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>11.2013</td>
    <td></td>
    <td>3296-&gt;3402-&gt;3381-&gt;3420-&gt;3882</td>
    <td>СА 0969 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>12.2001</td>
    <td></td>
    <td>3299-&gt;3453-&gt;3359-&gt;3438</td>
    <td>АМ 3299</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>18.02.1998</td>
    <td></td>
    <td>3406-&gt;3544-&gt;3456</td>
    <td>АМ 3406</td>
  </tr>
  <tr>
    <td>Ikarus 280.33</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3459-&gt;3630-&gt;3253-&gt;3514</td>
    <td>АМ 3459</td>
  </tr>
  <tr>
    <td>Ikarus 280.33</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>07.1997</td>
    <td></td>
    <td>3460-&gt;3673</td>
    <td>АМ 3460</td>
  </tr>
  <tr>
    <td>Ikarus 280.33</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>06.08.2001</td>
    <td></td>
    <td>3461-&gt;3545-&gt;3216-&gt;3430</td>
    <td>АМ 3461</td>
  </tr>
  <tr>
    <td>Ikarus 280.33</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>1998</td>
    <td></td>
    <td>3462-&gt;3674-&gt;3257</td>
    <td>АМ 3462</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>09.11.2005</td>
    <td></td>
    <td>3464-&gt;3546-&gt;3406-&gt;3265-&gt;3121</td>
    <td>АМ 3464</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>19.08.2005</td>
    <td></td>
    <td>3465-&gt;3547-&gt;3455-&gt;3355-&gt;3437</td>
    <td>АМ 3465</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>01.2004</td>
    <td></td>
    <td>3466-&gt;3675-&gt;4279-&gt;2257</td>
    <td>АМ 3466</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3467-&gt;3548-&gt;3681</td>
    <td>АМ 3467</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3468-&gt;3631-&gt;3331-&gt;3831</td>
    <td>АМ 3468</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1988</td>
    <td></td>
    <td>3469</td>
    <td>АМ 3469</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1997</td>
    <td></td>
    <td>3470-&gt;3632-&gt;3332-&gt;3832</td>
    <td>АМ 3470</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3471-&gt;3549-&gt;3639-&gt;3839</td>
    <td>АМ 3471</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>21.10.2005</td>
    <td></td>
    <td>3472-&gt;3550-&gt;3682-&gt;4281-&gt;2226</td>
    <td>АМ 3472</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>14.02.2000</td>
    <td></td>
    <td>3473-&gt;3551-&gt;3683</td>
    <td>АМ 3473</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>02.01.2002</td>
    <td></td>
    <td>3474-&gt;3633-&gt;3295-&gt;3428</td>
    <td>АМ 3474</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3475-&gt;3676</td>
    <td>АМ 3475</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>06.08.2001</td>
    <td></td>
    <td>3476-&gt;3123-&gt;3442</td>
    <td>АМ 3476</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3478-&gt;3634-&gt;3241-&gt;3843</td>
    <td>АМ 3478</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1998</td>
    <td></td>
    <td>3479-&gt;3677-&gt;655-&gt;1355</td>
    <td>АМ 3479</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3480-&gt;3552-&gt;3454-&gt;3354-&gt;3854</td>
    <td>АМ 3480</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3481-&gt;3553-&gt;3328-&gt;3829</td>
    <td>АМ 3481</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3482-&gt;3554-&gt;3640</td>
    <td>АМ 3482</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>19.08.2005</td>
    <td></td>
    <td>3483-&gt;3124-&gt;3443</td>
    <td>АМ 3483</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>14.01.2002</td>
    <td></td>
    <td>2101-&gt;4317-&gt;1831</td>
    <td>С 2925 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>09.2002</td>
    <td></td>
    <td>2103-&gt;2203-&gt;2302</td>
    <td>АП 2103</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>01.2004</td>
    <td></td>
    <td>2105-&gt;4339-&gt;2251</td>
    <td>С 2922 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>02.2002</td>
    <td></td>
    <td>2108-&gt;2310-&gt;2010</td>
    <td>АП 2108</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>06.2004</td>
    <td></td>
    <td>2122-&gt;1381</td>
    <td>С 7244 ВВ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>05.1999</td>
    <td></td>
    <td>2130-&gt;4227</td>
    <td>АП 2130</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2002</td>
    <td></td>
    <td>2134-&gt;2012-&gt;2412</td>
    <td>АП 2134</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>04.2011</td>
    <td></td>
    <td>2136-&gt;2102</td>
    <td>СА 0810 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2003</td>
    <td></td>
    <td>2138-&gt;2238-&gt;2305</td>
    <td>АП 2138</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2144-&gt;2416</td>
    <td>АП 2144</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>11.2011</td>
    <td></td>
    <td>2151-&gt;2051-&gt;3894</td>
    <td>СА 0979 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2000</td>
    <td></td>
    <td>2153-&gt;2252</td>
    <td>АП 2153</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2000</td>
    <td></td>
    <td>2154-&gt;2254</td>
    <td>АП 2154</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2000</td>
    <td></td>
    <td>2156-&gt;2256</td>
    <td>АП 2156</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2160</td>
    <td>АП 2160</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2165-&gt;2108</td>
    <td>АП 2165</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>11.2011</td>
    <td></td>
    <td>2213-&gt;2149-&gt;2348-&gt;3893</td>
    <td>СА 1275 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2231-&gt;2435</td>
    <td>АП 2231</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2000</td>
    <td></td>
    <td>2233-&gt;2158-&gt;2104</td>
    <td>АП 2233</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>11.2001</td>
    <td></td>
    <td>2234-&gt;2159-&gt;2259-&gt;3892</td>
    <td>СА 1521 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2004</td>
    <td></td>
    <td>2235-&gt;2402-&gt;601</td>
    <td>С 9586 РТ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>11.2013</td>
    <td>280.04.747.85</td>
    <td>-&gt;2236-&gt;2190-&gt;3414-&gt;3510-&gt;3819-&gt;3880</td>
    <td>СА 1512 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2000</td>
    <td></td>
    <td>2237-&gt;2168-&gt;2383-&gt;2083</td>
    <td>АП 2237</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2000</td>
    <td></td>
    <td>2238-&gt;2148-&gt;2103</td>
    <td>АП 2238</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>08.2009</td>
    <td>280.04.743.85</td>
    <td>2239-&gt;2187-&gt;2287-&gt;2309</td>
    <td>СА 0942 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>04.2004</td>
    <td></td>
    <td>2240-&gt;2447-&gt;2047</td>
    <td>АП 2240</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>06.08.2001</td>
    <td></td>
    <td>2241-&gt;2161-&gt;2105-&gt;1349</td>
    <td>АП 2241</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>06.05.2015</td>
    <td></td>
    <td>2244-&gt;2418</td>
    <td>СА 0940 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2003</td>
    <td></td>
    <td>2245-&gt;2405</td>
    <td>АП 2245</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2003</td>
    <td></td>
    <td>2247-&gt;2421-&gt;2313</td>
    <td>С 7428 РС</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2248</td>
    <td>АП 2248</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>03.2005</td>
    <td></td>
    <td>2249-&gt;2406-&gt;2101</td>
    <td>АП 2249</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>2003</td>
    <td></td>
    <td>2282-&gt;2429</td>
    <td>АП 2282</td>
  </tr>
  <tr>
    <td>Ikarus 280.33</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>2003</td>
    <td></td>
    <td>2292-&gt;2182-&gt;4185-&gt;2219</td>
    <td>С 2923 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.33</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>04.2006</td>
    <td></td>
    <td>2293-&gt;2163-&gt;2106-&gt;3890</td>
    <td>СА 1528 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.33</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>1999</td>
    <td></td>
    <td>2294-&gt;2344-&gt;2044</td>
    <td>АП 2294</td>
  </tr>
  <tr>
    <td>Ikarus 280.33</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>1999</td>
    <td></td>
    <td>2295-&gt;2411-&gt;4271</td>
    <td>С 2924 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.33</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>14.11.2014</td>
    <td></td>
    <td>2296-&gt;2169-&gt;2399-&gt;2099-&gt;2250</td>
    <td>СА 9961 ВХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>1997</td>
    <td></td>
    <td>2297-&gt;2412</td>
    <td>АП 2297</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>16.06.2015</td>
    <td></td>
    <td>2298-&gt;2430-&gt;2330</td>
    <td>СА 0382 СТ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>1997</td>
    <td></td>
    <td>2299-&gt;2436</td>
    <td>АП 2299</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1997</td>
    <td></td>
    <td>2314</td>
    <td>АП 2314</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2335-&gt;2035</td>
    <td>С 2115 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2337-&gt;2037</td>
    <td>С 2133 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2340-&gt;2040</td>
    <td>АП 2340</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1997</td>
    <td></td>
    <td>2341</td>
    <td>АП 2341</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2342-&gt;2042</td>
    <td>С 2437 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2348-&gt;2048</td>
    <td>С 2078 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2349-&gt;2049</td>
    <td>АП 2349</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2350-&gt;2050</td>
    <td>АП 2350</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2351</td>
    <td>АП 2351</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2356-&gt;2056</td>
    <td>АП 2356</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2357-&gt;2057</td>
    <td>АП 2357</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2358-&gt;2458</td>
    <td>С 2084 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2359-&gt;2059</td>
    <td>АП 2359</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>14.01.2002</td>
    <td></td>
    <td>2413-&gt;4291-&gt;1873</td>
    <td>АП 2413</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1995</td>
    <td></td>
    <td>2414</td>
    <td>АП 2414</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>14.01.2002</td>
    <td></td>
    <td>2457-&gt;4202-&gt;1895</td>
    <td>АП 2457</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2458</td>
    <td>АП 2458</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2459</td>
    <td>АП 2459</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2460</td>
    <td>АП 2460</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2461</td>
    <td>АП 2461</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>14.01.2002</td>
    <td></td>
    <td>2462-&gt;4204-&gt;1871</td>
    <td>АП 2462</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2463-&gt;2106-&gt;2206</td>
    <td>АП 2463</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>08.2005</td>
    <td></td>
    <td>2464-&gt;4206-&gt;2259</td>
    <td>АП 2464</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2465</td>
    <td>АП 2465</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>16.06.2015</td>
    <td></td>
    <td>2466</td>
    <td>СА 0939 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>11.2011</td>
    <td></td>
    <td>2470-&gt;3891</td>
    <td>СА 1507 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>2471</td>
    <td>АП 2471</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>01.2007</td>
    <td></td>
    <td>-&gt;2472-&gt;2123-&gt;3411-&gt;3313-&gt;3813-&gt;3883</td>
    <td>СА 1571 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>1999</td>
    <td></td>
    <td>2614-&gt;2259-&gt;2407</td>
    <td>АП 2614</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>08.1996</td>
    <td></td>
    <td>1615-&gt;1315</td>
    <td>АП 9148</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2004</td>
    <td></td>
    <td>501-&gt;4121-&gt;2207</td>
    <td>АП 9160</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2004</td>
    <td></td>
    <td>525-&gt;4327-&gt;1879</td>
    <td>АП 9161</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>01.2004</td>
    <td></td>
    <td>527-&gt;4329-&gt;2249</td>
    <td>АП 9162</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1991</td>
    <td></td>
    <td>1413-&gt;4161</td>
    <td>АП 9163</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>01.2004</td>
    <td></td>
    <td>1425-&gt;4251-&gt;2267</td>
    <td>АП 9164</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>09.1995</td>
    <td></td>
    <td>1401-&gt;4361</td>
    <td>АП 9165</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2003</td>
    <td></td>
    <td>1435-&gt;4257-&gt;2269</td>
    <td>АП 9166</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>09.2010</td>
    <td></td>
    <td>1437-&gt;4259-&gt;2231</td>
    <td>СА 0933 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>06.08.2001</td>
    <td></td>
    <td>679</td>
    <td>АП 9168</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>06.08.2001</td>
    <td></td>
    <td>757-&gt;1359-&gt;1225</td>
    <td>С 0022 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>06.08.2001</td>
    <td></td>
    <td>1629-&gt;1329</td>
    <td>С 2136 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>1669-&gt;4277</td>
    <td>АП 9171</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1998</td>
    <td></td>
    <td>1671-&gt;1215</td>
    <td>АП 9172</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>1691-&gt;1699</td>
    <td>С 0095 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>06.08.2001</td>
    <td></td>
    <td>1711-&gt;1243-&gt;1283</td>
    <td>С 5819 РТ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>1713</td>
    <td>АП 9175</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1998</td>
    <td></td>
    <td>745-&gt;1345</td>
    <td>АП 9004</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1996</td>
    <td></td>
    <td>1685-&gt;1351</td>
    <td>АП 9036</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>30.04.2005</td>
    <td></td>
    <td>733</td>
    <td>АП 9037</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>06.08.2001</td>
    <td></td>
    <td>1649-&gt;2397-&gt;1649-&gt;1371-&gt;1205</td>
    <td>С 6043 РТ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1998</td>
    <td></td>
    <td>1687-&gt;1367</td>
    <td>АП 9039</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2004</td>
    <td></td>
    <td>1277</td>
    <td>С 0591 НВ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>1715</td>
    <td>АП 9041</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2000</td>
    <td></td>
    <td>1721-&gt;1385-&gt;1355</td>
    <td>С 6858 КС</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2004</td>
    <td></td>
    <td>1723</td>
    <td>АП 9043</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2003</td>
    <td></td>
    <td>1433-&gt;4255-&gt;2250</td>
    <td>АП 9044</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>01.2004</td>
    <td></td>
    <td>1429-&gt;4249-&gt;2266</td>
    <td>АП 9045</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>01.2004</td>
    <td></td>
    <td>1415-&gt;4157-&gt;1811</td>
    <td>АП 9046</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>09.1995</td>
    <td></td>
    <td>1485-&gt;4379-&gt;4111</td>
    <td>АП 9047</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2009</td>
    <td></td>
    <td>1417-&gt;4159-&gt;1813</td>
    <td>СА 1143 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2004</td>
    <td></td>
    <td>1419-&gt;4163-&gt;1865</td>
    <td>АП 9049</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2004</td>
    <td></td>
    <td>637-&gt;1287</td>
    <td>С 1586 КХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>1999</td>
    <td></td>
    <td>727</td>
    <td>АП 9051</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>17.08.2005</td>
    <td></td>
    <td>1273-&gt;663-&gt;1323</td>
    <td>АП 9052</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2003</td>
    <td></td>
    <td>1409-&gt;4153-&gt;1863</td>
    <td>АП 9053</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>01.2004</td>
    <td></td>
    <td>1421-&gt;4247-&gt;2265</td>
    <td>АП 9054</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2003</td>
    <td></td>
    <td>1439-&gt;4355-&gt;2253</td>
    <td>АП 9055</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2003</td>
    <td></td>
    <td>1427-&gt;4357-&gt;1883</td>
    <td>АП 9056</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1985</td>
    <td>03.1986</td>
    <td>2002</td>
    <td></td>
    <td>1431-&gt;4359-&gt;1841</td>
    <td>С 3533 КХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.33</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>04.02.2002</td>
    <td></td>
    <td>1423-&gt;4323-&gt;1899</td>
    <td>АП 7121</td>
  </tr>
  <tr>
    <td>Ikarus 280.33</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>01.2004</td>
    <td></td>
    <td>507-&gt;4229-&gt;2262</td>
    <td>АП 7122</td>
  </tr>
  <tr>
    <td>Ikarus 280.33</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>06.08.2001</td>
    <td></td>
    <td>777</td>
    <td>С 8163 ТТ</td>
  </tr>
  <tr>
    <td>Ikarus 280.33</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>1999</td>
    <td></td>
    <td>511-&gt;4321</td>
    <td>АП 7124</td>
  </tr>
  <tr>
    <td>Ikarus 280.33</td>
    <td>1985</td>
    <td>12.1985</td>
    <td>1998</td>
    <td></td>
    <td>1647-&gt;1369</td>
    <td>АП 7125</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3380</td>
    <td>АМ 3380</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3381</td>
    <td>АМ 3381</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3382</td>
    <td>АМ 3382</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3383</td>
    <td>АМ 3383</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3384</td>
    <td>АМ 3384</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3385</td>
    <td>АМ 3385</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3386</td>
    <td>АМ 3386</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3387</td>
    <td>АМ 3387</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3388</td>
    <td>АМ 3388</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3389</td>
    <td>АМ 3389</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3391</td>
    <td>АМ 3391</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>06.08.2001</td>
    <td></td>
    <td>3392-&gt;3954-&gt;3839-&gt;3963</td>
    <td>АМ 3392</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>1996</td>
    <td></td>
    <td>3393-&gt;3707</td>
    <td>АМ 3393</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>1996</td>
    <td></td>
    <td>3394-&gt;3751</td>
    <td>АМ 3394</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>1996</td>
    <td></td>
    <td>3395-&gt;3708</td>
    <td>АМ 3395</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>12.01.2001</td>
    <td></td>
    <td>3396-&gt;3752-&gt;3919</td>
    <td>АМ 3396</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3397</td>
    <td>АМ 3397</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>29.06.2011</td>
    <td></td>
    <td>-&gt;3398-&gt;3834-&gt;3911-&gt;3809-&gt;3709-&gt;А 3005</td>
    <td>СА 7633 АК</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>1996</td>
    <td></td>
    <td>3401-&gt;3835</td>
    <td>АМ 3401</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3402</td>
    <td>АМ 3402</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>1996</td>
    <td></td>
    <td>3403-&gt;3836</td>
    <td>АМ 3403</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3404</td>
    <td>АМ 3404</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3405</td>
    <td>АМ 3405</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3406</td>
    <td>АМ 3406</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3407</td>
    <td>АМ 3407</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3408</td>
    <td>АМ 3408</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3409</td>
    <td>АМ 3409</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>3410</td>
    <td>АМ 3410</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>1996</td>
    <td></td>
    <td>3411-&gt;3837</td>
    <td>АМ 3411</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>1998</td>
    <td></td>
    <td>2770</td>
    <td>АП 2770</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>2771</td>
    <td>АП 2771</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>1995</td>
    <td></td>
    <td>2772-&gt;А-ТБ 22</td>
    <td>АП 2772</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>2773</td>
    <td>АП 2773</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>2774</td>
    <td>АП 2774</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>2775</td>
    <td>АП 2775</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>2776</td>
    <td>АП 2776</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>2777</td>
    <td>АП 2777</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>2778</td>
    <td>АП 2778</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>1995</td>
    <td></td>
    <td>2779-&gt;А-ТБ 24</td>
    <td>АП 2779</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>1999</td>
    <td></td>
    <td>2881-&gt;2735</td>
    <td>АП 2881</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>1995</td>
    <td></td>
    <td>2882-&gt;А-19</td>
    <td>АП 2882</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>2883</td>
    <td>АП 2883</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>2884</td>
    <td>АП 2884</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>2885</td>
    <td>АП 2885</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>2886</td>
    <td>АП 2886</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>2887</td>
    <td>АП 2887</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>2888</td>
    <td>АП 2888</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td></td>
    <td></td>
    <td>2889</td>
    <td>АП 2889</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>1999</td>
    <td></td>
    <td>185</td>
    <td>С 3776 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>1999</td>
    <td></td>
    <td>133</td>
    <td>АП 7825</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>2004</td>
    <td></td>
    <td>139</td>
    <td>АП 7826</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>25.07.2001</td>
    <td></td>
    <td>131</td>
    <td>С 9049 КТ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>1999</td>
    <td></td>
    <td>137</td>
    <td>АП 7828</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>25.07.2001</td>
    <td></td>
    <td>849-&gt;75</td>
    <td>АП 6075</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>2000</td>
    <td></td>
    <td>245</td>
    <td>АП 6076</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>2000</td>
    <td></td>
    <td>1</td>
    <td>АП 6077</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>1999</td>
    <td></td>
    <td>885-&gt;215-&gt;4633</td>
    <td>АП 6080</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>1999</td>
    <td></td>
    <td>201</td>
    <td>АП 6082</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1984</td>
    <td>1984</td>
    <td>1996</td>
    <td></td>
    <td>1885-&gt;143-&gt;4627</td>
    <td>АП 6083</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1984</td>
    <td>06.08.2000</td>
    <td>06.2014</td>
    <td>30710013042260</td>
    <td>345</td>
    <td>C 3207 КС</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>2000</td>
    <td></td>
    <td>3137-&gt;3208-&gt;4399</td>
    <td>АМ 3137</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>18.02.1998</td>
    <td></td>
    <td>3138-&gt;3541-&gt;3158</td>
    <td>АМ 3138</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>11.2013</td>
    <td></td>
    <td>3139-&gt;3542-&gt;3638-&gt;3835-&gt;3881</td>
    <td>СА 0976 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>07.1998</td>
    <td></td>
    <td>3140-&gt;3543-&gt;3159-&gt;627</td>
    <td>АМ 3140</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>18.02.1998</td>
    <td></td>
    <td>3147-&gt;3155</td>
    <td>АМ 3147</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>18.02.1998</td>
    <td></td>
    <td>3148-&gt;3156</td>
    <td>АМ 3148</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>18.02.1998</td>
    <td></td>
    <td>3150-&gt;3253-&gt;3544</td>
    <td>АМ 3150</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>18.02.1998</td>
    <td></td>
    <td>3227-&gt;3398</td>
    <td>АМ 3227</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3228-&gt;3399-&gt;3505-&gt;3837</td>
    <td>АМ 3228</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3229-&gt;3447-&gt;3347-&gt;3847</td>
    <td>АМ 3229</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>18.02.1998</td>
    <td></td>
    <td>3230-&gt;3448-&gt;3348-&gt;3512</td>
    <td>АМ 3230</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3255-&gt;3325-&gt;3825</td>
    <td>АМ 3255</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3256-&gt;3326-&gt;3826</td>
    <td>АМ 3256</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3323-&gt;3120-&gt;3840</td>
    <td>АМ 3323</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3325-&gt;3624-&gt;3824</td>
    <td>АМ 3325</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>1999</td>
    <td></td>
    <td>3390-&gt;3625-&gt;4183</td>
    <td>АМ 1837</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>1998</td>
    <td></td>
    <td>3400-&gt;3668-&gt;601-&gt;1303</td>
    <td>АМ 3400</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>01.1998</td>
    <td></td>
    <td>1611-&gt;1311</td>
    <td>С 8614 ТМ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>06.08.2001</td>
    <td></td>
    <td>1701</td>
    <td>С 8162 ТТ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>1999</td>
    <td></td>
    <td>1667-&gt;2398-&gt;1667</td>
    <td>АП 5587</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>1998</td>
    <td></td>
    <td>1645</td>
    <td>АП 5588</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>1998</td>
    <td></td>
    <td>693-&gt;1235</td>
    <td>АП 5589</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>06.08.2001</td>
    <td></td>
    <td>721-&gt;1321-&gt;1311</td>
    <td>С 2033 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>2003</td>
    <td></td>
    <td>597-&gt;4351-&gt;2223</td>
    <td>АП 5591</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>1996</td>
    <td></td>
    <td>591-&gt;4149</td>
    <td>АП 5592</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>2003</td>
    <td></td>
    <td>599-&gt;4353-&gt;1839</td>
    <td>АП 5593</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>05.1994</td>
    <td></td>
    <td>589-&gt;4145</td>
    <td>АП 5594</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>14.01.2002</td>
    <td></td>
    <td>1411-&gt;4245-&gt;4361-&gt;1885</td>
    <td>АП 5595</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>2002</td>
    <td></td>
    <td>585-&gt;4147-&gt;1861</td>
    <td>С 2917 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>06.2001</td>
    <td></td>
    <td>593-&gt;4349-&gt;4385</td>
    <td>АП 5597</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>1999</td>
    <td></td>
    <td>587-&gt;4143</td>
    <td>АП 5598</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>06.08.2001</td>
    <td></td>
    <td>1651-&gt;1659</td>
    <td>С 1407 НВ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>02.2002</td>
    <td></td>
    <td>1285</td>
    <td>С 7989 РТ</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>14.01.2002</td>
    <td></td>
    <td>1665-&gt;4387-&gt;1891</td>
    <td>АП 5601</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>06.08.2001</td>
    <td></td>
    <td>1703-&gt;1315-&gt;1383</td>
    <td>АП 2218</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>1986</td>
    <td></td>
    <td>603</td>
    <td>АП 5603</td>
  </tr>
  <tr>
    <td>Ikarus 280.43</td>
    <td>1984</td>
    <td>04.1985</td>
    <td>1997</td>
    <td></td>
    <td>1639-&gt;1339-&gt;1287</td>
    <td>АП 5604</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1983</td>
    <td>10.2005</td>
    <td>27.07.2017</td>
    <td>30710013038157</td>
    <td>2504</td>
    <td>СА 2287 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>30710013038093</td>
    <td>8059-&gt;б/н 4</td>
    <td>СВ 0566 РС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1983</td>
    <td>11.2000</td>
    <td>04.09.2016</td>
    <td>30710013035676</td>
    <td>361-&gt;1361</td>
    <td>C 0031 КT</td>
  </tr>
  <tr>
    <td>MAN SL200</td>
    <td>1983</td>
    <td>25.01.1998</td>
    <td>04.09.2016</td>
    <td>WMA2000127B001701</td>
    <td>4175-&gt;2663</td>
    <td>СА 8385 АМ	</td>
  </tr>
  <tr>
    <td>MAN SL200</td>
    <td>1983</td>
    <td>25.01.1998</td>
    <td>04.09.2016</td>
    <td>WMA2000129B001705</td>
    <td>4197-&gt;2664</td>
    <td>СА 8382 АМ</td>
  </tr>
  <tr>
    <td>MAN SL200</td>
    <td>1983</td>
    <td>25.01.1998</td>
    <td>04.09.2016</td>
    <td>WMA2000123B001699</td>
    <td>4131-&gt;2665</td>
    <td>СА 2243 АН</td>
  </tr>
  <tr>
    <td>MAN SL200</td>
    <td>1983</td>
    <td>25.01.1998</td>
    <td>04.09.2016</td>
    <td>WMA2000127B001703</td>
    <td>4179-&gt;2666</td>
    <td>СА 8377 АМ</td>
  </tr>
  <tr>
    <td>MAN SD200</td>
    <td>1983</td>
    <td>01.1998</td>
    <td>2003</td>
    <td></td>
    <td>4104-&gt;2667</td>
    <td>С 4233 ТТ</td>
  </tr>
  <tr>
    <td>MAN SD200</td>
    <td>1983</td>
    <td>01.1998</td>
    <td>31.12.2014</td>
    <td>WMA1960811B001828</td>
    <td>4106-&gt;2668-&gt;1111-&gt;007</td>
    <td>С 5134 НС</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1983</td>
    <td>1984</td>
    <td>1990</td>
    <td></td>
    <td>617</td>
    <td>АП ????</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1983</td>
    <td>1984</td>
    <td>1990</td>
    <td></td>
    <td>1463</td>
    <td>АП ????</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1983</td>
    <td>1984</td>
    <td>1990</td>
    <td></td>
    <td>1617</td>
    <td>АП ????</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1983</td>
    <td>1984</td>
    <td>1988</td>
    <td></td>
    <td>3276</td>
    <td>АМ 3276</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1983</td>
    <td>1984</td>
    <td>1988</td>
    <td></td>
    <td>3278</td>
    <td>АМ 3278</td>
  </tr>
  <tr>
    <td>Чавдар Б-1420</td>
    <td>1983</td>
    <td>1984</td>
    <td>1988</td>
    <td></td>
    <td>3463</td>
    <td>АМ 3463</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td>1996</td>
    <td></td>
    <td>3372-&gt;3831</td>
    <td>АМ 3372</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td>1996</td>
    <td></td>
    <td>3373-&gt;3832</td>
    <td>АМ 3373</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td>1996</td>
    <td></td>
    <td>3374-&gt;3952</td>
    <td>АМ 3374</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>3375</td>
    <td>АМ 3375</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>3376</td>
    <td>АМ 3376</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td>1996</td>
    <td></td>
    <td>3377-&gt;3909</td>
    <td>АМ 3377</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td>12.01.2001</td>
    <td></td>
    <td>3378-&gt;3953-&gt;3813-&gt;3958</td>
    <td>АМ 3378</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td>13.01.2003</td>
    <td></td>
    <td>3379-&gt;3833-&gt;3909-&gt;3961-&gt;2802</td>
    <td>АМ 3379</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2761</td>
    <td>АП 2761</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2762</td>
    <td>АП 2762</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2763</td>
    <td>АП 2763</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2764</td>
    <td>АП 2764</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2765</td>
    <td>АП 2765</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2766</td>
    <td>АП 2766</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2767</td>
    <td>АП 2767</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2768</td>
    <td>АП 2768</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td>1995</td>
    <td></td>
    <td>2769-&gt;2908</td>
    <td>АП 2769</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2860</td>
    <td>АП 2860</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2861</td>
    <td>АП 2861</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2862</td>
    <td>АП 2862</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2863</td>
    <td>АП 2863</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td>29.04.1999</td>
    <td></td>
    <td>2864-&gt;3803-&gt;3955</td>
    <td>АП 2864</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td>04.1999</td>
    <td></td>
    <td>2865</td>
    <td>АП 2865</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2866</td>
    <td>АП 2866</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td>1995</td>
    <td></td>
    <td>2867</td>
    <td>АП 2867</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td>1992</td>
    <td></td>
    <td>2868-&gt;А-13</td>
    <td>АП 2868</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2869</td>
    <td>АП 2869</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td>2000</td>
    <td></td>
    <td>2900-&gt;2766</td>
    <td>АП 2900</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td>1995</td>
    <td></td>
    <td>2901-&gt;А-18</td>
    <td>АП 2901</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td>2013</td>
    <td></td>
    <td>2902-&gt;А-12</td>
    <td>СА 6582 АС</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2903</td>
    <td>АП 2903</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2904</td>
    <td>АП 2904</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2905</td>
    <td>АП 2905</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2906</td>
    <td>АП 2906</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2907</td>
    <td>АП 2907</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2908</td>
    <td>АП 2908</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td>1995</td>
    <td></td>
    <td>2909-&gt;2672</td>
    <td>АП 2909</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2910</td>
    <td>АП 2910</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2911</td>
    <td>АП 2911</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2912</td>
    <td>АП 2912</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2913</td>
    <td>АП 2913</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2914</td>
    <td>АП 2914</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2915</td>
    <td>АП 2915</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2916</td>
    <td>АП 2916</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2917</td>
    <td>АП 2917</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2918</td>
    <td>АП 2918</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td>1988</td>
    <td></td>
    <td>2919</td>
    <td>АП 2919</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td>1988</td>
    <td></td>
    <td>2920</td>
    <td>АП 2920</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1983</td>
    <td>1983</td>
    <td>1990</td>
    <td></td>
    <td>1919</td>
    <td>АМ 6150</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1983</td>
    <td>11.01.1999</td>
    <td>02.08.2017</td>
    <td>30700013039757</td>
    <td>4609-&gt;2840-&gt;2848</td>
    <td>СА 8355 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1983</td>
    <td>11.01.1999</td>
    <td>13.05.2017</td>
    <td>30700013038351</td>
    <td>4645-&gt;2846</td>
    <td>СА 2268 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1983</td>
    <td>11.01.1999</td>
    <td>27.06.2017</td>
    <td>30700013038260</td>
    <td>4625-&gt;2842</td>
    <td>СА 8435 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1983</td>
    <td>20.01.1998</td>
    <td>28.10.2016</td>
    <td>30700013036234</td>
    <td>1669</td>
    <td>СА 8806 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1983</td>
    <td>20.01.1998</td>
    <td>08.12.2016</td>
    <td>30700013035557</td>
    <td>1743</td>
    <td>СА 1120 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1983</td>
    <td>19.05.1997</td>
    <td>13.09.2016</td>
    <td>30700013035528</td>
    <td>2559-&gt;3-&gt;1303</td>
    <td>СА 1167 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1983</td>
    <td>20.01.1998</td>
    <td>02.08.2017</td>
    <td>30700013035513</td>
    <td>1753</td>
    <td>СА 1172 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1983</td>
    <td>20.07.1998</td>
    <td>02.08.2017</td>
    <td>30700013035506</td>
    <td>3771-&gt;2677</td>
    <td>СА 2757 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1983</td>
    <td>19.05.1997</td>
    <td>13.09.2016</td>
    <td>30700013035498</td>
    <td>2551-&gt;3776-&gt;2837</td>
    <td>СА 6452 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1983</td>
    <td>20.01.1998</td>
    <td>06.2014</td>
    <td>30700013035483</td>
    <td>1663</td>
    <td>СА 9539 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1983</td>
    <td>11.01.1999</td>
    <td>13.09.2016</td>
    <td>30700013035457</td>
    <td>4641-&gt;2844</td>
    <td>СА 3612 АН</td>
  </tr>
  <tr>
    <td>Ikarus 280.03</td>
    <td>1983</td>
    <td>10.1992</td>
    <td>1999</td>
    <td></td>
    <td>2625-&gt;2180</td>
    <td>С 2153 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.02</td>
    <td>1983</td>
    <td>10.1992</td>
    <td>07.2004</td>
    <td></td>
    <td>2626-&gt;2166-&gt;2366-&gt;2066</td>
    <td>С 2154 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1988</td>
    <td></td>
    <td>3081</td>
    <td>АМ 3081</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>2000</td>
    <td></td>
    <td>3082-&gt;3207-&gt;4383</td>
    <td>АМ 3082</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1997</td>
    <td></td>
    <td>3083-&gt;3352</td>
    <td>АМ 3083</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1988</td>
    <td></td>
    <td>3127</td>
    <td>АМ 3127</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1988</td>
    <td></td>
    <td>3128</td>
    <td>АМ 3128</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>2003</td>
    <td></td>
    <td>3129-&gt;3252-&gt;3543-&gt;4145-&gt;1809</td>
    <td>АП 5594</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1997</td>
    <td></td>
    <td>3130-&gt;3316</td>
    <td>АМ 3130</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1997</td>
    <td></td>
    <td>3133-&gt;3114-&gt;767</td>
    <td>АМ 3133</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1997</td>
    <td></td>
    <td>3134-&gt;3115-&gt;1273</td>
    <td>АМ 3134</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>06.1998</td>
    <td></td>
    <td>3135-&gt;3116-&gt;633-&gt;1343-&gt;1279</td>
    <td>С 0121 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1989</td>
    <td></td>
    <td>3136</td>
    <td>АМ 3136</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>12.2000</td>
    <td></td>
    <td>3141-&gt;3154-&gt;629-&gt;673</td>
    <td>С 2015 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3142-&gt;3353-&gt;3982</td>
    <td>АМ 3142</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3143-&gt;3285</td>
    <td>АМ 3143</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1996</td>
    <td></td>
    <td>3201-&gt;3397</td>
    <td>АМ 3201</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1988</td>
    <td></td>
    <td>3202</td>
    <td>АМ 3202</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1997</td>
    <td></td>
    <td>3203-&gt;3286</td>
    <td>АМ 3203</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1988</td>
    <td></td>
    <td>3204</td>
    <td>АМ 3204</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>18.02.1998</td>
    <td></td>
    <td>3205-&gt;3317</td>
    <td>АМ 3205</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>18.02.1998</td>
    <td></td>
    <td>3252-&gt;3287</td>
    <td>АМ 3252</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1988</td>
    <td></td>
    <td>3253</td>
    <td>АМ 3253</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1997</td>
    <td></td>
    <td>3254-&gt;3324</td>
    <td>АМ 3254</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>07.09.2000</td>
    <td></td>
    <td>3279-&gt;3503-&gt;3864-&gt;3976</td>
    <td>АМ 3279</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>18.02.1998</td>
    <td></td>
    <td>3300-&gt;3288</td>
    <td>АМ 3300</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1996</td>
    <td></td>
    <td>3301-&gt;3504</td>
    <td>АМ 3301</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>2004</td>
    <td></td>
    <td>3324-&gt;3121-&gt;4177-&gt;2217</td>
    <td>АМ 3324</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>06.08.2001</td>
    <td></td>
    <td>3399-&gt;3122-&gt;739-&gt;1251-&gt;1267</td>
    <td>С 0502 КХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1988</td>
    <td></td>
    <td>3450</td>
    <td>АМ 3450</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1996</td>
    <td></td>
    <td>3451-&gt;3628</td>
    <td>АМ 3451</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1988</td>
    <td></td>
    <td>3452</td>
    <td>АМ 3452</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1988</td>
    <td></td>
    <td>3453</td>
    <td>АМ 3453</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1999</td>
    <td></td>
    <td>3454-&gt;3671-&gt;1289</td>
    <td>С 3184 НВ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>2002</td>
    <td></td>
    <td>3455-&gt;3629-&gt;3217-&gt;4285-&gt;2225</td>
    <td>АМ 3455</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>29.04.1999</td>
    <td></td>
    <td>3456-&gt;3672-&gt;3585-&gt;3868-&gt;3977</td>
    <td>АМ 3456</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1998</td>
    <td></td>
    <td>2334-&gt;2164-&gt;2107</td>
    <td>АП 2334</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1998</td>
    <td></td>
    <td>2601-&gt;2301-&gt;2171</td>
    <td>АП 2601</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1988</td>
    <td></td>
    <td>2604</td>
    <td>АП 2604</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1998</td>
    <td></td>
    <td>2605-&gt;2323-&gt;2023</td>
    <td>АП 2605</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1998</td>
    <td></td>
    <td>2606-&gt;2313-&gt;2013</td>
    <td>С 2382 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1998</td>
    <td></td>
    <td>2607-&gt;2121-&gt;2222</td>
    <td>АП 2607</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1997</td>
    <td></td>
    <td>2608-&gt;2258</td>
    <td>АП 2608</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1988</td>
    <td></td>
    <td>2609</td>
    <td>АП 2609</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1999</td>
    <td></td>
    <td>2610</td>
    <td>АП 2610</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1997</td>
    <td></td>
    <td>2611-&gt;2131</td>
    <td>АП 2611</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1997</td>
    <td></td>
    <td>2612-&gt;2250</td>
    <td>АП 2612</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1998</td>
    <td></td>
    <td>2613-&gt;2320-&gt;2020</td>
    <td>АП 2613</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1988</td>
    <td></td>
    <td>2644</td>
    <td>АП 2644</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1999</td>
    <td></td>
    <td>2645-&gt;2308-&gt;4216-&gt;4233</td>
    <td>АП 0512</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1988</td>
    <td></td>
    <td>2646</td>
    <td>АП 2646</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1988</td>
    <td></td>
    <td>2647</td>
    <td>АП 2647</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1988</td>
    <td></td>
    <td>2648</td>
    <td>АП 2648</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1988</td>
    <td></td>
    <td>2649</td>
    <td>АП 2649</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1996</td>
    <td></td>
    <td>569-&gt;4233</td>
    <td>АП 0512</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1998</td>
    <td></td>
    <td>1637-&gt;1337-&gt;625</td>
    <td>АП 0561</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1996</td>
    <td></td>
    <td>689</td>
    <td>АП 0562</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1999</td>
    <td></td>
    <td>691</td>
    <td>С 3183 НВ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1999</td>
    <td></td>
    <td>699</td>
    <td>АП 0564</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1997</td>
    <td></td>
    <td>793</td>
    <td>АП 0565</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1999</td>
    <td></td>
    <td>697</td>
    <td>С 9659 ТТ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>06.08.2001</td>
    <td></td>
    <td>1709-&gt;699</td>
    <td>С 3185 НВ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1998</td>
    <td></td>
    <td>705</td>
    <td>С 7255 ТТ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1996</td>
    <td></td>
    <td>755</td>
    <td>АП 0571</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1998</td>
    <td></td>
    <td>1655-&gt;4391</td>
    <td>АП 0572</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>2002</td>
    <td></td>
    <td>551-&gt;4333-&gt;1881</td>
    <td>АП 0573</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>2004</td>
    <td></td>
    <td>563-&gt;4341-&gt;1835</td>
    <td>АП 0574</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>10.2001</td>
    <td></td>
    <td>549-&gt;4139-&gt;4101-&gt;1897</td>
    <td>АП 0575</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1997</td>
    <td></td>
    <td>579-&gt;4131</td>
    <td>АП 0576</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1997</td>
    <td></td>
    <td>575-&gt;4343</td>
    <td>АП 0577</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1995</td>
    <td></td>
    <td>559-&gt;4345</td>
    <td>АП 0578</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1996</td>
    <td></td>
    <td>571-&gt;4235</td>
    <td>АП 0579</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1997</td>
    <td></td>
    <td>573-&gt;4237</td>
    <td>АП 0580</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>2004</td>
    <td></td>
    <td>561-&gt;4347-&gt;1837</td>
    <td>АП 0581</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>06.08.2001</td>
    <td></td>
    <td>1705-&gt;1239</td>
    <td>С 2778 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>12.1995</td>
    <td></td>
    <td>1205</td>
    <td>АП 0692</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>2002</td>
    <td></td>
    <td>577-&gt;4243-&gt;2264</td>
    <td>АП 0693</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1997</td>
    <td></td>
    <td>1657-&gt;2399-&gt;1657-&gt;1357</td>
    <td>АП 0694</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>06.08.2001</td>
    <td></td>
    <td>1659-&gt;1651</td>
    <td>С 3182 НВ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1998</td>
    <td></td>
    <td>1663-&gt;1317</td>
    <td>АП 0696</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>06.1998</td>
    <td></td>
    <td>1203-&gt;625-&gt;4389</td>
    <td>АП 0697</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>2002</td>
    <td></td>
    <td>583-&gt;4141-&gt;4109-&gt;1857</td>
    <td>АМ 7629</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1983</td>
    <td>08.1983</td>
    <td>1996</td>
    <td></td>
    <td>1239</td>
    <td>АП 0766</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1983</td>
    <td>19.05.1997</td>
    <td>02.08.2017</td>
    <td>30700013031581</td>
    <td>2555-&gt;3780-&gt;2838</td>
    <td>СА 1172 АН</td>
  </tr>
  <tr>
    <td>Karosa C734</td>
    <td>1982</td>
    <td>1998</td>
    <td>2000</td>
    <td></td>
    <td>4426</td>
    <td>С 1229 КР</td>
  </tr>
  <tr>
    <td>Karosa C734</td>
    <td>1982</td>
    <td>1998</td>
    <td>2000</td>
    <td></td>
    <td>4428</td>
    <td>С 1231 КР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1982</td>
    <td>11.2000</td>
    <td>10.12.2018</td>
    <td>30710013034888</td>
    <td>355-&gt;1355</td>
    <td>C 6870 КP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1982</td>
    <td>09.02.2006</td>
    <td>31.08.2018</td>
    <td>30710013034878</td>
    <td>3656-&gt;1609</td>
    <td>СА 7326 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1982</td>
    <td>06.07.2000</td>
    <td>17.03.2016</td>
    <td>30710013034506</td>
    <td>347</td>
    <td>C 5287 КС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1982</td>
    <td>06.08.2000</td>
    <td>04.2017</td>
    <td>30710013033734</td>
    <td>343-&gt;1343</td>
    <td>C 3412 КС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1982</td>
    <td>01.03.1994</td>
    <td>23.11.2005</td>
    <td>30710013032548</td>
    <td>2530-&gt;3656-&gt;3279-&gt;3656</td>
    <td>С 4109 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1982</td>
    <td>22.01.1996</td>
    <td>05.2016</td>
    <td>30710013032426</td>
    <td>1399</td>
    <td>СА 9543 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1982</td>
    <td>25.01.1996</td>
    <td>04.2015</td>
    <td>30710013032420</td>
    <td>3241-&gt;3571</td>
    <td>СА 9188 АР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1982</td>
    <td>22.01.1996</td>
    <td>06.2015</td>
    <td>30710013032389</td>
    <td>1373</td>
    <td>СА 8802 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1982</td>
    <td>09.1993</td>
    <td>05.2015</td>
    <td>30710013032367</td>
    <td>3652-&gt;1619</td>
    <td>СА 4432 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1982</td>
    <td>09.1993</td>
    <td>05.2015</td>
    <td>30710013032348</td>
    <td>3648-&gt;3241-&gt;3648-&gt;1627</td>
    <td>СА 4360 ВК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1982</td>
    <td>12.1998</td>
    <td>10.12.2018</td>
    <td>30710013032337</td>
    <td>333-&gt;1633</td>
    <td>С 4911 НМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1982</td>
    <td>09.1993</td>
    <td>05.2015</td>
    <td>30710013032294</td>
    <td>3649</td>
    <td>СА 7167 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1982</td>
    <td>08.01.1996</td>
    <td>04.2015</td>
    <td>30710013032260</td>
    <td>3654</td>
    <td>СА 3649 АХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1982</td>
    <td>26.01.1996</td>
    <td>05.2015</td>
    <td>30710013032221</td>
    <td>1375-&gt;1607-&gt;3676</td>
    <td>СА 3652 АХ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>3257</td>
    <td>АМ 3257</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>18.02.1998</td>
    <td></td>
    <td>3258-&gt;3704-&gt;3911</td>
    <td>С 2645 ТС</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>07.09.2000</td>
    <td></td>
    <td>-&gt;3259-&gt;3705-&gt;3902-&gt;3806-&gt;3706-&gt;3917</td>
    <td>АМ 3259</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>09.1996</td>
    <td></td>
    <td>3260-&gt;3706</td>
    <td>АМ 3260</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>3261</td>
    <td>АМ 3261</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>09.1996</td>
    <td></td>
    <td>3262-&gt;3807</td>
    <td>АМ 3262</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>09.1996</td>
    <td></td>
    <td>3263-&gt;3746</td>
    <td>АМ 3263</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>3264</td>
    <td>АМ 3264</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>29.01.2001</td>
    <td></td>
    <td>3265-&gt;А 3002</td>
    <td>С 3295 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>29.01.2001</td>
    <td></td>
    <td>3266-&gt;А 3003</td>
    <td>АМ 3266</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1997</td>
    <td></td>
    <td>3267-&gt;АТБ-12</td>
    <td>АМ 3267</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>09.1996</td>
    <td></td>
    <td>3268-&gt;3747</td>
    <td>АМ 3268</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>3269</td>
    <td>АМ 3269</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>3270</td>
    <td>АМ 3270</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>3271</td>
    <td>АМ 3271</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>11.1996</td>
    <td></td>
    <td>3272-&gt;3748-&gt;3955</td>
    <td>АМ 3272</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>11.1996</td>
    <td></td>
    <td>3273-&gt;3827</td>
    <td>АМ 3273</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>18.02.1998</td>
    <td></td>
    <td>3274-&gt;3749-&gt;3700-&gt;3902</td>
    <td>АМ 3274</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>3275</td>
    <td>АМ 3275</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>3361</td>
    <td>АМ 3361</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>3362</td>
    <td>АМ 3362</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>3363</td>
    <td>АМ 3363</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>3364</td>
    <td>АМ 3364</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>3365</td>
    <td>АМ 3365</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>3366</td>
    <td>АМ 3366</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>3367</td>
    <td>АМ 3367</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>3368</td>
    <td>АМ 3368</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>3369</td>
    <td>АМ 3369</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>3370</td>
    <td>АМ 3370</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>3371</td>
    <td>АМ 3371</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2690</td>
    <td>АП 2690</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2691</td>
    <td>АП 2691</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2692</td>
    <td>АП 2692</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2693</td>
    <td>АП 2693</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2694</td>
    <td>АП 2694</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2695</td>
    <td>АП 2695</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1988</td>
    <td></td>
    <td>2696-&gt;А-14</td>
    <td>АП 2696</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>03.2000</td>
    <td></td>
    <td>2697-&gt;2716</td>
    <td>АП 2697</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2698</td>
    <td>АП 2698</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2699</td>
    <td>АП 2699</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1990</td>
    <td></td>
    <td>2721-&gt;А-16</td>
    <td>АП 2721</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2722</td>
    <td>АП 2722</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2723</td>
    <td>АП 2723</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2724</td>
    <td>АП 2724</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2725</td>
    <td>АП 2725</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2726</td>
    <td>АП 2726</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2727</td>
    <td>АП 2727</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2728</td>
    <td>АП 2728</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2729</td>
    <td>АП 2729</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2730</td>
    <td>АП 2730</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2745</td>
    <td>АП 2745</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1995</td>
    <td></td>
    <td>2746-&gt;2691</td>
    <td>АП 2746</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1995</td>
    <td></td>
    <td>2747-&gt;2661</td>
    <td>АП 2747</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2748</td>
    <td>АП 2748</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>06.08.2001</td>
    <td></td>
    <td>2749</td>
    <td>АП 2749</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2750</td>
    <td>АП 2750</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2751</td>
    <td>АП 2751</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2752</td>
    <td>АП 2752</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2753</td>
    <td>АП 2753</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2754</td>
    <td>АП 2754</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2755</td>
    <td>АП 2755</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2756</td>
    <td>АП 2756</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2757</td>
    <td>АП 2757</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2758</td>
    <td>АП 2758</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2759</td>
    <td>АП 2759</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2760</td>
    <td>АП 2760</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2890</td>
    <td>АП 2890</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2891</td>
    <td>АП 2891</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2892</td>
    <td>АП 2892</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2893</td>
    <td>АП 2893</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1982</td>
    <td>1982</td>
    <td>1998</td>
    <td></td>
    <td>2894-&gt;2738</td>
    <td>АП 2894</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2895</td>
    <td>АП 2895</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1999</td>
    <td></td>
    <td>2896</td>
    <td>АП 2896</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1999</td>
    <td></td>
    <td>2897-&gt;2747</td>
    <td>АП 2897</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1999</td>
    <td></td>
    <td>2898-&gt;2748</td>
    <td>АП 2898</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>2899</td>
    <td>АП 2899</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1999</td>
    <td></td>
    <td>59</td>
    <td>АП 0301</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1999</td>
    <td></td>
    <td>79</td>
    <td>АП 0310</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1990</td>
    <td></td>
    <td>927</td>
    <td>АП 0361</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1999</td>
    <td></td>
    <td>123</td>
    <td>АП 0365</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1998</td>
    <td></td>
    <td>257</td>
    <td>АП 0366</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1999</td>
    <td></td>
    <td>125</td>
    <td>АП 0369</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1999</td>
    <td></td>
    <td>27</td>
    <td>АП 0371</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1990</td>
    <td></td>
    <td>929</td>
    <td>АП 0377</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1990</td>
    <td></td>
    <td>1921</td>
    <td>АМ 0802</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1988</td>
    <td></td>
    <td>277</td>
    <td>АП 2051</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1999</td>
    <td></td>
    <td>271</td>
    <td>АП 2052</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1999</td>
    <td></td>
    <td>289</td>
    <td>АП 2055</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1982</td>
    <td>1982</td>
    <td>1990</td>
    <td></td>
    <td>317</td>
    <td>АМ 5469</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1982</td>
    <td>20.07.1998</td>
    <td>27.05.2016</td>
    <td>30700013035450</td>
    <td>3772-&gt;2676</td>
    <td>СА 2786 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1982</td>
    <td>11.01.1999</td>
    <td>09.05.2017</td>
    <td>30700013035439</td>
    <td>4643-&gt;2845</td>
    <td>СА 2260 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1982</td>
    <td>11.01.1999</td>
    <td>27.07.2017</td>
    <td>30700013035436</td>
    <td>4647-&gt;2847</td>
    <td>СА 2273 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1982</td>
    <td>20.01.1998</td>
    <td>06.2014</td>
    <td>30700013035412</td>
    <td>1687</td>
    <td>СА 9563 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1982</td>
    <td>20.01.1998</td>
    <td>03.2016</td>
    <td>30700013035405</td>
    <td>1655</td>
    <td>СА 9547 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1982</td>
    <td>20.01.1998</td>
    <td>06.2014</td>
    <td>30700013035397</td>
    <td>1657</td>
    <td>СА 3360 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1982</td>
    <td>20.01.1998</td>
    <td>06.2014</td>
    <td>30700013035390</td>
    <td>1747</td>
    <td>СА 1192 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1982</td>
    <td>19.05.1997</td>
    <td>02.08.2017</td>
    <td>30700013035381</td>
    <td>2553-&gt;3778-&gt;2673</td>
    <td>СА 2192 АТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1982</td>
    <td>20.01.1998</td>
    <td>13.10.2016</td>
    <td>30700013035366</td>
    <td>1749</td>
    <td>СА 2173 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1982</td>
    <td>20.01.1998</td>
    <td>06.2014</td>
    <td>30700013035357</td>
    <td>1653</td>
    <td>СА 9532 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1982</td>
    <td>20.01.1998</td>
    <td>06.2014</td>
    <td>30700013035352</td>
    <td>1661</td>
    <td>СА 8809 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1982</td>
    <td>11.01.1999</td>
    <td>02.08.2017</td>
    <td>30700013035345</td>
    <td>4651-&gt;2849</td>
    <td>СА 8362 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1982</td>
    <td>11.01.1999</td>
    <td>07.2016</td>
    <td>30700013035340</td>
    <td>4627-&gt;2843</td>
    <td>СА 2275 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1982</td>
    <td>11.01.1999</td>
    <td>11.02.2017</td>
    <td>30700013035259</td>
    <td>4649-&gt;2848-&gt;2840</td>
    <td>СА 2261 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1982</td>
    <td>19.05.1997</td>
    <td>02.08.2017</td>
    <td>30700013035151</td>
    <td>2557-&gt;2781-&gt;2670</td>
    <td>СА 8353 АМ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1996</td>
    <td></td>
    <td>3114-&gt;3502</td>
    <td>АМ 3114</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1996</td>
    <td></td>
    <td>3115-&gt;3580</td>
    <td>АМ 3115</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1996</td>
    <td></td>
    <td>3116-&gt;3581</td>
    <td>АМ 3116</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1988</td>
    <td></td>
    <td>3117</td>
    <td>АМ 3117</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1988</td>
    <td></td>
    <td>3118</td>
    <td>АМ 3118</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1988</td>
    <td></td>
    <td>3119</td>
    <td>АМ 3119</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1996</td>
    <td></td>
    <td>3120-&gt;3622</td>
    <td>АМ 3120</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1997</td>
    <td></td>
    <td>3121-&gt;3248-&gt;3539-&gt;3584</td>
    <td>АМ 3121</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1996</td>
    <td></td>
    <td>3122-&gt;3249-&gt;3540</td>
    <td>АМ 3122</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>29.04.1999</td>
    <td></td>
    <td>3123-&gt;3284-&gt;3357-&gt;3974</td>
    <td>АМ 3123</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1988</td>
    <td></td>
    <td>3124</td>
    <td>АМ 3124</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1996</td>
    <td></td>
    <td>3125-&gt;3250-&gt;3541</td>
    <td>АМ 3125</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1997</td>
    <td></td>
    <td>3126-&gt;3251-&gt;3542-&gt;3359</td>
    <td>АМ 3126</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1997</td>
    <td></td>
    <td>3222-&gt;3318</td>
    <td>АМ 3222</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1987</td>
    <td></td>
    <td>3223</td>
    <td>АМ 3223</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1997</td>
    <td></td>
    <td>3224-&gt;3319</td>
    <td>АМ 3224</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1987</td>
    <td></td>
    <td>3225</td>
    <td>АМ 3225</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>02.1996</td>
    <td></td>
    <td>3226-&gt;3209</td>
    <td>АМ 3226</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>03.2000</td>
    <td></td>
    <td>3247-&gt;3321-&gt;4385</td>
    <td>АМ 5376</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1988</td>
    <td></td>
    <td>3248</td>
    <td>АМ 3248</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3249-&gt;3400-&gt;3682-&gt;3832</td>
    <td>АМ 3249</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>2003</td>
    <td></td>
    <td>3250-&gt;3322-&gt;4293-&gt;1875</td>
    <td>АМ 7633</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1997</td>
    <td></td>
    <td>3251-&gt;3323</td>
    <td>АМ 3251</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1998</td>
    <td></td>
    <td>3319-&gt;3118-&gt;4283</td>
    <td>АМ 3319</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1996</td>
    <td></td>
    <td>3320-&gt;3582</td>
    <td>АМ 3320</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1995</td>
    <td></td>
    <td>3321-&gt;3119</td>
    <td>АМ 3321</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1987</td>
    <td></td>
    <td>3322</td>
    <td>АМ 3322</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1988</td>
    <td></td>
    <td>3442</td>
    <td>АМ 3442</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1988</td>
    <td></td>
    <td>3443</td>
    <td>АМ 3443</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1988</td>
    <td></td>
    <td>3444</td>
    <td>АМ 3444</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1996</td>
    <td></td>
    <td>3445-&gt;3505</td>
    <td>АМ 3445</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1998</td>
    <td></td>
    <td>3446-&gt;3670-&gt;625-&gt;1305</td>
    <td>АМ 3446</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1996</td>
    <td></td>
    <td>3447-&gt;3627</td>
    <td>АМ 3447</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1988</td>
    <td></td>
    <td>3448</td>
    <td>АМ 3448</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1988</td>
    <td></td>
    <td>3449</td>
    <td>АМ 3449</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2168</td>
    <td>АП 2168</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1998</td>
    <td></td>
    <td>2169-&gt;2317-&gt;2017</td>
    <td>АП 2169</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2170</td>
    <td>АП 2170</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2171</td>
    <td>АП 2171</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2172</td>
    <td>АП 2172</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2174</td>
    <td>АП 2174</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1998</td>
    <td></td>
    <td>2177-&gt;4381</td>
    <td>АП 2177</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>07.2001</td>
    <td></td>
    <td>2178-&gt;4271-&gt;4402</td>
    <td>АП 2178</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1997</td>
    <td></td>
    <td>2179-&gt;4179</td>
    <td>С 2921 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2180</td>
    <td>АП 2180</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1995</td>
    <td></td>
    <td>2181</td>
    <td>АП 2181</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1995</td>
    <td></td>
    <td>2182</td>
    <td>АП 2182</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1997</td>
    <td></td>
    <td>2183-&gt;4175</td>
    <td>С 2920 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2634</td>
    <td>АП 2634</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1999</td>
    <td></td>
    <td>2635-&gt;4102</td>
    <td>АП 2635</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2636</td>
    <td>АП 2636</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2637</td>
    <td>АП 2637</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2638</td>
    <td>АП 2638</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2639</td>
    <td>АП 2639</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2640</td>
    <td>АП 2640</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1998</td>
    <td></td>
    <td>2641-&gt;2141-&gt;2241</td>
    <td>АП 2641</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td>1998</td>
    <td></td>
    <td>2642-&gt;2142-&gt;2242</td>
    <td>АП 2642</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>1983</td>
    <td></td>
    <td></td>
    <td>2643</td>
    <td>АП 2643</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>07.1983</td>
    <td>06.08.2001</td>
    <td></td>
    <td>619</td>
    <td>АМ 7540</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>07.1983</td>
    <td>1999</td>
    <td></td>
    <td>657</td>
    <td>АМ 7541</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>07.1983</td>
    <td>11.2013</td>
    <td></td>
    <td>-&gt;7542-&gt;1717-&gt;3555-&gt;3684-&gt;3828-&gt;3884</td>
    <td>СА 1347 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>07.1983</td>
    <td>2003</td>
    <td></td>
    <td>661</td>
    <td>АМ 7543</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>05.1983</td>
    <td>1996</td>
    <td></td>
    <td>539-&gt;4231</td>
    <td>АМ 7627</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>05.1983</td>
    <td>1996</td>
    <td></td>
    <td>537-&gt;4225</td>
    <td>АМ 7629</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>05.1983</td>
    <td>2003</td>
    <td></td>
    <td>533-&gt;4227-&gt;4491-&gt;1491</td>
    <td>АМ 7631</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>05.1983</td>
    <td>1995</td>
    <td></td>
    <td>543-&gt;4325</td>
    <td>АМ 7633</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>05.1983</td>
    <td>1996</td>
    <td></td>
    <td>541-&gt;4319</td>
    <td>АМ 7635</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>05.1983</td>
    <td>1997</td>
    <td></td>
    <td>535-&gt;4129</td>
    <td>АМ 7637</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>04.1983</td>
    <td>1996</td>
    <td></td>
    <td>431-&gt;4339-&gt;4275</td>
    <td>АМ 5376</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>04.1983</td>
    <td>1996</td>
    <td></td>
    <td>799</td>
    <td>АМ 5378</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>04.1983</td>
    <td>2003</td>
    <td></td>
    <td>417-&gt;4137-&gt;1859</td>
    <td>АМ 5379</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>04.1983</td>
    <td>12.1998</td>
    <td></td>
    <td>1211-&gt;1347</td>
    <td>СТГ 1159</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>04.1983</td>
    <td>1998</td>
    <td></td>
    <td>707</td>
    <td>АМ 5383</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>04.1983</td>
    <td>1998</td>
    <td></td>
    <td>421-&gt;4241</td>
    <td>АМ 5384</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>04.1983</td>
    <td>1999</td>
    <td></td>
    <td>425-&gt;4337</td>
    <td>С 0938 КХ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>04.1983</td>
    <td>1998</td>
    <td></td>
    <td>1245</td>
    <td>С 2395 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>04.1983</td>
    <td>1990</td>
    <td></td>
    <td>643</td>
    <td>АМ 5389</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>04.1983</td>
    <td>01.07.2005</td>
    <td></td>
    <td>415-&gt;4135-&gt;1807</td>
    <td>АМ 5280</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>04.1983</td>
    <td>1997</td>
    <td></td>
    <td>419-&gt;4239</td>
    <td>АМ 5281</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>04.1983</td>
    <td>1996</td>
    <td></td>
    <td>709</td>
    <td>АМ 5283</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>04.1983</td>
    <td>07.2001</td>
    <td></td>
    <td>423-&gt;4335-&gt;2234</td>
    <td>АМ 5284</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>04.1983</td>
    <td>1999</td>
    <td></td>
    <td>1209-&gt;641</td>
    <td>АМ 5285</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>04.1983</td>
    <td>1995</td>
    <td></td>
    <td>1251</td>
    <td>С 4023 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>04.1983</td>
    <td>1996</td>
    <td></td>
    <td>1704-&gt;2170-&gt;1621-&gt;1221</td>
    <td>АМ 5287</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>04.1983</td>
    <td>1999</td>
    <td></td>
    <td>647</td>
    <td>С 2397 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1982</td>
    <td>04.1983</td>
    <td>2003</td>
    <td></td>
    <td>413-&gt;4133-&gt;4319-&gt;2247</td>
    <td>АМ 5289</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1981</td>
    <td>08.2000</td>
    <td>06.2015</td>
    <td>30710013030588</td>
    <td>349</td>
    <td>C 3518 КM</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1981</td>
    <td>03.2001</td>
    <td>06.2014</td>
    <td>30710013030557</td>
    <td>369</td>
    <td>C 9399 PX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1981</td>
    <td>06.07.2000</td>
    <td>06.2015</td>
    <td>30710013030535</td>
    <td>339</td>
    <td>C 3073 КС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1981</td>
    <td>03.2001</td>
    <td>06.2015</td>
    <td>30710013030480</td>
    <td>371</td>
    <td>C 8371 PC</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1981</td>
    <td>10.2000</td>
    <td>2003</td>
    <td>30710013030456</td>
    <td>353</td>
    <td>C 1970 КP</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1981</td>
    <td>12.1998</td>
    <td>04.2014</td>
    <td>30710013030280</td>
    <td>337</td>
    <td>С 4916 НМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1981</td>
    <td>12.1998</td>
    <td>06.2015</td>
    <td>30710013030275</td>
    <td>319</td>
    <td>СА 9551 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1981</td>
    <td>08.2000</td>
    <td>06.2014</td>
    <td>30710013030235</td>
    <td>351</td>
    <td>C 3501 КM</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1981</td>
    <td>01.1999</td>
    <td>06.2014</td>
    <td>30710111026222</td>
    <td>323-&gt;1635</td>
    <td>С 9829 МВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1981</td>
    <td>01.1999</td>
    <td>30.08.2018</td>
    <td>30710111026176</td>
    <td>331-&gt;1641</td>
    <td>С 4917 НМ</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1981</td>
    <td>1981</td>
    <td>30.04.2003</td>
    <td></td>
    <td>3144-&gt;3850-&gt;3965-&gt;4454</td>
    <td>АМ 3144</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1981</td>
    <td>1981</td>
    <td>30.04.2003</td>
    <td></td>
    <td>3145-&gt;3753-&gt;3859-&gt;3973-&gt;4460</td>
    <td>АМ 3145</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>12.1984</td>
    <td>1985</td>
    <td>05.2010</td>
    <td>6821284</td>
    <td>3146-&gt;3851-&gt;3966-&gt;4452-&gt;1031</td>
    <td>СА 9556 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>3342-&gt;А-3006</td>
    <td>АМ 3342</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>3343</td>
    <td>АМ 3343</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>3344-&gt;3750</td>
    <td>АМ 3344</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>3345-&gt;3829</td>
    <td>АМ 3345</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>3346-&gt;3808</td>
    <td>АМ 3346</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>3347</td>
    <td>АМ 3347</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>3348-&gt;3809</td>
    <td>АМ 3348</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td>07.09.2000</td>
    <td></td>
    <td>3349-&gt;3810-&gt;3903-&gt;3807-&gt;3707</td>
    <td>АМ 3349</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td>07.09.2000</td>
    <td></td>
    <td>3350-&gt;3830-&gt;3910</td>
    <td>АМ 3350</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>3351</td>
    <td>АМ 3351</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>3352</td>
    <td>АМ 3352</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>3353</td>
    <td>АМ 3353</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>3354</td>
    <td>АМ 3354</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>3355</td>
    <td>АМ 3355</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>3356</td>
    <td>АМ 3356</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>3357</td>
    <td>АМ 3357</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>3358</td>
    <td>АМ 3358</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>3359</td>
    <td>АМ 3359</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>3360</td>
    <td>АМ 3360</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>3326</td>
    <td>АМ 3326</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>3327</td>
    <td>АМ 3327</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>3328</td>
    <td>АМ 3328</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td>29.01.2001</td>
    <td></td>
    <td>3329-&gt;А 3004</td>
    <td>АМ 3329</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>3330-&gt;А-3005</td>
    <td>АМ 3330</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2668-&gt;3801-&gt;3953</td>
    <td>АП 2668</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2669-&gt;4485-&gt;1485</td>
    <td>АП 2669</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2670</td>
    <td>АП 2670</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2671</td>
    <td>АП 2671</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2672</td>
    <td>АП 2672</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2673</td>
    <td>АП 2673</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2674</td>
    <td>АП 2674</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2675</td>
    <td>АП 2675</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2676</td>
    <td>АП 2676</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2677</td>
    <td>АП 2677</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2678</td>
    <td>АП 2678</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2679</td>
    <td>АП 2679</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2680</td>
    <td>АП 2680</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2681</td>
    <td>АП 2681</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2682</td>
    <td>АП 2682</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2683</td>
    <td>АП 2683</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2684</td>
    <td>АП 2684</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2685</td>
    <td>АП 2685</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2686</td>
    <td>АП 2686</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2687</td>
    <td>АП 2687</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2688</td>
    <td>АП 2688</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2689</td>
    <td>АП 2689</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2711</td>
    <td>АП 2711</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2712</td>
    <td>АП 2712</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2713</td>
    <td>АП 2713</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2714</td>
    <td>АП 2714</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2715</td>
    <td>АП 2715</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2716</td>
    <td>АП 2716</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td>1997</td>
    <td></td>
    <td>2717-&gt;2695</td>
    <td>АП 2717</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td>1988</td>
    <td></td>
    <td>2718</td>
    <td>АП 2718</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td>1993</td>
    <td></td>
    <td>2719-&gt;А-20</td>
    <td>АП 2719</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td>1988</td>
    <td></td>
    <td>2720</td>
    <td>АП 2720</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2731</td>
    <td>АП 2731</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2732</td>
    <td>АП 2732</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2734</td>
    <td>АП 2734</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2735</td>
    <td>АП 2735</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2736</td>
    <td>АП 2736</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2737</td>
    <td>АП 2737</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2738</td>
    <td>АП 2738</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2739</td>
    <td>АП 2739</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2740</td>
    <td>АП 2740</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2741</td>
    <td>АП 2741</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2850</td>
    <td>АП 2850</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2851</td>
    <td>АП 2851</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2852</td>
    <td>АП 2852</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2853</td>
    <td>АП 2853</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2854</td>
    <td>АП 2854</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2855</td>
    <td>АП 2855</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td>07.09.2000</td>
    <td></td>
    <td>2856-&gt;3844-&gt;3916</td>
    <td>АП 2856</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2857</td>
    <td>АП 2857</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2858</td>
    <td>АП 2858</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2859</td>
    <td>АП 2859</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1981</td>
    <td>1991</td>
    <td>11.2006</td>
    <td></td>
    <td>2961-&gt;4496-&gt;1049</td>
    <td>СА 3341 АН</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2980</td>
    <td>АП 2980</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2981</td>
    <td>АП 2981</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2982</td>
    <td>АП 2982</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2983</td>
    <td>АП 2983</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td>1988</td>
    <td></td>
    <td>2984-&gt;А-17</td>
    <td>АП 2984</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td>1999</td>
    <td></td>
    <td>2986-&gt;2787</td>
    <td>АП 2986</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td>1999</td>
    <td></td>
    <td>2987-&gt;2788</td>
    <td>АП 2987</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2988</td>
    <td>АП 2988</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2989</td>
    <td>АП 2989</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1981</td>
    <td>1981</td>
    <td>08.2007</td>
    <td></td>
    <td>907</td>
    <td>СА 1213 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1981</td>
    <td>10.1993</td>
    <td>23.07.2007</td>
    <td>30710111024965</td>
    <td>3225-&gt;3555</td>
    <td>СА 9183 АР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>20.07.1998</td>
    <td>02.08.2017</td>
    <td>30700013031810</td>
    <td>3774-&gt;2674</td>
    <td>СА 2758 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>19.05.1997</td>
    <td>13.09.2016</td>
    <td>30700013031788</td>
    <td>2561-&gt;3782-&gt;2839</td>
    <td>СА 8364 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>20.01.1998</td>
    <td>13.10.2016</td>
    <td>30700013031771</td>
    <td>1745</td>
    <td>СА 1185 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>19.05.1997</td>
    <td>06.2014</td>
    <td>30700013031649</td>
    <td>2556-&gt;7-&gt;1321</td>
    <td>СА 8816 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>19.05.1997</td>
    <td>04.09.2016</td>
    <td>30700013031591</td>
    <td>2554-&gt;3779-&gt;2671</td>
    <td>СА 8357 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>20.07.1998</td>
    <td>13.09.2016</td>
    <td>30700013031572</td>
    <td>3773-&gt;2675</td>
    <td>СА 3661 АХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>20.01.1998</td>
    <td>02.08.2018</td>
    <td>30700013031413</td>
    <td>1721</td>
    <td>СА 3308 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>12.07.1997</td>
    <td>06.2014</td>
    <td>30700013031401</td>
    <td>3765-&gt;1711</td>
    <td>СА 2754 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>12.07.1997</td>
    <td>13.09.2016</td>
    <td>30700013031376</td>
    <td>3763-&gt;1331</td>
    <td>СА 2753 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>19.05.1997</td>
    <td>13.09.2016</td>
    <td>30700013031323</td>
    <td>2560-&gt;5-&gt;1305</td>
    <td>СА 8823 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>20.01.1998</td>
    <td>06.2014</td>
    <td>30700013031315</td>
    <td>1685</td>
    <td>СА 2166 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>20.01.1998</td>
    <td>06.2015</td>
    <td>30700013031306</td>
    <td>1665</td>
    <td>СА 1178 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>20.01.1998</td>
    <td>06.2014</td>
    <td>30700013031284</td>
    <td>1671</td>
    <td>СА 9535 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>12.07.1997</td>
    <td>06.2015</td>
    <td>30700013031269</td>
    <td>3769-&gt;1327</td>
    <td>СА 4002 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>12.07.1997</td>
    <td>23.02.2015</td>
    <td>30700013031260</td>
    <td>3767-&gt;1325</td>
    <td>СА 2755 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>12.07.1997</td>
    <td>24.11.2017</td>
    <td>30700013031251</td>
    <td>3761-&gt;1329</td>
    <td>СА 2715 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>12.07.1997</td>
    <td>01.08.2017</td>
    <td>30700013031241</td>
    <td>3770-&gt;2678</td>
    <td>СА 2720 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>12.07.1997</td>
    <td>24.11.2017</td>
    <td>30700013031228</td>
    <td>3766-&gt;1757</td>
    <td>СА 2788 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>12.07.1997</td>
    <td>06.2014</td>
    <td>30700013031199</td>
    <td>3768-&gt;1323</td>
    <td>СА 2787 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>12.07.1997</td>
    <td>16.01.2019</td>
    <td>30700013030477</td>
    <td>3762-&gt;2679-&gt;1723</td>
    <td>СА 3669 АХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>12.07.1997</td>
    <td>03.2016</td>
    <td>30700013030463</td>
    <td>3760-&gt;1755</td>
    <td>СА 9185 АР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>02.1992</td>
    <td>02.08.2017</td>
    <td>30700013030458</td>
    <td>2410-&gt;2830-&gt;2660</td>
    <td> СА 2240 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>12.07.1997</td>
    <td>20.01.2014</td>
    <td>30700013030450</td>
    <td>3764-&gt;1709</td>
    <td>СА 2723 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>11.01.1999</td>
    <td>07.2016</td>
    <td>30700013030441</td>
    <td>4611-&gt;2841</td>
    <td>СА 6584 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>20.01.1998</td>
    <td>02.2016</td>
    <td>30700013030354</td>
    <td>1703-&gt;1301</td>
    <td>СА 8820 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>19.05.1997</td>
    <td>05.01.2017</td>
    <td>30700013030349</td>
    <td>2552-&gt;3777-&gt;2672-&gt;2658</td>
    <td>СА 2239 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>20.01.1998</td>
    <td>06.2015</td>
    <td>30700013030332</td>
    <td>1751</td>
    <td>СА 1184 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>19.05.1997</td>
    <td>16.10.2015</td>
    <td>30700013030322</td>
    <td>2550-&gt;3775-&gt;2836</td>
    <td>СА 2280 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1981</td>
    <td>19.05.1997</td>
    <td>06.2015</td>
    <td>30700013029986</td>
    <td>2558-&gt;9-&gt;1309</td>
    <td>СА 1187 АН</td>
  </tr>
  <tr>
    <td>Ikarus 250.67</td>
    <td>1985</td>
    <td>1986</td>
    <td>1997</td>
    <td></td>
    <td>2208</td>
    <td>АП 2208</td>
  </tr>
  <tr>
    <td>Ikarus 250.67</td>
    <td>1985</td>
    <td>1986</td>
    <td>1998</td>
    <td></td>
    <td>2210</td>
    <td>С 2178 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.03</td>
    <td>1981</td>
    <td>10.1995</td>
    <td>09.2009</td>
    <td></td>
    <td>4345-&gt;2252</td>
    <td>СА 0949 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.03</td>
    <td>1981</td>
    <td>05.1994</td>
    <td>1999</td>
    <td></td>
    <td>4187</td>
    <td>С 3603 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.03</td>
    <td>1981</td>
    <td>05.1994</td>
    <td>03.2000</td>
    <td></td>
    <td>4191</td>
    <td>С 2162 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.03</td>
    <td>1981</td>
    <td>05.1994</td>
    <td>2002</td>
    <td></td>
    <td>4195-&gt;1869</td>
    <td>С 3961 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.02</td>
    <td>1981</td>
    <td>01.1993</td>
    <td>04.2013</td>
    <td></td>
    <td>2274-&gt;2408-&gt;2396-&gt;2482</td>
    <td>СА 0811 АА</td>
  </tr>
  <tr>
    <td>Ikarus 280.02</td>
    <td>1981</td>
    <td>01.1993</td>
    <td>1997</td>
    <td></td>
    <td>2275-&gt;2409</td>
    <td>С 2294 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.02</td>
    <td>1981</td>
    <td>10.1992</td>
    <td>1999</td>
    <td></td>
    <td>2172</td>
    <td>С 2143 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.02</td>
    <td>1981</td>
    <td>10.1992</td>
    <td>1995</td>
    <td></td>
    <td>2415</td>
    <td>С 2157 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.02</td>
    <td>1981</td>
    <td>05.1994</td>
    <td>2003</td>
    <td></td>
    <td>4189-&gt;2220</td>
    <td>С 3689 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.03</td>
    <td>1981</td>
    <td>10.1992</td>
    <td>1999</td>
    <td></td>
    <td>2419</td>
    <td>С 2166 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.03</td>
    <td>1981</td>
    <td>10.1992</td>
    <td>18.11.2005</td>
    <td></td>
    <td>2420-&gt;2320</td>
    <td>С 2167 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.03</td>
    <td>1981</td>
    <td>10.1992</td>
    <td>2003</td>
    <td></td>
    <td>2448</td>
    <td>С 2144 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.03</td>
    <td>1981</td>
    <td>10.1992</td>
    <td>2000</td>
    <td></td>
    <td>2449-&gt;2349</td>
    <td>С 2145 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.03</td>
    <td>1981</td>
    <td>10.1992</td>
    <td>1999</td>
    <td></td>
    <td>2456</td>
    <td>С 2165 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>3076-&gt;3350</td>
    <td>АМ 3076</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>18.02.1998</td>
    <td></td>
    <td>3077-&gt;3205</td>
    <td>АМ 3077</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>3078-&gt;3351</td>
    <td>АМ 3078</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>3079-&gt;3312</td>
    <td>АМ 3079</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>18.02.1998</td>
    <td></td>
    <td>3080-&gt;3206</td>
    <td>АМ 3080</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>29.04.1999</td>
    <td></td>
    <td>3106-&gt;3313-&gt;3358-&gt;3975</td>
    <td>АМ 3106</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3107-&gt;3281</td>
    <td>АМ 3107</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>10.05.1999</td>
    <td></td>
    <td>3108-&gt;3247-&gt;3538-&gt;3848</td>
    <td>АМ 3108</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>11.1996</td>
    <td></td>
    <td>3109-&gt;3356</td>
    <td>АМ 3109</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>2000</td>
    <td></td>
    <td>3110-&gt;3282-&gt;4397</td>
    <td>АМ 3110</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1997</td>
    <td></td>
    <td>3111-&gt;3283</td>
    <td>АМ 3111</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>3112-&gt;3314</td>
    <td>АМ 3112</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>3113-&gt;3315</td>
    <td>АМ 3113</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1997</td>
    <td></td>
    <td>3149-&gt;3292-&gt;3327</td>
    <td>АМ 3292</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1987</td>
    <td></td>
    <td>3316</td>
    <td>АМ 3316</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>3317-&gt;3623-&gt;3641</td>
    <td>АМ 3317</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1987</td>
    <td></td>
    <td>3318</td>
    <td>АМ 3318</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>09.1998</td>
    <td></td>
    <td>3434-&gt;3669-&gt;4197</td>
    <td>С 2918 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1988</td>
    <td></td>
    <td>3435</td>
    <td>АМ 3435</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1988</td>
    <td></td>
    <td>3436</td>
    <td>АМ 3436</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1988</td>
    <td></td>
    <td>3437</td>
    <td>АМ 3437</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>3438-&gt;3583</td>
    <td>АМ 3438</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1988</td>
    <td></td>
    <td>3439</td>
    <td>АМ 3439</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>3440-&gt;2130-&gt;3621</td>
    <td>С 2130 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1988</td>
    <td></td>
    <td>3441</td>
    <td>АМ 3441</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1988</td>
    <td></td>
    <td>3457</td>
    <td>АМ 3457</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1988</td>
    <td></td>
    <td>3458</td>
    <td>АМ 3458</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2184</td>
    <td>АП 2184</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2185</td>
    <td>АП 2185</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2186</td>
    <td>АП 2186</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2187</td>
    <td>АП 2187</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2188</td>
    <td>АП 2188</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1995</td>
    <td></td>
    <td>2189</td>
    <td>АП 2189</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1995</td>
    <td></td>
    <td>2190</td>
    <td>АП 2190</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1998</td>
    <td></td>
    <td>2191-&gt;2332-&gt;2032</td>
    <td>АП 2191</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>2192-&gt;2292</td>
    <td>АП 2192</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2430</td>
    <td>АП 2430</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2431</td>
    <td>АП 2431</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1997</td>
    <td></td>
    <td>2432-&gt;2221</td>
    <td>АП 2432</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1997</td>
    <td></td>
    <td>2433-&gt;2318-&gt;791</td>
    <td>АП 2433</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>2003</td>
    <td></td>
    <td>2434-&gt;4212-&gt;2256</td>
    <td>АП 2434</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1997</td>
    <td></td>
    <td>2435-&gt;2227</td>
    <td>АП 2435</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>2003</td>
    <td></td>
    <td>2436-&gt;4293-&gt;4499-&gt;1499</td>
    <td>АП 2436</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>2437</td>
    <td>АП 2437</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>2438</td>
    <td>АП 2438</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1999</td>
    <td></td>
    <td>2439-&gt;4295</td>
    <td>АП 2439</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1987</td>
    <td></td>
    <td>2440</td>
    <td>АП 2440</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>2441</td>
    <td>С 0185 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1987</td>
    <td></td>
    <td>2442</td>
    <td>АП 2442</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>2443</td>
    <td>С 2117 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>14.01.2002</td>
    <td></td>
    <td>2444-&gt;4297-&gt;4211-&gt;1893</td>
    <td>АМ 1837</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>2003</td>
    <td></td>
    <td>2445-&gt;4299-&gt;2224</td>
    <td>АП 2445</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>06.08.2001</td>
    <td></td>
    <td>2446-&gt;1221</td>
    <td>АП 2446</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1997</td>
    <td></td>
    <td>2447-&gt;783</td>
    <td>АП 2447</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2448</td>
    <td>АП 2448</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2449</td>
    <td>АП 2449</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1995</td>
    <td></td>
    <td>2630</td>
    <td>АП 2630</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>2631</td>
    <td>АП 2631</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1995</td>
    <td></td>
    <td>2632-&gt;2326</td>
    <td>АП 2632</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1995</td>
    <td></td>
    <td>2633</td>
    <td>С 2060 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>2002</td>
    <td></td>
    <td>519-&gt;4317-&gt;4493-&gt;1493</td>
    <td>АМ 1832</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>1219-&gt;639</td>
    <td>С 2124 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1999</td>
    <td></td>
    <td>1275-&gt;665-&gt;1319</td>
    <td>АМ 1835</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>521-&gt;4221</td>
    <td>АМ 1836</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>12.1994</td>
    <td></td>
    <td>1241-&gt;4423-&gt;4183</td>
    <td>АМ 1837</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>789</td>
    <td>С 2434 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>523-&gt;4223</td>
    <td>АМ 1841</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1999</td>
    <td></td>
    <td>785-&gt;1221-&gt;1233</td>
    <td>С 1281 РН</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>12.1996</td>
    <td></td>
    <td>769-&gt;1301</td>
    <td>АМ 1847</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td>1996</td>
    <td></td>
    <td>1237</td>
    <td>АМ 1848</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1981</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>1605</td>
    <td>АМ ????</td>
  </tr>
  <tr>
    <td>Karosa B731</td>
    <td>1981</td>
    <td>01.1994</td>
    <td>1999</td>
    <td></td>
    <td>2846-&gt;2667</td>
    <td>С 4764 ПБ</td>
  </tr>
  <tr>
    <td>Karosa B731</td>
    <td>1981</td>
    <td>01.1994</td>
    <td>1999</td>
    <td></td>
    <td>2845-&gt;2667</td>
    <td>С 4765 ПБ</td>
  </tr>
  <tr>
    <td>Karosa B731</td>
    <td>1981</td>
    <td>01.1994</td>
    <td>1999</td>
    <td></td>
    <td>2844-&gt;2666</td>
    <td>С 4766 ПБ</td>
  </tr>
  <tr>
    <td>Karosa B731</td>
    <td>1981</td>
    <td>01.1994</td>
    <td>1999</td>
    <td></td>
    <td>2843-&gt;2665</td>
    <td>С 4167 ПБ</td>
  </tr>
  <tr>
    <td>Karosa B731</td>
    <td>1981</td>
    <td>01.1993</td>
    <td>1998</td>
    <td></td>
    <td>2835-&gt;2664</td>
    <td>С 4174 ПБ</td>
  </tr>
  <tr>
    <td>Karosa B731</td>
    <td>1980</td>
    <td>01.1992</td>
    <td>1997</td>
    <td></td>
    <td>2834-&gt;2663</td>
    <td>С 3647 ПБ</td>
  </tr>
  <tr>
    <td>Karosa B731</td>
    <td>1980</td>
    <td>01.1992</td>
    <td>1997</td>
    <td></td>
    <td>2833-&gt;2662</td>
    <td>С 3646 ПБ</td>
  </tr>
  <tr>
    <td>Karosa B731</td>
    <td>1980</td>
    <td>11.1991</td>
    <td>1998</td>
    <td></td>
    <td>2832-&gt;2661</td>
    <td>С 2906 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>01.03.1994</td>
    <td>14.02.2016</td>
    <td>30710111028495</td>
    <td>2516</td>
    <td>СА 2285 АН</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1980</td>
    <td>05.1996</td>
    <td>05.2010</td>
    <td></td>
    <td>4410-&gt;1017</td>
    <td>СА 2073 АТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1980</td>
    <td>06.07.2000</td>
    <td>04.2015</td>
    <td>30710013027121</td>
    <td>341</td>
    <td>C 3405 КС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1980</td>
    <td>02.01.1993</td>
    <td>04.2015</td>
    <td>30710013026555</td>
    <td>1607-&gt;1375</td>
    <td>СА 2078 АТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1980</td>
    <td>25.01.1996</td>
    <td>24.01.2016</td>
    <td>30710013026424</td>
    <td>3655-&gt;1601</td>
    <td>СА 9160 АВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1980</td>
    <td>02.01.1992</td>
    <td>13.09.2016</td>
    <td>30710013026091</td>
    <td>677-&gt;3660-&gt;1647</td>
    <td>СА 2724 АР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1980</td>
    <td>12.1998</td>
    <td>06.2015</td>
    <td>30710013026005</td>
    <td>325</td>
    <td>С 4913 НМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1980</td>
    <td>12.1998</td>
    <td>06.2014</td>
    <td>30710013025889</td>
    <td>321</td>
    <td>С 4908 НМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1980</td>
    <td>11.2000</td>
    <td>06.2014</td>
    <td>30710013025663</td>
    <td>363-&gt;1637</td>
    <td>C 5542 КT</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1980</td>
    <td>02.01.1993</td>
    <td>18.01.2005</td>
    <td>30710013025563</td>
    <td>1641-&gt;3678</td>
    <td>C 3625 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1980</td>
    <td>02.01.1993</td>
    <td>05.2015</td>
    <td>30710013024855</td>
    <td>763-&gt;3672-&gt;1607</td>
    <td>СА 3658 АХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1980</td>
    <td>02.01.1993</td>
    <td>05.2015</td>
    <td>30710013024774</td>
    <td>1617-&gt;3677-&gt;1623</td>
    <td>СА 3638 АХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1980</td>
    <td>05.1993</td>
    <td>1999</td>
    <td>30710013024557</td>
    <td>723</td>
    <td>C 3807 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1980</td>
    <td>02.1993</td>
    <td>1999</td>
    <td>30710013024528</td>
    <td>765</td>
    <td>C 3652 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>08.1993</td>
    <td>19.07.2005</td>
    <td>30710111024925</td>
    <td>3607</td>
    <td>С 3979 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>01.03.1994</td>
    <td>16.06.2017</td>
    <td>30710111024847</td>
    <td>2515</td>
    <td>СА 8434 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>10.1993</td>
    <td>02.08.2007</td>
    <td>30710111024446</td>
    <td>3230-&gt;3560</td>
    <td>СА 5438 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>01.03.1994</td>
    <td>02.09.2016</td>
    <td>30710111024423</td>
    <td>2525</td>
    <td>СА 8431 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>01.03.1994</td>
    <td>04.2015</td>
    <td>30710111024377</td>
    <td>2527-&gt;3698</td>
    <td>СА 3644 АТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>10.1993</td>
    <td>04.2015</td>
    <td>30710111024330</td>
    <td>3239-&gt;3569</td>
    <td>СА 7170 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>01.03.1994</td>
    <td>04.2015</td>
    <td>30710111024307</td>
    <td>2523</td>
    <td>СА 2256 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>10.1993</td>
    <td>04.2015</td>
    <td>30710111023996</td>
    <td>3231-&gt;3561</td>
    <td>СА 2718 АР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>10.1993</td>
    <td>29.06.2011</td>
    <td>30710111023934</td>
    <td>3235-&gt;3565</td>
    <td>СА 7522 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>10.1993</td>
    <td>04.2015</td>
    <td>30710111023913</td>
    <td>3222-&gt;3552</td>
    <td>СА 7530 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>01.03.1994</td>
    <td>27.07.2017</td>
    <td>30710111023860</td>
    <td>2528-&gt;2521</td>
    <td>СА 8370 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>01.03.1994</td>
    <td>17.08.2011</td>
    <td>30710111023739</td>
    <td>2529-&gt;3693</td>
    <td>СА 2715 АР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>08.1993</td>
    <td>04.2015</td>
    <td>30710111023717</td>
    <td>3606</td>
    <td>СА 9187 АР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>10.1993</td>
    <td>04.2015</td>
    <td>30710111023652</td>
    <td>3238-&gt;3568</td>
    <td>СА 1617 МР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>01.03.1994</td>
    <td>20.05.2017</td>
    <td>30710111023630</td>
    <td>2526</td>
    <td>СА 8433 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>19.03.1996</td>
    <td>21.06.2015</td>
    <td>30710111023606</td>
    <td>2532</td>
    <td>СА 8361 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>08.1993</td>
    <td>29.06.2011</td>
    <td>30710111023540</td>
    <td>3604</td>
    <td>СА 4011 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>10.1993</td>
    <td>14.02.2000</td>
    <td>30710111023466</td>
    <td>3220-&gt;3550</td>
    <td>С 4027 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>08.1993</td>
    <td>04.2015</td>
    <td>30710111023334</td>
    <td>3600</td>
    <td>СА 2707 АР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>08.1993</td>
    <td>04.2015</td>
    <td>30710111023302</td>
    <td>3605</td>
    <td>СА 5441 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>01.03.1994</td>
    <td>14.10.2015</td>
    <td>30710111023289</td>
    <td>2506</td>
    <td>СА 8356 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>01.03.1994</td>
    <td>30.12.2016</td>
    <td>30710111023279</td>
    <td>2517</td>
    <td>СА 8386 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1980</td>
    <td>01.03.1994</td>
    <td>27.07.2017</td>
    <td>30710111023235</td>
    <td>2502</td>
    <td>СА 2247 АН</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3091</td>
    <td>АМ 3091</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3092</td>
    <td>АМ 3092</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3093</td>
    <td>АМ 3093</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3094</td>
    <td>АМ 3094</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3095</td>
    <td>АМ 3095</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3096</td>
    <td>АМ 3096</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3097</td>
    <td>АМ 3097</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3098</td>
    <td>АМ 3098</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3331</td>
    <td>АМ 3331</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3332</td>
    <td>АМ 3332</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3333</td>
    <td>АМ 3333</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3334</td>
    <td>АМ 3334</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3335</td>
    <td>АМ 3335</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3336</td>
    <td>АМ 3336</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3337</td>
    <td>АМ 3337</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3338</td>
    <td>АМ 3338</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3339</td>
    <td>АМ 3339</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3340</td>
    <td>АМ 3340</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>3341</td>
    <td>АМ 3341</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2700</td>
    <td>АП 2700</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2701</td>
    <td>АП 2701</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2702-&gt;4489-&gt;1489</td>
    <td>АП 2702</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2704</td>
    <td>АП 2704</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2705</td>
    <td>АП 2705</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2706</td>
    <td>АП 2706</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2707</td>
    <td>АП 2707</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2708-&gt;2812</td>
    <td>АП 2708</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2709</td>
    <td>АП 2709</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2710</td>
    <td>АП 2710</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1980</td>
    <td>1989</td>
    <td>2014</td>
    <td></td>
    <td>2730-&gt;2761</td>
    <td>СА 2283 АН</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1980</td>
    <td>1991</td>
    <td>30.04.2003</td>
    <td></td>
    <td>2772-&gt;4434</td>
    <td>АМ 1959</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1980</td>
    <td>1989</td>
    <td>2005</td>
    <td></td>
    <td>2800-&gt;3990-&gt;809</td>
    <td>АД 0813</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1980</td>
    <td>1980</td>
    <td>05.2009</td>
    <td></td>
    <td>2807-&gt;1061</td>
    <td>СА 2068 АТ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2840</td>
    <td>АП 2840</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2841</td>
    <td>АП 2841</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2842</td>
    <td>АП 2842</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2843</td>
    <td>АП 2843</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2844</td>
    <td>АП 2844</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2845</td>
    <td>АП 2845</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2846</td>
    <td>АП 2846</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2847</td>
    <td>АП 2847</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2848</td>
    <td>АП 2848</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2849</td>
    <td>АП 2849</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1980</td>
    <td>1991</td>
    <td>30.04.2003</td>
    <td></td>
    <td>2964-&gt;3854-&gt;3969-&gt;4448</td>
    <td>АД 0212</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2970</td>
    <td>АП 2970</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2971</td>
    <td>АП 2971</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2972</td>
    <td>АП 2972</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2973</td>
    <td>АП 2973</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2974</td>
    <td>АП 2974</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2975</td>
    <td>АП 2975</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2976</td>
    <td>АП 2976</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2977</td>
    <td>АП 2977</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td>1995</td>
    <td></td>
    <td>2978-&gt;А-ТБ 13</td>
    <td>АП 2978</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td>1995</td>
    <td></td>
    <td>2979-&gt;А-ТБ 23</td>
    <td>АП 2979</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td>1999</td>
    <td></td>
    <td>19</td>
    <td>С&nbsp;&nbsp;5560</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>1219</td>
    <td>АД 0251</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td>1997</td>
    <td></td>
    <td>61</td>
    <td>АД 0297</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td>1997</td>
    <td></td>
    <td>1803</td>
    <td>С 4051 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>1801</td>
    <td>АД 0419</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>147</td>
    <td>АД 8401</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td>1990</td>
    <td></td>
    <td>847</td>
    <td>АД 8405</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>129</td>
    <td>АД 8406</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>25</td>
    <td>АД 8411</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>261</td>
    <td>АД 9625</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>361</td>
    <td>АД 9652</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td>1995</td>
    <td></td>
    <td>3-&gt;4415</td>
    <td>АД 9653</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>7</td>
    <td>АД 9654</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>955</td>
    <td>АМ 1291</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>1315</td>
    <td>АМ 8860</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1980</td>
    <td>05.1980</td>
    <td>30.04.2003</td>
    <td></td>
    <td>805-&gt;4470</td>
    <td>АД 0424</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1980</td>
    <td>05.1980</td>
    <td>1995</td>
    <td></td>
    <td>809</td>
    <td>АД 0427</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1980</td>
    <td>05.1980</td>
    <td>1996</td>
    <td></td>
    <td>811</td>
    <td>АД 0426</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1980</td>
    <td>05.1980</td>
    <td>2004</td>
    <td></td>
    <td>813</td>
    <td>С 8873 ТК</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1980</td>
    <td>05.1980</td>
    <td>30.04.2003</td>
    <td></td>
    <td>815-&gt;4472</td>
    <td>С 8211 РС</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1980</td>
    <td>05.1980</td>
    <td>30.04.2003</td>
    <td></td>
    <td>819-&gt;4492</td>
    <td>С 8478 КС</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1980</td>
    <td>05.1980</td>
    <td>30.04.2003</td>
    <td></td>
    <td>823-&gt;4468</td>
    <td>С 8471 КС</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1980</td>
    <td>05.1980</td>
    <td>1996</td>
    <td></td>
    <td>825</td>
    <td>СБ 0675</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>07.1985</td>
    <td></td>
    <td>3131</td>
    <td>АМ 3131</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1987</td>
    <td></td>
    <td>3132</td>
    <td>АМ 3132</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1997</td>
    <td></td>
    <td>4337-&gt;3245-&gt;3449</td>
    <td>АМ 3245</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1997</td>
    <td></td>
    <td>6695-&gt;3246-&gt;3320</td>
    <td>АМ 3246</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1987</td>
    <td></td>
    <td>3310</td>
    <td>АМ 3310</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1987</td>
    <td></td>
    <td>3311</td>
    <td>АМ 3311</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1987</td>
    <td></td>
    <td>3312</td>
    <td>АМ 3312</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1987</td>
    <td></td>
    <td>3313</td>
    <td>АМ 3313</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1987</td>
    <td></td>
    <td>3314</td>
    <td>АМ 3314</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1987</td>
    <td></td>
    <td>3315</td>
    <td>АМ 3315</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>3421</td>
    <td>АМ 3421</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>3422</td>
    <td>АМ 3422</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>3423</td>
    <td>АМ 3423</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>3424</td>
    <td>АМ 3424</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1996</td>
    <td></td>
    <td>3425-&gt;3626</td>
    <td>АМ 3425</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>3426</td>
    <td>АМ 3426</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>3427</td>
    <td>АМ 3427</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>3428</td>
    <td>АМ 3428</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>3429</td>
    <td>АМ 3429</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>3430</td>
    <td>АМ 3430</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>3431</td>
    <td>АМ 3431</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>3432</td>
    <td>АМ 3432</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td>3433</td>
    <td>АМ 3433</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1998</td>
    <td></td>
    <td>2400-&gt;2207-&gt;2826</td>
    <td>АП 2400</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1998</td>
    <td></td>
    <td>2401-&gt;2209-&gt;2831</td>
    <td>С 2381 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2402</td>
    <td>АП 2402</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1997</td>
    <td></td>
    <td>2403-&gt;2215</td>
    <td>АП 2403</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1997</td>
    <td></td>
    <td>2404-&gt;2216</td>
    <td>АП 2404</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2405</td>
    <td>АП 2405</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2406</td>
    <td>АП 2406</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1995</td>
    <td></td>
    <td>2407</td>
    <td>АП 2407</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2408</td>
    <td>АП 2408</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1995</td>
    <td></td>
    <td>2409</td>
    <td>С 2062 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2410</td>
    <td>АП 2410</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2411</td>
    <td>АП 2411</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2450</td>
    <td>АП 2450</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2451</td>
    <td>АП 2451</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2452</td>
    <td>АП 2452</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2454</td>
    <td>АП 2454</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2456</td>
    <td>АП 2456</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1998</td>
    <td></td>
    <td>2488-&gt;2246-&gt;2046</td>
    <td>АП 2488</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2489</td>
    <td>АП 2489</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2496</td>
    <td>АП 2496</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2497</td>
    <td>АП 2497</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2498</td>
    <td>АП 2498</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>2499</td>
    <td>АП 2499</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1995</td>
    <td></td>
    <td>362</td>
    <td>СВ 3563</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1988</td>
    <td></td>
    <td></td>
    <td>АМ 1880</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1989</td>
    <td></td>
    <td></td>
    <td>АМ 0874</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>2002</td>
    <td></td>
    <td>481-&gt;4119-&gt;4301-&gt;2241</td>
    <td>АМ 0847</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>14.01.2002</td>
    <td></td>
    <td>477-&gt;4101-&gt;4191-&gt;1867</td>
    <td>С 2162 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1980</td>
    <td>1980</td>
    <td>1998</td>
    <td></td>
    <td>479-&gt;4117</td>
    <td>С 0007 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.1999</td>
    <td>06.2014</td>
    <td>30710111020793</td>
    <td>335</td>
    <td>СА 9553 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.1999</td>
    <td>06.2014</td>
    <td>30710111020604</td>
    <td>317</td>
    <td>С 4915 НМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.1999</td>
    <td>06.2014</td>
    <td>30710111020546</td>
    <td>329-&gt;1639</td>
    <td>С 1668 НА</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>08.1993</td>
    <td>05.07.2005</td>
    <td>30710111019530</td>
    <td>3609</td>
    <td>С 3980 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>1998</td>
    <td>30710013025681</td>
    <td>659</td>
    <td>C 3800 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>04.2015</td>
    <td>30710013021024</td>
    <td>743-&gt;3668</td>
    <td>СА 8476 АТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>05.2015</td>
    <td>30710013021009</td>
    <td>797-&gt;3673-&gt;1617</td>
    <td>СА 7209 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>04.2015</td>
    <td>30710013020993</td>
    <td>717-&gt;3667</td>
    <td>СА 4438 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>09.1993</td>
    <td>04.2015</td>
    <td>30710013020927</td>
    <td>3645</td>
    <td>СА 3617 АР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>05.2015</td>
    <td>30710013020909</td>
    <td>711-&gt;3665-&gt;2534</td>
    <td>СА 3651 АX</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>04.2015</td>
    <td>30710013020884</td>
    <td>715-&gt;3666</td>
    <td>СА 0620 ВВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>02.01.1993</td>
    <td>04.2015</td>
    <td>30710013020227</td>
    <td>703-&gt;3664</td>
    <td>СА 8457 АТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>02.03.2001</td>
    <td>08.12.2016</td>
    <td>30710013019899</td>
    <td>367-&gt;1367</td>
    <td>C 0142 PС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>2000</td>
    <td>30710013018521</td>
    <td>785</td>
    <td>C 3817 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>02.1993</td>
    <td>05.2015</td>
    <td>30710013018202</td>
    <td>1601-&gt;3674-&gt;1621</td>
    <td>СА 4435 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>09.1993</td>
    <td>05.2015</td>
    <td>30710013018182</td>
    <td>3646-&gt;1629</td>
    <td>СА 8608 АХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>1999</td>
    <td>30710013018154</td>
    <td>761</td>
    <td>C 3814 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>09.1993</td>
    <td>17.08.2007</td>
    <td>30710013018140</td>
    <td>3647</td>
    <td>СА 7176 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>05.2015</td>
    <td>30710013018123</td>
    <td>747-&gt;3669-&gt;1605</td>
    <td>СА 2703 АР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>05.2015</td>
    <td>30710013018045</td>
    <td>681-&gt;3661-&gt;1603</td>
    <td>СА 7533 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>09.1993</td>
    <td>05.2015</td>
    <td>30710013017979</td>
    <td>3651-&gt;1625</td>
    <td>СА 8613 АХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>04.2015</td>
    <td>30710013017960</td>
    <td>751-&gt;3670</td>
    <td>СА 8473 АТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>13.09.2016</td>
    <td>30710013017941</td>
    <td>1631-&gt;1201-&gt;1643</td>
    <td>С 4912 НМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>04.2015</td>
    <td>30710013017923</td>
    <td>687-&gt;3663</td>
    <td>СА 7531 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>09.1993</td>
    <td>14.02.2000</td>
    <td>30710013017902</td>
    <td>3644</td>
    <td>C 3968 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>05.2015</td>
    <td>30710013017852</td>
    <td>753-&gt;3671-&gt;1611</td>
    <td>СА 2973 АТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>31.08.2018</td>
    <td>30710013017834</td>
    <td>759-&gt;1759</td>
    <td>СА 1194 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>09.1993</td>
    <td>05.2015</td>
    <td>30710013017791</td>
    <td>3643-&gt;2535</td>
    <td>СА 7197 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>05.2015</td>
    <td>30710013017733</td>
    <td>683-&gt;3662-&gt;2533</td>
    <td>СА 4453 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>02.2008</td>
    <td>16.01.2019</td>
    <td>30710013017693</td>
    <td>1645</td>
    <td>СА 1784 MB</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>1996</td>
    <td>30710013017524</td>
    <td>685</td>
    <td>C 3816 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>1999</td>
    <td>30710013017521</td>
    <td>1627</td>
    <td>C 3811 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>12.1998</td>
    <td>04.2015</td>
    <td>30710013017509</td>
    <td>327</td>
    <td>С 4914 НМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1993</td>
    <td>2000</td>
    <td>30710013017156</td>
    <td>1633</td>
    <td>C 3813 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>05.1994</td>
    <td>05.1994</td>
    <td>307100130?????</td>
    <td>725</td>
    <td></td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1979</td>
    <td>08.01.1996</td>
    <td>01.1996</td>
    <td>307100130?????</td>
    <td>3653</td>
    <td></td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>10.1993</td>
    <td>14.02.2000</td>
    <td>30710111019488</td>
    <td>3223-&gt;3553</td>
    <td>С 4047 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>10.1993</td>
    <td>10.06.2011</td>
    <td>30710111019403</td>
    <td>3229-&gt;3559</td>
    <td>СА 8466 АТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.03.1994</td>
    <td>04.2015</td>
    <td>30710111019361</td>
    <td>2511-&gt;3696</td>
    <td>СА 4439 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.03.1994</td>
    <td>02.08.2017</td>
    <td>30710111019319</td>
    <td>2501</td>
    <td>СА 8365 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>08.1993</td>
    <td>13.10.2005</td>
    <td>30710111019085</td>
    <td>3602</td>
    <td>С 3982 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.03.1994</td>
    <td>23.07.2007</td>
    <td>30710111019064</td>
    <td>2508-&gt;3690</td>
    <td>СА 8617 АХ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>10.1993</td>
    <td>20.08.2007</td>
    <td>30710111019044</td>
    <td>3224-&gt;3554</td>
    <td>СА 9193 АР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.03.1994</td>
    <td>27.07.2017</td>
    <td>30710111019023</td>
    <td>2513</td>
    <td>СА 4342 АР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.03.1994</td>
    <td>04.2015</td>
    <td>30710111019001</td>
    <td>2518-&gt;3697</td>
    <td>СА 8455 АТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>10.1993</td>
    <td>25.07.2007</td>
    <td>30710111018959</td>
    <td>3232-&gt;3562</td>
    <td>СА 4009 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.03.1994</td>
    <td>04.2015</td>
    <td>30710111018917</td>
    <td>2520-&gt;3692</td>
    <td>СА 8468 АТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.03.1994</td>
    <td>04.2015</td>
    <td>30710111018447</td>
    <td>2512</td>
    <td>СА 8381 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.03.1994</td>
    <td>03.2015</td>
    <td>30710111018413</td>
    <td>2514</td>
    <td>СА 8366 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.03.1994</td>
    <td>27.12.2015</td>
    <td>30710111018409</td>
    <td>2522</td>
    <td>СА 2246 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>10.1993</td>
    <td>14.02.2000</td>
    <td>30710111018350</td>
    <td>3233-&gt;3563</td>
    <td>С 4040 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.03.1994</td>
    <td>01.03.2011</td>
    <td>30710111018330</td>
    <td>2524</td>
    <td>СА 8430 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>10.1993</td>
    <td>14.02.2000</td>
    <td>30710111018309</td>
    <td>3228-&gt;3558</td>
    <td>С 4035 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>10.1993</td>
    <td>09.04.2003</td>
    <td>30710111018270</td>
    <td>3236-&gt;3566</td>
    <td>С 4043 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>08.1993</td>
    <td>29.06.2011</td>
    <td>30710111018249</td>
    <td>3603-&gt;3570</td>
    <td>СА 7535 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.03.1994</td>
    <td>04.2015</td>
    <td>30710111018230</td>
    <td>2509-&gt;3691</td>
    <td>СА 2721 АР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>08.1993</td>
    <td>08.2011</td>
    <td>30710111018190</td>
    <td>3608</td>
    <td>СА 0625 ВВ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.03.1994</td>
    <td>30.12.2016</td>
    <td>30710111018170</td>
    <td>2507</td>
    <td>СА 2276 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>08.1993</td>
    <td>01.04.2016</td>
    <td>30710111018151</td>
    <td>3601-&gt;2503</td>
    <td>СА 2279 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>10.1993</td>
    <td>04.2015</td>
    <td>30710111018131</td>
    <td>3226-&gt;3556</td>
    <td>СА 4436 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.03.1994</td>
    <td>04.2015</td>
    <td>30710111018110</td>
    <td>2503-&gt;3694</td>
    <td>СА 2713 АР</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>10.1993</td>
    <td>04.2015</td>
    <td>30710111018093</td>
    <td>3221-&gt;3551</td>
    <td>СА 8452 АТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>10.1993</td>
    <td>03.11.2003</td>
    <td>30710111018072</td>
    <td>3227-&gt;3557</td>
    <td>С 4034 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>10.1993</td>
    <td>04.2015</td>
    <td>30710111018053</td>
    <td>3234-&gt;3564</td>
    <td>СА 7526 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.03.1994</td>
    <td>04.2015</td>
    <td>30710111018033</td>
    <td>2504-&gt;3695</td>
    <td>СА 5440 АС</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.03.1994</td>
    <td>30.12.2016</td>
    <td>30710111018014</td>
    <td>2519</td>
    <td>СА 2281 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.03.1994</td>
    <td>01.03.2017</td>
    <td>30710111017860</td>
    <td>2521-&gt;2528</td>
    <td>СА 8384 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.03.1994</td>
    <td>30.05.2017</td>
    <td>30710111017824</td>
    <td>2510</td>
    <td>СА 8372 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>10.1993</td>
    <td>14.02.2000</td>
    <td>30710111017805</td>
    <td>3237-&gt;3567</td>
    <td>С 4044 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G Heuliez GTX </td>
    <td>1979</td>
    <td>01.03.1994</td>
    <td>30.05.2017</td>
    <td>30710111017785</td>
    <td>2505</td>
    <td>СА 8432 АМ</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1979</td>
    <td>1979</td>
    <td>01.07.2001</td>
    <td></td>
    <td>81-&gt;4421-&gt;1421</td>
    <td>С 5456 КА</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>3084</td>
    <td>АМ 3084</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>3085</td>
    <td>АМ 3085</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>3086</td>
    <td>АМ 3086</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>3087</td>
    <td>АМ 3087</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>3088</td>
    <td>АМ 3088</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>3089</td>
    <td>АМ 3089</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>3090</td>
    <td>АМ 3090</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2661</td>
    <td>АП 2661</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2662</td>
    <td>АП 2662</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td>1993</td>
    <td></td>
    <td>2663</td>
    <td>С 3372 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2664</td>
    <td>АП 2664</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2665</td>
    <td>АП 2665</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2666</td>
    <td>АП 2666</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2667</td>
    <td>АП 2667</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2830</td>
    <td>АП 2830</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2831</td>
    <td>АП 2831</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2832</td>
    <td>АП 2832</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2833</td>
    <td>АП 2833</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2834</td>
    <td>АП 2834</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2835</td>
    <td>АП 2835</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2836</td>
    <td>АП 2836</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2837</td>
    <td>АП 2837</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2838</td>
    <td>АП 2838</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2839</td>
    <td>АП 2839</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td>1995</td>
    <td></td>
    <td>2921-&gt;2780</td>
    <td>АП 2921</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2922</td>
    <td>АП 2922</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2923</td>
    <td>АП 2923</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2924</td>
    <td>АП 2924</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2925</td>
    <td>АП 2925</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2926</td>
    <td>АП 2926</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2927</td>
    <td>АП 2927</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2928</td>
    <td>АП 2928</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2929</td>
    <td>АП 2929</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1979</td>
    <td>1991</td>
    <td>30.04.2003</td>
    <td></td>
    <td>2959-&gt;4436</td>
    <td>АМ 2922</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2960</td>
    <td>АП 2960</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2961</td>
    <td>АП 2961</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2962</td>
    <td>АП 2962</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2963</td>
    <td>АП 2963</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2964</td>
    <td>АП 2964</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2965</td>
    <td>АП 2965</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2966</td>
    <td>АП 2966</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2967</td>
    <td>АП 2967</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2968</td>
    <td>АП 2968</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2969</td>
    <td>АП 2969</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td>1988</td>
    <td></td>
    <td>183</td>
    <td>АД 4600</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td>1988</td>
    <td></td>
    <td>247</td>
    <td>АД 4660</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td>01.07.2001</td>
    <td></td>
    <td>1841-&gt;У-12-&gt;4479-&gt;1479</td>
    <td>АД 4681</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td>1992</td>
    <td></td>
    <td>1835-&gt;У-06</td>
    <td>АД 4682</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1979</td>
    <td>1979</td>
    <td>1995</td>
    <td></td>
    <td>149</td>
    <td>АД 5193</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1979</td>
    <td>1989</td>
    <td>08.2008</td>
    <td></td>
    <td>2999-&gt;1065</td>
    <td>СА 2072 АТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>1996</td>
    <td>30700013020262</td>
    <td>441-&gt;1643</td>
    <td>C 3586 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>10.2013</td>
    <td>30700013020243</td>
    <td>422-&gt;1675</td>
    <td> СА 9567 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>06.2014</td>
    <td>30700013020338</td>
    <td>431-&gt;1677-&gt;17-&gt;1317</td>
    <td> СА 8824 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>06.2014</td>
    <td>30700013020479</td>
    <td>444-&gt;1679</td>
    <td>С 4910 НМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>06.2014</td>
    <td>30700013021995</td>
    <td>6-&gt;1681-&gt;11-&gt;1311</td>
    <td> СА 1158 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>04.09.2016</td>
    <td>30700013020177</td>
    <td>408-&gt;1683</td>
    <td>СА 8797 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>1997</td>
    <td>30700013020184</td>
    <td>409-&gt;1689</td>
    <td>C 3598 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>06.2015</td>
    <td>30700013020118</td>
    <td>402-&gt;1693</td>
    <td>СА 9545 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>06.2014</td>
    <td>30700013021965</td>
    <td>4-&gt;1707</td>
    <td>CA 6991 BC</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>06.2014</td>
    <td>30700013020237</td>
    <td>420-&gt;1717-&gt;15-&gt;1315</td>
    <td>СА 8826 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>06.1999</td>
    <td>30700013020345</td>
    <td>432-&gt;1725</td>
    <td>C 3589 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>06.2014</td>
    <td>30700013020138</td>
    <td>403-&gt;1727</td>
    <td>СА 8819 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>06.2014</td>
    <td>30700013019887</td>
    <td>401-&gt;1729-&gt;19-&gt;1319</td>
    <td>СА 8827 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>06.2014</td>
    <td>30700013020194</td>
    <td>412-&gt;1731</td>
    <td>СА 2077 АТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>14.09.2017</td>
    <td>30700013021860</td>
    <td>1-&gt;1733</td>
    <td>СА 2171 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>06.2014</td>
    <td>30700013020188</td>
    <td>410-&gt;1735</td>
    <td>СА 1170 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>06.1999</td>
    <td>3070001302????</td>
    <td>1737</td>
    <td>C 3591 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>13.09.2008</td>
    <td>30700013020327</td>
    <td>430-&gt;1739</td>
    <td>СА 1182 АН</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>13.04.2017</td>
    <td>30700013020573</td>
    <td>451-&gt;1741</td>
    <td>СА 8813 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1979</td>
    <td>20.11.1992</td>
    <td>20.02.2015</td>
    <td>30700013020254</td>
    <td>1697-&gt;2828</td>
    <td>С 2977 ВА</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1987</td>
    <td></td>
    <td>3302</td>
    <td>АМ 3302</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1987</td>
    <td></td>
    <td>3303</td>
    <td>АМ 3303</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1987</td>
    <td></td>
    <td>3304</td>
    <td>АМ 3304</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1987</td>
    <td></td>
    <td>3305</td>
    <td>АМ 3305</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1987</td>
    <td></td>
    <td>3306</td>
    <td>АМ 3306</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1987</td>
    <td></td>
    <td>3307</td>
    <td>АМ 3307</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1995</td>
    <td></td>
    <td>3308-&gt;3010</td>
    <td>АМ 3308</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1987</td>
    <td></td>
    <td>3309</td>
    <td>АМ 3309</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1987</td>
    <td></td>
    <td>3412</td>
    <td>АМ 3412</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1987</td>
    <td></td>
    <td>3413</td>
    <td>АМ 3413</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1987</td>
    <td></td>
    <td>3414</td>
    <td>АМ 3414</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1987</td>
    <td></td>
    <td>3415</td>
    <td>АМ 3415</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1987</td>
    <td></td>
    <td>3416</td>
    <td>АМ 3416</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1987</td>
    <td></td>
    <td>3417</td>
    <td>АМ 3417</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1987</td>
    <td></td>
    <td>3418</td>
    <td>АМ 3418</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1987</td>
    <td></td>
    <td>3419</td>
    <td>АМ 3419</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1987</td>
    <td></td>
    <td>3420</td>
    <td>АМ 3420</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1997</td>
    <td></td>
    <td>2300-&gt;2000</td>
    <td>АП 2300</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2301</td>
    <td>АП 2301</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2302</td>
    <td>АП 2302</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1997</td>
    <td></td>
    <td>2303-&gt;2003</td>
    <td>С 2067 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1997</td>
    <td></td>
    <td>2304-&gt;2004</td>
    <td>С 2076 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2305</td>
    <td>АП 2305</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1997</td>
    <td></td>
    <td>2306-&gt;2006</td>
    <td>С 2116 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2307</td>
    <td>АП 2307</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2308</td>
    <td>АП 2308</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2309</td>
    <td>АП 2309</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2310</td>
    <td>АП 2310</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1998</td>
    <td></td>
    <td>2383-&gt;4210</td>
    <td>АП 2383</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2384</td>
    <td>АП 2384</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2385</td>
    <td>АП 2385</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2386</td>
    <td>АП 2386</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1997</td>
    <td></td>
    <td>2387-&gt;2087</td>
    <td>АП 2387</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1997</td>
    <td></td>
    <td>2388-&gt;2088</td>
    <td>С 2082 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2389</td>
    <td>АП 2389</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1995</td>
    <td></td>
    <td>2390-&gt;2214</td>
    <td>С 2091 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2391</td>
    <td>АП 2391</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2392</td>
    <td>АП 2392</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2393</td>
    <td>АП 2393</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2394</td>
    <td>АП 2394</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2395</td>
    <td>АП 2395</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2396</td>
    <td>АП 2396</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2397</td>
    <td>АП 2397</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2398</td>
    <td>АП 2398</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2399</td>
    <td>АП 2399</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1992</td>
    <td></td>
    <td>2415</td>
    <td>С 2063 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1999</td>
    <td></td>
    <td>2416-&gt;2217</td>
    <td>АП 2416</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2417</td>
    <td>АП 2417</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2418</td>
    <td>АП 2418</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2419</td>
    <td>АП 2419</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2420</td>
    <td>АП 2420</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2421</td>
    <td>АП 2421</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2422</td>
    <td>АП 2422</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1997</td>
    <td></td>
    <td>2423-&gt;2219</td>
    <td>АП 2423</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2424</td>
    <td>АП 2424</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2426</td>
    <td>АП 2426</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2427</td>
    <td>АП 2427</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2428</td>
    <td>АП 2428</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td></td>
    <td></td>
    <td>2429</td>
    <td>АП 2429</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1979</td>
    <td>1979</td>
    <td>1998</td>
    <td></td>
    <td>1249</td>
    <td>С 2780 ПБ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1978</td>
    <td>02.01.1993</td>
    <td>08.2015</td>
    <td>30710013007906</td>
    <td>1603-&gt;3675-&gt;1613</td>
    <td>СА 1062 ВК</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1978</td>
    <td>02.1997</td>
    <td>04.2016</td>
    <td>30710013007828</td>
    <td>2500</td>
    <td>СА 2039 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1978</td>
    <td>22.05.1995</td>
    <td>05.2015</td>
    <td>30710013007821</td>
    <td>1755-&gt;3679-&gt;1615</td>
    <td>СА 8453 АТ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1978</td>
    <td>22.05.1995</td>
    <td>27.07.2017</td>
    <td>30710013007794</td>
    <td>2531</td>
    <td>СА 8359 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1978</td>
    <td>25.01.1996</td>
    <td>06.2014</td>
    <td>30710013007676</td>
    <td>1377</td>
    <td>СА 9548 АМ</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1978</td>
    <td>02.1993</td>
    <td>06.2014</td>
    <td>30710013007100</td>
    <td>1201-&gt;1631</td>
    <td>СА 3352 АН</td>
  </tr>
  <tr>
    <td>MAN SG192</td>
    <td>1978</td>
    <td>01.1996</td>
    <td>01.07.2001</td>
    <td></td>
    <td>2600</td>
    <td>С 8017 СТ</td>
  </tr>
  <tr>
    <td>MAN SG192</td>
    <td>1978</td>
    <td>01.1996</td>
    <td>09.2001</td>
    <td></td>
    <td>2601-&gt;2320</td>
    <td>С 8016 СТ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>3031</td>
    <td>АМ 3031</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>3032</td>
    <td>АМ 3032</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>3033</td>
    <td>АМ 3033</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>3034</td>
    <td>АМ 3034</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>3035</td>
    <td>АМ 3035</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>3056</td>
    <td>АМ 3056</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>3057</td>
    <td>АМ 3057</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>3058</td>
    <td>АМ 3058</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>3059</td>
    <td>АМ 3059</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td>09.1996</td>
    <td></td>
    <td>3060-&gt;3839-&gt;СТОЛОВА</td>
    <td>АМ 3060</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2651</td>
    <td>АП 2651</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2652</td>
    <td>АП 2652</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2653</td>
    <td>АП 2653</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2654</td>
    <td>АП 2654</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2655</td>
    <td>АП 2655</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td>1992</td>
    <td></td>
    <td>2656-&gt;А-11</td>
    <td>АП 2656</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2657</td>
    <td>АП 2657</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2658</td>
    <td>АП 2658</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2659</td>
    <td>АП 2659</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2660</td>
    <td>АП 2660</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2820</td>
    <td>АП 2820</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2821</td>
    <td>АП 2821</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2822</td>
    <td>АП 2822</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2823</td>
    <td>АП 2823</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2824</td>
    <td>АП 2824</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2825</td>
    <td>АП 2825</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2826</td>
    <td>АП 2826</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2827</td>
    <td>АП 2827</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2828</td>
    <td>АП 2828</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2829</td>
    <td>АП 2829</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2950</td>
    <td>АП 2950</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2951</td>
    <td>АП 2951</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2952</td>
    <td>АП 2952</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2953</td>
    <td>АП 2953</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2954</td>
    <td>АП 2954</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2955</td>
    <td>АП 2955</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2956</td>
    <td>АП 2956</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2957</td>
    <td>АП 2957</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2958</td>
    <td>АП 2958</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2959</td>
    <td>АП 2959</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td>1990</td>
    <td></td>
    <td>1853</td>
    <td>АД 3884</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td>1988</td>
    <td></td>
    <td>319</td>
    <td>АД 4166</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td>1993</td>
    <td></td>
    <td>839</td>
    <td>АД 4185</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td>1988</td>
    <td></td>
    <td>1019</td>
    <td>АД 4208</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td>1992</td>
    <td></td>
    <td>1909-&gt;У-08</td>
    <td>АД 4414</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1978</td>
    <td>1978</td>
    <td>1988</td>
    <td></td>
    <td>389</td>
    <td>АД 4494</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2145</td>
    <td>АП 2145</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2146</td>
    <td>АП 2146</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2147</td>
    <td>АП 2147</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2148</td>
    <td>АП 2148</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2149</td>
    <td>АП 2149</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2150</td>
    <td>АП 2150</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2158</td>
    <td>АП 2158</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2159</td>
    <td>АП 2159</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2161</td>
    <td>АП 2161</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2162</td>
    <td>АП 2162</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2163</td>
    <td>АП 2163</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2164</td>
    <td>АП 2164</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2166</td>
    <td>АП 2166</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2200</td>
    <td>АП 2200</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2232</td>
    <td>АП 2232</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2311</td>
    <td>АП 2311</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2312</td>
    <td>АП 2312</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td>1997</td>
    <td></td>
    <td>2313-&gt;2322-&gt;2022</td>
    <td>АП 2313</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2315</td>
    <td>АП 2315</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2316</td>
    <td>АП 2316</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2317</td>
    <td>АП 2317</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2318</td>
    <td>АП 2318</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2319</td>
    <td>АП 2319</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2320</td>
    <td>АП 2320</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2322</td>
    <td>АП 2322</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2323</td>
    <td>АП 2323</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2324</td>
    <td>АП 2324</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td>1997</td>
    <td></td>
    <td>2325-&gt;2025</td>
    <td>АП 2325</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2326</td>
    <td>АП 2326</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2327</td>
    <td>АП 2327</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2328</td>
    <td>АП 2328</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2329</td>
    <td>АП 2329</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td>1997</td>
    <td></td>
    <td>2330-&gt;2030</td>
    <td>АП 2330</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2331</td>
    <td>АП 2331</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2332</td>
    <td>АП 2332</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2333</td>
    <td>АП 2333</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2362</td>
    <td>АП 2362</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td>1998</td>
    <td></td>
    <td>2363-&gt;2063</td>
    <td>АП 2363</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td>1989</td>
    <td></td>
    <td>2364</td>
    <td>АП 2364</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td>1998</td>
    <td></td>
    <td>2365-&gt;2065</td>
    <td>АП 2365</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2366</td>
    <td>АП 2366</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>2372</td>
    <td>АП 2372</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td>1990</td>
    <td></td>
    <td>715</td>
    <td>АД 5727</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td>1991</td>
    <td></td>
    <td></td>
    <td>АД 5728</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1978</td>
    <td>1978</td>
    <td>1990</td>
    <td></td>
    <td>471</td>
    <td>С 0006 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 266.25</td>
    <td>1978</td>
    <td>1978</td>
    <td>1988</td>
    <td></td>
    <td>993</td>
    <td>С 6334</td>
  </tr>
  <tr>
    <td>Ikarus 266.25</td>
    <td>1978</td>
    <td>1978</td>
    <td>1988</td>
    <td></td>
    <td>999</td>
    <td>С 6271</td>
  </tr>
  <tr>
    <td>Ikarus 266.25</td>
    <td>1978</td>
    <td>1978</td>
    <td>1988</td>
    <td></td>
    <td>1813</td>
    <td>АП 0667</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305G</td>
    <td>1977</td>
    <td>09.1993</td>
    <td>14.02.2000</td>
    <td>30710013006305</td>
    <td>3650</td>
    <td>C 3977 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1977</td>
    <td>05.1996</td>
    <td>05.2010</td>
    <td></td>
    <td>4414-&gt;1021</td>
    <td>С 7774 РХ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>3011</td>
    <td>АМ 3011</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>3012</td>
    <td>АМ 3012</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>3013</td>
    <td>АМ 3013</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>3014</td>
    <td>АМ 3014</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>3015</td>
    <td>АМ 3015</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>3016</td>
    <td>АМ 3016</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td>09.1996</td>
    <td></td>
    <td>3017-&gt;3825</td>
    <td>АМ 3017</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>3018</td>
    <td>АМ 3018</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>3029</td>
    <td>АМ 3029</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>3030</td>
    <td>АМ 3030</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1977</td>
    <td>1991</td>
    <td>30.04.2003</td>
    <td></td>
    <td>2657-&gt;2757-&gt;4440</td>
    <td>СГ 1441</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2810</td>
    <td>АП 2810</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2811</td>
    <td>АП 2811</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2812</td>
    <td>АП 2812</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2813</td>
    <td>АП 2813</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2814</td>
    <td>АП 2814</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2815</td>
    <td>АП 2815</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2816</td>
    <td>АП 2816</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2817</td>
    <td>АП 2817</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2818</td>
    <td>АП 2818</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2819</td>
    <td>АП 2819</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2930</td>
    <td>АП 2930</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2931</td>
    <td>АП 2931</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2932</td>
    <td>АП 2932</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2933</td>
    <td>АП 2933</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2934</td>
    <td>АП 2934</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2935</td>
    <td>АП 2935</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2936</td>
    <td>АП 2936</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2937</td>
    <td>АП 2937</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2938</td>
    <td>АП 2938</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2939</td>
    <td>АП 2939</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1977</td>
    <td>1977</td>
    <td>2003</td>
    <td></td>
    <td>2992</td>
    <td>СО 2119 МА</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1977</td>
    <td>1977</td>
    <td>2004</td>
    <td></td>
    <td>2994-&gt;3994</td>
    <td>С 1197 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td>1989</td>
    <td></td>
    <td>905</td>
    <td>АД ????</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td>1988</td>
    <td></td>
    <td>21</td>
    <td>АД 4211</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td>1988</td>
    <td></td>
    <td>265</td>
    <td>АД 0844</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td>1988</td>
    <td></td>
    <td>285</td>
    <td>АД 0909</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td>2013</td>
    <td></td>
    <td>283-&gt;4417-&gt;А-17</td>
    <td>АД 0915</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>1052</td>
    <td>СЛ 0266</td>
  </tr>
  <tr>
    <td>Чавдар 11м4</td>
    <td>1977</td>
    <td>1993</td>
    <td>1999</td>
    <td></td>
    <td>1909</td>
    <td>С 4130 ПБ</td>
  </tr>
  <tr>
    <td>MAN SG192</td>
    <td>1977</td>
    <td>12.1991</td>
    <td>1996</td>
    <td></td>
    <td>2711-&gt;2824</td>
    <td>С 3560 ПБ</td>
  </tr>
  <tr>
    <td>MAN SG192</td>
    <td>1977</td>
    <td>10.1990</td>
    <td>2000</td>
    <td></td>
    <td>2821-&gt;2324</td>
    <td>С 2127 ПБ</td>
  </tr>
  <tr>
    <td>MAN SG192</td>
    <td>1977</td>
    <td>10.1990</td>
    <td>2000</td>
    <td></td>
    <td>2188-&gt;2632</td>
    <td>С 2138 ПБ</td>
  </tr>
  <tr>
    <td>MAN SG192</td>
    <td>1977</td>
    <td>10.1990</td>
    <td>2000</td>
    <td></td>
    <td>2451-&gt;2327</td>
    <td>С 2113 ПБ</td>
  </tr>
  <tr>
    <td>MAN SG192</td>
    <td>1977</td>
    <td>10.1990</td>
    <td>1996</td>
    <td></td>
    <td>2452</td>
    <td>С 2110 ПБ</td>
  </tr>
  <tr>
    <td>MAN SL200</td>
    <td>1977</td>
    <td>05.11.1992	</td>
    <td>2001</td>
    <td></td>
    <td>2804-&gt;2661</td>
    <td>С 3459 ПБ</td>
  </tr>
  <tr>
    <td>MAN SL200</td>
    <td>1977</td>
    <td>05.11.1992	</td>
    <td>2001</td>
    <td></td>
    <td>2813-&gt;2662</td>
    <td>С 3460 ПБ</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td>01.07.1989</td>
    <td></td>
    <td>1901-&gt;У-02</td>
    <td>АД 3535</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1977</td>
    <td>1977</td>
    <td>01.07.1989</td>
    <td></td>
    <td>1903-&gt;У-04</td>
    <td>АД 3516</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>3206</td>
    <td>АМ 3206</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>3207</td>
    <td>АМ 3207</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>3208</td>
    <td>АМ 3208</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>3209</td>
    <td>АМ 3209</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>3210</td>
    <td>АМ 3210</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>3211</td>
    <td>АМ 3211</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>3212</td>
    <td>АМ 3212</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>3213</td>
    <td>АМ 3213</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>3214</td>
    <td>АМ 3214</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>3215</td>
    <td>АМ 3215</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>3216</td>
    <td>АМ 3216</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>3217</td>
    <td>АМ 3217</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>3218</td>
    <td>АМ 3218</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>3219</td>
    <td>АМ 3219</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>3220</td>
    <td>АМ 3220</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>3221</td>
    <td>АМ 3221</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>669-&gt;3231</td>
    <td>АМ 3231</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>671-&gt;3232</td>
    <td>АМ 3232</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>673-&gt;3233</td>
    <td>АМ 3233</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>675-&gt;3234</td>
    <td>АМ 3234</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>677-&gt;3235</td>
    <td>АМ 3235</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>679-&gt;3236</td>
    <td>АМ 3236</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>681-&gt;3237</td>
    <td>АМ 3237</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>683-&gt;3238</td>
    <td>АМ 3238</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>685-&gt;3239</td>
    <td>АМ 3239</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>687-&gt;3240</td>
    <td>АМ 3240</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1987</td>
    <td></td>
    <td>689-&gt;3241</td>
    <td>АМ 3241</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2250</td>
    <td>АП 2250</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1994</td>
    <td></td>
    <td>2251</td>
    <td>С 2061 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2252</td>
    <td>АП 2252</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2253</td>
    <td>АП 2253</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1995</td>
    <td></td>
    <td>2254</td>
    <td>АП 2254</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2255</td>
    <td>АП 2255</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2256</td>
    <td>АП 2256</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2257</td>
    <td>АП 2257</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2258</td>
    <td>АП 2258</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2259</td>
    <td>АП 2259</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2260</td>
    <td>АП 2260</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2261</td>
    <td>АП 2261</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2262</td>
    <td>АП 2262</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2263</td>
    <td>АП 2263</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1998</td>
    <td></td>
    <td>2264-&gt;4289</td>
    <td>АП 2264</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1997</td>
    <td></td>
    <td>2265-&gt;2316-&gt;2016</td>
    <td>АП 2265</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1997</td>
    <td></td>
    <td>2266-&gt;2319-&gt;2019</td>
    <td>АП 2266</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1997</td>
    <td></td>
    <td>2267-&gt;2312</td>
    <td>АП 2267</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2268</td>
    <td>АП 2268</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2269</td>
    <td>АП 2269</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2270</td>
    <td>АП 2270</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2271</td>
    <td>АП 2271</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2272</td>
    <td>АП 2272</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1997</td>
    <td></td>
    <td>2273-&gt;2315-&gt;2015</td>
    <td>АП 2273</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1993</td>
    <td></td>
    <td>2274</td>
    <td>АП 2274</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2275</td>
    <td>АП 2275</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2276</td>
    <td>АП 2276</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1997</td>
    <td></td>
    <td>2277-&gt;2339-&gt;2039</td>
    <td>АП 2277</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2278</td>
    <td>АП 2278</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1993</td>
    <td></td>
    <td>2279</td>
    <td>АП 2279</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2280</td>
    <td>АП 2280</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2281</td>
    <td>АП 2281</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2283</td>
    <td>АП 2283</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2284</td>
    <td>АП 2284</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2285</td>
    <td>АП 2285</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2286</td>
    <td>АП 2286</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1999</td>
    <td></td>
    <td>2287-&gt;4214-&gt;4269</td>
    <td>С 0007 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2288</td>
    <td>АП 2288</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2290</td>
    <td>АП 2290</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2291</td>
    <td>АП 2291</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1997</td>
    <td></td>
    <td>2336-&gt;2036</td>
    <td>АП 2336</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2338</td>
    <td>АП 2338</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2339</td>
    <td>АП 2339</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2344</td>
    <td>АП 2344</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2345</td>
    <td>АП 2345</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2346</td>
    <td>АП 2346</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2347</td>
    <td>АП 2347</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2352</td>
    <td>АП 2352</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2353</td>
    <td>АП 2353</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2354</td>
    <td>АП 2354</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2355</td>
    <td>АП 2355</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2618</td>
    <td>АП 2618</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2620</td>
    <td>АП 2620</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2621</td>
    <td>АП 2621</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2622</td>
    <td>АП 2622</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2623</td>
    <td>АП 2623</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2624</td>
    <td>АП 2624</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2625</td>
    <td>АП 2625</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2626</td>
    <td>АП 2626</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2627</td>
    <td>АП 2627</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2628</td>
    <td>АП 2628</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>2629</td>
    <td>АП 2629</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1996</td>
    <td></td>
    <td>781</td>
    <td>АД 5607</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1997</td>
    <td></td>
    <td>783-&gt;3290</td>
    <td>АД 5723</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1998</td>
    <td></td>
    <td>499-&gt;4215-&gt;4420</td>
    <td>АД 5167</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1996</td>
    <td></td>
    <td>493-&gt;4209</td>
    <td>АД 5168</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>04.1996</td>
    <td></td>
    <td>1215</td>
    <td>АД 5182</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1999</td>
    <td></td>
    <td>651</td>
    <td>С 0161 НВ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1996</td>
    <td></td>
    <td>497-&gt;4211</td>
    <td>АД 5187</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1990</td>
    <td></td>
    <td>495</td>
    <td>АД ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1988</td>
    <td></td>
    <td>643</td>
    <td>АД 5190</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>01.1998</td>
    <td></td>
    <td>623</td>
    <td>С 2123 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1993</td>
    <td></td>
    <td>655</td>
    <td>С 2187 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1997</td>
    <td></td>
    <td>695</td>
    <td>С 2197 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>2000</td>
    <td></td>
    <td>491-&gt;4109-&gt;4391</td>
    <td>АД 6645</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1997</td>
    <td></td>
    <td>1243</td>
    <td>С 2931 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1996</td>
    <td></td>
    <td>1489-&gt;4219</td>
    <td>СТГ 1552</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1988</td>
    <td></td>
    <td>1495</td>
    <td>СТГ 1549</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>06.1998</td>
    <td></td>
    <td>1203</td>
    <td>С 2398 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>10.1996</td>
    <td></td>
    <td>1207-&gt;627-&gt;3550</td>
    <td>С 2135 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1997</td>
    <td></td>
    <td>1217</td>
    <td>С 0184 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1998</td>
    <td></td>
    <td>1241</td>
    <td>С 2424 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1988</td>
    <td></td>
    <td></td>
    <td>АД 5036</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1989</td>
    <td></td>
    <td>536</td>
    <td>АД 5039</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1977</td>
    <td>1977</td>
    <td>1989</td>
    <td></td>
    <td>540</td>
    <td>АД ????</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>3001</td>
    <td>АМ 3001</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>3002</td>
    <td>АМ 3002</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>3003</td>
    <td>АМ 3003</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>3004</td>
    <td>АМ 3004</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td>07.09.2000</td>
    <td></td>
    <td>3005-&gt;А-3001</td>
    <td>С 1546 НН</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>3006</td>
    <td>АМ 3006</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>3007</td>
    <td>АМ 3007</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>3008</td>
    <td>АМ 3008</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>3009</td>
    <td>АМ 3009</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>3010</td>
    <td>АМ 3010</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2800</td>
    <td>АП 2800</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2801</td>
    <td>АП 2801</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2802</td>
    <td>АП 2802</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2803</td>
    <td>АП 2803</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2804</td>
    <td>АП 2804</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2805</td>
    <td>АП 2805</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2806</td>
    <td>АП 2806</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2808</td>
    <td>АП 2808</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2809</td>
    <td>АП 2809</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2990</td>
    <td>АП 2990</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2991</td>
    <td>АП 2991</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2993</td>
    <td>АП 2993</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2995</td>
    <td>АП 2995</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2996</td>
    <td>АП 2996</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2997</td>
    <td>АП 2997</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2999</td>
    <td>АП 2999</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td>1988</td>
    <td></td>
    <td>1877</td>
    <td>СР 1543</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td>1982</td>
    <td></td>
    <td>580</td>
    <td>СР ????</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td>1988</td>
    <td></td>
    <td></td>
    <td>СР 1234</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1976</td>
    <td>1976</td>
    <td>1990</td>
    <td></td>
    <td>925</td>
    <td>СР 0614</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1976</td>
    <td>20.11.1992</td>
    <td>24.07.2017</td>
    <td>30700013004599</td>
    <td>2822-&gt;2658-&gt;2672</td>
    <td>СА 8360 АМ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1990</td>
    <td></td>
    <td>500</td>
    <td>СГ 0500</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1990</td>
    <td></td>
    <td>8655</td>
    <td>АД 8655</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1989</td>
    <td></td>
    <td>3036</td>
    <td>АМ 3036</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1996</td>
    <td></td>
    <td>3037-&gt;3500</td>
    <td>АМ 3037</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1989</td>
    <td></td>
    <td>3038</td>
    <td>АМ 3038</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1996</td>
    <td></td>
    <td>3039-&gt;3501</td>
    <td>АМ 3039</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1989</td>
    <td></td>
    <td>3040</td>
    <td>АМ 3040</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1989</td>
    <td></td>
    <td>3041</td>
    <td>АМ 3041</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1989</td>
    <td></td>
    <td>3042</td>
    <td>АМ 3042</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1989</td>
    <td></td>
    <td>3043</td>
    <td>АМ 3043</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1989</td>
    <td></td>
    <td>3044</td>
    <td>АМ 3044</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1989</td>
    <td></td>
    <td>3045</td>
    <td>АМ 3045</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1989</td>
    <td></td>
    <td>3046</td>
    <td>АМ 3046</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1989</td>
    <td></td>
    <td>3047</td>
    <td>АМ 3047</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1989</td>
    <td></td>
    <td>3048</td>
    <td>АМ 3048</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1989</td>
    <td></td>
    <td>3049</td>
    <td>АМ 3049</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1989</td>
    <td></td>
    <td>3050</td>
    <td>АМ 3050</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1989</td>
    <td></td>
    <td>3051</td>
    <td>АМ 3051</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1989</td>
    <td></td>
    <td>3052</td>
    <td>АМ 3052</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1989</td>
    <td></td>
    <td>3053</td>
    <td>АМ 3053</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1989</td>
    <td></td>
    <td>3054</td>
    <td>АМ 3054</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1994</td>
    <td></td>
    <td>3055-&gt;3204</td>
    <td>АМ 3055</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1988</td>
    <td></td>
    <td>3061</td>
    <td>АМ 3061</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1988</td>
    <td></td>
    <td>3062</td>
    <td>АМ 3062</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1988</td>
    <td></td>
    <td>3063</td>
    <td>АМ 3063</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1988</td>
    <td></td>
    <td>3064</td>
    <td>АМ 3064</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1988</td>
    <td></td>
    <td>3065</td>
    <td>АМ 3065</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1988</td>
    <td></td>
    <td>3066</td>
    <td>АМ 3066</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1988</td>
    <td></td>
    <td>3067</td>
    <td>АМ 3067</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1988</td>
    <td></td>
    <td>3068</td>
    <td>АМ 3068</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1988</td>
    <td></td>
    <td>3069</td>
    <td>АМ 3069</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1988</td>
    <td></td>
    <td>3070</td>
    <td>АМ 3070</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2102</td>
    <td>АП 2102</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2104</td>
    <td>АП 2104</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2106</td>
    <td>АП 2106</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2107</td>
    <td>АП 2107</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2109</td>
    <td>АП 2109</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2110</td>
    <td>АП 2110</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2111</td>
    <td>АП 2111</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2112</td>
    <td>АП 2112</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2113</td>
    <td>АП 2113</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2114</td>
    <td>АП 2114</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2115</td>
    <td>АП 2115</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2116</td>
    <td>АП 2116</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2117</td>
    <td>АП 2117</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2118</td>
    <td>АП 2118</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2119</td>
    <td>АП 2119</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2120</td>
    <td>АП 2120</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2121</td>
    <td>АП 2121</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2123</td>
    <td>АП 2123</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2124</td>
    <td>АП 2124</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2125</td>
    <td>АП 2125</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2126</td>
    <td>АП 2126</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2127</td>
    <td>АП 2127</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2128</td>
    <td>АП 2128</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2129</td>
    <td>АП 2129</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2131</td>
    <td>АП 2131</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2132</td>
    <td>АП 2132</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2133</td>
    <td>АП 2133</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2135</td>
    <td>АП 2135</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2137</td>
    <td>АП 2137</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2140</td>
    <td>АП 2140</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2141</td>
    <td>АП 2141</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>2142</td>
    <td>АП 2142</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1990</td>
    <td></td>
    <td>715</td>
    <td>АД 1727</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1986</td>
    <td></td>
    <td>727</td>
    <td>АД 1742</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>12.1996</td>
    <td></td>
    <td>787</td>
    <td>СГ 0267</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1996</td>
    <td></td>
    <td>785</td>
    <td>СГ 0287</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1988</td>
    <td></td>
    <td>685</td>
    <td>СГ 0327</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1988</td>
    <td></td>
    <td>673</td>
    <td>СР 0376</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1996</td>
    <td></td>
    <td>795</td>
    <td>СГ 0407</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>12.1996</td>
    <td></td>
    <td>767-&gt;1293</td>
    <td>СГ 0435</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1997</td>
    <td></td>
    <td>791-&gt;3289</td>
    <td>СГ 0449</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1988</td>
    <td></td>
    <td>545</td>
    <td>АД ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1988</td>
    <td></td>
    <td></td>
    <td>АД 1923</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1996</td>
    <td></td>
    <td>1213</td>
    <td>АД 1911</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1998</td>
    <td></td>
    <td>1209</td>
    <td>С 2451 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1987</td>
    <td></td>
    <td>17??</td>
    <td>СГ 0401</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>1987</td>
    <td></td>
    <td>1733</td>
    <td>СГ 2790</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1976</td>
    <td>1976</td>
    <td>12.1988</td>
    <td></td>
    <td>1617</td>
    <td>СГ 3549</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>1243</td>
    <td>СЛ 0092</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1975</td>
    <td>1975</td>
    <td>1985</td>
    <td></td>
    <td>365</td>
    <td>СЛ 0474</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1975</td>
    <td>1975</td>
    <td>1990</td>
    <td></td>
    <td>1837</td>
    <td>СЛ 0481</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1975</td>
    <td>1975</td>
    <td>1986</td>
    <td></td>
    <td>760</td>
    <td>СЛ 0495</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1975</td>
    <td>1975</td>
    <td>1988</td>
    <td></td>
    <td></td>
    <td>СА 1002</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1975</td>
    <td>1975</td>
    <td>1988</td>
    <td></td>
    <td></td>
    <td>СА 1018</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1975</td>
    <td>1975</td>
    <td>1988</td>
    <td></td>
    <td></td>
    <td>СГ 1749</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1975</td>
    <td>1975</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>СА 3511</td>
  </tr>
  <tr>
    <td>Чавдар 11г5</td>
    <td>1975</td>
    <td>1975</td>
    <td>1985</td>
    <td></td>
    <td></td>
    <td>СА 3514</td>
  </tr>
  <tr>
    <td>Чавдар 11м3</td>
    <td>1975</td>
    <td>1975</td>
    <td></td>
    <td></td>
    <td></td>
    <td>АД 7746</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1988</td>
    <td></td>
    <td>3099</td>
    <td>АМ 3099</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1988</td>
    <td></td>
    <td>3100</td>
    <td>АМ 3100</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1995</td>
    <td></td>
    <td>3101-&gt;3009</td>
    <td>АМ 3101</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>3102</td>
    <td>АМ 3102</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>3103</td>
    <td>АМ 3103</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>3104</td>
    <td>АМ 3104</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>3105</td>
    <td>АМ 3105</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1995</td>
    <td></td>
    <td>2703</td>
    <td>АП 2703</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1989</td>
    <td></td>
    <td>111</td>
    <td>СЛ 0142</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>627</td>
    <td>СЛ 0225</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1988</td>
    <td></td>
    <td>717</td>
    <td>СА 2132</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1988</td>
    <td></td>
    <td>1110</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>1120</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>1122</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1988</td>
    <td></td>
    <td>1247</td>
    <td>СВ 2069</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1999</td>
    <td></td>
    <td>1255</td>
    <td>С 3836 ПБ</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1988</td>
    <td></td>
    <td>1430</td>
    <td>СЛ 0138</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>1459</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>1463</td>
    <td>СЛ 0459</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1988</td>
    <td></td>
    <td>1490</td>
    <td>СЛ 0454</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1988</td>
    <td></td>
    <td>1496</td>
    <td>СЛ 0384</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1988</td>
    <td></td>
    <td>1498</td>
    <td>СЛ 0385</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1988</td>
    <td></td>
    <td>1644</td>
    <td>СВ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1989</td>
    <td></td>
    <td>1640</td>
    <td>СВ 2518</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1989</td>
    <td></td>
    <td></td>
    <td>СВ 3940</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1989</td>
    <td></td>
    <td></td>
    <td>СВ 3948</td>
  </tr>
  <tr>
    <td>Ikarus 280.08</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td></td>
    <td>СЛ 0026</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1988</td>
    <td></td>
    <td></td>
    <td>СЛ 0120</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1989</td>
    <td></td>
    <td></td>
    <td>СЛ 0200</td>
  </tr>
  <tr>
    <td>Ikarus 280.08</td>
    <td>1975</td>
    <td>1975</td>
    <td>1985</td>
    <td></td>
    <td>1649</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.08</td>
    <td>1975</td>
    <td>1975</td>
    <td>1985</td>
    <td></td>
    <td>1651</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.08</td>
    <td>1975</td>
    <td>1975</td>
    <td>1985</td>
    <td></td>
    <td>1653</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.08</td>
    <td>1975</td>
    <td>1975</td>
    <td>1983</td>
    <td></td>
    <td>1655</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.08</td>
    <td>1975</td>
    <td>1975</td>
    <td>1983</td>
    <td></td>
    <td>1657</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.08</td>
    <td>1975</td>
    <td>1975</td>
    <td>1983</td>
    <td></td>
    <td>1659</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.08</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>1661</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.08</td>
    <td>1975</td>
    <td>1975</td>
    <td>1983</td>
    <td></td>
    <td>1663</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.08</td>
    <td>1975</td>
    <td>1975</td>
    <td>1984</td>
    <td></td>
    <td>1665</td>
    <td>СЛ 0027</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1984</td>
    <td></td>
    <td>1667</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1984</td>
    <td></td>
    <td>1669</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1984</td>
    <td></td>
    <td>1671</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>1673</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>1675</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>1677</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>1679</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>1681</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>1683</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>1685</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1984</td>
    <td></td>
    <td>1687</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1984</td>
    <td></td>
    <td>1689</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1984</td>
    <td></td>
    <td>1691</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1989</td>
    <td></td>
    <td>1693</td>
    <td>СЛ 0158</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1987</td>
    <td></td>
    <td>1695</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1989</td>
    <td></td>
    <td>1697</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1975</td>
    <td>1975</td>
    <td>1984</td>
    <td></td>
    <td>1699</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.08</td>
    <td>1975</td>
    <td>1975</td>
    <td>1988</td>
    <td></td>
    <td>1737-&gt;3244</td>
    <td>АМ 3244</td>
  </tr>
  <tr>
    <td>Ikarus 280.08</td>
    <td>1975</td>
    <td>1975</td>
    <td>1988</td>
    <td></td>
    <td>1739</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1975</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3727</td>
    <td>С 5379 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1975</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3736</td>
    <td>С 5370 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1975</td>
    <td>за части</td>
    <td>07.1992</td>
    <td></td>
    <td>б/н</td>
    <td>без номер</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1975</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3726</td>
    <td>С 5371 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1975</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3730</td>
    <td>С 5368 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1975</td>
    <td>за части</td>
    <td>07.1992</td>
    <td></td>
    <td>б/н</td>
    <td>без номер</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1974</td>
    <td>20.11.1992</td>
    <td>10.02.2015</td>
    <td>30700013002251</td>
    <td>2821-&gt;2657</td>
    <td>СА 2274 AH</td>
  </tr>
  <tr>
    <td>Mercedes-Benz O305</td>
    <td>1974</td>
    <td>20.11.1992</td>
    <td>10.11.2013</td>
    <td>30700013002250</td>
    <td>2825-&gt;2659</td>
    <td>СА 2263 AH</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>1974</td>
    <td>1987</td>
    <td></td>
    <td>3019</td>
    <td>АМ 3019</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>1974</td>
    <td>1987</td>
    <td></td>
    <td>3020</td>
    <td>АМ 3020</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>1974</td>
    <td>1987</td>
    <td></td>
    <td>3021</td>
    <td>АМ 3021</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>1974</td>
    <td>1987</td>
    <td></td>
    <td>3022</td>
    <td>АМ 3022</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>1974</td>
    <td>1987</td>
    <td></td>
    <td>3023</td>
    <td>АМ 3023</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>1974</td>
    <td>1987</td>
    <td></td>
    <td>3024</td>
    <td>АМ 3024</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>1974</td>
    <td>1987</td>
    <td></td>
    <td>3025</td>
    <td>АМ 3025</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>1974</td>
    <td>1987</td>
    <td></td>
    <td>3026</td>
    <td>АМ 3026</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>1974</td>
    <td>1987</td>
    <td></td>
    <td>3027</td>
    <td>АМ 3027</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>1974</td>
    <td>1987</td>
    <td></td>
    <td>3028</td>
    <td>АМ 3028</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>1974</td>
    <td>1987</td>
    <td></td>
    <td>3071</td>
    <td>АМ 3071</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>1974</td>
    <td>1987</td>
    <td></td>
    <td>3072</td>
    <td>АМ 3072</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>1974</td>
    <td>1987</td>
    <td></td>
    <td>3073</td>
    <td>АМ 3073</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>1974</td>
    <td>1987</td>
    <td></td>
    <td>3074</td>
    <td>АМ 3074</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>1974</td>
    <td>1987</td>
    <td></td>
    <td>3075</td>
    <td>АМ 3075</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>1974</td>
    <td>1987</td>
    <td></td>
    <td>3154</td>
    <td>АМ 3154</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>20.08.1974</td>
    <td>1989</td>
    <td></td>
    <td>23-&gt;601</td>
    <td>СА 2889</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>20.08.1974</td>
    <td>1988</td>
    <td></td>
    <td>33-&gt;603</td>
    <td>СА 2839</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>20.08.1974</td>
    <td>1988</td>
    <td></td>
    <td>35-&gt;605</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>20.08.1974</td>
    <td>1989</td>
    <td></td>
    <td>43-&gt;607</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>20.08.1974</td>
    <td>1989</td>
    <td></td>
    <td>61-&gt;609</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>20.08.1974</td>
    <td>1989</td>
    <td></td>
    <td>95-&gt;611</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>20.08.1974</td>
    <td>1989</td>
    <td></td>
    <td>109-&gt;613</td>
    <td>СА 2885</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>20.08.1974</td>
    <td>1989</td>
    <td></td>
    <td>117-&gt;615</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>20.08.1974</td>
    <td>1989</td>
    <td></td>
    <td>1031-&gt;617</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>2</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>4</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>6</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>8</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>10</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>12</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>14</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>16</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>18</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>20</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>22</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>24</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>26</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>28</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>30</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>32</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.10</td>
    <td>1974</td>
    <td>01.12.1974</td>
    <td>1987</td>
    <td></td>
    <td>34</td>
    <td>СК ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.10</td>
    <td>1974</td>
    <td>01.12.1974</td>
    <td>1987</td>
    <td></td>
    <td>36</td>
    <td>СК ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.10</td>
    <td>1974</td>
    <td>01.12.1974</td>
    <td>1987</td>
    <td></td>
    <td>38</td>
    <td>СК ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.10</td>
    <td>1974</td>
    <td>01.12.1974</td>
    <td>1987</td>
    <td></td>
    <td>40</td>
    <td>СК ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.10</td>
    <td>1974</td>
    <td>01.12.1974</td>
    <td>1987</td>
    <td></td>
    <td>42</td>
    <td>СК 0837</td>
  </tr>
  <tr>
    <td>Ikarus 280.10</td>
    <td>1974</td>
    <td>01.12.1974</td>
    <td>1987</td>
    <td></td>
    <td>44</td>
    <td>СК 0929</td>
  </tr>
  <tr>
    <td>Ikarus 280.10</td>
    <td>1974</td>
    <td>01.12.1974</td>
    <td>1987</td>
    <td></td>
    <td>46</td>
    <td>СК ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.10</td>
    <td>1974</td>
    <td>02.1975</td>
    <td>1987</td>
    <td></td>
    <td>48</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.10</td>
    <td>1974</td>
    <td>02.1975</td>
    <td>1986</td>
    <td></td>
    <td>50-&gt;1407</td>
    <td>СЛ 0053</td>
  </tr>
  <tr>
    <td>Ikarus 280.10</td>
    <td>1974</td>
    <td>02.1975</td>
    <td>1987</td>
    <td></td>
    <td>52</td>
    <td>СЛ 0054</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>02.1975</td>
    <td>1987</td>
    <td></td>
    <td>54</td>
    <td>СЛ ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>400</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>402</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>404</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>406</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>408</td>
    <td>С 4813</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>410</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>412</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>414</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>416</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>418</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>420</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>422</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>424</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>426</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>428</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>430</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>432</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>434</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>436</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>438</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>440</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>442</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>444</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>446</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.08.1974</td>
    <td></td>
    <td></td>
    <td>448</td>
    <td>С ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1609</td>
    <td>СК ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1611</td>
    <td>СК ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1613</td>
    <td>СК ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1615</td>
    <td>СК 1097</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1617</td>
    <td>СК ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1619</td>
    <td>СК ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1621</td>
    <td>СК ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1623</td>
    <td>СК ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1625</td>
    <td>СК ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1627</td>
    <td>СК ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1629</td>
    <td>СК 0926</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1631</td>
    <td>СК ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1633</td>
    <td>СК 1009</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1635</td>
    <td>СК ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1637</td>
    <td>СК 1246</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1639</td>
    <td>СК 1231</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1641-&gt;3242</td>
    <td>АМ 3242</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1643-&gt;3243</td>
    <td>АМ 3243</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1645</td>
    <td>СК ????</td>
  </tr>
  <tr>
    <td>Ikarus 280.04</td>
    <td>1974</td>
    <td>01.03.1974</td>
    <td>1987</td>
    <td></td>
    <td>1647</td>
    <td>СК 1293</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1974</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3729</td>
    <td>С 5369 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1974</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3715</td>
    <td>С 5374 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1974</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3713</td>
    <td>С 5313 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1974</td>
    <td>за части</td>
    <td>07.1992</td>
    <td></td>
    <td>б/н</td>
    <td>без номер</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1974</td>
    <td>за части</td>
    <td>07.1992</td>
    <td></td>
    <td>б/н</td>
    <td>без номер</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1973</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3717</td>
    <td>С 5332 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1973</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3719</td>
    <td>С 5341 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1973</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3720</td>
    <td>С 5334 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1973</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3728</td>
    <td>С 5380 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1973</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3714</td>
    <td>С 5340 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1973</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3716</td>
    <td>С 5378 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1973</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3734</td>
    <td>С 5338 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1973</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3735</td>
    <td>С 5367 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1973</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3732</td>
    <td>С 5376 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1973</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3733</td>
    <td>С 5322 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1973</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3723</td>
    <td>С 5331 ТК</td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1980</td>
    <td></td>
    <td>360</td>
    <td></td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1980</td>
    <td></td>
    <td>362</td>
    <td></td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1980</td>
    <td></td>
    <td>364</td>
    <td></td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1980</td>
    <td></td>
    <td>366</td>
    <td></td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1980</td>
    <td></td>
    <td>368</td>
    <td></td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1980</td>
    <td></td>
    <td>370</td>
    <td></td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1980</td>
    <td></td>
    <td>372</td>
    <td>СБ 3936</td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1980</td>
    <td></td>
    <td>374</td>
    <td></td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1980</td>
    <td></td>
    <td>376</td>
    <td></td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1980</td>
    <td></td>
    <td>378</td>
    <td></td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1980</td>
    <td></td>
    <td>380</td>
    <td></td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1980</td>
    <td></td>
    <td>382</td>
    <td>СБ 3717</td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1980</td>
    <td></td>
    <td>384</td>
    <td>СБ 3700</td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1980</td>
    <td></td>
    <td>386</td>
    <td></td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1980</td>
    <td></td>
    <td>388</td>
    <td>СА 3965</td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1981</td>
    <td></td>
    <td>390</td>
    <td></td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1981</td>
    <td></td>
    <td>392</td>
    <td></td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1981</td>
    <td></td>
    <td>394</td>
    <td></td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1981</td>
    <td></td>
    <td>396</td>
    <td></td>
  </tr>
  <tr>
    <td>Ikarus 260.08</td>
    <td>1973</td>
    <td>01.06.1974</td>
    <td>1981</td>
    <td></td>
    <td>398</td>
    <td></td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1972</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3722</td>
    <td>С 5372 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1972</td>
    <td>за части</td>
    <td>07.1992</td>
    <td></td>
    <td>б/н</td>
    <td>без номер</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1972</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3718</td>
    <td>С 5342 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1972</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3725</td>
    <td>С 5344 ТК </td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1972</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3721</td>
    <td>С 5366 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1972</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3712</td>
    <td>С 5375 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1972</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3724</td>
    <td>С 5337 ТК</td>
  </tr>
  <tr>
    <td>Fiat Iveco 421 AL</td>
    <td>1972</td>
    <td>07.1992</td>
    <td>1995</td>
    <td></td>
    <td>3731</td>
    <td>С 5309 ТК</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>СР 0525</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>СР 0526</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>СР 0527</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>1982</td>
    <td></td>
    <td></td>
    <td>СР 2633</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td></td>
    <td></td>
    <td></td>
    <td>СР 2644</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td></td>
    <td></td>
    <td></td>
    <td>СР 2646</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td></td>
    <td></td>
    <td></td>
    <td>СР 2653</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>1982</td>
    <td></td>
    <td>325</td>
    <td>СР 0521</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>1982</td>
    <td></td>
    <td>335</td>
    <td>СР 2636</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>1979</td>
    <td></td>
    <td>615</td>
    <td>СР ????</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>1979</td>
    <td></td>
    <td>616</td>
    <td>СР ????</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>01.07.1974</td>
    <td></td>
    <td>622</td>
    <td>СР ????</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>01.07.1974</td>
    <td></td>
    <td>634</td>
    <td>СР ????</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>01.07.1974</td>
    <td></td>
    <td>648</td>
    <td>СР ????</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>01.07.1974</td>
    <td></td>
    <td>650</td>
    <td>СР ????</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>1981</td>
    <td></td>
    <td>653</td>
    <td>СР ????</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>01.07.1974</td>
    <td></td>
    <td>654</td>
    <td>СР 2652</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>01.07.1974</td>
    <td></td>
    <td>666</td>
    <td>СР ????</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>1981</td>
    <td></td>
    <td>689</td>
    <td>СР 2617</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>01.07.1974</td>
    <td></td>
    <td>690</td>
    <td>СР ????</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>1982</td>
    <td></td>
    <td>740</td>
    <td>СР ????</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>1980</td>
    <td></td>
    <td>767</td>
    <td>СР 2759</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>1980</td>
    <td></td>
    <td>781</td>
    <td>СР 2757</td>
  </tr>
  <tr>
    <td>Ikarus 180.00</td>
    <td>1967</td>
    <td>1967</td>
    <td>1981</td>
    <td></td>
    <td>993</td>
    <td>С&nbsp;&nbsp;3291</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1970</td>
    <td>1970</td>
    <td>1981</td>
    <td></td>
    <td>51</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td>61</td>
    <td>СР ????</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td>145</td>
    <td>СР 3601</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td>207</td>
    <td>СР ????</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1976</td>
    <td></td>
    <td>471</td>
    <td>СБ ????</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td>745</td>
    <td>СА 1335</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td>772</td>
    <td>СР ????</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1976</td>
    <td></td>
    <td>849</td>
    <td>СБ ????</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td>963</td>
    <td>СВ 2345</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>СБ 1719</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>СГ 1348</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>СР 1270</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>СР 1298</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>СР 1537</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>СВ 2817</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>СА 8245</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td>521</td>
    <td>СБ 1592</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO - JELCZ 043</td>
    <td></td>
    <td></td>
    <td>1982</td>
    <td></td>
    <td>83-&gt;Аварийна</td>
    <td>СЛ 0320</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>СГ 1104</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>1981</td>
    <td></td>
    <td>175</td>
    <td>СГ 1107</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>1981</td>
    <td></td>
    <td>177</td>
    <td>СГ 1108</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>1980</td>
    <td></td>
    <td>407</td>
    <td>СР 2262</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>1978</td>
    <td></td>
    <td>954</td>
    <td>СГ ????</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>1978</td>
    <td></td>
    <td>962</td>
    <td>СГ ????</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>1978</td>
    <td></td>
    <td>430</td>
    <td>СГ ????</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>01.07.1974</td>
    <td></td>
    <td>416</td>
    <td>СГ ????</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>01.07.1974</td>
    <td></td>
    <td>422</td>
    <td>СГ ????</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>1980</td>
    <td></td>
    <td>773</td>
    <td>СГ ????</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>1982</td>
    <td></td>
    <td>937</td>
    <td>АД 1504</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>1982</td>
    <td></td>
    <td>3563</td>
    <td>Б&nbsp;&nbsp;3563</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>1997</td>
    <td></td>
    <td>2998-&gt;А-10</td>
    <td>АП 2998</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>1982</td>
    <td></td>
    <td>6</td>
    <td>ТхБ 0006</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td>164</td>
    <td>С 0968</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1979</td>
    <td></td>
    <td>215</td>
    <td>СБ 3645</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>01.07.1974</td>
    <td></td>
    <td>482</td>
    <td>СБ ????</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>01.07.1974</td>
    <td></td>
    <td>490</td>
    <td>СБ ????</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>01.07.1974</td>
    <td></td>
    <td>498</td>
    <td>СБ ????</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td>526</td>
    <td>СБ ????</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td>600</td>
    <td>С 5470</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td>625</td>
    <td>СА 3844</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td>663</td>
    <td>С 0938</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td>674</td>
    <td>СБ ????</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td>704</td>
    <td>СБ 2109</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>01.07.1974</td>
    <td></td>
    <td>856</td>
    <td>СБ ????</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>01.07.1974</td>
    <td></td>
    <td>864</td>
    <td>СБ ????</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>01.07.1974</td>
    <td></td>
    <td>888</td>
    <td>СБ ????</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td>981</td>
    <td>СА 2982</td>
  </tr>
  <tr>
    <td>Чавдар М80</td>
    <td>1968</td>
    <td>1968</td>
    <td>1980</td>
    <td></td>
    <td>1027</td>
    <td>СБ 0964</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1966</td>
    <td>1966</td>
    <td>1976</td>
    <td></td>
    <td>365</td>
    <td>Сфб 2031</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1966</td>
    <td>1966</td>
    <td>1976</td>
    <td></td>
    <td></td>
    <td>СБ 1877</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1966</td>
    <td>1966</td>
    <td>1977</td>
    <td></td>
    <td></td>
    <td>СФ 5488</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1966</td>
    <td>1966</td>
    <td>1978</td>
    <td></td>
    <td>5</td>
    <td>СФ 5497</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1966</td>
    <td>1966</td>
    <td>1975</td>
    <td></td>
    <td>7</td>
    <td>СФ 10323</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1966</td>
    <td>1966</td>
    <td>01.07.1974</td>
    <td></td>
    <td>224</td>
    <td>СГ ????</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1966</td>
    <td>1966</td>
    <td>01.07.1974</td>
    <td></td>
    <td>236</td>
    <td>СГ ????</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1966</td>
    <td>1966</td>
    <td>01.07.1974</td>
    <td></td>
    <td>242</td>
    <td>СГ ????</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1966</td>
    <td>1966</td>
    <td>1975</td>
    <td></td>
    <td>244</td>
    <td>СГ ????</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>1975</td>
    <td></td>
    <td>246</td>
    <td>СФ 0495</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>1980</td>
    <td></td>
    <td>249</td>
    <td>СФ ????</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>01.07.1974</td>
    <td></td>
    <td>252</td>
    <td>СГ ????</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>01.07.1974</td>
    <td></td>
    <td>258</td>
    <td>СГ ????</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>01.07.1974</td>
    <td></td>
    <td>264</td>
    <td>СГ ????</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>1982</td>
    <td></td>
    <td>266-&gt;Аварийна</td>
    <td>СГ ????</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>01.07.1974</td>
    <td></td>
    <td>272</td>
    <td>СГ ????</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>01.07.1974</td>
    <td></td>
    <td>288</td>
    <td>СГ ????</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>1980</td>
    <td></td>
    <td>298</td>
    <td>СГ ????</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td>1965</td>
    <td>1965</td>
    <td>1980</td>
    <td></td>
    <td>736</td>
    <td>СГ 1154</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO LUX</td>
    <td>1965</td>
    <td>1965</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>С&nbsp;&nbsp;1211</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO LUX</td>
    <td>1965</td>
    <td>1965</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>С 1223</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO LUX</td>
    <td>1965</td>
    <td>1965</td>
    <td>1981</td>
    <td></td>
    <td></td>
    <td>С&nbsp;&nbsp;9018</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO LUX</td>
    <td>1965</td>
    <td>1965</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>С&nbsp;&nbsp;9194</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO LUX</td>
    <td>1965</td>
    <td>1965</td>
    <td>1980</td>
    <td></td>
    <td></td>
    <td>СфА 0319</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO LUX</td>
    <td>1965</td>
    <td>1965</td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>СфА 0771</td>
  </tr>
  <tr>
    <td>Skoda 706 RTO</td>
    <td></td>
    <td></td>
    <td>1978</td>
    <td></td>
    <td></td>
    <td>СфА 5293</td>
  </tr>
  <tr>
    <td>Чавдар М 65</td>
    <td>1965</td>
    <td>1965</td>
    <td>01.07.1974</td>
    <td></td>
    <td>20</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Чавдар М 65</td>
    <td>1965</td>
    <td>1965</td>
    <td>01.07.1974</td>
    <td></td>
    <td>32</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Чавдар М 65</td>
    <td>1965</td>
    <td>1965</td>
    <td>01.07.1974</td>
    <td></td>
    <td>92</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Чавдар М 65</td>
    <td>1965</td>
    <td>1965</td>
    <td>01.07.1974</td>
    <td></td>
    <td>100</td>
    <td>СА ????</td>
  </tr>
  <tr>
    <td>Чавдар М 66</td>
    <td>1965</td>
    <td>1965</td>
    <td>01.07.1974</td>
    <td></td>
    <td>120</td>
    <td>СА 2521</td>
  </tr>
  <tr>
    <td>Чавдар М 65</td>
    <td>1965</td>
    <td>1965</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Чавдар М 65</td>
    <td>1965</td>
    <td>1965</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Чавдар М 65</td>
    <td>1965</td>
    <td>1965</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Чавдар М 65</td>
    <td>1965</td>
    <td>1965</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Чавдар М 65</td>
    <td>1965</td>
    <td>1965</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Чавдар М 65</td>
    <td>1965</td>
    <td>1965</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Чавдар М 65</td>
    <td>1965</td>
    <td>1965</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Чавдар М 65</td>
    <td>1965</td>
    <td>1965</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Чавдар М 65</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Лаз</td>
    <td>1949</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Лаз</td>
    <td>1949</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Лаз</td>
    <td>1949</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Лаз</td>
    <td>1949</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Лаз</td>
    <td>1949</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Лаз</td>
    <td>1949</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Лаз</td>
    <td>1949</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Лаз</td>
    <td>1949</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Лаз</td>
    <td>1949</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Лаз</td>
    <td>1949</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Лаз</td>
    <td>1949</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Лаз</td>
    <td>1949</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Лаз</td>
    <td>1949</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Лаз</td>
    <td>1949</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Лаз</td>
    <td>1949</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Mercedes</td>
    <td>1940</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Mercedes</td>
    <td>1940</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Mercedes</td>
    <td>1940</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Mercedes</td>
    <td>1940</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Mercedes</td>
    <td>1940</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Mercedes</td>
    <td>1940</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>MAN</td>
    <td>1940</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>MAN</td>
    <td>1940</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>MAN</td>
    <td>1940</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>MAN</td>
    <td>1940</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>MAN</td>
    <td>1940</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>MAN</td>
    <td>1940</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>MAN</td>
    <td>1940</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>MAN</td>
    <td>1940</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>MAN</td>
    <td>1940</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>MAN</td>
    <td>1940</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Прага NDO</td>
    <td>1935</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Прага NDO</td>
    <td>1935</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Прага NDO</td>
    <td>1935</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Прага NDO</td>
    <td>1935</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Прага NDO</td>
    <td>1935</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Прага NDO</td>
    <td>1935</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Прага NDO</td>
    <td>1935</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Прага NDO</td>
    <td>1935</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Прага NDO</td>
    <td>1935</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Прага NDO</td>
    <td>1935</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</tbody>
</table>
