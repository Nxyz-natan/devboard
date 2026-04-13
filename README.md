# devboard
A compact ESP32 development board with onboard 2" ST7789 display, USB-C, LiPo charging via IP5306, GPIO headers, status LEDs, and CH340C for easy programming. Built on the ESP32-WROOM-32 for WiFi and Bluetooth.
<img width="427" height="559" alt="Screenshot 2026-04-13 at 12 08 58 AM" src="https://github.com/user-attachments/assets/cacffb9f-cc92-431f-b44d-2bac1c634d1c" />
my finished pcb
<img width="773" height="546" alt="Screenshot 2026-04-13 at 3 15 34 PM" src="https://github.com/user-attachments/assets/d3416a85-79ae-4812-b957-df050be96e86" />

my finished schematics
Name	Purpose	Quantity	Total Cost (USD)	Link	Distributor
pcb	pcb		1.5		jlcpcb
mini hotplate 	soldering	1	13.26		amazon
YICUAA 523450 3.7v 1000mAh Battery Rechargeable LI-PO Battery with JST Connector for Household Appliances	battery	1	7.83		amazon
LCSC-boards LCKFB-st7789-2.0inch-screen	screen	1	7.67	https://www.lcsc.com/product-detail/C53184555.html?spm=wm.gwc.xh.20.cbm___wm.ssy.ssl.gwc&lcsc_vid=ElILAgAEQVUPAgEDTldfUFVVQgMPUQdXRlUMVFMHQVcxVlNRQVBeV1FUR1NaVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS	lcsc
ESPRESSIF ESP32-WROOM-32-N4	mcu	1	4.29	https://www.lcsc.com/product-detail/C82899.html?spm=wm.gwc.xh.19.cbm___wm.ssy.ssl.gwc&lcsc_vid=ElILAgAEQVUPAgEDTldfUFVVQgMPUQdXRlUMVFMHQVcxVlNRQVBeV1FUR1NaVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS	lcsc
Korean Hroparts Elec K2-1102SP-C4SC-04	component	10	0.45	https://www.lcsc.com/product-detail/C127509.html?spm=wm.gwc.xh.18.cbm___wm.ssy.ssl.gwc&lcsc_vid=ElILAgAEQVUPAgEDTldfUFVVQgMPUQdXRlUMVFMHQVcxVlNRQVBeV1FUR1NaVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS	lcsc
YONGYUTAI YLED0402Y	component	50	0.69	https://www.lcsc.com/product-detail/C20608782.html?spm=wm.gwc.xh.17.cbm___wm.ssy.ssl.gwc&lcsc_vid=ElILAgAEQVUPAgEDTldfUFVVQgMPUQdXRlUMVFMHQVcxVlNRQVBeV1FUR1NaVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS	lcsc
EVERLIGHT 16-213/GHC-YR1S1/3T	component	10	0.43	https://www.lcsc.com/product-detail/C74338.html?spm=wm.gwc.xh.16.cbm___wm.ssy.ssl.gwc&lcsc_vid=ElILAgAEQVUPAgEDTldfUFVVQgMPUQdXRlUMVFMHQVcxVlNRQVBeV1FUR1NaVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS	lcsc
NATIONSTAR NCD0805R1	component	50	0.67	https://www.lcsc.com/product-detail/C84256.html?spm=wm.gwc.xh.15.cbm___wm.ssy.ssl.gwc&lcsc_vid=ElILAgAEQVUPAgEDTldfUFVVQgMPUQdXRlUMVFMHQVcxVlNRQVBeV1FUR1NaVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS	lcsc
YAGEO RC0402FR-07100RL	component	100	0.09	https://www.lcsc.com/product-detail/C106232.html?spm=wm.gwc.xh.14.cbm___wm.ssy.ssl.gwc&lcsc_vid=ElILAgAEQVUPAgEDTldfUFVVQgMPUQdXRlUMVFMHQVcxVlNRQVBeV1FUR1NaVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS	lcsc
UNI-ROYAL 0402WGF1001TCE	component	100	0.07	https://www.lcsc.com/product-detail/C11702.html?spm=wm.gwc.xh.13.cbm___wm.ssy.ssl.gwc&lcsc_vid=ElILAgAEQVUPAgEDTldfUFVVQgMPUQdXRlUMVFMHQVcxVlNRQVBeV1FUR1NaVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS	lcsc
YAGEO RC0603FR-0710KL	component	100	0.15	https://www.lcsc.com/product-detail/C98220.html?spm=wm.gwc.xh.12.cbm___wm.ssy.ssl.gwc&lcsc_vid=ElILAgAEQVUPAgEDTldfUFVVQgMPUQdXRlUMVFMHQVcxVlNRQVBeV1FUR1NaVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS	lcsc
YAGEO RC0402FR-075K1L	component	100	0.09	https://www.lcsc.com/product-detail/C105872.html?spm=wm.gwc.xh.11.cbm___wm.ssy.ssl.gwc&lcsc_vid=ElILAgAEQVUPAgEDTldfUFVVQgMPUQdXRlUMVFMHQVcxVlNRQVBeV1FUR1NaVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS	lcsc
Samsung Electro-Mechanics CL31A107MQHNNNE	component	10	0.61	https://www.lcsc.com/product-detail/C15008.html?spm=wm.gwc.xh.10.cbm___wm.ssy.ssl.gwc&lcsc_vid=ElILAgAEQVUPAgEDTldfUFVVQgMPUQdXRlUMVFMHQVcxVlNRQVBeV1FUR1NaVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS	lcsc
YAGEO CC0402KRX7R7BB104	led	100	0.1	https://www.lcsc.com/product-detail/C60474.html	lcsc
Samsung Electro-Mechanics CL10A106KP8NNNC	component	50	0.4	https://www.lcsc.com/product-detail/C19702.html	lcsc
BOOMELE(Boom Precision Elec) 2.54-1*20P	component	50	0.72	https://www.lcsc.com/product-detail/C50981.html	lcsc
BOOMELE(Boom Precision Elec) 2.54-1*2P	component	10	0.61	https://www.lcsc.com/product-detail/C49661.html	lcsc
Korean Hroparts Elec TYPE-C-31-M-12	component	5	0.85	https://www.lcsc.com/product-detail/C165948.html	lcsc
JSCJ MMBT3904(RANGE:100-300)	component	50	0.49	https://www.lcsc.com/product-detail/C20526.html	lcsc
JSCJ 2N7002	component	50	0.67	https://www.lcsc.com/product-detail/C8545.html	lcsc
INJOINIC IP5306	component	5	1.41	https://www.lcsc.com/product-detail/C181692.html	lcsc
Advanced Monolithic Systems AMS1117-3.3	compents	5	1.13	https://www.lcsc.com/product-detail/C6186.html	lcsc
CH340C	component	1	0.58	https://www.lcsc.com/product-detail/C84681.html?spm=wm.gwc.xqv.0.xq___wm.ssy.ssl.gwc&lcsc_vid=ElILAgAEQVUPAgEDTldfUFVVQgMPUQdXRlUMVFMHQVcxVlNRQVBeV1FUR1NaVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS	lcsc
