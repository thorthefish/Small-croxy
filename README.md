# Smol-croxy

This project is a cross gantry 3d printer, that uses a mostly 3d printed frame. It is a very useful tool for prototyping, due to its low cost compared to other costom 3d printers, especialy other cross gantry design, which are usualy $1200 minimum. Another fun part about it is the insane acceleration and speeds that are accesable through the dual motors and direct drive system.

# Why

I decided to build and design this particular project because of the hypercube overkill project on Reprap https://reprap.org/forum/read.php?177,807843, and after I saw the forum post for the first time about a year ago, I havnt been able to get it out of my head. I love the benefits of cross gantry designs and they are one of the fastest possible kinematic syatems of printers, but due to their cost,I have never been able to consider building one, so I decided to make a cross gantry design for as little as possible to prove that the high pricetag was not nesicary to get into this particular design.

Also I just wanted a  fun first printer project.

# CAD

![image](https://github.com/user-attachments/assets/201bc916-6a51-45df-82e9-28e341c0a06e)

# BOM

|Motion| | |
|------|-|-|
|GT2 6mm wide Belt 4 meters	| free |	Use old stuff i have|
|4 - 20 Tooth 5mm Bore Pulley |	$7.00	|https://s.click.aliexpress.com/e/_DmbhjDN|
|4 - 20 Tooth 5mm Bore idler |	free	| 3dp |
|6 - Gantry mgn 9 200mm	| $66.00	|https://www.robotdigg.com/product/1314/Black-anodized-linear-rail-7,-9,-12-and-15|
|4 - 8mm Linear Rod 200mm length	| $25.00	|https://www.aliexpress.us/item/2255800086494873.html?aff_fcid=306d62e50f0348e9982e6cc829c00d71-1748987556342-08848-_DkKxwdt&tt=CPS_NORMAL&aff_fsk=_DkKxwdt&aff_platform=shareComponent-detail&sk=_DkKxwdt&aff_trace_key=306d62e50f0348e9982e6cc829c00d71-1748987556342-08848-_DkKxwdt&terminal_id=ffcf64e248684970b8fdbe380ac19e19&afSmartRedirect=y&gatewayAdapt=glo2usa4itemAdapt|
|5 - Nema 17 Steppers	| $46.00	|https://www.omc-stepperonline.com/nema-17-bipolar-59ncm-84oz-in-2a-42x48mm-4-wires-w-1m-cable-connector-17hs19-2004s1|
|Lead Screw 8 mm lead 200mm	| $6.00	|https://www.aliexpress.us/item/3256803126209223.html?aff_fcid=876c1b6831b34ef086b03f7f31695c39-1748987470418-07548-_DEBYMsL&tt=CPS_NORMAL&aff_fsk=_DEBYMsL&aff_platform=shareComponent-detail&sk=_DEBYMsL&aff_trace_key=876c1b6831b34ef086b03f7f31695c39-1748987470418-07548-_DEBYMsL&terminal_id=ffcf64e248684970b8fdbe380ac19e19&afSmartRedirect=y&gatewayAdapt=glo2usa4itemAdapt|
|Linear Bearings (igus design)	| $8.00	|https://www.aliexpress.us/item/3256806998378536.html?pdp_npi=4%40dis%21USD%21US%20%243.70%21US%20%243.50%21%21%2126.52%2125.09%21%402103209b17489885608175906e642d%2112000039733031325%21sh%21US%210%21X&spm=a2g0o.store_pc_allItems_or_groupList.new_all_items_2008152185346.1005007184693288&gatewayAdapt=glo2usa|
|Lead screw to stepper addapter|	free	| 3dp |
		
		
|Hardware| | |	
|--------|-|-|
|m3 x 20mm	| $7.00	|https://www.amazon.com/Socket-Screw-Thread-stainless-100pcs/dp/B078CXM81F?crid=SVZ6ZVO9CH88&dib=eyJ2IjoiMSJ9.q6E9NIbUqM2ZUEv1RWL1WRtvKj3SNLDo2R1ZT8rj0JjJymfK7DlziPyPhQ9RmYXqtFsmmF5RfL8V4i02E_YMdOe8PfafsIYf-f2_rEaEErhMN4e815gjUTRqY2QU83KdpUdh8nADbf6dZQZNQqsK2pDqByec_Kuya0WOqCijrjozfrKOcGIRmeSK5eXGzWMCCAY-3pPW9X5ySbmHxO28B7zKEQrdl4dj_4N4csIqrsQ.U1aUu0Slo90zMGR9u3oTCXOrKLJl8OYB_KGRmXcT-MM&dib_tag=se&keywords=m3%2B20mm&qid=1749000859&sprefix=m3%2B20mm%2Caps%2C140&sr=8-3&th=1|
|m3 x 30mm + Nuts and Washers	| $9.00	|https://www.amazon.com/Bemaka-550PCS-Washers-Assortment-Stainless/dp/B0D5CSSYGH?crid=S58YKB8LL37P&dib=eyJ2IjoiMSJ9.ZKNbl2CPI2XDQY9Ibd_7LZmvYFcoQXlVfWOB0m5eTD-_wRMsi7I54oWgMg5hld89O7g4XlfLEG_0d_3-YdgNx8etwGZaQzn7JoEeeUbCqAtzdG91wov3J04QlE3UJPb6wiC_iXU8IPN_eCq18U1llZY_RfoE9-M0ZFaMmbisvw45dQ53Qy-UCH-TH--UDKfqZZHnBy1fOIJFL5Rh4S1HV--cY4l6u8t1esgMvZALkuI.61Co7bKb9cPZ_CJNxUDbKlNWgyFjVWlhQs5Hqee0XM8&dib_tag=se&keywords=m3%2B30mm&qid=1749001163&sprefix=m3%2B30mm%2Caps%2C181&sr=8-23&th=1
|m3 x 15mm(chop down 20mm)	| $7.00	|https://www.amazon.com/Socket-Screw-Thread-stainless-100pcs/dp/B078CXM81F?|crid=SVZ6ZVO9CH88&dib=eyJ2IjoiMSJ9.q6E9NIbUqM2ZUEv1RWL1WRtvKj3SNLDo2R1ZT8rj0JjJymfK7DlziPyPhQ9RmYXqtFsmmF5RfL8V4i02E_YMdOe8PfafsIYf-f2_rEaEErhMN4e815gjUTRqY2QU83KdpUdh8nADbf6dZQZNQqsK2pDqByec_Kuya0WOqCijrjozfrKOcGIRmeSK5eXGzWMCCAY-3pPW9X5ySbmHxO28B7zKEQrdl4dj_4N4csIqrsQ.U1aUu0Slo90zMGR9u3oTCXOrKLJl8OYB_KGRmXcT-MM&dib_tag=se&keywords=m3%2B20mm&qid=1749000859&sprefix=m3%2B20mm%2Caps%2C140&sr=8-3&th=1|
|Heatset Inserts	| $8.00	|https://www.aliexpress.us/item/2255800046543591.html?aff_fcid=b276c905df0d4e15bdf68bb6aa0dd61b-1749004809574-03378-_DkeMr5Z&tt=CPS_NORMAL&aff_fsk=_DkeMr5Z&aff_platform=shareComponent-detail&sk=_DkeMr5Z&aff_trace_key=b276c905df0d4e15bdf68bb6aa0dd61b-1749004809574-03378-_DkeMr5Z&terminal_id=ffcf64e248684970b8fdbe380ac19e19&afSmartRedirect=y&gatewayAdapt=glo2usa4itemAdapt|
|bearings 5x14	| $8.00	|https://www.amazon.com/HiPicco-605-2RS-Bearings-Miniature-Pre-Lubricated/dp/B0CH2X65Y6?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&smid=A8J8GEQFEWSTZ&gQT=1&th=1|
||||	
|Extruder + Hotend| | |
||||
|Trianglelab v6 all metal hotend	| $15.00	|https://trianglelab.net/products/v6-all-metal-hotend?VariantsId=10012|
|BMG clone cxtruder	| $6.00	|https://www.aliexpress.us/item/3256805805447850.html?spm=a2g0o.productlist.main.7.3ce93ae14ou9FX&algo_pvid=d5674794-46ca-47b3-b12f-8cb1f652468e&algo_exp_id=d5674794-46ca-47b3-b12f-8cb1f652468e-6&pdp_ext_f=%7B%22order%22%3A%22127%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21USD%215.91%215.71%21%21%2142.37%2140.94%21%40210337bc17490034624662927e7119%2112000035210668495%21sea%21US%210%21ABX&curPageLogUid=Q1lIWxmGTDVg&utparam-url=scene%3Asearch%7Cquery_from%3A|
|Pankake stepper for extruder	| $5.00	|https://www.omc-stepperonline.com/e-series-nema-17-bipolar-1-8deg-17ncm-24-07oz-in-1a-42x42x23mm-4-wires-17he08-1004s|
|PTFE tube	| $2.00	|https://www.aliexpress.us/item/3256801260455800.html?aff_fcid=97c620ad2f4e44be9e412feb78f18f93-1749004715048-07628-_DFB3fCX&tt=CPS_NORMAL&aff_fsk=_DFB3fCX&aff_platform=shareComponent-detail&sk=_DFB3fCX&aff_trace_key=97c620ad2f4e44be9e412feb78f18f93-1749004715048-07628-_DFB3fCX&terminal_id=ffcf64e248684970b8fdbe380ac19e19&afSmartRedirect=y&gatewayAdapt=glo2usa4itemAdapt|
||||	
|BED| | |
||||
|Buildplate	| $16.00	|https://www.aliexpress.us/item/3256808481230553.html?src=google&pdp_npi=4%40dis%21USD%2110.46%2110.46%21%21%21%21%21%40%2112000046161234568%21ppc%21%21%21&gPromoCode=5000000169902232&gQT=1&gatewayAdapt=glo2usa#nav-specification|
|100 x 100mm Heater	| $11.00	|https://s.click.aliexpress.com/e/_DdKRBD1|
|Bed Springs and M3 Bolts	| $4.00	|https://s.click.aliexpress.com/e/_DFBWBZP|
||||		
|Electronics| | |
||||
|Power supply - Mean Well |	$29	|https://www.digikey.com/en/products/detail/mean-well-usa-inc/LRS-150-24/7705015|
|klipper laptop (instead of pi)	| freeeeee	|old vaio|
|btt spyder	| $40	|https://www.aliexpress.us/item/3256802425339653.html?gatewayAdapt=glo2usa4itemAdapt|
|4010 fans	| $6	|https://www.aliexpress.us/item/2251832626712781.html?spm=a2g0o.productlist.main.8.c25efaacf2UqnC&algo_pvid=cde8af7f-ee07-41fe-bd00-f1e11ec8b71e&algo_exp_id=cde8af7f-ee07-41fe-bd00-f1e11ec8b71e-7&pdp_ext_f=%7B%22order%22%3A%22134%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21USD%212.37%212.37%21%21%212.37%212.37%21%402103277f17490017840836254e2b29%2165355038955%21sea%21US%210%21ABX&curPageLogUid=2moNP351FL7n&utparam-url=scene%3Asearch%7Cquery_from%3A|
|5015 fans	| $8	|https://www.aliexpress.us/item/3256804896091521.html?spm=a2g0o.productlist.main.5.24292dfdyUQBOp&algo_pvid=8f5fd244-3051-47f3-8ee1-9b274c699314&algo_exp_id=8f5fd244-3051-47f3-8ee1-9b274c699314-4&pdp_ext_f=%7B%22order%22%3A%22115%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21USD%215.03%214.13%21%21%215.03%214.13%21%40210318c317490019106188148e39e0%2112000031576133991%21sea%21US%210%21ABX&curPageLogUid=lK1PGSptyFsF&utparam-url=scene%3Asearch%7Cquery_from%3A|
|limit switches	| $3	|https://www.aliexpress.us/item/3256801412797483.html?spm=a2g0o.detail.pcDetailTopMoreOtherSeller.1.7281EN7iEN7iEw&gps-id=pcDetailTopMoreOtherSeller&scm=1007.14452.396806.0&scm_id=1007.14452.396806.0&scm-url=1007.14452.396806.0&pvid=b97728e4-87ac-45ef-88c4-bf1cdbf0d7cc&_t=gps-id:pcDetailTopMoreOtherSeller,scm-url:1007.14452.396806.0,pvid:b97728e4-87ac-45ef-88c4-bf1cdbf0d7cc,tpp_buckets:668%232846%238114%231999&pdp_ext_f=%7B%22order%22%3A%22441%22%2C%22eval%22%3A%221%22%2C%22sceneId%22%3A%2230050%22%7D&pdp_npi=4%40dis%21USD%212.93%212.55%21%21%212.93%212.55%21%402101c5ac17490034128137397e69ea%2112000047027348662%21rec%21US%21%21ABXZ&utparam-url=scene%3ApcDetailTopMoreOtherSeller%7Cquery_from%3A&search_p4p_id=202506031916528631335802323094798288_0|
||||
|TOTAL USD	| $342.00| |


