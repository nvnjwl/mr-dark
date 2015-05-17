```
<!-- BEGIN switch_user_logged_in -->
<div id="pun-visit" class="clearfix">
<ul>
<!-- BEGIN switch_plus_menu -->
<li>
<script type="text/javascript">
//<![CDATA[
var url_favourite = '{switch_user_logged_in.U_FAVOURITE_JS_PLUS_MENU}';
var url_newposts = '{U_NEWPOSTS_JS_PLUS_MENU}';
var url_egosearch = '{U_EGOSEARCH_JS_PLUS_MENU}';
var url_unanswered = '{U_UNANSWERED_JS_PLUS_MENU}';
var url_watchsearch = '{U_WATCHSEARCH_JS_PLUS_MENU}';
var url_tellfriend = '{U_TELLFRIEND_JS_PLUS_MENU}';
insert_plus_menu_new('f{FORUM_ID}&amp;t={TOPIC_ID}', '{JS_SESSION_ID}', {
JS_AUTH_FAVOURITES
});
//]]>



Unknown end tag for &lt;/script&gt;




Unknown end tag for &lt;/li&gt;


<!-- END switch_plus_menu -->
<li>
<a href="{U_SEARCH_NEW}">{L_SEARCH_NEW}

Unknown end tag for &lt;/a&gt;




Unknown end tag for &lt;/li&gt;


<li>
<a href="{U_SEARCH_SELF}">{L_SEARCH_SELF}

Unknown end tag for &lt;/a&gt;




Unknown end tag for &lt;/li&gt;


<!-- BEGIN watchtopic -->
<li>{S_WATCH_TOPIC}

Unknown end tag for &lt;/li&gt;


<!-- END watchtopic -->


Unknown end tag for &lt;/ul&gt;


<p>{LOGGED_AS}. {LAST_VISIT_DATE}

Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;


<!-- END switch_user_logged_in -->
<!-- BEGIN switch_user_logged_out -->
<div id="pun-visit">
<p>{L_NOT_CONNECTED} {L_LOGIN_REGISTER}

Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;


<!-- END switch_user_logged_out -->
<div class="pun-crumbs noprint">
<a href="{U_INDEX}">{L_INDEX}

Unknown end tag for &lt;/a&gt;

{NAV_CAT_DESC}&nbsp;&raquo;&nbsp;
<strong>
<a href="{TOPIC_URL}">{TOPIC_TITLE}

Unknown end tag for &lt;/a&gt;




Unknown end tag for &lt;/strong&gt;




Unknown end tag for &lt;/div&gt;


<p class="posting">
<span id="twitter_btn" style="margin-left: 6px; ">
<a href="http://twitter.com/share" class="twitter-share-button" data-count="horizontal">Tweet

Unknown end tag for &lt;/a&gt;


<script type="text/javascript" src="http://platform.twitter.com/widgets.js">

Unknown end tag for &lt;/script&gt;




Unknown end tag for &lt;/span&gt;


<span id="fb_likebtn" style="margin-left: 6px; ">
<iframe src="http://www.facebook.com/plugins/like.php?href={FORUM_URL}{TOPIC_URL}&amp;layout=button_count&amp;show_faces=false&amp;width=450&amp;action=like&amp;colorscheme=light&amp;height=21"
scrolling="no" frameborder="0" style="border:none; overflow:hidden; width:auto; height:21px;"
allowTransparency="true">

Unknown end tag for &lt;/iframe&gt;




Unknown end tag for &lt;/span&gt;


<span style="margin-left: 6px; ">
<g:plusone size="medium">

Unknown end tag for &lt;/plusone&gt;




Unknown end tag for &lt;/span&gt;


<a class="btn btn-warning addthis_button" href="http://www.addthis.com/bookmark.php?v=250&amp;pubid=kalenv"
data-original-title="Chia sẻ bài viết đến các mạng xã hội" style="float: right;">Chia sẻ

Unknown end tag for &lt;/a&gt;




Unknown end tag for &lt;/p&gt;


<div class="main paged">
<div class="paged-head clearfix">
<!-- BEGIN topicpagination -->
<p class="paging">{PAGINATION}

Unknown end tag for &lt;/p&gt;


<!-- END topicpagination -->
<p class="posting">
<!-- BEGIN switch_user_authpost -->
<a href="{U_POST_NEW_TOPIC}" rel="nofollow" class="btn btn-large btn-danger i_post" data-original-title="Gửi một chủ đề khác"><i class="i-white i-plus-sign">

Unknown end tag for &lt;/i&gt;

 Gửi bài mới

Unknown end tag for &lt;/a&gt;


<!-- END switch_user_authpost -->&nbsp;&nbsp;
<!-- BEGIN switch_user_authreply -->
<a href="{U_POST_REPLY_TOPIC}" class="btn btn-large btn-success i_reply" data-original-title="Trả lời chủ đề này"><i class="i-white i-comment">

Unknown end tag for &lt;/i&gt;

 Trả lời

Unknown end tag for &lt;/a&gt;


<!-- END switch_user_authreply -->


Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;

{POLL_DISPLAY}
<div class="main-head clearfix">
<p class="h2">
<a href="{U_VIEW_OLDER_TOPIC}">{L_VIEW_PREVIOUS_TOPIC}

Unknown end tag for &lt;/a&gt;

&nbsp;
<a href="{U_VIEW_NEWER_TOPIC}">{L_VIEW_NEXT_TOPIC}

Unknown end tag for &lt;/a&gt;

&nbsp;
<a href="#bottom">{L_GOTO_DOWN}

Unknown end tag for &lt;/a&gt;

&nbsp;&nbsp; {L_MESSAGE} [{PAGE_NUMBER}]

Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;


<div class="main-content-topic">
<!-- BEGIN postrow -->
<div class="main-content-topic">
<!-- BEGIN displayed -->
<span class="baigui" style="display:none">{postrow.displayed.COUNT_POSTS}

Unknown end tag for &lt;/span&gt;


<div id="p50" class="posthead clearfix" style="background: #FBFBFB;float: left; width: 746px; margin-bottom: -11px;margin-left: 21px;margin-top: 10px;" align="center"><p class="h2" align="center"><a href="http://www.onepiecefm.net{TOPIC_URL}">{postrow.displayed.POST_SUBJECT}

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/p&gt;



Unknown end tag for &lt;/div&gt;


<div class="post" {postrow.displayed.THANK_BGCOLOR}>
<a name="{postrow.displayed.U_POST_ID}">

Unknown end tag for &lt;/a&gt;



<div class="user"><div class="blast1">

Unknown end tag for &lt;/div&gt;

<div class="blast">  <marquee behavior="scroll" onmouseover="this.stop()" onmouseout="this.start()" scrollamount="1" scrolldelay="20" direction="left" truespeed="truespeed" style="width: 640px;margin-left: -8px;">

<!-- BEGIN profile_field -->
<span class="khung">  <span class="c3stats"><span class="coin"><p>{postrow.displayed.profile_field.LABEL}{postrow.displayed.profile_field.CONTENT}


Unknown end tag for &lt;/p&gt;

  

Unknown end tag for &lt;/span&gt;

  

Unknown end tag for &lt;/span&gt;

  

Unknown end tag for &lt;/span&gt;

      <!-- END profile_field -->


Unknown end tag for &lt;/marquee&gt;



Unknown end tag for &lt;/div&gt;



<script type="text/javascript">$(".coin").each(function(){$(this).html($(this).find("div:contains('Status:') div").html());});});

Unknown end tag for &lt;/script&gt;



<script type="text/javascript">$(function(){$(".khung:contains('Liked')").css('display','none');$(".khung:contains('Tham Gia')").css('display','none');$(".khung:contains('Birthday')").css('display','none');$(".khung:contains('Danh vọng')").css('display','none');$(".khung:contains('Bài viết')").css('display','none');$(".khung:contains('Tớ đang')").css('display','none');$(".khung:contains('Tài sản')").css('display','none');$(".user-info:contains('Status:')").css('display','none');$(".vipprovip:contains('gender')").css('display','none');$(".vipprovip:contains('Châm ngôn sống')").css('display','none');$(".vipprovip:contains('Posts')").css('display','none');$(".vipprovip:contains('points')").css('display','none');$(".vipprovip:contains('Đến từ')").css('display','none');$(".vipprovip:contains('Join date')").css('display','none');$(".vipprovip:contains('Kỉ luật')").css('display','none');$(".vipprovip:contains('Thanked')").css('display','none');$(".vipprovip:contains('avatar-dulieu')").css('display','none');$(".vipprovip:contains('Tài sản')").css('display','none');$(".taisanmi:contains('Status')").css('display','none');$(".taisanmi:contains('gender')").css('display','none');$(".taisanmi:contains('Châm ngôn sống')").css('display','none');$(".taisanmi:contains('Posts')").css('display','none');$(".taisanmi:contains('points')").css('display','none');$(".taisanmi:contains('Đến từ')").css('display','none');$(".taisanmi:contains('Join date')").css('display','none');$(".taisanmi:contains('Kỉ luật')").css('display','none');$(".taisanmi:contains('Thanked')").css('display','none');$(".taisanmi:contains('avatar-dulieu')").css('display','none');$(".taisanmi:contains('Tớ đang')").css('display','none');})

Unknown end tag for &lt;/script&gt;


<script type="text/javascript">
document.getElementById('c3stats').innerHTML=document.getElementById('c3stats').innerHTML.replace(/Status/,'=>').replace(/Status/,'=>').replace(/Status/,'=>').replace(/Users with a birthday within the next (.+) days/,'Thành viên có sinh nhật trong $1 ngày kế tiếp').replace(/No users are having a birthday in the upcoming (.+) days/,'Không có thành viên nào có sinh nhật trong $1 ngày kế tiếp');


Unknown end tag for &lt;/script&gt;








<div class="user-ident">
<div class="user-avatar">{postrow.displayed.POSTER_AVATAR}

Unknown end tag for &lt;/div&gt;


<div class="user-basic-info">
<p class="user-name">{postrow.displayed.POSTER_NAME} {postrow.displayed.ONLINE_IMG}

Unknown end tag for &lt;/p&gt;


<p class="user-rank">{postrow.displayed.RANK_IMAGE}

Unknown end tag for &lt;/p&gt;


<p class="user-contact" align="center">{postrow.displayed.PROFILE_IMG} {postrow.displayed.PM_IMG} {postrow.displayed.EMAIL_IMG}

<!-- BEGIN contact_field --> {postrow.displayed.contact_field.CONTENT}<!-- END contact_field -->

Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;



<div class="user-pet"><img alt="pet" onclick="javascript:alert('Đang phát triển')" src="http://i47.servimg.com/u/f47/17/57/92/32/c1410.gif" />

Unknown end tag for &lt;/div&gt;


<div class="user-pet"><div class="huanchuong">
<!-- BEGIN profile_field --><p>{postrow.displayed.profile_field.LABEL} {postrow.displayed.profile_field.CONTENT}

Unknown end tag for &lt;/p&gt;

<!-- END profile_field -->


Unknown end tag for &lt;/div&gt;



Unknown end tag for &lt;/div&gt;




<div style="display:none">
<span class="prone"><div class="user-info" style="display: block;margin-left: 45px;"><span style="white-space:nowrap;"><span style="color:#000000;">
<!-- BEGIN profile_field --><p>{postrow.displayed.profile_field.LABEL} {postrow.displayed.profile_field.CONTENT}

Unknown end tag for &lt;/p&gt;

<!-- END profile_field -->


Unknown end tag for &lt;/span&gt;



Unknown end tag for &lt;/span&gt;

 

Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;

 

Unknown end tag for &lt;/div&gt;



Unknown end tag for &lt;/div&gt;



<div style="clear:both;">

Unknown end tag for &lt;/div&gt;



<div class="postbody" {postrow.displayed.THANK_BGCOLOR}>

<p style="margin-left:-10px" align="center">
<img src="/users/1113/13/44/26/avatars/gallery/thanhn10.png">  

Unknown end tag for &lt;/p&gt;



<div class="hihi"><span class="smallfont" style="font-style: italic;">
<img src="{postrow.displayed.MINI_POST_IMG}" alt="{postrow.displayed.L_MINI_POST_ALT}" title="{postrow.displayed.L_MINI_POST_ALT}" border="0" style="margin-top: -5px;"/>{L_POST_SUBJECT}: {postrow.displayed.POST_SUBJECT} <img src="{postrow.displayed.MINI_TIME_IMG}" alt="" border="0" />{postrow.displayed.POST_DATE}<strong style="float: right; background: #2ebcff;padding: 2px;color: #fff;min-width:15px;height: 15px;font-size: 12px;text-align: center;-webkit-border-radius: 99px;  -moz-border-radius: 99px;  border-radius: 99px;position: relative;top: -2px;">{postrow.displayed.COUNT_POSTS}

Unknown end tag for &lt;/strong&gt;



Unknown end tag for &lt;/span&gt;



Unknown end tag for &lt;/div&gt;


<hr>

<br>
<div class="post-entry">

<div class="entry-content">
<div>
{postrow.displayed.MESSAGE}
<!-- BEGIN switch_attachments -->
<dl class="attachbox">
<dt>{postrow.displayed.switch_attachments.L_ATTACHMENTS}

Unknown end tag for &lt;/dt&gt;


<dd>
<!-- BEGIN switch_post_attachments -->
<dl class="file">
<dt>
<img src="{postrow.displayed.switch_attachments.switch_post_attachments.U_IMG}" />
<!-- BEGIN switch_dl_att -->
<a class="postlink" href="{postrow.displayed.switch_attachments.switch_post_attachments.switch_dl_att.U_ATTACHMENT}">{postrow.displayed.switch_attachments.switch_post_attachments.switch_dl_att.ATTACHMENT}

Unknown end tag for &lt;/a&gt;

{postrow.displayed.switch_attachments.switch_post_attachments.switch_dl_att.ATTACHMENT_DEL}
<!-- END switch_dl_att -->
<!-- BEGIN switch_no_dl_att -->{postrow.displayed.switch_attachments.switch_post_attachments.switch_no_dl_att.ATTACHMENT}
{postrow.displayed.switch_attachments.switch_post_attachments.switch_no_dl_att.ATTACHMENT_DEL}
<!-- END switch_no_dl_att -->


Unknown end tag for &lt;/dt&gt;


<!-- BEGIN switch_no_comment -->
<dd>
<em>{postrow.displayed.switch_attachments.switch_post_attachments.switch_no_comment.ATTACHMENT_COMMENT}

Unknown end tag for &lt;/em&gt;




Unknown end tag for &lt;/dd&gt;


<!-- END switch_no_comment -->
<!-- BEGIN switch_no_dl_att -->
<dd>
<em>
<strong>{postrow.displayed.switch_attachments.switch_post_attachments.switch_no_dl_att.TEXT_NO_DL}

Unknown end tag for &lt;/strong&gt;




Unknown end tag for &lt;/em&gt;




Unknown end tag for &lt;/dd&gt;


<!-- END switch_no_dl_att -->
<dd>({postrow.displayed.switch_attachments.switch_post_attachments.FILE_SIZE})
{postrow.displayed.switch_attachments.switch_post_attachments.NB_DL}

Unknown end tag for &lt;/dd&gt;




Unknown end tag for &lt;/dl&gt;


<!-- END switch_post_attachments -->


Unknown end tag for &lt;/dd&gt;




Unknown end tag for &lt;/dl&gt;


<!-- END switch_attachments -->
<div class="clear">

Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;


<p>{postrow.displayed.EDITED_MESSAGE}

Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;


<img src="/users/2211/12/43/96/album/box-sh10.gif" style="margin-left: 10px">
<p style="padding-bottom: 10px">

Unknown end tag for &lt;/p&gt;


<!-- BEGIN switch_signature -->
<div class="sig-content">{postrow.displayed.SIGNATURE_NEW}

Unknown end tag for &lt;/div&gt;


<!-- END switch_signature -->


<div class="postfoot">
<div style="float: left;margin-top: 1px;">
<!-- BEGIN switch_vote_active -->
<div class="vote vote-button" title="Thích bài viết này">
<!-- BEGIN switch_vote -->
<a target="v{postrow.displayed.U_POST_ID}" href="{postrow.displayed.switch_vote_active.switch_vote.U_VOTE_PLUS}" alt="c3zplus" class="c3zplus lvote"><span style="font: normal 11px Tahoma, Arial, Helvetica, sans-serif;margin-left: -2px; color: #3B5998;">Thích

Unknown end tag for &lt;/span&gt;



Unknown end tag for &lt;/a&gt;


<!-- END switch_vote -->


Unknown end tag for &lt;/div&gt;


<div class="vote vote-button" title="Không thích bài viết này">
<!-- BEGIN switch_vote -->
<a target="v{postrow.displayed.U_POST_ID}" href="{postrow.displayed.switch_vote_active.switch_vote.U_VOTE_MINUS}" alt="c3zminus" class="c3zminus lvote"><span style="font: normal 11px Tahoma, Arial, Helvetica, sans-serif;margin-left: -2px; color: #3B5998;">Không thích

Unknown end tag for &lt;/span&gt;



Unknown end tag for &lt;/a&gt;


<!-- END switch_vote -->

Unknown end tag for &lt;/div&gt;

<div id="v{postrow.displayed.U_POST_ID}" class="loadding" style="display: none"><img src="http://i43.servimg.com/u/f43/16/03/04/56/icon_l12.gif"> Đang Vote (_)^^! 

Unknown end tag for &lt;/div&gt;


<!-- END switch_vote_active -->



Unknown end tag for &lt;/div&gt;


<div class="post-options" style="float: right;margin-top: -2.9px;">
<span class="options-button">{postrow.displayed.MULTIQUOTE_IMG} {postrow.displayed.QUOTE_IMG}<a href="#quickreply" onclick="quick($(this))" class="small_textbutton">Trả lời nhanh

Unknown end tag for &lt;/a&gt;


{postrow.displayed.EDIT_IMG} {postrow.displayed.DELETE_IMG}
{postrow.displayed.REPORT_IMG}

Unknown end tag for &lt;/span&gt;



Unknown end tag for &lt;/div&gt;


<div style="clear:both;">

Unknown end tag for &lt;/div&gt;



Unknown end tag for &lt;/div&gt;



Unknown end tag for &lt;/div&gt;


<div class="main-footp clearfix" style="background: #FBFBFB;float: left; width: 746px; margin-bottom: 10px;margin-left: 21px;margin-top: -11px;" align="center">
<div style="float:left; margin-top:-1px;">
<!-- BEGIN switch_vote_active -->
<iframe name="v{postrow.displayed.U_POST_ID}" class="ajaxvote" style="display:none">

Unknown end tag for &lt;/iframe&gt;


<!-- BEGIN switch_no_bar -->
<span class="c3zvau v{postrow.displayed.U_POST_ID}" title="{postrow.displayed.switch_vote_active.L_VOTE_TITLE}">{postrow.displayed.switch_vote_active.L_VOTE_TITLE}

Unknown end tag for &lt;/span&gt;


<!-- END switch_no_bar -->
<!-- BEGIN switch_bar -->
<span class="c3zvau v{postrow.displayed.U_POST_ID}" title="{postrow.displayed.switch_vote_active.L_VOTE_TITLE}">{postrow.displayed.switch_vote_active.L_VOTE_TITLE}

Unknown end tag for &lt;/span&gt;


<!-- END switch_bar -->
<!-- END switch_vote_active -->

Unknown end tag for &lt;/div&gt;


<div style="float:right;margin-top:-1px;font-weight:bold;text-align:right"><span class="ost"><strong>#1

Unknown end tag for &lt;/strong&gt;

 - <a href="#" onclick="link_bbcode();return false">BBCode

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/span&gt;

 <a target="blank" class="share" href="http://www.addthis.com/bookmark.php?v=250&amp;pub=9xstudio">Chia sẻ

Unknown end tag for &lt;/a&gt;

<div align="center" style="width:600px;display:none; padding-top:6px" >

Unknown end tag for &lt;/div&gt;



Unknown end tag for &lt;/div&gt;

  

Unknown end tag for &lt;/font&gt;



Unknown end tag for &lt;/div&gt;



Unknown end tag for &lt;/span&gt;



Unknown end tag for &lt;/div&gt;


<div class="main-footp clearfix" style="background: #FBFBFB;float: left; width: 746px; margin-bottom: 10px;margin-left: 21px;margin-top: -11px;" align="center">
<div style="float:left; margin-top:-1px;">
<div style="overflow: auto; max-height: 160px;"><div align="center">{postrow.displayed.POSTER_RPG}

Unknown end tag for &lt;/div&gt;



Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;



Unknown end tag for &lt;/div&gt;


<!-- END displayed -->
<!-- END postrow -->


Unknown end tag for &lt;/div&gt;


<div class="main-foot clearfix" style="float: left; width: 776px; margin-bottom: 10px;">
<p class="h2">
<a href="{U_VIEW_OLDER_TOPIC}">{L_VIEW_PREVIOUS_TOPIC}

Unknown end tag for &lt;/a&gt;

&nbsp;
<a href="{U_VIEW_NEWER_TOPIC}">{L_VIEW_NEXT_TOPIC}

Unknown end tag for &lt;/a&gt;

&nbsp;
<a href="#top">{L_BACK_TO_TOP}

Unknown end tag for &lt;/a&gt;

&nbsp;&nbsp; {L_MESSAGE} [{PAGE_NUMBER}]

Unknown end tag for &lt;/p&gt;


<p class="options options-button">
<input type="hidden" name="t" value="{TOPIC_ID}" />
<!-- <input type="hidden" name="sid" value="{S_SID}" />-->
<input type="hidden" name="{SECURE_ID_NAME}" value="{SECURE_ID_VALUE}" />
<!-- BEGIN viewtopic_bottom -->{S_TOPIC_ADMIN}
<!-- END viewtopic_bottom -->


Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;


<a name="bottomtitle">

Unknown end tag for &lt;/a&gt;


<div class="paged-foot clearfix">
<!-- BEGIN topicpagination -->
<p class="paging">{PAGINATION}

Unknown end tag for &lt;/p&gt;


<!-- END topicpagination -->
<p class="posting">
<!-- BEGIN switch_user_authpost -->
<a href="{U_POST_NEW_TOPIC}" rel="nofollow" class="btn btn-large btn-danger i_post" data-original-title="Gửi một chủ đề khác"><i class="i-white i-plus-sign">

Unknown end tag for &lt;/i&gt;

 Gửi bài mới

Unknown end tag for &lt;/a&gt;


<!-- END switch_user_authpost -->&nbsp;&nbsp;
<!-- BEGIN switch_user_authreply -->
<a href="{U_POST_REPLY_TOPIC}" class="btn btn-large btn-success i_reply" data-original-title="Trả lời chủ đề này"><i class="i-white i-comment">

Unknown end tag for &lt;/i&gt;

 Trả lời

Unknown end tag for &lt;/a&gt;


<!-- END switch_user_authreply -->


Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;


<div class="pun-crumbs">
<p class="crumbs">
<a href="{U_INDEX}">{L_INDEX}

Unknown end tag for &lt;/a&gt;

{NAV_CAT_DESC}&nbsp;&raquo;&nbsp;
<strong>
<a href="{TOPIC_URL}">{TOPIC_TITLE}

Unknown end tag for &lt;/a&gt;




Unknown end tag for &lt;/strong&gt;




Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;


<!-- BEGIN switch_forum_rules -->
<div class="main" id="forum_rules">
<div class="main-head clearfix">
<p class="h2">{L_FORUM_RULES}

Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;


<table class="main-content frm">
<tr>
<!-- BEGIN switch_forum_rule_image -->
<td class="logo">
<img src="{RULE_IMG_URL}" />


Unknown end tag for &lt;/td&gt;


<!-- END switch_forum_rule_image -->
<td class="rules entry-content">{RULE_MSG}

Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;




Unknown end tag for &lt;/table&gt;




Unknown end tag for &lt;/div&gt;


<!-- END switch_forum_rules -->
<!-- BEGIN switch_user_logged_in -->
<a name="quickreply">

Unknown end tag for &lt;/a&gt;


<div class="quotenhanh" style="display:none">

Unknown end tag for &lt;/div&gt;


{QUICK_REPLY_FORM}
<!-- END switch_user_logged_in -->
<div id="fb-root">

Unknown end tag for &lt;/div&gt;


<script>(function(d, s, id) {
var js, fjs = d.getElementsByTagName(s)[0];
if (d.getElementById(id)) return;
js = d.createElement(s); js.id = id;
js.src = "//connect.facebook.net/vi_VN/all.js#xfbml=1&appId=342609102468033";
fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));

Unknown end tag for &lt;/script&gt;


<div id="copyright"><div class="module main"><div class="main-head" style="background-color: #000000"><h2><font color="#FFFFFF">Gửi bình luận lên Facebook

Unknown end tag for &lt;/font&gt;



Unknown end tag for &lt;/h2&gt;



Unknown end tag for &lt;/div&gt;

<div class="fb-comments" data-href="http://www.onepiecefm.net{TOPIC_URL}" data-num-posts="2" data-width="770">

Unknown end tag for &lt;/div&gt;



Unknown end tag for &lt;/div&gt;



Unknown end tag for &lt;/div&gt;


<div id="pun-info" class="main">
<div class="main-content">
<div id="stats">
<p>{L_TABS_PERMISSIONS}
<br />{S_AUTH_LIST}

Unknown end tag for &lt;/p&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;



<script type="text/javascript">

function hehe(){
$(".options-button a").addClass("small_textbutton");
$(".options-button a[href*='?thank=']").text("Cảm ơn");
$(".options-button a[href^='/post?p='][href*='&mode=quote']").text("Trích dẫn");
$(".options-button a[href^='/post?p='][href*='&mode=editpost']").text("Sửa");
$(".options-button a[href^='/post?p='][href*='&mode=delete']").text("Xóa");
$(".options-button a[href^='/report?mode=report']").text("Báo cáo");
$(".options-button a[href^='/report?mode=unlock']").text("Mở báo cáo");
$(".options-button a[href^='/report?mode=lock']").text("Chặn báo cáo");
}
hehe();


Unknown end tag for &lt;/script&gt;


<script type="text/javascript" src="/25903.js">

Unknown end tag for &lt;/script&gt;

     <script type="text/javascript" src="/27740.js">

Unknown end tag for &lt;/script&gt;


<script src="{JS_DIR}addthis/addthis_widget.js" type="text/javascript">

Unknown end tag for &lt;/script&gt;


<script type="text/javascript">

function chvote(a, b) {
"Message not voted" == b && (b = "c3zone z vietk 0% (0 vote)");
var d = parseInt(b.split(" ")[3], 10) / 100,
c = parseInt(b.split(" ")[4].substr(1), 10),
b = "Message reputation : " + Math.round(100 * ("c3zplus" == a ? (d * c + 1) / (c + 1) : d * c / (c + 1))) + "% (" + (c + 1) + " vote)";
return votetrans(b)
}
$(".c3zvau").each(function () {
var a = $(this).text();
$(this).html(votetrans(a))
});

function votetrans(a) {
if ("Message not voted" == a) return "<span class='qua'>Hãy là người đầu tiên thích điều này

Unknown end tag for &lt;/span&gt;

";
var b = parseInt(a.split(" ")[3], 10) / 100,
a = parseInt(a.split(" ")[4].substr(1), 10),
d = 0 != b ? "<span class=vop>" + Math.round(b * a) + "+

Unknown end tag for &lt;/span&gt;

" : "",
c = 0 != b && 1 != b ? ' <span style="color:#C2D5E3">|

Unknown end tag for &lt;/span&gt;

 ' : "",
a = 1 != b ? "<span class=vom>" + Math.round(a - b * a) + "-

Unknown end tag for &lt;/span&gt;

" : "",
b = Math.round(100 * b);
return "<span class=no>" + d + c + a + "

Unknown end tag for &lt;/span&gt;

 <span class=qua>Đánh giá: " + b + "%

Unknown end tag for &lt;/span&gt;

"
}
$(".lvote").click(function () {
"c3zplus" == $(this).attr("alt") ? $(this).parent().html("").next().html("") : $(this).parent().html("").prev().html("");
var a = $(this).attr("target"),
b = $(this).attr("alt"),
d = $("." + a).attr("title");
$("#" + a).show();
$("." + a).html(chvote(b, d));
$("#" + a).fadeIn("slow").animate({
opacity: 1
}, 1500).fadeOut("slow", function () {
$("." + a).fadeOut("slow").animate({
opacity: 1
}, 1E3).fadeIn()
});
$("." + $(this).attr("target")).removeAttr("title")
});


Unknown end tag for &lt;/script&gt;


<style>.sig-content{clear:none;max-height:150px;overflow:hidden}
#profile-advanced-details .stats-field{border:1px solid #DDD}
#profile-advanced-details .stats-field legend{background-color:#F4F4F4;border:1px solid #DDD;color:#097BC2;font-size:16px;font-variant:small-caps;font-weight:700;padding:3px 10px 5px}
#profile-advanced-details .message-block{margin-left:63px;border:1px solid #DDD;padding:5px}
#profile-advanced-details .message-footer{margin-right:-3px;padding-bottom:3px;padding-top:10px;text-align:right}
#profile-advanced-details .message-header{border:1px solid #DDD}
#profile-advanced-details .message-footer li:after{content:""!important}
#profile-advanced-details .message-footer li{background:url(http://i48.servimg.com/u/f48/16/58/89/73/view_d10.png) no-repeat scroll 2px center #FCFEE8;border:1px solid #DDD;text-shadow:1px 1px 1px #000;padding:2px 3px 2px 20px}
#profile-advanced-details .message-footer li.last{background:url(http://i48.servimg.com/u/f48/16/58/89/73/remove10.png) no-repeat scroll 2px center #FFEDED;border:1px solid #DDD;padding:2px 3px 2px 20px}
#profile-advanced-right .main-content.center{color:#FFF}
#profile-advanced-details .new-message.bottom{display:none}
.user-pet {min-height:100px;}
.huanchuong{width:180px!important}
.stavote .qua{background-position:5px 50%;background-repeat:no-repeat;border:1px solid #c2d5e3;margin:2px 0 0;padding:5px 8px 5px 25px}
#profile-advanced-details .pagination{background:url(http://i48.servimg.com/u/f48/16/58/89/73/36054_10.png) no-repeat scroll 2px center #E8F9FF;border:1px solid #E4E4E4;float:right!important;margin:5px 0 10px!important;padding:5px 10px 5px 20px}
.lovemes table, .lovemes div, .lovemes hr, .lovemes br, .lovemes embed{display:none!important}
.lovemes {font-weight:bold; font-size:11px}
.lovemes img {vertical-align: middle; max-height:24px}
.rightrecent {text-align: left!important;right: 240px!important;}
.lastcate {width: 145px!important;}
.leftrecent {width: 38%!important;}
.coin {font-weight: bold;color: blue;}
#onlinelist, #stats, #onlinechat {width: 773px;margin-left: -15px;}
.songuoi strong{color:deepSkyBlue;font-family:georgia;text-decoration:none;font-style:normal;font-weight:normal;font-size:38px}
.sobai strong{color:yellowGreen;font-family:georgia;text-decoration:none;font-style:normal;font-weight:normal;font-size:42px}
.mamoi strong{font-family:georgia;text-decoration:none;font-style:normal;font-weight:normal;font-size:20px}


Unknown end tag for &lt;/style&gt;

```