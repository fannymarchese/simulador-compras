ariba.Community=function(){if((typeof ENABLE_COMMUNITY==="undefined")||!ENABLE_COMMUNITY){return 
}var P="";
var J=ariba.Dom;
var N=ariba.Util;
var Q=ariba.Event;
var E=ariba.Request;
var L="MSIE 5.0";
var I="wCommunityPaneHidden";
var O="wCommunityPaneShown";
var M="250";
var K="52";
var D="85";
var C=function(R,Y){var V={};
if(R){for(var S=0;
S<R.length;
S++){var W=R[S];
var U=W.split(":");
if(U){var T;
var W;
if(U.length==1){T="misc";
W=U[0]
}else{T=U[0];
W=U[1]
}if(!Y){W=T+":"+W
}var X=V[T];
if(!X){X=[];
V[T]=X
}X.push(W)
}}}return V
};
var G=function(U){var S;
var R=[];
if(U.getElementsByClassName){S=U.getElementsByClassName("_community_context");
for(var T=0;
T<S.length;
T++){R.push(S[T])
}}else{R=J.findChildrenUsingPredicate(U,function(V){return V.className&&V.className.indexOf("_community_context")>=0
})
}return R
};
var B=function(S){S=S.replace(/\s\s+/g," ");
var T=[];
var R=S.split(",");
for(var U=0;
U<R.length;
U++){if(typeof String.prototype.trim!=="function"){R[U]=N.strTrim(R[U])
}else{R[U]=R[U].trim()
}if(R[U].length>0){T.push(R[U])
}}return T
};
var F=function(V){var S={},U=[],T=0,R=V.length;
for(;
T<R;
++T){if(!S[V[T]]){S[V[T]]=true;
U.push(V[T])
}}return U
};
var H=function(R){var T="";
for(var S=0;
S<R.length;
S++){if(T.length==0){T=R[S]
}else{T=T.concat(",",R[S])
}}return T
};
var A={getCommunityTags:function(S){if(!S){S=J.documentElement()
}var U=G(S);
var T;
var X="";
for(var V=0;
V<U.length;
V++){var W=U[V];
var R=W.innerHTML;
if(X.length==0){X=R
}else{X=X.concat(",",R)
}}T=B(X);
T=F(T);
return T
},getCommunityTagsCSV:function(R){if(!R){R=J.documentElement()
}var T;
var S=A.getCommunityTags(R);
T=H(S);
return T
},gotoCommunityWithContext:function(R,S){A.gotoCommunity(R,S,true)
},gotoCommunityNoContext:function(R,S){A.openCommunityWindow(R,S,false)
},gotoCommunity:function(W,X,U){var S="";
if(U){var V="";
var R=0;
var T=A.getCommunityTags(J.documentElement());
if(T){R=T.length
}if(T){V=H(T)
}S+='<input name="ctxtTags" value="'+V+'" type="hidden"/>'
}A.openCommunityWindow(W,X,S)
},openDocWin:function(R){return this.openWindow("","CommunityDocWin",R)
},getCurrentWindowHeight:function(){return screen.height
},openCommunityWindow:function(T,Y,R){if(P&&!P.closed&&P.location){P.close()
}var W=new RegExp("heights*=s*[0-9]+","g");
var S="height="+A.getCurrentWindowHeight();
if(W.test(Y)===true){Y=Y.replace(W,S)
}P=A.openDocWin(Y);
var U="";
if(R!=""){U='<html><body onLoad="document.form1.submit();"><form method="post" action="'+T+'" id="form1" name="form1">'+R+"</form></body>"
}else{U='<html><body onLoad="document.form1.submit();"><form method="post" action="'+T+'" id="form1" name="form1"></form></body>'
}try{P.document.write(U)
}catch(V){if(P){P.close()
}P=A.openDocWin(null);
if(P){P.document.write(U)
}}P.document.close();
if(P.focus){if(J.IsFF){function X(){P.focus()
}setTimeout(X)
}else{P.focus()
}}},getCommunityContextObject:function(T){var R=A.getCommunityTags(J.documentElement());
var S=C(R,T);
return S
},viewCommunityContext:function(){var R=J.openWindow("","awcommunitycontext","resizable=yes,height=660,width=850");
if(!R){return 
}var W=A.getCommunityContextObject(true);
var T="";
var V=["app","page","activity","domainObject","av"];
var U={};
var S;
for(S=0;
S<V.length;
S++){Y=V[S];
if(W.hasOwnProperty(Y)){U[Y]=true;
var X=H(W[Y]);
T=T.concat("<tr><td class='tableBody'>",Y,"</td><td class='tableBody'>",X,"</td></tr>")
}}for(var Y in W){if(!U[Y]&&W.hasOwnProperty(Y)){var X=H(W[Y]);
T=T.concat("<tr><td class='tableBody'>",Y,"</td><td class='tableBody'>",X,"</td></tr>")
}}R.document.write("<html><head><title>View CommunityContext</title></head><body><h2>View CommunityContext</h2><table><tbody><tr><th class='tableHead' align='left'> Name </th><th class='tableHead' align='left'> Value </th></tr>"+T+"</tbody></body></html>");
R.document.close();
R.focus()
},passCommunityTags:function(){var S=J.getElementById("communityContentIframe");
if(S){var T=A.getCommunityTagsCSV(J.documentElement());
if(T!=undefined){var R=S.src;
if(R.indexOf("#")==-1){R=R+"#"+T
}else{R=R.substring(0,R.indexOf("#"));
R=R+"#"+T
}S.src=R
}}},gotoDoc:function(S,h,g,W,Z,a,d,X,f,U,T){if(P&&!P.closed&&P.location){P.close()
}P=this.openDocWin(T);
if(!P){return 
}var R="";
var V=f.split(",");
for(var Y=0;
Y<V.length;
Y++){R+='<input name="ft" value="'+V[Y]+'" type="hidden"/>'
}var c='<html><body onLoad="document.form1.submit();"><form method="post" action="'+S+'" id="form1" name="form1"><input name="ss" value="'+h+'" type="hidden"/><input name="doc" value="'+g+'" type="hidden"/><input name="ut" value="'+W+'" type="hidden"/><input name="un" value="'+Z+'" type="hidden"/><input name="rn" value="'+a+'" type="hidden"/><input name="ul" value="'+d+'" type="hidden"/><input name="anId" value="'+X+'" type="hidden"/>'+R+'<input name="area" value="'+U+'" type="hidden"/></form></body>';
try{P.document.write(c)
}catch(b){if(P){P.close()
}P=this.openDocWin(null);
if(P){P.document.write(c)
}else{}}if(P){P.document.close();
if(P.focus){P.focus()
}}},openWindow:function(U,R,T){var S=null;
try{if(!S||S.closed){S=window.open(U,R,T);
if(navigator.appVersion.indexOf(L)!=-1||ariba.Dom.isNetscape){S.focus()
}else{if(ariba.Dom.IsIE6){function X(){S.focus()
}setTimeout(X)
}}}else{if(navigator.appVersion.indexOf(L)!=-1||ariba.Dom.isNetscape){S.focus();
S.location.href=U
}else{S.close();
S=window.open(U,R,T)
}}}catch(V){function W(){alert(J.AWOpenWindowErrorMsg)
}setTimeout(W,100)
}return S
},showInSituFrame:function(){var R=J.getElementById("InSituContentPane");
if(R){R.className="wCommunityPaneShown";
if(document.documentElement.clientWidth<SCREEN_RESOLUTION_WIDTH){R.style.display="inline";
R.style.visibility="visible"
}else{R.style.visibility="visible";
R.style.display="block"
}}},hideInSituFrame:function(){var S=J.getElementById("InSituContentPane");
var R=J.getElementById("insitumain");
if(S){S.className="wCommunityPaneHidden";
S.style.display="none";
S.style.visibility="hidden"
}if(R){R.width="0"
}},showInSituElement:function(R){var S=J.getElementById(R);
if(S){S.className="is-block"
}},showInSituElementInline:function(R){var S=J.getElementById(R);
if(S){S.className="is-iblock"
}},hideInSituElement:function(R){var S=J.getElementById(R);
if(S){S.className="is-dnone"
}},setInSituIFrameHeight:function(){var T=J.getElementById("communityContentIframe");
var S=J.getElementById("UIPreferencesBannerDiv");
var R=J.getElementById("UIPreferencesBannerDivAW5");
if(T){if(S||R){T.className="aucIframeExpanded a-community-frameDashboard";
T.height=document.documentElement.clientHeight-D
}else{T.height=document.documentElement.clientHeight-K
}}},updateCookie:function(R){document.cookie="insitu=isCollapsed:"+R+"|winWidth:"+document.documentElement.clientWidth+"|winHeight:"+document.documentElement.clientHeight+"; path=/"
},expandInSitu:function(R){A.showInSituFrame();
A.showInSituElement("insituonexpand");
A.hideInSituElement("insituoncollapse");
if(R){A.updateCookie(0)
}A.setInSituIFrameHeight()
},collapseInSitu:function(R){A.hideInSituFrame();
A.hideInSituElement("insituonexpand");
A.showInSituElementInline("insituoncollapse");
if(R){A.updateCookie(1)
}},isInSituOverLappedOnPage:function(){var T=false;
var S=document.body.scrollWidth>document.body.clientWidth;
var U=J.getElementById("InSituContentPane");
if(U&&U.style.visibility==="visible"){var R=document.body.offsetWidth-(U.offsetLeft+M);
T=(R<0)
}return S||T
},resizeCommunityContentIframe:function(){var R=document.documentElement.clientWidth;
A.setInSituIFrameHeight();
if(IN_SITU_COLLAPSED_BY_USER||(R<SCREEN_RESOLUTION_WIDTH)){A.collapseInSitu()
}else{A.expandInSitu()
}if(A.isInSituOverLappedOnPage()){A.collapseInSitu()
}},setInSituFramePrams:function(R){Q.registerRefreshCallback(function(){A.setInSituIframeSrcUrl(R)
})
},setInSituIframeSrcUrl:function(S){var Z=document.getElementById("communityContentIframe");
var Y="&overlapped=";
var V="&lessthanMinWidth=";
var a="&collapsed_by_user=";
var U="&winWidth=";
var W="&winHeight=";
var R="true";
var T="";
var X="";
if(Z){T=U+document.documentElement.clientWidth+W+document.documentElement.clientHeight;
if(document.documentElement.clientWidth<1280){T=T+V+R
}else{if(A.isInSituOverLappedOnPage()){T=T+Y+R
}}if(IN_SITU_COLLAPSED_BY_USER){T=T+a+R
}var b=A.getCommunityTagsCSV(J.documentElement());
if(b!=undefined){X="#"+b
}Z.src=S+T+X;
A.resizeCommunityContentIframe()
}},EOF:0};
Q.addEvent(window,"onresize",A.resizeCommunityContentIframe);
return A
}();