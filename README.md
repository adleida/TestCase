# **整理test case**

## 目前case 有四类

- right case
- format case
- logic case
- network case

## right case

[right](https://github.com/adleida/TestCase/tree/master/right)

####  DSP response 中的字段不完整

| result             | casename                                                     | reason |
|--------------------|--------------------------------------------------------------|--------|
| :white_check_mark: | not_full_feild_response/008-1/README.md                      | None   |
| :white_check_mark: | not_full_feild_response/008-2/README.md                      | None   |
| :white_check_mark: | not_full_feild_response/008/README.md                        | None   |
| :white_check_mark: | not_full_feild_response/010/README.md                        | None   |
| :white_check_mark: | not_full_feild_response/without_click_url/005-1/README.md    | None   |
| :white_check_mark: | not_full_feild_response/without_click_url/005-2/README.md    | None   |
| :white_check_mark: | not_full_feild_response/without_click_url/005/README.md      | None   |
| :white_check_mark: | not_full_feild_response/without_click_url/007-1/README.md    | None   |
| :white_check_mark: | not_full_feild_response/without_click_url/007-2/README.md    | None   |
| :white_check_mark: | not_full_feild_response/without_click_url/007/README.md      | None   |
| :white_check_mark: | not_full_feild_response/without_tracking_url/004-1/README.md | None   |
| :white_check_mark: | not_full_feild_response/without_tracking_url/004-2/README.md | None   |
| :white_check_mark: | not_full_feild_response/without_tracking_url/004/README.md   | None   |
| :white_check_mark: | not_full_feild_response/without_tracking_url/006-1/README.md | None   |
| :white_check_mark: | not_full_feild_response/without_tracking_url/006-2/README.md | None   |
| :white_check_mark: | not_full_feild_response/without_tracking_url/006/README.md   | None   |

#### 一家DSP 返回正确

| result             | casename                            | reason |
|--------------------|-------------------------------------|--------|
| :white_check_mark: | one_dsp_response_ok/001-1/README.md | None   |
| :white_check_mark: | one_dsp_response_ok/001-2/README.md | None   |
| :white_check_mark: | one_dsp_response_ok/001-3/README.md | None   |
| :white_check_mark: | one_dsp_response_ok/001/README.md   | None   |

#### 两家DSP 返回正确

| result             | casename                            | reason |
|--------------------|-------------------------------------|--------|
| :white_check_mark: | three_dsp_response_ok/003/README.md | None   |
| :white_check_mark: | three_dsp_response_ok/009/README.md | None   |

#### 三家DSP 返回正确

| result             | casename                            | reason |
|--------------------|-------------------------------------|--------|
| :white_check_mark: | two_dsp_response_ok/002-1/README.md | None   |
| :white_check_mark: | two_dsp_response_ok/002-2/README.md | None   |
| :white_check_mark: | two_dsp_response_ok/002/README.md   | None   |


## logic case

[logic](https://github.com/adleida/TestCase/tree/master/logic)

#### 一家DSP

| result             | casename                       | reason |
|--------------------|--------------------------------|--------|
| :white_check_mark: | one_dsp_response/001/README.md | None   |
| :white_check_mark: | one_dsp_response/007/README.md | None   |
| :white_check_mark: | one_dsp_response/009/README.md | None   |
| :white_check_mark: | one_dsp_response/016/README.md | None   |

#### 三家DSP

| result             | casename                         | reason |
|--------------------|----------------------------------|--------|
| :white_check_mark: | three_dsp_response/005/README.md | None   |
| :white_check_mark: | three_dsp_response/006/README.md | None   |
| :white_check_mark: | three_dsp_response/015/README.md | None   |
| :white_check_mark: | three_dsp_response/100/README.md | None   |
| :white_check_mark: | three_dsp_response/101/README.md | None   |
| :white_check_mark: | three_dsp_response/102/README.md | None   |
| :white_check_mark: | three_dsp_response/103/README.md | None   |
| :white_check_mark: | three_dsp_response/104/README.md | None   |
| :white_check_mark: | three_dsp_response/61/README.md  | None   |

#### 两家DSP

| result             | casename                         | reason |
|--------------------|----------------------------------|--------|
| :white_check_mark: | two_dsp_response/002/README.md   | None   |
| :white_check_mark: | two_dsp_response/003/README.md   | None   |
| :white_check_mark: | two_dsp_response/004/README.md   | None   |
| :white_check_mark: | two_dsp_response/008/README.md   | None   |
| :white_check_mark: | two_dsp_response/010/README.md   | None   |
| :white_check_mark: | two_dsp_response/011/README.md   | None   |
| :white_check_mark: | two_dsp_response/012-1/README.md | None   |
| :white_check_mark: | two_dsp_response/012/README.md   | None   |
| :white_check_mark: | two_dsp_response/013/README.md   | None   |
| :white_check_mark: | two_dsp_response/014/README.md   | None   |


## format error case

[format](https://github.com/adleida/TestCase/tree/master/format)

#### request 请求头错误

| result             | casename                        | reason |
|--------------------|---------------------------------|--------|
| :white_check_mark: | header_error/003/README.md      | None   |
| :white_check_mark: | header_error/004/README.md      | None   |
| :white_check_mark: | json_format_error/002/README.md | None   |

#### SDK 请求的字段不完整

| result             | casename                             | reason |
|--------------------|--------------------------------------|--------|
| :white_check_mark: | Not_full_feild_request/001/README.md | None   |
| :white_check_mark: | Not_full_feild_request/005/README.md | None   |
| :white_check_mark: | Not_full_feild_request/006/README.md | None   |
| :white_check_mark: | Not_full_feild_request/007/README.md | None   |
| :white_check_mark: | Not_full_feild_request/008/README.md | None   |
| :white_check_mark: | Not_full_feild_request/009/README.md | None   |
| :white_check_mark: | Not_full_feild_request/021/README.md | None   |
| :white_check_mark: | Not_full_feild_request/022/README.md | None   |
| :white_check_mark: | Not_full_feild_request/023/README.md | None   |
| :white_check_mark: | Not_full_feild_request/024/README.md | None   |
| :white_check_mark: | Not_full_feild_request/025/README.md | None   |
| :white_check_mark: | Not_full_feild_request/026/README.md | None   |
| :white_check_mark: | Not_full_feild_request/027/README.md | None   |
| :white_check_mark: | Not_full_feild_request/028/README.md | None   |
| :white_check_mark: | Not_full_feild_request/029/README.md | None   |
| :white_check_mark: | Not_full_feild_request/030/README.md | None   |
| :white_check_mark: | Not_full_feild_request/031/README.md | None   |
| :white_check_mark: | Not_full_feild_request/035/README.md | None   |
| :white_check_mark: | Not_full_feild_request/036/README.md | None   |
| :white_check_mark: | Not_full_feild_request/037/README.md | None   |
| :white_check_mark: | Not_full_feild_request/038/README.md | None   |
| :white_check_mark: | Not_full_feild_request/039/README.md | None   |
| :white_check_mark: | Not_full_feild_request/040/README.md | None   |
| :white_check_mark: | Not_full_feild_request/041/README.md | None   |
| :white_check_mark: | Not_full_feild_request/042/README.md | None   |
| :white_check_mark: | Not_full_feild_request/043/README.md | None   |
| :white_check_mark: | Not_full_feild_request/044/README.md | None   |
| :white_check_mark: | Not_full_feild_request/045/README.md | None   |
| :white_check_mark: | Not_full_feild_request/046/README.md | None   |
| :white_check_mark: | Not_full_feild_request/047/README.md | None   |
| :white_check_mark: | Not_full_feild_request/048/README.md | None   |
| :white_check_mark: | Not_full_feild_request/049/README.md | None   |
| :white_check_mark: | Not_full_feild_request/050/README.md | None   |
| :white_check_mark: | Not_full_feild_request/051/README.md | None   |
| :white_check_mark: | Not_full_feild_request/052/README.md | None   |
| :white_check_mark: | Not_full_feild_request/053/README.md | None   |
| :white_check_mark: | Not_full_feild_request/054/README.md | None   |
| :white_check_mark: | Not_full_feild_request/055/README.md | None   |
| :white_check_mark: | Not_full_feild_request/056/README.md | None   |
| :white_check_mark: | Not_full_feild_request/057/README.md | None   |
| :white_check_mark: | Not_full_feild_request/058/README.md | None   |
| :white_check_mark: | Not_full_feild_request/059/README.md | None   |
| :white_check_mark: | Not_full_feild_request/060/README.md | None   |
| :white_check_mark: | Not_full_feild_request/061/README.md | None   |
| :white_check_mark: | Not_full_feild_request/062/README.md | None   |
| :white_check_mark: | Not_full_feild_request/063/README.md | None   |
| :white_check_mark: | Not_full_feild_request/065/README.md | None   |
| :white_check_mark: | Not_full_feild_request/066/README.md | None   |
| :white_check_mark: | Not_full_feild_request/067/README.md | None   |
| :white_check_mark: | Not_full_feild_request/068/README.md | None   |
| :white_check_mark: | Not_full_feild_request/201/README.md | None   |
| :white_check_mark: | Not_full_feild_request/202/README.md | None   |
| :white_check_mark: | Not_full_feild_request/203/README.md | None   |
| :white_check_mark: | Not_full_feild_request/204/README.md | None   |
| :white_check_mark: | Not_full_feild_request/205/README.md | None   |
| :white_check_mark: | Not_full_feild_request/206/README.md | None   |
| :white_check_mark: | Not_full_feild_request/207/README.md | None   |
| :white_check_mark: | Not_full_feild_request/208/README.md | None   |
| :white_check_mark: | Not_full_feild_request/209/README.md | None   |
| :white_check_mark: | Not_full_feild_request/210/README.md | None   |
| :white_check_mark: | Not_full_feild_request/211/README.md | None   |
| :white_check_mark: | Not_full_feild_request/212/README.md | None   |

#### DSP 响应错误

| result             | casename                       | reason                |
|--------------------|--------------------------------|-----------------------|
| :white_check_mark: | response_error/010-1/README.md | None                  |
| :white_check_mark: | response_error/010/README.md   | None                  |
| :white_check_mark: | response_error/011-1/README.md | None                  |
| :white_check_mark: | response_error/011/README.md   | None                  |
| :white_check_mark: | response_error/012-1/README.md | None                  |
| :white_check_mark: | response_error/012-2/README.md | None                  |
| :white_check_mark: | response_error/012/README.md   | None                  |
| :white_check_mark: | response_error/013-1/README.md | None                  |
| :white_check_mark: | response_error/013/README.md   | None                  |
| :white_check_mark: | response_error/014-1/README.md | None                  |
| :white_check_mark: | response_error/014/README.md   | None                  |
| :white_check_mark: | response_error/015/README.md   | None                  |
| :white_check_mark: | response_error/016/README.md   | None                  |
| :white_check_mark: | response_error/017/README.md   | None                  |
| :white_check_mark: | response_error/018/README.md   | None                  |
| :x:                | response_error/019/README.md   | result fail
| :white_check_mark: | response_error/020-1/README.md | None                  |
| :white_check_mark: | response_error/020-2/README.md | None                  |
| :white_check_mark: | response_error/020/README.md   | None                  |
| :white_check_mark: | response_error/032/README.md   | None                  |
| :white_check_mark: | response_error/033-1/README.md | None                  |
| :white_check_mark: | response_error/033/README.md   | None                  |
| :white_check_mark: | response_error/034-1/README.md | None                  |
| :white_check_mark: | response_error/034/README.md   | None                  |
| :x:                | response_error/064/README.md   | response format error |
| :white_check_mark: | response_error/099/README.md   | None                  |
| :white_check_mark: | response_error/101/README.md   | None                  |
| :white_check_mark: | response_error/213/README.md   | None                  |
| :white_check_mark: | response_error/214/README.md   | None                  |
| :white_check_mark: | response_error/215/README.md   | None                  |
| :white_check_mark: | response_error/216/README.md   | None                  |
| :white_check_mark: | response_error/new1/README.md  | None                  |
| :white_check_mark: | response_error/new2/README.md  | None                  |
| :white_check_mark: | response_error/new3/README.md  | None                  |


## network case

[network](https://github.com/adleida/TestCase/tree/master/network)

#### 网络错误

| result             | casename        | reason                    |
|--------------------|-----------------|---------------------------|
| :x:                | 001/README.md   | Nothing                   |
| :x:                | 001-1/README.md | no README file            |
| :x:                | 001-2/README.md | no README file            |
| :x:                | 001-3/README.md | no README file            |
| :x:                | 002/README.md   | no DSP config             |
| :x:                | 003/README.md   | config error              |
| :x:                | 004/README.md   | exchange response success |
| :white_check_mark: | 005/README.md   | None                      |
| :x:                | 014/README.md   | None                      |
| :white_check_mark: | 006/README.md   | None                      |
| :white_check_mark: | 007/README.md   | None                      |
| :white_check_mark: | 008/README.md   | None                      |
| :white_check_mark: | 009/README.md   | None                      |
| :white_check_mark: | 010/README.md   | None                      |
| :white_check_mark: | 011/README.md   | None                      |
| :white_check_mark: | 012/README.md   | None                      |
| :white_check_mark: | 013/README.md   | None                      |
| :white_check_mark: | 015/README.md   | None                      |
