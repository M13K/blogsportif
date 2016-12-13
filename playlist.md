---
layout: page
title: Playlist
permalink: /playlist/
---

<h2>Quelques vidéos</h2>

 <ul>
	{%for playlist in site.data.playlist%}
	
         {{site.baseurl}}{{playlist}}
	
	{%endfor%}

 </ul>