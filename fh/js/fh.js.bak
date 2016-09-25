window.onload=main;



function main(){

//开始第一幅广告变换代码
var num=0;
var a1=[];
a1[0]='img/g211.jpg';
a1[1]='img/g10.jpg';
a1[2]='img/g11.jpg';

var photo1=function(){

if(num>a1.length-1)
	num=0;

var chg1=document.getElementById('b1');
chg1.src=a1[num];
++num;

setTimeout(photo1,5000);

}

photo1();


//开始第二幅广告变换代码

var num1=0;
var a2=[];
a2[0]='img/g1.jpg';
a2[1]='img/g2.jpg';
a2[2]='img/g3.jpg';
a2[3]='img/g41.jpg';


var photo2=function(){

if(num1>a2.length-1)
	num1=0;

var chg2=document.getElementById('b2');
chg2.src=a2[num1];
++num1;

setTimeout(photo2,3000);

}

photo2();

//开始数据块自动变化显示)（网页中间栏下方区域）

var num3=0;
var a3=[];
a3[0]="xz1";
a3[1]="xz2";
a3[2]="xz3";
a3[3]="xz4";
a3[4]="xz5";

var divchg=function(){
	
	  var c12=document.getElementById("c12");
	  var c13=document.getElementById("c13");
	  var c14=document.getElementById("c14");
	  var c15=document.getElementById("c15");
	  var c16=document.getElementById("c16");
	
	   if(num3>a3.length-1)
			  num3=0;
	   
	   var chg3=document.getElementById(a3[num3]);

	   if((num3==0)){
			 
			 chg3.style.display="block";
			 c12.style.background="url(img/c11.jpg) no-repeat -71px 0px";
			 c13.style.background="url(img/c11.jpg) no-repeat -32px 0px";
			 c14.style.background="url(img/c11.jpg) no-repeat -48px 0px";
			 c15.style.background="url(img/c11.jpg) no-repeat -60px 0px";
			 c16.style.background="url(img/c11.jpg) no-repeat -19px 0px";
			 document.getElementById(a3[1]).style.display="none";
			 document.getElementById(a3[2]).style.display="none";
			 document.getElementById(a3[3]).style.display="none";
			 document.getElementById(a3[4]).style.display="none";



		}


		 if(num3==1){
		  chg3.style.display="block";
          c12.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  c13.style.background="url(img/c11.jpg) no-repeat -71px 0px";
		  c14.style.background="url(img/c11.jpg) no-repeat -48px 0px";
		  c15.style.background="url(img/c11.jpg) no-repeat -60px 0px";
		  c16.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  document.getElementById(a3[0]).style.display="none";
			 document.getElementById(a3[2]).style.display="none";
			 document.getElementById(a3[3]).style.display="none";
			 document.getElementById(a3[4]).style.display="none";

		 
		 }

		  if(num3==2){
			  chg3.style.display="block";
		  c13.style.background="url(img/c11.jpg) no-repeat -32px 0px";
		  c14.style.background="url(img/c11.jpg) no-repeat -74px 0px";
		  c15.style.background="url(img/c11.jpg) no-repeat -60px 0px";
		  c16.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  document.getElementById(a3[1]).style.display="none";
			 document.getElementById(a3[0]).style.display="none";
			 document.getElementById(a3[3]).style.display="none";
			 document.getElementById(a3[4]).style.display="none";


		 }

		  if(num3==3){
			  chg3.style.display="block";
			  c12.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  c13.style.background="url(img/c11.jpg) no-repeat -32px 0px";
		  c14.style.background="url(img/c11.jpg) no-repeat -48px 0px";
		  c15.style.background="url(img/c11.jpg) no-repeat -73px 0px";
		  c16.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  document.getElementById(a3[1]).style.display="none";
			 document.getElementById(a3[2]).style.display="none";
			 document.getElementById(a3[0]).style.display="none";
			 document.getElementById(a3[4]).style.display="none";

		 
		 }

		  if(num3==4){
			  chg3.style.display="block";
			  c12.style.background="url(img/c11.jpg) no-repeat -19px 0px";
          c13.style.background="url(img/c11.jpg) no-repeat -32px 0px";
		  c14.style.background="url(img/c11.jpg) no-repeat -48px 0px";
		  c15.style.background="url(img/c11.jpg) no-repeat -60px 0px";
		  c16.style.background="url(img/c11.jpg) no-repeat -71px 0px";
		  document.getElementById(a3[1]).style.display="none";
			 document.getElementById(a3[2]).style.display="none";
			 document.getElementById(a3[3]).style.display="none";
			 document.getElementById(a3[0]).style.display="none";

		 }
				     ++num3;  
        setTimeout(divchg,3000);
		
}

divchg();


//开始第段鼠标点击数据块变换代码(数据块自动变化显示,点击右边箭头)（网页中间栏下方区域）

/*
var num4=0;
var a3=[];
a3[0]="xz1";
a3[1]="xz2";
a3[2]="xz3";
a3[3]="xz4";
a3[4]="xz5";


var divchg1=function(){
	
	  var c12=document.getElementById("c12");
	  var c13=document.getElementById("c13");
	  var c14=document.getElementById("c14");
	  var c15=document.getElementById("c15");
	  var c16=document.getElementById("c16");
	
	   if(num4>a3.length-1)
			  num4=0;
	   
	   var chg3=document.getElementById(a3[num4]);

	   if((num4==0)){
			 document.getElementById(a3[a3.length-1]).style.display="none";
			 chg3.style.display="block";
			 c12.style.background="url(img/c11.jpg) no-repeat -71px 0px";

		}else if((num4!=0)){
			        document.getElementById(a3[num4-1]).style.display="none"
				    chg3.style.display="block";
					c12.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		 }

		 if(num4==1){
		  
		  c13.style.background="url(img/c11.jpg) no-repeat -71px 0px";

		 
		 }else if(num4!=1){
		 
		  c13.style.background="url(img/c11.jpg) no-repeat -32px 0px";

		 
		 }

		  if(num4==2){
		 
		  c14.style.background="url(img/c11.jpg) no-repeat -74px 0px";

		 }else if(num4!=2){
		 
		  c14.style.background="url(img/c11.jpg) no-repeat -48px 0px";

		 
		 }

		  if(num4==3){
		  c15.style.background="url(img/c11.jpg) no-repeat -73px 0px";

		 
		 }else if(num4!=3){
		  c15.style.background="url(img/c11.jpg) no-repeat -60px 0px";

		 
		 
		 }

		  if(num4==4){
		 
		  c16.style.background="url(img/c11.jpg) no-repeat -62px 0px";

		 }else if(num4!=4){
		 
		  c16.style.background="url(img/c11.jpg) no-repeat -19px 0px";

		 
		 }
				     ++num4;  
        
		
		
}*/

var num4=0;
var a3=[];
a3[0]="xz1";
a3[1]="xz2";
a3[2]="xz3";
a3[3]="xz4";
a3[4]="xz5";


var divchg1=function(){
	
	  var c12=document.getElementById("c12");
	  var c13=document.getElementById("c13");
	  var c14=document.getElementById("c14");
	  var c15=document.getElementById("c15");
	  var c16=document.getElementById("c16");
	
	   if(num4>a3.length-1)
			  num4=0;
	   
	   var chg3=document.getElementById(a3[num4]);

	   if((num4==0)){
			 
			 chg3.style.display="block";
			 c12.style.background="url(img/c11.jpg) no-repeat -71px 0px";
			 c13.style.background="url(img/c11.jpg) no-repeat -32px 0px";
			 c14.style.background="url(img/c11.jpg) no-repeat -48px 0px";
			 c15.style.background="url(img/c11.jpg) no-repeat -60px 0px";
			 c16.style.background="url(img/c11.jpg) no-repeat -19px 0px";
			 document.getElementById(a3[1]).style.display="none";
			 document.getElementById(a3[2]).style.display="none";
			 document.getElementById(a3[3]).style.display="none";
			 document.getElementById(a3[4]).style.display="none";



		}


		 if(num4==1){
		  chg3.style.display="block";
          c12.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  c13.style.background="url(img/c11.jpg) no-repeat -71px 0px";
		  c14.style.background="url(img/c11.jpg) no-repeat -48px 0px";
		  c15.style.background="url(img/c11.jpg) no-repeat -60px 0px";
		  c16.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  document.getElementById(a3[0]).style.display="none";
			 document.getElementById(a3[2]).style.display="none";
			 document.getElementById(a3[3]).style.display="none";
			 document.getElementById(a3[4]).style.display="none";

		 
		 }

		  if(num4==2){
			  chg3.style.display="block";
		  c13.style.background="url(img/c11.jpg) no-repeat -32px 0px";
		  c14.style.background="url(img/c11.jpg) no-repeat -74px 0px";
		  c15.style.background="url(img/c11.jpg) no-repeat -60px 0px";
		  c16.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  document.getElementById(a3[1]).style.display="none";
			 document.getElementById(a3[0]).style.display="none";
			 document.getElementById(a3[3]).style.display="none";
			 document.getElementById(a3[4]).style.display="none";


		 }

		  if(num4==3){
			  chg3.style.display="block";
			  c12.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  c13.style.background="url(img/c11.jpg) no-repeat -32px 0px";
		  c14.style.background="url(img/c11.jpg) no-repeat -48px 0px";
		  c15.style.background="url(img/c11.jpg) no-repeat -73px 0px";
		  c16.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  document.getElementById(a3[1]).style.display="none";
			 document.getElementById(a3[2]).style.display="none";
			 document.getElementById(a3[0]).style.display="none";
			 document.getElementById(a3[4]).style.display="none";

		 
		 }

		  if(num4==4){
			  chg3.style.display="block";
			  c12.style.background="url(img/c11.jpg) no-repeat -19px 0px";
          c13.style.background="url(img/c11.jpg) no-repeat -32px 0px";
		  c14.style.background="url(img/c11.jpg) no-repeat -48px 0px";
		  c15.style.background="url(img/c11.jpg) no-repeat -60px 0px";
		  c16.style.background="url(img/c11.jpg) no-repeat -71px 0px";
		  document.getElementById(a3[1]).style.display="none";
			 document.getElementById(a3[2]).style.display="none";
			 document.getElementById(a3[3]).style.display="none";
			 document.getElementById(a3[0]).style.display="none";

		 }
				     ++num4;  
}

document.getElementById("c17").onclick=divchg1;



//开始第段鼠标点击数据块变换代码(数据块自动变化显示,点击左边箭头)（网页中间栏下方区域）

/*
var num5=4;
var a3=[];
a3[0]="xz1";
a3[1]="xz2";
a3[2]="xz3";
a3[3]="xz4";
a3[4]="xz5";


var divchg2=function(){
	
	  var c12=document.getElementById("c12");
	  var c13=document.getElementById("c13");
	  var c14=document.getElementById("c14");
	  var c15=document.getElementById("c15");
	  var c16=document.getElementById("c16");
	
	   if(num5<0)
			  num5=4;
	   
	   var chg3=document.getElementById(a3[num5]);

	   if((num5==4)){
			 document.getElementById(a3[0]).style.display="none";
			 chg3.style.display="block";
			 

		}else if((num5!=4)){
			        document.getElementById(a3[num5+1]).style.display="none"
				    chg3.style.display="block";
					
		 }


    if(num5==0){
	c12.style.background="url(img/c11.jpg) no-repeat -71px 0px";
	
	}else if(num5!=0){
	
	c12.style.background="url(img/c11.jpg) no-repeat -19px 0px";
	
	}


		 if(num5==1){
		  
		  c13.style.background="url(img/c11.jpg) no-repeat -71px 0px";

		 
		 }else if(num5!=1){
		 
		  c13.style.background="url(img/c11.jpg) no-repeat -32px 0px";

		 
		 }

		  if(num5==2){
		 
		  c14.style.background="url(img/c11.jpg) no-repeat -74px 0px";

		 }else if(num5!=2){
		 
		 c14.style.background="url(img/c11.jpg) no-repeat -48px 0px";

		 
		 }

		  if(num5==3){
		  c15.style.background="url(img/c11.jpg) no-repeat -73px 0px";

		 
		 }else if(num5!=3){
		 c15.style.background="url(img/c11.jpg) no-repeat -60px 0px";

		 
		 
		 }

		  if(num5==4){
		 
		 c16.style.background="url(img/c11.jpg) no-repeat -62px 0px";

		 }else if(num5!=4){
		 
		  c16.style.background="url(img/c11.jpg) no-repeat -19px 0px";

		 
		 }
				     --num5;  
        
		
		
}*/
var num5=4;
var a3=[];
a3[0]="xz1";
a3[1]="xz2";
a3[2]="xz3";
a3[3]="xz4";
a3[4]="xz5";


var divchg2=function(){
	
	  var c12=document.getElementById("c12");
	  var c13=document.getElementById("c13");
	  var c14=document.getElementById("c14");
	  var c15=document.getElementById("c15");
	  var c16=document.getElementById("c16");
	
	   if(num5<0)
			  num5=4;
	   
	   var chg3=document.getElementById(a3[num5]);

 if((num5==0)){
			 
			 chg3.style.display="block";
			 c12.style.background="url(img/c11.jpg) no-repeat -71px 0px";
			 c13.style.background="url(img/c11.jpg) no-repeat -32px 0px";
			 c14.style.background="url(img/c11.jpg) no-repeat -48px 0px";
			 c15.style.background="url(img/c11.jpg) no-repeat -60px 0px";
			 c16.style.background="url(img/c11.jpg) no-repeat -19px 0px";
			 document.getElementById(a3[1]).style.display="none";
			 document.getElementById(a3[2]).style.display="none";
			 document.getElementById(a3[3]).style.display="none";
			 document.getElementById(a3[4]).style.display="none";



		}


		 if(num5==1){
		  chg3.style.display="block";
          c12.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  c13.style.background="url(img/c11.jpg) no-repeat -71px 0px";
		  c14.style.background="url(img/c11.jpg) no-repeat -48px 0px";
		  c15.style.background="url(img/c11.jpg) no-repeat -60px 0px";
		  c16.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  document.getElementById(a3[0]).style.display="none";
			 document.getElementById(a3[2]).style.display="none";
			 document.getElementById(a3[3]).style.display="none";
			 document.getElementById(a3[4]).style.display="none";

		 
		 }

		  if(num5==2){
			  chg3.style.display="block";
		  c13.style.background="url(img/c11.jpg) no-repeat -32px 0px";
		  c14.style.background="url(img/c11.jpg) no-repeat -74px 0px";
		  c15.style.background="url(img/c11.jpg) no-repeat -60px 0px";
		  c16.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  document.getElementById(a3[1]).style.display="none";
			 document.getElementById(a3[0]).style.display="none";
			 document.getElementById(a3[3]).style.display="none";
			 document.getElementById(a3[4]).style.display="none";


		 }

		  if(num5==3){
			  chg3.style.display="block";
			  c12.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  c13.style.background="url(img/c11.jpg) no-repeat -32px 0px";
		  c14.style.background="url(img/c11.jpg) no-repeat -48px 0px";
		  c15.style.background="url(img/c11.jpg) no-repeat -73px 0px";
		  c16.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  document.getElementById(a3[1]).style.display="none";
			 document.getElementById(a3[2]).style.display="none";
			 document.getElementById(a3[0]).style.display="none";
			 document.getElementById(a3[4]).style.display="none";

		 
		 }

		  if(num5==4){
			  chg3.style.display="block";
			  c12.style.background="url(img/c11.jpg) no-repeat -19px 0px";
          c13.style.background="url(img/c11.jpg) no-repeat -32px 0px";
		  c14.style.background="url(img/c11.jpg) no-repeat -48px 0px";
		  c15.style.background="url(img/c11.jpg) no-repeat -60px 0px";
		  c16.style.background="url(img/c11.jpg) no-repeat -71px 0px";
		  document.getElementById(a3[1]).style.display="none";
			 document.getElementById(a3[2]).style.display="none";
			 document.getElementById(a3[3]).style.display="none";
			 document.getElementById(a3[0]).style.display="none";

		 }
		        --num5;
}

document.getElementById("c11").onclick=divchg2;

//开始第段鼠标滑过数据块变换代码(数据块自动变化显示,点击左边箭头)（网页中间栏下方区域）



var a3=[];
a3[0]="xz1";
a3[1]="xz2";
a3[2]="xz3";
a3[3]="xz4";
a3[4]="xz5";

var divchg3=function(){
      var num6=0;
      var c12=document.getElementById("c12");
	  var c13=document.getElementById("c13");
	  var c14=document.getElementById("c14");
	  var c15=document.getElementById("c15");
	  var c16=document.getElementById("c16");

	   
	   var chg3=document.getElementById(a3[num6]);

	  if(num6==0){
			 
			 chg3.style.display="block";
			 c12.style.background="url(img/c11.jpg) no-repeat -71px 0px";
			 c13.style.background="url(img/c11.jpg) no-repeat -32px 0px";
			 c14.style.background="url(img/c11.jpg) no-repeat -48px 0px";
			 c15.style.background="url(img/c11.jpg) no-repeat -60px 0px";
			 c16.style.background="url(img/c11.jpg) no-repeat -19px 0px";
			 document.getElementById(a3[1]).style.display="none";
			 document.getElementById(a3[2]).style.display="none";
			 document.getElementById(a3[3]).style.display="none";
			 document.getElementById(a3[4]).style.display="none";

		}

}

document.getElementById("c12").onmouseover=divchg3;

//开始第段鼠标滑过数据块变换代码(数据块自动变化显示,点击左边箭头)（网页中间栏下方区域）


var divchg4=function(){
      var num7=1;
      var c12=document.getElementById("c12");
	  var c13=document.getElementById("c13");
	  var c14=document.getElementById("c14");
	  var c15=document.getElementById("c15");
	  var c16=document.getElementById("c16");

	   
	   var chg3=document.getElementById(a3[num7]);

	  if(num7==1){
			 
			chg3.style.display="block";
          c12.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  c13.style.background="url(img/c11.jpg) no-repeat -71px 0px";
		  c14.style.background="url(img/c11.jpg) no-repeat -48px 0px";
		  c15.style.background="url(img/c11.jpg) no-repeat -60px 0px";
		  c16.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  document.getElementById(a3[0]).style.display="none";
			 document.getElementById(a3[2]).style.display="none";
			 document.getElementById(a3[3]).style.display="none";
			 document.getElementById(a3[4]).style.display="none";
		}

}

document.getElementById("c13").onmouseover=divchg4;

//开始第段鼠标滑过数据块变换代码(数据块自动变化显示,点击左边箭头)（网页中间栏下方区域）



var divchg5=function(){
      var num8=2;
      var c12=document.getElementById("c12");
	  var c13=document.getElementById("c13");
	  var c14=document.getElementById("c14");
	  var c15=document.getElementById("c15");
	  var c16=document.getElementById("c16");

	   
	   var chg3=document.getElementById(a3[num8]);

	  if(num8==2){
			 
			 chg3.style.display="block";
		  c13.style.background="url(img/c11.jpg) no-repeat -32px 0px";
		  c14.style.background="url(img/c11.jpg) no-repeat -74px 0px";
		  c15.style.background="url(img/c11.jpg) no-repeat -60px 0px";
		  c16.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  document.getElementById(a3[1]).style.display="none";
			 document.getElementById(a3[0]).style.display="none";
			 document.getElementById(a3[3]).style.display="none";
			 document.getElementById(a3[4]).style.display="none";
		}

}

document.getElementById("c14").onmouseover=divchg5;

//开始第段鼠标滑过数据块变换代码(数据块自动变化显示,点击左边箭头)（网页中间栏下方区域）


var divchg6=function(){
      var num9=3;
      var c12=document.getElementById("c12");
	  var c13=document.getElementById("c13");
	  var c14=document.getElementById("c14");
	  var c15=document.getElementById("c15");
	  var c16=document.getElementById("c16");

	   
	   var chg3=document.getElementById(a3[num9]);

	  if(num9==3){
			 
			 chg3.style.display="block";
			  c12.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  c13.style.background="url(img/c11.jpg) no-repeat -32px 0px";
		  c14.style.background="url(img/c11.jpg) no-repeat -48px 0px";
		  c15.style.background="url(img/c11.jpg) no-repeat -73px 0px";
		  c16.style.background="url(img/c11.jpg) no-repeat -19px 0px";
		  document.getElementById(a3[1]).style.display="none";
			 document.getElementById(a3[2]).style.display="none";
			 document.getElementById(a3[0]).style.display="none";
			 document.getElementById(a3[4]).style.display="none";
		}

}

document.getElementById("c15").onmouseover=divchg6;

//开始第段鼠标滑过数据块变换代码(数据块自动变化显示,点击左边箭头)（网页中间栏下方区域）


var divchg7=function(){
      var num10=4;
      var c12=document.getElementById("c12");
	  var c13=document.getElementById("c13");
	  var c14=document.getElementById("c14");
	  var c15=document.getElementById("c15");
	  var c16=document.getElementById("c16");

	   
	   var chg3=document.getElementById(a3[num10]);

	  if(num10==4){
			 
			 chg3.style.display="block";
			  c12.style.background="url(img/c11.jpg) no-repeat -19px 0px";
          c13.style.background="url(img/c11.jpg) no-repeat -32px 0px";
		  c14.style.background="url(img/c11.jpg) no-repeat -48px 0px";
		  c15.style.background="url(img/c11.jpg) no-repeat -60px 0px";
		  c16.style.background="url(img/c11.jpg) no-repeat -71px 0px";
		  document.getElementById(a3[1]).style.display="none";
			 document.getElementById(a3[2]).style.display="none";
			 document.getElementById(a3[3]).style.display="none";
			 document.getElementById(a3[0]).style.display="none";
		}

}

document.getElementById("c16").onmouseover=divchg7;



//开始图片自动变换（网页右栏栏上方区域）

var num11=0;
var a4=[];

a4[0]="img/d1.jpg";
a4[1]="img/d2.jpg";
a4[2]="img/d3.jpg";
a4[3]="img/d4.jpg";
a4[4]="img/d5.jpg";
a4[5]="img/d6.jpg";
a4[6]="img/d7.jpg";
a4[7]="img/d8.jpg";
a4[8]="img/d9.jpg";

var photochg=function(){


      var timg=document.getElementById("tcm");

	  var y1=document.getElementById("y1");
	  var y2=document.getElementById("y2");
	  var y3=document.getElementById("y3");
	  var y4=document.getElementById("y4");
	  var y5=document.getElementById("y5");
	  var y6=document.getElementById("y6");
	  var y7=document.getElementById("y7");
	  var y8=document.getElementById("y8");
	  var y9=document.getElementById("y9");
	  
	
	   if(num11>a4.length-1)
			  num11=0;
	    
			 timg.src=a4[num11];


       if(num11==0){

	   
	   y1.style.background="red";
	   y1.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   }
	    if(num11==1){

	    y2.style.background="red";
	   y2.style.color="white";

       y1.style.background="transparent";
	   y1.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   
	   }
	   if(num11==2){

	    y3.style.background="red";
	   y3.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   
	   
	   }
	   if(num11==3){

	   y4.style.background="red";
	   y4.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y1.style.background="transparent";
	   y1.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   
	   
	   }
	   if(num11==4){
        y5.style.background="red";
	   y5.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   
	   }
	   if(num11==5){

	    y6.style.background="red";
	   y6.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   
	   }
	   if(num11==6){

	  y7.style.background="red";
	   y7.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   }
	   if(num11==7){

	   y8.style.background="red";
	   y8.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   
	   }
	   if(num11==8){
       y9.style.background="red";
	   y9.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y1.style.background="transparent";
	   y1.style.color="#004276";
	   
	   }
	  
			
				     ++num11;
					 
					 setTimeout(photochg,3000);


}

photochg();

//开始鼠标点击右箭头图片自动变换（网页右栏栏上方区域）

var num12=0;
var photochg1=function(){


      var timg=document.getElementById("tcm");

	  var y1=document.getElementById("y1");
	  var y2=document.getElementById("y2");
	  var y3=document.getElementById("y3");
	  var y4=document.getElementById("y4");
	  var y5=document.getElementById("y5");
	  var y6=document.getElementById("y6");
	  var y7=document.getElementById("y7");
	  var y8=document.getElementById("y8");
	  var y9=document.getElementById("y9");
	  
	
	   if(num12>a4.length-1)
			  num12=0;
	    
			 timg.src=a4[num12];


       if(num12==0){

	   
	   y1.style.background="red";
	   y1.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   }
	    if(num12==1){

	    y2.style.background="red";
	   y2.style.color="white";

       y1.style.background="transparent";
	   y1.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   
	   }
	   if(num12==2){

	    y3.style.background="red";
	   y3.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   
	   
	   }
	   if(num12==3){

	   y4.style.background="red";
	   y4.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y1.style.background="transparent";
	   y1.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   
	   
	   }
	   if(num12==4){
        y5.style.background="red";
	   y5.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   
	   }
	   if(num12==5){

	    y6.style.background="red";
	   y6.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   
	   }
	   if(num12==6){

	  y7.style.background="red";
	   y7.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   }
	   if(num12==7){

	   y8.style.background="red";
	   y8.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   
	   }
	   if(num12==8){
       y9.style.background="red";
	   y9.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y1.style.background="transparent";
	   y1.style.color="#004276";
	   
	   }
	  
			
				     ++num12;
					 
				
}

document.getElementById("a_next").onclick=photochg1;

//开始鼠标点击左箭头图片自动变换（网页右栏栏上方区域）

var num13=a4.length-1;
var photochg2=function(){


      var timg=document.getElementById("tcm");

	  var y1=document.getElementById("y1");
	  var y2=document.getElementById("y2");
	  var y3=document.getElementById("y3");
	  var y4=document.getElementById("y4");
	  var y5=document.getElementById("y5");
	  var y6=document.getElementById("y6");
	  var y7=document.getElementById("y7");
	  var y8=document.getElementById("y8");
	  var y9=document.getElementById("y9");
	  
	
	   if(num13<0)
	num13=a4.length-1;
	    
			 timg.src=a4[num13];


       if(num13==0){

	   
	   y1.style.background="red";
	   y1.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   }
	    if(num13==1){

	    y2.style.background="red";
	   y2.style.color="white";

       y1.style.background="transparent";
	   y1.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   
	   }
	   if(num13==2){

	    y3.style.background="red";
	   y3.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   
	   
	   }
	   if(num13==3){

	   y4.style.background="red";
	   y4.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y1.style.background="transparent";
	   y1.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   
	   
	   }
	   if(num13==4){
        y5.style.background="red";
	   y5.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   
	   }
	   if(num13==5){

	    y6.style.background="red";
	   y6.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   
	   }
	   if(num13==6){

	  y7.style.background="red";
	   y7.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   }
	   if(num13==7){

	   y8.style.background="red";
	   y8.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   
	   }
	   if(num13==8){
       y9.style.background="red";
	   y9.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y1.style.background="transparent";
	   y1.style.color="#004276";
	   
	   }
	  
			
				     --num13;
					 
				
}

document.getElementById("a_prev").onclick=photochg2;


//开始鼠标滑过图片自动变换（网页右栏栏上方区域）

/*
var num14=0;
var y=[];

      y[0]=document.getElementById("y1");
	  y[1]=document.getElementById("y2");
	  y[2]=document.getElementById("y3");
	  y[3]=document.getElementById("y4");
	  y[4]=document.getElementById("y5");
	  y[5]=document.getElementById("y6");
	  y[6]=document.getElementById("y7");
	  y[7]=document.getElementById("y8");
	  y[8]=document.getElementById("y9");

var photochg1=[];

for(var i=0;i<a4.length;i++){
    photochg1[i]=function(){


      var timg=document.getElementById("tcm"); 
			 timg.src=a4[num14];


       if(i==num14){

	   
	   y[i].style.background="red";
	   
	   y[i].style.color="white";

	   var j=i+1;
	   if(j==a4.length){
		   j=0;
	   y[j].style.background="transparent";
	   y[j].style.color="#004276";
		   
		   
		}else {
   for(j;j<a4.length;j++){

	   
       y[j].style.background="transparent";
	   y[j].style.color="#004276";
	    
   }
		}   

	 }
	   }
	   
				     
	         ++num14;
y[i].onmouseover=photochg1[i];				 
				
}

 */ 

	


      var y1=document.getElementById("y1");
	  var y2=document.getElementById("y2");
	  var y3=document.getElementById("y3");
	  var y4=document.getElementById("y4");
	  var y5=document.getElementById("y5");
	  var y6=document.getElementById("y6");
	  var y7=document.getElementById("y7");
	  var y8=document.getElementById("y8");
	  var y9=document.getElementById("y9");


  var photochg3=function(){
         var num14=0;

      var timg=document.getElementById("tcm"); 
			 timg.src=a4[num14];


	    if(num14==0){

	   
	   y1.style.background="red";
	   y1.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   }
	 
	             
	 
}
	   
				     
	          
document.getElementById("y1").onmouseover=photochg3;				 
				

//开始鼠标滑过图片自动变换（网页右栏栏上方区域）



var photochg4=function(){
         var num14=1;

      var timg=document.getElementById("tcm"); 
			 timg.src=a4[num14];


	    if(num14==1){

	   
	   y2.style.background="red";
	   y2.style.color="white";

       y1.style.background="transparent";
	   y1.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   }
	 
	             
	 
}
	   
				    	          
document.getElementById("y2").onmouseover=photochg4;				 
				

//开始鼠标滑过图片自动变换（网页右栏栏上方区域）


var photochg5=function(){
         var num14=2;

      var timg=document.getElementById("tcm"); 
			 timg.src=a4[num14];


	    if(num14==2){

	   
	  y3.style.background="red";
	   y3.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   }
	 
	             
	 
}
	   				    	          
document.getElementById("y3").onmouseover=photochg5;				 
				

//开始鼠标滑过图片自动变换（网页右栏栏上方区域）


var photochg6=function(){
         var num14=3;

      var timg=document.getElementById("tcm"); 
			 timg.src=a4[num14];


	    if(num14==3){

	   
	  y4.style.background="red";
	   y4.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y1.style.background="transparent";
	   y1.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   }
	 
	             
	 
}
	   				    	          
document.getElementById("y4").onmouseover=photochg6;



//开始鼠标滑过图片自动变换（网页右栏栏上方区域）

var photochg7=function(){
         var num14=4;

      var timg=document.getElementById("tcm"); 
			 timg.src=a4[num14];


	    if(num14==4){

	   
	  y5.style.background="red";
	   y5.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   }
	 
	             
	 
}
	   				    	          
document.getElementById("y5").onmouseover=photochg7;


//开始鼠标滑过图片自动变换（网页右栏栏上方区域）


var photochg8=function(){
         var num14=5;

      var timg=document.getElementById("tcm"); 
			 timg.src=a4[num14];


	    if(num14==5){

	   
	  y6.style.background="red";
	   y6.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   }
	 
	             
	 
}
	   				    	          
document.getElementById("y6").onmouseover=photochg8;


//开始鼠标滑过图片自动变换（网页右栏栏上方区域）


var photochg9=function(){
         var num14=6;

      var timg=document.getElementById("tcm"); 
			 timg.src=a4[num14];


	    if(num14==6){

	   
	   y7.style.background="red";
	   y7.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   }
	 
	             
	 
}
	   				    	          
document.getElementById("y7").onmouseover=photochg9;

//开始鼠标滑过图片自动变换（网页右栏栏上方区域）


var photochg10=function(){
         var num14=7;

      var timg=document.getElementById("tcm"); 
			 timg.src=a4[num14];


	    if(num14==7){

	   
	  y8.style.background="red";
	   y8.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y1.style.background="transparent";
	   y1.style.color="#004276";
	   y9.style.background="transparent";
	   y9.style.color="#004276";
	   
	   }
	 
	             
	 
}
	   				    	          
document.getElementById("y8").onmouseover=photochg10;


//开始鼠标滑过图片自动变换（网页右栏栏上方区域）


var photochg11=function(){
         var num14=8;

      var timg=document.getElementById("tcm"); 
			 timg.src=a4[num14];


	    if(num14==8){

	   
	   y9.style.background="red";
	   y9.style.color="white";

       y2.style.background="transparent";
	   y2.style.color="#004276";
	    y3.style.background="transparent";
	   y3.style.color="#004276";
	   y4.style.background="transparent";
	   y4.style.color="#004276";
	    y5.style.background="transparent";
	   y5.style.color="#004276";
	    y6.style.background="transparent";
	   y6.style.color="#004276";
	    y7.style.background="transparent";
	   y7.style.color="#004276";
	    y8.style.background="transparent";
	   y8.style.color="#004276";
	   y1.style.background="transparent";
	   y1.style.color="#004276";
	   
	   }
	 
	             
	 
}
	   				    	          
document.getElementById("y9").onmouseover=photochg11;



//弹出广告代码(自动消失、点击消失)

var ad=function(){


var adimg1=document.getElementById("add1_1");
var adimg2=document.getElementById("add1_2");

adimg1.style.display="none";
adimg2.style.display="none";

}

setTimeout(ad,3000);

document.getElementById("add1_2").onclick=ad;




























}