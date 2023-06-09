主題：醫院掛號系統

組員：110111232 鄭忻恬、110111204 李祐丞、110111239 游翊丞

案例描述：

醫院掛號系統主要任務：(1) 協助患者掛號，使患者能夠在線上預約醫生和診療時間，並能夠方便地查看醫生的可用時段和預約狀態。(2) 管理、統計掛號資料，提供醫院管理人員查看和管理掛號相關的資訊。患者掛號前要先註冊，提供個人基本資料，例如姓名、性別等。患者可以透過系統選擇特定的醫生和時段進行掛號。顯示可預約的時段列表，供患者選擇。一旦預約人數已滿，該時段將不再對其他患者開放。系統向患者發出預約通知，包括預約日期、時間、醫生姓名等詳細資訊。可以透過電子郵件或簡訊等方式進行通知。患者可以在需要時取消已經預約的掛號。提供取消掛號的功能，同時釋出被取消的時段，使其可供其他患者預約。系統向醫院管理人員提供一個管理介面，供醫院管理人員查看和管理掛號相關的資訊。管理人員可以查看已掛號的患者列表、患者的基本資料、醫生的診斷時段等。加入醫生診斷系統，根據病人的症狀提供醫生診斷的參考資訊，系統需能夠保存醫生的診斷結果和處方記錄，方便病人和醫生查詢和追蹤治療進度，以及確認患者是否需要住院。

利害人關係表：

| 利害關係人(參與者) | 目標 |
| ----- | ----- |
| 系統管理員 | 1. 系統運行和維護 |
| 患者 | 1. 透過掛號系統，線上預約醫生和診療時間 <br> 2. 接收預約通知 <br> 3. 使用系統查詢診斷結果和處方記錄，追蹤治療進度。|
| 醫生 | 1. 利用掛號系統接收患者預約掛號 <br> 2. 管理預約時段和患者資料 <br> 3. 診斷和記錄患者的診斷結果和處方記錄 |
| 醫院管理人員 | 1. 管理和統計掛號資料 <br> 2. 查看和管理掛號相關資訊 <br> 3. 管理患者的診斷紀錄，確認患者是否需要住院 |

事件表：

| 案例名稱 | 事件描述 |
| ----- | ----- |
| 註冊資料 | 患者掛號前要先註冊，提供個人基本資料。 |
| 預約掛號 | 患者透過系統選擇特定的醫生和時段進行掛號。 |
| 取消掛號 | 患者可以在需要時取消已經預約的掛號。 |
| 預約通知 | 系統向患者發出預約通知，包括預約日期、時間、醫生姓名等詳細資訊。可以透過電子郵件或簡訊等方式進行通知。 |
| 查詢治療進度 | 根據病人的症狀提供醫生診斷的參考資訊，系統需能夠保存醫生的診斷結果和處方記錄，方便病人和醫生查詢和追蹤治療進度，以及確認患者是否需要住院。 |

使用者案例圖

