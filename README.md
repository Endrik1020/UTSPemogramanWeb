# UTSPemogramanWeb
~~~
Nama   = Endrik
NIM    = 311910088
Kelas  = TI.19.C.1
Universitas Pelita Bangsa
Tugas UTS Pemograman Web
~~~
# Langkah-langkah Praktikum
 Mencari mockup/sketsa desain web (dalam format psd, png, cdr, svg, dll)
	Cari di web https://www.graphberry.com
![web](https://user-images.githubusercontent.com/81820421/117516632-d6133a80-afc3-11eb-9302-4ae8ccf95838.JPG)

# Pilih mockup design sesuai selera kalian , saya pilih seperti ini . 
Link mockup : https://www.graphberry.com/item/nord-free-simple-app-landingage-one-page-template
![1](https://user-images.githubusercontent.com/81820421/117516743-24c0d480-afc4-11eb-81df-6156cab4a747.JPG)

# Setelah itu kita  download mock up nya.
Setelah didownload file harus di extraxt terlebih dahulu dan akan muncul file psd nya .
![2](https://user-images.githubusercontent.com/81820421/117516833-72d5d800-afc4-11eb-8360-5b59f4fda137.JPG)
![3](https://user-images.githubusercontent.com/81820421/117516836-74070500-afc4-11eb-8289-139fc43b0b7a.JPG)

File psd kita convert menjadi html . 

# Setelah kita mendapatkan sourcodenya html dan css , buka di aplikasi visual code.
![4](https://user-images.githubusercontent.com/81820421/117516933-c47e6280-afc4-11eb-8d7a-0d2864a77f8c.JPG)
![5](https://user-images.githubusercontent.com/81820421/117516938-c6482600-afc4-11eb-9c79-df897e7ac924.JPG)
~~~
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"	"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
	<head>
		<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
		<title>psdtowebNordSimpleAppPresentationPage.psd</title>
		<link href="styles.css" rel="stylesheet" type="text/css">
	</head>
	<body>
		<div id="background">
			<div id="Background"><img src="images/Background.png"></div>
			<div id="Path"><img src="images/Path.png"></div>
			<div id="2016NORDAllR"><img src="images/2016NORDAllR.png"></div>
			<div id="Logo"><img src="images/Logo.png"></div>
			<div id="ADDIMAGEHERE"><img src="images/ADDIMAGEHERE.png"></div>
			<div id="Mask"><img src="images/Mask.png"></div>
			<div id="Left"><img src="images/Left.png"></div>
			<div id="Right1"><img src="images/Right1.png"></div>
			<div id="Right2"><img src="images/Right2.png"></div>
			<div id="Mid"><img src="images/Mid.png"></div>
			<div id="Path_0"><img src="images/Path_0.png"></div>
			<div id="JohnDoe"><img src="images/JohnDoe.png"></div>
			<div id="layer_13"><img src="images/layer_13.png"></div>
			<div id="Peoplearedefinitel"><img src="images/Peoplearedefinitel.png"></div>
			<div id="layer_15"><img src="images/layer_15.png"></div>
			<div id="VectorPhone"><img src="images/VectorPhone.png"></div>
			<div id="Screen"><img src="images/Screen.png"></div>
			<div id="Peoplearedefinitel_0"><img src="images/Peoplearedefinitel_0.png"></div>
			<div id="Somewordsfromour"><img src="images/Somewordsfromour.png"></div>
			<div id="Path_1"><img src="images/Path_1.png"></div>
			<div id="SendButton"><img src="images/SendButton.png"></div>
			<div id="SEND"><img src="images/SEND.png"></div>
			<div id="TypeForm"><img src="images/TypeForm.png"></div>
			<div id="YourMail"><img src="images/YourMail.png"></div>
			<div id="Wewillsendyoufro"><img src="images/Wewillsendyoufro.png"></div>
			<div id="Joinus"><img src="images/Joinus.png"></div>
			<div id="Path_2"><img src="images/Path_2.png"></div>
			<div id="Path_3"><img src="images/Path_3.png"></div>
			<div id="VectorPhone_0"><img src="images/VectorPhone_0.png"></div>
			<div id="Screen_0"><img src="images/Screen_0.png"></div>
			<div id="PlayButton"><img src="images/PlayButton.png"></div>
			<div id="Peoplearedefinitel_1"><img src="images/Peoplearedefinitel_1.png"></div>
			<div id="Joinmorethan1000"><img src="images/Joinmorethan1000.png"></div>
			<div id="Button"><img src="images/Button.png"></div>
			<div id="SUBSCRIBE"><img src="images/SUBSCRIBE.png"></div>
			<div id="GETITNOW"><img src="images/GETITNOW.png"></div>
			<div id="Logo_0"><img src="images/Logo_0.png"></div>
			<div id="Path_4"><img src="images/Path_4.png"></div>
			<div id="Left_0"><img src="images/Left_0.png"></div>
			<div id="Right"><img src="images/Right.png"></div>
			<div id="Right2_0"><img src="images/Right2_0.png"></div>
			<div id="Mid_0"><img src="images/Mid_0.png"></div>
			<div id="Screen2"><img src="images/Screen2.png"></div>
			<div id="Screen1"><img src="images/Screen1.png"></div>
			<div id="Button_0"><img src="images/Button_0.png"></div>
			<div id="GETITNOW_0"><img src="images/GETITNOW_0.png"></div>
			<div id="Peoplearedefinitel_2"><img src="images/Peoplearedefinitel_2.png"></div>
			<div id="Whatyouget"><img src="images/Whatyouget.png"></div>
			<div id="GRID960Pix"><img src="images/GRID960Pix.png"></div>
		</div>
 </body>
 </html>
 ~~~
![css](https://user-images.githubusercontent.com/81820421/117516941-c6e0bc80-afc4-11eb-9e8a-a52cfe90cc03.JPG)
~~~
 body {
	margin: 0;
	padding: 0;
 }
 
 #background 
{ 
	 left: 0px; 
	 top: 0px; 
	 position: relative; 
	 margin-left: auto; 
	 margin-right: auto; 
	 width: 1920px;
	 height: 3395px; 
	 overflow: hidden;
	 z-index:0;
	} 

 #Background 
{ 
	 left: 0px; 
	 top: 0px; 
	 position: absolute; 
	 width: 1920px;
	 height: 3395px;
	 z-index:1;
} 

 #Path 
{ 
	 left: -1px; 
	 top: 3099px; 
	 position: absolute; 
	 width: 1922px;
	 height: 297px;
	 z-index:2;
} 

 #2016NORDAllR 
{ 
	 left: 836px; 
	 top: 3289px; 
	 position: absolute; 
	 width: 234px;
	 height: 16px;
	 z-index:3;
} 

 #Logo 
{ 
	 left: 934px; 
	 top: 3180px; 
	 position: absolute; 
	 width: 54px;
	 height: 68px;
	 z-index:4;
} 

 #ADDIMAGEHERE 
{ 
	 left: 0px; 
	 top: 1760px; 
	 position: absolute; 
	 width: 1920px;
	 height: 900px;
	 z-index:5;
} 

 #Mask 
{ 
	 left: -1px; 
	 top: 1759px; 
	 position: absolute; 
	 width: 1922px;
	 height: 902px;
	 z-index:6;
} 

 #Left 
{ 
	 left: 1087px; 
	 top: 2580px; 
	 position: absolute; 
	 width: 16px;
	 height: 16px;
	 z-index:7;
} 

 #Right1 
{ 
	 left: 1151px; 
	 top: 2580px; 
	 position: absolute; 
	 width: 16px;
	 height: 16px;
	 z-index:8;
} 

 #Right2 
{ 
	 left: 1173px; 
	 top: 2580px; 
	 position: absolute; 
	 width: 16px;
	 height: 16px;
	 z-index:9;
} 

 #Mid 
{ 
	 left: 1111px; 
	 top: 2580px; 
	 position: absolute; 
	 width: 29px;
	 height: 15px;
	 z-index:10;
} 

 #Path_0 
{ 
	 left: 813px; 
	 top: 2317px; 
	 position: absolute; 
	 width: 617px;
	 height: 234px;
	 z-index:11;
} 

 #JohnDoe 
{ 
	 left: 911px; 
	 top: 2494px; 
	 position: absolute; 
	 width: 65px;
	 height: 15px;
	 z-index:12;
} 

 #layer_13 
{ 
	 left: 870px; 
	 top: 2350px; 
	 position: absolute; 
	 width: 14px;
	 height: 10px;
	 z-index:13;
} 

 #Peoplearedefinitel 
{ 
	 left: 912px; 
	 top: 2380px; 
	 position: absolute; 
	 width: 442px;
	 height: 82px;
	 z-index:14;
} 

 #layer_15 
{ 
	 left: 1356px; 
	 top: 2501px; 
	 position: absolute; 
	 width: 14px;
	 height: 10px;
	 z-index:15;
} 

 #VectorPhone 
{ 
	 left: 488px; 
	 top: 2206px; 
	 position: absolute; 
	 width: 311px;
	 height: 630px;
	 z-index:16;
} 

 #Screen 
{ 
	 left: 509px; 
	 top: 2282px; 
	 position: absolute; 
	 width: 269px;
	 height: 479px;
	 z-index:17;
} 

 #Peoplearedefinitel_0 
{ 
	 left: 837px; 
	 top: 2063px; 
	 position: absolute; 
	 width: 332px;
	 height: 49px;
	 z-index:18;
} 

 #Somewordsfromour 
{ 
	 left: 718px; 
	 top: 1988px; 
	 position: absolute; 
	 width: 587px;
	 height: 33px;
	 z-index:19;
} 

 #Path_1 
{ 
	 left: -1px; 
	 top: 2659px; 
	 position: absolute; 
	 width: 1922px;
	 height: 442px;
	 z-index:20;
} 

 #SendButton 
{ 
	 left: 1130px; 
	 top: 2954px; 
	 position: absolute; 
	 width: 141px;
	 height: 52px;
	 z-index:21;
} 

 #SEND 
{ 
	 left: 1182px; 
	 top: 2975px; 
	 position: absolute; 
	 width: 38px;
	 height: 11px;
	 z-index:22;
} 

 #TypeForm 
{ 
	 left: 649px; 
	 top: 2954px; 
	 position: absolute; 
	 width: 462px;
	 height: 52px;
	 z-index:23;
} 

 #YourMail 
{ 
	 left: 677px; 
	 top: 2974px; 
	 position: absolute; 
	 width: 65px;
	 height: 12px;
	 z-index:24;
} 

 #Wewillsendyoufro 
{ 
	 left: 839px; 
	 top: 2822px; 
	 position: absolute; 
	 width: 244px;
	 height: 45px;
	 z-index:25;
} 

 #Joinus 
{ 
	 left: 890px; 
	 top: 2743px; 
	 position: absolute; 
	 width: 145px;
	 height: 42px;
	 z-index:26;
} 

 #Path_2 
{ 
	 left: -1px; 
	 top: -1px; 
	 position: absolute; 
	 width: 1922px;
	 height: 902px;
	 z-index:27;
} 

 #Path_3 
{ 
	 left: -1px; 
	 top: -1px; 
	 position: absolute; 
	 width: 961px;
	 height: 901px;
	 z-index:28;
} 

 #VectorPhone_0 
{ 
	 left: 495px; 
	 top: 350px; 
	 position: absolute; 
	 width: 311px;
	 height: 630px;
	 z-index:29;
} 

 #Screen_0 
{ 
	 left: 516px; 
	 top: 426px; 
	 position: absolute; 
	 width: 269px;
	 height: 479px;
	 z-index:30;
} 

 #PlayButton 
{ 
	 left: 971px; 
	 top: 756px; 
	 position: absolute; 
	 width: 171px;
	 height: 58px;
	 z-index:31;
} 

 #Peoplearedefinitel_1 
{ 
	 left: 974px; 
	 top: 558px; 
	 position: absolute; 
	 width: 340px;
	 height: 115px;
	 z-index:32;
} 

 #Joinmorethan1000 
{ 
	 left: 973px; 
	 top: 370px; 
	 position: absolute; 
	 width: 453px;
	 height: 98px;
	 z-index:33;
} 

 #Button 
{ 
	 left: 1289px; 
	 top: 60px; 
	 position: absolute; 
	 width: 142px;
	 height: 48px;
	 z-index:34;
} 

 #SUBSCRIBE 
{ 
	 left: 1165px; 
	 top: 79px; 
	 position: absolute; 
	 width: 66px;
	 height: 9px;
	 z-index:35;
} 

 #GETITNOW 
{ 
	 left: 1327px; 
	 top: 79px; 
	 position: absolute; 
	 width: 70px;
	 height: 9px;
	 z-index:36;
} 

 #Logo_0 
{ 
	 left: 533px; 
	 top: 19px; 
	 position: absolute; 
	 width: 54px;
	 height: 68px;
	 z-index:37;
} 

 #Path_4 
{ 
	 left: -1px; 
	 top: 898px; 
	 position: absolute; 
	 width: 1922px;
	 height: 863px;
	 z-index:38;
} 

 #Left_0 
{ 
	 left: 1151px; 
	 top: 1558px; 
	 position: absolute; 
	 width: 16px;
	 height: 16px;
	 z-index:39;
} 

 #Right 
{ 
	 left: 1212px; 
	 top: 1558px; 
	 position: absolute; 
	 width: 16px;
	 height: 16px;
	 z-index:40;
} 

 #Right2_0 
{ 
	 left: 1236px; 
	 top: 1558px; 
	 position: absolute; 
	 width: 16px;
	 height: 16px;
	 z-index:41;
} 

 #Mid_0 
{ 
	 left: 1175px; 
	 top: 1558px; 
	 position: absolute; 
	 width: 28px;
	 height: 16px;
	 z-index:42;
} 

 #Screen2 
{ 
	 left: 1202px; 
	 top: 1135px; 
	 position: absolute; 
	 width: 228px;
	 height: 404px;
	 z-index:43;
} 

 #Screen1 
{ 
	 left: 963px; 
	 top: 1135px; 
	 position: absolute; 
	 width: 228px;
	 height: 404px;
	 z-index:44;
} 

 #Button_0 
{ 
	 left: 490px; 
	 top: 1478px; 
	 position: absolute; 
	 width: 140px;
	 height: 48px;
	 z-index:45;
} 

 #GETITNOW_0 
{ 
	 left: 528px; 
	 top: 1496px; 
	 position: absolute; 
	 width: 70px;
	 height: 9px;
	 z-index:46;
} 

 #Peoplearedefinitel_2 
{ 
	 left: 488px; 
	 top: 1271px; 
	 position: absolute; 
	 width: 340px;
	 height: 115px;
	 z-index:47;
} 

 #Whatyouget 
{ 
	 left: 490px; 
	 top: 1138px; 
	 position: absolute; 
	 width: 283px;
	 height: 43px;
	 z-index:48;
} 

 #GRID960Pix 
{ 
	 left: 489px; 
	 top: -1px; 
	 position: absolute; 
	 width: 942px;
	 height: 3397px;
	 z-index:49;
} 
~~~
# Dan ini  Gambar sumber dari desain mockup tersebut.
![6](https://user-images.githubusercontent.com/81820421/117516984-dfe96d80-afc4-11eb-815f-2ea32de8bae8.JPG)

# Ini tampilan index.html yang saya buat dan design mockupnya.
![7](https://user-images.githubusercontent.com/81820421/117517023-fa234b80-afc4-11eb-9740-19e45c642e57.JPG)
![8](https://user-images.githubusercontent.com/81820421/117517032-fbed0f00-afc4-11eb-988a-dbc6d33f0c96.JPG)
![9](https://user-images.githubusercontent.com/81820421/117517038-fc85a580-afc4-11eb-8aec-64fb5ca6cfc9.JPG)
![10](https://user-images.githubusercontent.com/81820421/117517046-fe4f6900-afc4-11eb-9336-160b5622a6cf.JPG)




