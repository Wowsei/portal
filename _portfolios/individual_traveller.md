---
layout: portfolio
title: "Tickets for individual travelers"
icon: "/assets/images/icon_2.png"
post_image: "/assets/images/trains.png"
---

<h2>{{site.data.data.individual_traveller_booking}}</h2>

### {{site.data.data.booking_site}}

<p>{{site.data.data.individual_traveller_description_web}}</p>

### {{site.data.data.booking_app}}

<!-- <img src="{{relative_url}}/assets/images/xmove.jpg" class="img-fluid" alt="Xmove App"> -->

<p>{{site.data.data.app_description_web}}</p>

<div class="download_buttons">
	<a href="{{site.data.data.app_download_google_play_url}}" target="_blank" class="deneb_btn download_btn">
		<i class="fab fa-google-play"></i> {{site.data.data.app_download_google_play_text}}
	</a>
	<a href="{{site.data.data.app_download_app_store_url}}" target="_blank" class="deneb_btn download_btn">
		<i class="fab fa-apple"></i> {{site.data.data.app_download_app_store_text}}
	</a>
</div>


### {{site.data.data.ultimate_guides}}

* [{{site.data.data.uk_rail}}]({{site.data.data.uk_rail_url}})
* [{{site.data.data.de_rail}}]({{site.data.data.de_rail_url}})
* [{{site.data.data.austria_rail}}]({{site.data.data.australia_rail_url}})
* [{{site.data.data.italy_rail}}]({{site.data.data.italy_rail_url}})
* [{{site.data.data.spain_rail}}]({{site.data.data.spain_rail_url}})
* [{{site.data.data.france_rail}}]({{site.data.data.france_rail_url}})
* [{{site.data.data.bene_rail}}]({{site.data.data.bene_rail_url}})
* [{{site.data.data.italo_rail}}]({{site.data.data.italo_rail_url}})
* [{{site.data.data.italo_rail}}]({{site.data.data.flixbus_rail_url}})
* [{{site.data.data.poland_rail}}]({{site.data.data.poland_rail_url}})
* [{{site.data.data.nsb_rail}}]({{site.data.data.nsb_rail_url}})
* [{{site.data.data.rzd_rail}}]({{site.data.data.rzd_rail_url}})
* [{{site.data.data.vr_rail}}]({{site.data.data.vr_rail_url}})
* [{{site.data.data.sj_rail}}]({{site.data.data.sj_rail_url}})
* [{{site.data.data.cr_rail}}]({{site.data.data.cr_rail_url}})
* [{{site.data.data.korail_rail}}]({{site.data.data.korail_rail_url}})
* [{{site.data.data.taiwan_rail}}]({{site.data.data.taiwan_rail_url}})

### {{site.data.data.station_guides}}

#### {{site.data.data.europe}}

##### {{site.data.data.germany_stations}}

* [{{site.data.data.berlin_station}}]({{site.data.data.berlin_station_url}})
* [{{site.data.data.frankfurt_station}}]({{site.data.data.frankfurt_station_url}})
* [{{site.data.data.frankfurt_airport_station}}]({{site.data.data.frankfurt_airport_station_url}})
* [{{site.data.data.hamburg_station}}]({{site.data.data.hamburg_station_url}})
* [{{site.data.data.munich_station}}]({{site.data.data.munich_station_url}})
* [{{site.data.data.hannover_station}}]({{site.data.data.hannover_station_url}})
* [{{site.data.data.koln_station}}]({{site.data.data.koln_station_url}})

##### {{site.data.data.italy_stations}}

* [{{site.data.data.roma_termini}}]({{site.data.data.frankfurt_sroma_termini_urltation}})
* [{{site.data.data.napoli_c}}]({{site.data.data.napoli_c_url}})
* [{{site.data.data.roma_airport}}]({{site.data.data.roma_airport_url}})
* [{{site.data.data.torino_station}}]({{site.data.data.torino_station_url}})
* [{{site.data.data.pisa_c}}]({{site.data.data.pisa_c_url}})
* [{{site.data.data.milano_c}}]({{site.data.data.milano_c_url}})
* [{{site.data.data.venice_station}}]({{site.data.data.venice_station_url}})
* [{{site.data.data.florence_station}}]({{site.data.data.florence_station_url}})
* [{{site.data.data.malpensa_airport}}]({{site.data.data.malpensa_airport_url}})

<style>
.download_buttons {
	margin-top: 30px;
	display: flex;
	gap: 15px;
	flex-wrap: wrap;
}

.download_btn {
	display: inline-flex;
	align-items: center;
	gap: 8px;
	padding: 12px 24px;
	text-decoration: none;
	border-radius: 5px;
	transition: all 0.3s ease;
}

.download_btn:hover {
	transform: translateY(-2px);
	box-shadow: 0 5px 15px rgba(0,0,0,0.2);
}

@media (max-width: 768px) {
	.download_buttons {
		flex-direction: column;
	}
	
	.download_btn {
		justify-content: center;
	}
}
</style>

