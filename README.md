

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=sngxpro)](https://github.com/anuraghazra/github-readme-stats)

^_^

#### AutoSyncScript
```
此项目用于定时拉取github上各作者的脚本备份。

使用github action的用户，请善用本项目拉取原作者的脚本到自己这里，

然后引用自己仓库的脚本地址运行ac，

不要给原作者添麻烦！
```

{
            "id": "ency.app.sub",
            "name": "ency 应用订阅",
            "author": "@ency",
            "icon": "https://ftp.bmp.ovh/imgs/2021/05/a49833e49f15dc6b.jpg",
            "repo": "https://github.com/whany98/xixi",
            "apps": [{
            "id": "PushBoxjsTask",
            "name": "V2pTask",
            "keys": ["v2purl", "v2token", "v2pblacklist"],
    "settings": [{
        "id": "v2ptaskupdate",
        "name": "V2P上传任务",
        "val": false,
        "type": "boolean",
        "desc": "打开才会上传定时任务,用来刚开始使用的时候"
      },
      {
        "id": "jdtaskupdate",
        "name": "京东上传任务",
        "val": false,
        "type": "boolean",
        "desc": "用来打开上传定时任务包含京东系列"
      },
      {
        "id": "v2pblacklist",
        "name": "上传黑名单",
        "val": "",
        "type": "textarea",
        "desc": "删除你要上传的任务对象"
      },
      {
        "id": "v2purl",
        "name": "主页地址",
        "val": "",
        "type": "text",
        "desc": "请到设置查询,例子:http://192.168.1.102:12521"
      },
      {
        "id": "v2token",
        "name": "WEBHOOK TOKEN",
        "val": "",
        "type": "text",
        "desc": "请到设置查询,例子:a8c259b2-67fe-D-7bfdf1f55cb3"
      }
    ],
    "author": "@cenbomin",
    "repo": ["https://raw.githubusercontent.com/CenBoMin/GithubSync"],
    "script": "https://raw.githubusercontent.com/CenBoMin/GithubSync/main/ELECV2PJS/PushTask_elecV2p.js",
    "icons": ["https://raw.githubusercontent.com/Ariszy/Private-Script/master/img/elecv2p-mini.png",     
     "https://raw.githubusercontent.com/Ariszy/Private-Script/master/img/elecv2p.png"]
  },

  {
    "id": "PushBoxjsCookie",
    "name": "V2pCookie",
    "keys": ["v2purl", "v2token"],
    "settings": [{
        "id": "v2pcookieupdate",
        "name": "V2P上传任务",
        "val": false,
        "type": "boolean",
        "desc": "打开才会上传cookie,用来刚开始使用的时候。"
      }, {
        "id": "v2purl",
        "name": "主页地址",
        "val": "",
        "type": "text",
        "desc": "请到设置查询,例子:http://192.168.1.102:12521"
      },
      {
        "id": "v2token",
        "name": "WEBHOOK TOKEN",
        "val": "",
        "type": "text",
        "desc": "请到设置查询,例子:a8c259b2-67fe-D-7bfdf1f55cb3"
      }
    ],
    "author": "@cenbomin",
    "repo": ["https://raw.githubusercontent.com/CenBoMin/GithubSync"],
    "script": "https://raw.githubusercontent.com/CenBoMin/GithubSync/main/ELECV2PJS/PushBoxjsCookie_elecV2p.js",
    "icons": ["https://raw.githubusercontent.com/Ariszy/Private-Script/master/img/elecv2p-mini.png", "https://raw.githubusercontent.com/Ariszy/Private-Script/master/img/elecv2p.png"]
  },
 
  {
    "id": "chonghauapp",
    "name": "加点葱花",
    "keys": ["uid", "chgetbody_video", "chgetbody_share", "chgetbody_timered", "chgetbody_taskcenter", "chgetbody_sharereward", "logbutton", "tzbutton", "chgetbody_video_index", "cashbody", "cashkey", "callbackkey", "callbackurl"],
    "settings": [{
        "id": "chgetbody_video",
        "name": "请求body",
        "val": "",
        "type": "textarea",
        "autoGrow": false,
        "rows": 1,
        "desc": "看视频，倒计时转一圈显示金币到账。。建议看5篇视频,获取请求包"
      },
      {
        "id": "uid",
        "name": "自己的邀请码",
        "val": "",
        "type": "text",
        "desc": "输入才可查看账户金币明细"
      },
      {
        "id": "chgetbody_video_index",
        "name": "上次执行位置",
        "val": "",
        "type": "textarea",
        "autoGrow": false,
        "rows": 1,
        "desc": "记录上次执行的位置，可以控制从第几个body开始执行"
      },
      {
        "id": "logbutton",
        "name": "日志开关",
        "val": "",
        "type": "number",
        "desc": "0为关闭日志，1为开启，默认为关闭日志"
      },
      {
        "id": "tzbutton",
        "name": "安静开关",
        "val": "",
        "type": "number",
        "desc": "0为关闭通知，1为所有通知，默认为关闭通知"
      }
    ],
    "author": "@cenbomin",
    "repo": ["https://raw.githubusercontent.com/CenBoMin/GithubSync"],
    "script": "https://raw.githubusercontent.com/CenBoMin/GithubSync/main/CONGHUA/chonghua.js",
    "icons": ["https://raw.githubusercontent.com/ChuheGit/1/main/QuantumultX/Gallery/API-Icon/AutoRead.png",
      "https://raw.githubusercontent.com/58xinian/icon/master/chsp.png"
    ]
   }, 

   {
    "id": "txstockapp",
    "name": "自选羊毛股",
    "keys": ["signheader", "signkey", "taskheader", "taskkey", "userheader", "userkey", "wxtaskkey", "cash",     "cashheader"],
    "settings": [{
      "id": "cash",
      "name": "提现开关:0,不自动提现;1，提现1元；5，提现5元",
      "val": "",
      "type": "number",
      "desc": "默认为0,不自动提现"
    }],
    "author": "@cenbomin",
    "repo": ["https://raw.githubusercontent.com/CenBoMin/GithubSync"],
    "script": "https://raw.githubusercontent.com/CenBoMin/GithubSync/main/TXSTOCK/txstockqx.js",
    "icons": ["https://raw.githubusercontent.com/CenBoMin/GithubSync/main/TXSTOCK/txzxg.png",     "https://raw.githubusercontent.com/CenBoMin/GithubSync/main/TXSTOCK/txzxg.png"]
    },

    {
            "id": "rl",
            "name": "燃旅视频",
            "keys": ["rlurl", "rlurl2", "rlurl3", "rlurl4", "rlurl5", "rlurl6", "rlurl7", "rlurl8"],
            "author": "@ziye",
            "settings": [{
                    "id": "rlSuffix",
                    "name": "当前账号",
                    "val": "1",
                    "type": "number",
                    "desc": "当前抓取ck记录的账号序号，如：1、2、3、"
                },
                {
                    "id": "rlCount",
                    "name": "账号个数",
                    "val": "1",
                    "type": "number",
                    "desc": "指定任务最多跑几个账号，根据抓取的账号数据个数来设值"
                },
                {
                    "id": "rlXH",
                    "name": "循环获取CK",
                    "val": "0",
                    "type": "number",
                    "desc": "0关闭 1开启,默认关闭"
                }, 
                {
                    "id": "rlXYZ",
                    "name": "执行概率",
                    "val": "100",
                    "type": "number",
                    "desc": "0不执行 可设置0-100,默认百分百"
                },
                {
                    "id": "rlnotifyttt",
                    "name": "推送控制",
                    "val": "1",
                    "type": "number",
                    "desc": "0关闭，1推送,默认12点以及23点推送"
                },
                {
                    "id": "rlnotifyInterval",
                    "name": "通知控制",
                    "val": "2",
                    "type": "number",
                    "desc": "0关闭，1为 所有通知，2为 12，23 点通知，3为 6，12，18，23 点通知 "
                },
                {
                    "id": "rlMinutes",
                    "name": "推送-通知 分钟控制",
                    "val": "10",
                    "type": "number",
                    "desc": "推送以及通知控制在什么分钟段，可设置0-59,默认0到10"
                }],
            "repo": "https://cdn.jsdelivr.net/gh/ziye888/JavaScript@main/Task/rl.js",
            "icons": ["https://cdn.jsdelivr.net/gh/ziye888/JavaScript@main/Task/rl.png", "https://cdn.jsdelivr.net/gh/ziye888/JavaScript@main/Task/rl.png"],
            "script": "https://cdn.jsdelivr.net/gh/ziye888/JavaScript@main/Task/rl.js"
        },

       {
            "id": "dsj",
            "name": "电视家APP",
            "keys": ["dsjheader","dsjheader2","dsjheader3","dsjheader4","dsjheader5","dsjheader6","dsjheader7","dsjheader8"],
            "author": "@ziye",
            "settings": [{
                    "id": "dsjSuffix",
                    "name": "当前账号",
                    "val": "1",
                    "type": "number",
                    "desc": "当前抓取ck记录的账号序号，如：1、2、3、"
                },
                {
                    "id": "dsjCount",
                    "name": "账号个数",
                    "val": "1",
                    "type": "number",
                    "desc": "指定任务最多跑几个账号，根据抓取的账号数据个数来设值"
                },
                {
                    "id": "dsjXH",
                    "name": "循环获取CK",
                    "val": "0",
                    "type": "number",
                    "desc": "0关闭 1开启,默认关闭"
                }, 
                {
                    "id": "dsjXYZ",
                    "name": "执行概率",
                    "val": "100",
                    "type": "number",
                    "desc": "0不执行 可设置0-100,默认百分百"
                }, 
                {
                    "id": "dsjTXTX",
                    "name": "余额提醒",
                    "val": "0",
                    "type": "number",
                    "desc": "0不提醒 可设置0,5,10,20,25,30,50,100"
                },
                {
                    "id": "dsjnotifyttt",
                    "name": "推送控制",
                    "val": "1",
                    "type": "number",
                    "desc": "0关闭，1推送,默认12点以及23点推送"
                },
                {
                    "id": "dsjnotifyInterval",
                    "name": "通知控制",
                    "val": "2",
                    "type": "number",
                    "desc": "0关闭，1为 所有通知，2为 12，23 点通知，3为 6，12，18，23 点通知 "
                },
                {
                    "id": "dsjMinutes",
                    "name": "推送-通知 分钟控制",
                    "val": "10",
                    "type": "number",
                    "desc": "推送以及通知控制在什么分钟段，可设置0-59,默认0到10"
                }],
            "repo": "https://cdn.jsdelivr.net/gh/ziye888/JavaScript@main/Task/dsj.js",
            "icons": ["https://cdn.jsdelivr.net/gh/ziye888/JavaScript@main/Task/dsj.png", "https://cdn.jsdelivr.net/gh/ziye888/JavaScript@main/Task/dsj.png"],
            "script": "https://cdn.jsdelivr.net/gh/ziye888/JavaScript@main/Task/dsj.js"
        },

        {
      "author": "@sunert", 
      "descs_html": [
        "<h4 align=\"center\">获取Cookie以及脚本配置请查看< a href= "https://github.com/Sunert/Script/raw/master/TaskConf/youth/readme.md\">配置说明</ a></h4>", 
        "<br />", 
        "<p>其中<font color='#FF0000',font-weight: bold>zq_nick、zqcash</font>和<font color='#FF0000',font-weight: bold>zqcard</font>为昵称、提现金额和早起打卡开关，无需另外获取，相关项设置后自动生成，cashurl_zq和cashbody_zq为提现请求，获取后方可自动提现，可选</p >"
      ], 
      "keys": [
        "zq_nick", 
        "youthheader_zq", 
        "read_zq", 
        "readtime_zq", 
        "cashurl_zq", 
        "cashbody_zq", 
        "zqcash", 
        "zqcard"
      ], 
      "repo": "https://github.com/Sunert/Script/blob/master/Task/youth.js", 
      "id": "youth", 
      "script": "https://raw.githubusercontent.com/Sunert/Script/master/Task/youth.js", 
      "settings": [
        {
          "id": "zqcard", 
          "val": "false", 
          "name": "打卡赚钱", 
          "type": "boolean", 
          "desc": "每日打卡报名及早起打卡"
        }, 
        {
          "id": "zqtime", 
          "val": "05", 
          "name": "打卡时间", 
          "type": "number", 
          "desc": "每日早起打卡时间"
        }, 
        {
          "id": "delay_rotary_zq", 
          "val": "10", 
          "name": "转盘时间间隔", 
          "type": "number", 
          "desc": "间隔时间设置，如1秒填1即可"
        }, 
        {
          "id": "notifytimes", 
          "val": "", 
          "name": "通知频率 (点击查看设置说明)", 
          "type": "number", 
          "desc": "设定通知频率，前三次为全部通知，之后转盘次数/设定频率整除时通知，如设置0为无通知，设置1为全部通知，设置其他数可整除余0时通知，默认值50"
        }, 
        {
          "id": "zqcash", 
          "val": "30", 
          "name": "提现金额", 
          "type": "radios", 
          "desc": "自动提现金额需和获取提现请求保持一致", 
          "items": [
            {
              "key": "10", 
              "label": "10元"
            }, 
            {
              "key": "30", 
              "label": "30元"
            }, 
            {
              "key": "100", 
              "label": "100元"
            }
          ]
        }
      ], 
      "name": "中青看点", 
      "icons": [
        "https://cdn.jsdelivr.net/gh/Orz-3/mini@master/Alpha/youth.png", 
        "https://cdn.jsdelivr.net/gh/Orz-3/mini@master/Color/youth.png"
      ]
    }, 
    {
      "author": "@sunert", 
      "keys": [
        "youth_start", 
        "youth_look"
      ], 
      "repo": "https://github.com/Sunert/Script/blob/master/Task/youth_gain.js", 
      "id": "youthGain", 
      "script": "https://raw.githubusercontent.com/Sunert/Script/master/Task/youth_gain.js", 
      "name": "中青浏览赚&看看赚", 
      "icons": [
        "https://cdn.jsdelivr.net/gh/Orz-3/mini@master/Alpha/youth.png", 
        "https://cdn.jsdelivr.net/gh/Orz-3/mini@master/Color/youth.png"
      ]
    }, 
    {
      "author": "@sunert", 
      "keys": [
        "youth_autoread", 
        "autotime_zq"
      ], 
      "settings": [
      {
          "id": "youth_cut", 
          "val": false, 
          "name": "缩减请求", 
          "type": "boolean", 
          "desc": "自动删除收益为0或者错误的阅读请求，使用完后请立即关闭，避免清空阅读请求"
        }
      ],
      "repo": "https://github.com/Sunert/Script/blob/master/Task/Youth_Read.js", 
      "id": "youthRead", 
      "script": "https://raw.githubusercontent.com/Sunert/Script/master/Task/Youth_Read.js", 
      "name": "中青自动阅读", 
      "icons": [
        "https://cdn.jsdelivr.net/gh/Orz-3/mini@master/Alpha/youth.png", 
        "https://cdn.jsdelivr.net/gh/Orz-3/mini@master/Color/youth.png"
      ]
    },
 
    {
      "author": "@sunert", 
      "keys": [
        "jukan_body", 
        "jukan_name"
      ], 
      "repo": "https://github.com/Sunert/Script/blob/master/Task/jukan.js", 
      "id": "jukan", 
      "script": "https://raw.githubusercontent.com/Sunert/Script/master/Task/jukan.js", 
      "settings": [
        {
          "id": "jukan_out", 
          "val": false, 
          "name": "自动提现", 
          "type": "boolean", 
          "desc": "自动提现开关，请填入提现金额及微信绑定实名，默认关闭"
        }, 
        {
          "id": "jukan_cash", 
          "val": "", 
          "name": "提现金额", 
          "type": "radios", 
          "items": [
            {
              "key": "3", 
              "label": "3元(邀请专享)"
            }, 
            {
              "key": "10", 
              "label": "10元(阅读/邀请)"
            }, 
            {
              "key": "30", 
              "label": "30元(无条件)"
            }, 
            {
              "key": "50", 
              "label": "50元(无条件)"
            }, 
            {
              "key": "100", 
              "label": "100元(无条件)"
            }
          ]
        }, 
        {
          "id": "jukan_name", 
          "placeholder": "填入微信真实姓名", 
          "val": "", 
          "name": "微信真实姓名", 
          "type": "text"
        }
      ], 
      "name": "聚看点", 
      "icons": [
        "https://cdn.jsdelivr.net/gh/Sunert/Profiles@master/QuantumultX/Rules/Images/icon/jukan_mini.png", 
        "https://cdn.jsdelivr.net/gh/Sunert/Profiles@master/QuantumultX/Rules/Images/icon/jukan.png"
      ]
    }, 
    {
            "id": "fhxz",
            "name": "富豪小镇",
            "keys": ["fhxzurl","fhxzhd","fhxzurl2","fhxzhd2","fhxzurl3","fhxzhd3","fhxzurl4","fhxzhd4","fhxzurl5","fhxzhd5","fhxzurl6"],
            "author": "@ency",
            "settings": [{
            "id": "fhxzstatus",
            "name": "当前账号",
            "val": "1",
            "type": "number",
            "desc": "当前账号对应"
    },
    {
            "id": "fhxzcount",
            "name": "账号个数",
            "val": "1",
            "type": "number",
            "desc": "需要几个账号，数字为几"
    }],
            "repo": "",
            "icons": ["", ""],
            "script": ""
    },

    {
    "id": "days",
    "name": "28days",
    "keys": ["daysheader","daysbody","daysheader2","daysbody2","daysheader3","daysbody3","daysheader4","daysbody4","daysheader5","daysbody5"],
    "author": "@tom",
    "settings": [{
      "id": "daysSuffix",
      "name": "当前账号",
      "val": "1",
      "type": "number",
      "desc": "当前抓取ck记录的账号序号，如：1、2、3、4"
    }, {
      "id": "daysCount",
      "name": "账号个数",
      "val": "1",
      "type": "number",
      "desc": "指定任务最多跑几个账号，根据抓取的账号数据个数来设值"
    }, {
      "id": "daysXH",
      "name": "循环获取ck",
      "val": "0",
      "type": "number",
      "desc": "0关闭，1打开，默认关闭"
    }, {
      "id": "daysTXTX",
      "name": "txtx",
      "val": "0",
      "type": "number",
      "desc": "0关闭，1打开，默认关闭"
    }, {
      "id": "daysSC",
      "name": "sc",
      "val": "0",
      "type": "number",
      "desc": "0关闭，1打开，默认关闭"
    }, {
      "id": "daysnotifyttt",
      "name": "推送控制",
      "val": "1",
      "type": "number",
      "desc": "0关闭，1推送,默认12点以及23点推送"
    }, {
      "id": "daysnotifyInterval",
      "name": "通知控制",
      "val": "2",
      "type": "number",
      "desc": "0关闭，1为 所有通知，2为 12，23 点通知，3为 6，12，18，23 点通知"
    }, {
      "id": "daysMinutes",
      "name": "推送-通知 分钟控制",
      "val": "10",
      "type": "number",
      "desc": "推送以及通知控制在什么分钟段，可设置0-59,默认0到10"
    }],
    "repo": "https://raw.githubusercontent.com/xl2101200/-/main/days.js",
    "icons": ["https://raw.githubusercontent.com/xl2101200/-/main/tom/tom.jpg", "https://raw.githubusercontent.com/xl2101200/-/main/tom/tom.jpg"],
    "script": "https://raw.githubusercontent.com/xl2101200/-/main/days.js"
    },
    {
    "id": "jscfz",
    "name": "嘉实宠粉站",
    "keys": ["jscfzheader","jscfzheader2","jscfzheader3","jscfzheader4","jscfzheader5","jscfzheader6","jscfzheader7","jscfzheader8"],
    "author": "@tom",
    "settings": [{
      "id": "jscfzSuffix",
      "name": "当前账号",
      "val": "1",
      "type": "number",
      "desc": "当前抓取ck记录的账号序号，如：1、2、3、4"
    }, {
      "id": "jscfzCount",
      "name": "账号个数",
      "val": "1",
      "type": "number",
      "desc": "指定任务最多跑几个账号，根据抓取的账号数据个数来设值"
    }, {
      "id": "jscfzXH",
      "name": "循环获取ck",
      "val": "0",
      "type": "number",
      "desc": "0关闭，1打开，默认关闭"
    }, {
      "id": "jscfzTXTX",
      "name": "txtx",
      "val": "0",
      "type": "number",
      "desc": "0关闭，1打开，默认关闭"
    }, {
      "id": "jscfzSC",
      "name": "sc",
      "val": "0",
      "type": "number",
      "desc": "0关闭，1打开，默认关闭"
    }, {
      "id": "jscfznotifyttt",
      "name": "推送控制",
      "val": "1",
      "type": "number",
      "desc": "0关闭，1推送,默认12点以及23点推送"
    }, {
      "id": "jscfznotifyInterval",
      "name": "通知控制",
      "val": "2",
      "type": "number",
      "desc": "0关闭，1为 所有通知，2为 12，23 点通知，3为 6，12，18，23 点通知"
    }, {
      "id": "jscfzMinutes",
      "name": "推送-通知 分钟控制",
      "val": "10",
      "type": "number",
      "desc": "推送以及通知控制在什么分钟段，可设置0-59,默认0到10"
    }],
    "repo": "https://raw.githubusercontent.com/xl2101200/-/main/jscfz.js",
    "icons": ["https://raw.githubusercontent.com/xl2101200/-/main/tom/tom.jpg", "https://raw.githubusercontent.com/xl2101200/-/main/tom/tom.jpg"],
    "script": "https://raw.githubusercontent.com/xl2101200/-/main/jscfz.js"
    },

    {
      "id": "jztt",
  "name": "九章头条",
  "keys": ["jztturl", "jztturl2", "jztturl3", "jztturl4", "jztturl5", "jztturl6", "jztturl7", "jztturl8", "jztturl9", "jztturl10", "jztturl11", "jztturl12", "jztturl13", "jztturl14", "jztturl15", "jztturl16", "jztturl17", "jztturl18", "jztturl19", "jztturl20"],
  "author": "@tom",
  "settings": [{
    "id": "jzttSuffix",
    "name": "当前账号",
    "val": "1",
    "type": "number",
    "desc": "当前抓取ck记录的账号序号，如：1、2、3、4"
  }, {
    "id": "jzttCount",
    "name": "账号个数",
    "val": "1",
    "type": "number",
    "desc": "指定任务最多跑几个账号，根据抓取的账号数据个数来设值"
  }, {
    "id": "jzttXH",
    "name": "循环获取ck",
    "val": "0",
    "type": "number",
    "desc": "0关闭，1打开，默认关闭"
  }, {
    "id": "jzttTXTX",
    "name": "txtx",
    "val": "0",
    "type": "number",
    "desc": "0关闭，1打开，默认关闭"
  }, {
    "id": "jzttSC",
    "name": "sc",
    "val": "0",
    "type": "number",
    "desc": "0关闭，1打开，默认关闭"
  }, {
    "id": "jzttnotifyttt",
    "name": "推送控制",
    "val": "1",
    "type": "number",
    "desc": "0关闭，1推送,默认12点以及23点推送"
  }, {
    "id": "jzttnotifyInterval",
    "name": "通知控制",
    "val": "2",
    "type": "number",
    "desc": "0关闭，1为 所有通知，2为 12，23 点通知，3为 6，12，18，23 点通知"
  }, {
    "id": "jzttMinutes",
    "name": "推送-通知 分钟控制",
    "val": "10",
    "type": "number",
    "desc": "推送以及通知控制在什么分钟段，可设置0-59,默认0到10"
  }],
                        "repo": "https://raw.githubusercontent.com/xl2101200/-/main/jztt.js",
                            "icons": ["https://raw.githubusercontent.com/xl2101200/-/main/tom/tom.jpg", "https://raw.githubusercontent.com/xl2101200/-/main/tom/tom.jpg"],
                                "script": "https://raw.githubusercontent.com/xl2101200/-/main/jztt.js"
   },

   {
    "id": "kkd",
    "name": "快看点",
    "keys": ["kkdheader", "kkdcookie","kkdsign", "kkdheader2", "kkdcookie2","kkdsign2", "kkdheader3", "kkdcookie3","kkdsign3", "kkdheader4", "kkdcookie4","kkdsign4", "kkdheader5", "kkdcookie5","kkdsign5", "kkdheader6", "kkdcookie6","kkdsign6"],
    "author": "@Ariszy",
    "settings": [{
            "id": "tz",
            "name": "静默运行",
            "val": "1",
            "type": "number",
            "desc": "0为不通知，1为全部通知"
        },
      {
        "id": "kkdsetting",
        "name": "当前账号",
        "val": "1",
        "type": "number",
        "desc": "当前账号对应"
      },
      {
        "id": "kkdcount",
        "name": "账号个数",
        "val": "1",
        "type": "number",
        "desc": "需要几个账号，数字为几"
      }],
    "repo": "https://github.com/Ariszy/Private-Script/blob/master/Scripts/kkd.js",
    "icons": ["https://raw.githubusercontent.com/Ariszy/Private-Script/master/img/kkd-mini.png", "https://raw.githubusercontent.com/Ariszy/Private-Script/master/img/kkd.png"],
    "script": "https://raw.githubusercontent.com/Ariszy/Private-Script/master/Scripts/kkd.js"
      }
]
}
