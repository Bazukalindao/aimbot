--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then local v87=0;while true do if (v87==0) then v19=v0(v3(v30,1,1));return "";end end else local v88=v2(v0(v30,16));if v19 then local v113=v5(v88,v19);v19=nil;return v113;else return v88;end end end);local function v20(v31,v32,v33) if v33 then local v89=(v31/((5 -3)^(v32-(2 -1))))%((1 + 1)^(((v33-(1 -(0 -0))) -(v32-(2 -(118 -(32 + 85))))) + 1 + 0)) ;return v89-(v89%(1 + 0)) ;else local v90=0 -0 ;local v91;while true do if (v90==0) then v91=(621 -(124 + 431 + (1021 -(892 + 65))))^(v32-(932 -(857 + 74))) ;return (((v31%(v91 + v91))>=v91) and (569 -(367 + 201))) or (927 -(214 + 713)) ;end end end end local function v21() local v34=0;local v35;while true do if (v34==(0 -0)) then v35=v1(v16,v18,v18);v18=v18 + (1 -0) ;v34=1 -0 ;end if (v34==(351 -(87 + 263))) then return v35;end end end local function v22() local v36,v37=v1(v16,v18,v18 + (182 -(67 + 113)) );v18=v18 + 2 + 0 ;return (v37 * (628 -372)) + v36 ;end local function v23() local v38=0 + 0 ;local v39;local v40;local v41;local v42;while true do if (v38==1) then return (v42 * (66680831 -49903615)) + (v41 * ((188265 -121777) -(802 + 150))) + (v40 * (689 -(253 + 180))) + v39 ;end if (v38==(0 -(0 -0))) then v39,v40,v41,v42=v1(v16,v18,v18 + 3 + 0 );v18=v18 + (1001 -(915 + 82)) ;v38=1;end end end local function v24() local v43=772 -(201 + 571) ;local v44;local v45;local v46;local v47;local v48;local v49;while true do if (v43==2) then v48=v20(v45,1159 -(116 + 1022) ,1218 -(1069 + 118) );v49=((v20(v45,133 -(35 + 66) )==(2 -1)) and  -(1 -0)) or (1 + 0) ;v43=(10 -6) -1 ;end if (v43==(1 + (0 -0))) then v46=792 -(368 + 423) ;v47=(v20(v45,1 + 0 + 0 ,7 + 1 + 12 ) * ((6 -4)^(50 -(10 + 8)))) + v44 ;v43=(1062 -(87 + 968)) -5 ;end if ((445 -(416 + 26))==v43) then if (v48==(0 -0)) then if (v47==(0 + 0)) then return v49 * (0 -0) ;else v48=3 -(8 -6) ;v46=438 -(145 + 293) ;end elseif (v48==(2477 -(44 + 386))) then return ((v47==(1486 -(998 + 488))) and (v49 * (((3 + 0) -2)/(1747 -(760 + 987))))) or (v49 * NaN) ;end return v8(v49,v48-(325 + 698) ) * (v46 + (v47/(2^(1965 -(1789 + 124))))) ;end if (v43==(766 -(745 + 21))) then v44=v23();v45=v23();v43=1 + 0 ;end end end local function v25(v50) local v51=0 -0 ;local v52;local v53;while true do if (v51==(1413 -(447 + (1342 -(85 + 291))))) then v52=nil;if  not v50 then local v120=0 -0 ;while true do if (0==v120) then v50=v23();if (v50==0) then return "";end break;end end end v51=1818 -((2968 -(243 + 1022)) + 114) ;end if (v51==((2671 -1969) -(376 + 325))) then v52=v3(v16,v18,(v18 + v50) -(1 -0) );v18=v18 + v50 ;v51=5 -3 ;end if ((1 + 1)==v51) then v53={};for v114=1, #v52 do v53[v114]=v2(v1(v3(v52,v114,v114)));end v51=6 -3 ;end if (v51==(17 -(9 + 5))) then return v6(v53);end end end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v54=(function() return function(v92,v93,v94,v95,v96,v97,v98,v99) local v92=(function() return 1824 -(1195 + 629) ;end)();local v93=(function() return;end)();local v94=(function() return;end)();while true do if (v92~= #"<") then else if (v93== #".") then v94=(function() return v95()~=(0 -0) ;end)();elseif (v93==2) then v94=(function() return v96();end)();elseif (v93== #"gha") then v94=(function() return v97();end)();end v98[v99]=(function() return v94;end)();break;end if (v92==(241 -(187 + 54))) then local v122=(function() return 780 -(162 + 618) ;end)();local v123=(function() return;end)();while true do if (v122~=(0 + 0)) then else v123=(function() return 0 + 0 ;end)();while true do if (v123~=1) then else v92=(function() return  #">";end)();break;end if (0~=v123) then else v93=(function() return v95();end)();v94=(function() return nil;end)();v123=(function() return 1;end)();end end break;end end end end return v92,v93,v94,v95,v96,v97,v98,v99;end;end)();local v55=(function() return function(v100,v101,v102) local v103=(function() return 0 -0 ;end)();local v104=(function() return;end)();while true do if (v103==0) then v104=(function() return 0 -0 ;end)();while true do if (v104==0) then local v125=(function() return 0 + 0 ;end)();while true do if (v125==(1636 -(1373 + 263))) then v100[v101-#"|" ]=(function() return v102();end)();return v100,v101,v102;end end end end break;end end end;end)();local v56=(function() return {};end)();local v57=(function() return {};end)();local v58=(function() return {};end)();local v59=(function() return {v56,v57,nil,v58};end)();local v60=(function() return v23();end)();local v61=(function() return {};end)();for v69= #":",v60 do FlatIdent_2661B,Type,Cons,v21,v24,v25,v61,v69=(function() return v54(FlatIdent_2661B,Type,Cons,v21,v24,v25,v61,v69);end)();end v59[ #"91("]=(function() return v21();end)();for v70= #"/",v23() do local v71=(function() return v21();end)();if (v20(v71, #"|", #"|")==0) then local v108=(function() return 0 + 0 ;end)();local v109=(function() return;end)();local v110=(function() return;end)();local v111=(function() return;end)();local v112=(function() return;end)();while true do if (v108==0) then local v124=(function() return 0;end)();while true do if (v124~=1) then else v108=(function() return 1;end)();break;end if ((0 -0)==v124) then v109=(function() return 0 -0 ;end)();v110=(function() return nil;end)();v124=(function() return 1385 -(746 + 638) ;end)();end end end if (v108==(1 + 0)) then v111=(function() return nil;end)();v112=(function() return nil;end)();v108=(function() return 2 -0 ;end)();end if (v108==(343 -(218 + 123))) then while true do if (v109== #"91(") then if (v20(v111, #"91(", #"19(")~= #"|") then else v112[ #"?id="]=(function() return v61[v112[ #"xnxx"]];end)();end v56[v70]=(function() return v112;end)();break;end if (v109== #"}") then local v127=(function() return 0;end)();local v128=(function() return;end)();while true do if (v127~=0) then else v128=(function() return 1581 -(1535 + 46) ;end)();while true do if (v128==1) then v109=(function() return 2;end)();break;end if (v128==0) then v112=(function() return {v22(),v22(),nil,nil};end)();if (v110==(0 + 0)) then local v184=(function() return 0 + 0 ;end)();local v185=(function() return;end)();while true do if (v184~=0) then else v185=(function() return 560 -(306 + 254) ;end)();while true do if (v185~=0) then else v112[ #"asd"]=(function() return v22();end)();v112[ #"0836"]=(function() return v22();end)();break;end end break;end end elseif (v110== #"|") then v112[ #"gha"]=(function() return v23();end)();elseif (v110==2) then v112[ #"xnx"]=(function() return v23() -(2^16) ;end)();elseif (v110== #"nil") then local v192=(function() return 0;end)();while true do if (v192==(0 + 0)) then v112[ #"xnx"]=(function() return v23() -((3 -1)^(1483 -(899 + 568))) ;end)();v112[ #"http"]=(function() return v22();end)();break;end end end v128=(function() return 1;end)();end end break;end end end if (0~=v109) then else local v129=(function() return 0;end)();local v130=(function() return;end)();while true do if (v129==0) then v130=(function() return 0 + 0 ;end)();while true do if (v130==(2 -1)) then v109=(function() return  #"}";end)();break;end if (v130==0) then v110=(function() return v20(v71,2, #"nil");end)();v111=(function() return v20(v71, #"asd1",609 -(268 + 335) );end)();v130=(function() return 291 -(60 + 230) ;end)();end end break;end end end if ((574 -(426 + 146))~=v109) then else local v131=(function() return 0;end)();while true do if (v131~=(1 + 0)) then else v109=(function() return  #"gha";end)();break;end if (v131~=0) then else if (v20(v111, #":", #"<")== #".") then v112[1458 -(282 + 1174) ]=(function() return v61[v112[813 -(569 + 242) ]];end)();end if (v20(v111,5 -3 ,1 + 1 )== #":") then v112[ #"-19"]=(function() return v61[v112[ #"19("]];end)();end v131=(function() return 1;end)();end end end end break;end end end end for v72= #" ",v23() do v57,v72,v28=(function() return v55(v57,v72,v28);end)();end return v59;end local function v29(v63,v64,v65) local v66=v63[1025 -(706 + 318) ];local v67=v63[1253 -(721 + 530) ];local v68=v63[1274 -((2765 -1820) + 326) ];return function(...) local v73=v66;local v74=v67;local v75=v68;local v76=v27;local v77=(379 -(142 + 235)) -1 ;local v78= -(1 + 0);local v79={};local v80={...};local v81=v12("#",...) -(701 -(271 + (1946 -1517))) ;local v82={};local v83={};for v105=0 + 0 ,v81 do if (v105>=v75) then v79[v105-v75 ]=v80[v105 + 1 ];else v83[v105]=v80[v105 + 1 ];end end local v84=(v81-v75) + (1501 -(1408 + 92)) ;local v85;local v86;while true do v85=v73[v77];v86=v85[(237 + 850) -(461 + 625) ];if (v86<=(985 -(553 + 424))) then if (v86<=3) then if (v86<=(1289 -(993 + 295))) then if (v86>0) then v83[v85[1 + 1 ]]=v65[v85[3]];else v83[v85[1173 -(418 + (1423 -670)) ]]=v65[v85[2 + 1 ]];end elseif (v86>(1 + 0 + 1)) then v83[v85[1 + 1 ]]={};else local v137=v85[1 + 1 ];v83[v137]=v83[v137](v13(v83,v137 + ((526 + 4) -(406 + 123)) ,v78));end elseif (v86<=(1774 -(1749 + 20))) then if (v86==(1 + 2 + 1)) then v83[v85[1324 -(1249 + 73) ]]();else v83[v85[1 + 1 ]]=v85[1148 -(466 + 679) ]~=(0 -0) ;end elseif (v86<=(17 -11)) then v83[v85[1902 -(106 + 763 + 1031) ]]={};elseif (v86==(3 + 4)) then local v161=0;local v162;while true do if ((v161==(0 + 0 + (0 -0))) or (3151<1284)) then v162=v85[5 -3 ];v83[v162]=v83[v162](v13(v83,v162 + 1 ,v78));break;end end else v83[v85[5 -3 ]]();end elseif ((v86<=(126 -(4 + 110))) or (1850==1529)) then if (v86<=10) then if (v86>((1651 -1058) -(57 + 527))) then do return;end else local v141=0;local v142;local v143;local v144;local v145;while true do if ((821<2123) and (v141==(1429 -(41 + 1386)))) then for v176=v142,v78 do v145=v145 + (104 -(17 + 86)) ;v83[v176]=v143[v145];end break;end if ((902<2325) and ((1 + 0)==v141)) then v78=(v144 + v142) -(1 -0) ;v145=0 -0 ;v141=168 -(122 + 44) ;end if ((858<=2962) and ((0 -0)==v141)) then v142=v85[6 -4 ];v143,v144=v76(v83[v142](v13(v83,v142 + 1 + 0 ,v85[(2 -1) + 2 ])));v141=1 -0 ;end end end elseif ((v86==(76 -(30 + 35))) or (3946<1288)) then v83[v85[2 + 0 ]]=v85[3];else v83[v85[2]]=v85[1260 -(1043 + 214) ]~=(0 -0) ;end elseif (v86<=(1226 -(323 + 259 + 630))) then if (v86==((164 -130) -(774 -(239 + 514)))) then v83[v85[582 -(361 + 219) ]]=v85[(114 + 209) -((1382 -(797 + 532)) + 267) ];else local v151=v85[1 + 1 ];local v152=v83[v85[416 -(15 + 398) ]];v83[v151 + (983 -(14 + 4 + 964)) ]=v152;v83[v151]=v152[v85[14 -10 ]];end elseif (v86<=(9 + 6)) then local v156=0;local v157;local v158;while true do if (v156==(1 + 0)) then v83[v157 + ((288 + 563) -((47 -27) + 830)) ]=v158;v83[v157]=v158[v85[4 + 0 ]];break;end if (0==v156) then v157=v85[128 -((1318 -(373 + 829)) + 10) ];v158=v83[v85[1 + 2 ]];v156=1;end end elseif ((v86==(754 -((1273 -(476 + 255)) + (1326 -(369 + 761))))) or (3242==567)) then local v163=0 -0 ;local v164;local v165;local v166;local v167;while true do if (v163==1) then v78=(v166 + v164) -(1 + 0) ;v167=0 + 0 ;v163=2;end if ((v163==(0 + 0 + 0)) or (847>=1263)) then v164=v85[4 -2 ];v165,v166=v76(v83[v164](v13(v83,v164 + (2 -1) ,v85[1554 -(1126 + 425) ])));v163=406 -(118 + 287) ;end if (v163==(7 -5)) then for v182=v164,v78 do local v183=0;while true do if (v183==0) then v167=v167 + (1122 -(118 + 1003)) ;v83[v182]=v165[v167];break;end end end break;end end else do return;end end v77=v77 + (1 -0) ;end end;end return v29(v28(),{},v17)(...);end return v15("LOL!043Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q747047657403213Q00682Q7470733A2Q2F706173746562696E2E636F6D2F7261772F32714B436E615934000A4Q00067Q00122Q000100013Q00122Q000200023Q00200E00020002000300120B000400044Q0005000500014Q0010000200054Q000700013Q00022Q00040001000100012Q000A3Q00017Q00",v9(),...);
