/* jQuery v3.5.1 | (c) JS Foundation and other contributors | jquery.org/license */
!function(B,A){"object"==typeof module&&"object"==typeof module.exports?module.exports=B.document?A(B,!0):function(C){if(!C.document){throw new Error("jQuery requires a window with a document")
}return A(C)
}:A(B)
}("undefined"!=typeof window?window:this,function(CP,Bk){var BR=[],BT=Object.getPrototypeOf,BS=BR.slice,Bh=BR.flat?function(A){return BR.flat.call(A)
}:function(A){return BR.concat.apply([],A)
},BP=BR.push,Bf=BR.indexOf,BX={},BW=BX.toString,BO=BX.hasOwnProperty,Bo=BO.toString,Ba=Bo.call(Object),BK={},BZ=function(A){return"function"==typeof A&&"number"!=typeof A.nodeType
},BM=function(A){return null!=A&&A===A.window
},CL=CP.document,Bm={type:!0,src:!0,nonce:!0,noModule:!0};
function Bn(D,B,F){var C,A,E=(F=F||CL).createElement("script");
if(E.text=D,B){for(C in Bm){(A=B[C]||B.getAttribute&&B.getAttribute(C))&&E.setAttribute(C,A)
}}F.head.appendChild(E).parentNode.removeChild(E)
}function BN(A){return null==A?A+"":"object"==typeof A||"function"==typeof A?BX[BW.call(A)]||"object":typeof A
}var Bi="3.5.1",B3=function(B,A){return new B3.fn.init(B,A)
};
function BV(B){var A=!!B&&"length" in B&&B.length,C=BN(B);
return !BZ(B)&&!BM(B)&&("array"===C||0===A||"number"==typeof A&&0<A&&A-1 in B)
}B3.fn=B3.prototype={jquery:Bi,constructor:B3,length:0,toArray:function(){return BS.call(this)
},get:function(A){return null==A?BS.call(this):A<0?this[A+this.length]:this[A]
},pushStack:function(B){var A=B3.merge(this.constructor(),B);
return A.prevObject=this,A
},each:function(A){return B3.each(this,A)
},map:function(A){return this.pushStack(B3.map(this,function(C,B){return A.call(C,B,C)
}))
},slice:function(){return this.pushStack(BS.apply(this,arguments))
},first:function(){return this.eq(0)
},last:function(){return this.eq(-1)
},even:function(){return this.pushStack(B3.grep(this,function(B,A){return(A+1)%2
}))
},odd:function(){return this.pushStack(B3.grep(this,function(B,A){return A%2
}))
},eq:function(B){var A=this.length,C=+B+(B<0?A:0);
return this.pushStack(0<=C&&C<A?[this[C]]:[])
},end:function(){return this.prevObject||this.constructor()
},push:BP,sort:BR.sort,splice:BR.splice},B3.extend=B3.fn.extend=function(){var F,I,C,A,E,B,G=arguments[0]||{},J=1,H=arguments.length,D=!1;
for("boolean"==typeof G&&(D=G,G=arguments[J]||{},J++),"object"==typeof G||BZ(G)||(G={}),J===H&&(G=this,J--);
J<H;
J++){if(null!=(F=arguments[J])){for(I in F){A=F[I],"__proto__"!==I&&G!==A&&(D&&A&&(B3.isPlainObject(A)||(E=Array.isArray(A)))?(C=G[I],B=E&&!Array.isArray(C)?[]:E||B3.isPlainObject(C)?C:{},E=!1,G[I]=B3.extend(D,B,A)):void 0!==A&&(G[I]=A))
}}}return G
},B3.extend({expando:"jQuery"+(Bi+Math.random()).replace(/\D/g,""),isReady:!0,error:function(A){throw new Error(A)
},noop:function(){},isPlainObject:function(B){var A,C;
return !(!B||"[object Object]"!==BW.call(B))&&(!(A=BT(B))||"function"==typeof (C=BO.call(A,"constructor")&&A.constructor)&&Bo.call(C)===Ba)
},isEmptyObject:function(B){var A;
for(A in B){return !1
}return !0
},globalEval:function(B,A,C){Bn(B,{nonce:A&&A.nonce},C)
},each:function(C,A){var D,B=0;
if(BV(C)){for(D=C.length;
B<D;
B++){if(!1===A.call(C[B],B,C[B])){break
}}}else{for(B in C){if(!1===A.call(C[B],B,C[B])){break
}}}return C
},makeArray:function(B,A){var C=A||[];
return null!=B&&(BV(Object(B))?B3.merge(C,"string"==typeof B?[B]:B):BP.call(C,B)),C
},inArray:function(B,A,C){return null==A?-1:Bf.call(A,B,C)
},merge:function(D,B){for(var E=+B.length,C=0,A=D.length;
C<E;
C++){D[A++]=B[C]
}return D.length=A,D
},grep:function(E,C,G){for(var D=[],B=0,F=E.length,A=!G;
B<F;
B++){!C(E[B],B)!==A&&D.push(E[B])
}return D
},map:function(E,C,G){var D,B,F=0,A=[];
if(BV(E)){for(D=E.length;
F<D;
F++){null!=(B=C(E[F],F,G))&&A.push(B)
}}else{for(F in E){null!=(B=C(E[F],F,G))&&A.push(B)
}}return Bh(A)
},guid:1,support:BK}),"function"==typeof Symbol&&(B3.fn[Symbol.iterator]=BR[Symbol.iterator]),B3.each("Boolean Number String Function Array Date RegExp Object Error Symbol".split(" "),function(B,A){BX["[object "+A+"]"]=A.toLowerCase()
});
var Bl=function(C3){var DE,DF,DI,C2,C9,DA,DD,DC,Ct,Cv,C6,DR,Dn,DJ,Dk,Cu,Cx,DG,Cr,DT="sizzle"+1*new Date,C1=C3.document,C7=0,Cy=0,C4=DH(),Cs=DH(),Dp=DH(),DZ=DH(),Dl=function(B,A){return B===A&&(C6=!0),0
},C8={}.hasOwnProperty,Cw=[],C0=Cw.pop,Dc=Cw.push,Dh=Cw.push,DX=Cw.slice,DW=function(C,A){for(var D=0,B=C.length;
D<B;
D++){if(C[D]===A){return D
}}return -1
},DU="checked|selected|async|autofocus|autoplay|controls|defer|disabled|hidden|ismap|loop|multiple|open|readonly|required|scoped",Db="[\\x20\\t\\r\\n\\f]",Df="(?:\\\\[\\da-fA-F]{1,6}"+Db+"?|\\\\[^\\r\\n\\f]|[\\w-]|[^\0-\\x7f])+",DO="\\["+Db+"*("+Df+")(?:"+Db+"*([*^$|!~]?=)"+Db+"*(?:'((?:\\\\.|[^\\\\'])*)'|\"((?:\\\\.|[^\\\\\"])*)\"|("+Df+"))|)"+Db+"*\\]",Dj=":("+Df+")(?:\\((('((?:\\\\.|[^\\\\'])*)'|\"((?:\\\\.|[^\\\\\"])*)\")|((?:\\\\.|[^\\\\()[\\]]|"+DO+")*)|.*)\\)|)",Do=new RegExp(Db+"+","g"),Du=new RegExp("^"+Db+"+|((?:^|[^\\\\])(?:\\\\.)*)"+Db+"+$","g"),DK=new RegExp("^"+Db+"*,"+Db+"*"),Cq=new RegExp("^"+Db+"*([>+~]|"+Db+")"+Db+"*"),DQ=new RegExp(Db+"|>"),DN=new RegExp(Dj),DP=new RegExp("^"+Df+"$"),Di={ID:new RegExp("^#("+Df+")"),CLASS:new RegExp("^\\.("+Df+")"),TAG:new RegExp("^("+Df+"|[*])"),ATTR:new RegExp("^"+DO),PSEUDO:new RegExp("^"+Dj),CHILD:new RegExp("^:(only|first|last|nth|nth-last)-(child|of-type)(?:\\("+Db+"*(even|odd|(([+-]|)(\\d*)n|)"+Db+"*(?:([+-]|)"+Db+"*(\\d+)|))"+Db+"*\\)|)","i"),bool:new RegExp("^(?:"+DU+")$","i"),needsContext:new RegExp("^"+Db+"*[>+~]|:(even|odd|eq|gt|lt|nth|first|last)(?:\\("+Db+"*((?:-\\d)?\\d*)"+Db+"*\\)|)(?=[^-]|$)","i")},DM=/HTML$/i,DV=/^(?:input|select|textarea|button)$/i,De=/^h\d$/i,Dd=/^[^{]+\{\s*\[native \w/,DL=/^(?:#([\w-]+)|(\w+)|\.([\w-]+))$/,Ae=/[+~]/,Dm=new RegExp("\\\\[\\da-fA-F]{1,6}"+Db+"?|\\\\([^\\r\\n\\f])","g"),Dg=function(B,A){var C="0x"+B.slice(1)-65536;
return A||(C<0?String.fromCharCode(C+65536):String.fromCharCode(C>>10|55296,1023&C|56320))
},Dz=/([\0-\x1f\x7f]|^-?\d)|^-$|[^\0-\x1f\x7f-\uFFFF\w-]/g,C5=function(B,A){return A?"\0"===B?"\ufffd":B.slice(0,-1)+"\\"+B.charCodeAt(B.length-1).toString(16)+" ":"\\"+B
},DB=function(){DR()
},Dq=DS(function(A){return !0===A.disabled&&"fieldset"===A.nodeName.toLowerCase()
},{dir:"parentNode",next:"legend"});
try{Dh.apply(Cw=DX.call(C1.childNodes),C1.childNodes),Cw[C1.childNodes.length].nodeType
}catch(DE){Dh={apply:Cw.length?function(B,A){Dc.apply(B,DX.call(A))
}:function(C,A){var D=C.length,B=0;
while(C[D++]=A[B++]){}C.length=D-1
}}
}function Dt(L,H,D,A){var F,C,J,M,K,E,I,G=H&&H.ownerDocument,B=H?H.nodeType:9;
if(D=D||[],"string"!=typeof L||!L||1!==B&&9!==B&&11!==B){return D
}if(!A&&(DR(H),H=H||Dn,Dk)){if(11!==B&&(K=DL.exec(L))){if(F=K[1]){if(9===B){if(!(J=H.getElementById(F))){return D
}if(J.id===F){return D.push(J),D
}}else{if(G&&(J=G.getElementById(F))&&Cr(H,J)&&J.id===F){return D.push(J),D
}}}else{if(K[2]){return Dh.apply(D,H.getElementsByTagName(L)),D
}if((F=K[3])&&DF.getElementsByClassName&&H.getElementsByClassName){return Dh.apply(D,H.getElementsByClassName(F)),D
}}}if(DF.qsa&&!DZ[L+" "]&&(!Cu||!Cu.test(L))&&(1!==B||"object"!==H.nodeName.toLowerCase())){if(I=L,G=H,1===B&&(DQ.test(L)||Cq.test(L))){(G=Ae.test(L)&&Dv(H.parentNode)||H)===H&&DF.scope||((M=H.getAttribute("id"))?M=M.replace(Dz,C5):H.setAttribute("id",M=DT)),C=(E=DA(L)).length;
while(C--){E[C]=(M?"#"+M:":scope")+" "+D0(E[C])
}I=E.join(",")
}try{return Dh.apply(D,G.querySelectorAll(I)),D
}catch(H){DZ(L,!0)
}finally{M===DT&&H.removeAttribute("id")
}}}return DC(L.replace(Du,"$1"),H,D,A)
}function DH(){var A=[];
return function B(C,D){return A.push(C+" ")>DI.cacheLength&&delete B[A.shift()],B[C+" "]=D
}
}function Dy(A){return A[DT]=!0,A
}function Cz(B){var A=Dn.createElement("fieldset");
try{return !!B(A)
}catch(B){return !1
}finally{A.parentNode&&A.parentNode.removeChild(A),A=null
}}function Dx(C,A){var D=C.split("|"),B=D.length;
while(B--){DI.attrHandle[D[B]]=A
}}function Co(C,A){var D=A&&C,B=D&&1===C.nodeType&&1===A.nodeType&&C.sourceIndex-A.sourceIndex;
if(B){return B
}if(D){while(D=D.nextSibling){if(D===A){return -1
}}}return C?1:-1
}function Be(A){return function(B){return"input"===B.nodeName.toLowerCase()&&B.type===A
}
}function DY(A){return function(C){var B=C.nodeName.toLowerCase();
return("input"===B||"button"===B)&&C.type===A
}
}function Dr(A){return function(B){return"form" in B?B.parentNode&&!1===B.disabled?"label" in B?"label" in B.parentNode?B.parentNode.disabled===A:B.disabled===A:B.isDisabled===A||B.isDisabled!==!A&&Dq(B)===A:B.disabled===A:"label" in B&&B.disabled===A
}
}function Cp(A){return Dy(function(B){return B=+B,Dy(function(F,D){var G,E=A([],F.length,B),C=E.length;
while(C--){F[G=E[C]]&&(F[G]=!(D[G]=F[G]))
}})
})
}function Dv(A){return A&&"undefined"!=typeof A.getElementsByTagName&&A
}for(DE in DF=Dt.support={},C9=Dt.isXML=function(B){var A=B.namespaceURI,C=(B.ownerDocument||B).documentElement;
return !DM.test(A||C&&C.nodeName||"HTML")
},DR=Dt.setDocument=function(C){var A,D,B=C?C.ownerDocument||C:C1;
return B!=Dn&&9===B.nodeType&&B.documentElement&&(DJ=(Dn=B).documentElement,Dk=!C9(Dn),C1!=Dn&&(D=Dn.defaultView)&&D.top!==D&&(D.addEventListener?D.addEventListener("unload",DB,!1):D.attachEvent&&D.attachEvent("onunload",DB)),DF.scope=Cz(function(E){return DJ.appendChild(E).appendChild(Dn.createElement("div")),"undefined"!=typeof E.querySelectorAll&&!E.querySelectorAll(":scope fieldset div").length
}),DF.attributes=Cz(function(E){return E.className="i",!E.getAttribute("className")
}),DF.getElementsByTagName=Cz(function(E){return E.appendChild(Dn.createComment("")),!E.getElementsByTagName("*").length
}),DF.getElementsByClassName=Dd.test(Dn.getElementsByClassName),DF.getById=Cz(function(E){return DJ.appendChild(E).id=DT,!Dn.getElementsByName||!Dn.getElementsByName(DT).length
}),DF.getById?(DI.filter.ID=function(F){var E=F.replace(Dm,Dg);
return function(G){return G.getAttribute("id")===E
}
},DI.find.ID=function(F,E){if("undefined"!=typeof E.getElementById&&Dk){var G=E.getElementById(F);
return G?[G]:[]
}}):(DI.filter.ID=function(E){var F=E.replace(Dm,Dg);
return function(H){var G="undefined"!=typeof H.getAttributeNode&&H.getAttributeNode("id");
return G&&G.value===F
}
},DI.find.ID=function(H,F){if("undefined"!=typeof F.getElementById&&Dk){var J,G,E,I=F.getElementById(H);
if(I){if((J=I.getAttributeNode("id"))&&J.value===H){return[I]
}E=F.getElementsByName(H),G=0;
while(I=E[G++]){if((J=I.getAttributeNode("id"))&&J.value===H){return[I]
}}}return[]
}}),DI.find.TAG=DF.getElementsByTagName?function(F,E){return"undefined"!=typeof E.getElementsByTagName?E.getElementsByTagName(F):DF.qsa?E.querySelectorAll(F):void 0
}:function(H,F){var J,G=[],E=0,I=F.getElementsByTagName(H);
if("*"===H){while(J=I[E++]){1===J.nodeType&&G.push(J)
}return G
}return I
},DI.find.CLASS=DF.getElementsByClassName&&function(F,E){if("undefined"!=typeof E.getElementsByClassName&&Dk){return E.getElementsByClassName(F)
}},Cx=[],Cu=[],(DF.qsa=Dd.test(Dn.querySelectorAll))&&(Cz(function(F){var E;
DJ.appendChild(F).innerHTML="<a id='"+DT+"'></a><select id='"+DT+"-\r\\' msallowcapture=''><option selected=''></option></select>",F.querySelectorAll("[msallowcapture^='']").length&&Cu.push("[*^$]="+Db+"*(?:''|\"\")"),F.querySelectorAll("[selected]").length||Cu.push("\\["+Db+"*(?:value|"+DU+")"),F.querySelectorAll("[id~="+DT+"-]").length||Cu.push("~="),(E=Dn.createElement("input")).setAttribute("name",""),F.appendChild(E),F.querySelectorAll("[name='']").length||Cu.push("\\["+Db+"*name"+Db+"*="+Db+"*(?:''|\"\")"),F.querySelectorAll(":checked").length||Cu.push(":checked"),F.querySelectorAll("a#"+DT+"+*").length||Cu.push(".#.+[+~]"),F.querySelectorAll("\\\f"),Cu.push("[\\r\\n\\f]")
}),Cz(function(F){F.innerHTML="<a href='' disabled='disabled'></a><select disabled='disabled'><option/></select>";
var E=Dn.createElement("input");
E.setAttribute("type","hidden"),F.appendChild(E).setAttribute("name","D"),F.querySelectorAll("[name=d]").length&&Cu.push("name"+Db+"*[*^$|!~]?="),2!==F.querySelectorAll(":enabled").length&&Cu.push(":enabled",":disabled"),DJ.appendChild(F).disabled=!0,2!==F.querySelectorAll(":disabled").length&&Cu.push(":enabled",":disabled"),F.querySelectorAll("*,:x"),Cu.push(",.*:")
})),(DF.matchesSelector=Dd.test(DG=DJ.matches||DJ.webkitMatchesSelector||DJ.mozMatchesSelector||DJ.oMatchesSelector||DJ.msMatchesSelector))&&Cz(function(E){DF.disconnectedMatch=DG.call(E,"*"),DG.call(E,"[s!='']:x"),Cx.push("!=",Dj)
}),Cu=Cu.length&&new RegExp(Cu.join("|")),Cx=Cx.length&&new RegExp(Cx.join("|")),A=Dd.test(DJ.compareDocumentPosition),Cr=A||Dd.test(DJ.contains)?function(G,E){var H=9===G.nodeType?G.documentElement:G,F=E&&E.parentNode;
return G===F||!(!F||1!==F.nodeType||!(H.contains?H.contains(F):G.compareDocumentPosition&&16&G.compareDocumentPosition(F)))
}:function(F,E){if(E){while(E=E.parentNode){if(E===F){return !0
}}}return !1
},Dl=A?function(F,E){if(F===E){return C6=!0,0
}var G=!F.compareDocumentPosition-!E.compareDocumentPosition;
return G||(1&(G=(F.ownerDocument||F)==(E.ownerDocument||E)?F.compareDocumentPosition(E):1)||!DF.sortDetached&&E.compareDocumentPosition(F)===G?F==Dn||F.ownerDocument==C1&&Cr(C1,F)?-1:E==Dn||E.ownerDocument==C1&&Cr(C1,E)?1:Cv?DW(Cv,F)-DW(Cv,E):0:4&G?-1:1)
}:function(J,G){if(J===G){return C6=!0,0
}var L,I=0,F=J.parentNode,K=G.parentNode,E=[J],H=[G];
if(!F||!K){return J==Dn?-1:G==Dn?1:F?-1:K?1:Cv?DW(Cv,J)-DW(Cv,G):0
}if(F===K){return Co(J,G)
}L=J;
while(L=L.parentNode){E.unshift(L)
}L=G;
while(L=L.parentNode){H.unshift(L)
}while(E[I]===H[I]){I++
}return I?Co(E[I],H[I]):E[I]==C1?-1:H[I]==C1?1:0
}),Dn
},Dt.matches=function(B,A){return Dt(B,null,null,A)
},Dt.matchesSelector=function(B,A){if(DR(B),DF.matchesSelector&&Dk&&!DZ[A+" "]&&(!Cx||!Cx.test(A))&&(!Cu||!Cu.test(A))){try{var C=DG.call(B,A);
if(C||DF.disconnectedMatch||B.document&&11!==B.document.nodeType){return C
}}catch(B){DZ(A,!0)
}}return 0<Dt(A,Dn,null,[B]).length
},Dt.contains=function(B,A){return(B.ownerDocument||B)!=Dn&&DR(B),Cr(B,A)
},Dt.attr=function(C,A){(C.ownerDocument||C)!=Dn&&DR(C);
var D=DI.attrHandle[A.toLowerCase()],B=D&&C8.call(DI.attrHandle,A.toLowerCase())?D(C,A,!Dk):void 0;
return void 0!==B?B:DF.attributes||!Dk?C.getAttribute(A):(B=C.getAttributeNode(A))&&B.specified?B.value:null
},Dt.escape=function(A){return(A+"").replace(Dz,C5)
},Dt.error=function(A){throw new Error("Syntax error, unrecognized expression: "+A)
},Dt.uniqueSort=function(D){var B,E=[],C=0,A=0;
if(C6=!DF.detectDuplicates,Cv=!DF.sortStable&&D.slice(0),D.sort(Dl),C6){while(B=D[A++]){B===D[A]&&(C=E.push(A))
}while(C--){D.splice(E[C],1)
}}return Cv=null,D
},C2=Dt.getText=function(D){var B,E="",C=0,A=D.nodeType;
if(A){if(1===A||9===A||11===A){if("string"==typeof D.textContent){return D.textContent
}for(D=D.firstChild;
D;
D=D.nextSibling){E+=C2(D)
}}else{if(3===A||4===A){return D.nodeValue
}}}else{while(B=D[C++]){E+=C2(B)
}}return E
},(DI=Dt.selectors={cacheLength:50,createPseudo:Dy,match:Di,attrHandle:{},find:{},relative:{">":{dir:"parentNode",first:!0}," ":{dir:"parentNode"},"+":{dir:"previousSibling",first:!0},"~":{dir:"previousSibling"}},preFilter:{ATTR:function(A){return A[1]=A[1].replace(Dm,Dg),A[3]=(A[3]||A[4]||A[5]||"").replace(Dm,Dg),"~="===A[2]&&(A[3]=" "+A[3]+" "),A.slice(0,4)
},CHILD:function(A){return A[1]=A[1].toLowerCase(),"nth"===A[1].slice(0,3)?(A[3]||Dt.error(A[0]),A[4]=+(A[4]?A[5]+(A[6]||1):2*("even"===A[3]||"odd"===A[3])),A[5]=+(A[7]+A[8]||"odd"===A[3])):A[3]&&Dt.error(A[0]),A
},PSEUDO:function(B){var A,C=!B[6]&&B[2];
return Di.CHILD.test(B[0])?null:(B[3]?B[2]=B[4]||B[5]||"":C&&DN.test(C)&&(A=DA(C,!0))&&(A=C.indexOf(")",C.length-A)-C.length)&&(B[0]=B[0].slice(0,A),B[2]=C.slice(0,A)),B.slice(0,3))
}},filter:{TAG:function(B){var A=B.replace(Dm,Dg).toLowerCase();
return"*"===B?function(){return !0
}:function(C){return C.nodeName&&C.nodeName.toLowerCase()===A
}
},CLASS:function(B){var A=C4[B+" "];
return A||(A=new RegExp("(^|"+Db+")"+B+"("+Db+"|$)"))&&C4(B,function(C){return A.test("string"==typeof C.className&&C.className||"undefined"!=typeof C.getAttribute&&C.getAttribute("class")||"")
})
},ATTR:function(C,B,A){return function(E){var D=Dt.attr(E,C);
return null==D?"!="===B:!B||(D+="","="===B?D===A:"!="===B?D!==A:"^="===B?A&&0===D.indexOf(A):"*="===B?A&&-1<D.indexOf(A):"$="===B?A&&D.slice(-A.length)===A:"~="===B?-1<(" "+D.replace(Do," ")+" ").indexOf(A):"|="===B&&(D===A||D.slice(0,A.length+1)===A+"-"))
}
},CHILD:function(E,G,D,F,C){var H="nth"!==E.slice(0,3),B="last"!==E.slice(-4),A="of-type"===G;
return 1===F&&0===C?function(I){return !!I.parentNode
}:function(P,U,L){var I,N,K,S,V,T,M=H!==B?"nextSibling":"previousSibling",R=P.parentNode,O=A&&P.nodeName.toLowerCase(),J=!L&&!A,Q=!1;
if(R){if(H){while(M){S=P;
while(S=S[M]){if(A?S.nodeName.toLowerCase()===O:1===S.nodeType){return !1
}}T=M="only"===E&&!T&&"nextSibling"
}return !0
}if(T=[B?R.firstChild:R.lastChild],B&&J){Q=(V=(I=(N=(K=(S=R)[DT]||(S[DT]={}))[S.uniqueID]||(K[S.uniqueID]={}))[E]||[])[0]===C7&&I[1])&&I[2],S=V&&R.childNodes[V];
while(S=++V&&S&&S[M]||(Q=V=0)||T.pop()){if(1===S.nodeType&&++Q&&S===P){N[E]=[C7,V,Q];
break
}}}else{if(J&&(Q=V=(I=(N=(K=(S=P)[DT]||(S[DT]={}))[S.uniqueID]||(K[S.uniqueID]={}))[E]||[])[0]===C7&&I[1]),!1===Q){while(S=++V&&S&&S[M]||(Q=V=0)||T.pop()){if((A?S.nodeName.toLowerCase()===O:1===S.nodeType)&&++Q&&(J&&((N=(K=S[DT]||(S[DT]={}))[S.uniqueID]||(K[S.uniqueID]={}))[E]=[C7,Q]),S===P)){break
}}}}return(Q-=C)===F||Q%F==0&&0<=Q/F
}}
},PSEUDO:function(C,D){var B,A=DI.pseudos[C]||DI.setFilters[C.toLowerCase()]||Dt.error("unsupported pseudo: "+C);
return A[DT]?A(D):1<A.length?(B=[C,C,"",D],DI.setFilters.hasOwnProperty(C.toLowerCase())?Dy(function(H,F){var I,G=A(H,D),E=G.length;
while(E--){H[I=DW(H,G[E])]=!(F[I]=G[E])
}}):function(E){return A(E,0,B)
}):A
}},pseudos:{not:Dy(function(D){var C=[],A=[],B=DD(D.replace(Du,"$1"));
return B[DT]?Dy(function(I,G,K,H){var F,J=B(I,null,H,[]),E=I.length;
while(E--){(F=J[E])&&(I[E]=!(G[E]=F))
}}):function(F,E,G){return C[0]=F,B(C,null,G,A),C[0]=null,!A.pop()
}
}),has:Dy(function(A){return function(B){return 0<Dt(A,B).length
}
}),contains:Dy(function(A){return A=A.replace(Dm,Dg),function(B){return -1<(B.textContent||C2(B)).indexOf(A)
}
}),lang:Dy(function(A){return DP.test(A||"")||Dt.error("unsupported lang: "+A),A=A.replace(Dm,Dg).toLowerCase(),function(C){var B;
do{if(B=Dk?C.lang:C.getAttribute("xml:lang")||C.getAttribute("lang")){return(B=B.toLowerCase())===A||0===B.indexOf(A+"-")
}}while((C=C.parentNode)&&1===C.nodeType);
return !1
}
}),target:function(B){var A=C3.location&&C3.location.hash;
return A&&A.slice(1)===B.id
},root:function(A){return A===DJ
},focus:function(A){return A===Dn.activeElement&&(!Dn.hasFocus||Dn.hasFocus())&&!!(A.type||A.href||~A.tabIndex)
},enabled:Dr(!1),disabled:Dr(!0),checked:function(B){var A=B.nodeName.toLowerCase();
return"input"===A&&!!B.checked||"option"===A&&!!B.selected
},selected:function(A){return A.parentNode&&A.parentNode.selectedIndex,!0===A.selected
},empty:function(A){for(A=A.firstChild;
A;
A=A.nextSibling){if(A.nodeType<6){return !1
}}return !0
},parent:function(A){return !DI.pseudos.empty(A)
},header:function(A){return De.test(A.nodeName)
},input:function(A){return DV.test(A.nodeName)
},button:function(B){var A=B.nodeName.toLowerCase();
return"input"===A&&"button"===B.type||"button"===A
},text:function(B){var A;
return"input"===B.nodeName.toLowerCase()&&"text"===B.type&&(null==(A=B.getAttribute("type"))||"text"===A.toLowerCase())
},first:Cp(function(){return[0]
}),last:Cp(function(B,A){return[A-1]
}),eq:Cp(function(B,A,C){return[C<0?C+A:C]
}),even:Cp(function(B,A){for(var C=0;
C<A;
C+=2){B.push(C)
}return B
}),odd:Cp(function(B,A){for(var C=1;
C<A;
C+=2){B.push(C)
}return B
}),lt:Cp(function(C,A,D){for(var B=D<0?D+A:A<D?A:D;
0<=--B;
){C.push(B)
}return C
}),gt:Cp(function(C,A,D){for(var B=D<0?D+A:D;
++B<A;
){C.push(B)
}return C
})}}).pseudos.nth=DI.pseudos.eq,{radio:!0,checkbox:!0,file:!0,password:!0,image:!0}){DI.pseudos[DE]=Be(DE)
}for(DE in {submit:!0,reset:!0}){DI.pseudos[DE]=DY(DE)
}function Ds(){}function D0(C){for(var A=0,D=C.length,B="";
A<D;
A++){B+=C[A].value
}return B
}function DS(D,G,C){var B=G.dir,A=G.next,H=A||B,E=C&&"parentNode"===H,F=Cy++;
return G.first?function(J,I,K){while(J=J[B]){if(1===J.nodeType||E){return D(J,I,K)
}}return !1
}:function(M,K,O){var L,J,N,I=[C7,F];
if(O){while(M=M[B]){if((1===M.nodeType||E)&&D(M,K,O)){return !0
}}}else{while(M=M[B]){if(1===M.nodeType||E){if(J=(N=M[DT]||(M[DT]={}))[M.uniqueID]||(N[M.uniqueID]={}),A&&A===M.nodeName.toLowerCase()){M=M[B]||M
}else{if((L=J[H])&&L[0]===C7&&L[1]===F){return I[2]=L[2]
}if((J[H]=I)[2]=D(M,K,O)){return !0
}}}}}return !1
}
}function At(A){return 1<A.length?function(D,B,E){var C=A.length;
while(C--){if(!A[C](D,B,E)){return !1
}}return !0
}:A[0]
}function Dw(F,I,C,A,E){for(var B,G=[],J=0,H=F.length,D=null!=I;
J<H;
J++){(B=F[J])&&(C&&!C(B,A,E)||(G.push(B),D&&I.push(J)))
}return G
}function Da(E,B,C,A,F,D){return A&&!A[DT]&&(A=Da(A)),F&&!F[DT]&&(F=Da(F,D)),Dy(function(N,R,J,G){var L,I,P,S=[],Q=[],K=R.length,O=N||function(W,U,X){for(var V=0,T=U.length;
V<T;
V++){Dt(W,U[V],X)
}return X
}(B||"*",J.nodeType?[J]:J,[]),M=!E||!N&&B?O:Dw(O,S,E,J,G),H=C?F||(N?E:K||A)?[]:R:M;
if(C&&C(M,H,J,G),A){L=Dw(H,Q),A(L,[],J,G),I=L.length;
while(I--){(P=L[I])&&(H[Q[I]]=!(M[Q[I]]=P))
}}if(N){if(F||E){if(F){L=[],I=H.length;
while(I--){(P=H[I])&&L.push(M[I]=P)
}F(null,H=[],L,G)
}I=H.length;
while(I--){(P=H[I])&&-1<(L=F?DW(N,P):S[I])&&(N[L]=!(R[L]=P))
}}}else{H=Dw(H===R?H.splice(K,H.length):H),F?F(null,R,H,G):Dh.apply(R,H)
}})
}function Bt(F){for(var E,J,C,A=F.length,B=DI.relative[F[0].type],H=B||DI.relative[" "],K=B?1:0,I=DS(function(L){return L===E
},H,!0),D=DS(function(L){return -1<DW(E,L)
},H,!0),G=[function(N,L,O){var M=!B&&(O||L!==Ct)||((E=L).nodeType?I(N,L,O):D(N,L,O));
return E=null,M
}];
K<A;
K++){if(J=DI.relative[F[K].type]){G=[DS(At(G),J)]
}else{if((J=DI.filter[F[K].type].apply(null,F[K].matches))[DT]){for(C=++K;
C<A;
C++){if(DI.relative[F[C].type]){break
}}return Da(1<K&&At(G),1<K&&D0(F.slice(0,K-1).concat({value:" "===F[K-2].type?"*":""})).replace(Du,"$1"),J,K<C&&Bt(F.slice(K,C)),C<A&&Bt(F=F.slice(C)),C<A&&D0(F))
}G.push(J)
}}return At(G)
}return Ds.prototype=DI.filters=DI.pseudos,DI.setFilters=new Ds,DA=Dt.tokenize=function(F,I){var C,A,E,B,G,J,H,D=Cs[F+" "];
if(D){return I?0:D.slice(0)
}G=F,J=[],H=DI.preFilter;
while(G){for(B in C&&!(A=DK.exec(G))||(A&&(G=G.slice(A[0].length)||G),J.push(E=[])),C=!1,(A=Cq.exec(G))&&(C=A.shift(),E.push({value:C,type:A[0].replace(Du," ")}),G=G.slice(C.length)),DI.filter){!(A=Di[B].exec(G))||H[B]&&!(A=H[B](A))||(C=A.shift(),E.push({value:C,type:B,matches:A}),G=G.slice(C.length))
}if(!C){break
}}return I?G.length:G?Dt.error(F):Cs(F,J).slice(0)
},DD=Dt.compile=function(F,K){var C,J,G,D,I,A,E=[],B=[],H=Dp[F+" "];
if(!H){K||(K=DA(F)),C=K.length;
while(C--){(H=Bt(K[C]))[DT]?E.push(H):B.push(H)
}(H=Dp(F,(J=B,D=0<(G=E).length,I=0<J.length,A=function(U,Z,O,L,Q){var N,X,b,Y=0,P="0",W=U&&[],T=[],M=Ct,V=U||I&&DI.find.TAG("*",Q),R=C7+=null==M?1:Math.random()||0.1,S=V.length;
for(Q&&(Ct=Z==Dn||Z||Q);
P!==S&&null!=(N=V[P]);
P++){if(I&&N){X=0,Z||N.ownerDocument==Dn||(DR(N),O=!Dk);
while(b=J[X++]){if(b(N,Z||Dn,O)){L.push(N);
break
}}Q&&(C7=R)
}D&&((N=!b&&N)&&Y--,U&&W.push(N))
}if(Y+=P,D&&P!==Y){X=0;
while(b=G[X++]){b(W,T,Z,O)
}if(U){if(0<Y){while(P--){W[P]||T[P]||(T[P]=C0.call(L))
}}T=Dw(T)
}Dh.apply(L,T),Q&&!U&&0<T.length&&1<Y+G.length&&Dt.uniqueSort(L)
}return Q&&(C7=R,Ct=M),W
},D?Dy(A):A))).selector=F
}return H
},DC=Dt.select=function(F,J,C,A){var E,B,H,K,I,D="function"==typeof F&&F,G=!A&&DA(F=D.selector||F);
if(C=C||[],1===G.length){if(2<(B=G[0]=G[0].slice(0)).length&&"ID"===(H=B[0]).type&&9===J.nodeType&&Dk&&DI.relative[B[1].type]){if(!(J=(DI.find.ID(H.matches[0].replace(Dm,Dg),J)||[])[0])){return C
}D&&(J=J.parentNode),F=F.slice(B.shift().value.length)
}E=Di.needsContext.test(F)?0:B.length;
while(E--){if(H=B[E],DI.relative[K=H.type]){break
}if((I=DI.find[K])&&(A=I(H.matches[0].replace(Dm,Dg),Ae.test(B[0].type)&&Dv(J.parentNode)||J))){if(B.splice(E,1),!(F=A.length&&D0(B))){return Dh.apply(C,A),C
}break
}}}return(D||DD(F,G))(A,J,!Dk,C,!J||Ae.test(F)&&Dv(J.parentNode)||J),C
},DF.sortStable=DT.split("").sort(Dl).join("")===DT,DF.detectDuplicates=!!C6,DR(),DF.sortDetached=Cz(function(A){return 1&A.compareDocumentPosition(Dn.createElement("fieldset"))
}),Cz(function(A){return A.innerHTML="<a href='#'></a>","#"===A.firstChild.getAttribute("href")
})||Dx("type|href|height|width",function(B,A,C){if(!C){return B.getAttribute(A,"type"===A.toLowerCase()?1:2)
}}),DF.attributes&&Cz(function(A){return A.innerHTML="<input/>",A.firstChild.setAttribute("value",""),""===A.firstChild.getAttribute("value")
})||Dx("value",function(B,A,C){if(!C&&"input"===B.nodeName.toLowerCase()){return B.defaultValue
}}),Cz(function(A){return null==A.getAttribute("disabled")
})||Dx(DU,function(C,A,D){var B;
if(!D){return !0===C[A]?A.toLowerCase():(B=C.getAttributeNode(A))&&B.specified?B.value:null
}}),Dt
}(CP);
B3.find=Bl,B3.expr=Bl.selectors,B3.expr[":"]=B3.expr.pseudos,B3.uniqueSort=B3.unique=Bl.uniqueSort,B3.text=Bl.getText,B3.isXMLDoc=Bl.isXML,B3.contains=Bl.contains,B3.escapeSelector=Bl.escape;
var Bg=function(D,B,E){var C=[],A=void 0!==E;
while((D=D[B])&&9!==D.nodeType){if(1===D.nodeType){if(A&&B3(D).is(E)){break
}C.push(D)
}}return C
},B1=function(B,A){for(var C=[];
B;
B=B.nextSibling){1===B.nodeType&&B!==A&&C.push(B)
}return C
},Bb=B3.expr.match.needsContext;
function CS(B,A){return B.nodeName&&B.nodeName.toLowerCase()===A.toLowerCase()
}var CA=/^<([a-z][^\/\0>:\x20\t\r\n\f]*)[\x20\t\r\n\f]*\/?>(?:<\/\1>|)$/i;
function CN(B,C,A){return BZ(C)?B3.grep(B,function(E,D){return !!C.call(E,D,E)!==A
}):C.nodeType?B3.grep(B,function(D){return D===C!==A
}):"string"!=typeof C?B3.grep(B,function(D){return -1<Bf.call(C,D)!==A
}):B3.filter(C,B,A)
}B3.filter=function(C,A,D){var B=A[0];
return D&&(C=":not("+C+")"),1===A.length&&1===B.nodeType?B3.find.matchesSelector(B,C)?[B]:[]:B3.find.matches(C,B3.grep(A,function(E){return 1===E.nodeType
}))
},B3.fn.extend({find:function(D){var B,E,C=this.length,A=this;
if("string"!=typeof D){return this.pushStack(B3(D).filter(function(){for(B=0;
B<C;
B++){if(B3.contains(A[B],this)){return !0
}}}))
}for(E=this.pushStack([]),B=0;
B<C;
B++){B3.find(D,A[B],E)
}return 1<C?B3.uniqueSort(E):E
},filter:function(A){return this.pushStack(CN(this,A||[],!1))
},not:function(A){return this.pushStack(CN(this,A||[],!0))
},is:function(A){return !!CN(this,"string"==typeof A&&Bb.test(A)?B3(A):A||[],!1).length
}});
var Bc,BU=/^(?:\s*(<[\w\W]+>)[^>]*|#([\w-]+))$/;
(B3.fn.init=function(D,B,E){var C,A;
if(!D){return this
}if(E=E||Bc,"string"==typeof D){if(!(C="<"===D[0]&&">"===D[D.length-1]&&3<=D.length?[null,D,null]:BU.exec(D))||!C[1]&&B){return !B||B.jquery?(B||E).find(D):this.constructor(B).find(D)
}if(C[1]){if(B=B instanceof B3?B[0]:B,B3.merge(this,B3.parseHTML(C[1],B&&B.nodeType?B.ownerDocument||B:CL,!0)),CA.test(C[1])&&B3.isPlainObject(B)){for(C in B){BZ(this[C])?this[C](B[C]):this.attr(C,B[C])
}}return this
}return(A=CL.getElementById(C[2]))&&(this[0]=A,this.length=1),this
}return D.nodeType?(this[0]=D,this.length=1,this):BZ(D)?void 0!==E.ready?E.ready(D):D(B3):B3.makeArray(D,this)
}).prototype=B3.fn,Bc=B3(CL);
var CC=/^(?:parents|prev(?:Until|All))/,CH={children:!0,contents:!0,next:!0,prev:!0};
function B8(B,A){while((B=B[A])&&1!==B.nodeType){}return B
}B3.fn.extend({has:function(B){var A=B3(B,this),C=A.length;
return this.filter(function(){for(var D=0;
D<C;
D++){if(B3.contains(this,A[D])){return !0
}}})
},closest:function(E,C){var G,D=0,B=this.length,F=[],A="string"!=typeof E&&B3(E);
if(!Bb.test(E)){for(;
D<B;
D++){for(G=this[D];
G&&G!==C;
G=G.parentNode){if(G.nodeType<11&&(A?-1<A.index(G):1===G.nodeType&&B3.find.matchesSelector(G,E))){F.push(G);
break
}}}}return this.pushStack(1<F.length?B3.uniqueSort(F):F)
},index:function(A){return A?"string"==typeof A?Bf.call(B3(A),this[0]):Bf.call(this,A.jquery?A[0]:A):this[0]&&this[0].parentNode?this.first().prevAll().length:-1
},add:function(B,A){return this.pushStack(B3.uniqueSort(B3.merge(this.get(),B3(B,A))))
},addBack:function(A){return this.add(null==A?this.prevObject:this.prevObject.filter(A))
}}),B3.each({parent:function(B){var A=B.parentNode;
return A&&11!==A.nodeType?A:null
},parents:function(A){return Bg(A,"parentNode")
},parentsUntil:function(B,A,C){return Bg(B,"parentNode",C)
},next:function(A){return B8(A,"nextSibling")
},prev:function(A){return B8(A,"previousSibling")
},nextAll:function(A){return Bg(A,"nextSibling")
},prevAll:function(A){return Bg(A,"previousSibling")
},nextUntil:function(B,A,C){return Bg(B,"nextSibling",C)
},prevUntil:function(B,A,C){return Bg(B,"previousSibling",C)
},siblings:function(A){return B1((A.parentNode||{}).firstChild,A)
},children:function(A){return B1(A.firstChild)
},contents:function(A){return null!=A.contentDocument&&BT(A.contentDocument)?A.contentDocument:(CS(A,"template")&&(A=A.content||A),B3.merge([],A.childNodes))
}},function(B,A){B3.fn[B]=function(D,C){var E=B3.map(this,A,D);
return"Until"!==B.slice(-5)&&(C=D),C&&"string"==typeof C&&(E=B3.filter(C,E)),1<this.length&&(CH[B]||B3.uniqueSort(E),CC.test(B)&&E.reverse()),this.pushStack(E)
}
});
var B7=/[^\x20\t\r\n\f]+/g;
function B4(A){return A
}function CB(A){throw A
}function CG(D,B,E,C){var A;
try{D&&BZ(A=D.promise)?A.call(D).done(B).fail(E):D&&BZ(A=D.then)?A.call(D,B,E):B.apply(void 0,[D].slice(C))
}catch(D){E.apply(void 0,[D])
}}B3.Callbacks=function(A){var G,C;
A="string"==typeof A?(G=A,C={},B3.each(G.match(B7)||[],function(N,M){C[M]=!0
}),C):B3.extend({},A);
var E,K,B,I,L=[],J=[],D=-1,H=function(){for(I=I||A.once,B=E=!0;
J.length;
D=-1){K=J.shift();
while(++D<L.length){!1===L[D].apply(K[0],K[1])&&A.stopOnFalse&&(D=L.length,K=!1)
}}A.memory||(K=!1),E=!1,I&&(L=K?[]:"")
},F={add:function(){return L&&(K&&!E&&(D=L.length-1,J.push(K)),function M(N){B3.each(N,function(P,O){BZ(O)?A.unique&&F.has(O)||L.push(O):O&&O.length&&"string"!==BN(O)&&M(O)
})
}(arguments),K&&!E&&H()),this
},remove:function(){return B3.each(arguments,function(N,M){var O;
while(-1<(O=B3.inArray(M,L,O))){L.splice(O,1),O<=D&&D--
}}),this
},has:function(M){return M?-1<B3.inArray(M,L):0<L.length
},empty:function(){return L&&(L=[]),this
},disable:function(){return I=J=[],L=K="",this
},disabled:function(){return !L
},lock:function(){return I=J=[],K||E||(L=K=""),this
},locked:function(){return !!I
},fireWith:function(N,M){return I||(M=[N,(M=M||[]).slice?M.slice():M],J.push(M),E||H()),this
},fire:function(){return F.fireWith(this,arguments),this
},fired:function(){return !!B
}};
return F
},B3.extend({Deferred:function(D){var E=[["notify","progress",B3.Callbacks("memory"),B3.Callbacks("memory"),2],["resolve","done",B3.Callbacks("once memory"),B3.Callbacks("once memory"),0,"resolved"],["reject","fail",B3.Callbacks("once memory"),B3.Callbacks("once memory"),1,"rejected"]],B="pending",A={state:function(){return B
},always:function(){return C.done(arguments).fail(arguments),this
},"catch":function(F){return A.then(null,F)
},pipe:function(){var F=arguments;
return B3.Deferred(function(G){B3.each(E,function(I,H){var J=BZ(F[H[4]])&&F[H[4]];
C[H[1]](function(){var K=J&&J.apply(this,arguments);
K&&BZ(K.promise)?K.promise().progress(G.notify).done(G.resolve).fail(G.reject):G[H[0]+"With"](this,J?[K]:arguments)
})
}),F=null
}).promise()
},then:function(H,J,I){var G=0;
function F(L,N,K,M){return function(){var R=this,P=arguments,Q=function(){var T,S;
if(!(L<G)){if((T=K.apply(R,P))===N.promise()){throw new TypeError("Thenable self-resolution")
}S=T&&("object"==typeof T||"function"==typeof T)&&T.then,BZ(S)?M?S.call(T,F(G,N,B4,M),F(G,N,CB,M)):(G++,S.call(T,F(G,N,B4,M),F(G,N,CB,M),F(G,N,B4,N.notifyWith))):(K!==B4&&(R=void 0,P=[T]),(M||N.resolveWith)(R,P))
}},O=M?Q:function(){try{S()
}catch(S){B3.Deferred.exceptionHook&&B3.Deferred.exceptionHook(S,O.stackTrace),G<=L+1&&(K!==CB&&(R=void 0,P=[S]),N.rejectWith(R,P))
}};
L?O():(B3.Deferred.getStackHook&&(O.stackTrace=B3.Deferred.getStackHook()),CP.setTimeout(O))
}
}return B3.Deferred(function(K){E[0][3].add(F(0,K,BZ(I)?I:B4,K.notifyWith)),E[1][3].add(F(0,K,BZ(H)?H:B4)),E[2][3].add(F(0,K,BZ(J)?J:CB))
}).promise()
},promise:function(F){return null!=F?B3.extend(F,A):A
}},C={};
return B3.each(E,function(H,F){var I=F[2],G=F[5];
A[F[1]]=I.add,G&&I.add(function(){B=G
},E[3-H][2].disable,E[3-H][3].disable,E[0][2].lock,E[0][3].lock),I.add(F[3].fire),C[F[0]]=function(){return C[F[0]+"With"](this===C?void 0:this,arguments),this
},C[F[0]+"With"]=I.fireWith
}),A.promise(C),D&&D.call(C,C),C
},when:function(E){var G=arguments.length,C=G,D=Array(C),B=BS.call(arguments),F=B3.Deferred(),A=function(H){return function(I){D[H]=this,B[H]=1<arguments.length?BS.call(arguments):I,--G||F.resolveWith(D,B)
}
};
if(G<=1&&(CG(E,F.done(A(C)).resolve,F.reject,!G),"pending"===F.state()||BZ(B[C]&&B[C].then))){return F.then()
}while(C--){CG(B[C],A(C),F.reject)
}return F.promise()
}});
var Bx=/^(Eval|Internal|Range|Reference|Syntax|Type|URI)Error$/;
B3.Deferred.exceptionHook=function(B,A){CP.console&&CP.console.warn&&B&&Bx.test(B.name)&&CP.console.warn("jQuery.Deferred exception: "+B.message,B.stack,A)
},B3.readyException=function(A){CP.setTimeout(function(){throw A
})
};
var CK=B3.Deferred();
function CQ(){CL.removeEventListener("DOMContentLoaded",CQ),CP.removeEventListener("load",CQ),B3.ready()
}B3.fn.ready=function(A){return CK.then(A)["catch"](function(B){B3.readyException(B)
}),this
},B3.extend({isReady:!1,readyWait:1,ready:function(A){(!0===A?--B3.readyWait:B3.isReady)||(B3.isReady=!0)!==A&&0<--B3.readyWait||CK.resolveWith(CL,[B3])
}}),B3.ready.then=CK.then,"complete"===CL.readyState||"loading"!==CL.readyState&&!CL.documentElement.doScroll?CP.setTimeout(B3.ready):(CL.addEventListener("DOMContentLoaded",CQ),CP.addEventListener("load",CQ));
var Cc=function(F,I,C,A,E,B,G){var J=0,H=F.length,D=null==C;
if("object"===BN(C)){for(J in E=!0,C){Cc(F,I,J,C[J],!0,B,G)
}}else{if(void 0!==A&&(E=!0,BZ(A)||(G=!0),D&&(G?(I.call(F,A),I=null):(D=I,I=function(L,K,M){return D.call(B3(L),M)
})),I)){for(;
J<H;
J++){I(F[J],C,G?A:A.call(F[J],J,I(F[J],C)))
}}}return E?F:D?I.call(F):H?I(F[0],C):B
},Bq=/^-ms-/,BJ=/-([a-z])/g;
function B0(B,A){return A.toUpperCase()
}function Bw(A){return A.replace(Bq,"ms-").replace(BJ,B0)
}var By=function(A){return 1===A.nodeType||9===A.nodeType||!+A.nodeType
};
function CI(){this.expando=B3.expando+CI.uid++
}CI.uid=1,CI.prototype={cache:function(B){var A=B[this.expando];
return A||(A={},By(B)&&(B.nodeType?B[this.expando]=A:Object.defineProperty(B,this.expando,{value:A,configurable:!0}))),A
},set:function(D,B,E){var C,A=this.cache(D);
if("string"==typeof B){A[Bw(B)]=E
}else{for(C in B){A[Bw(C)]=B[C]
}}return A
},get:function(B,A){return void 0===A?this.cache(B):B[this.expando]&&B[this.expando][Bw(A)]
},access:function(B,A,C){return void 0===A||A&&"string"==typeof A&&void 0===C?this.get(B,A):(this.set(B,A,C),void 0!==C?C:A)
},remove:function(C,A){var D,B=C[this.expando];
if(void 0!==B){if(void 0!==A){D=(A=Array.isArray(A)?A.map(Bw):(A=Bw(A)) in B?[A]:A.match(B7)||[]).length;
while(D--){delete B[A[D]]
}}(void 0===A||B3.isEmptyObject(B))&&(C.nodeType?C[this.expando]=void 0:delete C[this.expando])
}},hasData:function(B){var A=B[this.expando];
return void 0!==A&&!B3.isEmptyObject(A)
}};
var Bv=new CI,B6=new CI,CF=/^(?:\{[\w\W]*\}|\[[\w\W]*\])$/,CD=/[A-Z]/g;
function Bs(D,B,E){var C,A;
if(void 0===E&&1===D.nodeType){if(C="data-"+B.replace(CD,"-$&").toLowerCase(),"string"==typeof (E=D.getAttribute(C))){try{E="true"===(A=E)||"false"!==A&&("null"===A?null:A===+A+""?+A:CF.test(A)?JSON.parse(A):A)
}catch(D){}B6.set(D,B,E)
}else{E=void 0
}}return E
}B3.extend({hasData:function(A){return B6.hasData(A)||Bv.hasData(A)
},data:function(B,A,C){return B6.access(B,A,C)
},removeData:function(B,A){B6.remove(B,A)
},_data:function(B,A,C){return Bv.access(B,A,C)
},_removeData:function(B,A){Bv.remove(B,A)
}}),B3.fn.extend({data:function(G,E){var C,D,B,F=this[0],A=F&&F.attributes;
if(void 0===G){if(this.length&&(B=B6.get(F),1===F.nodeType&&!Bv.get(F,"hasDataAttrs"))){C=A.length;
while(C--){A[C]&&0===(D=A[C].name).indexOf("data-")&&(D=Bw(D.slice(5)),Bs(F,D,B[D]))
}Bv.set(F,"hasDataAttrs",!0)
}return B
}return"object"==typeof G?this.each(function(){B6.set(this,G)
}):Cc(this,function(I){var H;
if(F&&void 0===I){return void 0!==(H=B6.get(F,G))?H:void 0!==(H=Bs(F,G))?H:void 0
}this.each(function(){B6.set(this,G,I)
})
},null,E,1<arguments.length,null,!0)
},removeData:function(A){return this.each(function(){B6.remove(this,A)
})
}}),B3.extend({queue:function(C,A,D){var B;
if(C){return A=(A||"fx")+"queue",B=Bv.get(C,A),D&&(!B||Array.isArray(D)?B=Bv.access(C,A,B3.makeArray(D)):B.push(D)),B||[]
}},dequeue:function(D,B){B=B||"fx";
var F=B3.queue(D,B),C=F.length,A=F.shift(),E=B3._queueHooks(D,B);
"inprogress"===A&&(A=F.shift(),C--),A&&("fx"===B&&F.unshift("inprogress"),delete E.stop,A.call(D,function(){B3.dequeue(D,B)
},E)),!C&&E&&E.empty.fire()
},_queueHooks:function(B,A){var C=A+"queueHooks";
return Bv.get(B,C)||Bv.access(B,C,{empty:B3.Callbacks("once memory").add(function(){Bv.remove(B,[A+"queue",C])
})})
}}),B3.fn.extend({queue:function(A,C){var B=2;
return"string"!=typeof A&&(C=A,A="fx",B--),arguments.length<B?B3.queue(this[0],A):void 0===C?this:this.each(function(){var D=B3.queue(this,A,C);
B3._queueHooks(this,A),"fx"===A&&"inprogress"!==D[0]&&B3.dequeue(this,A)
})
},dequeue:function(A){return this.each(function(){B3.dequeue(this,A)
})
},clearQueue:function(A){return this.queue(A||"fx",[])
},promise:function(F,C){var H,E=1,B=B3.Deferred(),G=this,A=this.length,D=function(){--E||B.resolveWith(G,[G])
};
"string"!=typeof F&&(C=F,F=void 0),F=F||"fx";
while(A--){(H=Bv.get(G[A],F+"queueHooks"))&&H.empty&&(E++,H.empty.add(D))
}return D(),B.promise(C)
}});
var A8=/[+-]?(?:\d*\.|)\d+(?:[eE][+-]?\d+|)/.source,Ak=new RegExp("^(?:([+-])=|)("+A8+")([a-z%]*)$","i"),CT=["Top","Right","Bottom","Left"],A3=CL.documentElement,AZ=function(A){return B3.contains(A.ownerDocument,A)
},Br={composed:!0};
A3.getRootNode&&(AZ=function(A){return B3.contains(A.ownerDocument,A)||A.getRootNode(Br)===A.ownerDocument
});
var CZ=function(B,A){return"none"===(B=A||B).style.display||""===B.style.display&&AZ(B)&&"none"===B3.css(B,"display")
};
function As(F,J,C,A){var E,B,H=20,K=A?function(){return A.cur()
}:function(){return B3.css(F,J,"")
},I=K(),D=C&&C[3]||(B3.cssNumber[J]?"":"px"),G=F.nodeType&&(B3.cssNumber[J]||"px"!==D&&+I)&&Ak.exec(B3.css(F,J));
if(G&&G[3]!==D){I/=2,D=D||G[3],G=+I||1;
while(H--){B3.style(F,J,G+D),(1-B)*(1-(B=K()/I||0.5))<=0&&(H=0),G/=B
}G*=2,B3.style(F,J,G+D),C=C||[]
}return C&&(G=+G||+I||0,E=C[1]?G+(C[1]+1)*C[2]:+C[2],A&&(A.unit=D,A.start=G,A.end=E)),E
}var Ab={};
function Cn(G,K){for(var C,A,E,B,I,L,J,D=[],H=0,F=G.length;
H<F;
H++){(A=G[H]).style&&(C=A.style.display,K?("none"===C&&(D[H]=Bv.get(A,"display")||null,D[H]||(A.style.display="")),""===A.style.display&&CZ(A)&&(D[H]=(J=I=B=void 0,I=(E=A).ownerDocument,L=E.nodeName,(J=Ab[L])||(B=I.body.appendChild(I.createElement(L)),J=B3.css(B,"display"),B.parentNode.removeChild(B),"none"===J&&(J="block"),Ab[L]=J)))):"none"!==C&&(D[H]="none",Bv.set(A,"display",C)))
}for(H=0;
H<F;
H++){null!=D[H]&&(G[H].style.display=D[H])
}return G
}B3.fn.extend({show:function(){return Cn(this,!0)
},hide:function(){return Cn(this)
},toggle:function(A){return"boolean"==typeof A?A?this.show():this.hide():this.each(function(){CZ(this)?B3(this).show():B3(this).hide()
})
}});
var Bd,A0,BI=/^(?:checkbox|radio)$/i,BF=/<([a-z][^\/\0>\x20\t\r\n\f]*)/i,Ai=/^$|^module$|\/(?:java|ecma)script/i;
Bd=CL.createDocumentFragment().appendChild(CL.createElement("div")),(A0=CL.createElement("input")).setAttribute("type","radio"),A0.setAttribute("checked","checked"),A0.setAttribute("name","t"),Bd.appendChild(A0),BK.checkClone=Bd.cloneNode(!0).cloneNode(!0).lastChild.checked,Bd.innerHTML="<textarea>x</textarea>",BK.noCloneChecked=!!Bd.cloneNode(!0).lastChild.defaultValue,Bd.innerHTML="<option></option>",BK.option=!!Bd.lastChild;
var Aq={thead:[1,"<table>","</table>"],col:[2,"<table><colgroup>","</colgroup></table>"],tr:[2,"<table><tbody>","</tbody></table>"],td:[3,"<table><tbody><tr>","</tr></tbody></table>"],_default:[0,"",""]};
function AT(B,A){var C;
return C="undefined"!=typeof B.getElementsByTagName?B.getElementsByTagName(A||"*"):"undefined"!=typeof B.querySelectorAll?B.querySelectorAll(A||"*"):[],void 0===A||A&&CS(B,A)?B3.merge([B],C):C
}function Ch(C,A){for(var D=0,B=C.length;
D<B;
D++){Bv.set(C[D],"globalEval",!A||Bv.get(A[D],"globalEval"))
}}Aq.tbody=Aq.tfoot=Aq.colgroup=Aq.caption=Aq.thead,Aq.th=Aq.td,BK.option||(Aq.optgroup=Aq.option=[1,"<select multiple='multiple'>","</select>"]);
var Cf=/<|&#?\w+;/;
function AC(I,N,D,A,F){for(var C,L,O,M,E,K,H=N.createDocumentFragment(),B=[],J=0,G=I.length;
J<G;
J++){if((C=I[J])||0===C){if("object"===BN(C)){B3.merge(B,C.nodeType?[C]:C)
}else{if(Cf.test(C)){L=L||H.appendChild(N.createElement("div")),O=(BF.exec(C)||["",""])[1].toLowerCase(),M=Aq[O]||Aq._default,L.innerHTML=M[1]+B3.htmlPrefilter(C)+M[2],K=M[0];
while(K--){L=L.lastChild
}B3.merge(B,L.childNodes),(L=H.firstChild).textContent=""
}else{B.push(N.createTextNode(C))
}}}}H.textContent="",J=0;
while(C=B[J++]){if(A&&-1<B3.inArray(C,A)){F&&F.push(C)
}else{if(E=AZ(C),L=AT(H.appendChild(C),"script"),E&&Ch(L),D){K=0;
while(C=L[K++]){Ai.test(C.type||"")&&D.push(C)
}}}}return H
}var CE=/^key/,AL=/^(?:mouse|pointer|contextmenu|drag|drop)|click/,Cg=/^([^.]*)(?:\.(.+)|)/;
function Ah(){return !0
}function AQ(){return !1
}function AB(B,A){return B===function(){try{return CL.activeElement
}catch(C){}}()==("focus"===A)
}function AJ(F,C,H,E,B,G){var A,D;
if("object"==typeof C){for(D in "string"!=typeof H&&(E=E||H,H=void 0),C){AJ(F,D,H,E,C[D],G)
}return F
}if(null==E&&null==B?(B=H,E=H=void 0):null==B&&("string"==typeof H?(B=E,E=void 0):(B=E,E=H,H=void 0)),!1===B){B=AQ
}else{if(!B){return F
}}return 1===G&&(A=B,(B=function(I){return B3().off(I),A.apply(this,arguments)
}).guid=A.guid||(A.guid=B3.guid++)),F.each(function(){B3.event.add(this,C,B,E,H)
})
}function Az(B,A,C){C?(Bv.set(B,A,!1),B3.event.add(B,A,{namespace:!1,handler:function(F){var D,G,E=Bv.get(this,A);
if(1&F.isTrigger&&this[A]){if(E.length){(B3.event.special[A]||{}).delegateType&&F.stopPropagation()
}else{if(E=BS.call(arguments),Bv.set(this,A,E),D=C(this,A),this[A](),E!==(G=Bv.get(this,A))||D?Bv.set(this,A,!1):G={},E!==G){return F.stopImmediatePropagation(),F.preventDefault(),G.value
}}}else{E.length&&(Bv.set(this,A,{value:B3.event.trigger(B3.extend(E[0],B3.Event.prototype),E.slice(1),this)}),F.stopImmediatePropagation())
}}})):void 0===Bv.get(B,A)&&B3.event.add(B,A,Ah)
}B3.event={global:{},add:function(P,J,D,A,F){var C,M,Q,O,E,L,I,B,K,G,H,N=Bv.get(P);
if(By(P)){D.handler&&(D=(C=D).handler,F=C.selector),F&&B3.find.matchesSelector(A3,F),D.guid||(D.guid=B3.guid++),(O=N.events)||(O=N.events=Object.create(null)),(M=N.handle)||(M=N.handle=function(R){return"undefined"!=typeof B3&&B3.event.triggered!==R.type?B3.event.dispatch.apply(P,arguments):void 0
}),E=(J=(J||"").match(B7)||[""]).length;
while(E--){K=H=(Q=Cg.exec(J[E])||[])[1],G=(Q[2]||"").split(".").sort(),K&&(I=B3.event.special[K]||{},K=(F?I.delegateType:I.bindType)||K,I=B3.event.special[K]||{},L=B3.extend({type:K,origType:H,data:A,handler:D,guid:D.guid,selector:F,needsContext:F&&B3.expr.match.needsContext.test(F),namespace:G.join(".")},C),(B=O[K])||((B=O[K]=[]).delegateCount=0,I.setup&&!1!==I.setup.call(P,A,G,M)||P.addEventListener&&P.addEventListener(K,M)),I.add&&(I.add.call(P,L),L.handler.guid||(L.handler.guid=D.guid)),F?B.splice(B.delegateCount++,0,L):B.push(L),B3.event.global[K]=!0)
}}},remove:function(J,P,D,A,F){var C,M,Q,O,E,L,I,B,K,G,H,N=Bv.hasData(J)&&Bv.get(J);
if(N&&(O=N.events)){E=(P=(P||"").match(B7)||[""]).length;
while(E--){if(K=H=(Q=Cg.exec(P[E])||[])[1],G=(Q[2]||"").split(".").sort(),K){I=B3.event.special[K]||{},B=O[K=(A?I.delegateType:I.bindType)||K]||[],Q=Q[2]&&new RegExp("(^|\\.)"+G.join("\\.(?:.*\\.|)")+"(\\.|$)"),M=C=B.length;
while(C--){L=B[C],!F&&H!==L.origType||D&&D.guid!==L.guid||Q&&!Q.test(L.namespace)||A&&A!==L.selector&&("**"!==A||!L.selector)||(B.splice(C,1),L.selector&&B.delegateCount--,I.remove&&I.remove.call(J,L))
}M&&!B.length&&(I.teardown&&!1!==I.teardown.call(J,G,N.handle)||B3.removeEvent(J,K,N.handle),delete O[K])
}else{for(K in O){B3.event.remove(J,K+P[E],D,A,!0)
}}}B3.isEmptyObject(O)&&Bv.remove(J,"handle events")
}},dispatch:function(F){var J,C,A,E,B,H,K=new Array(arguments.length),I=B3.event.fix(F),D=(Bv.get(this,"events")||Object.create(null))[I.type]||[],G=B3.event.special[I.type]||{};
for(K[0]=I,J=1;
J<arguments.length;
J++){K[J]=arguments[J]
}if(I.delegateTarget=this,!G.preDispatch||!1!==G.preDispatch.call(this,I)){H=B3.event.handlers.call(this,I,D),J=0;
while((E=H[J++])&&!I.isPropagationStopped()){I.currentTarget=E.elem,C=0;
while((B=E.handlers[C++])&&!I.isImmediatePropagationStopped()){I.rnamespace&&!1!==B.namespace&&!I.rnamespace.test(B.namespace)||(I.handleObj=B,I.data=B.data,void 0!==(A=((B3.event.special[B.origType]||{}).handle||B.handler).apply(E.elem,K))&&!1===(I.result=A)&&(I.preventDefault(),I.stopPropagation()))
}}return G.postDispatch&&G.postDispatch.call(this,I),I.result
}},handlers:function(F,I){var C,A,E,B,G,J=[],H=I.delegateCount,D=F.target;
if(H&&D.nodeType&&!("click"===F.type&&1<=F.button)){for(;
D!==this;
D=D.parentNode||this){if(1===D.nodeType&&("click"!==F.type||!0!==D.disabled)){for(B=[],G={},C=0;
C<H;
C++){void 0===G[E=(A=I[C]).selector+" "]&&(G[E]=A.needsContext?-1<B3(E,this).index(D):B3.find(E,this,null,[D]).length),G[E]&&B.push(A)
}B.length&&J.push({elem:D,handlers:B})
}}}return D=this,H<I.length&&J.push({elem:D,handlers:I.slice(H)}),J
},addProp:function(A,B){Object.defineProperty(B3.Event.prototype,A,{enumerable:!0,configurable:!0,get:BZ(B)?function(){if(this.originalEvent){return B(this.originalEvent)
}}:function(){if(this.originalEvent){return this.originalEvent[A]
}},set:function(C){Object.defineProperty(this,A,{enumerable:!0,configurable:!0,writable:!0,value:C})
}})
},fix:function(A){return A[B3.expando]?A:new B3.Event(A)
},special:{load:{noBubble:!0},click:{setup:function(B){var A=this||B;
return BI.test(A.type)&&A.click&&CS(A,"input")&&Az(A,"click",Ah),!1
},trigger:function(B){var A=this||B;
return BI.test(A.type)&&A.click&&CS(A,"input")&&Az(A,"click"),!0
},_default:function(B){var A=B.target;
return BI.test(A.type)&&A.click&&CS(A,"input")&&Bv.get(A,"click")||CS(A,"a")
}},beforeunload:{postDispatch:function(A){void 0!==A.result&&A.originalEvent&&(A.originalEvent.returnValue=A.result)
}}}},B3.removeEvent=function(B,A,C){B.removeEventListener&&B.removeEventListener(A,C)
},B3.Event=function(B,A){if(!(this instanceof B3.Event)){return new B3.Event(B,A)
}B&&B.type?(this.originalEvent=B,this.type=B.type,this.isDefaultPrevented=B.defaultPrevented||void 0===B.defaultPrevented&&!1===B.returnValue?Ah:AQ,this.target=B.target&&3===B.target.nodeType?B.target.parentNode:B.target,this.currentTarget=B.currentTarget,this.relatedTarget=B.relatedTarget):this.type=B,A&&B3.extend(this,A),this.timeStamp=B&&B.timeStamp||Date.now(),this[B3.expando]=!0
},B3.Event.prototype={constructor:B3.Event,isDefaultPrevented:AQ,isPropagationStopped:AQ,isImmediatePropagationStopped:AQ,isSimulated:!1,preventDefault:function(){var A=this.originalEvent;
this.isDefaultPrevented=Ah,A&&!this.isSimulated&&A.preventDefault()
},stopPropagation:function(){var A=this.originalEvent;
this.isPropagationStopped=Ah,A&&!this.isSimulated&&A.stopPropagation()
},stopImmediatePropagation:function(){var A=this.originalEvent;
this.isImmediatePropagationStopped=Ah,A&&!this.isSimulated&&A.stopImmediatePropagation(),this.stopPropagation()
}},B3.each({altKey:!0,bubbles:!0,cancelable:!0,changedTouches:!0,ctrlKey:!0,detail:!0,eventPhase:!0,metaKey:!0,pageX:!0,pageY:!0,shiftKey:!0,view:!0,"char":!0,code:!0,charCode:!0,key:!0,keyCode:!0,button:!0,buttons:!0,clientX:!0,clientY:!0,offsetX:!0,offsetY:!0,pointerId:!0,pointerType:!0,screenX:!0,screenY:!0,targetTouches:!0,toElement:!0,touches:!0,which:function(B){var A=B.button;
return null==B.which&&CE.test(B.type)?null!=B.charCode?B.charCode:B.keyCode:!B.which&&void 0!==A&&AL.test(B.type)?1&A?1:2&A?3:4&A?2:0:B.which
}},B3.event.addProp),B3.each({focus:"focusin",blur:"focusout"},function(B,A){B3.event.special[B]={setup:function(){return Az(this,B,AB),!1
},trigger:function(){return Az(this,B),!0
},delegateType:A}
}),B3.each({mouseenter:"mouseover",mouseleave:"mouseout",pointerenter:"pointerover",pointerleave:"pointerout"},function(B,A){B3.event.special[B]={delegateType:A,bindType:A,handle:function(E){var C,F=E.relatedTarget,D=E.handleObj;
return F&&(F===this||B3.contains(this,F))||(E.type=D.origType,C=D.handler.apply(this,arguments),E.type=A),C
}}
}),B3.fn.extend({on:function(C,A,D,B){return AJ(this,C,A,D,B)
},one:function(C,A,D,B){return AJ(this,C,A,D,B,1)
},off:function(D,B,E){var C,A;
if(D&&D.preventDefault&&D.handleObj){return C=D.handleObj,B3(D.delegateTarget).off(C.namespace?C.origType+"."+C.namespace:C.origType,C.selector,C.handler),this
}if("object"==typeof D){for(A in D){this.off(A,B,D[A])
}return this
}return !1!==B&&"function"!=typeof B||(E=B,B=void 0),!1===E&&(E=AQ),this.each(function(){B3.event.remove(this,D,E,B)
})
}});
var Ar=/<script|<style|<link/i,AY=/checked\s*(?:[^=]|=\s*.checked.)/i,AR=/^\s*<!(?:\[CDATA\[|--)|(?:\]\]|--)>\s*$/g;
function BB(B,A){return CS(B,"table")&&CS(11!==A.nodeType?A:A.firstChild,"tr")&&B3(B).children("tbody")[0]||B
}function BA(A){return A.type=(null!==A.getAttribute("type"))+"/"+A.type,A
}function Cd(A){return"true/"===(A.type||"").slice(0,5)?A.type=A.type.slice(5):A.removeAttribute("type"),A
}function Aj(F,C){var H,E,B,G,A,D;
if(1===C.nodeType){if(Bv.hasData(F)&&(D=Bv.get(F).events)){for(B in Bv.remove(C,"handle events"),D){for(H=0,E=D[B].length;
H<E;
H++){B3.event.add(C,B,D[B][H])
}}}B6.hasData(F)&&(G=B6.access(F),A=B3.extend({},G),B6.set(C,A))
}}function Aa(D,A,F,C){A=Bh(A);
var I,N,L,O,M,E,K=0,H=D.length,B=H-1,J=A[0],G=BZ(J);
if(G||1<H&&"string"==typeof J&&!BK.checkClone&&AY.test(J)){return D.each(function(Q){var P=D.eq(Q);
G&&(A[0]=J.call(this,Q,P.html())),Aa(P,A,F,C)
})
}if(H&&(N=(I=AC(A,D[0].ownerDocument,!1,D,C)).firstChild,1===I.childNodes.length&&(I=N),N||C)){for(O=(L=B3.map(AT(I,"script"),BA)).length;
K<H;
K++){M=I,K!==B&&(M=B3.clone(M,!0,!0),O&&B3.merge(L,AT(M,"script"))),F.call(D[K],M,K)
}if(O){for(E=L[L.length-1].ownerDocument,B3.map(L,Cd),K=0;
K<O;
K++){M=L[K],Ai.test(M.type||"")&&!Bv.access(M,"globalEval")&&B3.contains(E,M)&&(M.src&&"module"!==(M.type||"").toLowerCase()?B3._evalUrl&&!M.noModule&&B3._evalUrl(M.src,{nonce:M.nonce||M.getAttribute("nonce")},E):Bn(M.textContent.replace(AR,""),M,E))
}}}return D
}function AK(D,B,F){for(var C,A=B?B3.filter(B,D):D,E=0;
null!=(C=A[E]);
E++){F||1!==C.nodeType||B3.cleanData(AT(C)),C.parentNode&&(F&&AZ(C)&&Ch(AT(C,"script")),C.parentNode.removeChild(C))
}return D
}B3.extend({htmlPrefilter:function(A){return A
},clone:function(G,K,C){var A,E,B,I,L,J,D,H=G.cloneNode(!0),F=AZ(G);
if(!(BK.noCloneChecked||1!==G.nodeType&&11!==G.nodeType||B3.isXMLDoc(G))){for(I=AT(H),A=0,E=(B=AT(G)).length;
A<E;
A++){L=B[A],J=I[A],void 0,"input"===(D=J.nodeName.toLowerCase())&&BI.test(L.type)?J.checked=L.checked:"input"!==D&&"textarea"!==D||(J.defaultValue=L.defaultValue)
}}if(K){if(C){for(B=B||AT(G),I=I||AT(H),A=0,E=B.length;
A<E;
A++){Aj(B[A],I[A])
}}else{Aj(G,H)
}}return 0<(I=AT(H,"script")).length&&Ch(I,!F&&AT(G,"script")),H
},cleanData:function(D){for(var B,F,C,A=B3.event.special,E=0;
void 0!==(F=D[E]);
E++){if(By(F)){if(B=F[Bv.expando]){if(B.events){for(C in B.events){A[C]?B3.event.remove(F,C):B3.removeEvent(F,C,B.handle)
}}F[Bv.expando]=void 0
}F[B6.expando]&&(F[B6.expando]=void 0)
}}}}),B3.fn.extend({detach:function(A){return AK(this,A,!0)
},remove:function(A){return AK(this,A)
},text:function(A){return Cc(this,function(B){return void 0===B?B3.text(this):this.empty().each(function(){1!==this.nodeType&&11!==this.nodeType&&9!==this.nodeType||(this.textContent=B)
})
},null,A,arguments.length)
},append:function(){return Aa(this,arguments,function(A){1!==this.nodeType&&11!==this.nodeType&&9!==this.nodeType||BB(this,A).appendChild(A)
})
},prepend:function(){return Aa(this,arguments,function(B){if(1===this.nodeType||11===this.nodeType||9===this.nodeType){var A=BB(this,B);
A.insertBefore(B,A.firstChild)
}})
},before:function(){return Aa(this,arguments,function(A){this.parentNode&&this.parentNode.insertBefore(A,this)
})
},after:function(){return Aa(this,arguments,function(A){this.parentNode&&this.parentNode.insertBefore(A,this.nextSibling)
})
},empty:function(){for(var B,A=0;
null!=(B=this[A]);
A++){1===B.nodeType&&(B3.cleanData(AT(B,!1)),B.textContent="")
}return this
},clone:function(B,A){return B=null!=B&&B,A=null==A?B:A,this.map(function(){return B3.clone(this,B,A)
})
},html:function(A){return Cc(this,function(D){var B=this[0]||{},E=0,C=this.length;
if(void 0===D&&1===B.nodeType){return B.innerHTML
}if("string"==typeof D&&!Ar.test(D)&&!Aq[(BF.exec(D)||["",""])[1].toLowerCase()]){D=B3.htmlPrefilter(D);
try{for(;
E<C;
E++){1===(B=this[E]||{}).nodeType&&(B3.cleanData(AT(B,!1)),B.innerHTML=D)
}B=0
}catch(D){}}B&&this.empty().append(D)
},null,A,arguments.length)
},replaceWith:function(){var A=[];
return Aa(this,arguments,function(C){var B=this.parentNode;
B3.inArray(this,A)<0&&(B3.cleanData(AT(this)),B&&B.replaceChild(C,this))
},A)
}}),B3.each({appendTo:"append",prependTo:"prepend",insertBefore:"before",insertAfter:"after",replaceAll:"replaceWith"},function(B,A){B3.fn[B]=function(F){for(var D,H=[],E=B3(F),C=E.length-1,G=0;
G<=C;
G++){D=G===C?this:this.clone(!0),B3(E[G])[A](D),BP.apply(H,D.get())
}return this.pushStack(H)
}
});
var A2=new RegExp("^("+A8+")(?!px)[a-z%]+$","i"),CR=function(B){var A=B.ownerDocument.defaultView;
return A&&A.opener||(A=CP),A.getComputedStyle(B)
},BQ=function(D,B,F){var C,A,E={};
for(A in B){E[A]=D.style[A],D.style[A]=B[A]
}for(A in C=F.call(D),B){D.style[A]=E[A]
}return C
},AI=new RegExp(CT.join("|"),"i");
function Ap(F,C,H){var E,B,G,A,D=F.style;
return(H=H||CR(F))&&(""!==(A=H.getPropertyValue(C)||H[C])||AZ(F)||(A=B3.style(F,C)),!BK.pixelBoxStyles()&&A2.test(A)&&AI.test(C)&&(E=D.width,B=D.minWidth,G=D.maxWidth,D.minWidth=D.maxWidth=D.width=A,A=H.width,D.width=E,D.minWidth=B,D.maxWidth=G)),void 0!==A?A+"":A
}function CO(B,A){return{get:function(){if(!B()){return(this.get=A).apply(this,arguments)
}delete this.get
}}
}!function(){function F(){if(D){H.style.cssText="position:absolute;left:-11111px;width:60px;margin-top:1px;padding:0;border:0",D.style.cssText="position:relative;display:block;box-sizing:border-box;overflow:scroll;margin:auto;border:1px;padding:1px;width:60%;top:1%",A3.appendChild(H).appendChild(D);
var K=CP.getComputedStyle(D);
C="1%"!==K.top,J=12===I(K.marginLeft),D.style.right="60%",B=36===I(K.right),A=36===I(K.width),D.style.position="absolute",E=12===I(D.offsetWidth/3),A3.removeChild(H),D=null
}}function I(K){return Math.round(parseFloat(K))
}var C,A,E,B,G,J,H=CL.createElement("div"),D=CL.createElement("div");
D.style&&(D.style.backgroundClip="content-box",D.cloneNode(!0).style.backgroundClip="",BK.clearCloneStyle="content-box"===D.style.backgroundClip,B3.extend(BK,{boxSizingReliable:function(){return F(),A
},pixelBoxStyles:function(){return F(),B
},pixelPosition:function(){return F(),C
},reliableMarginLeft:function(){return F(),J
},scrollboxSize:function(){return F(),E
},reliableTrDimensions:function(){var M,K,N,L;
return null==G&&(M=CL.createElement("table"),K=CL.createElement("tr"),N=CL.createElement("div"),M.style.cssText="position:absolute;left:-11111px",K.style.height="1px",N.style.height="9px",A3.appendChild(M).appendChild(K).appendChild(N),L=CP.getComputedStyle(K),G=3<parseInt(L.height),A3.removeChild(M)),G
}}))
}();
var AF=["Webkit","Moz","ms"],CW=CL.createElement("div").style,CV={};
function BD(B){var A=B3.cssProps[B]||CV[B];
return A||(B in CW?B:CV[B]=function(D){var C=D[0].toUpperCase()+D.slice(1),E=AF.length;
while(E--){if((D=AF[E]+C) in CW){return D
}}}(B)||B)
}var Bz=/^(none|table(?!-c[ea]).+)/,Cm=/^--/,A5={position:"absolute",visibility:"hidden",display:"block"},AS={letterSpacing:"0",fontWeight:"400"};
function Bp(C,A,D){var B=Ak.exec(A);
return B?Math.max(0,B[2]-(D||0))+(B[3]||"px"):A
}function BH(E,H,C,A,D,B){var F="width"===H?1:0,I=0,G=0;
if(C===(A?"border":"content")){return 0
}for(;
F<4;
F+=2){"margin"===C&&(G+=B3.css(E,C+CT[F],!0,D)),A?("content"===C&&(G-=B3.css(E,"padding"+CT[F],!0,D)),"margin"!==C&&(G-=B3.css(E,"border"+CT[F]+"Width",!0,D))):(G+=B3.css(E,"padding"+CT[F],!0,D),"padding"!==C?G+=B3.css(E,"border"+CT[F]+"Width",!0,D):I+=B3.css(E,"border"+CT[F]+"Width",!0,D))
}return !A&&0<=B&&(G+=Math.max(0,Math.ceil(E["offset"+H[0].toUpperCase()+H.slice(1)]-B-G-I-0.5))||0),G
}function Aw(F,C,H){var E=CR(F),B=(!BK.boxSizingReliable()||H)&&"border-box"===B3.css(F,"boxSizing",!1,E),G=B,A=Ap(F,C,E),D="offset"+C[0].toUpperCase()+C.slice(1);
if(A2.test(A)){if(!H){return A
}A="auto"
}return(!BK.boxSizingReliable()&&B||!BK.reliableTrDimensions()&&CS(F,"tr")||"auto"===A||!parseFloat(A)&&"inline"===B3.css(F,"display",!1,E))&&F.getClientRects().length&&(B="border-box"===B3.css(F,"boxSizing",!1,E),(G=D in F)&&(A=F[D])),(A=parseFloat(A)||0)+BH(F,C,H||(B?"border":"content"),G,E,A)+"px"
}function A4(D,B,E,C,A){return new A4.prototype.init(D,B,E,C,A)
}B3.extend({cssHooks:{opacity:{get:function(B,A){if(A){var C=Ap(B,"opacity");
return""===C?"1":C
}}}},cssNumber:{animationIterationCount:!0,columnCount:!0,fillOpacity:!0,flexGrow:!0,flexShrink:!0,fontWeight:!0,gridArea:!0,gridColumn:!0,gridColumnEnd:!0,gridColumnStart:!0,gridRow:!0,gridRowEnd:!0,gridRowStart:!0,lineHeight:!0,opacity:!0,order:!0,orphans:!0,widows:!0,zIndex:!0,zoom:!0},cssProps:{},style:function(F,I,C,A){if(F&&3!==F.nodeType&&8!==F.nodeType&&F.style){var E,B,G,J=Bw(I),H=Cm.test(I),D=F.style;
if(H||(I=BD(J)),G=B3.cssHooks[I]||B3.cssHooks[J],void 0===C){return G&&"get" in G&&void 0!==(E=G.get(F,!1,A))?E:D[I]
}"string"===(B=typeof C)&&(E=Ak.exec(C))&&E[1]&&(C=As(F,I,E),B="number"),null!=C&&C==C&&("number"!==B||H||(C+=E&&E[3]||(B3.cssNumber[J]?"":"px")),BK.clearCloneStyle||""!==C||0!==I.indexOf("background")||(D[I]="inherit"),G&&"set" in G&&void 0===(C=G.set(F,C,A))||(H?D.setProperty(I,C):D[I]=C))
}},css:function(F,C,H,E){var B,G,A,D=Bw(C);
return Cm.test(C)||(C=BD(D)),(A=B3.cssHooks[C]||B3.cssHooks[D])&&"get" in A&&(B=A.get(F,!0,H)),void 0===B&&(B=Ap(F,C,E)),"normal"===B&&C in AS&&(B=AS[C]),""===H||H?(G=parseFloat(B),!0===H||isFinite(G)?G||0:B):B
}}),B3.each(["height","width"],function(B,A){B3.cssHooks[A]={get:function(D,C,E){if(C){return !Bz.test(B3.css(D,"display"))||D.getClientRects().length&&D.getBoundingClientRect().width?Aw(D,A,E):BQ(D,A5,function(){return Aw(D,A,E)
})
}},set:function(H,E,J){var G,D=CR(H),I=!BK.scrollboxSize()&&"absolute"===D.position,C=(I||J)&&"border-box"===B3.css(H,"boxSizing",!1,D),F=J?BH(H,A,J,C,D):0;
return C&&I&&(F-=Math.ceil(H["offset"+A[0].toUpperCase()+A.slice(1)]-parseFloat(D[A])-BH(H,A,"border",!1,D)-0.5)),F&&(G=Ak.exec(E))&&"px"!==(G[3]||"px")&&(H.style[A]=E,E=B3.css(H,A)),Bp(0,E,F)
}}
}),B3.cssHooks.marginLeft=CO(BK.reliableMarginLeft,function(B,A){if(A){return(parseFloat(Ap(B,"marginLeft"))||B.getBoundingClientRect().left-BQ(B,{marginLeft:0},function(){return B.getBoundingClientRect().left
}))+"px"
}}),B3.each({margin:"",padding:"",border:"Width"},function(A,B){B3.cssHooks[A+B]={expand:function(E){for(var C=0,F={},D="string"==typeof E?E.split(" "):[E];
C<4;
C++){F[A+CT[C]+B]=D[C]||D[C-2]||D[0]
}return F
}},"margin"!==A&&(B3.cssHooks[A+B].set=Bp)
}),B3.fn.extend({css:function(B,A){return Cc(this,function(G,E,I){var F,D,H={},C=0;
if(Array.isArray(E)){for(F=CR(G),D=E.length;
C<D;
C++){H[E[C]]=B3.css(G,E[C],!1,F)
}return H
}return void 0!==I?B3.style(G,E,I):B3.css(G,E)
},B,A,1<arguments.length)
}}),((B3.Tween=A4).prototype={constructor:A4,init:function(D,B,F,C,A,E){this.elem=D,this.prop=F,this.easing=A||B3.easing._default,this.options=B,this.start=this.now=this.cur(),this.end=C,this.unit=E||(B3.cssNumber[F]?"":"px")
},cur:function(){var A=A4.propHooks[this.prop];
return A&&A.get?A.get(this):A4.propHooks._default.get(this)
},run:function(B){var A,C=A4.propHooks[this.prop];
return this.options.duration?this.pos=A=B3.easing[this.easing](B,this.options.duration*B,0,1,this.options.duration):this.pos=A=B,this.now=(this.end-this.start)*A+this.start,this.options.step&&this.options.step.call(this.elem,this.now,this),C&&C.set?C.set(this):A4.propHooks._default.set(this),this
}}).init.prototype=A4.prototype,(A4.propHooks={_default:{get:function(B){var A;
return 1!==B.elem.nodeType||null!=B.elem[B.prop]&&null==B.elem.style[B.prop]?B.elem[B.prop]:(A=B3.css(B.elem,B.prop,""))&&"auto"!==A?A:0
},set:function(A){B3.fx.step[A.prop]?B3.fx.step[A.prop](A):1!==A.elem.nodeType||!B3.cssHooks[A.prop]&&null==A.elem.style[BD(A.prop)]?A.elem[A.prop]=A.now:B3.style(A.elem,A.prop,A.now+A.unit)
}}}).scrollTop=A4.propHooks.scrollLeft={set:function(A){A.elem.nodeType&&A.elem.parentNode&&(A.elem[A.prop]=A.now)
}},B3.easing={linear:function(A){return A
},swing:function(A){return 0.5-Math.cos(A*Math.PI)/2
},_default:"swing"},B3.fx=A4.prototype.init,B3.fx.step={};
var Ag,B9,Ay,AV,BY=/^(?:toggle|show|hide)$/,CU=/queueHooks$/;
function Ao(){B9&&(!1===CL.hidden&&CP.requestAnimationFrame?CP.requestAnimationFrame(Ao):CP.setTimeout(Ao,B3.fx.interval),B3.fx.tick())
}function AX(){return CP.setTimeout(function(){Ag=void 0
}),Ag=Date.now()
}function Cj(D,B){var E,C=0,A={height:D};
for(B=B?1:0;
C<4;
C+=2-B){A["margin"+(E=CT[C])]=A["padding"+E]=D
}return B&&(A.opacity=A.width=D),A
}function BL(E,C,G){for(var D,B=(Av.tweeners[C]||[]).concat(Av.tweeners["*"]),F=0,A=B.length;
F<A;
F++){if(D=B[F].call(G,C,E)){return D
}}}function Av(B,F,J){var C,H,A=0,E=Av.prefilters.length,K=B3.Deferred().always(function(){delete I.elem
}),I=function(){if(H){return !1
}for(var O=Ag||AX(),M=Math.max(0,D.startTime+D.duration-O),P=1-(M/D.duration||0),N=0,L=D.tweens.length;
N<L;
N++){D.tweens[N].run(P)
}return K.notifyWith(B,[D,P,M]),P<1&&L?M:(L||K.notifyWith(B,[D,1,0]),K.resolveWith(B,[D]),!1)
},D=K.promise({elem:B,props:B3.extend({},F),opts:B3.extend(!0,{specialEasing:{},easing:B3.easing._default},J),originalProperties:F,originalOptions:J,startTime:Ag||AX(),duration:J.duration,tweens:[],createTween:function(M,L){var N=B3.Tween(B,D.opts,M,L,D.opts.specialEasing[M]||D.opts.easing);
return D.tweens.push(N),N
},stop:function(M){var L=0,N=M?D.tweens.length:0;
if(H){return this
}for(H=!0;
L<N;
L++){D.tweens[L].run(1)
}return M?(K.notifyWith(B,[D,1,0]),K.resolveWith(B,[D,M])):K.rejectWith(B,[D,M]),this
}}),G=D.props;
for(!function(P,N){var R,O,M,Q,L;
for(R in P){if(M=N[O=Bw(R)],Q=P[R],Array.isArray(Q)&&(M=Q[1],Q=P[R]=Q[0]),R!==O&&(P[O]=Q,delete P[R]),(L=B3.cssHooks[O])&&"expand" in L){for(R in Q=L.expand(Q),delete P[O],Q){R in P||(P[R]=Q[R],N[R]=M)
}}else{N[O]=M
}}}(G,D.opts.specialEasing);
A<E;
A++){if(C=Av.prefilters[A].call(D,B,G,D.opts)){return BZ(C.stop)&&(B3._queueHooks(D.elem,D.opts.queue).stop=C.stop.bind(C)),C
}}return B3.map(G,BL,D),BZ(D.opts.start)&&D.opts.start.call(B,D),D.progress(D.opts.progress).done(D.opts.done,D.opts.complete).fail(D.opts.fail).always(D.opts.always),B3.fx.timer(B3.extend(I,{elem:B,anim:D,queue:D.opts.queue})),D
}B3.Animation=B3.extend(Av,{tweeners:{"*":[function(B,A){var C=this.createTween(B,A);
return As(C.elem,B,Ak.exec(A),C),C
}]},tweener:function(D,B){BZ(D)?(B=D,D=["*"]):D=D.match(B7);
for(var E,C=0,A=D.length;
C<A;
C++){E=D[C],Av.tweeners[E]=Av.tweeners[E]||[],Av.tweeners[E].unshift(B)
}},prefilters:[function(J,P,D){var A,F,C,M,Q,O,E,L,I="width" in P||"height" in P,B=this,K={},G=J.style,H=J.nodeType&&CZ(J),N=Bv.get(J,"fxshow");
for(A in D.queue||(null==(M=B3._queueHooks(J,"fx")).unqueued&&(M.unqueued=0,Q=M.empty.fire,M.empty.fire=function(){M.unqueued||Q()
}),M.unqueued++,B.always(function(){B.always(function(){M.unqueued--,B3.queue(J,"fx").length||M.empty.fire()
})
})),P){if(F=P[A],BY.test(F)){if(delete P[A],C=C||"toggle"===F,F===(H?"hide":"show")){if("show"!==F||!N||void 0===N[A]){continue
}H=!0
}K[A]=N&&N[A]||B3.style(J,A)
}}if((O=!B3.isEmptyObject(P))||!B3.isEmptyObject(K)){for(A in I&&1===J.nodeType&&(D.overflow=[G.overflow,G.overflowX,G.overflowY],null==(E=N&&N.display)&&(E=Bv.get(J,"display")),"none"===(L=B3.css(J,"display"))&&(E?L=E:(Cn([J],!0),E=J.style.display||E,L=B3.css(J,"display"),Cn([J]))),("inline"===L||"inline-block"===L&&null!=E)&&"none"===B3.css(J,"float")&&(O||(B.done(function(){G.display=E
}),null==E&&(L=G.display,E="none"===L?"":L)),G.display="inline-block")),D.overflow&&(G.overflow="hidden",B.always(function(){G.overflow=D.overflow[0],G.overflowX=D.overflow[1],G.overflowY=D.overflow[2]
})),O=!1,K){O||(N?"hidden" in N&&(H=N.hidden):N=Bv.access(J,"fxshow",{display:E}),C&&(N.hidden=!H),H&&Cn([J],!0),B.done(function(){for(A in H||Cn([J]),Bv.remove(J,"fxshow"),K){B3.style(J,A,K[A])
}})),O=BL(H?N[A]:0,A,B),A in N||(N[A]=O.start,H&&(O.end=O.start,O.start=0))
}}}],prefilter:function(B,A){A?Av.prefilters.unshift(B):Av.prefilters.push(B)
}}),B3.speed=function(C,A,D){var B=C&&"object"==typeof C?B3.extend({},C):{complete:D||!D&&A||BZ(C)&&C,duration:C,easing:D&&A||A&&!BZ(A)&&A};
return B3.fx.off?B.duration=0:"number"!=typeof B.duration&&(B.duration in B3.fx.speeds?B.duration=B3.fx.speeds[B.duration]:B.duration=B3.fx.speeds._default),null!=B.queue&&!0!==B.queue||(B.queue="fx"),B.old=B.complete,B.complete=function(){BZ(B.old)&&B.old.call(this),B.queue&&B3.dequeue(this,B.queue)
},B
},B3.fn.extend({fadeTo:function(C,A,D,B){return this.filter(CZ).css("opacity",0).show().end().animate({opacity:A},C,D,B)
},animate:function(C,E,G,D){var B=B3.isEmptyObject(C),F=B3.speed(E,G,D),A=function(){var H=Av(this,B3.extend({},C),F);
(B||Bv.get(this,"finish"))&&H.stop(!0)
};
return A.finish=A,B||!1===F.queue?this.each(A):this.queue(F.queue,A)
},stop:function(B,C,D){var A=function(F){var E=F.stop;
delete F.stop,E(D)
};
return"string"!=typeof B&&(D=C,C=B,B=void 0),C&&this.queue(B||"fx",[]),this.each(function(){var G=!0,E=null!=B&&B+"queueHooks",H=B3.timers,F=Bv.get(this);
if(E){F[E]&&F[E].stop&&A(F[E])
}else{for(E in F){F[E]&&F[E].stop&&CU.test(E)&&A(F[E])
}}for(E=H.length;
E--;
){H[E].elem!==this||null!=B&&H[E].queue!==B||(H[E].anim.stop(D),G=!1,H.splice(E,1))
}!G&&D||B3.dequeue(this,B)
})
},finish:function(A){return !1!==A&&(A=A||"fx"),this.each(function(){var E,C=Bv.get(this),G=C[A+"queue"],D=C[A+"queueHooks"],B=B3.timers,F=G?G.length:0;
for(C.finish=!0,B3.queue(this,A,[]),D&&D.stop&&D.stop.call(this,!0),E=B.length;
E--;
){B[E].elem===this&&B[E].queue===A&&(B[E].anim.stop(!0),B.splice(E,1))
}for(E=0;
E<F;
E++){G[E]&&G[E].finish&&G[E].finish.call(this)
}delete C.finish
})
}}),B3.each(["toggle","show","hide"],function(C,B){var A=B3.fn[B];
B3.fn[B]=function(E,D,F){return null==E||"boolean"==typeof E?A.apply(this,arguments):this.animate(Cj(B,!0),E,D,F)
}
}),B3.each({slideDown:Cj("show"),slideUp:Cj("hide"),slideToggle:Cj("toggle"),fadeIn:{opacity:"show"},fadeOut:{opacity:"hide"},fadeToggle:{opacity:"toggle"}},function(B,A){B3.fn[B]=function(D,C,E){return this.animate(A,D,C,E)
}
}),B3.timers=[],B3.fx.tick=function(){var B,A=0,C=B3.timers;
for(Ag=Date.now();
A<C.length;
A++){(B=C[A])()||C[A]!==B||C.splice(A--,1)
}C.length||B3.fx.stop(),Ag=void 0
},B3.fx.timer=function(A){B3.timers.push(A),B3.fx.start()
},B3.fx.interval=13,B3.fx.start=function(){B9||(B9=!0,Ao())
},B3.fx.stop=function(){B9=null
},B3.fx.speeds={slow:600,fast:200,_default:400},B3.fn.delay=function(A,B){return A=B3.fx&&B3.fx.speeds[A]||A,B=B||"fx",this.queue(B,function(D,C){var E=CP.setTimeout(D,A);
C.stop=function(){CP.clearTimeout(E)
}
})
},Ay=CL.createElement("input"),AV=CL.createElement("select").appendChild(CL.createElement("option")),Ay.type="checkbox",BK.checkOn=""!==Ay.value,BK.optSelected=AV.selected,(Ay=CL.createElement("input")).value="t",Ay.type="radio",BK.radioValue="t"===Ay.value;
var BE,BC=B3.expr.attrHandle;
B3.fn.extend({attr:function(B,A){return Cc(this,B3.attr,B,A,1<arguments.length)
},removeAttr:function(A){return this.each(function(){B3.removeAttr(this,A)
})
}}),B3.extend({attr:function(D,B,F){var C,A,E=D.nodeType;
if(3!==E&&8!==E&&2!==E){return"undefined"==typeof D.getAttribute?B3.prop(D,B,F):(1===E&&B3.isXMLDoc(D)||(A=B3.attrHooks[B.toLowerCase()]||(B3.expr.match.bool.test(B)?BE:void 0)),void 0!==F?null===F?void B3.removeAttr(D,B):A&&"set" in A&&void 0!==(C=A.set(D,F,B))?C:(D.setAttribute(B,F+""),F):A&&"get" in A&&null!==(C=A.get(D,B))?C:null==(C=B3.find.attr(D,B))?void 0:C)
}},attrHooks:{type:{set:function(B,A){if(!BK.radioValue&&"radio"===A&&CS(B,"input")){var C=B.value;
return B.setAttribute("type",A),C&&(B.value=C),A
}}}},removeAttr:function(D,B){var E,C=0,A=B&&B.match(B7);
if(A&&1===D.nodeType){while(E=A[C++]){D.removeAttribute(E)
}}}}),BE={set:function(B,A,C){return !1===A?B3.removeAttr(B,C):B.setAttribute(C,C),C
}},B3.each(B3.expr.match.bool.source.match(/\w+/g),function(C,B){var A=BC[B]||B3.find.attr;
BC[B]=function(G,E,I){var F,D,H=E.toLowerCase();
return I||(D=BC[H],BC[H]=F,F=null!=A(G,E,I)?H:null,BC[H]=D),F
}
});
var Ad=/^(?:input|select|textarea|button)$/i,Am=/^(?:a|area)$/i;
function AP(A){return(A.match(B7)||[]).join(" ")
}function Cb(A){return A.getAttribute&&A.getAttribute("class")||""
}function CY(A){return Array.isArray(A)?A:"string"==typeof A&&A.match(B7)||[]
}B3.fn.extend({prop:function(B,A){return Cc(this,B3.prop,B,A,1<arguments.length)
},removeProp:function(A){return this.each(function(){delete this[B3.propFix[A]||A]
})
}}),B3.extend({prop:function(D,B,F){var C,A,E=D.nodeType;
if(3!==E&&8!==E&&2!==E){return 1===E&&B3.isXMLDoc(D)||(B=B3.propFix[B]||B,A=B3.propHooks[B]),void 0!==F?A&&"set" in A&&void 0!==(C=A.set(D,F,B))?C:D[B]=F:A&&"get" in A&&null!==(C=A.get(D,B))?C:D[B]
}},propHooks:{tabIndex:{get:function(B){var A=B3.find.attr(B,"tabindex");
return A?parseInt(A,10):Ad.test(B.nodeName)||Am.test(B.nodeName)&&B.href?0:-1
}}},propFix:{"for":"htmlFor","class":"className"}}),BK.optSelected||(B3.propHooks.selected={get:function(B){var A=B.parentNode;
return A&&A.parentNode&&A.parentNode.selectedIndex,null
},set:function(B){var A=B.parentNode;
A&&(A.selectedIndex,A.parentNode&&A.parentNode.selectedIndex)
}}),B3.each(["tabIndex","readOnly","maxLength","cellSpacing","cellPadding","rowSpan","colSpan","useMap","frameBorder","contentEditable"],function(){B3.propFix[this.toLowerCase()]=this
}),B3.fn.extend({addClass:function(H){var E,C,A,D,B,F,I,G=0;
if(BZ(H)){return this.each(function(J){B3(this).addClass(H.call(this,J,Cb(this)))
})
}if((E=CY(H)).length){while(C=this[G++]){if(D=Cb(C),A=1===C.nodeType&&" "+AP(D)+" "){F=0;
while(B=E[F++]){A.indexOf(" "+B+" ")<0&&(A+=B+" ")
}D!==(I=AP(A))&&C.setAttribute("class",I)
}}}return this
},removeClass:function(H){var E,C,A,D,B,F,I,G=0;
if(BZ(H)){return this.each(function(J){B3(this).removeClass(H.call(this,J,Cb(this)))
})
}if(!arguments.length){return this.attr("class","")
}if((E=CY(H)).length){while(C=this[G++]){if(D=Cb(C),A=1===C.nodeType&&" "+AP(D)+" "){F=0;
while(B=E[F++]){while(-1<A.indexOf(" "+B+" ")){A=A.replace(" "+B+" "," ")
}}D!==(I=AP(A))&&C.setAttribute("class",I)
}}}return this
},toggleClass:function(C,B){var D=typeof C,A="string"===D||Array.isArray(C);
return"boolean"==typeof B&&A?B?this.addClass(C):this.removeClass(C):BZ(C)?this.each(function(E){B3(this).toggleClass(C.call(this,E,Cb(this),B),B)
}):this.each(function(){var G,E,H,F;
if(A){E=0,H=B3(this),F=CY(C);
while(G=F[E++]){H.hasClass(G)?H.removeClass(G):H.addClass(G)
}}else{void 0!==C&&"boolean"!==D||((G=Cb(this))&&Bv.set(this,"__className__",G),this.setAttribute&&this.setAttribute("class",G||!1===C?"":Bv.get(this,"__className__")||""))
}})
},hasClass:function(C){var A,D,B=0;
A=" "+C+" ";
while(D=this[B++]){if(1===D.nodeType&&-1<(" "+AP(Cb(D))+" ").indexOf(A)){return !0
}}return !1
}});
var Cl=/\r/g;
B3.fn.extend({val:function(E){var C,D,B,A=this[0];
return arguments.length?(B=BZ(E),this.each(function(G){var F;
1===this.nodeType&&(null==(F=B?E.call(this,G,B3(this).val()):E)?F="":"number"==typeof F?F+="":Array.isArray(F)&&(F=B3.map(F,function(H){return null==H?"":H+""
})),(C=B3.valHooks[this.type]||B3.valHooks[this.nodeName.toLowerCase()])&&"set" in C&&void 0!==C.set(this,F,"value")||(this.value=F))
})):A?(C=B3.valHooks[A.type]||B3.valHooks[A.nodeName.toLowerCase()])&&"get" in C&&void 0!==(D=C.get(A,"value"))?D:"string"==typeof (D=A.value)?D.replace(Cl,""):null==D?"":D:void 0
}}),B3.extend({valHooks:{option:{get:function(B){var A=B3.find.attr(B,"value");
return null!=A?A:AP(B3.text(B))
}},select:{get:function(E){var H,C,A,D=E.options,B=E.selectedIndex,F="select-one"===E.type,I=F?null:[],G=F?B+1:D.length;
for(A=B<0?G:F?B:0;
A<G;
A++){if(((C=D[A]).selected||A===B)&&!C.disabled&&(!C.parentNode.disabled||!CS(C.parentNode,"optgroup"))){if(H=B3(C).val(),F){return H
}I.push(H)
}}return I
},set:function(E,C){var G,D,B=E.options,F=B3.makeArray(C),A=B.length;
while(A--){((D=B[A]).selected=-1<B3.inArray(B3.valHooks.option.get(D),F))&&(G=!0)
}return G||(E.selectedIndex=-1),F
}}}}),B3.each(["radio","checkbox"],function(){B3.valHooks[this]={set:function(B,A){if(Array.isArray(A)){return B.checked=-1<B3.inArray(B3(B).val(),A)
}}},BK.checkOn||(B3.valHooks[this].get=function(A){return null===A.getAttribute("value")?"on":A.value
})
}),BK.focusin="onfocusin" in CP;
var Bu=/^(?:focusinfocus|focusoutblur)$/,AH=function(A){A.stopPropagation()
};
B3.extend(B3.event,{trigger:function(I,N,D,A){var F,C,L,O,M,E,K,H,B=[D||CL],J=BO.call(I,"type")?I.type:I,G=BO.call(I,"namespace")?I.namespace.split("."):[];
if(C=H=L=D=D||CL,3!==D.nodeType&&8!==D.nodeType&&!Bu.test(J+B3.event.triggered)&&(-1<J.indexOf(".")&&(J=(G=J.split(".")).shift(),G.sort()),M=J.indexOf(":")<0&&"on"+J,(I=I[B3.expando]?I:new B3.Event(J,"object"==typeof I&&I)).isTrigger=A?2:3,I.namespace=G.join("."),I.rnamespace=I.namespace?new RegExp("(^|\\.)"+G.join("\\.(?:.*\\.|)")+"(\\.|$)"):null,I.result=void 0,I.target||(I.target=D),N=null==N?[I]:B3.makeArray(N,[I]),K=B3.event.special[J]||{},A||!K.trigger||!1!==K.trigger.apply(D,N))){if(!A&&!K.noBubble&&!BM(D)){for(O=K.delegateType||J,Bu.test(O+J)||(C=C.parentNode);
C;
C=C.parentNode){B.push(C),L=C
}L===(D.ownerDocument||CL)&&B.push(L.defaultView||L.parentWindow||CP)
}F=0;
while((C=B[F++])&&!I.isPropagationStopped()){H=C,I.type=1<F?O:K.bindType||J,(E=(Bv.get(C,"events")||Object.create(null))[I.type]&&Bv.get(C,"handle"))&&E.apply(C,N),(E=M&&C[M])&&E.apply&&By(C)&&(I.result=E.apply(C,N),!1===I.result&&I.preventDefault())
}return I.type=J,A||I.isDefaultPrevented()||K._default&&!1!==K._default.apply(B.pop(),N)||!By(D)||M&&BZ(D[J])&&!BM(D)&&((L=D[M])&&(D[M]=null),B3.event.triggered=J,I.isPropagationStopped()&&H.addEventListener(J,AH),D[J](),I.isPropagationStopped()&&H.removeEventListener(J,AH),B3.event.triggered=void 0,L&&(D[M]=L)),I.result
}},simulate:function(C,A,D){var B=B3.extend(new B3.Event,D,{type:C,isSimulated:!0});
B3.event.trigger(B,null,A)
}}),B3.fn.extend({trigger:function(B,A){return this.each(function(){B3.event.trigger(B,A,this)
})
},triggerHandler:function(B,A){var C=this[0];
if(C){return B3.event.trigger(B,A,C,!0)
}}}),BK.focusin||B3.each({focus:"focusin",blur:"focusout"},function(C,B){var A=function(D){B3.event.simulate(B,D.target,B3.event.fix(D))
};
B3.event.special[B]={setup:function(){var E=this.ownerDocument||this.document||this,D=Bv.access(E,B);
D||E.addEventListener(C,A,!0),Bv.access(E,B,(D||0)+1)
},teardown:function(){var E=this.ownerDocument||this.document||this,D=Bv.access(E,B)-1;
D?Bv.access(E,B,D):(E.removeEventListener(C,A,!0),Bv.remove(E,B))
}}
});
var Ca=CP.location,Ac={guid:Date.now()},AM=/\?/;
B3.parseXML=function(B){var A;
if(!B||"string"!=typeof B){return null
}try{A=(new CP.DOMParser).parseFromString(B,"text/xml")
}catch(B){A=void 0
}return A&&!A.getElementsByTagName("parsererror").length||B3.error("Invalid XML: "+B),A
};
var Ck=/\[\]$/,AE=/\r?\n/g,Au=/^(?:submit|button|image|reset|file)$/i,An=/^(?:input|select|textarea|keygen)/i;
function AU(E,D,C,B){var A;
if(Array.isArray(D)){B3.each(D,function(G,F){C||Ck.test(E)?B(E,F):AU(E+"["+("object"==typeof F&&null!=F?G:"")+"]",F,C,B)
})
}else{if(C||"object"!==BN(D)){B(E,D)
}else{for(A in D){AU(E+"["+A+"]",D[A],C,B)
}}}}B3.param=function(D,B){var E,C=[],A=function(G,F){var H=BZ(F)?F():F;
C[C.length]=encodeURIComponent(G)+"="+encodeURIComponent(null==H?"":H)
};
if(null==D){return""
}if(Array.isArray(D)||D.jquery&&!B3.isPlainObject(D)){B3.each(D,function(){A(this.name,this.value)
})
}else{for(E in D){AU(E,D[E],B,A)
}}return C.join("&")
},B3.fn.extend({serialize:function(){return B3.param(this.serializeArray())
},serializeArray:function(){return this.map(function(){var A=B3.prop(this,"elements");
return A?B3.makeArray(A):this
}).filter(function(){var A=this.type;
return this.name&&!B3(this).is(":disabled")&&An.test(this.nodeName)&&!Au.test(A)&&(this.checked||!BI.test(A))
}).map(function(B,A){var C=B3(this).val();
return null==C?null:Array.isArray(C)?B3.map(C,function(D){return{name:A.name,value:D.replace(AE,"\r\n")}
}):{name:A.name,value:C.replace(AE,"\r\n")}
}).get()
}});
var AN=/%20/g,A7=/#.*$/,A6=/([?&])_=[^&]*/,CX=/^(.*?):[ \t]*([^\r\n]*)$/gm,Af=/^(?:GET|HEAD)$/,AW=/^\/\//,AG={},Ax={},B5="*/".concat("*"),BG=CL.createElement("a");
function AD(A){return function(E,C){"string"!=typeof E&&(C=E,E="*");
var F,D=0,B=E.toLowerCase().match(B7)||[];
if(BZ(C)){while(F=B[D++]){"+"===F[0]?(F=F.slice(1)||"*",(A[F]=A[F]||[]).unshift(C)):(A[F]=A[F]||[]).push(C)
}}}
}function Al(E,D,G,B){var F={},C=E===Ax;
function A(I){var H;
return F[I]=!0,B3.each(E[I]||[],function(K,J){var L=J(D,G,B);
return"string"!=typeof L||C||F[L]?C?!(H=L):void 0:(D.dataTypes.unshift(L),A(L),!1)
}),H
}return A(D.dataTypes[0])||!F["*"]&&A("*")
}function B2(D,B){var E,C,A=B3.ajaxSettings.flatOptions||{};
for(E in B){void 0!==B[E]&&((A[E]?D:C||(C={}))[E]=B[E])
}return C&&B3.extend(!0,D,C),D
}BG.href=Ca.href,B3.extend({active:0,lastModified:{},etag:{},ajaxSettings:{url:Ca.href,type:"GET",isLocal:/^(?:about|app|app-storage|.+-extension|file|res|widget):$/.test(Ca.protocol),global:!0,processData:!0,async:!0,contentType:"application/x-www-form-urlencoded; charset=UTF-8",accepts:{"*":B5,text:"text/plain",html:"text/html",xml:"application/xml, text/xml",json:"application/json, text/javascript"},contents:{xml:/\bxml\b/,html:/\bhtml/,json:/\bjson\b/},responseFields:{xml:"responseXML",text:"responseText",json:"responseJSON"},converters:{"* text":String,"text html":!0,"text json":JSON.parse,"text xml":B3.parseXML},flatOptions:{url:!0,context:!0}},ajaxSetup:function(B,A){return A?B2(B2(B,B3.ajaxSettings),A):B2(B3.ajaxSettings,B)
},ajaxPrefilter:AD(AG),ajaxTransport:AD(Ax),ajax:function(S,G){"object"==typeof S&&(G=S,S=void 0),G=G||{};
var V,R,J,L,U,I,P,Q,O,K,E=B3.ajaxSetup({},G),B=E.context||E,M=E.context&&(B.nodeType||B.jquery)?B3(B):B3.event,C=B3.Deferred(),W=B3.Callbacks("once memory"),D=E.statusCode||{},X={},H={},F="canceled",A={readyState:0,getResponseHeader:function(Y){var T;
if(P){if(!L){L={};
while(T=CX.exec(J)){L[T[1].toLowerCase()+" "]=(L[T[1].toLowerCase()+" "]||[]).concat(T[2])
}}T=L[Y.toLowerCase()+" "]
}return null==T?null:T.join(", ")
},getAllResponseHeaders:function(){return P?J:null
},setRequestHeader:function(Y,T){return null==P&&(Y=H[Y.toLowerCase()]=H[Y.toLowerCase()]||Y,X[Y]=T),this
},overrideMimeType:function(T){return null==P&&(E.mimeType=T),this
},statusCode:function(Y){var T;
if(Y){if(P){A.always(Y[A.status])
}else{for(T in Y){D[T]=[D[T],Y[T]]
}}}return this
},abort:function(Y){var T=Y||F;
return V&&V.abort(T),N(0,T),this
}};
if(C.promise(A),E.url=((S||E.url||Ca.href)+"").replace(AW,Ca.protocol+"//"),E.type=G.method||G.type||E.method||E.type,E.dataTypes=(E.dataType||"*").toLowerCase().match(B7)||[""],null==E.crossDomain){I=CL.createElement("a");
try{I.href=E.url,I.href=I.href,E.crossDomain=BG.protocol+"//"+BG.host!=I.protocol+"//"+I.host
}catch(S){E.crossDomain=!0
}}if(E.data&&E.processData&&"string"!=typeof E.data&&(E.data=B3.param(E.data,E.traditional)),Al(AG,E,G,A),P){return A
}for(O in (Q=B3.event&&E.global)&&0==B3.active++&&B3.event.trigger("ajaxStart"),E.type=E.type.toUpperCase(),E.hasContent=!Af.test(E.type),R=E.url.replace(A7,""),E.hasContent?E.data&&E.processData&&0===(E.contentType||"").indexOf("application/x-www-form-urlencoded")&&(E.data=E.data.replace(AN,"+")):(K=E.url.slice(R.length),E.data&&(E.processData||"string"==typeof E.data)&&(R+=(AM.test(R)?"&":"?")+E.data,delete E.data),!1===E.cache&&(R=R.replace(A6,"$1"),K=(AM.test(R)?"&":"?")+"_="+Ac.guid+++K),E.url=R+K),E.ifModified&&(B3.lastModified[R]&&A.setRequestHeader("If-Modified-Since",B3.lastModified[R]),B3.etag[R]&&A.setRequestHeader("If-None-Match",B3.etag[R])),(E.data&&E.hasContent&&!1!==E.contentType||G.contentType)&&A.setRequestHeader("Content-Type",E.contentType),A.setRequestHeader("Accept",E.dataTypes[0]&&E.accepts[E.dataTypes[0]]?E.accepts[E.dataTypes[0]]+("*"!==E.dataTypes[0]?", "+B5+"; q=0.01":""):E.accepts["*"]),E.headers){A.setRequestHeader(O,E.headers[O])
}if(E.beforeSend&&(!1===E.beforeSend.call(B,A,E)||P)){return A.abort()
}if(F="abort",W.add(E.complete),A.done(E.success),A.fail(E.error),V=Al(Ax,E,G,A)){if(A.readyState=1,Q&&M.trigger("ajaxSend",[A,E]),P){return A
}E.async&&0<E.timeout&&(U=CP.setTimeout(function(){A.abort("timeout")
},E.timeout));
try{P=!1,V.send(X,N)
}catch(S){if(P){throw S
}N(-1,S)
}}else{N(-1,"No Transport")
}function N(d,h,Z,T){var c,Y,f,j,g,b=h;
P||(P=!0,U&&CP.clearTimeout(U),V=void 0,J=T||"",A.readyState=0<d?4:0,c=200<=d&&d<300||304===d,Z&&(j=function(q,x,m){var k,p,l,v,y=q.contents,w=q.dataTypes;
while("*"===w[0]){w.shift(),void 0===k&&(k=q.mimeType||x.getResponseHeader("Content-Type"))
}if(k){for(p in y){if(y[p]&&y[p].test(k)){w.unshift(p);
break
}}}if(w[0] in m){l=w[0]
}else{for(p in m){if(!w[0]||q.converters[p+" "+w[0]]){l=p;
break
}v||(v=p)
}l=l||v
}if(l){return l!==w[0]&&w.unshift(l),m[l]
}}(E,A,Z)),!c&&-1<B3.inArray("script",E.dataTypes)&&(E.converters["text script"]=function(){}),j=function(w,Ae,p,k){var v,m,y,At,z,q={},x=w.dataTypes.slice();
if(x[1]){for(y in w.converters){q[y.toLowerCase()]=w.converters[y]
}}m=x.shift();
while(m){if(w.responseFields[m]&&(p[w.responseFields[m]]=Ae),!z&&k&&w.dataFilter&&(Ae=w.dataFilter(Ae,w.dataType)),z=m,m=x.shift()){if("*"===m){m=z
}else{if("*"!==z&&z!==m){if(!(y=q[z+" "+m]||q["* "+m])){for(v in q){if((At=v.split(" "))[1]===m&&(y=q[z+" "+At[0]]||q["* "+At[0]])){!0===y?y=q[v]:!0!==q[v]&&(m=At[0],x.unshift(At[1]));
break
}}}if(!0!==y){if(y&&w["throws"]){Ae=y(Ae)
}else{try{Ae=y(Ae)
}catch(w){return{state:"parsererror",error:y?w:"No conversion from "+z+" to "+m}
}}}}}}}return{state:"success",data:Ae}
}(E,j,A,c),c?(E.ifModified&&((g=A.getResponseHeader("Last-Modified"))&&(B3.lastModified[R]=g),(g=A.getResponseHeader("etag"))&&(B3.etag[R]=g)),204===d||"HEAD"===E.type?b="nocontent":304===d?b="notmodified":(b=j.state,Y=j.data,c=!(f=j.error))):(f=b,!d&&b||(b="error",d<0&&(d=0))),A.status=d,A.statusText=(h||b)+"",c?C.resolveWith(B,[Y,b,A]):C.rejectWith(B,[A,b,f]),A.statusCode(D),D=void 0,Q&&M.trigger(c?"ajaxSuccess":"ajaxError",[A,E,c?Y:f]),W.fireWith(B,[A,b]),Q&&(M.trigger("ajaxComplete",[A,E]),--B3.active||B3.event.trigger("ajaxStop")))
}return A
},getJSON:function(B,A,C){return B3.get(B,A,C,"json")
},getScript:function(B,A){return B3.get(B,void 0,A,"script")
}}),B3.each(["get","post"],function(B,A){B3[A]=function(E,C,F,D){return BZ(C)&&(D=D||F,F=C,C=void 0),B3.ajax(B3.extend({url:E,type:A,dataType:D,data:C,success:F},B3.isPlainObject(E)&&E))
}
}),B3.ajaxPrefilter(function(B){var A;
for(A in B.headers){"content-type"===A.toLowerCase()&&(B.contentType=B.headers[A]||"")
}}),B3._evalUrl=function(B,A,C){return B3.ajax({url:B,type:"GET",dataType:"script",cache:!0,async:!1,global:!1,converters:{"text script":function(){}},dataFilter:function(D){B3.globalEval(D,A,C)
}})
},B3.fn.extend({wrapAll:function(B){var A;
return this[0]&&(BZ(B)&&(B=B.call(this[0])),A=B3(B,this[0].ownerDocument).eq(0).clone(!0),this[0].parentNode&&A.insertBefore(this[0]),A.map(function(){var C=this;
while(C.firstElementChild){C=C.firstElementChild
}return C
}).append(this)),this
},wrapInner:function(A){return BZ(A)?this.each(function(B){B3(this).wrapInner(A.call(this,B))
}):this.each(function(){var C=B3(this),B=C.contents();
B.length?B.wrapAll(A):C.append(A)
})
},wrap:function(A){var B=BZ(A);
return this.each(function(C){B3(this).wrapAll(B?A.call(this,C):A)
})
},unwrap:function(A){return this.parent(A).not("body").each(function(){B3(this).replaceWith(this.childNodes)
}),this
}}),B3.expr.pseudos.hidden=function(A){return !B3.expr.pseudos.visible(A)
},B3.expr.pseudos.visible=function(A){return !!(A.offsetWidth||A.offsetHeight||A.getClientRects().length)
},B3.ajaxSettings.xhr=function(){try{return new CP.XMLHttpRequest
}catch(A){}};
var AA={0:200,1223:204},CM=B3.ajaxSettings.xhr();
BK.cors=!!CM&&"withCredentials" in CM,BK.ajax=CM=!!CM,B3.ajaxTransport(function(B){var C,A;
if(BK.cors||CM&&!B.crossDomain){return{send:function(F,D){var G,E=B.xhr();
if(E.open(B.type,B.url,B.async,B.username,B.password),B.xhrFields){for(G in B.xhrFields){E[G]=B.xhrFields[G]
}}for(G in B.mimeType&&E.overrideMimeType&&E.overrideMimeType(B.mimeType),B.crossDomain||F["X-Requested-With"]||(F["X-Requested-With"]="XMLHttpRequest"),F){E.setRequestHeader(G,F[G])
}C=function(H){return function(){C&&(C=A=E.onload=E.onerror=E.onabort=E.ontimeout=E.onreadystatechange=null,"abort"===H?E.abort():"error"===H?"number"!=typeof E.status?D(0,"error"):D(E.status,E.statusText):D(AA[E.status]||E.status,E.statusText,"text"!==(E.responseType||"text")||"string"!=typeof E.responseText?{binary:E.response}:{text:E.responseText},E.getAllResponseHeaders()))
}
},E.onload=C(),A=E.onerror=E.ontimeout=C("error"),void 0!==E.onabort?E.onabort=A:E.onreadystatechange=function(){4===E.readyState&&CP.setTimeout(function(){C&&A()
})
},C=C("abort");
try{E.send(B.hasContent&&B.data||null)
}catch(F){if(C){throw F
}}},abort:function(){C&&C()
}}
}}),B3.ajaxPrefilter(function(A){A.crossDomain&&(A.contents.script=!1)
}),B3.ajaxSetup({accepts:{script:"text/javascript, application/javascript, application/ecmascript, application/x-ecmascript"},contents:{script:/\b(?:java|ecma)script\b/},converters:{"text script":function(A){return B3.globalEval(A),A
}}}),B3.ajaxPrefilter("script",function(A){void 0===A.cache&&(A.cache=!1),A.crossDomain&&(A.type="GET")
}),B3.ajaxTransport("script",function(C){var B,A;
if(C.crossDomain||C.scriptAttrs){return{send:function(E,D){B=B3("<script>").attr(C.scriptAttrs||{}).prop({charset:C.scriptCharset,src:C.url}).on("load error",A=function(F){B.remove(),A=null,F&&D("error"===F.type?404:200,F.type)
}),CL.head.appendChild(B[0])
},abort:function(){A&&A()
}}
}});
var CJ,A9=[],Bj=/(=)\?(?=&|$)|\?\?/;
B3.ajaxSetup({jsonp:"callback",jsonpCallback:function(){var A=A9.pop()||B3.expando+"_"+Ac.guid++;
return this[A]=!0,A
}}),B3.ajaxPrefilter("json jsonp",function(E,C,G){var D,B,F,A=!1!==E.jsonp&&(Bj.test(E.url)?"url":"string"==typeof E.data&&0===(E.contentType||"").indexOf("application/x-www-form-urlencoded")&&Bj.test(E.data)&&"data");
if(A||"jsonp"===E.dataTypes[0]){return D=E.jsonpCallback=BZ(E.jsonpCallback)?E.jsonpCallback():E.jsonpCallback,A?E[A]=E[A].replace(Bj,"$1"+D):!1!==E.jsonp&&(E.url+=(AM.test(E.url)?"&":"?")+E.jsonp+"="+D),E.converters["script json"]=function(){return F||B3.error(D+" was not called"),F[0]
},E.dataTypes[0]="json",B=CP[D],CP[D]=function(){F=arguments
},G.always(function(){void 0===B?B3(CP).removeProp(D):CP[D]=B,E[D]&&(E.jsonpCallback=C.jsonpCallback,A9.push(D)),F&&BZ(B)&&B(F[0]),F=B=void 0
}),"script"
}}),BK.createHTMLDocument=((CJ=CL.implementation.createHTMLDocument("").body).innerHTML="<form></form><form></form>",2===CJ.childNodes.length),B3.parseHTML=function(D,B,F){return"string"!=typeof D?[]:("boolean"==typeof B&&(F=B,B=!1),B||(BK.createHTMLDocument?((C=(B=CL.implementation.createHTMLDocument("")).createElement("base")).href=CL.location.href,B.head.appendChild(C)):B=CL),E=!F&&[],(A=CA.exec(D))?[B.createElement(A[1])]:(A=AC([D],B,E),E&&E.length&&B3(E).remove(),B3.merge([],A.childNodes)));
var C,A,E
},B3.fn.load=function(F,C,H){var E,B,G,A=this,D=F.indexOf(" ");
return -1<D&&(E=AP(F.slice(D)),F=F.slice(0,D)),BZ(C)?(H=C,C=void 0):C&&"object"==typeof C&&(B="POST"),0<A.length&&B3.ajax({url:F,type:B||"GET",dataType:"html",data:C}).done(function(I){G=arguments,A.html(E?B3("<div>").append(B3.parseHTML(I)).find(E):I)
}).always(H&&function(J,I){A.each(function(){H.apply(this,G||[J.responseText,I,J])
})
}),this
},B3.expr.pseudos.animated=function(A){return B3.grep(B3.timers,function(B){return A===B.elem
}).length
},B3.offset={setOffset:function(G,K,C){var A,E,B,I,L,J,D=B3.css(G,"position"),H=B3(G),F={};
"static"===D&&(G.style.position="relative"),L=H.offset(),B=B3.css(G,"top"),J=B3.css(G,"left"),("absolute"===D||"fixed"===D)&&-1<(B+J).indexOf("auto")?(I=(A=H.position()).top,E=A.left):(I=parseFloat(B)||0,E=parseFloat(J)||0),BZ(K)&&(K=K.call(G,C,B3.extend({},L))),null!=K.top&&(F.top=K.top-L.top+I),null!=K.left&&(F.left=K.left-L.left+E),"using" in K?K.using.call(G,F):("number"==typeof F.top&&(F.top+="px"),"number"==typeof F.left&&(F.left+="px"),H.css(F))
}},B3.fn.extend({offset:function(A){if(arguments.length){return void 0===A?this:this.each(function(E){B3.offset.setOffset(this,A,E)
})
}var C,D,B=this[0];
return B?B.getClientRects().length?(C=B.getBoundingClientRect(),D=B.ownerDocument.defaultView,{top:C.top+D.pageYOffset,left:C.left+D.pageXOffset}):{top:0,left:0}:void 0
},position:function(){if(this[0]){var D,B,E,C=this[0],A={top:0,left:0};
if("fixed"===B3.css(C,"position")){B=C.getBoundingClientRect()
}else{B=this.offset(),E=C.ownerDocument,D=C.offsetParent||E.documentElement;
while(D&&(D===E.body||D===E.documentElement)&&"static"===B3.css(D,"position")){D=D.parentNode
}D&&D!==C&&1===D.nodeType&&((A=B3(D).offset()).top+=B3.css(D,"borderTopWidth",!0),A.left+=B3.css(D,"borderLeftWidth",!0))
}return{top:B.top-A.top-B3.css(C,"marginTop",!0),left:B.left-A.left-B3.css(C,"marginLeft",!0)}
}},offsetParent:function(){return this.map(function(){var A=this.offsetParent;
while(A&&"static"===B3.css(A,"position")){A=A.offsetParent
}return A||A3
})
}}),B3.each({scrollLeft:"pageXOffset",scrollTop:"pageYOffset"},function(B,A){var C="pageYOffset"===A;
B3.fn[B]=function(D){return Cc(this,function(G,E,H){var F;
if(BM(G)?F=G:9===G.nodeType&&(F=G.defaultView),void 0===H){return F?F[A]:G[E]
}F?F.scrollTo(C?F.pageXOffset:H,C?H:F.pageYOffset):G[E]=H
},B,D,arguments.length)
}
}),B3.each(["top","left"],function(A,B){B3.cssHooks[B]=CO(BK.pixelPosition,function(D,C){if(C){return C=Ap(D,B),A2.test(C)?B3(D).position()[B]+"px":C
}})
}),B3.each({Height:"height",Width:"width"},function(A,B){B3.each({padding:"inner"+A,content:B,"":"outer"+A},function(C,D){B3.fn[D]=function(G,F){var H=arguments.length&&(C||"boolean"!=typeof G),E=C||(!0===G||!0===F?"margin":"border");
return Cc(this,function(K,I,L){var J;
return BM(K)?0===D.indexOf("outer")?K["inner"+A]:K.document.documentElement["client"+A]:9===K.nodeType?(J=K.documentElement,Math.max(K.body["scroll"+A],J["scroll"+A],K.body["offset"+A],J["offset"+A],J["client"+A])):void 0===L?B3.css(K,I,E):B3.style(K,I,L,E)
},B,H?G:void 0,H)
}
})
}),B3.each(["ajaxStart","ajaxStop","ajaxComplete","ajaxError","ajaxSuccess","ajaxSend"],function(B,A){B3.fn[A]=function(C){return this.on(A,C)
}
}),B3.fn.extend({bind:function(B,A,C){return this.on(B,null,A,C)
},unbind:function(B,A){return this.off(B,null,A)
},delegate:function(C,A,D,B){return this.on(A,C,D,B)
},undelegate:function(B,A,C){return 1===arguments.length?this.off(B,"**"):this.off(A,B||"**",C)
},hover:function(B,A){return this.mouseenter(B).mouseleave(A||B)
}}),B3.each("blur focus focusin focusout resize scroll click dblclick mousedown mouseup mousemove mouseover mouseout mouseenter mouseleave change select submit keydown keypress keyup contextmenu".split(" "),function(A,B){B3.fn[B]=function(D,C){return 0<arguments.length?this.on(B,null,D,C):this.trigger(B)
}
});
var Ci=/^[\s\uFEFF\xA0]+|[\s\uFEFF\xA0]+$/g;
B3.proxy=function(D,B){var E,C,A;
if("string"==typeof B&&(E=D[B],B=D,D=E),BZ(D)){return C=BS.call(arguments,2),(A=function(){return D.apply(B||this,C.concat(BS.call(arguments)))
}).guid=D.guid=D.guid||B3.guid++,A
}},B3.holdReady=function(A){A?B3.readyWait++:B3.ready(!0)
},B3.isArray=Array.isArray,B3.parseJSON=JSON.parse,B3.nodeName=CS,B3.isFunction=BZ,B3.isWindow=BM,B3.camelCase=Bw,B3.type=BN,B3.now=Date.now,B3.isNumeric=function(B){var A=B3.type(B);
return("number"===A||"string"===A)&&!isNaN(B-parseFloat(B))
},B3.trim=function(A){return null==A?"":(A+"").replace(Ci,"")
},"function"==typeof define&&define.amd&&define("jquery",[],function(){return B3
});
var A1=CP.jQuery,AO=CP.$;
return B3.noConflict=function(A){return CP.$===B3&&(CP.$=AO),A&&CP.jQuery===B3&&(CP.jQuery=A1),B3
},"undefined"==typeof Bk&&(CP.jQuery=CP.$=B3),B3
});
if(window["$"]){var old$=window["$"];
window["$"]=function(A,C,B){if(typeof (A)==="string"){A=A.replace(/\$/g,"\\$")
}return old$(A,C,B)
};
old$.extend(window["$"],old$)
}if(!this.ariba){this.ariba={awCurrWindow:null}
}ariba.Debug={log:function(){},logEvent:function(){}};
ariba.Util=function(){var AWAlertException=false;
var Util={isAW5:function(){var isAW5=!!document.getElementById("isAW5");
Util.isAW5=function(){return isAW5
};
return isAW5
},isBrowserFeatureDetectionEnabled:function(){var detectBrowserFeatures=!!document.getElementById("isBrowserFeatureDetectionEnabled");
Util.isBrowserFeatureDetectionEnabled=function(){return detectBrowserFeatures
};
return detectBrowserFeatures
},bind:function(f,oCtx){return $.proxy(f,oCtx)
},extend:function(oDest,oSrc){return $.extend(oDest,oSrc)
},_arrayAdd:function(aArray1,aArray2,fnPredicate,fnChildren){var aNewArray=[].concat(aArray1);
if(!fnPredicate){fnPredicate=function(){return true
}
}if(!fnChildren){fnChildren=function(){return null
}
}$.each(aArray2,function(i,o){var oChildren;
if(fnPredicate(o)){aNewArray.push(o)
}if((oChildren=fnChildren(o))){aNewArray=Util._arrayAdd(aNewArray,oChildren,fnPredicate,fnChildren)
}});
return aNewArray
},concatArr:function(a,b){if(!(a&&a.length)){a=[]
}if(!(b&&b.length)){b=[]
}return a.concat(b)
},toArray:function(o){return $.makeArray(o)
},arrayRemoveMatching:function(arr,target,getter){if(!arr){return 
}for(var i=0,c=arr.length;
i<c;
i++){var e=(getter)?getter(arr[i]):arr[i];
if(e==target){arr.splice(i,1);
break
}}},isArray:function(o){return $.isArray(o)
},itemOrArrAdd:function(orig,obj){if(!orig){return obj
}else{if(this.isArray(orig)){orig.push(obj);
return orig
}else{var itemArray=[orig];
itemArray.push(obj);
return itemArray
}}},arrayIndexOf:function(a,o){$.inArray(o,a)
},arrayAddIfNotExists:function(a,o){if($.inArray(o,a)<0){a.push(o)
}},arrayMakeUnique:function(aOriginal){var oFound={},aCopy=[],i=aOriginal.length;
while(i-->=0){if(!oFound[aOriginal[i]]){oFound[aOriginal[i]]=true;
aCopy.push(aOriginal[i])
}}return aCopy
},isUndefined:function(o){return o===undefined
},isNullOrUndefined:function(o){return o===null||Util.isUndefined(o)
},isNullOrBlank:function(o){return Util.isNullOrUndefined(o)||o===""
},stringEndsWith:function(sourceString,searchString){return(sourceString.lastIndexOf(searchString)==(sourceString.length-searchString.length))
},takeValue:function(obj,keypath,value){function set(obj,keyArr,value){if(keyArr.length==1){obj[keyArr[0]]=value
}else{set(obj[keyArr.shift()],keyArr,value)
}}set(obj,keypath.split("."),value)
},takeValues:function(obj,keys,values){for(var i=0;
i<values.length;
i++){this.takeValue(obj,keys[i],values[i])
}},printStack:function(){var sMsg="";
var oFunc;
if(arguments.length!=0){oFunc=arguments[0]
}else{oFunc=this.printStack.caller
}while(oFunc!=null){var sFunc=oFunc.toString();
sMsg+="<li>"+sFunc.substring(0,sFunc.search(/\n/))+"<br/>";
oFunc=oFunc.caller
}return sMsg
},getExceptionMsg:function(e,sMsg){if(AWAlertException){alert(sMsg)
}var str="****************************<br/>"+sMsg+"<br/>Exception: "+e.message+"<br/>"+this.printStack(getExceptionMsg.caller)+"<br/>****************************<br/>";
return str
},htmlEscapeValue:function(sValue){if(sValue==null){return 
}if(sValue.search(/</)!=-1){sValue=sValue.replace(/&/g,"&amp;");
sValue=sValue.replace(/</g,"&lt;");
sValue=sValue.replace(/>/g,"&gt;");
sValue="<pre>"+sValue+"</pre>"
}else{if(sValue.search(/function/)!=-1){sValue="<pre>"+sValue+"</pre>"
}}return sValue
},uriEncode:function(s){return encodeURIComponent(s).replace("+","%2B").replace("/","%2F")
},strTrim:function(s){return $.trim(s)
},max:function(iNumber1,iNumber2){return Math.max(iNumber1,iNumber2)
},toHHMMSS:function(sec_num){if(!sec_num){return"00:00"
}sec_num=parseInt(sec_num,10);
var hours=Math.floor(sec_num/3600),minutes=Math.floor((sec_num-(hours*3600))/60),seconds=sec_num-(hours*3600)-(minutes*60);
if(hours<10){hours="0"+hours
}if(minutes<10){minutes="0"+minutes
}if(seconds<10){seconds="0"+seconds
}return(hours==="00"?"":hours+":")+minutes+":"+seconds
},indexOf:function(a,o){$.inArray(o,a)
},indexOfCharInSet:function(targetString,startIndex,charSet){var length=targetString.length;
for(var index=startIndex;
index<length;
index++){if(charSet.indexOf(targetString.charAt(index))!=-1){return index
}}return -1
},indexOfCharNotInSet:function(targetString,startIndex,charSet){var length=targetString.length;
for(var index=startIndex;
index<length;
index++){if(charSet.indexOf(targetString.charAt(index))==-1){return index
}}return -1
},indexOfNotChar:function(targetString,startIndex,ch){var length=targetString.length;
for(var index=startIndex;
index<length;
index++){if(targetString.charAt(index)!=ch){return index
}}return -1
},parseInt:function(intString){if(intString&&typeof intString=="number"){return intString
}if(intString&&typeof intString=="string"&&intString.charAt(0)=="0"){var index=this.indexOfNotChar(intString,1,"0");
intString=intString.substring(index,intString.length)
}return parseInt(intString)
},incrementAttribute:function(object,attributeName){if(!object||!attributeName){return 
}var attributeValue=object.getAttribute(attributeName);
if(attributeValue){attributeValue=this.parseInt(attributeValue)+1
}else{attributeValue=1
}object.setAttribute(attributeName,attributeValue)
},getIntAttribute:function(object,attributeName){if(!object||!attributeName){return 0
}var attributeValue=object.getAttribute(attributeName);
if(attributeValue){return this.parseInt(attributeValue)
}return 0
},valueForBinding:function(target,key){var keyValue=target[key];
if(typeof keyValue=="function"){keyValue=eval("target."+key+"()")
}else{keyValue=target["_"+key]
}return keyValue
},setValueForBinding:function(target,key,value){var uppercaseKey=key.charAt(0).toUpperCase()+key.substr(1);
var setterKey="set"+uppercaseKey;
var keyValue=target[setterKey];
if(typeof keyValue=="function"){eval("target."+setterKey+"(value)")
}else{eval("target._"+key+" = value")
}},EOF:0};
if(!isAngularBootstrapUpgradeEnable){Function.prototype.bind=function(){var __method=this,a=Util.toArray(arguments),obj=a.shift();
return function(){return __method.apply(obj,Util.concatArr(a,Util.toArray(arguments)))
}
}
}return Util
}();
ariba.Dom=function(){var I=ariba.Util;
var T="MSIE 5.0";
var E="Netscape";
var N=1;
var L=[];
var B=navigator.appVersion;
var Y=(window.attachEvent&&!window.opera)?true:false;
var X=!!(navigator.userAgent.match(/Trident/)&&!navigator.userAgent.match(/MSIE/));
var O=B.indexOf("MSIE 10")!=-1;
var V=B.indexOf("MSIE 9")!=-1;
var W=B.indexOf("MSIE 8")!=-1;
var Z=B.indexOf("MSIE 7")!=-1;
var a=B.indexOf("MSIE 6")!=-1;
var K=O||X;
var U=V||K;
var J=W||U;
var S=Z||J;
var D=a||S;
var M=Y&&(document.all&&!document.addEventListener);
var Q=15;
var P=1;
var C=100;
var b;
var G="below";
var F="topIn";
var d="in";
var c="topOut";
var R="above";
var H=[G,F,d,c,R];
var A={IsIE:Y||X,IsIE11Up:X,IsIE10:O,IsIE9:V,IsIE8:W,IsIE7:I.isAW5()?S:Z,IsIE6Only:a,IsIE6:D,IsIEonMac:Y&&(navigator.platform!=="Win32")&&(navigator.platform!=="Win64"),IsNS6:!document.all&&document.getElementById,IsMoz:!document.all&&document.getElementById,IsFF:navigator.userAgent.indexOf("Firefox")!==-1,isChrome:navigator.appVersion.indexOf("Chrome")!==-1,isSafari:navigator.appVersion.indexOf("Safari")!==-1,isIPad:navigator.platform.indexOf("iPad")!==-1,isWindowsSystem:navigator.userAgent.indexOf("Win")!==-1,IsIE8AndOlder:M,AWEmptyDocScriptlet:a?"javascript:false":"javascript:void(0);",ApplicationType:"",AWOpenWindowErrorMsg:null,generateId:function(){return"aw_gen_"+P++
},prepareForAbsolute:function(f,e){if(!b){b=$("body").prepend('<div class="w-layer" id="js-layers"></div>').find(":first-child")[0]
}f.each(function(g,h){h=b.appendChild(h);
f[g]=h;
if(e!==false){$(h).css("z-index",++C)
}})
},getElementById:function(h){var f=null;
try{if(h&&h!=null&&h!=""){f=document.getElementById?document.getElementById(h):document.all[h]
}}catch(g){}return f
},getElementsBy:function(l,f,n,k){var e=[],m=l.getElementsByTagName(f),h=0,g=m.length;
for(;
h<g;
++h){if(n(m[h])){if(k){return m[h]
}else{e.push(m[h])
}}}return e
},getElementBy:function(f,e,g){return A.getElementsBy(f,e,g,true)||null
},getElementsByClassName:function(l,f,g){var e=[],m;
if(l.getElementsByClassName){m=l.getElementsByClassName(f);
if(g){for(var k=0,h=m.length;
k<h;
++k){if(g===m[k].tagName){e.push(m[k])
}}return e
}else{return m
}}else{return A.getElementsBy(l,g||"*",function(i){return A.hasClass(i,f)
})
}},isElementInView:function(e){var f=e.getBoundingClientRect();
return(f.top>=0&&f.left>=0&&f.bottom<=(window.innerHeight||document.documentElement.clientHeight)&&f.right<=(window.innerWidth||document.documentElement.clientWidth))
},getDocumentElementById:function(e,f){if(!e){return null
}return e.getElementById?e.getElementById(f):e.all[f]
},findParent:function(e,h,g){var f=g?e:e.parentNode;
while(f!=null&&f.nodeName!=h){f=f.parentNode
}return f
},findChild:function(e,k,h){var g=null;
if(!e){return e
}else{if(h&&(e.nodeName==k)){return e
}else{if(e.childNodes){var j=e.childNodes;
for(var f=0;
f<j.length&&g==null;
f++){g=this.findChild(j[f],k,true)
}}}}return g
},findParentUsingPredicate:function(e,h,g){var f=g?e:e.parentNode;
while(f!=null&&!h(f)){f=f.parentNode
}return f
},findChildUsingPredicate:function(e,k,h){var g=null;
if(!e){return e
}else{if(h&&k(e)){return e
}else{if(e.childNodes){var j=e.childNodes;
for(var f=0;
f<j.length&&g==null;
f++){g=this.findChildUsingPredicate(j[f],k,true)
}}}}return g
},find:function(f,e){return this.findChildrenUsingPredicate(f,function(g){return g.className&&g.className.indexOf(e)>=0
})
},findChildrenUsingPredicate:function(f,l,j){var e=[];
if(!f){return f
}else{if(j&&l(f)){return[f]
}else{if(f.childNodes){var k=f.childNodes;
for(var g=0;
g<k.length;
g++){var h=this.findChildrenUsingPredicate(k[g],l,true);
e=e.concat(h)
}}}}return e
},elementInDom:function(f){var g=this.documentElement();
while(f&&f!=g){f=f.parentNode
}return f==g
},appendToBody:function(e){if(document&&document.body){document.body.appendChild(e)
}else{alert("unable to find document / document.body")
}},_appendChildren:function(g,e){for(var f=0;
f<e.length;
f++){g.appendChild(e[f])
}},getInnerText:function(e){var f;
if(e){if(e.innerText){f=e.innerText
}else{if(e.textContent){f=e.textContent
}else{f=e.innerHTML.replace(/<[^>]+>/g,"");
f=f.replace(/&amp;/g,"&");
f=f.replace(/&lt;/g,"<");
f=f.replace(/&gt;/g,">")
}}}return f
},setInnerText:function(f,e){if(f){if(f.innerText||f.innerText==""){f.innerText=e
}else{f.innerHTML=e
}}},copyInnerText:function(f,e){if(f&&e){this.setInnerText(e,this.getInnerText(f))
}},isNetscape:function(){return(navigator.appName.indexOf(E)!=-1)
},forgetWindowMapping:function(e){delete L[e]
},openWindow:function(i,f,h){var g=null;
try{g=L[f];
if(g==null||g.closed){if(h){g=window.open(i,f,h)
}else{g=window.open(i,f)
}L[f]=g;
if(this.IsIE6||this.IsFF){function l(){g.focus()
}setTimeout(l)
}else{if(navigator.appVersion.indexOf(T)!=-1||navigator.appName.indexOf(E)!=-1){g.focus()
}}}else{if(navigator.appVersion.indexOf(T)!=-1||navigator.appName.indexOf(E)!=-1){g.focus();
g.location.href=i
}else{g.close();
if(h){g=window.open(i,f,h)
}else{g=window.open(i,f)
}}}}catch(j){function k(){alert(A.AWOpenWindowErrorMsg)
}setTimeout(k)
}return g
},formForName:function(e){return document.forms[e]
},addFormField:function(f,g,e){return this.addFormFieldWithId(f,g,g,e)
},addFormFieldWithId:function(h,e,i,f){if(document.getElementById){var g=h[e];
if(g==null){g=document.createElement("input");
g.type="hidden";
g.id=e;
g.name=i
}if(g.parentNode!=h){h.appendChild(g)
}g.value=f;
return g
}},removeFormField:function(e,g){var f=e[g];
if(f&&f.parentNode){f.parentNode.removeChild(f);
if(ariba.Dom.IsMoz){delete e[g]
}else{e[g]=null
}}},lookupFormId:function(f){var g=this.findParentUsingPredicate(f,function(i){return i.tagName=="FORM"||A.hasClass(i,"formProxy")
});
var h=null;
if(g){var e=g.getAttribute("_fn");
if(e!=null){g=this.formForName(e)
}h=g.id
}return h
},limitTextLength:function(j,g){if(g<1){return 
}var f=j.value;
if(this.IsMoz){f=f.replace(/([^\r])\n/g,"$1\r\n");
f=f.replace(/^\n/g,"\r\n")
}var k=f.length;
if(k>g){j.value=f.substring(0,g)
}else{var e=this.getElementById(j.id+"MLI");
if(!e){return 
}var h=e.clientWidth;
e.style.width="";
e.innerHTML=g-k;
var i=e.clientWidth;
e.style.width=Math.max(h,i)+"px"
}},addClass:function(f,e){if(f.nodeType==N){if(f.className!=""&&e&&e.charAt(e.length-1)!=" "){e=e+" "
}if(f.className&&f.className.indexOf(e)==-1){f.className=e+f.className
}else{if(!f.className){f.className=e
}}}},removeClass:function(i,h){var e=i.className;
if(!h||!e){return 
}var f=e.indexOf(h);
if(f!=-1){var g=f+h.length;
if(g<e.length&&e.charAt(g)==" "){g++
}i.className=e.substring(0,f)+e.substring(g,e.length)
}},hasClass:function(g,f){return g.className&&(g.className.match(new RegExp("(^|\\s)"+f+"(\\s|$)"))!=null)
},positionDialogBox:function(h){var e=this.positioningParent(h.parentNode);
var g=(e==this.documentElement())?this.documentClientHeight():e.clientHeight;
var f=(e==this.documentElement())?this.documentClientWidth():e.clientWidth;
h.style.left=f/2-h.offsetWidth/2+this.getScrollLeft(e)+"px";
h.style.top=g/2-h.offsetHeight/2+this.getScrollTop(e)+"px";
if(h.onresize){h.onresize.call(h)
}},getDocumentElement:function(){return document.documentElement
},documentClientHeight:function(){if(window.innerHeight){return window.innerHeight
}else{return document.documentElement.clientHeight
}},documentClientWidth:function(){if(window.innerWidth){return window.innerWidth
}else{return document.documentElement.clientWidth
}},setOpacity:function(f,e){var g=f.style;
if(Y&&I.isAW5()){g.filter="alpha(opacity="+e+")"
}else{g.opacity=(parseInt(e)/100)
}},absoluteTop:function(g){var f=g.offsetTop;
var e=g.parentNode;
var h=g.offsetParent;
while(e!=null&&h!=null&&e!=this.getPageScrollElement()){if(e==h){f+=e.offsetTop;
h=e.offsetParent
}f-=e.scrollTop;
e=e.parentNode
}return f
},clientHeight:function(f,g){var e=f.clientHeight;
if(!g){g=f
}e+=g.scrollTop;
return e
},visibleInScrollArea:function(l){var i=this.documentElement();
var k=this.getPageScrollElement();
var g=k.scrollTop;
var e=this.clientHeight(i,k);
var h=this.absoluteTop(l);
var m=h+l.clientHeight;
var f=(h>g)&&(e>h);
var j=(m>g)&&(e>m);
return f||j
},isElementInViewport:function(f){var e=this._viewportState(f);
return e!=R&&e!=G
},setViewportState:function(f){var e=this._viewportState(f);
this.setState(f,e,H)
},_viewportState:function(g){var h=g.getBoundingClientRect();
var e=this.getWindowSize();
var j=h.top;
var f=h.bottom;
var i=e[1];
if(j>i){return G
}else{if(j<=i&&f>i){return F
}else{if(j<0&&f<=i){return c
}else{if(f<0){return R
}}}}return d
},clientWidth:function(e,f){var g=e.clientWidth;
if(!f){f=e
}g+=f.scrollLeft;
return g
},correctForRightEdge:function(e,h){var g=this.clientWidth(document.documentElement,this.getPageScrollElement());
var f=g-h.offsetWidth;
if(e>f){if(I.isAW5()){e=f
}else{e=f-Q
}}return e
},correctForBottomEdge:function(g,h){var e=this.clientHeight(document.documentElement,this.getPageScrollElement());
var f=e-h.offsetHeight;
if(g>f){if(I.isAW5()){g=f
}else{g=f-Q
}}return g
},repositionDivToWindow:function(i){if(i.className.indexOf("noReposition")==-1){var h=this.absoluteTop(i);
var f=this.absoluteLeft(i);
var g=this.correctForBottomEdge(h,i);
var e=this.correctForRightEdge(f,i);
this.setAbsolutePosition(i,e,g)
}},absoluteLeft:function(h){var g=false;
var k=[];
var f=0;
if(this.IsIE){var m=$(h).parents();
var l;
if(m.size){l=m.size()
}else{l=m.length
}for(var j=0;
j<l;
++j){if($($(m)[j]).css("position")==="absolute"){g=true;
k[f]=j;
f++;
$($(m)[j]).css("position","static")
}}}var o=h.offsetLeft;
var n=h.parentNode;
var e=h.offsetParent;
if(this.IsIE&&g){var m=$(h).parents();
for(var j=0;
j<f;
++j){$($(m)[k[j]]).css("position","absolute")
}}while(n!=null&&e!=null&&n!=this.getPageScrollElement()){if(n==e){o+=n.offsetLeft;
e=n.offsetParent
}o-=n.scrollLeft;
n=n.parentNode
}return o
},minInsetWidth:function(h,g){var f=this.absoluteLeft(h);
var e=f+h.offsetWidth;
var j=this.absoluteLeft(g);
var i=j+g.offsetWidth;
return Math.min((j-f),(e-i))
},cssToJSName:function(k){if(k.indexOf("-")<0){return k
}var h=k.split("-");
var e=h[0];
for(var f=1,g=h.length;
f<g;
f++){var j=h[f];
e+=j.charAt(0).toUpperCase()+j.substring(1)
}return e
},effectiveStyle:function(f,i){if(!f.style){return 
}var e=this.cssToJSName(i);
var h=f.style[e];
if(!h){if(document.defaultView&&document.defaultView.getComputedStyle){var g=document.defaultView.getComputedStyle(f,null);
h=g?g.getPropertyValue(i):null
}else{if(f.currentStyle){h=f.currentStyle[e]
}}}return h=="auto"?null:h
},offsetParent:function(e){if(e.offsetParent){return e.offsetParent
}if(e==document.body){return e
}while((e=e.parentNode)&&e!=document.body){if(this.effectiveStyle(e,"position")!="static"){return e
}}return document.body
},positioningParent:function(e){while(e&&(e=e.parentNode)&&e!=document.documentElement){var f=this.effectiveStyle(e,"position");
if(f=="absolute"||f=="relative"||f=="fixed"){break
}}return e||document.documentElement
},contentParent:function(e){var f=this.positioningParent(e);
return f==document.documentElement?document.body:f
},containerParent:function(f){var e=this.findParentUsingPredicate(f,function(g){return A.hasClass(g,"panelContainer")
});
return e!=null?e:document.body
},isRightToLeft:function(){var e=$("html").attr("dir");
return e&&e.toLowerCase()==="rtl"
},rightToLeftHandler:function(f,g,h){var e=$(window).width()+$(window).scrollLeft()-(g+h);
f.style.right=e+"px";
f.style.left="auto"
},setAbsolutePosition:function(f,i,h,e){var g=this.offsetParent(f);
if(g){i-=this.absoluteLeft(g);
h-=this.absoluteTop(g);
if(g!=this.getPageScrollElement()){i+=g.scrollLeft;
h+=g.scrollTop
}}if(0>h){h=0
}f.style.top=h+"px";
if(e){e(f,i)
}else{f.style.left=i+"px"
}},relativeOffset:function(f){var h,g=0;
var e=false;
do{h+=f.offsetTop||0;
g+=f.offsetLeft||0;
f=f.offsetParent;
if(f){var i=this.effectiveStyle(f,"position");
e=(i=="absolute"||i=="relative")
}}while(f&&!e);
return[g,h]
},isVisible:function(e){var f=this.documentElement();
while(e!=f){if(e.style.display=="none"||$(e).hasClass("is-dnone")){return false
}e=e.parentNode
}return true
},containerOffsetSize:function(h){var g;
var f=h.offsetWidth,e=h.offsetHeight;
if(!f){g=h.style.display;
h.style.display="BLOCK";
f=h.offsetWidth;
e=h.offsetHeight;
h.style.display=g
}return[f,e]
},getWindowSize:function(){var f=0,e=0,g=0;
if(typeof (window.innerWidth)=="number"){f=window.innerWidth;
e=window.innerHeight
}else{if(document.documentElement&&(document.documentElement.clientWidth||document.documentElement.clientHeight)){f=document.documentElement.clientWidth;
e=document.documentElement.clientHeight;
g=document.documentElement.scrollHeight
}else{if(document.body&&(document.body.clientWidth||document.body.clientHeight)){f=document.body.clientWidth;
e=document.body.clientHeight;
g=document.body.scrollHeight
}}}return new Array(f,e,g)
},isWindowNarrow:function(){var e=this.getWindowSize();
return(e[0]<300)
},fadeInElement:function(e){this.fadeElement(e,"hidden","visible")
},fadeOutElement:function(e){this.fadeElement(e,"visible","hidden")
},fadeElement:function(g,f,i){try{if(g.filters){if(!g.filters.blendTrans){g.style.filter="blendTrans(duration=.2)"
}g.style.visibility=f;
if(g.filters.blendTrans){if(g.filters.blendTrans.status!=2){g.filters.blendTrans.apply();
g.style.visibility=i;
g.filters.blendTrans.play()
}}}}catch(h){g.style.visibility=i
}},setBodyClass:function(e){if(this.IsIE){e+=" IsIE";
if(!I.isAW5()){if(this.IsIE9){e+=" IsIE9"
}else{if(this.IsIE10){e+=" IsIE10"
}else{e+=" IsIE11"
}}}else{e+=this.IsIE7?" IsIE7":" IsIE6"
}}else{if(this.isSafari){e+=" IsSaf";
if(this.isIPad){e+=" IsIPad"
}if(this.isChrome){e+=" IsChr"
}}else{e+=" IsMoz"
}}this.addClass(document.body,e)
},removeBodyClass:function(e){this.removeClass(document.body,e)
},findRow:function(h,e){var j;
var g=h.childNodes;
for(var f=0;
f<g.length;
f++){if(g[f].id==e){j=g[f];
break
}}return j
},findRowIndex:function(f,j){var e=-1;
var h=j.rows;
for(var g=0;
g<h.length;
g++){if(h[g].id==f){e=g;
break
}}return e
},findElement:function(e,g){if(!e){return null
}for(var f=0;
f<e.length;
f++){if(e[f].id==g){return e[f]
}}return null
},getHashLocation:function(){var e=window.location.hash;
if(!e||e==""||e=="#"){return null
}else{if(e.charAt(0)=="#"){return e.substring(1)
}else{return e
}}},boolAttr:function(h,e,g){var f=h.getAttribute(e);
return(f)?(f=="true"):g
},relocateDiv:function(i,j){if(i.getAttribute("_reloc")=="1"){var g=i.id;
this.removeRelocatedCopy(g);
var e=this.findParentUsingPredicate(i,function(l){return l.className&&l.className.indexOf("relocdest")!=-1
},true);
if(e){var f=document.createElement("div");
f.id=g+"_MovedCopy";
if(j){var h=g+"_OrigLocation";
var k=document.createElement("div");
k.id=h;
i.parentNode.replaceChild(k,i)
}else{i.parentNode.removeChild(i)
}e.appendChild(f);
f.appendChild(i);
i.setAttribute("_reloc",0)
}}},revertRelocatedCopy:function(h){var e=this.getElementById(h+"_MovedCopy");
if(e){var g=this.getElementById(h+"_OrigLocation");
if(g){e.parentNode.removeChild(e);
var f=e.firstChild;
f.setAttribute("_reloc","1");
g.parentNode.replaceChild(f,g)
}}},removeRelocatedCopy:function(g){var f=g+"_MovedCopy";
var e=this.getElementById(f);
if(e){e.parentNode.removeChild(e)
}},elementValue:function(f){var g=this.getElementById(f);
return g?g.value:null
},elementIntValue:function(f){var g=this.getElementById(f);
return g?parseInt(g.value):0
},setElementValue:function(f,g){if(f){var h=this.getElementById(f);
if(h){h.value=g
}}},elmBottom:function(f){var e=f;
while(e=e.nextSibling){if(e.offsetTop){return e.offsetTop
}}return f.offsetTop+f.offsetHeight
},getRowCells:function(e){var f=e.children;
if(f==null){f=e.cells
}return f
},overlay:function(e){},unoverlay:function(e){},getActiveElementId:function(){var e=document.activeElement;
if(e){return e.id
}return null
},getScrollTop:function(e){return e.scrollTop
},getScrollLeft:function(e){return e.scrollLeft
},getPageScrollElement:function(){return document.documentElement
},checkWindowScrollbar:function(g,e){if(!I.isAW5()){return false
}if(g){var f=document.documentElement;
e=(f.scrollHeight>f.clientHeight)
}if(e&&document.documentElement.style.overflowY!="scroll"){$(document.documentElement).addClass("yScroll").removeClass("is-of-hidden");
return true
}if(!e&&document.documentElement.style.overflowY!="hidden"){$(document.documentElement).addClass("leg-p-r-0").addClass("w-body");
$(document.documentElement).addClass("is-of-hidden").removeClass("yScroll");
return true
}return false
},setState:function(q,l,h){if(!q){return 
}var r=q.className;
if(!r){return 
}if(!h){h=[l]
}var n,m,g,s,f,p,e;
var k=[];
var o=r.split(" ");
for(n=0;
n<o.length;
n++){e=false;
f=o[n];
for(m=0;
m<h.length;
m++){g=h[m];
if(g==l){e=true
}p=this._isStateClass(f,g);
if(p){break
}}if(!p){k.push(f);
if(e){s=f+"-"+l;
k.push(s)
}}}q.className=k.join(" ")
},unsetState:function(m,f){if(!m){return 
}var n=m.className;
if(!n){return 
}var k,h,o,e;
var g=[];
var l=n.split(" ");
for(k=0;
k<l.length;
k++){e=l[k];
if(!this._isStateClass(e,f)){g.push(e)
}}m.className=g.join(" ")
},_isStateClass:function(f,e){return f.indexOf("-"+e)>=0
},createElement:function(f){var e=document.createElement("div");
e.innerHTML=f;
return e.firstChild
},EOF:0};
if(A.isSafari){I.extend(A,function(){return{getScrollTop:function(e){var f=e.scrollTop;
if(e==document.documentElement){f=this.getPageScrollElement().scrollTop
}return f
},getScrollLeft:function(e){var f=e.scrollLeft;
if(e==document.documentElement){f=this.getPageScrollElement().scrollLeft
}return f
},getPageScrollElement:function(){if(document.scrollingElement){return document.scrollingElement
}return A.isChrome?document.documentElement:document.body
},EOF:0}
}())
}if(A.IsIE){I.extend(A,function(){var e;
var f=function(){ariba.Dom.overlay(this)
};
return{setPageScroll:function(h,g){this.setPageScrollLeft(h);
this.setPageScrollTop(g)
},setPageScrollTop:function(g){this.documentElement().scrollTop=g
},getPageScrollTop:function(){return this.documentElement().scrollTop
},setPageScrollLeft:function(g){this.documentElement().scrollLeft=g
},getPageScrollLeft:function(){return this.documentElement().scrollLeft
},documentElement:function(){return ariba.Dom.IsIE6?document.documentElement:document.body
},getChildren:function(g){if(g){return g.children
}else{return null
}},getParentElement:function(g){return g.parentElement
},styleSheetRules:function(g){return g.rules
},getOuterHTML:function(g){return g.outerHTML
},setOuterHTML:function(g,h){g.outerHTML=h
},registerOverlayIframe:function(g){if(!e){e=new Object()
}e[g.id]=g
},deregisterOverlayIframe:function(g){if(e&&e[g.id]){e[g.id]=null
}},updateOverlayIframes:function(){if(this.IsIE6Only&&e){var k=e;
e=null;
for(var h in k){var l=k[h];
if(l){var g=true;
var j=this.getElementById(l.divObjectId);
if(this.elementInDom(j)&&this.effectiveStyle(j,"display")!="none"&&j.overlayIframe==l){g=false
}if(g){l.style.display="none"
}else{if(j.awOnOverlayUpdate){j.awOnOverlayUpdate(j,l)
}}}}}},overlay:function(k,j){var i;
var g;
var l;
if(this.IsIE6Only&&k){if(k.style.display=="none"||!k.currentStyle){return 
}if(k.currentStyle.zIndex==0){k.style.zIndex=100
}l=k.id+"IFrame";
i=k.overlayIframe;
if(!i){i=this.getElementById(l)
}if(!i){l=k.id+"IFrame";
g=document.createElement("span");
var h=this.containerParent(k);
h.appendChild(g);
g.innerHTML="<iframe src='"+this.AWEmptyDocScriptlet+"' id='"+l+"' style='position:absolute;top:0px;left:0px;display:none;filter:alpha(opacity=000);background-color:#FFFFFF'></iframe>";
i=this.getElementById(l)
}k.overlayIframe=i;
if(typeof (j)=="undefined"||j){i.divObjectId=k.id;
this.registerOverlayIframe(i)
}i.style.width=k.offsetWidth;
i.style.height=k.offsetHeight;
if(k.style.top){i.style.top=k.style.top
}else{i.style.top=this.absoluteTop(k)
}if(k.style.left){i.style.left=k.style.left
}else{i.style.left=this.absoluteLeft(k)
}i.style.zIndex=k.currentStyle.zIndex-1;
i.style.display="block";
if(!k.onresize){k.onresize=f
}}},unoverlay:function(h){var g;
if(this.IsIE6Only&&h){g=h.overlayIframe;
if(h.overlayIframe){g.style.display="none";
this.deregisterOverlayIframe(g);
h.onresize=null
}}},EOF:0}
}())
}if(!A.IsIE){I.extend(A,function(){var e={IMG:true,BR:true,INPUT:true,META:true,LINK:true,PARAM:true,HR:true};
return{setPageScroll:function(g,f){window.scroll(g,f)
},setPageScrollTop:function(f){window.scroll(this.getPageScrollLeft(),f)
},getPageScrollTop:function(){return Math.round(window.pageYOffset)
},setPageScrollLeft:function(f){window.scroll(f,this.getPageScrollTop())
},getPageScrollLeft:function(){return window.pageXOffset
},documentElement:function(){return document.documentElement
},getChildren:function(f){return f.childNodes
},getParentElement:function(f){return f.parentNode
},styleSheetRules:function(f){return null
},getOuterHTML:function(h){var f=h.attributes;
var j="<"+h.tagName;
for(var g=0;
g<f.length;
g++){j+=" "+f[g].name+'="'+f[g].value+'"'
}if(e[this.tagName]){return j+">"
}return j+">"+h.innerHTML+"</"+h.tagName+">"
},setOuterHTML:function(f,h){var g=f.ownerDocument.createRange();
g.setStartBefore(f);
var i=g.createContextualFragment(h);
f.parentNode.replaceChild(i,f)
},EOF:0}
}())
}return A
}();
ariba.Event=function(){var Util=ariba.Util;
var Debug=ariba.Debug;
var Dom=ariba.Dom;
var AWDomCompleteCallbackList;
var AWDomCompleteCallbackListArgs;
var AWOnRefreshCallbacks;
var AWVBScriptOnLoad;
var _ScriptLockCount=0;
var _IdsByEvent={};
var _FE=false;
var EventsEnabled=true;
var AWDocHandler={};
var AWGMouseHandler={};
var AWPrintWindowName="AWPrintPage";
var AWMouseDown="AWMouseDown";
var AWMouseUp="AWMouseUp";
var _LastFunc=null;
var _FakeEvent=function(){this.stopPropagation=function(){};
this.preventDefault=function(){}
};
var _awEventsPending=null,_awEventsPhase2Pending=null;
var _awPendingLockCount=0;
var AWWindowResizeCallbackList;
var _awPrevWS,_awProcessedWS,_awWSId,_awWSTime;
var AWWindowFixedCallbackList;
var AWWindowScrollCallback=null;
var AWWindowOnScrollTimeout=null;
var AWOrigDocumentOnMouseDown=window.document.onmousedown;
var _docReadyLockCount=0;
var Timeouts={};
var docReadyOnce=false;
$(document).ready(function(){docReadyOnce=true
});
var Event={behaviors:{},registerBehaviors:function(map){Util.extend(this.behaviors,map)
},registerRefreshCallback:function(f){if(!AWOnRefreshCallbacks){AWOnRefreshCallbacks=new Array(f)
}else{AWOnRefreshCallbacks[AWOnRefreshCallbacks.length]=f
}},unregisterRefreshCallback:function(f){Util.arrayRemoveMatching(AWOnRefreshCallbacks,f)
},registerVBScriptRefreshCallback:function(name){if((Dom.IsIE&&Util.isAW5())||(Dom.IsIE&&!Util.isAW5()&&!Dom.IsIE11Up)){this.registerRefreshCallback(function(){Event.GlobalEvalVBScript(name)
})
}},registerVBScriptOnLoad:function(name){Debug.log("awDomRegisterVBScriptOnLoad -- registering: "+name);
AWVBScriptOnLoad=name
},refreshIncrementNesting:function(){_ScriptLockCount++
},docReadyIncrementNesting:function(){_docReadyLockCount++
},notifyRefreshComplete:function(){this.eventLock();
if(_ScriptLockCount>0){Debug.log("refreshComplete() -- deferred ("+_ScriptLockCount+")");
_ScriptLockCount--;
this.registerUpdateCompleteCallback(this.eventUnlock.bind(this));
return false
}Debug.log("refreshComplete() -- executing...");
var i;
if(AWDomCompleteCallbackList){for(i=0;
i<AWDomCompleteCallbackList.length;
i++){try{if(AWDomCompleteCallbackListArgs[i]){AWDomCompleteCallbackList[i].apply(this,AWDomCompleteCallbackListArgs[i])
}else{AWDomCompleteCallbackList[i]()
}}catch(e){var msg="refreshComplete: Exception evaluating: "+AWDomCompleteCallbackList[i].toString()+"\n\n: "+e;
Debug.log(msg);
if(ariba.Request.AWDebugEnabled){alert(msg)
}}if(_ScriptLockCount){Debug.log("refreshComplete() -- Script block ("+_ScriptLockCount+") while executing "+(i+1)+" of "+AWDomCompleteCallbackList.length);
while(i-->=0){AWDomCompleteCallbackList.shift()
}_ScriptLockCount--;
this.registerUpdateCompleteCallback(this.eventUnlock.bind(this));
return false
}}Debug.log("refreshComplete() -- done...");
AWDomCompleteCallbackList=null
}if(ariba.Request.clearCancelRequestDelayHandle){ariba.Request.clearCancelRequestDelayHandle()
}if(AWOnRefreshCallbacks){for(i=0;
i<AWOnRefreshCallbacks.length;
i++){AWOnRefreshCallbacks[i]()
}}if((AWVBScriptOnLoad&&Dom.IsIE&&Util.isAW5())||(AWVBScriptOnLoad&&Dom.IsIE&&!Util.isAW5()&&!Dom.IsIE11Up)){try{this.GlobalEvalVBScript(AWVBScriptOnLoad)
}catch(e){alert("Exception in VBScript OnLoad Callback: "+e.message+AWVBScriptOnLoad)
}}this.eventUnlock();
return this.notifyDocReady()
},notifyDocReady:function(){if(_docReadyLockCount>0){Debug.log("waitForDocReady() -- deferred ("+_docReadyLockCount+")");
_docReadyLockCount--;
return false
}Debug.log("waitForDocReady() -- executing...");
this.invokeRegisteredHandlers("onDocReady");
Debug.log("waitForDocReady() -- done...");
return true
},evalJSSpan:function(id){var elm=Dom.getElementById(id);
if(elm){var script=Dom.getInnerText(elm);
eval(script)
}},registerHandler:function(id,eventNames,func){var list=eventNames.split(/\s+/);
for(var i=0;
i<list.length;
i++){var eventName=list[i];
Debug.log("Registering handler for: "+eventName+" -- "+id);
var map=_IdsByEvent[eventName];
if(!map){map={};
_IdsByEvent[eventName]=map
}map[id]=func||id
}},invokeRegisteredHandlers:function(eventName){var map=_IdsByEvent[eventName];
if(map){for(var id in map){var func=map[id];
try{if(typeof (func)=="function"){func.call(this)
}else{this.evalJSSpan(id)
}}catch(exp){try{if(ariba.Request.AWDebugEnabled){var event=document.createEvent("UIEvents");
event.initUIEvent(eventName,true,true,window,1);
window.dispatchEvent(event)
}}catch(exp2){}}}}},registerUpdateCompleteCallback:function(method,args){if(!AWDomCompleteCallbackList){AWDomCompleteCallbackList=[];
AWDomCompleteCallbackListArgs=[]
}AWDomCompleteCallbackList[AWDomCompleteCallbackList.length]=method;
AWDomCompleteCallbackListArgs[AWDomCompleteCallbackListArgs.length]=args
},addEvent:function(node,event,handler){if(node.addEventListener){node.addEventListener(event.substring(2),handler,false)
}else{if(node.attachEvent){node.attachEvent(event,handler)
}}},removeEvent:function(node,event,handler){if(node.removeEventListener){node.removeEventListener(event.substring(2),handler,false)
}else{if(node.detachEvent){node.detachEvent(event,handler)
}}},shouldBubble:function(evt){return !evt.awCancelBubble
},modallyDisabled:function(target){return false
},selectFirstText:function(){},enableEvents:function(){EventsEnabled=true
},disableEvents:function(){EventsEnabled=false
},updateDocHandler:function(eventType,docHandler){var origDocHandler=AWDocHandler[eventType];
AWDocHandler[eventType]=docHandler;
return origDocHandler
},getDocHandler:function(eventType){return AWDocHandler[eventType]
},registerGMouseHandler:function(eventType,mouseHandler){AWGMouseHandler[eventType]=mouseHandler
},gl_handler:function(e){if(_FE){return true
}if(document.readyState&&document.readyState!="complete"){if(!(docReadyOnce&&document.readyState=="interactive")){return true
}}if(!Dom.IsIE&&!e){return true
}if(!EventsEnabled){return false
}if(window.name==AWPrintWindowName){return true
}var evt=(e)?e:event;
var target=(evt.srcElement)?evt.srcElement:evt.target;
if(ariba.Request.AWDebugEnabled&&Debug.checkDebugClick(evt)){Event.cancelBubble(evt);
return true
}if(this.modallyDisabled(target)){if((evt.type=="activate"||evt.type=="focus"||evt.type=="mousedown"||evt.type=="click"||evt.type=="keydown")&&target!=window){this.selectFirstText()
}if(evt.type=="keydown"&&Event.keyCode(evt)==ariba.Input.KeyCodeEscape){var currentDialogLookup="div.w-dlg-panel-active div.w-dlg-dialog";
var targets=$(currentDialogLookup);
if(targets.length>0){var targetDialog=targets[targets.length-1];
if(targetDialog){target=targetDialog
}}}else{return true
}}_FE=true;
var ret=false;
try{if(this.handleMouseEvent(target,evt)){var gMouseHandler=AWGMouseHandler[evt.type];
if(gMouseHandler){gMouseHandler(evt)
}ret=this.fireBehaviors(target,evt,("on"+evt.type),("x"+evt.type))
}}catch(ex){ret=true
}finally{_FE=false
}return ret
},handleMouseEvent:function(target,evt){var shouldFireEvent=true;
if(target&&target.setAttribute){var evtType=evt.type;
if(evtType=="mousedown"){target.setAttribute(AWMouseDown,"true");
target.removeAttribute(AWMouseUp)
}else{if(evtType=="mouseup"){target.setAttribute(AWMouseUp,"true")
}else{if(evtType=="mouseout"){target.removeAttribute(AWMouseDown);
target.removeAttribute(AWMouseUp)
}else{if(evtType=="click"){shouldFireEvent=target.getAttribute(AWMouseDown)&&target.getAttribute(AWMouseUp);
target.removeAttribute(AWMouseDown);
target.removeAttribute(AWMouseUp)
}}}}}return shouldFireEvent&&!Event.isRightClick(evt)
},isRightClick:function(evt){return evt&&evt.which===3
},_elementInvoke:function(elm,evt,onName,xName){var ret=true;
var func;
var evtType=evt.type;
if(elm==window.document){var docHandler=AWDocHandler[evtType];
if(docHandler){return docHandler(evt)
}}var handler=elm[onName];
if(handler&&(handler.call!=null)){ret=handler.call(elm,evt)
}else{if(elm.tagName){handler=elm.getAttribute(xName);
if(handler){ret=this.handleInline(handler,evt,elm)
}else{if(func=this.bhHandler(elm,evt.type)){ret=func(elm,evt)
}else{if(evt.type=="click"){var sourceElm=this.eventSourceElement(evt);
if(elm.tagName=="LABEL"&&sourceElm.type!="checkbox"&&sourceElm.type!="radio"&&sourceElm.tagName!="SELECT"&&sourceElm.tagName!="A"){var forId=elm.htmlFor;
if(forId){var target=Dom.getElementById(forId),$el=$(target);
if(target&&!(target.disabled||$el.hasClass("w-btn-disabled"))){if(target.type=="radio"){target.checked=true;
target.focus();
ret=false;
Event.cancelBubble(evt)
}else{if(target.type=="checkbox"){target.checked=!target.checked;
target.focus();
ret=false;
Event.cancelBubble(evt)
}else{if(target.tagName=="SELECT"){target.focus();
ret=false;
Event.cancelBubble(evt)
}}}handler=target.getAttribute("xclick");
if(handler){this.handleInline(handler,evt,target);
ret=false;
Event.cancelBubble(evt)
}}}}}}}}}return ret
},fireBehaviors:function(elm,evt,onName,xName){if(!elm){return true
}var ret=this._elementInvoke(elm,evt,onName,xName);
return(this.shouldBubble(evt)&&(elm!=window.document))?(this.fireBehaviors(elm.parentNode,evt,onName,xName)&&ret):ret
},handleInline:function(handler,evt,elm){eval("_LastFunc = function(event) {"+handler+"}");
var ret=_LastFunc.call(elm,evt);
_LastFunc=null;
return ret
},elementInvoke:function(elm,evtName){var evt=new _FakeEvent();
evt.type=evtName;
evt.srcElement=evt.target=elm;
return this._elementInvoke(elm,evt,("on"+evtName),("x"+evtName))
},bhHandler:function(elm,type){var bhName=elm.getAttribute("bh");
if(bhName){var handler=this.behaviors[bhName];
if(handler){if(!handler.didInit){this.behaviorInit(handler)
}return handler[type]
}}return null
},hasHandler:function(elm,type){return elm["on"+type]||elm.getAttribute("x"+type)||this.bhHandler(elm,type)
},behaviorInit:function(handler){handler.didInit=true;
var proto=handler.prototype;
for(var p in proto){if(!handler[p]){handler[p]=proto[p]
}}if(Dom.IsIE){var f;
if(f=handler.focus){handler.activate=f
}if(f=handler.blur){handler.deactivate=f
}}},eh_stop:function(eml,evt){this.cancelBubble(evt);
return false
},eventEnqueue:function(target,event,isP2){if(!_awEventsPending){_awEventsPending=[]
}if(!_awEventsPhase2Pending){_awEventsPhase2Pending=[]
}var q=isP2?_awEventsPhase2Pending:_awEventsPending;
Util.arrayRemoveMatching(q,target,function(e){return e[0]
});
q.push([target,event]);
if(_awPendingLockCount==0){this.eventsFire()
}},eventLock:function(){_awPendingLockCount++
},eventUnlock:function(){_awPendingLockCount--;
if(_awPendingLockCount==0){this.eventsFire()
}},eventsFire:function(){_awPendingLockCount++;
var didFire;
do{didFire=false;
var q=(_awEventsPending&&_awEventsPending.length)?_awEventsPending:_awEventsPhase2Pending;
if(q&&q.length){didFire=true;
var entry=q[0];
entry[0](entry[1]);
this._arrayShift(q)
}}while(didFire);
_awPendingLockCount--;
if(_awPendingLockCount!=0){alert("Unbalanced lock count!")
}},_arrayShift:function(a){return(a&&a.length)?a.splice(0,1)[0]:null
},_onWindowResize:function(event,delay){var ws=Dom.getWindowSize();
if(!_awWSId&&(!_awPrevWS||(_awPrevWS[0]!=ws[0])||(_awPrevWS[1]!=ws[1]))){delay=delay||100;
if(!_awPrevWS){_awPrevWS=[-1,-1]
}Debug.log("_awOnWindowResize -- delay:"+delay+" -- _awPendingLockCount: "+_awPendingLockCount+" -- size: "+ws[0]+", "+ws[1]+"// "+_awPrevWS[0]+", "+_awPrevWS[1]);
_awPrevWS=ws;
if(_awPendingLockCount){this.eventEnqueue(this.onWindowResize.bind(this))
}else{if(_awWSId){clearTimeout(_awWSId)
}_awWSId=setTimeout(this.onWindowResize.bind(this),delay);
_awWSTime=(new Date()).getTime()+delay
}}},onWindowResize:function(force){var ws=Dom.getWindowSize();
var delay=_awWSTime-(new Date()).getTime();
Debug.log("Resize invoked: "+delay+(force?" -- FORCE":""));
if(force){_awPrevWS=ws
}if((_awPrevWS&&((_awPrevWS[0]!=ws[0])||(_awPrevWS[1]!=ws[1])))||(!force&&delay>0)){_awWSId=null;
Debug.log("Bailing out / rescheduling!");
this._onWindowResize(null,delay>0?delay:0);
return 
}Debug.log("Enqueuing resize: "+_awPendingLockCount+" / "+(AWDomCompleteCallbackList?AWDomCompleteCallbackList.length:0));
if(!_awProcessedWS||force){_awProcessedWS=[-1,-1]
}if((_awProcessedWS[0]!=ws[0])||(_awProcessedWS[1]!=ws[1])){_awProcessedWS=ws;
this.wSFlush()
}_awWSId=null
},forceOnWindowResize:function(){this.onWindowResize(true)
},wSFlush:function(){var ws=Dom.getWindowSize();
Debug.log("^^^^^ Resize!!! -- "+ws[0]+", "+ws[1]+" // "+_awPrevWS[0]+", "+_awPrevWS[1]+" ^^^^^");
if(AWWindowResizeCallbackList){for(var i=0;
i<AWWindowResizeCallbackList.length;
i++){this.eventEnqueue(AWWindowResizeCallbackList[i])
}}this.fireWindowFixedCallback()
},registerOnWindowFixed:function(callback){if(!AWWindowFixedCallbackList){AWWindowFixedCallbackList=[]
}for(var i=0;
i<AWWindowFixedCallbackList.length;
i++){if(AWWindowFixedCallbackList[i]==callback){return 
}}AWWindowFixedCallbackList.push(callback)
},fireWindowFixedCallback:function(){if(AWWindowFixedCallbackList){for(var i=0;
i<AWWindowFixedCallbackList.length;
i++){this.eventEnqueue(AWWindowFixedCallbackList[i],null,true)
}}},unregisterOnWindowFixed:function(method){Util.arrayRemoveMatching(AWWindowFixedCallbackList,method)
},_fireWindowCallback:function(){if(AWWindowFixedCallbackList){for(var i=0;
i<AWWindowFixedCallbackList.length;
i++){AWWindowFixedCallbackList[i]()
}}},registerOnWindowResize:function(method){if(!AWWindowResizeCallbackList){AWWindowResizeCallbackList=[]
}AWWindowResizeCallbackList[AWWindowResizeCallbackList.length]=method;
return method
},unregisterOnWindowResize:function(method){Util.arrayRemoveMatching(AWWindowResizeCallbackList,method)
},registerWindowOnScroll:function(callback){if(!AWWindowScrollCallback){AWWindowScrollCallback=[]
}for(var i=0;
i<AWWindowScrollCallback.length;
i++){if(AWWindowScrollCallback[i]==callback){return 
}}AWWindowScrollCallback.push(callback)
},windowOnScroll:function(){this.fireWindowOnScroll()
},windowOnMouseWheel:function(){this.fireWindowOnScroll()
},fireWindowOnScroll:function(){if(AWWindowOnScrollTimeout){clearTimeout(AWWindowOnScrollTimeout)
}AWWindowOnScrollTimeout=setTimeout(this._fireWindowOnScroll.bind(this),0)
},_fireWindowOnScroll:function(){if(AWWindowScrollCallback){for(var i=0;
i<AWWindowScrollCallback.length;
i++){AWWindowScrollCallback[i]()
}}},enableDocumentClick:function(func){AWOrigDocumentOnMouseDown=this.updateDocHandler("mousedown",func.bindEventHandler(this))
},disableDocumentClick:function(){if(AWOrigDocumentOnMouseDown){this.updateDocHandler("mousedown",AWOrigDocumentOnMouseDown);
AWOrigDocumentOnMouseDown=null
}},notifyParents:function(src,handlerName){var node=src;
while(node&&node.nodeType==1){try{var handler=node[handlerName];
if(handler){handler(node,src)
}node=node.parentNode
}catch(ex){}}},GlobalEvalVBScript:function(str){alert("GlobalEvalVBScript is IE only...")
},setTimeout:function(elm,func,delay){if(elm&&elm.id){this.clearTimeout(elm);
Timeouts[elm.id]=setTimeout(func,delay)
}},clearTimeout:function(elm){if(elm&&elm.id){var timeout=Timeouts[elm.id];
if(timeout){clearTimeout(timeout);
delete Timeouts[elm.id]
}}},addLoadEvent:function(func){var oldonload=window.onload;
if(typeof window.onload!="function"){window.onload=func
}else{window.onload=function(){if(oldonload){oldonload()
}func()
}
}},EOF:0};
if(Dom.isIPad){Util.extend(Event,function(){return{enableDocumentClick:function(func){},disableDocumentClick:function(){},EOF:0}
}())
}if((Dom.IsIE&&Util.isAW5())||(Dom.IsIE&&!Util.isAW5()&&!Dom.IsIE11Up)){Util.extend(Event,function(){return{keyCode:function(mevent){return mevent.keyCode
},cancelBubble:function(mevent,allowDefault){if(!Util.isNullOrUndefined(mevent)){mevent.cancelBubble=true;
mevent.awCancelBubble=true;
if(!allowDefault){Event.preventDefault(mevent)
}if(!Util.isAW5()){if(mevent.stopPropagation){mevent.stopPropagation()
}if(mevent.preventDefault){if(!allowDefault){mevent.preventDefault()
}}}}},eventSourceElement:function(mevent){return mevent.srcElement
},preventDefault:function(mevent){mevent.returnValue=false
},GlobalEvalVBScript:function(str){window.GlobalEvalVBScript(str)
},EOF:0}
}())
}if(!Dom.IsIE||(Dom.IsIE&&!Util.isAW5()&&Dom.IsIE11Up)){Util.extend(Event,function(){return{keyCode:function(mevent){return mevent.which
},cancelBubble:function(mevent,allowDefault){if(mevent){mevent.stopPropagation();
if(!allowDefault){mevent.preventDefault()
}mevent.awCancelBubble=true
}},eventSourceElement:function(mevent){return mevent.target
},preventDefault:function(mevent){mevent.preventDefault()
},EOF:0}
}())
}var bh=Event.eh_stop.bind(Event);
Util.extend(Event.behaviors,{StopPropagation:{click:bh,keydown:bh,keyup:bh,keypress:bh,mousedown:bh,mouseup:bh,mousein:bh,mouseover:bh,mousemove:bh,mouseout:bh,focus:bh,blur:bh}});
Function.prototype.bindEventHandler=function(){var __method=this,a=Util.toArray(arguments),obj=a.shift();
return function(evt){return(_FE)?__method.apply(obj,Util.concatArr([evt||window.event],a)):true
}
};
if(window==ariba.awCurrWindow){var bHandler=function(evt){return Event.gl_handler(evt)
};
var d=window.document;
if(Dom.IsIE){d.onmousein=bHandler;
d.onmouseover=bHandler;
d.onmouseout=bHandler;
d.onmousedown=bHandler;
d.onmouseup=bHandler;
d.onmousemove=bHandler;
d.onclick=bHandler;
d.onkeydown=bHandler;
d.onkeyup=bHandler;
d.onkeypress=bHandler;
d.ondeactivate=bHandler;
d.onfocusin=bHandler;
d.onfocusout=bHandler;
window.onfocus=function(e){Event.invokeRegisteredHandlers("onfocusin")
};
window.onblur=function(e){Event.invokeRegisteredHandlers("onblur")
}
}else{d.addEventListener("mousein",bHandler,false);
d.addEventListener("mouseover",bHandler,false);
d.addEventListener("mouseout",bHandler,false);
d.addEventListener("mousedown",bHandler,false);
d.addEventListener("mouseup",bHandler,false);
d.addEventListener("mousemove",bHandler,false);
d.addEventListener("click",bHandler,false);
d.addEventListener("keydown",bHandler,false);
d.addEventListener("keyup",bHandler,false);
d.addEventListener("keypress",bHandler,false);
d.addEventListener("blur",bHandler,false);
d.addEventListener("focus",bHandler,false);
window.addEventListener("focus",function(e){Event.invokeRegisteredHandlers("onfocusin")
},false);
window.addEventListener("blur",function(e){Event.invokeRegisteredHandlers("onblur")
},false)
}function _bindEv(func,obj){return function(evt){return func.apply(obj,[evt||window.event])
}
}window.onscroll=_bindEv(Event.windowOnScroll,Event);
window.onmousewheel=_bindEv(Event.windowOnMouseWheel,Event);
window.onresize=_bindEv(Event._onWindowResize,Event);
Event.registerRefreshCallback(function(){Event.invokeRegisteredHandlers("onupdate")
})
}return Event
}();
ariba.Input=function(){var G=ariba.Util;
var U=ariba.Event;
var P=ariba.Debug;
var B=ariba.Dom;
if(B.IsIE&&G.isAW5()){if(document.namespaces){document.createStyleSheet().addRule("v\\: *","behavior:url(#default#VML);");
!document.namespaces.rvml&&document.namespaces.add("v","urn:schemas-microsoft-com:vml")
}}var D;
var Q=null;
var S=null;
var E=null;
var A=null;
var I=false;
var F=false;
var T=false;
var R=null,K=null;
var M=null;
var O=null;
var C=null;
var H=false;
var L=null;
var N=0;
var J={AWWaitAlertMillis:2000,AWWaitMillis:20000,AWAutomationTestModeEnabled:false,KeyCodeBackspace:8,KeyCodeTab:9,KeyCodeEnter:13,KeyCodeShift:16,KeyCodeCapsLock:20,KeyCodeEscape:27,KeyCodeSpaceBar:32,KeyCodeArrowLeft:37,KeyCodeArrowUp:38,KeyCodeArrowRight:39,KeyCodeArrowDown:40,KeyCodeDelete:46,isCharChange:function(V){var X=V.keyCode;
if(X==this.KeyCodeBackspace||X==this.KeyCodeDelete){return true
}var W=null;
if(V.which==null){W=String.fromCharCode(V.keyCode)
}else{if(V.which!=0&&V.charCode!=0){W=String.fromCharCode(V.which)
}}return W!=null
},focus:function(W){try{W.focus()
}catch(V){}},keyDownEvtHandler:function(W){var V=U.eventSourceElement(W);
var X=J.modallyDisabled(V);
if(X){U.cancelBubble(W);
window.focus()
}return !X
},setShowWaitCursorDisabled:function(V){I=V
},showWaitCursor:function(){if(this.AWAutomationTestModeEnabled){window.status="Processing request ..."
}if(I){return 
}Q=document.getElementById("awwaitAlertDiv");
if(Q!=null){$(Q).addClass("is-dnone").removeClass("is-block");
$(Q).addClass("is-visible")
}var V=this.waitAlertSettings();
this.disableInput(true);
if(!F){clearTimeout(S);
clearTimeout(D);
S=setTimeout(this.showWaitAlert.bind(this),V);
D=setTimeout(this.hideWaitCursor.bind(this),V+this.AWWaitMillis)
}},waitAlertSettings:function(V){N=(new Date()).getTime()+500;
return this.AWWaitAlertMillis
},updateWaitMessage:function(W){W=(W?G.strTrim(W):"");
if(W.length<=0){return 
}if(!T){this.showWaitAlert()
}var V=B.getElementById("awwaitMessage");
if(V){V.innerHTML=W
}},hideWaitCursor:function(){if(I){return 
}clearTimeout(D);
clearTimeout(S);
this.enableInput();
this.hideWaitAlert()
},showWaitAlert:function(){if(I){return 
}if((new Date()).getTime()<N){return 
}clearTimeout(S);
if(!T&&!F){T=true;
if(Q!=null){$(Q).addClass("is-block").removeClass("is-dnone");
E=window.onscroll;
A=window.onresize;
window.onscroll=function(){B.positionDialogBox(Q);
U.invokeRegisteredHandlers("onWaitAlertResize")
};
window.onresize=window.onscroll;
B.positionDialogBox(Q);
B.overlay(Q)
}}},hideWaitAlert:function(){if(T){T=false;
window.onscroll=E;
window.onresize=A;
E=null;
A=null;
if(Q!=null){$(Q).addClass("is-dnone").removeClass("is-block");
var V=B.getElementById("awwaitMessage");
if(V){V.innerHTML=""
}B.unoverlay(Q)
}}},showWaitAlertInWindow:function(W){if(W!=null){W.document.writeln("<html><head><title>");
W.document.writeln(document.title);
W.document.writeln("</title></head><body>");
if(!B.IsIE){var V=B.getElementById("awwaitAlertDiv");
if(V!=null){var Y=V.cloneNode(true);
$(Q).addClass("is-visible");
$(Q).addClass("is-block");
Y.style.left="50%";
Y.style.top="50%";
Y.style.marginLeft="-"+V.offsetWidth/2+"px";
Y.style.marginTop="-"+V.offsetHeight/2+"px";
var X=document.createElement("span");
X.appendChild(Y);
W.document.writeln(X.innerHTML)
}}W.document.writeln("</body></html>");
W.document.close();
if(this.AWAutomationTestModeEnabled){W.status="Processing request ..."
}}},hideSelects:function(){},showSelects:function(){},createCoverDiv:function(Z,X){var V=null;
var W=null;
if(B.IsIE&&G.isAW5()){V=document.createElement('<v:rect stroked="False">');
var Y=document.createElement('<v:fill color="black">');
Y.opacity=X+"%";
V.appendChild(Y);
W=V.style
}else{V=document.createElement("div");
W=V.style;
W.backgroundColor="#000000";
B.setOpacity(V,X)
}W.position="absolute";
W.zIndex=Z;
return V
},coverDocument:function(Y,W){if(!G.isAW5()&&$("#coverDiv").is(":visible")){return 
}var V=this.createCoverDiv(Y,W);
this.updateCoverSize(V);
var X=document.body;
X.appendChild(V,document.body.firstChild);
V.style.display="";
this.registerCoverDiv(V);
this.hideSelects();
return V
},updateCoverSize:function(W){var X=W.style;
var Z=B.getDocumentElement();
var Y=G.max(Z.scrollWidth,Z.clientWidth);
var V=G.max(Z.scrollHeight,Z.clientHeight);
X.top="0px";
X.left="0px";
if(G.isAW5()){X.width=Y-1+"px";
X.height=V-1+"px"
}else{X.width="100%";
W.id="coverDiv";
X.height=$(document).height()-1+"px"
}},uncoverDocument:function(V){V=V||R;
this.showSelects();
if(V){this.unregisterCoverDiv(V);
document.body.removeChild(V)
}},registerCoverDiv:function(W){R=W;
if(M){P.log("reg cover div "+M);
K=M;
var V=B.getElementById(K);
if(V&&V.blur){V.blur()
}}},unregisterCoverDiv:function(V){if(K){P.log("unreg cover div "+K);
this.registerActiveElementId(K)
}R=K=null
},registerModalDiv:function(V){this.registerCoverDiv(V)
},unregisterModalDiv:function(V){this.unregisterCoverDiv(V)
},modallyDisabled:function(W){if(!B.elementInDom(R)){return false
}if(!R){return false
}var V=W;
while(V){if(V==R){return false
}V=V.parentNode
}return this.modallyDisabled_zindex(W)
},modallyDisabled_zindex:function(Y){if(!R){return false
}var V=Y;
while((V=B.positioningParent(V))&&V!=B.documentElement()){var X=B.effectiveStyle(V,"z-index");
if(X){var W=B.effectiveStyle(B.positioningParent(R),"z-index");
P.log("awModallyDisabled: "+W+", "+X);
if(!W){return false
}if(parseInt(X)>parseInt(W)){return false
}}}return true
},registerActiveElementId:function(V){M=V?V:B.getActiveElementId();
P.log("registerActiveElementId: "+M)
},setFocusRegion:function(V){C=V
},postLoadFocusOnActiveElement:function(){U.eventEnqueue(function(){U.eventEnqueue(J.focusOnActiveElement.bind(J))
},null,true)
},focusOnActiveElement:function(){if(C){var W=B.getElementById(C);
C=null;
if(W){var V=this.findFirstText(W);
if(V){M=V.id
}}}if(M){try{var X=B.getElementById(M);
if(B.elementInDom(X)&&!this.modallyDisabled(X)){P.log("Focusing on element id: "+M);
var Z=M;
function a(){try{if(!B.getActiveElementId()){P.log("Refocusing on element id: "+Z);
if(X.focus){X.focus();
X.focus();
if(X.select){X.select()
}}ariba.Menu.onLoadMenuHandleFocus(ariba.Menu.AWActiveMenu)
}}catch(b){}}setTimeout(a,1000);
if(X.focus){X.focus();
X.focus();
if(X.select){X.select()
}}}ariba.Menu.onLoadMenuHandleFocus(ariba.Menu.AWActiveMenu)
}catch(Y){P.log("Focusing exception: "+Y)
}finally{M=null
}}if(!B.getActiveElementId()&&H){H=false;
P.log("Focusing on first text: ");
this.selectFirstText();
ariba.Menu.onLoadMenuHandleFocus(ariba.Menu.AWActiveMenu)
}},selectFirstText:function(){var Z=null;
if(O){Z=B.getElementById(O);
O=null
}if(!Z){var V=document.forms;
var X=V.length;
for(var W=0;
W<X;
W++){Z=this.findFirstText(V[W]);
if(Z!=null){break
}}}if(Z){if(Z.value==null){Z.value=" "
}try{Z.focus();
Z.select()
}catch(Y){}}},findFirstText:function(Z){if(Z==null){return null
}var Y=B.boolAttr(Z,"_aa",false);
var V=B.findChildrenUsingPredicate(Z,function(b){return b.tagName=="INPUT"||b.tagName=="TEXTAREA"||(Y&&b.tagName=="A")
});
for(var X=0,a=V.length;
X<a;
X++){var W=V[X];
if((((W.type=="text"||W.type=="password")&&W.getAttribute("awautoselect")!="0")||W.nodeName=="TEXTAREA"||W.nodeName=="A")&&B.visibleInScrollArea(W)&&!W.getAttribute("disabled")&&!this.modallyDisabled(W)&&B.effectiveStyle(W,"display")!="none"){return W
}}return null
},setTextFocus:function(V){O=V
},allowSelectFirstText:function(){H=true
},initRegexNote:function(a,e){var k={dataAttrMatcherRegex:"rxmatcher",dataAttrPlaceholder:"placeholder",dataAttrReplacement:"replacement",invalidText:"Invalid input",replacementFunction:null,targetClass:"regexInputNote"},Y,d,b,V,h,g,Z,X=document.getElementById(a),W;
function j(){clearTimeout(V);
var l=X.value;
if(d){W.innerHTML=d(l)
}else{while(l.length<b){l+=g
}W.innerHTML=l.match(h)?l.replace(h,Z):Y.invalidText
}}function f(){j()
}function c(){clearTimeout(V);
V=setTimeout(function(){j()
},100)
}function i(){var l,m=X;
Y=ariba.Util.extend({},k);
Y=ariba.Util.extend(Y,e);
while(m.nextSibling){m=m.nextSibling;
if(m.className&&-1!==m.className.indexOf(Y.targetClass)){W=m;
break
}}l=X.getAttribute("data"+Y.dataAttrMatcherRegex);
b=parseInt(X.getAttribute("maxlength"),10);
g=""+X.getAttribute("data"+Y.dataAttrPlaceholder);
Z=X.getAttribute("data"+Y.dataAttrReplacement);
h=new RegExp(l);
d=Y.replacementFunction;
U.addEvent(X,"onchange",f);
U.addEvent(X,"onkeyup",c);
if(!d){if(!b){alert("RegexInputNode - please specify the maxlength attribute")
}if(!g){alert("RegexInputNode - please specify dataAttrPlaceholder or use `"+Y.dataAttrPlaceholder+"` attribute.")
}if(!Z){alert("RegexInputNode - please specify dataAttrReplacement or use `"+Y.dataAttrReplacement+"` attribute.")
}if(!h){alert("RegexInputNode - please specify dataAttrMatcherRegex or use `"+Y.dataAttrMatcherRegex+"` attribute.")
}if(!W){alert("RegexInputNode - please specify targetClass or apply `"+Y.targetClass+"` to a nextSibling of the target element.")
}}}i()
},EOF:0};
if(B.isIPad){G.extend(J,function(){return{waitAlertSettings:function(V){N=(new Date()).getTime();
return 500
},updateWaitMessage:function(W){if(!T){this.showWaitAlert()
}var V=B.getElementById("awwaitMessage");
if(V){V.innerHTML=W;
V.style.paddingTop="15px";
B.positionDialogBox(Q)
}},hideWaitAlert:function(){if(T){T=false;
window.onscroll=E;
window.onresize=A;
E=null;
A=null;
if(Q!=null){$(Q).addClass("is-dnone").removeClass("is-block");
var V=B.getElementById("awwaitMessage");
if(V){V.innerHTML="";
V.style.paddingTop="0px"
}B.unoverlay(Q)
}}},EOF:0}
}())
}if(B.IsIE6Only){G.extend(J,function(){var V=new Array();
return{hideSelects:function(b){var e;
var d;
var c=document.getElementsByTagName("select");
if(!b){this.disposeDummySelects()
}for(var a=0;
a<c.length;
a++){d=c[a];
if(!b&&d.offsetWidth>0){if(d.size>1){continue
}var Y;
for(Y=0;
Y<d.options.length;
Y++){if(d.options[Y].selected){e=d.options[Y].text
}}var X=document.getElementById("AWDummySelect");
var W=X.cloneNode(true);
document.body.appendChild(W);
var Z=W.getElementsByTagName("td");
for(Y=0;
Y<Z.length;
Y++){if(Z[Y].className=="dummySelect"){Z[Y].innerText=e
}}W.style.width=d.offsetWidth-1;
W.style.zIndex="-100";
W.style.position="absolute";
$(W).removeClass("is-dnone");
W.style.top=B.absoluteTop(d);
W.style.left=B.absoluteLeft(d);
V[V.length]=W
}if(this.modallyDisabled(d)){d.style.visibility="hidden"
}}},showSelects:function(){var Y=document.getElementsByTagName("select");
for(var X=0;
X<Y.length;
X++){var W=Y[X];
W.style.visibility="visible"
}this.disposeDummySelects()
},disposeDummySelects:function(){for(var W=0;
W<V.length;
W++){V[W].removeNode(true)
}V=new Array()
},EOF:0}
}())
}if(G.isAW5()&&B.IsIE){G.extend(J,function(){var V=null;
return{disableInput:function(W){U.disableEvents();
if(V==null){V=document.createElement("div");
document.body.appendChild(V)
}V.setCapture(false);
V.style.cursor="wait";
if(W){V.onmousedown=this.showWaitAlert.bindEventHandler(this);
V.onkeydown=this.showWaitAlert.bindEventHandler(this)
}},enableInput:function(){U.enableEvents();
if(V==null){return 
}V.onmousedown=null;
V.onkeydown=null;
V.releaseCapture();
V.style.cursor="pointer"
},EOF:0}
}())
}if(!G.isAW5()||(G.isAW5()&&!B.IsIE)){G.extend(J,function(){function V(W){J.showWaitAlert();
U.cancelBubble(W)
}return{disableInput:function(W){if(G.isAW5()){if(B.isSafari&&!B.isIPad){return 
}}var X=document.body;
if(W){X.addEventListener("mousedown",V,true);
X.addEventListener("keydown",V,true);
X.addEventListener("click",V,true)
}X.addEventListener("mouseover",U.cancelBubble,true);
X.style.cursor="wait"
},enableInput:function(){var W=document.body;
W.removeEventListener("mousedown",V,true);
W.removeEventListener("mouseover",U.cancelBubble,true);
W.removeEventListener("click",V,true);
W.removeEventListener("keydown",V,true);
W.style.cursor=""
},EOF:0}
}())
}G.extend(U,{modallyDisabled:function(V){return J.modallyDisabled(V)
},selectFirstText:function(){return J.selectFirstText()
}});
return J
}();
ariba.Request=function(){var J=ariba.Util;
var Z=ariba.Event;
var Q=ariba.Debug;
var O=ariba.Input;
var B=ariba.Dom;
var S=true;
var U=null;
var V=true;
var P=false;
var A,K,R,H;
var I;
var X;
var D;
var M=0;
var F=false;
var W;
var T=0;
var Y;
var L=0;
var G;
var E=0;
var C=[];
document.cookie="awscreenstats="+window.screen.width+"x"+window.screen.height;
var N={AWSenderIdKey:"awsn",AWResponseId:"",AWRefreshUrl:"",AWPingUrl:"",AWProgressUrl:"",AWFrameName:null,AWReqUrl:null,AWSessionIdKey:null,AWSessionId:null,AWDebugEnabled:false,AWJSDebugEnabled:false,AWShowRequestFrame:false,AWUpdateCompleteTime:0,AWSessionSecureId:"",UseXmlHttpRequests:false,AWPollCallback:null,AWPollErrorState:"pollError",AWPollState:"poll",initParams:function(){J.takeValues(ariba,["Request.AWResponseId","Request.AWSessionSecureId","Request.AWRefreshUrl","Request.AWPingUrl","Request.AWProgressUrl","Request.AWReqUrl","Request.UseXmlHttpRequests","Request.AWSessionIdKey","Request.AWSessionId","Request.AWFrameName","Refresh.AWBackTrackUrl","Refresh.AWForwardTrackUrl","Input.AWWaitAlertMillis","Dom.AWOpenWindowErrorMsg"],arguments)
},setDocumentLocation:function(b,a,c){if(J.isNullOrUndefined(a)){this.getContent(b)
}else{if(J.isNullOrUndefined(c)){c=""
}window.open(b,a,c)
}return false
},openWaitWindow:function(a,c){var b=B.openWindow("",a,c);
b.focus();
O.showWaitAlertInWindow(b);
return b
},submitFormAtIndexWithHiddenField:function(b,d,c){var e=document.forms[b];
var a=e[d];
a.value=c;
this.submitForm(e);
return false
},submitFormForElementName:function(b,a,e,c){var d=B.formForName(b);
if(a){B.addFormField(d,this.AWSenderIdKey,a)
}this.submitForm(d,c);
Z.cancelBubble(e);
return false
},invoke:function(b,h,d,f,i,e,a,c){var g=null;
if(!h){h=b.id
}if(b&&!f){g=B.lookupFormId(b)
}return this.senderClicked(h,g,i,e,d,a,c)
},senderClicked:function(h,i,j,g,e,a,c,f){var l=null;
if(i!=null){l=B.getElementById(i)
}if(l!=null){Z.cancelBubble(e);
var d;
if(a){d=document.createElement("input");
d.type="hidden";
d.id=h;
d.name=h;
l.appendChild(d);
d.value=c?c:h
}var k=l.wzrd_action;
if((k!=null)&&(g!=null)){k.value=g
}B.addFormField(l,this.AWSenderIdKey,h);
this.invokeSenderClickedCallbacks(h,i);
if(j!=null&&j!="_self"){this.submitForm(l,j,f)
}else{this.submitForm(l)
}if(a){l.removeChild(d)
}}else{var b=this.formatUrl(h);
this.invokeSenderClickedCallbacks(h,null);
this.setDocumentLocation(b,j,f)
}if(e){Z.cancelBubble(e)
}return false
},registerSenderClickedCallback:function(a){if(!U){U=new Array()
}U[U.length]=a
},invokeSenderClickedCallbacks:function(c,b){if(U){for(var a=0;
a<U.length;
a++){U[a](c,b)
}}},formatUrl:function(b){var a=this.formatSenderUrl(b);
return this.appendScrollValues(a)
},formatSenderUrl:function(a){return this.partialUrl()+this.AWSenderIdKey+"="+a
},formatInPageRequestUrl:function(a){return this.formatSenderUrl(a)+"&awip=1"
},appendScrollValues:function(a){if(a.indexOf("#")==-1){a=a+"&awst="+B.getPageScrollTop()+"&awsl="+B.getPageScrollLeft()
}return a
},gotoLink:function(e,b,c,d){var a=this.formatUrl(e);
this.setDocumentLocation(a,b,c);
Z.cancelBubble(d);
return false
},setResponseId:function(a){this.AWResponseId=a
},appendQueryValue:function(a,b,d){var c=a.toString();
var e=null;
if(c.match(/\?/)==null){e="?"
}else{e="&"
}c=c+e+b+"="+encodeURIComponent(d);
return c
},setupPoll:function(e,c,h,j,g){V=e;
var a=c*1000;
if(H!=a){H=a;
clearTimeout(A);
A=null
}K=h;
R=j;
P=g;
b();
function b(){if(V&&A==null){A=setTimeout(f.bind(N),H)
}}function d(){if(V){clearTimeout(A);
A=setTimeout(f.bind(N),0)
}}this.pollNow=d;
function i(n){clearTimeout(A);
A=null;
var l=n.responseText;
var k=n.status;
Q.log("poll response: "+J.htmlEscapeValue(l));
Q.log("poll status: "+k);
var m=P;
if(l=="<AWPoll state='update'/>"){Q.log("page changed -- go get content");
if(!S){this.getContent(this.formatInPageRequestUrl(R))
}m=true
}else{if(l=="<AWPoll state='nochange'/>"){m=true
}else{if(this.AWPollCallback){this.AWPollCallback(this.AWPollErrorState)
}}}if(m){b()
}}function f(){Q.log("AWRequestInProgress: "+S+", AWPollEnabled="+V);
if(!S&&V){if(this.AWPollCallback){this.AWPollCallback(this.AWPollState)
}var k=this.formatInPageRequestUrl(K);
this.initiateXMLHttpRequest(k,i.bind(this))
}else{clearTimeout(A);
A=null;
b()
}}},submitFormObjectNamed:function(a){var b=document.forms(a);
this.submitForm(b);
return false
},submitForm:function(k,i,f,c){var g=true;
if(k.onsubmit){g=k.onsubmit();
if(typeof (g)=="undefined"){g=true
}}if(g){Z.invokeRegisteredHandlers("onsubmit");
this.addAWFormFields(k);
if(i&&i!="_self"){B.removeFormField(k,"awii");
if(i=="_blank"){i="AWWindow_"+new Date().getTime()
}k.target=i;
k.submit()
}else{this.prepareForRequest(c);
try{var j=this.hasPopulatedFileInputContol(k,true);
var b=null;
if(j){b=k.enctype;
if(!b||(b.indexOf("multipart")!=0)){k.enctype="multipart/form-data";
k.encoding="multipart/form-data"
}else{b=null
}}if(this.UseXmlHttpRequests&&!j){Q.log("<--- Incremental post: XMLHTTP");
B.addFormField(k,"awii","xmlhttp");
var a=this.encodedFormValueString(k);
N.initiateXMLHttpRequest(this.partialUrl(),function(l){var e=l.responseText;
ariba.Refresh.processXMLHttpResponse(e)
},a)
}else{Q.log("<--- Incremental post: IFRAME");
var d=this.createRefreshIFrame();
k.target=d.name;
B.addFormField(k,"awii",d.name);
B.addFormField(k,"awdnd","false");
k.submit();
if(b){k.enctype=b
}}}catch(h){this.requestComplete();
this.handleFileUploadError(h);
throw (h)
}}}this.removeAWFormFields(k);
k.target=null
},formValueAccessors:{input:function(a){switch(a.type.toLowerCase()){case"checkbox":case"radio":return a.checked?a.value:null;
default:return a.value
}},textarea:function(a){return a.value
},select:function(g){function f(h){return h.value||h.text
}if(g.type.toLowerCase()=="select-one"){var b=g.selectedIndex;
return b>=0?f(g.options[b]):null
}else{var a,e=g.length;
if(!e){return null
}for(var c=0,a=[];
c<e;
c++){var d=g.options[c];
if(d.selected){a.push(f(d))
}}return a
}}},serialize:function(c){var b=c.tagName.toLowerCase();
var a=this.formValueAccessors[b];
return(a)?a(c):null
},formValueMap:function(a){var b={};
$(a).find("*[name]").each(function(e,f){var d=$(f);
if(!(d.hasClass("w-btn-disabled")||f.disabled)){var g=N.serialize(f);
if(g){var c=f.name;
b[c]=J.itemOrArrAdd(b[c],g)
}}});
return b
},encodedFormValueString:function(g){var e=this.formValueMap(g);
var b=[];
for(var d in e){var a=encodeURIComponent(d);
var f=e[d];
if(J.isArray(f)){for(var c=0;
c<f.length;
c++){b.push(a+"="+encodeURIComponent(f[c]||""))
}}else{b.push(a+"="+encodeURIComponent(f||""))
}}return b.join("&")
},addRequestValue:function(a,b){if(!I){I=new Object()
}I[a]=b
},addAWFormFields:function(b){B.addFormField(b,"awr",this.AWResponseId);
B.addFormField(b,"awst",B.getPageScrollTop());
B.addFormField(b,"awsl",B.getPageScrollLeft());
B.addFormField(b,"awssk",this.AWSessionSecureId);
if(I){for(var a in I){B.addFormField(b,a,I[a])
}}},removeAWFormFields:function(b){B.removeFormField(b,this.AWSenderIdKey);
B.removeFormField(b,"awr");
B.removeFormField(b,"awst");
B.removeFormField(b,"awsl");
B.removeFormField(b,"awssk");
if(I){for(var a in I){B.removeFormField(b,a)
}}},uploadFileAsync:function(c){var b=Z.eventSourceElement(c);
var a=b;
var e=a.id;
var d=B.lookupFormId(a);
this.submitFormForElementName(d,e)
},handleFileUploadError:function(b){var a=B.getElementById("AWFileUploadErrorMessage");
if(a){alert(a.innerText)
}},partialUrl:function(){var a=this.AWReqUrl+"?awr="+this.AWResponseId;
if(this.AWSessionIdKey){a+="&"+this.AWSessionIdKey+"="+this.AWSessionId
}if(this.AWFrameName){a+="&awf="+this.AWFrameName
}if(this.AWSessionSecureId){a+="&awssk="+this.AWSessionSecureId
}return a+"&"
},simpleXMLHTTP:function(a,b){this._asyncGet(function(c){if(c){c.onreadystatechange=function(){if(c.readyState==4){if(c.status==200){b(c)
}else{if(N.AWDebugEnabled){alert('Got "'+c.status+" "+c.statusText+'" for '+a)
}}N._asyncDone(c)
}};
try{c.open("GET",a,true);
c.send(null)
}catch(d){alert("XMLHTTP Error in send: "+d.message);
N._asyncDone(c)
}}})
},appendFrameName:function(a){if(!J.isNullOrUndefined(this.AWFrameName)&&a.match(/awf=/)==null){return this.appendQueryValue(a,"awf",this.AWFrameName)
}return a
},redirectRefresh:function(){var a=this.appendFrameName(this.AWRefreshUrl);
this.redirect(a)
},redirect:function(c){this.prepareRedirectRequest();
var b=window.location;
if(B.isSafari){if(c.indexOf("/")==0){if(b.href.indexOf("awrdt=1")<0){c=c+"&awrdt=1"
}else{c=c.replace(/\&awrdt=1/,"")
}}}if(B.isChrome||B.isSafari){setTimeout(function(){b.href=c
},500)
}else{b.href=c
}if(B.IsIE6Only){function a(){if(document.readyState!="loading"){window.location.href=c;
setTimeout(a,500)
}}setTimeout(a,500)
}},invokeAction:function(a){this.getContent(this.formatUrl(a))
},addAWQueryValues:function(a){var c=a;
if(I){for(var b in I){c=this.appendQueryValue(c,b,I[b])
}}return c
},getContent:function(a,b){this.prepareForRequest();
a=this.addAWQueryValues(a);
if(this.UseXmlHttpRequests&&!b){Q.log("<--- Incremental get: XMLHTTP");
a=this.appendQueryValue(a,"awii","xmlhttp");
N.initiateXMLHttpRequest(a,function(e){var d=e.responseText;
ariba.Refresh.processXMLHttpResponse(d)
})
}else{Q.log("<--- Incremental get: IFRAME");
var c=this.createRefreshIFrame();
a=this.appendQueryValue(a,"awii",c.name);
c.src=this.appendFrameName(a)
}},__retryRequest:function(a){Q.log("Server responded with retry request ("+a+") -- doing IFrame retry ");
this.getContent(this.formatUrl(a),true)
},prepareForRequest:function(a){this.requestComplete();
S=true;
ariba.Refresh.enableRefreshScript();
Z.invokeRegisteredHandlers("onRefreshRequestBegin");
if(!a){O.showWaitCursor()
}setTimeout(this.startRefreshTimer.bind(this),1);
if(this.AWProgressUrl){O.AWWaitMillis=20*60*1000;
this.initProgressCheck(this.AWProgressUrl,O.AWWaitAlertMillis+2000,O.AWWaitAlertMillis)
}},isRequestInProgress:function(){return S
},requestNotInProgress:function(){S=false
},requestComplete:function(){this.requestNotInProgress();
O.hideWaitCursor()
},prepareRedirectRequest:function(){this.refreshRequestComplete();
V=false
},isRequestInProgress:function(){return S
},displayErrorDiv:function(a){if(ariba.Dom.ApplicationType!==""){if(N.AWDebugEnabled){var b=document.createElement("div");
b.className="debugFloat";
b.innerHTML=a;
document.body.appendChild(b)
}else{this.redirectRefresh()
}}else{this.redirectRefresh()
}},createRequestIFrame:function(b,e){var d=b+"Div";
var a=B.getElementById(d);
if(!a){a=document.createElement("div");
if(!e){a.style.display="none"
}a.id=d;
document.body.appendChild(a)
}var c=e?" style='border:2px solid blue;' height='300px' width='400px'":" style='border:0px;display:none' height='0px' width='0px'";
a.innerHTML="<iframe src='"+B.AWEmptyDocScriptlet+"' id='"+b+"' name='"+b+"'"+c+"></iframe>";
return B.getElementById(b)
},destroyRequestIFrame:function(a){var c=B.getElementById(a);
if(c){function b(){Z.removeEvent(c,"onload",b);
setTimeout(function(){if(!B.elementInDom(c)){Q.log("Skipped destroying Iframe: "+a+": no longer in DOM");
return 
}var d=B.getElementById(a+"Div");
if(d){d.innerHTML="";
Q.log("Destroyed Iframe: "+a)
}},1)
}Z.addEvent(c,"onload",b);
c.src=B.AWEmptyDocScriptlet
}},createRefreshIFrame:function(){if(this.AWJSDebugEnabled){var a=new Date();
Q.setRequestStartTime(a.getTime())
}return this.createRequestIFrame("AWRefreshFrame",this.AWShowRequestFrame)
},startRefreshTimer:function(){if(!B.IsMoz){X=setTimeout(this.checkRequestComplete.bind(this),500)
}},setWindowLocation:function(a){window.location=a
},checkRequestComplete:function(){Q.log("awCheckRequestComplete");
var a=B.getElementById("AWRefreshFrame");
if(!a){return 
}var d=false;
try{if(a.contentWindow&&a.contentWindow.document&&a.contentWindow.document.URL.indexOf(B.AWEmptyDocScriptlet)==-1){var c=a.contentWindow.document;
if(c.readyState){if(c.readyState!="complete"){D=setTimeout(this.checkDocumentLoad.bind(this),500)
}this.checkDocumentLoad()
}d=true
}}catch(b){d=true;
O.hideWaitCursor();
this.pingServer()
}if(!d){Q.log("continuing "+M);
M++;
if(M<30){X=setTimeout(this.checkRequestComplete.bind(this),10000)
}else{Q.log("request not initiated ...")
}}},checkDocumentLoad:function(){var b=B.getElementById("AWRefreshFrame");
if(!b){return 
}var a;
try{var d=b.contentWindow.document;
if(d.readyState){Q.log("readyState: "+d.readyState);
if(d.readyState!="complete"){D=setTimeout(this.checkDocumentLoad.bind(this),200);
return 
}}a=B.getDocumentElementById(d,"AWRefreshComplete")
}catch(c){}if(!a){this.handleRequestError()
}},refreshRequestComplete:function(){M=0;
clearTimeout(X);
clearTimeout(D);
ariba.Refresh.clearPendingCompleteRequestRun()
},handleRequestError:function(){O.hideWaitCursor();
var e=B.getElementById("AWRefreshFrame");
e.style.left=0;
e.style.top=0;
var b=B.getElementById("AWRefreshFrameDiv");
if(b){Q.log("setting location of iframediv");
b.style.position="absolute";
b.style.left=0;
b.style.top=0
}else{Q.log("just setting iframe")
}var c;
if(window.innerHeight){c=document.body;
window.scroll(0,0)
}else{c=document.documentElement;
c.scrollTop=0;
c.scrollLeft=0
}var a=c.scrollHeight>screen.availHeight?c.scrollHeight:screen.availHeight;
var d=c.scrollWidth>(screen.availWidth)?c.scrollWidth:(screen.availWidth);
b.style.width=d+"px";
b.style.height=a+"px";
e.style.width=d+"px";
e.style.height=a+"px"
},pingServer:function(){var a=this.createRequestIFrame("AWPingFrame",F);
a.src=this.AWPingUrl;
W=setTimeout(this.checkPingRequestComplete.bind(this),1000)
},checkPingRequestComplete:function(){var b=B.getElementById("AWPingFrame");
if(!b){return 
}var f=false;
try{if(b.contentWindow&&b.contentWindow.document&&b.contentWindow.document.URL.indexOf(B.AWEmptyDocScriptlet)==-1){var d=b.contentWindow.document;
f=true
}}catch(c){f=true;
this.handleRequestError()
}if(!f){T++;
if(T<30){X=setTimeout(this.checkPingRequestComplete.bind(this),10000)
}else{this.handleRequestError()
}}else{if(!F){var a=B.getElementById("AWPingFrameDiv");
if(a){document.body.removeChild(a)
}}}},initProgressCheck:function(c,e,b){function d(g){if(!S){return 
}var h=g.responseText;
Q.log("Progress check.  Message:"+h);
if(h=="--NO_REQUEST--"){var i=function(){Z.notifyRefreshComplete();
N.requestComplete()
};
if(L<=0){i()
}else{Q.log("setTimeout: AWCancelRequestDelayHandle, delay = "+L);
G=setTimeout(i,L)
}}else{O.updateWaitMessage(g.responseText);
f(b);
if(window.awStartInactivityTimer){awStartInactivityTimer()
}}}function a(){Y=null;
if(!S){return 
}N.initiateXMLHttpRequest(c,d.bind(N))
}function f(g){if(Y){clearTimeout(Y)
}Y=setTimeout(a.bind(N),g)
}f(e)
},setCancelRequestDelay:function(a){L=a
},getCancelRequestDelay:function(){return L
},clearCancelRequestDelayHandle:function(){if(G){Q.log("clearTimeout: AWCancelRequestDelayHandle");
clearTimeout(G);
G=null
}},setStatusDone:function(){window.status="Done"
},hasPopulatedFileInputContol:function(b,c){var a=$(b).find("input[type=file]");
if(!c){a.filter(function(){return this.value.length>0
})
}return !!a.length
},getXMLHttp:function(){var a=null;
try{a=new XMLHttpRequest()
}catch(d){try{a=new ActiveXObject("Msxml2.XMLHTTP")
}catch(c){try{}catch(b){a=new ActiveXObject("Microsoft.XMLHTTP")
}}}return a
},_asyncGet:function(a){C.push(a);
this._notifyGet()
},nullFunc:function(){},_asyncDone:function(a){E--;
if(a){a.onreadystatechange=this.nullFunc
}this._notifyGet()
},_notifyGet:function(){if(E>2||(C.length==0)){return 
}var b=C.shift();
E++;
var a=this.getXMLHttp();
setTimeout(function(){b(a)
},0)
},initiateXMLHttpRequest:function(b,e,c){function a(f){f.open("GET",b,true);
f.setRequestHeader("Content-type","text/html");
var h=this;
f.onreadystatechange=function(){h.manageStateChange(f,e)
};
try{f.send(null)
}catch(g){alert("Error initiating request")
}}function d(f){f.open("POST",b,true);
f.setRequestHeader("Content-Type","application/x-www-form-urlencoded; charset=UTF-8");
var h=this;
f.onreadystatechange=function(){h.manageStateChange(f,e)
};
try{f.send(c)
}catch(g){alert("Error initiating request")
}}if(c){this._asyncGet(d.bind(this))
}else{this._asyncGet(a.bind(this))
}},manageStateChange:function(b,c){switch(b.readyState){case 2,3:break;
case 4:var a=function(){c(b);
this._asyncDone(b)
};
setTimeout(a.bind(this),0);
break
}},downloadContent:function(b){var a=N.createRequestIFrame("AWDownload");
a.src=this.addAWQueryValues(b)
},fileDownloadCompleteCheck:function(f,b,c){function d(h){var g=h.responseText;
if(g=="completed"){e()
}else{if(g=="started"){setTimeout(a.bind(this),c)
}else{Q.log("Error running fileDownloadCompleteCheck -- received: "+g)
}}}function e(){N.getContent(b)
}function a(){N.initiateXMLHttpRequest(f,d)
}if(f!=null&&f.length>0){setTimeout(a.bind(this),c)
}else{setTimeout(e.bind(this),c)
}},progressBarSetWidth:function(){if(B.isWindowNarrow()){var a=B.getElementById("awProgressBar");
if(a&&a.width>150){a.width="150px"
}}},EOF:0};
Z.registerRefreshCallback(N.progressBarSetWidth.bind(N));
if(B.isIPad){J.extend(N,function(){var a=N.requestComplete.bind(N);
return{requestComplete:function(){a();
this.hideFCToolText()
},hideFCToolText:function(){if(B.isIPad){var b=B.getElementById("fusioncharts-tooltip-element");
if(b&&!B.getElementById("fc_awchart")){b.style.display="none"
}}},EOF:0}
}())
}return N
}();
window.ariba_IR=false;
ariba.Refresh=function(){var Util=ariba.Util;
var Event=ariba.Event;
var Input=ariba.Input;
var Debug=ariba.Debug;
var Request=ariba.Request;
var Dom=ariba.Dom;
var AWDELETE="d";
var AWINSERT="i";
var AWDomSyncData=new Object();
var AWDomScopeUpdateList=new Object();
var AWRefreshStartTime;
var AWRefreshTrace;
var AWMaxRefreshTraceLength=10;
var AWWindowLoadStartTime;
var AWWindowOnLoad=false;
var _RunningIncrementalAction=false;
var _LoadedJSStrs=[];
var VBSEnqueue=false;
var VBSArray=null;
var _LoadedJS=new Array();
var AWHandlingNewRequest=false;
var AWHandlingTrackRequest=false;
var AWHistoryDebugString;
var AWHistoryBack=0;
var AWHistoryForward=0;
var AWHistoryLimit=2;
var RelocatableDivSuffix="_MovedCopy";
var _CheckLocInterval=null;
var _LocationCheckActive=false;
var _currentUpdateSource=null;
var _isXMLHttpResponse=false;
var _IDPat=/\s+id=(.+?)[\s>]/;
var _IDPatQuote=/\s+id=["\'](.+?)["\']/;
var _ScriptAllPat=/<script[^>]*>([\s\S]*?)<\/script>/ig;
var _ScriptOnePat=/<script([^>]*)>([\s\S]*?)<\/script>/i;
var _currScript=null;
var _pendingCompleteRequestRun=false;
var AWRefreshScriptEnabled=true;
var _ignoreRefreshComplete=false;
var _historyHandler=function(){};
var _MarkedRRs;
var _historyCurrent;
var _historyLength;
var _runCompleteRefreshOnLoad=false;
var _lazyActionScrollInited=false;
var _lazyActionIds=[];
var _inViewportLazyActionIds=[];
var _FireLazyActionsTimeout;
var oModeClassMap={block:"is-block",inline:"is-inline",inlineBlock:"is-iblock",none:"is-dnone"};
var Refresh={AWShowHistoryFrame:false,AWBackTrackUrl:"",AWForwardTrackUrl:"",AWMarkRefreshRegions:false,AWAllowParentFrame:false,_refreshTable:function(sourceHandle,poTarget){var tmpDiv=document.createElement("div");
tmpDiv.innerHTML=_currentUpdateSource.getOuterHtml(sourceHandle);
var tmpTable=null;
for(var i=0;
i<tmpDiv.childNodes.length;
++i){if(tmpDiv.childNodes[i].tagName===poTarget.tagName){tmpTable=tmpDiv.childNodes[i];
break
}}if(tmpTable==null){tmpTable=tmpDiv.firstChild
}this.replaceRows(tmpTable,poTarget)
},_scopeUpdate:function(sourceHandle){var id=_currentUpdateSource.getId(sourceHandle);
var target=Dom.getElementById(id);
if(target){Dom.setOuterHTML(target,_currentUpdateSource.getOuterHtml(sourceHandle));
this._markRR(Dom.getElementById(id))
}else{alert("scopeUpdate target not found: "+id)
}},replaceRows:function(poSourceTable,poTargetTable){var targetTBody=Dom.findChild(poTargetTable,"TBODY");
var sourceRows=Dom.findChild(poSourceTable,"TBODY").childNodes;
var elementDomSyncData=this.findDomSyncElementData(poSourceTable.id);
var i,target;
Debug.log("replaceRows -- table: "+poSourceTable.id+", count: "+sourceRows.length);
var insertArray=elementDomSyncData[AWINSERT];
for(i=0;
insertArray&&i<insertArray.length;
i+=2){var element=Dom.findElement(sourceRows,insertArray[i+1]);
target=null;
if(insertArray[i]=="null"){var rows=targetTBody.childNodes;
var rowNum=0;
while(rowNum<rows.length){var row=rows[rowNum++];
if(row.id&&row.id!=""){target=row;
break
}}}else{target=Dom.getElementById(insertArray[i]);
target=target.nextSibling;
while(target&&!target.tagName){target=target.nextSibling
}}if(target){targetTBody.insertBefore(element,target)
}else{targetTBody.appendChild(element)
}this._markRR(element)
}i=0;
while(i<sourceRows.length){var sourceRow=sourceRows[i];
if(sourceRow.nodeName=="TR"&&sourceRow.id){var targetRow=Dom.findRow(targetTBody,sourceRow.id);
if(targetRow==null){i++
}else{targetTBody.replaceChild(sourceRow,targetRow);
this._markRR(sourceRow)
}}else{i++
}}},handleUpdateError:function(message){var shouldDebug=false;
if(Request.AWDebugEnabled){shouldDebug=confirm(message+".\n\nShow details?")
}if(shouldDebug){var msg=['<h1>Refresh Trace</h1><textarea cols="150" rows="46">'];
if(AWRefreshTrace!=null){for(var i=0;
i<AWRefreshTrace.length;
i=i+2){msg.push("\n=============== Main content ("+i/2+") ====================");
msg.push(AWRefreshTrace[i]);
msg.push("\n=============== Incremental update ("+i/2+") ====================");
msg.push(AWRefreshTrace[i+1])
}}msg.push("</textarea>");
Request.displayErrorDiv(msg.join("\n"))
}else{top.location.href=top.ariba.Request.appendFrameName(top.ariba.Request.AWRefreshUrl)
}return false
},_updateRefreshTrace:function(){var refreshFrame=Dom.getElementById("AWRefreshFrame");
if(false&&Request.AWDebugEnabled){if(AWRefreshTrace==null){AWRefreshTrace=new Array()
}var refreshBody=refreshFrame.contentWindow.document.body;
if(refreshBody){if(AWRefreshTrace.length==AWMaxRefreshTraceLength){for(var traceIndex=0;
traceIndex<AWRefreshTrace.length-2;
traceIndex++){AWRefreshTrace[traceIndex]=AWRefreshTrace[traceIndex+1]
}AWRefreshTrace.length=AWMaxRefreshTraceLength-2
}AWRefreshTrace[AWRefreshTrace.length]=Dom.getOuterHTML(document.body);
AWRefreshTrace[AWRefreshTrace.length]=Dom.getOuterHTML(refreshBody)
}}},IFrameUpdateSource:function(){var refreshFrame=Dom.getElementById("AWRefreshFrame");
var body=Dom.findChild(refreshFrame.contentWindow.document,"BODY");
var elements=[];
if(body!=null){var refreshNodes=body.childNodes;
for(var i=0;
i<refreshNodes.length;
i++){var source=refreshNodes[i];
if(source.id&&source.getAttribute("ignore")!="true"){elements.push(source)
}}}return{getHandles:function(){return elements
},getId:function(handle){return handle.id
},getHandleForId:function(id){return refreshFrame.contentWindow.document.getElementById(id)
},getNodeName:function(handle){return handle.nodeName
},getInnerHtml:function(handle){return handle.innerHTML
},getOuterHtml:function(handle){return Dom.getOuterHTML(handle)
}}
},XMLHTTPUpdateSource:function(response){var ids=[];
var info={};
function init(){var start=0;
while(start!=-1){start+=10;
var end=response.indexOf("<!--@&@-->",start);
var body=(end==-1)?response.substring(start):response.substring(start,end);
var tagEnd=body.indexOf(">");
var tag=body.substring(0,tagEnd+1);
var nodeNameEnd=tag.indexOf(" ");
var nodeName=tag.substring(1,nodeNameEnd).toUpperCase();
var m=_IDPatQuote.exec(tag);
if(!m){m=_IDPat.exec(tag)
}if(m){var id=m[1];
ids.push(id);
info[id]={body:body,nodeName:nodeName}
}start=end
}}init();
return{getHandles:function(){return ids
},getId:function(handle){return handle
},getHandleForId:function(id){return id
},getNodeName:function(handle){return info[handle].nodeName
},getInnerHtml:function(handle){var body=info[handle].body;
var start=body.indexOf(">"),end=body.lastIndexOf("<");
return body.substring(start+1,end)
},getOuterHtml:function(handle){return info[handle].body
}}
},evalScriptTags:function(str){var matches=str.match(_ScriptAllPat)||[];
for(var i=0;
i<matches.length;
i++){var outer=matches[i];
var m=_ScriptOnePat.exec(outer);
_currScript=m[2];
if(m[1].indexOf("VBScript")==-1){eval(_currScript)
}else{if((Dom.IsIE&&Util.isAW5())||(Dom.IsIE&&!Util.isAW5()&&!Dom.IsIE11Up)){Event.GlobalEvalVBScript(_currScript)
}}_currScript=null
}},processXMLHttpResponse:function(response){response=(response?Util.strTrim(response):"");
if(response.length<=0){return 
}window.ariba_IR=_isXMLHttpResponse=true;
try{_pendingCompleteRequestRun=true;
_currentUpdateSource=new this.XMLHTTPUpdateSource(response);
this.evalScriptTags(response)
}catch(e){Request.displayErrorDiv("<h1>Error applying incremental refresh</h1><b>"+e+"</b><br/><br/><b>Script:</b> <pre><code>"+_currScript+"</code></pre><br/><br/><h2>Attaching full response content below...</h2>"+response);
throw (e)
}finally{window.ariba_IR=_isXMLHttpResponse=false
}setTimeout(function(){if(_pendingCompleteRequestRun){Request.displayErrorDiv("<h1>Bad XMLHTTP Incremental Refresh Response</h1><h2>Attaching full response content below...</h2>"+response)
}},1)
},_markRR:function(target){if(this.AWMarkRefreshRegions){Dom.addClass(target,"showRR");
if(!_MarkedRRs){_MarkedRRs=[]
}_MarkedRRs.push(target)
}},clearPendingCompleteRequestRun:function(){_pendingCompleteRequestRun=false
},enableRefreshScript:function(){AWRefreshScriptEnabled=true
},disableRefreshScript:function(){AWRefreshScriptEnabled=false
},domRefreshContentCallback:function(){if(_MarkedRRs){while(_MarkedRRs.length){var e=_MarkedRRs.pop();
try{Dom.removeClass(e,"showRR")
}catch(e){}}}if(Request.AWJSDebugEnabled){AWRefreshStartTime=(new Date()).getTime()
}var i,target;
if(!Util.isNullOrUndefined(AWDomSyncData)){for(var elementId in AWDomSyncData){var elementDomSyncData=AWDomSyncData[elementId];
var deleteArray=elementDomSyncData[AWDELETE];
if(deleteArray){target=Dom.getElementById(elementId);
var targetTBody=Dom.findChild(target,"TBODY");
for(i=0;
i<deleteArray.length;
i++){var child=Dom.getElementById(deleteArray[i]);
if(Util.isNullOrUndefined(child)){return this.handleUpdateError("AW: Error detected during delete. Unable to find element '"+deleteArray[i]+"'")
}targetTBody.removeChild(child)
}}}}var handles=_currentUpdateSource.getHandles();
for(i=0;
i<handles.length;
i++){var handle=handles[i];
var id=_currentUpdateSource.getId(handle);
var nodeName=_currentUpdateSource.getNodeName(handle);
target=Dom.getElementById(id);
if(Util.isNullOrUndefined(target)){this.handleUpdateError("AW: Error detected during update. Unable to find element '"+id+"'")
}if(AWDomScopeUpdateList&&AWDomScopeUpdateList[id]=="true"){this._scopeUpdate(handle)
}else{if(nodeName=="TABLE"){this._refreshTable(handle,target)
}else{if(nodeName=="DIV"||nodeName=="SPAN"){var scrollTop=target.scrollTop;
target.innerHTML=_currentUpdateSource.getInnerHtml(handle);
if(scrollTop){target.scrollTop=scrollTop
}this._markRR(target)
}else{if(Dom.isNetscape()&&target.nodeName=="PRE"){target.innerHTML=_currentUpdateSource.getInnerHtml(handle);
this._markRR(target)
}else{this.handleUpdateError("AW: Error detected during update. Unknown refresh node type '"+target.nodeName+", element '"+id+"'")
}}}}}AWDomSyncData=null;
AWDomScopeUpdateList=null
},windowOnLoad:function(){AWWindowOnLoad=true;
AWWindowLoadStartTime=(new Date()).getTime();
this.refreshComplete();
AWWindowOnLoad=false
},checkParentFrame:function(allowParentFrame){var enablePage=allowParentFrame||top==self;
if(!enablePage){var pop=true;
try{if(top.location.hostname==document.location.hostname){pop=false;
enablePage=true
}}catch(e){}if(pop){top.location=self.location
}}if(enablePage){$(document.body).addClass("is-visible");
$(document.body).removeClass("is-dnone")
}},refreshComplete:function(){Debug.log("Refresh complete called...");
if(this.AWMarkRefreshRegions){Dom.addClass(document.body,"rrVis")
}else{Dom.removeClass(document.body,"rrVis")
}Event.notifyRefreshComplete()
},findDomSyncElementData:function(parentBufferName){if(AWDomSyncData==null){AWDomSyncData=new Object()
}if(!AWDomSyncData[parentBufferName]){AWDomSyncData[parentBufferName]=new Object()
}return AWDomSyncData[parentBufferName]
},registerScopeChanges:function(parentBufferName,inserts,deletes){var elementDomSyncData=this.findDomSyncElementData(parentBufferName);
elementDomSyncData[AWINSERT]=inserts;
elementDomSyncData[AWDELETE]=deletes
},registerScopeUpdate:function(elementName){if(AWDomScopeUpdateList==null){AWDomScopeUpdateList=new Object()
}AWDomScopeUpdateList[elementName]="true"
},registerGlobalJS:function(str){if(_LoadedJSStrs[str]=="true"){Debug.log("awRegisterGlobalJS: Skipping reload of already registered JS: "+str)
}else{_LoadedJSStrs[str]="true";
this.insertGlobalJS(str)
}},RSS:function(sync,isGlobalScope,funcString){_RunningIncrementalAction=true;
var func=function(){try{if(isGlobalScope){var bodyString=Refresh.extractFuncBody(funcString);
ariba.Debug.log("Executing AWClientSideScript ["+bodyString+"]");
Refresh.registerGlobalJS(bodyString)
}else{eval("var f="+funcString+"; f.call();")
}}catch(e){e.message="Exception evaluating script: \n\n"+funcString+"\n -- \n"+e.message;
throw e
}};
Refresh.RSF(sync,false,func)
},RSF:function(sync,isGlobalScope,func){if(!AWRefreshScriptEnabled){return 
}if(sync){func.call(null)
}else{if(isGlobalScope){var funcStr=this.extractFuncBody(func.toString());
func=function(){Refresh.registerGlobalJS(funcStr)
}
}Event.registerUpdateCompleteCallback(func)
}},RVBS:function(id,isGlobalScope){Event.registerUpdateCompleteCallback(function(){Refresh.execVBS(id,isGlobalScope)
})
},execVBS:function(id,isGlobalScope){if(VBSEnqueue){if(!VBSArray){VBSArray=[]
}VBSArray[VBSArray.length]=[id,isGlobalScope];
return 
}var pre=Dom.getElementById(id);
var preInnerText=Dom.getInnerText(pre);
if((Dom.IsIE&&Util.isAW5())||(Dom.IsIE&&!Util.isAW5()&&!Dom.IsIE11Up)){try{Event.GlobalEvalVBScript(preInnerText)
}catch(e){var msg="execVBS: exception evaluating script at id: "+id+"\n"+e.description;
if(pre&&preInnerText){msg+="\n\n"+preInnerText
}alert(msg)
}}},flushVBSQueue:function(){VBSEnqueue=false;
if(VBSArray!=null){for(var i=0;
i<VBSArray.length;
i++){this.execVBS(VBSArray[i][0],VBSArray[i][1])
}}},extractFuncBody:function(str){var re=/function\s*\(\)\s*\{((.|\s)*)\}$\s*/m;
var m=re.exec(str);
var bodyString="";
if(m){bodyString=m[1]
}else{alert("No Match: !  -- "+str)
}return bodyString
},insertGlobalJS:function(str){var head=document.getElementsByTagName("head")[0];
var scriptElem=document.createElement("script");
scriptElem.setAttribute("type","text/javascript");
if(typeof nonceValue!=="undefined"){scriptElem.setAttribute("nonce",nonceValue)
}head.appendChild(scriptElem);
scriptElem.text=str
},loadJSFile:function(url,noRetry){if(_LoadedJS[url]==1){return 
}_LoadedJS[url]=1;
Debug.log("JS Load initiated ("+_RunningIncrementalAction+"): "+url);
var scriptHolder=[];
function applyJS(){if(scriptHolder.length>0){Debug.log("Applying JS: "+url);
this.insertGlobalJS(scriptHolder[0]);
if(!Dom.IsIE){Event.refreshIncrementNesting();
setTimeout(Event.notifyRefreshComplete.bind(Event),0)
}}else{if(noRetry){alert("Failed to load JS: "+url)
}else{_LoadedJS[url]=0;
this.loadJSFile(url,true)
}}}function httpSuccess(http){scriptHolder[0]=http.responseText;
Debug.log("JS Load complete: "+url);
Event.notifyRefreshComplete()
}Event.refreshIncrementNesting();
Event.registerUpdateCompleteCallback(applyJS.bind(this));
Request.simpleXMLHTTP(url,httpSuccess.bind(this))
},iFrameFormSubmit:function(iframeFormName){ariba.Request.prepareRedirectRequest();
var us=_currentUpdateSource||new this.IFrameUpdateSource();
var handle=us.getHandleForId(iframeFormName);
var formHtml=us.getOuterHtml(handle);
var div=document.createElement("div");
document.body.appendChild(div);
div.innerHTML=formHtml;
var realForm=div.firstChild;
realForm.submit()
},completeRequest:function(current,length,isRefreshRequest,ignoreRefreshComplete){_ignoreRefreshComplete=ignoreRefreshComplete;
if(!_isXMLHttpResponse&&Dom.isSafari&&isRefreshRequest){_historyCurrent=current;
_historyLength=length;
_runCompleteRefreshOnLoad=true
}else{this._completeRequest(current,length,isRefreshRequest)
}},ignoreRefreshComplete:function(){return _ignoreRefreshComplete
},completeRefreshOnLoad:function(){if(_runCompleteRefreshOnLoad){_runCompleteRefreshOnLoad=false;
ariba.Debug.log("completeRefreshOnLoad");
this._completeRequest(_historyCurrent,_historyLength,true)
}},_completeRequest:function(current,length,isRefreshRequest){_pendingCompleteRequestRun=false;
AWRefreshScriptEnabled=false;
Event.eventLock();
if(_isXMLHttpResponse){isRefreshRequest=true
}if(isRefreshRequest){Debug.log("*** refresh");
Event.invokeRegisteredHandlers("onRefreshRequestComplete");
Request.refreshRequestComplete();
if(_isXMLHttpResponse){this.domRefreshContentCallback()
}else{_currentUpdateSource=new this.IFrameUpdateSource();
this.domRefreshContentCallback();
if(!Request.AWShowRequestFrame){Request.destroyRequestIFrame("AWRefreshFrame")
}}_currentUpdateSource=null;
if(current!=null&&length!=null){Event.registerUpdateCompleteCallback(function(){Refresh.updateHistory(current,length)
})
}if(Input.AWAutomationTestModeEnabled){Event.registerUpdateCompleteCallback(function(){setTimeout(Request.setStatusDone.bind(Request),0)
})
}this.refreshComplete()
}else{Debug.log("*** full page update");
if(current!=null&&length!=null){Event.registerUpdateCompleteCallback(this.updateHistory.bind(this),[current,length])
}Event.registerRefreshCallback(Request.requestComplete.bind(Request))
}var e=Dom.getElementById("FPR_Warning");
if(e){if(isRefreshRequest){if(e.tagName=="DIV"){Dom.getElementById("debugBar").className="debugBar"
}e.className="";
e.innerHTML=""
}else{Dom.getElementById("debugBar").className="debugBarVis";
var msg=e.innerHTML;
if(msg&&msg.indexOf("(OK)")>=0){e.className="debugWarning";
e.innerHTML="Full Page Refresh: <br/>"+e.innerHTML
}else{e.className="debugError";
e.innerHTML="FULL PAGE REFRESH!: <br/>"+e.innerHTML
}}}if(Request.AWJSDebugEnabled){Request.AWUpdateCompleteTime=(new Date()).getTime();
setTimeout(this.debugRequestComplete.bind(this),0)
}Event.eventUnlock()
},debugRequestComplete:function(){if(this.AWJSDebugEnabled){var currTime=(new Date()).getTime();
var total="n/a";
var refreshTime="n/a";
var postRefreshTime="n/a";
var onloadTime="n/a";
var requestStartTime=Debug.getRequestStartTime();
if(!Util.isNullOrUndefined(requestStartTime)){total=currTime-requestStartTime
}else{Debug.log("Null start time. Request not initiated through iframe.")
}if(!Util.isNullOrUndefined(AWRefreshStartTime)){refreshTime=currTime-AWRefreshStartTime
}if(!Util.isNullOrUndefined(this.AWUpdateCompleteTime)){postRefreshTime=currTime-this.AWUpdateCompleteTime
}if(!Util.isNullOrUndefined(AWWindowLoadStartTime)){onloadTime=currTime-AWWindowLoadStartTime
}Debug.log("--> request complete - total:"+total+" onload: "+onloadTime+" refresh:"+refreshTime+" postRefresh:"+postRefreshTime)
}},loadLazyChildren:function(divObject,postLoadCallback){var childrenArray=Dom.getChildren(divObject);
var arrayLength=childrenArray.length;
var index=0;
var val=false,loaded;
for(index=0;
index<arrayLength;
index++){var childObject=childrenArray[index];
if(childObject.tagName=="DIV"){loaded=this.loadLazyDiv(childObject,postLoadCallback);
val=val||loaded
}else{if(childObject.tagName=="SPAN"){loaded=this.loadLazyChildren(childObject,postLoadCallback);
val=val||loaded
}}}return val
},loadLazyDivCallback:function(divObject,xmlhttp){var parent=divObject.parentNode;
this.evalScriptTags(xmlhttp.responseText);
AWRefreshScriptEnabled=false;
Dom.setOuterHTML(divObject,xmlhttp.responseText);
Refresh.refreshComplete();
this.markDivLoadingDone(divObject);
Input.hideWaitCursor();
Event.notifyParents(parent,"lazyCallback");
this.postLoadLazyDiv();
if(Input.AWAutomationTestModeEnabled){setTimeout(Request.setStatusDone.bind(Request),0)
}},loadLazyDiv:function(divObject,postLoadCallback){if(this.divNeedsLoading(divObject)){this.markDivLoadingInProgress(divObject);
Request.prepareForRequest();
var divId=divObject.id;
var url=Request.formatSenderUrl(divId);
Request.initiateXMLHttpRequest(url,function(xmlhttp){var div=Dom.getElementById(divId);
if(div){if(postLoadCallback){postLoadCallback(div,xmlhttp)
}else{Refresh.loadLazyDivCallback(div,xmlhttp)
}}});
return true
}else{if(this.loadLazyChildren(divObject,postLoadCallback)){return true
}}return false
},markDivLoadingInProgress:function(divObject){divObject.setAttribute("awneedsLoading","inProgress")
},markDivLoadingDone:function(divObject){divObject.setAttribute("awneedsLoading","false")
},divNeedsLoading:function(divObject){return divObject.getAttribute("awneedsLoading")=="true"
},childrenNeedLoading:function(divObject){var childrenArray=Dom.getChildren(divObject);
if(childrenArray){var arrayLength=childrenArray.length;
var index=0;
for(index=0;
index<arrayLength;
index++){var childDiv=childrenArray[index];
if(childDiv.tagName=="DIV"||childDiv.tagName=="SPAN"){if(this.divNeedsLoading(childDiv)){return true
}else{return this.childrenNeedLoading(childDiv)
}}}}return false
},initLazyAction:function(lazyActionId){if(!_lazyActionScrollInited){_lazyActionScrollInited=true;
Event.registerRefreshCallback(this.checkLazyActions.bind(this));
Event.registerWindowOnScroll(this.checkLazyActions.bind(this))
}_lazyActionIds.push(lazyActionId)
},checkLazyActions:function(){var i,lazyActionId,elm,fireLazyActions;
var notInViewportLazyActionIds=[];
for(i=0;
i<_lazyActionIds.length;
i++){lazyActionId=_lazyActionIds[i];
elm=Dom.getElementById(lazyActionId);
if(elm){if(Dom.isElementInViewport(elm)){Debug.log(lazyActionId+" in viewport");
Util.arrayAddIfNotExists(_inViewportLazyActionIds,lazyActionId);
fireLazyActions=true
}else{Util.arrayAddIfNotExists(notInViewportLazyActionIds,lazyActionId)
}}}if(fireLazyActions){this.fireLazyActions()
}_lazyActionIds=notInViewportLazyActionIds
},fireLazyActions:function(){if(_FireLazyActionsTimeout){clearTimeout(_FireLazyActionsTimeout)
}_FireLazyActionsTimeout=setTimeout(this._fireLazyActions.bind(this),500)
},_fireLazyActions:function(){if(!Request.isRequestInProgress()){var senderId=_inViewportLazyActionIds.join(",");
_inViewportLazyActionIds=[];
Request.getContent(Request.formatInPageRequestUrl(senderId))
}else{this.fireLazyActions()
}},evalOnVisibleScript:function(element){var children=element.childNodes;
for(var index=children.length-1;
index>-1;
index--){var child=children[index];
if(child.id=="_awonVisible"){var onVisibleScript=child.innerHTML;
eval(onVisibleScript);
return 
}}},undisplayDiv:function(el){var $el=$(el);
$el.addClass("is-dnone");
var containerId=$el.id;
var relocateDiv=$("#"+containerId+RelocatableDivSuffix);
if(relocateDiv){relocateDiv.addClass("is-dnone")
}Dom.unoverlay($el[0])
},undisplayDivLegacy:function(divObject){if(divObject!=null){divObject.style.display="none";
Dom.unoverlay(divObject)
}},getHistoryIFrame:function(){return Dom.getElementById("AWHistoryControl")
},createHistoryIFrame:function(){var iframeDiv=Dom.getElementById("AWHistoryFrameDiv");
if(!iframeDiv){alert("AWHistoryFrameDiv not found")
}var height;
var style;
if(ariba.Util.isAW5()){height=this.AWShowHistoryFrame?"height='55px'":" height='0px' width='0px'";
style="'border:0px'"+height
}else{if(this.AWShowHistoryFrame){height=";height:'55px'"
}else{height="; height:0px; width:0px";
iframeDiv.style.height=0;
iframeDiv.style.width=0
}style="'border:0px;"+height+"'"
}iframeDiv.innerHTML="<iframe src='"+Dom.AWEmptyDocScriptlet+"' id='AWHistoryControl' name='AWHistoryControl' style="+style+"></iframe>";
return this.getHistoryIFrame()
},updateHistory:function(current,length){var backCount=current;
if(backCount>AWHistoryLimit){backCount=AWHistoryLimit
}var forwardCount=0;
if(length-1-current>=1){forwardCount=1
}var iframe=this.getHistoryIFrame();
if(iframe){if(AWHistoryBack==backCount&&AWHistoryForward==forwardCount){return 
}}else{}AWHandlingNewRequest=true;
AWHistoryDebugString="back: "+(backCount+1)+" forward: "+forwardCount;
AWHistoryBack=backCount;
AWHistoryForward=forwardCount;
setTimeout(this.startBacktrackHistoryCreate.bind(this),10)
},historyRequest:function(distance){if(AWHandlingNewRequest){AWHandlingNewRequest=false;
return 
}if(_CheckLocInterval){clearInterval(_CheckLocInterval);
_CheckLocInterval=null
}if(distance==-1){AWHandlingTrackRequest=true;
Request.getContent(this.AWBackTrackUrl)
}else{if(distance==1){AWHandlingTrackRequest=true;
Request.getContent(this.AWForwardTrackUrl)
}else{alert("refresh?")
}}},startBacktrackHistoryCreate:function(){if(Dom.IsIE){var iframe=this.createHistoryIFrame()
}else{if(!_CheckLocInterval){_CheckLocInterval=setInterval(this.checkForLocationChange.bind(this),100)
}}_LocationCheckActive=false;
this.createBacktrackHistory(AWHistoryBack+1,AWHistoryForward)
},checkForLocationChange:function(){if(!_LocationCheckActive){return 
}var loc=Dom.getHashLocation();
this.processLocationChange(loc)
},processLocationChange:function(loc){if(loc&&loc!="b0"){var dir=loc.charAt(0);
if(dir=="b"){this.historyRequest(-1)
}else{if(dir=="f"){this.historyRequest(1)
}}}},createBacktrackHistory:function(backCount,forwardCount){if(backCount>0){AWHandlingNewRequest=true;
this.backtrackHistory(backCount-1,forwardCount)
}else{this.createForwardtrackHistory(forwardCount,forwardCount)
}},createForwardtrackHistory:function(forwardCount,currentCount){if(forwardCount>0){AWHandlingNewRequest=true;
this.forwardtrackHistory(forwardCount-1,currentCount)
}else{if(currentCount!=0){AWHandlingNewRequest=true;
_historyHandler=function(){_historyHandler=Refresh.processLocationChange.bind(Refresh)
};
history.go(-currentCount)
}else{_historyHandler=Refresh.processLocationChange.bind(Refresh)
}AWHandlingNewRequest=false;
_LocationCheckActive=true
}},historyKey:function(url){var m=url.toString().match(/(&|\?)k=(\w+)/);
return m?m[2]:null
},historyEvent:function(url){_historyHandler(this.historyKey(url))
},addHistory:function(key,postAddHandler){var iframe=this.getHistoryIFrame();
if(this.historyKey(iframe.src)==key){key+="1"
}iframe.src=Request.AWReqUrl+"?awh=s&k="+key;
_historyHandler=postAddHandler
},backtrackHistory:function(backCount,forwardCount){if(Dom.IsIE){this.addHistory("b",function(key){Refresh.createBacktrackHistory(backCount,forwardCount)
})
}else{function bt(){window.location.hash="b"+backCount;
Refresh.createBacktrackHistory(backCount,forwardCount)
}setTimeout(bt,50)
}},forwardtrackHistory:function(forwardCount,currentCount){Debug.log("Add Forwardtrack: "+forwardCount);
if(Dom.IsIE){this.addHistory("f",function(key){Refresh.createForwardtrackHistory(forwardCount,currentCount)
})
}else{function ft(){window.location.hash="f"+forwardCount;
Refresh.createForwardtrackHistory(forwardCount,currentCount)
}setTimeout(ft,50)
}},EOF:0};
if(Dom.IsIE&&Util.isAW5()){Util.extend(Refresh,function(){var AWCurrDiv_IE;
return{postLoadLazyDiv:function(){if(AWCurrDiv_IE&&Dom.elementInDom(AWCurrDiv_IE)){Dom.repositionDivToWindow(AWCurrDiv_IE);
Dom.overlay(AWCurrDiv_IE,true)
}AWCurrDiv_IE=null
},preDisplayDiv:function(divObject){},displayDiv:function(el,mode,needsUpdate,skipOverlay){if(el){var sDisplayClass=oModeClassMap[mode],$el=$(el);
$el.removeClass("is-dnone").addClass(sDisplayClass);
if($el.css("display")==="none"){$el.css("display","");
var containerId=$el.id;
var relocateDiv=$("#"+containerId+RelocatableDivSuffix);
if(relocateDiv){relocateDiv.removeClass("is-dnone").addClass(sDisplayClass)
}}AWCurrDiv_IE=el;
Refresh.loadLazyDiv(el);
if(!skipOverlay){Refresh.preDisplayDiv(el);
Dom.overlay(el,needsUpdate)
}Refresh.evalOnVisibleScript(el)
}},EOF:0}
}())
}if(!Dom.IsIE||(Dom.IsIE&&!Util.isAW5())){Util.extend(Refresh,function(){var AWCurrDiv_NS;
return{postLoadLazyDiv:function(mode){if(AWCurrDiv_NS){mode=mode?mode:"";
AWCurrDiv_NS.style.display=mode;
Dom.repositionDivToWindow(AWCurrDiv_NS);
AWCurrDiv_NS=null
}},displayDiv:function(el,mode){if(el){var sDisplayClass=oModeClassMap[mode],$el=$(el);
$el.removeClass("is-dnone").addClass(sDisplayClass);
if($el.css("display")==="none"){$el.css("display","");
var containerId=$el.id;
var relocateDiv=$("#"+containerId+RelocatableDivSuffix);
if(relocateDiv){relocateDiv.css("display","")
}}AWCurrDiv_NS=el;
if(!Refresh.loadLazyDiv(el)){Refresh.postLoadLazyDiv(mode||"")
}Refresh.evalOnVisibleScript(el)
}},EOF:0}
}())
}window.onload=Refresh.windowOnLoad.bind(Refresh);
return Refresh
}();
function RJS(C,A,D,B){if(ariba.Refresh._isXMLHttpResponse){if(C){ariba.Refresh.RSS(A,D,B.toString())
}}else{ariba.Refresh.RSF(A,D,B)
}}ariba.Handlers=function(){var O=ariba.Event;
var K=ariba.Input;
var B=ariba.Request;
var I=ariba.Dom;
var M=ariba.Util;
var A="awfa";
var J="awdidchg";
var E="AWPopupSelectedCaptured";
var H=null;
var G;
var N=false;
var F=false;
var L=[];
var D=null;
function P(R){var T=R.getAttribute("_pl");
if(T){var S=R.value;
if(T==S){R.value="";
I.removeClass(R,"ph");
I.removeClass(R,"w-txt-placeholder")
}}}var Q={AWActionPopupEnabled:true,mouseWheelOnPopup:function(R,S){O.cancelBubble(S);
return false
},actionPopupChanged:function(R,U){if(this.AWActionPopupEnabled){R.setAttribute(J,"0");
var S=R.options[R.selectedIndex];
var V=S.value;
if(V=="awnop"){R.selectedIndex=R.selectedIndex-1;
return false
}this.AWActionPopupEnabled=false;
var T;
if(V=="awaction"){T=R.form;
I.addFormField(T,B.AWSenderIdKey,S.id);
B.submitForm(T,null,null,true)
}else{T=R.form;
I.addFormField(T,B.AWSenderIdKey,R.name);
B.submitForm(T,null,null,true)
}return true
}this.AWActionPopupEnabled=true;
return true
},actionPopupKeyDown:function(R,U){var S=O.keyCode(U);
if(S==K.KeyCodeEnter||S==K.KeyCodeTab){var T=R.getAttribute(E);
if(R.getAttribute(J)=="1"||(!M.isNullOrUndefined(T)&&(R.selectedIndex!=T))){this.AWActionPopupEnabled=true;
return this.actionPopupChanged(R,U)
}}else{if(S==K.KeyCodeArrowUp||S==K.KeyCodeArrowDown){R.setAttribute(J,"1");
R.setAttribute(E,null);
this.AWActionPopupEnabled=false
}else{this.AWActionPopupEnabled=false;
if(ariba.Dom.IsMoz){R.setAttribute(J,"1")
}else{R.setAttribute(E,R.selectedIndex)
}}}return true
},textFieldRefresh:function(T,S){var R=I.getElementById(T);
I.addFormField(R,B.AWSenderIdKey,S);
B.submitForm(R,null);
return true
},resetTextFieldChanged:function(){if(H!=null){H=null;
O.updateDocHandler("click",null)
}},textRefresh:function(U,R){var S=O.keyCode(U);
if(S==K.KeyCodeShift){return true
}if((S==K.KeyCodeEnter&&R.nodeName!="TEXTAREA")||S==K.KeyCodeTab){if(R.getAttribute(J)=="1"){R.setAttribute(J,"0");
return this.textFieldRefresh(R.form.id,R.name)
}}else{R.setAttribute(J,"1");
if(O.getDocHandler("click")==null){O.registerUpdateCompleteCallback(this.resetTextFieldChanged.bind(this));
H=R.id;
var T=function(X){if(H!=null){X=X?X:event;
var V=I.getElementById(H);
if(V!=null){var W=V.form;
return Q.textFieldRefresh(W.id,V.name)
}}}.bindEventHandler(this);
O.updateDocHandler("click",T)
}}return true
},checkCapsLockErrorTxtRfrsh:function(S,R){this.checkCapsLockError(S);
return this.textRefresh(S,R)
},checkCapsLockError:function(R){if(G){if(O.keyCode(R)==K.KeyCodeCapsLock||O.keyCode(R)==K.KeyCodeBackspace){this.hideCapsLockError()
}}},hideCapsLockError:function(){if(G&&G.style.display!="none"){I.fadeOutElement(G);
G.style.display="none";
G=null
}},noCapsLockTxt:function(X,S,R){var W=0;
var U=false;
if(document.all){W=X.keyCode;
U=X.shiftKey
}else{if(document.getElementById){W=X.which;
U=X.shiftKey
}else{return true
}}if(((W>=65&&W<=90)&&!U)||((W>=97&&W<=122)&&U)){var Y=I.getElementById(R);
if(Y&&Y.style.display!="block"){Y.style.display="block";
var T=I.absoluteTop(S);
var V=I.absoluteLeft(S)+S.offsetWidth+2;
Y.style.top=I.correctForBottomEdge(T,Y)+"px";
Y.style.left=I.correctForRightEdge(V,Y)+"px";
I.fadeInElement(Y);
G=Y
}}else{this.hideCapsLockError()
}return true
},hPassFocus:function(S,R){if(S.value){I.removeClass(S.parentNode,"pfc");
I.addClass(S.parentNode,"field-border")
}K.focus(S)
},hPassBlur:function(S,R){if(!S.value){I.addClass(S.parentNode,"pfc")
}},hPassChange:function(S,R){if(S.value){I.removeClass(S.parentNode,"pfc");
I.addClass(S.parentNode,"field-border")
}if(!S.value){I.addClass(S.parentNode,"pfc")
}},hTextKeyPress:function(R,S){if(K.isCharChange(S)){P(R);
I.addClass(R,"w-txt-active")
}},hTextClick:function(R,S){P(R);
I.addClass(R,"w-txt-active")
},hTextBlur:function(R,U){var T=R.getAttribute("_pl");
if(T){var S=R.value;
if(!S){R.value=T;
I.addClass(R,"ph");
I.addClass(R,"w-txt-placeholder")
}}I.removeClass(R,"w-txt-active")
},textNoSubmit:function(S,R){if(O.keyCode(S)==K.KeyCodeEnter){O.cancelBubble(S);
return false
}},virtualFormKeyPress:function(R,V){V=V?V:event;
var S=O.keyCode(V);
if(S==K.KeyCodeEnter){var U=R.id;
var T=I.findParent(R,"FORM",false);
I.addFormField(T,B.AWSenderIdKey,U);
B.submitForm(T,null);
O.cancelBubble(V)
}return false
},hSubmit:function(S,R){B.submitForm(S,R)
},hKeyDown:function(S,R,T){if((T.type=="keypress")&&(O.keyCode(T)!=K.KeyCodeEnter)){return true
}return B.submitFormForElementName(S,R,T)
},hPopupChanged:function(R,S){if(ariba.Dom.IsIE){this.AWActionPopupEnabled=true
}return this.actionPopupChanged(R,S)
},hLinkClick:function(U,R,S,T){if(N){N=false;
return false
}if((T.type=="keypress")&&(O.keyCode(T)!=K.KeyCodeEnter)){return true
}B.gotoLink(U,R,S,T);
return false
},hTagClick:function(R,X,T,S,W,V,U){return this.tagOnClick(R,X,T,S,W,V,U)
},hTagKeyDown:function(R,W,T,S,V,U){return this.tagOnKeyPress(R,W,T,S,V,U)
},hTagRefreshKeyDown:function(R,W,T,S,V,U){if(this.tagOnKeyPress(R,W,T,S,V,U)){return this.textRefresh(V,R)
}return false
},hPopupAction:function(R,T){var S=R.options[R.selectedIndex];
if(S.value.match(/^aw/)==null){this.AWActionPopupEnabled=false
}return this.actionPopupChanged(R,T)
},hSubmitAtIndex:function(R,T,S){return B.submitFormAtIndexWithHiddenField(R,T,S)
},hOpenWindow:function(T,R,S){return I.openWindow(T,R,S)
},hActionPopupKeyDown:function(R,S){return this.actionPopupKeyDown(R,S)
},hMouseWheelOnPopup:function(R,S){return this.mouseWheelOnPopup(R,S)
},hVirtualFormKeyPress:function(R,S){return this.virtualFormKeyPress(R,S)
},tagOnClick:function(R,X,T,S,W,V,U){return B.senderClicked(R.id,X,T,S,W,V,R.value,U)
},tagOnKeyPress:function(R,W,T,S,V,U){if(O.keyCode(V)==K.KeyCodeEnter){this.tagOnClick(R,W,T,S,V,U);
ariba.Event.cancelBubble(V);
return false
}return true
},fireActionInScope:function(W,V){if(O.keyCode(V)==K.KeyCodeEnter){var R=O.eventSourceElement(V);
var U=false;
if(R&&R.nodeName=="INPUT"){U=R.type=="text"||R.type=="password"
}if(U){var T=ariba.Handlers.fireDefaultActionButton(W,V);
if(I.boolAttr(W,"_hfa",false)&&O.shouldBubble(V)){var S=W[A];
O.cancelBubble(V);
I.addFormField(W,B.AWSenderIdKey,S.value);
B.submitForm(W);
T=false
}return T
}}return true
},fakeClick:function(U,T){if(U){O.elementInvoke(U,"mousein");
O.elementInvoke(U,"mousedown");
var S=O.elementInvoke(U,"click");
O.cancelBubble(T);
var R=function(){if(I.elementInDom(U)){O.elementInvoke(U,"mouseout")
}}.bind(this);
if(B.isRequestInProgress()){O.registerUpdateCompleteCallback(R)
}else{setTimeout(R,1000)
}return S
}return true
},fireDefaultActionButton:function(T,R){var S=I.findChildUsingPredicate(T,function(U){return U.tagName&&I.boolAttr(U,"_isdef",false)
});
return this.fakeClick(S,R)
},ignoreKey:function(R){R=R?R:event;
O.preventDefault(R);
O.cancelBubble(R);
return false
},ignoreKeyDown:function(R){K.showWaitAlert();
this.ignoreKey(R);
return false
},_awHandlers_MARKER:function(){},hoverControlOver:function(R){var S=I.findParentUsingPredicate(R,function(T){return T.getAttribute("bh")=="AWHC"
});
if(S){I.setState(S,"hover")
}},hoverContainerOver:function(R){O.clearTimeout(R)
},hoverContainerOut:function(S){var R=function(){I.unsetState(S,"hover")
};
O.setTimeout(S,R,500);
return true
},initViewportContainer:function(R){if(!F){F=true;
var T=this.checkViewportContainers.bind(this);
var S=function(){O.eventEnqueue(T)
};
O.registerRefreshCallback(S);
O.registerWindowOnScroll(this.checkViewportContainers.bind(this))
}M.arrayAddIfNotExists(L,R)
},checkViewportContainers:function(){var U,S,V,T;
var R=[];
for(U=0;
U<L.length;
U++){S=L[U];
V=I.getElementById(S);
if(V){M.arrayAddIfNotExists(R,S);
I.setViewportState(V)
}}L=R
},EOF:0};
var C={click:function(T,R){if(T.getAttribute("_sL")){B.redirect(T.getAttribute("_sL"));
return true
}if(I.boolAttr(T,"_dC",false)){return true
}var S=I.boolAttr(T,"_sf",true)?I.lookupFormId(T):null;
return ariba.Handlers.tagOnClick(T,S,T.getAttribute("_t"),T.getAttribute("_a"),R,I.boolAttr(T,"_av"),T.getAttribute("_w"))
},focusin:function(S,R){$("body").attr("role","application")
},focusout:function(S,R){$("body").removeAttr("role")
},keydown:function(S,R){if(I.boolAttr(S,"_dC",false)){return true
}if(S.getAttribute("role")=="button"||S.getAttribute("role")=="tab"){if(S.getAttribute("role")=="tab"&&(O.keyCode(R)==K.KeyCodeEnter||O.keyCode(R)==K.KeyCodeSpaceBar)){S.setAttribute("aria-selected","true")
}return(O.keyCode(R)==K.KeyCodeEnter||O.keyCode(R)==K.KeyCodeSpaceBar)?C.click(S,R):true
}else{if((S.getAttribute("role")=="treeitem")&&(O.keyCode(R)==39)&&(S.getAttribute("aria-expanded")=="false")){return C.click(S,R)
}else{if((S.getAttribute("role")=="treeitem")&&(O.keyCode(R)==37)&&(S.getAttribute("aria-expanded")=="true")){return C.click(S,R)
}}return(O.keyCode(R)==K.KeyCodeEnter)?C.click(S,R):true
}}};
O.registerBehaviors({GAT:C,HL:{prototype:C},DHL:{prototype:C,keyup:function(U,R){if((U.getAttribute("role")=="tab"||U.getAttribute("role")=="link")&&O.keyCode(R)==K.KeyCodeArrowDown){O.preventDefault(R);
O.cancelBubble(R);
D=document.querySelector('[aria-selected="true"]');
var S=window.top.document.getElementById("CBDFrame");
if(S!=null){var T='{"type": "FocusOnIframe"}';
S.contentWindow.postMessage(T,"*")
}else{$(".mastCmd").find('[tabindex="0"]')[0].focus()
}}},keydown:function(U,S){if(U.getAttribute("role")=="tab"&&isShellBarAccessibilityEnabled===true){var T=document.getElementsByClassName("w-tabitem-a");
if(T.length>0){var R=U.parentElement.getAttribute("index");
if(O.keyCode(S)==K.KeyCodeArrowRight){T[(R*1)+1].childNodes[1].focus()
}if(O.keyCode(S)==K.KeyCodeArrowLeft){T[(R*1)-1].childNodes[1].focus()
}}}return C.keydown(U,S)
}},TF:{keypress:function(S,R){ariba.Handlers.hTextKeyPress(S,R);
return ariba.Handlers.textNoSubmit(R,S)
},keydown:function(U,R){var S=U.getAttribute("_tf");
if(!S){return true
}var T=I.lookupFormId(U);
return(S=="AC")?ariba.Handlers.hTagKeyDown(U,T,null,null,R,false,null):(S=="ROKP")?ariba.Handlers.hTagRefreshKeyDown(U,T,null,null,R,false,null):ariba.Handlers.textRefresh(R,U)
},click:function(S,R){ariba.Handlers.hTextClick(S,R);
return true
},focusin:function(S,R){$("td.ffi").has("div.required").next().find("input").attr("aria-required","true")
}},TFICON:{prototype:O.behaviors.TF,click:function(V,R){var T=$(V);
var U=T[0].getAttribute("for");
var S=I.getElementById(U);
if(S.disabled==true){return 
}S.focus()
}},PF:{click:function(T,R){var S=I.findChild(T,"INPUT");
ariba.Handlers.hPassFocus(S);
$("div.loginFormBox").find("label").next().attr("aria-required","true");
return true
},focusin:function(S,R){$("div.loginFormBox").find("label").next().attr("aria-required","true")
}},TA:{keyup:function(S,R){ariba.Dom.limitTextLength(S,S.getAttribute("_mL"))
},keydown:function(S,R){return I.boolAttr(S,"_isRF",false)?ariba.Handlers.textRefresh(R,S):true
},click:function(S,R){ariba.Handlers.hTextClick(S,R);
$("td.ffi").has("div.required").next().find(".w-txtarea").attr("aria-required","true");
return true
},focusin:function(S,R){$("td.ffi").has("div.required").next().find(".w-txtarea").attr("aria-required","true")
}},ARIA:{keyup:function(S,R){if(O.keyCode(R)==K.KeyCodeArrowUp){if(D!=null){O.preventDefault(R);
O.cancelBubble(R);
D.focus();
D=null
}}}},AS:{keydown:function(S,R){Q.fireActionInScope(S,R)
}},FUP:{keydown:function(S,R){if(I.IsIE){if(O.keyCode(R)==K.KeyCodeSpaceBar||O.keyCode(R)==K.KeyCodeEnter){event.preventDefault();
S.click()
}}}},ROV:{mouseover:function(T,R){var S=T.getAttribute("roClass")||"hov";
T.setAttribute("origClass",T.className);
T.className=S;
return true
},mouseout:function(S,R){S.className=S.getAttribute("origClass");
return true
}},HLP:{keydown:function(S,R){if(R.keyCode==K.KeyCodeTab||R.keyCode==K.KeyCodeEscape){document.getElementById(ariba.Menu.AWLinkId).focus();
ariba.Menu.hideActiveMenu()
}}},GH:{mouseover:function(S,R){I.setState(S,"hover")
},mouseout:function(S,R){I.unsetState(S,"hover")
}},AWHC:{mouseover:function(S,R){ariba.Handlers.hoverContainerOver(S)
},mouseout:function(S,R){ariba.Handlers.hoverContainerOut(S)
}},AWHCT:{mouseover:function(S,R){ariba.Handlers.hoverControlOver(S)
}}});
if(window==ariba.awCurrWindow){if(I.IsIE6Only){O.registerRefreshCallback(I.updateOverlayIframes.bind(I))
}}return Q
}();
ariba.AWWidgets=function(){var G=ariba.Event;
var D=ariba.Dom;
var F=ariba.Input;
var A={};
var J=false;
var H=[];
var E="";
var B=undefined;
var C=false;
var I={DropDown:(function(){var L=function(){var P=null;
if(J){if(D.IsIE&&C){P=$(document).find(".w-dropdown.u-open")
}var Q=$(document).find(".w-dropdown.u-open");
Q.removeClass("u-open");
$(document).find(".w-dropdown-items.w-dropdown-slide-down, .w-dropdown-items.w-dropdown-slide-up").removeClass("w-dropdown-slide-up").removeClass("w-dropdown-slide-down");
$(document).find(".w-dropdown-items").each(function(){var R=$(this).css("width");
$(this).removeAttr("style").css("width",R)
});
J=false;
Q.attr("aria-expanded","false");
Q.removeAttr("aria-activedescendant");
B=-1;
if(D.IsIE&&C){C=false;
P.blur()
}}};
var N=function(P){E="";
P.trigger(jQuery.Event("keyup",{which:F.KeyCodeBackspace}));
H=[]
};
var O=function(Q){var P=false;
$(Q).parents("div").not(".w-dropdown").not(".rr").each(function(R){if($(this).css("overflow")==="auto"||$(this).css("overflow")==="hidden"||$(this).css("overflow-y")==="scroll"){P=true;
return false
}else{if(R>4){return false
}}});
return P
};
var K=function(R){var P=undefined;
function Q(S){$(R).parents("div").not(".w-dropdown").not(".rr").each(function(T){if($(this).css("overflow-y")===S){P=$(this);
return false
}else{if(T>4){return false
}}})
}Q("scroll");
if(!P){Q("hidden")
}if(!P){Q("auto")
}return P
};
var M=function(Q,S,W){var P,U,X;
var V=null;
var T=0;
W||(W={});
var R=function(){T=W.leading===false?0:new Date;
V=null;
X=Q.apply(P,U)
};
return function(){var Y=new Date;
if(!T&&W.leading===false){T=Y
}var Z=S-(Y-T);
P=this;
U=arguments;
if(Z<=0){clearTimeout(V);
V=null;
T=Y;
X=Q.apply(P,U)
}else{if(!V&&W.trailing!==false){V=setTimeout(R,Z)
}}return X
}
};
$(document).click(function(P){if($(P.target).parents(".w-dropdown").length===0&&!$(P.target).hasClass("w-dropdown")){L()
}});
$(window).resize(function(){L()
});
return{initDisplay:function(P){if(P.isInitDone){return 
}var W=P.isActionEnabled;
var Q=P.isAWDisabled;
var U=$(P);
var V=U.children("input");
var T=U.children(".w-dropdown-items").children(".w-dropdown-item[data-selected]").html();
var S=V.attr("value");
U.children(".w-dropdown-selected").html(T);
U.attr("index",S);
U.children(".w-dropdown-items").children(".w-dropdown-item[index="+S+"]").addClass("is-bold");
if(Q){U.children(".w-dropdown-selected,.w-dropdown-pic-ct").addClass("w-dropdown-disabled");
U.children(".w-dropdown-pic-ct").children(".w-dropdown-pic").addClass("w-dropdown-disabled")
}var R=this.initSizing(U);
U.children(".w-dropdown-items").append(R);
if(D.IsIE7&&ariba.Util.isAW5()){U.find(".w-dropdown-items").width(size+33)
}this.ddHoverInit(U);
this.initKeyboardNavigation(U);
this.initFiltering(U);
U.find(".w-dropdown-item[awname*=ApndPlcHolder]").each(function(X){var Y=$(this).attr("awname");
$(this).attr("awname",Y.replace("ApndPlcHolder",$(this).text().trim()))
});
P.isInitDone=true
},isDeferInit:function(T){var R=D.documentElement();
var Q=T;
while(Q!=R){var P=$(Q);
if(P.hasClass("awmenu")){if(Q.style.display=="none"||P.hasClass("is-dnone")){var S=Q.getAttribute("data-deferDropDownInit");
if(S=="true"){return true
}}return false
}Q=Q.parentNode
}return false
},init:function(R,P,S,T){var Q=document.getElementById(T);
Q.id=T;
Q.isActionEnabled=R;
Q.isAWDisabled=P;
Q.isRefresh=S;
Q.isInitDone=false;
A[T]=Q;
if(this.isDeferInit(Q)){Q.isInitDone=false
}else{this.initDisplay(Q)
}},initSizing:function(T){var X=$("#w-dropdown-sizer");
var U=T.children(".w-dropdown-items").children(".w-dropdown-item");
var P=T.css("min-width");
if(P&&P!=="auto"){X.css("min-width",P)
}X.append(U);
var Y=10,W=26,R=28,S=1,V=1;
var Z=ariba.AWWidgets.DropDown.sizeWithOverflowing(T,X);
var Q=function(){var a=T.parent().hasClass("w-dropdown-fxd-size");
if(ariba.AWWidgets.DropDown.useJSWidth(T,X)||a){T.find(".w-dropdown-selected").width(Z-R-S+1);
T.width(Z+(2*Y)+1)
}var b=(parseInt(T.css("min-width").replace("px","")));
if(b===0){T.css("min-width",Z+"px")
}T.children(".w-dropdown-items").width(Z+(2*Y)-V)
};
G.registerRefreshCallback(Q.bind(this));
G.registerOnWindowResize(Q.bind(this));
if(Z===0){X.children().each(function(a,b){if($(this).width()>Z){Z=$(this).width()
}});
if(ariba.AWWidgets.DropDown.useJSWidth(T,X)){X.width(Z);
Z=ariba.AWWidgets.DropDown.sizeWithOverflowing(T,X);
X.width("auto");
T.children(".w-dropdown-selected").width(Z);
T.children(".w-dropdown-selected").width(Z-R-S-Y-10-1)
}}else{Q()
}X.empty();
return U
},isOverflowing:function(Q,P){return Q.offset().left+P>$("body").offset().left+$("body").width()&&P>($("body").offset().left+$("body").width()*0.5)
},sizeWithOverflowing:function(T,S){var R=T.parent().hasClass("w-dropdown-fxd-size");
var Q=R?T.parent().width():S.width();
var P=0;
if(ariba.AWWidgets.DropDown.isOverflowing(T,Q)){P=(($("body").offset().left+$("body").width())-$(T).offset().left)*0.9
}return(P>200)?P:Q
},useJSWidth:function(S,Q){var P=ariba.AWWidgets.DropDown.dropdownWidth(S,Q);
var R=ariba.AWWidgets.DropDown.overflowWidth(S);
return ariba.AWWidgets.DropDown.isOverflowing(S,P)&&R>0
},overflowWidth:function(P){return(($("body").offset().left+$("body").width())-$(P).offset().left)*0.9
},dropdownWidth:function(R,Q){var P=R.parent().hasClass("w-dropdown-fxd-size");
return P?R.parent().width():Q.width()
},ddHoverInit:function(P){P=P[0];
if(P.isAWDisabled){$("#"+P.id).find(".w-dropdown-pic").addClass("w-dropdown-disabled")
}},initKeyboardNavigation:function(P){if(P[0]){$(P[0]).keydown(function(R){var S=R.which||R.charCode||R.keyCode;
if(S==F.KeyCodeArrowUp||S==F.KeyCodeArrowDown){return ariba.AWWidgets.DropDown.handleArrowUpDownEvents(R,$(this))
}else{if(S===F.KeyCodeEscape){N(P);
L();
return false
}else{if(S===F.KeyCodeEnter){var T=$(this).find('.w-dropdown-item[index="'+B+'"]');
var Q=T.attr("bh");
if(Q=="DDI"){ariba.AWWidgets.DropDown.dropDownMenuAction(T,null)
}else{if(Q=="DDIA"){ariba.AWWidgets.DropDown.dropDownMenuActionExt(T,null)
}}return false
}else{if(S===F.KeyCodeBackspace){if(E.length>0){E=E.substring(0,E.length-1)
}return false
}}}}return true
});
$(P[0]).keypress(function(Q){if(/[a-zA-Z0-9-_]/.test(String.fromCharCode(Q.which||Q.charCode||Q.keyCode))){E+=String.fromCharCode(Q.which||Q.charCode||Q.keyCode)
}return true
})
}},initFiltering:function(P){P.focus(function(Q){$(this).find(".w-dropdown-items .w-dropdown-item[bh]").each(function(S){var R={text:$(this).text(),elem:$(this)};
H.push(R)
})
});
$(P[0]).keyup(M(function(T){if(!(/[a-zA-Z0-9-_\b]/.test(String.fromCharCode(T.which||T.charCode||T.keyCode)))){return 
}if(H&&H.length>0){P.find(".w-dropdown-item").removeClass("is-bold");
for(var Q in H){var S=H[Q];
var V=S.text.trim().toLowerCase().indexOf(E.toLowerCase());
var R="";
if(E.length>0&&V===0){if(!J){ariba.AWWidgets.DropDown.openDropdown(P)
}var U=S.elem.text();
var R=ariba.AWWidgets.DropDown.highlight(U,E,"HighlightBegin","HighlightEnd");
R=$("<div/>").text(R).html();
R=R.replace("HighlightBegin","<strong>");
R=R.replace("HighlightEnd","</strong>");
if(S.elem.attr("bh")==="DDIA"){S.elem.children().html(R)
}else{S.elem.html(R)
}S.elem.fadeIn("slow")
}else{if(E.length>0&&(V>0||V===-1)){if(S.elem.attr("bh")==="DDIA"){S.elem.children().text(S.elem.text())
}else{S.elem.text(S.elem.text())
}S.elem.hide()
}else{if(S.elem.attr("bh")==="DDIA"){S.elem.children().text(S.elem.text())
}else{S.elem.text(S.elem.text())
}S.elem.fadeIn("slow")
}}}ariba.AWWidgets.DropDown.adjustHeight(P)
}},400));
P.blur(function(Q){N(P);
if(D.IsIE&&C){Q.preventDefault();
Q.stopImmediatePropagation();
return false
}L()
})
},highlight:function(T,R,P,S){function Q(U){return(U+"").replace(/([\\\.\+\*\?\[\^\]\$\(\)\{\}\=\!\<\>\|\:])/g,"\\$1")
}if(P!==undefined&&S!==undefined){return String(T).replace(new RegExp("("+Q(R)+")","i"),P+"$&"+S)
}return String(T).replace(new RegExp("("+Q(R)+")","i"),"<strong>$&</strong>")
},adjustHeight:function(U){var S=U.find(".w-dropdown-items");
S.removeClass("w-dropdown-slide-down").removeClass("w-dropdown-slide-up").css("height","");
var X=U.find(".w-dropdown-item:visible");
var R=S.outerHeight();
var Y=$(window).height()-(U.offset().top-($(document).scrollTop()))-15;
var W=S.offset().top-$(document).scrollTop();
var T;
if(X.size){T=R/X.size()
}else{T=R/X.length
}if((R>Y)&&Y>(T*4)){var a=0;
if(!S.size){a=S.width()
}S.css("height",Y-T).addClass("w-dropdown-slide-down");
if(!S.size){var V=S.width();
if(V<a){var Q=(parseInt(U.css("min-width").replace("px","")));
S.css("min-width",(Q+19)+"px")
}}}else{if((R>Y)){var P=W>R;
var Z=P?R:(W-T);
var a=0;
if(!S.size){a=S.width()
}S.css("height",Z).addClass("w-dropdown-slide-up");
if(!S.size){var V=S.width();
if(V<a){var Q=(parseInt(U.css("min-width").replace("px","")));
S.css("min-width",(Q+19)+"px")
}}}else{S.addClass("w-dropdown-slide-down");
S.css("height",R)
}}this.dealWithClipping(U,S)
},openDropdown:function(Q){var R=!Q.hasClass("u-open");
$(document).find(".w-dropdown.u-open").removeClass("u-open");
if(!Q[0].isAWDisabled){var P=Q.find(".w-dropdown-items");
if(D.IsIE7){P.removeClass("w-dropdown-ie7").addClass("w-dropdown-ie7")
}J=true;
Q.addClass("u-open");
Q.attr("aria-expanded","true");
if(R){ariba.AWWidgets.DropDown.adjustHeight(Q)
}}},dealWithClipping:function(S,Q){Q.removeClass("w-dropdown-items-clipped");
if(O(Q)){Q.addClass("w-dropdown-items-clipped");
var P=K(Q)[0];
var R=function(){ddt=((S.offset().top+S.outerHeight())-$(document).scrollTop());
ddl=((S.offset().left)-$(document).scrollLeft());
Q.css("top",ddt+"px");
Q.css("left",ddl+"px")
};
$(P).scroll(R);
$(document).scroll(R);
R()
}},dropDownMenuAction:function(V,Q){var P=$(V);
var R=P.parent();
R.children(".w-dropdown-item").removeClass("is-bold");
P.addClass("is-bold");
var S=$(A[R.attr("data-dropdownid")]);
S.attr("index",$(V).attr("index"));
S.find(".w-dropdown-selected").html($(V).html());
S.children("input").attr("value",$(V).attr("index"));
S.removeClass("u-open");
S.attr("aria-expanded","false");
S.removeAttr("aria-activedescendant");
J=false;
B=-1;
if(S[0].isRefresh||S[0].isActionEnabled){var U=S.closest("form").attr("id");
var T=S.children("input").attr("name");
ariba.Handlers.textFieldRefresh(U,T)
}return false
},dropDownMenuActionExt:function(S,P){var Q=$(S).find('a[bh="HL"]');
if(Q.length>0){var R=D.lookupFormId(S);
return ariba.Handlers.tagOnClick(Q[0],R,undefined,undefined,P,undefined,undefined)
}return false
},handleArrowUpDownEvents:function(P,T){var Y=P.which||P.charCode||P.keyCode;
var S=Y==F.KeyCodeArrowDown;
var X=Y==F.KeyCodeArrowUp;
var V=P.altKey;
B=T.find(".w-dropdown-item[data-selected]").attr("index");
var W=T.find(".w-dropdown-items");
if(S&&!J){ariba.AWWidgets.DropDown.openDropdown(T);
var Z=T.find('.w-dropdown-item[index="'+B+'"]');
W.scrollTop(W.scrollTop()+Z.position().top);
T.attr("aria-activedescendant",Z.attr("id"))
}else{if(V&&X){N(T);
L()
}else{var U=[];
T.find(".w-dropdown-item:visible").each(function(a){if($(this).attr("index")!==undefined){U.push(parseInt($(this).attr("index")))
}});
nextItem=ariba.AWWidgets.DropDown.nextVisibleItem(B,U,S);
if((S&&nextItem<=U.length)||nextItem>=0&&!S){B=U[nextItem];
+"";
var Z=T.find('.w-dropdown-item[index="'+B+'"]');
T.find(".w-dropdown-item").removeAttr("data-selected").removeClass("is-bold");
Z.attr("data-selected",true).addClass("is-bold");
T.attr("aria-activedescendant",Z.attr("id"));
if(!ariba.AWWidgets.DropDown.isItemVisible(W,Z)){var R=U.length;
if(nextItem==0||nextItem==(R-1)){W.scrollTop(W.scrollTop()+Z.position().top)
}else{var Q=S?0+Z.height():0-Z.height();
W.scrollTop(W.scrollTop()+Q)
}}}}}return false
},nextVisibleItem:function(T,Q,P){var U=parseInt(T);
var S=Q.indexOf(U);
var R=Q.length;
if(S>=0){return P?(((S+1)<R)?(S+1):0):((S-1)>=0?(S-1):(R-1))
}else{return 0
}},isItemVisible:function(P,S){var U=P.offset().top;
var R=U+P.height();
var T=S.offset().top;
var Q=T+S.height();
return((Q<=R)&&(T>=U))
}}
}()),EOF:0};
G.registerBehaviors({DDM:{mousedown:function(M,K){var L=$(M);
G.cancelBubble(K);
L.focus();
ariba.AWWidgets.DropDown.openDropdown(L);
if(D.IsIE&&L.outerWidth()<=K.clientX){C=true
}else{C=false
}return false
},focusin:function(L,K){$("td.ffi").has("div.required").next().find("div").attr("aria-required","true")
},click:function(L,K){G.cancelBubble(K)
}},DDI:{mousedown:function(L,K){G.cancelBubble(K);
return ariba.AWWidgets.DropDown.dropDownMenuAction(L,K)
}},DDIA:{mousedown:function(L,K){G.cancelBubble(K);
return ariba.AWWidgets.DropDown.dropDownMenuActionExt(L,K)
}}});
return I
}();
var EVENTS=["click","keydown"];
function checkStorageAccess(){var A=localStorage.getItem("SAA");
if(A!==null){handleStorageAccess(A==="true");
return 
}if(document.hasStorageAccess){document.hasStorageAccess().then(handleStorageAccess,hasStorageAccessFailed)
}else{console.log("Storage access API is not supported in this browser")
}}function hasStorageAccessFailed(A){console.log("Error checking storage access"+A)
}function handleStorageAccess(A){if(A){console.log("Storage access is already granted")
}else{listenForUserGesture()
}}function listenForUserGesture(){for(var A=0;
A<EVENTS.length;
A++){document.addEventListener(EVENTS[A],requestStorageAccess)
}}function requestStorageAccess(){console.log("User gesture detected. Requesting storage access...");
document.requestStorageAccess().then(handleRequestStorageSuccess,handleStorageAccessFailure)
}function removeEventListeners(){for(var A=0;
A<EVENTS.length;
A++){document.removeEventListener(EVENTS[A],requestStorageAccess)
}}function handleRequestStorageSuccess(){console.log("Storage access granted");
localStorage.setItem("SAA","true");
removeEventListeners()
}function handleStorageAccessFailure(A){console.log("Storage access request failed"+A);
removeEventListeners()
}document.addEventListener("DOMContentLoaded",function(){checkStorageAccess()
});