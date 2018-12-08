# 各癌別開放資料

共有以下癌別的相關資料

* 大腸癌
* 肺癌
* 肝癌
* 乳癌
* 口腔癌
* 攝護腺癌
* 胃癌
* 皮膚癌
* 甲狀腺癌
* 食道癌
* 子宮頸癌
* 淋巴癌
* 喉癌
* 腦瘤
* 鼻咽癌
* 腎臟癌
* 膀胱癌
* 卵巢癌
* 胰臟癌
* 白血病
* 骨肉瘤
* 多發性骨髓瘤
* 腸胃道基質瘤
* 神經內分泌腫瘤
* 慢性骨髓性白血病
* 子宮內膜癌
* 軟組織惡性肉瘤

## 格式說明

以下列舉較重要的內容說明

### data.xml

* `#diagnose_type > option`：所有癌別
* `#diagnose_type > option[female=true]`：女性癌別
* `#diagnose_type > option[male=true]`：男性癌別
* `#image_test > option`：影像檢查結果
* `page[id=3]`：腫瘤切片結果
* `#hematology > test`：血液檢查結果
* `#hematology > test[min]`：單一血液檢查項目的正常最小值
* `#hematology > test[max]`：單一血液檢查項目的正常最大值
* `#hematology > test[f-min]`：單一血液檢查項目的女性正常最小值
* `#hematology > test[f-max]`：單一血液檢查項目的女性正常最大值
* `#hematology > test[m-min]`：單一血液檢查項目的男性正常最小值
* `#hematology > test[m-max]`：單一血液檢查項目的男性正常最大值
* `#hematology > test[unit]`：單一血液檢查項目的單位

### cancer.xml

* `cancer > drugs > drug`：單一癌別的使用藥物
* `cancer > drugs > drug > effect`：單一癌別的使用藥物後副作用
* `cancer > tumor_type`：單一癌別的腫瘤類型
* `cancer > image_test > test`：單一癌別的影像檢查類型
* `cancer > tests > test > range`：單一癌別的其他檢查 (範圍類型)
* `cancer > tests > test > option`：單一癌別的其他檢查 (下拉式類型)
* `cancer > other_treatment`：單一癌別的其他治療方式

## 資料更新頻率

持續更新中

## 建置單位

* 財團法人癌症希望基金會 Hope Foundation for Cancer Care

## 資料提供單位

* 台大醫院 National Taiwan University Hospital
* 長庚醫院 Chang Gung Memorial Hospital