<div class="mxgraph" style="max-width:100%;border:1px solid transparent;" data-mxgraph="{&quot;highlight&quot;:&quot;#0000ff&quot;,&quot;nav&quot;:true,&quot;resize&quot;:true,&quot;toolbar&quot;:&quot;zoom layers tags lightbox&quot;,&quot;edit&quot;:&quot;_blank&quot;,&quot;xml&quot;:&quot;&lt;mxfile&gt;&lt;diagram id=\&quot;0UfyoSpAn6ECmIHnitit\&quot; name=\&quot;使用者案例圖\&quot;&gt;&lt;mxGraphModel dx=\&quot;822\&quot; dy=\&quot;568\&quot; grid=\&quot;1\&quot; gridSize=\&quot;10\&quot; guides=\&quot;1\&quot; tooltips=\&quot;1\&quot; connect=\&quot;1\&quot; arrows=\&quot;1\&quot; fold=\&quot;1\&quot; page=\&quot;1\&quot; pageScale=\&quot;1\&quot; pageWidth=\&quot;827\&quot; pageHeight=\&quot;1169\&quot; math=\&quot;0\&quot; shadow=\&quot;0\&quot;&gt;&lt;root&gt;&lt;mxCell id=\&quot;0\&quot;/&gt;&lt;mxCell id=\&quot;1\&quot; parent=\&quot;0\&quot;/&gt;&lt;mxCell id=\&quot;2\&quot; value=\&quot;掛號系統\&quot; style=\&quot;swimlane;whiteSpace=wrap;html=1;\&quot; parent=\&quot;1\&quot; vertex=\&quot;1\&quot;&gt;&lt;mxGeometry x=\&quot;240\&quot; y=\&quot;40\&quot; width=\&quot;240\&quot; height=\&quot;540\&quot; as=\&quot;geometry\&quot;&gt;&lt;mxRectangle x=\&quot;240\&quot; y=\&quot;40\&quot; width=\&quot;90\&quot; height=\&quot;30\&quot; as=\&quot;alternateBounds\&quot;/&gt;&lt;/mxGeometry&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;7\&quot; value=\&quot;註冊資料\&quot; style=\&quot;ellipse;whiteSpace=wrap;html=1;\&quot; parent=\&quot;2\&quot; vertex=\&quot;1\&quot;&gt;&lt;mxGeometry x=\&quot;60\&quot; y=\&quot;290\&quot; width=\&quot;120\&quot; height=\&quot;60\&quot; as=\&quot;geometry\&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;8\&quot; value=\&quot;維護掛號系統\&quot; style=\&quot;ellipse;whiteSpace=wrap;html=1;\&quot; parent=\&quot;2\&quot; vertex=\&quot;1\&quot;&gt;&lt;mxGeometry x=\&quot;60\&quot; y=\&quot;50\&quot; width=\&quot;120\&quot; height=\&quot;60\&quot; as=\&quot;geometry\&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;9\&quot; value=\&quot;預約掛號\&quot; style=\&quot;ellipse;whiteSpace=wrap;html=1;\&quot; parent=\&quot;2\&quot; vertex=\&quot;1\&quot;&gt;&lt;mxGeometry x=\&quot;60\&quot; y=\&quot;210\&quot; width=\&quot;120\&quot; height=\&quot;60\&quot; as=\&quot;geometry\&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;10\&quot; value=\&quot;取消掛號\&quot; style=\&quot;ellipse;whiteSpace=wrap;html=1;\&quot; parent=\&quot;2\&quot; vertex=\&quot;1\&quot;&gt;&lt;mxGeometry x=\&quot;60\&quot; y=\&quot;370\&quot; width=\&quot;120\&quot; height=\&quot;60\&quot; as=\&quot;geometry\&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;11\&quot; value=\&quot;預約通知\&quot; style=\&quot;ellipse;whiteSpace=wrap;html=1;\&quot; parent=\&quot;2\&quot; vertex=\&quot;1\&quot;&gt;&lt;mxGeometry x=\&quot;60\&quot; y=\&quot;450\&quot; width=\&quot;120\&quot; height=\&quot;60\&quot; as=\&quot;geometry\&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;25\&quot; value=\&quot;查詢治療進度\&quot; style=\&quot;ellipse;whiteSpace=wrap;html=1;\&quot; parent=\&quot;2\&quot; vertex=\&quot;1\&quot;&gt;&lt;mxGeometry x=\&quot;60\&quot; y=\&quot;130\&quot; width=\&quot;120\&quot; height=\&quot;60\&quot; as=\&quot;geometry\&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;3\&quot; value=\&quot;系統管理員\&quot; style=\&quot;shape=umlActor;verticalLabelPosition=bottom;verticalAlign=top;html=1;outlineConnect=0;\&quot; parent=\&quot;1\&quot; vertex=\&quot;1\&quot;&gt;&lt;mxGeometry x=\&quot;570\&quot; y=\&quot;145\&quot; width=\&quot;30\&quot; height=\&quot;60\&quot; as=\&quot;geometry\&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;23\&quot; style=\&quot;edgeStyle=none;html=1;exitX=1;exitY=0.3333333333333333;exitDx=0;exitDy=0;exitPerimeter=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;endArrow=none;endFill=0;\&quot; parent=\&quot;1\&quot; source=\&quot;4\&quot; target=\&quot;25\&quot; edge=\&quot;1\&quot;&gt;&lt;mxGeometry relative=\&quot;1\&quot; as=\&quot;geometry\&quot;&gt;&lt;mxPoint x=\&quot;300\&quot; y=\&quot;200\&quot; as=\&quot;targetPoint\&quot;/&gt;&lt;/mxGeometry&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;26\&quot; style=\&quot;edgeStyle=none;html=1;exitX=1;exitY=0.3333333333333333;exitDx=0;exitDy=0;exitPerimeter=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;endArrow=none;endFill=0;\&quot; edge=\&quot;1\&quot; parent=\&quot;1\&quot; source=\&quot;4\&quot; target=\&quot;11\&quot;&gt;&lt;mxGeometry relative=\&quot;1\&quot; as=\&quot;geometry\&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;4\&quot; value=\&quot;醫院管理人員\&quot; style=\&quot;shape=umlActor;verticalLabelPosition=bottom;verticalAlign=top;html=1;outlineConnect=0;\&quot; parent=\&quot;1\&quot; vertex=\&quot;1\&quot;&gt;&lt;mxGeometry x=\&quot;120\&quot; y=\&quot;370\&quot; width=\&quot;30\&quot; height=\&quot;60\&quot; as=\&quot;geometry\&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;5\&quot; value=\&quot;醫生\&quot; style=\&quot;shape=umlActor;verticalLabelPosition=bottom;verticalAlign=top;html=1;outlineConnect=0;\&quot; parent=\&quot;1\&quot; vertex=\&quot;1\&quot;&gt;&lt;mxGeometry x=\&quot;120\&quot; y=\&quot;145\&quot; width=\&quot;30\&quot; height=\&quot;60\&quot; as=\&quot;geometry\&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;6\&quot; value=\&quot;患者\&quot; style=\&quot;shape=umlActor;verticalLabelPosition=bottom;verticalAlign=top;html=1;outlineConnect=0;\&quot; parent=\&quot;1\&quot; vertex=\&quot;1\&quot;&gt;&lt;mxGeometry x=\&quot;570\&quot; y=\&quot;370\&quot; width=\&quot;30\&quot; height=\&quot;60\&quot; as=\&quot;geometry\&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;13\&quot; style=\&quot;edgeStyle=none;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.3333333333333333;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;\&quot; parent=\&quot;1\&quot; source=\&quot;8\&quot; target=\&quot;3\&quot; edge=\&quot;1\&quot;&gt;&lt;mxGeometry relative=\&quot;1\&quot; as=\&quot;geometry\&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;14\&quot; style=\&quot;edgeStyle=none;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=1;entryY=0.3333333333333333;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;\&quot; parent=\&quot;1\&quot; source=\&quot;9\&quot; target=\&quot;4\&quot; edge=\&quot;1\&quot;&gt;&lt;mxGeometry relative=\&quot;1\&quot; as=\&quot;geometry\&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;15\&quot; style=\&quot;edgeStyle=none;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;endArrow=none;endFill=0;entryX=0;entryY=0.3333333333333333;entryDx=0;entryDy=0;entryPerimeter=0;\&quot; parent=\&quot;1\&quot; source=\&quot;7\&quot; target=\&quot;6\&quot; edge=\&quot;1\&quot;&gt;&lt;mxGeometry relative=\&quot;1\&quot; as=\&quot;geometry\&quot;&gt;&lt;mxPoint x=\&quot;220\&quot; y=\&quot;410\&quot; as=\&quot;targetPoint\&quot;/&gt;&lt;/mxGeometry&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;16\&quot; style=\&quot;edgeStyle=none;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.3333333333333333;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;\&quot; parent=\&quot;1\&quot; source=\&quot;9\&quot; target=\&quot;6\&quot; edge=\&quot;1\&quot;&gt;&lt;mxGeometry relative=\&quot;1\&quot; as=\&quot;geometry\&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;17\&quot; style=\&quot;edgeStyle=none;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.3333333333333333;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;\&quot; parent=\&quot;1\&quot; source=\&quot;10\&quot; target=\&quot;6\&quot; edge=\&quot;1\&quot;&gt;&lt;mxGeometry relative=\&quot;1\&quot; as=\&quot;geometry\&quot;/&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;18\&quot; style=\&quot;edgeStyle=none;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;endArrow=none;endFill=0;\&quot; parent=\&quot;1\&quot; source=\&quot;11\&quot; edge=\&quot;1\&quot;&gt;&lt;mxGeometry relative=\&quot;1\&quot; as=\&quot;geometry\&quot;&gt;&lt;mxPoint x=\&quot;570\&quot; y=\&quot;390\&quot; as=\&quot;targetPoint\&quot;/&gt;&lt;/mxGeometry&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;19\&quot; style=\&quot;edgeStyle=none;html=1;exitX=1;exitY=0.3333333333333333;exitDx=0;exitDy=0;endArrow=none;endFill=0;exitPerimeter=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;\&quot; parent=\&quot;1\&quot; source=\&quot;5\&quot; target=\&quot;25\&quot; edge=\&quot;1\&quot;&gt;&lt;mxGeometry relative=\&quot;1\&quot; as=\&quot;geometry\&quot;&gt;&lt;mxPoint x=\&quot;302.76\&quot; y=\&quot;207.20000000000005\&quot; as=\&quot;targetPoint\&quot;/&gt;&lt;/mxGeometry&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;21\&quot; style=\&quot;edgeStyle=none;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;endArrow=none;endFill=0;\&quot; parent=\&quot;1\&quot; source=\&quot;10\&quot; edge=\&quot;1\&quot;&gt;&lt;mxGeometry relative=\&quot;1\&quot; as=\&quot;geometry\&quot;&gt;&lt;mxPoint x=\&quot;150\&quot; y=\&quot;390\&quot; as=\&quot;targetPoint\&quot;/&gt;&lt;/mxGeometry&gt;&lt;/mxCell&gt;&lt;mxCell id=\&quot;24\&quot; style=\&quot;edgeStyle=none;html=1;endArrow=none;endFill=0;\&quot; parent=\&quot;1\&quot; edge=\&quot;1\&quot;&gt;&lt;mxGeometry relative=\&quot;1\&quot; as=\&quot;geometry\&quot;&gt;&lt;mxPoint x=\&quot;570\&quot; y=\&quot;390\&quot; as=\&quot;targetPoint\&quot;/&gt;&lt;mxPoint x=\&quot;420\&quot; y=\&quot;200\&quot; as=\&quot;sourcePoint\&quot;/&gt;&lt;/mxGeometry&gt;&lt;/mxCell&gt;&lt;/root&gt;&lt;/mxGraphModel&gt;&lt;/diagram&gt;&lt;/mxfile&gt;&quot;}"></div>
<script type="text/javascript" src="https://viewer.diagrams.net/js/viewer-static.min.js"></script>

