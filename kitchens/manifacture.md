---
layout: manufacturing.ect
href: '/kitchens/manifacturing'
title: 'Manufacture of kitchens'
navigationTitle: 'Manufacture'
lang: en
photo: '/kitchens/manifacture/the-crew-of-kitchens-dialog.jpg'
topics:
  -
    title: 'Casing'
    caption: 'Casing meeting the European standards of quality and environmental protection'
    description: 'The casing structure is the standard one, with load-bearing vertical sides. These are made of particle boards of 18 mm in width, made by Egger, Kaindl – Austria and Kronospan – Bulgaria (meeting the requirements of all European standards of quality and environmental protection). They have ABS edging made by Hranipex, 0.5, 1 or 2 mm thick, with the respective rounding. The eccentric Ø8 dowel pin connection ensures precision, sturdiness and aesthetic appearance. For reliable fixing of the hardware to the particle board, we use euro screw of Ø6.3 mm in diameter. We provide all hidden edgings. The monolithic structure of the kitchen casing is achieved by means of M4 nut and screw fixing elements.'
    highlight: 'Aluminium shelves|that make the kitchen better'
    roundphoto: '/kitchens/manifacture/rounded/casing-1.png'
    photos:
      - '/kitchens/manifacture/casing/casing-1.jpg'
      - '/kitchens/manifacture/casing/casing-2.jpg'
  -
    title: 'Drawers'
    caption: 'Special system for drawers from 35 to 50 kg'
    description: 'For drawers of 35 to 50 kg (total load-bearing capacity) and 20, 35 kg (payload) we use „Tandembox“ by Blum with an integrated system for smooth closing, complete drawing out and synchronised running of unevenly distributed load. The bottom is hard, 16 mm thick. The railing system provides the option for various combinations of superstructures and divisions. The front is fixed precisely and firmly using Ø10 mm PVC dowel pin. The front can be easily disassembled thanks to a clip system which ensures easy cleaning. In Dialog kitchens you will also find the Servo drive electro-system for assisted opening. The advantages as compared to other systems are several, and the most important of them is the shared control via a single controller of the Tandembox drawers and the "Aventos" clapping mechanisms.'
    highlight: 'Functional|and comfortable'
    roundphoto: '/kitchens/manifacture/rounded/drawers-2.png'
    photos:
      - '/kitchens/manifacture/drawers/drawers-tandemboks-4.jpg'
      - '/kitchens/manifacture/drawers/drawers-tandemboks-3.jpg'
      - '/kitchens/manifacture/drawers/drawers-tandemboks-1.jpg'
  -
    title: 'Legs'
    caption: 'Stable legs bearing excessive loads'
    description: 'The legs of the lower row casings are adjustable in order to ensure perfect levelling, they have wide heels to provide stability, fine threading and load-bearing capacity of 145 kg (per leg).'
    highlight: 'Functional|and comfortable'
    roundphoto: '/kitchens/manifacture/rounded/legs-1.png'
    photos:
      - '/kitchens/manifacture/legs/legs-1.jpg'
      - '/kitchens/manifacture/legs/legs-2.jpg'
  -
    title: 'Hinges'
    caption: 'Firmly fixed hinges for smooth closing'
    description: 'The hinges ensure smooth closing, have a built-in or external Blumotion and are firmly fixed to the casing using Blum PVC dowel pins. The quick clip system is convenient for cleaning and service purpoces.'
    highlight: 'Functional|and comfortable'
    roundphoto: '/kitchens/manifacture/rounded/hinges-1.png'
    photos:
      - '/kitchens/manifacture/hinges/hinges-1.jpg'
      - '/kitchens/manifacture/hinges/hinges-2.jpg'
      - '/kitchens/manifacture/hinges/hinges-3.jpg'
  -
    title: 'Baseboards'
    caption: 'PVC baseboards in a modern style'
    description: 'The baseboards are PVC and have aluminium and white foil for the modern style kitchens and wood decors for the classic style kitchens. They are water and detergent resistant. They are practical, easy to dismantle, clean and service. They have good ergonomic properties and a height of 100 mm, 120 mm and 150 mm. They are elegant and have a transparent or coloured silicon water protector. They are fixed to the legs by means of flexible stable clamps and corners.'
    highlight: 'Functional|and comfortable'
    roundphoto: '/kitchens/manifacture/rounded/baseboards-1.png'
    photos:
      - '/kitchens/manifacture/baseboards/baseboards-1.jpg'
      - '/kitchens/manifacture/baseboards/baseboards-2.jpg'
      - '/kitchens/manifacture/baseboards/baseboards-3.jpg'
  -
    title: 'Metabox'
    caption: '"Metabox" of Blum for drawers up to 20 kg'
    description: 'For drawers up to 20 kg (total load-bearing capacity) and 15 kg (payload) we use Metabox of Blum. Smooth closing is ensured by an external Blumotion, the sides of the drawer are metal, 54 mm, 85 mm and 118 mm high. The superstructure railings are practical and comfortable. The front is fixed using Ø10 PVC dowel pins. The drawer runs easily on Teflon rolls.'
    highlight: 'Functional|and comfortable'
    roundphoto: '/kitchens/manifacture/rounded/drawers-1.png'
    photos:
      - '/kitchens/manifacture/drawers/drawers-metabox-1.jpg'
      - '/kitchens/manifacture/drawers/drawers-metabox.jpg'
      - '/kitchens/manifacture/drawers/drawers-metabox-1.jpg'
  -
    title: 'Suspension'
    caption: 'Suspension with high load-bearing capacity'
    description: 'The casings of the upper row are suspended safely and securely, the load-bearing capacity is 2 x 65 kg – Blum.'
    highlight: 'Functional|and comfortable'
    roundphoto: '/kitchens/manifacture/rounded/suspension-1.png'
    photos:
      - '/kitchens/manifacture/suspension/suspension-1.jpg'
      - '/kitchens/manifacture/suspension/suspension-2.jpg'
  -
    title: 'Back'
    caption: 'Back along the whole length of the sides'
    description: 'The back is installed in a recess along the whole length of the sides. It is fixed by thin screws and washers (not staples) to the upper and lower sides.'
    roundphoto: '/kitchens/manifacture/rounded/back-1.png'
    photos:
      - '/kitchens/manifacture/back/back-1.jpg'
      - '/kitchens/manifacture/back/back-2.jpg'
      - '/kitchens/manifacture/back/back-3.jpg'
