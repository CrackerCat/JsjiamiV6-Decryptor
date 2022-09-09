# JsjiamiV6 解密工具

* **简易** [`JsjiamiV6`](https://www.jsjiami.com/) 解密工具。
* **完全** 使用 `NodeJs` 开发。
* **无需** 依赖第三方模块。

## 远程仓库

> 仓库总是由 [![GitHub](https://img.shields.io/badge/GitHub-181717?style=plastic&logo=Github)](https://github.com/)
> 同步至 [![Gitee](https://img.shields.io/badge/Gitee-C71D23?style=plastic&logo=Gitee)](https://gitee.com/) ，同步可能会有延迟。

[![JsjiamiV6-Decryptor - GitHub](https://img.shields.io/badge/GitHub-JsjiamiV6--Decryptor-white?logo=Github&labelColor=181717)](https://github.com/NXY666/JsjiamiV6-Decryptor.git)<br>
[![JsjiamiV6-Decryptor - Gitee](https://img.shields.io/badge/Gitee-JsjiamiV6--Decryptor-white?logo=Gitee&labelColor=C71D23)](https://gitee.com/NXY666/JsjiamiV6-Decryptor.git)

## 解密效果

<details><summary>源代码</summary>

```javascript
function cancelMacWithUserNameAndMac(userId, userMac, trid) {
	var test = confirm("关闭无感认证后,只能在设备本机上再次开启!");
	if (test) {
		AuthInterFace.cancelMacWithUserNameAndMac(userId, userMac, function (data) {
			if (data.result == 'success') {
				//$("#"+trid).hide();
				//$("#autoMacNumTip").html($("#autoMacNumTip").html()-1);
				var userIndex = getQueryStringByName("userIndex");
				AuthInterFace.freshOnlineUserInfo(userIndex, function (freshOnline) {
					getTime = 1;
					fillData();
				});
			} else {
				alert(data.message);
			}
		});
	}
}
```

</details> 
<details><summary>加密后</summary>

> 已省略全局解密函数

> 为方便对比已进行格式化处理

```javascript
function cancelMacWithUserNameAndMac(_0x1437f8, _0x17c421, _0x18daca) {
	var _0x18d784 = {
		'OGRic': '4|2|6|8|0|5|7|3|9|1',
		'AAvHe': function (_0x4a9629, _0x140a6c) {
			return _0x4a9629(_0x140a6c);
		},
		'wIUwe': 'margin-left',
		'TQJfu': '#loginFrameLogofood_hk_2',
		'Ussjm': function (_0x3a631e, _0x5a538a) {
			return _0x3a631e - _0x5a538a;
		},
		'mwhyn': function (_0x5c1515, _0x3e12d0) {
			return _0x5c1515 * _0x3e12d0;
		},
		'eMmnc': '#hk_margin_left_1',
		'pROLs': _0x64f0('9c5', 'DWlJ'),
		'RtPyd': function (_0x1a2925, _0x3178e2) {
			return _0x1a2925(_0x3178e2);
		},
		'ktmyn': _0x64f0('9c6', 'NMy2'),
		'gxaAs': 'width',
		'QzLeH': function (_0x52c760, _0x2740a1) {
			return _0x52c760(_0x2740a1);
		},
		'MhTAi': _0x64f0('9c7', '*6xD'),
		'FkPFD': '#leftId',
		'izkEP': _0x64f0('9c8', 'a5h*'),
		'qjdIA': function (_0x2af297, _0xb650bb) {
			return _0x2af297 * _0xb650bb;
		},
		'feKqI': function (_0x1f7f78, _0x596751) {
			return _0x1f7f78 === _0x596751;
		},
		'hmFcx': 'yhlbV',
		'lNkRh': function (_0x16de55) {
			return _0x16de55();
		},
		'mGvzI': _0x64f0('9c9', 'hSvn'),
		'mjXUQ': function (_0x112f06, _0x404547) {
			return _0x112f06 - _0x404547;
		},
		'dKWSL': function (_0x5dba1c, _0x2b83a9) {
			return _0x5dba1c(_0x2b83a9);
		},
		'oOHzr': function (_0x3e2c53, _0x4c0c40) {
			return _0x3e2c53 - _0x4c0c40;
		},
		'KnyVW': function (_0x1a0714, _0x336008) {
			return _0x1a0714(_0x336008);
		},
		'oJrGK': function (_0x3f8456, _0x1ddba4) {
			return _0x3f8456 / _0x1ddba4;
		},
		'hQFPI': function (_0xd930d9, _0x1db4bd) {
			return _0xd930d9 - _0x1db4bd;
		},
		'EZHrV': function (_0x5ab773, _0x3893c7) {
			return _0x5ab773(_0x3893c7);
		},
		'lMeUM': function (_0x34d463, _0x4d6b7b) {
			return _0x34d463 - _0x4d6b7b;
		},
		'aycWe': function (_0x58ef0e, _0x3891ab) {
			return _0x58ef0e - _0x3891ab;
		},
		'lKwci': _0x64f0('9ca', 'OJFQ'),
		'ZkOVs': function (_0x4a6dbd, _0x4542cb) {
			return _0x4a6dbd - _0x4542cb;
		},
		'zyJTu': function (_0x5e1b93, _0x446452) {
			return _0x5e1b93 / _0x446452;
		},
		'vjWbs': function (_0x2575e0, _0x11c14c) {
			return _0x2575e0 / _0x11c14c;
		},
		'NFCIT': _0x64f0('9cb', 'Zg5['),
		'dsuhf': function (_0x89f937, _0x597b3f) {
			return _0x89f937 + _0x597b3f;
		},
		'ncXTx': function (_0x12a7de, _0x22e70b) {
			return _0x12a7de > _0x22e70b;
		},
		'lPPfO': function (_0x275710, _0x5a84db) {
			return _0x275710(_0x5a84db);
		},
		'JBQXr': function (_0x287953, _0x123071, _0x2eab92) {
			return _0x287953(_0x123071, _0x2eab92);
		},
		'AMUoZ': _0x64f0('9cc', 'NMy2'),
		'OzLtF': _0x64f0('9cd', 'DWlJ'),
		'TBrqo': 'userIndex',
		'zaUUW': function (_0x43ad2d, _0x154b85) {
			return _0x43ad2d !== _0x154b85;
		},
		'GJkAC': _0x64f0('9ce', 'gS57'),
		'uJjdS': _0x64f0('9cf', 'y@FJ'),
		'GKNWk': function (_0x446ff5, _0x613452) {
			return _0x446ff5 !== _0x613452;
		},
		'PcETE': _0x64f0('9d0', 'tkAR')
	};
	var _0x3c08d6 = _0x18d784[_0x64f0('9d1', 'HmCh')](confirm, _0x18d784[_0x64f0('9d2', ')rYM')]);
	if (_0x3c08d6) {
		if (_0x18d784[_0x64f0('9d3', 'y@FJ')](_0x64f0('9d4', '7#T0'), _0x18d784['PcETE'])) {
			var _0x2cfb1e = _0x18d784[_0x64f0('9d5', 'a5h*')][_0x64f0('9d6', 'z1V4')]('|'), _0x234a2d = 0x0;
			while (!![]) {
				switch (_0x2cfb1e[_0x234a2d++]) {
					case'0':
						_0x18d784[_0x64f0('9d7', 'fv0b')]($, _0x64f0('9d8', 'A4bS'))[_0x64f0('9d9', '*E$X')](_0x18d784['wIUwe'], $marginLeft - 0x64);
						continue;
					case'1':
						$(_0x18d784[_0x64f0('9da', '7zoT')])[_0x64f0('871', 'G%jM')]('margin-left', _0x18d784['Ussjm'](0xc8, _0x18d784['mwhyn']($body, 0.1)));
						continue;
					case'2':
						_0x18d784[_0x64f0('9db', 'TR]&')]($, _0x18d784['eMmnc'])['css'](_0x18d784['pROLs'], $marginLeft);
						continue;
					case'3':
						_0x18d784[_0x64f0('9dc', 'JsoZ')]($, _0x18d784['ktmyn'])['css'](_0x18d784[_0x64f0('9dd', 'nO3k')], $width);
						continue;
					case'4':
						if ($marginLeft < 0x6e) {
							$marginLeft = 0x6e;
						}
						continue;
					case'5':
						_0x18d784[_0x64f0('9de', 'Zg5[')]($, _0x18d784['ktmyn'])['css'](_0x64f0('9df', 'xViR'), $marginLeft);
						continue;
					case'6':
						_0x18d784[_0x64f0('9e0', 'xViR')]($, _0x18d784[_0x64f0('9e1', '8Vu)')])['css'](_0x18d784[_0x64f0('9e2', '(DaA')], $marginLeft);
						continue;
					case'7':
						$(_0x18d784[_0x64f0('9e3', 't7O$')])['css'](_0x64f0('9e4', 'HmCh'), $width);
						continue;
					case'8':
						$(_0x18d784[_0x64f0('9e5', '8Vu)')])[_0x64f0('289', 'hSvn')](_0x64f0('9e6', 'OJFQ'), $marginLeft - 0x6e);
						continue;
					case'9':
						$(_0x18d784['izkEP'])[_0x64f0('26f', 'fv0b')](_0x18d784['wIUwe'], 0xc8 - _0x18d784[_0x64f0('9e7', 'kUYz')]($body, 0.1));
						continue;
				}
				break;
			}
		} else {
			AuthInterFace[_0x64f0('9e8', 'j510')](_0x1437f8, _0x17c421, function (_0x2380dc) {
				var _0x3d57b1 = {
					'MfrKs': function (_0x423e2b, _0x595c7e) {
						return _0x18d784[_0x64f0('9e9', 'hY8M')](_0x423e2b, _0x595c7e);
					},
					'riefY': _0x18d784[_0x64f0('9ea', '8Vu)')],
					'XnjaP': function (_0x154812, _0x17b089) {
						return _0x18d784[_0x64f0('9eb', '4Ats')](_0x154812, _0x17b089);
					},
					'BtknR': function (_0x4afb84, _0x199c9f) {
						return _0x18d784[_0x64f0('9ec', 'DWlJ')](_0x4afb84, _0x199c9f);
					},
					'qyGnJ': function (_0x489a77, _0x12aaa3) {
						return _0x18d784[_0x64f0('9ed', 'Bk0K')](_0x489a77, _0x12aaa3);
					},
					'AFDMo': function (_0x4abfba, _0x219d81) {
						return _0x18d784[_0x64f0('9eb', '4Ats')](_0x4abfba, _0x219d81);
					},
					'mPxnb': function (_0x3693d8, _0x598331) {
						return _0x18d784['lPPfO'](_0x3693d8, _0x598331);
					},
					'eoqvl': function (_0x24b619, _0xfe706) {
						return _0x18d784[_0x64f0('9ee', 'NMy2')](_0x24b619, _0xfe706);
					},
					'YICcj': '</div><div\x20class=\x27secondLine\x27>小时</div>',
					'sUjOF': function (_0x1661d8, _0x395e79, _0x34d552) {
						return _0x18d784['JBQXr'](_0x1661d8, _0x395e79, _0x34d552);
					}
				};
				if (_0x18d784[_0x64f0('9ef', 'JsoZ')](_0x18d784['AMUoZ'], _0x18d784['OzLtF'])) {
					limit = limit[_0x64f0('9f0', 'FBUA')](0x0, limit[_0x64f0('9f1', 'EeGR')]('B'));
					limit = _0x3d57b1[_0x64f0('9f2', 'kUYz')](limit, 0x400) + 'KB';
				} else {
					if (_0x2380dc['result'] == _0x64f0('9f3', 'hSvn')) {
						var _0x36923d = getQueryStringByName(_0x18d784[_0x64f0('9f4', 'fv0b')]);
						AuthInterFace[_0x64f0('9f5', '3Pmi')](_0x36923d, function (_0x5c66cc) {
							if (_0x18d784[_0x64f0('9f6', '(DaA')](_0x18d784['hmFcx'], 'IAutA')) {
								var _0x130c29 = _0x3d57b1['riefY']['split']('|'), _0x5d6347 = 0x0;
								while (!![]) {
									switch (_0x130c29[_0x5d6347++]) {
										case'0':
											var _0x2d9053 = _0x3d57b1[_0x64f0('9f7', '3Pmi')](theTime2, '');
											continue;
										case'1':
											if (_0x3d57b1['BtknR'](_0x2d9053[_0x64f0('9f8', 'Q((!')]('.'), -0x1)) {
												_0x2d9053 = _0x2d9053['substring'](0x0, _0x2d9053['indexOf']('.'));
											}
											continue;
										case'2':
											if (_0x3d57b1[_0x64f0('9f9', 'j510')](_0x542dd2, 0x0)) {
												_0x2d9053 = _0x3d57b1[_0x64f0('9fa', '7zoT')](_0x3d57b1[_0x64f0('9fb', '8Vu)')](parseInt, _0x2d9053), _0x542dd2);
											}
											continue;
										case'3':
											result = _0x3d57b1['AFDMo'](_0x3d57b1[_0x64f0('9fc', '7#T0')]('<div\x20class=\x27firstLine\x27>', _0x2d9053), _0x3d57b1['YICcj']);
											continue;
										case'4':
											var _0x542dd2 = _0x3d57b1[_0x64f0('9fd', 'kUYz')](fomatFloat, _0x3d57b1[_0x64f0('9fe', '(DaA')](_0x3d57b1[_0x64f0('9ff', 'Lclw')](parseInt, theTime1), 0x3c), 0x1);
											continue;
									}
									break;
								}
							} else {
								getTime = 0x1;
								_0x18d784[_0x64f0('a00', 'xViR')](fillData);
							}
						});
					} else {
						if (_0x18d784[_0x64f0('a01', 'DWlJ')](_0x18d784[_0x64f0('a02', 'hSvn')], _0x18d784[_0x64f0('a03', '*6xD')])) {
							var _0x529cc9 = _0x18d784[_0x64f0('a04', 'A4bS')][_0x64f0('a05', 'EeGR')]('|'),
								_0x5cbedb = 0x0;
							while (!![]) {
								switch (_0x529cc9[_0x5cbedb++]) {
									case'0':
										_0x18d784[_0x64f0('a06', 'wpSi')]($, _0x64f0('a07', 'tUE5'))[_0x64f0('894', 'nO3k')](_0x18d784[_0x64f0('a08', 'Lclw')], _0x18d784[_0x64f0('a09', 'F[EM')](_0x18d784[_0x64f0('a0a', 'F[EM')]($body, 0x384) / 0x2, 0xfa));
										continue;
									case'1':
										_0x18d784[_0x64f0('a0b', 'tkAR')]($, '#divPop')['css'](_0x18d784[_0x64f0('a0c', 'fv0b')], _0x18d784['oOHzr'](_0x18d784[_0x64f0('a0d', '3Pmi')]($body, 0x384) / 0x2, 0xfa));
										continue;
									case'2':
										_0x18d784['KnyVW']($, _0x64f0('a0e', ')rYM'))['css'](_0x18d784[_0x64f0('a0f', 'G%jM')], _0x18d784[_0x64f0('a10', 'wpSi')](_0x18d784[_0x64f0('a11', 'hSvn')]($body, 0x384), 0x2) - 0xfa);
										continue;
									case'3':
										_0x18d784['EZHrV']($, _0x64f0('a12', 'G%jM'))[_0x64f0('4ed', '4Ats')](_0x64f0('a13', 'xViR'), _0x18d784[_0x64f0('a14', 'FBUA')](_0x18d784[_0x64f0('a15', 'Zg5[')](_0x18d784['aycWe']($body, 0x384), 0x2), 0xfa));
										continue;
									case'4':
										$(_0x18d784[_0x64f0('a16', '4Ats')])['css'](_0x18d784['wIUwe'], _0x18d784[_0x64f0('a17', 'hSvn')](_0x18d784[_0x64f0('a18', 'Lclw')](_0x18d784[_0x64f0('a19', 'm*Jj')]($body, 0x384), 0x2), 0xd2));
										continue;
								}
								break;
							}
						} else {
							alert(_0x2380dc[_0x64f0('868', 'xViR')]);
						}
					}
				}
			});
		}
	}
}
```

</details>
<details><summary>解密后</summary>

> 为方便对比已进行格式化处理

```javascript
function cancelMacWithUserNameAndMac(_0x1437f8, _0x17c421, _0x18daca) {
	var _0x3c08d6 = confirm('关闭无感认证后,只能在设备本机上再次开启!');
	if (_0x3c08d6) {
		AuthInterFace.cancelMacWithUserNameAndMac(_0x1437f8, _0x17c421, function (_0x2380dc) {
			if (_0x2380dc.result == 'success') {
				var _0x36923d = getQueryStringByName('userIndex');
				AuthInterFace.freshOnlineUserInfo(_0x36923d, function (_0x5c66cc) {
					getTime = 1;
					fillData();
				});
			} else {
				alert(_0x2380dc.message);
			}
		});
	}
}
```

</details>

## 功能介绍

* 解除全局加密
    * 还原类似 `_0x51f5('7', 'Ik*@')` 的加密内容。
* 解除代码块加密
    * 还原代码块中被统一收集的字符串及运算符。
* 清理死代码（花指令）
    1. 清理仅包含常量字符串判断的 if 语句。
    2. 还原使用 `switch...while` 打乱顺序执行的语句。
* 解除环境限制
    1. 解除 `禁止控制台调试` 限制。
    2. 解除 `禁止控制台输出` 限制。
    3. 解除 `防止格式化` 限制。
    4. 解除 `安全域名` 限制。
* 提升代码可读性
    1. 合并串联字符串（`'spl'+'it'` → `'split'`）
    2. 转换十六进制数字（`0xf` → `15`）
    3. 替换索引器（`Object['keys']` → `Object.keys`）
    4. 转换Unicode字符（`\x22` → `"`）
* 格式化代码
    1. 将代码根据语句进行简易的代码缩进。
    2. 因能力有限且类似工具颇多，不做更多的优化和处理。

## 使用须知

* `JS最牛加密` 为加密器名称，并非浮夸的宣传标语。（😅）
* 解密文件中**必须**有且仅有通过 `JsjiamiV6` 加密的内容（支持经过格式化的代码）。
* 注释和局部变量名在代码压缩、混淆的过程中已经丢失或被篡改，无法还原。
* 在不安装依赖的情况下解密器将会使用 Node.js 内建的 vm 模块。若你无法安装依赖，请不要用于解密**不可信**的 JS 文件。

## 使用方法

> 值得注意的是，请务必确保 `config.json` 文件存放在**运行脚本时**所在的文件夹（而不是解密器所在的文件夹，虽然它们通常是相同的）。

1. 运行 `npm install` 。（可选，安装依赖后解密更安全）
2. 根据需求在 [`config.json`](/config.json) 中自定义配置。
3. 运行 [`Decryptor.js`](/Decryptor.js) 。

## 输出结果

> 每一解密步骤完成后，解密器都会输出一个**结果文件**。

> 你可以根据你的**需求**从以下结果中选择一个作为最终解密结果。

> 支持通过配置文件修改输出文件的位置和命名格式。 

* `DecryptResult0.js`：净化代码
* `DecryptResult1.js`：解除全局加密
* `DecryptResult2.js`：解除代码块加密
* `DecryptResult3.js`：清理死代码（花指令）
* `DecryptResult4.js`：解除环境限制
* `DecryptResult5.js`：提升代码可读性
* `DecryptResult6.js`：格式化代码

## 问题反馈

* 如果目标 JS **使用了(我)不常用的语法**，可能导致解密失败。如遇到此类情况欢迎提交 `Issue` 。
* 为防止议题分散不便管理，仅支持通过 [![GitHub](https://img.shields.io/badge/GitHub-181717?style=plastic&logo=Github)](https://github.com/) 提交 `Issue` 。
* 鉴于强迫症等一些特殊原因，本仓库几乎不接受 `Pull Request` ，如有建议可通过 `Issue` 提交。

## 开发计划

> 目前针对 `JsjiamiV6` 的解密功能已基本完善，暂无新功能的开发计划。

> 不想开学😣

## 特别感谢

[![Licenses for Open Source Development](https://img.shields.io/badge/JetBrains-Open%20Source%20License-white?logo=JetBrains&style=plastic)](https://www.jetbrains.com/community/opensource/#support)