使用案例

註冊資料

| 案例名稱 | 註冊資料 |
| ----- | ----- |
| 案例描述 | 患者掛號前要先註冊，提供個人基本資料，例如姓名、性別等。 |
| 主要參與者 | 患者 |
| 利害關係人與目標 | 患者：能夠線上預約掛號。 |
| 前置作業 | 患者必須先開啟網站。 |
| 後置作業 | 患者註冊成功，可以開始掛號。 |
| 主要成功情節 | 1. 患者進入網站頁面。 <br> 2. 患者選擇註冊按鈕。 <br> 3. 患者輸入個人基本資料(例如姓名、性別等)。 <br> 4. 患者註冊成功。 |
| 例外情節 | 無 |
| 其他需求 | 系統需要定期備份資料，避免資料遺失。 |

預約掛號

| 案例名稱 | 預約掛號 |
| ----- | ----- |
| 案例描述 | 患者可以透過系統選擇特定的醫生和時段進行掛號。顯示可預約的時段列表，供患者選擇。一旦預約人數已滿，該時段將不再對其他患者開放。 |
| 主要參與者 | 患者、醫院管理者 |
| 利害關係人與目標 | 患者：能夠成功預約掛號。 <br> 醫院管理者：有善管理和統計掛號資料。 |
| 前置作業 | 患者必須事先註冊。 |
| 後置作業 | 系統推播電子郵件或簡訊給患者，患者收到預約通知。 |
| 主要成功情節 | 1. 患者登入掛號系統。<br> 2. 患者選擇預約掛號。 <br> 3. 患者選擇科別。 <br> 4. 患者選擇初診或複診。 <br> 5. 患者選擇診斷醫生、診斷時間。 <br> 6. 醫院管理者接收到患者掛號資料。 <br> 7. 患者掛號成功。 |
| 例外情節 | 1. 患者未註冊，則無法預約掛號。 <br> 2. 患者給予錯誤的電子郵件或手機號碼，則無法取得通知訊息。 <br> 3. 當該診斷時段人數已滿，則患者無法預約掛號該時段。 |
| 其他需求 | 系統需要定期備份資料，避免資料遺失。 |

