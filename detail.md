#### gp detail

[test url](view-source:https://play.google.com/store/apps/details?id=com.google.android.youtube)

##### 1.1 find all key
[src](https://github.com/facundoolano/google-play-scraper/blob/dev/lib/app.js#L47:25)

Some have speculated that the id is the only identifier that returns the data 
```js
var AF_initDataKeys = ["ds:0","ds:1","ds:2","ds:3","ds:4","ds:5","ds:6","ds:7","ds:8","ds:9","ds:10","ds:11","ds:12","ds:13","ds:14","ds:15","ds:16"]
; var AF_dataServiceRequests = {'ds:0' : {id: 1.2055667E8 ,request:[1]
},'ds:1' : {id: 1.31330917E8 ,request:[]
},'ds:2' : {id: 1.29152375E8 ,request:[]
},'ds:3' : {id: 1.84915516E8 ,request:[["com.google.android.youtube",7]
]
},'ds:4' : {id: 1.59150235E8 ,request:[["com.google.android.youtube",7]
,2]
},'ds:5' : {id: 1.39809457E8 ,request:[null,["com.google.android.youtube",7]
]
},'ds:6' : {id: 1.42707228E8 ,request:[["com.google.android.youtube",7]
]
},'ds:7' : {id: 1.63762857E8 ,request:[[null,["com.google.android.youtube",7]
]
]
},'ds:8' : {id: 1.62435799E8 ,request:[null,null,[null,[[1,[2]
]
,true,null,[4,8,11,1,9,10]
]
,["com.google.android.youtube",7]
]
]
},'ds:9' : {id: 1.62435799E8 ,request:[null,null,[null,[[1,[5]
]
,true,null,[4,8,11,1,9,10]
]
,["com.google.android.youtube",7]
]
,true]
},'ds:10' : {id: 1.4425375E8 ,request:[["com.google.android.youtube",7]
]
},'ds:11' : {id: 1.52841326E8 ,request:[[null,["com.google.android.youtube",7]
]
]
},'ds:12' : {id: 1.49598938E8 ,request:[["com.google.android.youtube",7]
]
},'ds:13' : {id: 1.47043747E8 ,request:[[null,["com.google.android.youtube",7]
,[true]
]
]
},'ds:14' : {id: 1.36880256E8 ,request:[null,null,[2,null,[40]
]
,["com.google.android.youtube",7]
]
},'ds:15' : {id: 1.47043747E8 ,request:[[null,["com.google.android.youtube",7]
]
]
},'ds:16' : {id: 1.30982371E8 ,request:[]
}}; 
```
![findTheKey](https://raw.githubusercontent.com/huoyinghui/static/master/gp_deail01.jpg)


##### 1.2 find Value by key
![value](https://raw.githubusercontent.com/huoyinghui/static/master/gp_detail02.jpg)

##### 1.3 get detail by mapping 