---

<div class="separator small"></div>

<div class="container model-details">
	<% for topic in @document.topics: %>
    
    <% if topic.description.length > 380 : %>
		<div class="detail long" id="<%= topic.title %>">
			<h3><%= topic.caption %></h3>
			<p><%= topic.description %></p>
		</div>
    <% else: %>
    <div class="detail" id="<%= topic.title %>">
      <h3><%= topic.caption %></h3>
      <p><%= topic.description %></p>
    </div>
    <% end %>

		<div class="slider <%= topic.orientation %>">
			<ul class="detail-slideshow">
				<% for photo in topic.photos: %>
				 <li><img src="<%- @document.ptr %><%= photo %>" alt="<%= topic.caption %>"></li>
				<% end %>
			</ul>
			<div class="detail-thumbs">
				<% for photo, idx in topic.photos: %>
				<a data-slide-index="<%- idx %>" href=""><div class="overlay"><img src="<%- @document.ptr %><%= @getThumbnail(photo) %>" alt="<%= topic.caption %>"></div></a>
				<% end %>
			</div>
		</div>

		<div class="clear"></div>
	<% end %>
</div>

<% if @document.parent?: %>
<div class="separator small"></div>
<div class="container category models">
  <hr />
  <h3>Kitchen models</h3>
  <% for document in @getCollection("html").findAll({parent:'/kitchens/models.html'}).toJSON(): %>
  <div class="separator small"></div>
    <h5><%=document.title%></h5>
    <% for model in @getCollection("html").findAll({parent:document.url}).toJSON(): %>
    <a href="<%- @document.ptr %><%=model.url%>" title="Have a look on a kitchen model - <%= model.title %>">
      <%=model.title%>
      <img src="<%- @document.ptr %><%= @getThumbnail(model.photo) %>" alt="<%=model.title%>">
    </a>
    <% end %>
  <% end %>
</div>
<% end %>


<div class="separator"></div>
<div class="container technologies">
  <hr/>
  <h3>Technologies in the kitchen</h3>
  <div class="clear"></div>
  <a class="next"><img src="<%- @document.ptr %>/images/right-arrow.jpg" alt="Forward"></a>
  <a class="prev"><img src="<%- @document.ptr %>/images/left-arrow.jpg" alt="Back"></a>
  <div class="carousel" data-items="4">
    <% for document in @getCollection("html").findAll({parent:'/kitchens/technology.html'}).toJSON(): %>
    <div class="technology">
      <a href="<%- @document.ptr %><%=document.url%>" title="<%=document.title%> for kitchen"><img src="<%- @document.ptr %><%= @getThumbnail(document.photo) %>" alt="<%=document.title%>"></a>
      <h5><%=document.title%></h5>
      <p><%=document.description%></p>
      <a class="more" href="<%- @document.ptr %><%=document.url%>" title="<%=document.title%> for kitchen"><span>Learn more</span></a>
    </div>
    <% end %>
  </div>
</div>
<div class="separator small"></div>