取消掛號

| 案例名稱 | 取消掛號 |
| ----- | ----- |
| 案例描述 | 患者可以在需要時取消已經預約的掛號。提供取消掛號的功能，同時釋出被取消的時段，使其可供其他患者預約。 |
| 主要參與者 | 患者、醫院管理者 |
| 利害關係人與目標 | 患者：能夠成功取消掛號。 <br> 醫院管理者：有善管理和統計掛號資料。 |
| 前置作業 | 患者必須事先有預約掛號。 |
| 後置作業 | 系統推播電子郵件或簡訊給患者，患者收到取消預約通知。 |
| 主要成功情節 | 1. 患者登入掛號系統。<br> 2. 患者選擇取消預約掛號。 <br> 3. 患者尋找要取消的掛號。 <br> 4. 患者選擇取消掛號的按鈕。 <br> 5. 患者確認取消該掛號。 <br> 6. 醫院管理者接收到患者取消掛號通知。 <br> 7. 患者取消掛號成功。 <br> 8. 醫院釋出被取消的時段供其他患者預約。 |
| 例外情節 | 1. 患者未預約掛號，則無法取消預約掛號。 |
| 其他需求 | 系統需要定期備份資料，避免資料遺失。 |

預約通知

| 案例名稱 | 預約通知 |
| ----- | ----- |
| 案例描述 | 系統向患者發出預約通知，包括預約日期、時間、醫生姓名等詳細資訊。可以透過電子郵件或簡訊等方式進行通知。患者可以在需要時取消已經預約的掛號。 |
| 主要參與者 | 患者、醫院管理者 |
| 利害關係人與目標 | 患者：能夠成功接收到預約通知。 |
| 前置作業 | 患者必須事先有預約掛號。 |
| 後置作業 | 系統推播電子郵件或簡訊給患者，患者收到預約通知。 |
| 主要成功情節 | 1. 患者完成預約掛號。<br> 2. 醫院管理者接收到患者掛號資料。 <br> 3. 醫院管理者確認該時段人數未滿。 <br> 4. 醫院管理人員利用系統傳送預約通知給患者。 <br> 5. 患者接收預約掛號通知。 |
| 例外情節 | 1. 患者未預約掛號，則無法接收預約通知。 <br> 2. 患者給予錯誤的電子郵件或手機號碼，則無法取得通知訊息。 |
| 其他需求 | 系統需要定期備份資料，避免資料遺失。 |

