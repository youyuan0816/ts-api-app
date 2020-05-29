# ts-api-app

参照[AcrGIS官网示例](https://developers.arcgis.com/javascript/latest/guide/typescript-setup/ )搭建的typescript开发环境，用以写一些简单入门的WebGIS demo。

## 环境准备

+ 安装typescript ``` npm install -g typescript```

## 目录结构

```
ts-api-app
├── app
│   ├──  utils (工具类)
│   │      ├──  TianDiTuLayer.ts
│   │      └──  ...
│   └──  main.ts (当前装载的demo)
├── demo (demo列表)
│   ├──  01.HellowWorld.ts
│   └──  ...
├── node_modules (依赖)
├── .gitattributes (git配置)
├── .gitignore (git忽略配置)
├── index.html (入口文件)
├── LICENSE (许可)
├── package.json (包管理)
└── tsconfig (ts配置)
```

## 安装

~~~ shell
git clone https://github.com/GeoDaoyu/ts-api-app.git
cd ts-api-app
npm install
~~~

## 运行启动

~~~ shell
cd ts-api-app
tsc -w
~~~

## 检索

列表提供检索功能，可检索感兴趣的关键字，也可通过bilibili BV号观看对应视频。

| FileName                  | Keyword                                                      | BV           |
| ------------------------- | ------------------------------------------------------------ | ------------ |
| 01.HelloWorld             | Map,MapView                                                  | [BV1JE411g7Wm](https://www.bilibili.com/video/BV1JE411g7Wm) |
| 02.Basemap-baseLayers     | Basemap,TileLayer                                            | [BV147411f7rs](https://www.bilibili.com/video/BV147411f7rs) |
| 03.Basemap-tianditu-4326  | SpatialReference,WebTileLayer,<br />TileInfo,天地图          | [BV1y7411R7cS](https://www.bilibili.com/video/BV1y7411R7cS) |
| 04.Basemap-tianditu-3857  | SpatialReference,WebTileLayer,<br />TileInfo,天地图          | [BV1y7411R7cS](https://www.bilibili.com/video/BV1y7411R7cS) |
| 05.BasemapToggle          | BasemapToggle                                                | [BV1dg4y1b7Xg](https://www.bilibili.com/video/BV1dg4y1b7Xg) |
| 06.BasemapToggleViewModel | BasemapToggleViewModel                                       | [BV1eZ4y1j7Se](https://www.bilibili.com/video/BV1eZ4y1j7Se) |
| 07.BasemapGallery         | Basemap,BasemapGallery,<br />BasemapGalleryViewModel,<br />LocalBasemapsSource | [BV1r5411471d](https://www.bilibili.com/video/BV1r5411471d) |
| 08.TianDiTuLayer          | WebTileLayer,天地图                                          | [BV1st4y1U7VB](https://www.bilibili.com/video/BV1st4y1U7VB) |
| 09.BasemapLayerList       | BasemapLayerList,GroupLayer                                  | [BV1LT4y1G7x9](https://www.bilibili.com/video/BV1LT4y1G7x9) |
| 10.LayerList              | LayerList,MapImageLayer,GroupLayer                           | [BV1Dt4y117KS](https://www.bilibili.com/video/BV1Dt4y117KS) |
| 11.FeatureLayer           | FeatureLayer                                                 | [BV1dK4y1475e](https://www.bilibili.com/video/BV1dK4y1475e) |
| 12.Graphic                | Graphic,Point,Polyline,Polygon                               | [BV14Z4y1p76Y](https://www.bilibili.com/video/BV14Z4y1p76Y) |
| 13.RailwayLine            | Graphic,Polyline,SimpleLineSymbol                            | [BV1mz411v7Kj](https://www.bilibili.com/video/BV1mz411v7Kj) |
| 14.VectorTileLayer        | VectorTileLayer                                              |              |
|                           |                                                              |              |

## 后续计划

+ import react
+ Swipe
+ draw
+ measurement
