body{background-color:#101010;font-family: 'Ubuntu', sans-serif;padding: 25px;-webkit-user-select: none; -ms-user-select: none; user-select: none;} a{text-decoration:none;}
body::before{content:"\00A9  SKULL";color:white;opacity:.3;font-size:2vw;position:fixed;bottom:25px;left:25px;}
#bodyblur{opacity:.2;position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.3);z-index:-1;transition:all 1s ease;}
@keyframes jj{0%  {transform: scale(1.1);} 50% {transform: scale(1.2);} 100% {transform: scale(1.1);}}
#bodyblur img{animation-name:jj;animation-duration: 5s;animation-iteration-count: infinite;}

@keyframes leaves {0% {transform: scale(1.0);} 100% {transform: scale(.8);}}
#lope, .lopdeg{animation: leaves 1s ease-in-out infinite alternate;-webkit-animation: leaves 1s ease-in-out infinite alternate;}
.lovein:hover{transform: scale(1.3);}

@keyframes kont{0%  {left:-1px; top:-3px;} 50% {left:1px; top:3px;} 100% {left:-1px; top:-3px;}}
blockquote{opacity:0;visibility:hidden;transition:all 1s ease;position:relative;margin-top:120px;margin-left:0;margin-right:0;}
blockquote{width:400px;background:var(--warna-bg);color:var(--warna-teks);text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);text-align:center;line-height:1.3em;padding:16px 30px 16px 30px;border: 1px solid var(--warna-teks);border-radius:var(--bingkai);}
p{font-size:18px;font-weight:700;margin:1.5em 0;transition:all .3s ease;}
#katabawah{font-size:13px;font-weight:400}
#katajawab{font-weight:400;margin:0;display:none;}
#katanimasi{font-size:18px;}
@keyframes rto{from {transform:scale(.93);} to {transform:scale(1);}}
@keyframes rt{from {transform: rotate(0deg);} to {transform: rotate(360deg);}}
#bq img{display:none;padding:10px;width:130px;height:130px;margin:20px 0 0 0;}
#bq img:first-child{display:inline-flex}
#foto1, #foto2, #foto3{background:rgba(255,255,255, .5);border-radius:10px;}
#akhiran{display:none;color:#FFC700;font-size:14px;text-align:center;background:rgba(0,0,0,.55);text-shadow: 0px;padding:10px;border-radius:var(--bingkai);line-height:10px;transition:all .2s ease;} #akhiran:hover{transform: scale(.9);opacity:.5;}

#pergeseran{opacity:0;visibility:hidden;transition:all 1s ease;display:flex;flex-wrap:nowrap;align-items:flex-start;justify-content:flex-start;position:relative;max-width:500px;padding:0 20px; overflow-y:hidden;overflow-x:scroll;scroll-behavior:smooth;scroll-snap-type:x mandatory; -ms-overflow-style:none;-webkit-overflow-scrolling:touch}
#pergeseran p{background:#003A76;color:white;border: 1px dashed #fff;border-radius:8px;padding:8px;display:flex;flex-wrap:nowrap;text-align:center;font-size:16px;font-weight:700;align-items:center;justify-content:center;flex-shrink:0; width:90%; min-height:130px;margin:0 15px 0 0; scroll-snap-align:center} #pergeseran > *:last-child{margin-right:0} #pergeseran:after{content:'';display:block;flex-shrink:0; align-self:stretch;padding-left:20px}
#pergeseran p b{display:block;} #pergeseran p b img{width:80px;height:80px;margin:20px 0;}
/*#pergeseran p b span{display:flex;}*/
#tm{color:#FFB400;transition:all .5s ease;} #tm:hover{transform: scale(.7);}
#idgeser{position:relative;top:30vh;font-size:17px;color:white}

#contTom{margin:0;display:flex;align-items:left;list-style:none}
.button{display:inline-flex;align-items:center; margin:0;margin:12px 8px 12px 0;transition:all .3s ease;padding:10px 15px;outline:0;border:1px solid var(--warna-teks); border-radius:var(--bingkai);line-height:20px;background:var(--warna-bg);color:var(--warna-teks);font-size:14px;font-weight:700;white-space:nowrap;overflow:hidden;z-index:1} 
.button:hover{transform: scale(.90);opacity:.98;}
#buttonv2{position:absolute;font-size:15px;color:white;background:var(--warna-bg);padding:10px;border-radius:8px;line-height:10px;text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);opacity:0}

.lovein{font-size:50px;display:flex;align-items:center;justify-content:center;transition:all .3s ease;}
.lovein svg{width:80px;height:80px;fill:#fefefe}

.content2{display:block;text-align:center;width:100%;height:180px;margin-top:50px;}
.content2 > *{display:flex;align-items:center;justify-content:center;margin-top:15px;font-size:17px;color:white}
.image img{border-radius:10%;transform:scale(.1);transition:all .8s ease;}
#k2 .image > *{margin-bottom:40px;} #k2{font-weight:700;font-size:17px;color:white;text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);} #final1{transition:all 3s ease;}

#idkirim{font-size:13px;text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);color:white;transition:all .5s ease;}
#idkirim{opacity:0;visibility:hidden;margin-top:100px} #idkirim:hover{transform:scale(.8);}

.content2{display:none;}
#Content, #k2{animation-name:none;animation-duration: 3s;animation-iteration-count: infinite;position:relative;opacity:0;margin-top:50px;width:100%;height:180px;transition:all 1.8s ease;}
#Content > *, #k2 > *{display:flex;align-items:center;text-align:center;justify-content:center;margin-top:15px;}
#k2, #final1{transform:scale(.1);}

.swal2-title{margin-right:20px;margin-left:20px;font-size:20px;text-align:center;padding:15px 30px 0 30px;}
.swal2-modal{background:rgba(255, 255, 255, .99);border: .7px solid #000;border-radius:var(--bingkai);}

.fa-heart {opacity:.3;color:white;font-size: 30px;position: absolute;animation:  heartMove linear 1;top: -10vh;z-index: 0;}
@keyframes heartMove {0%{transform: translateY(-10vh) ;} 100%{transform: translateY(100vh) ;}}