查詢治療進度

| 案例名稱 | 查詢治療進度 |
| ----- | ----- |
| 案例描述 | 根據病人的症狀提供醫生診斷的參考資訊，系統需能夠保存醫生的診斷結果和處方記錄，方便病人和醫生查詢和追蹤治療進度，以及確認患者是否需要住院。 |
| 主要參與者 | 患者、醫生、醫院管理人員 |
| 利害關係人與目標 | 患者；能夠方便追蹤自己的診斷紀錄。 <br> 醫生：能夠方便記錄患者的診斷結果和處方記錄。 <br> 醫院管理者：有效管理患者的診斷紀錄，並且確認患者是否需要住院。 |
| 前置作業 | 患者必須事先預約掛號成功，並且在該預約時段完成報到。 |
| 後置作業 | 患者能夠查詢自己的診斷結果、治療進度。 |
| 主要成功情節 | 1. 患者預約掛號成功。<br> 2. 患者在該預約時段完成報到。 <br> 3. 醫生使用系統紀錄患者的診斷結果和處方記錄。 <br> 4. 醫院管理人員管理患者的診斷紀錄。 <br> 5. 醫院管理人員確認患者是否需要住院。 <br> 6. 患者查詢自己的診斷結果及治療進度。 |
| 例外情節 | 1. 患者未預約掛號，則無法查詢自己的診斷結果、治療進度。<br> 2. 患者未在該預約時段完成報到，則無法查詢自己的診斷結果、治療進度。 |
| 其他需求 | 系統需要定期備份資料，避免資料遺失。 |