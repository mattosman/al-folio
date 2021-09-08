---
layout: page
permalink: /photos/
title: photos
description: <br>some places I've been, things I've seen. <br>
images:
  - image_path: /assets/img/gallery/CWG_Uummannaq_2015.jpg
    title: Uummannaq, Greenland (circa May 2015)
  - image_path: /assets/img/gallery/Flam_Norway_2018.jpg
    title: Flam, Norway (circa May 2018)
  - image_path: /assets/img/gallery/TMP_2020.jpg
    title: Near Saguaro National Park, AZ (circa June 2020)
  - image_path: /assets/img/gallery/Abisko_Reindeer_2013.jpg
    title: Abisko, Sweden (circa July 2013)
  - image_path: /assets/img/gallery/CWG_Race_2015.jpg
    title: Outside Uummannaq, Greenland (circa May 2015)
  - image_path: /assets/img/gallery/Rondane_2017.jpg
    title: Rondane National Park, Norway (circa Sept. 2017)
  - image_path: /assets/img/gallery/JIRP_C18_2012.jpg
    title: Juneau Icefield, AK (circa July 2012)
  - image_path: /assets/img/gallery/SonoranDesert_2020.jpg
    title: Sonoran Desert, north of Tucson, AZ (circa Nov. 2020)
  - image_path: /assets/img/gallery/Abisko_Tornetrask_2013.jpg
    title: Abisko, Sweden (circa July 2013)
  - image_path: /assets/img/gallery/Kalymnos_Ally_2017.jpg
    title: Kalymnos, Greece (circa May 2017)
  - image_path: /assets/img/gallery/Abisko_U_2013.jpg
    title: Abisko, Sweden (circa July 2013)
  - image_path: /assets/img/gallery/Gila_2021.jpg
    title: Gila National Forest, NM (circa April 2021)
  - image_path: /assets/img/gallery/CanyonLands_2015.jpg		
    title: Canyonlands, UT (circa Jan. 2015, photo cred Ally Frickman)
  - image_path: /assets/img/gallery/Kalymnos_2017.jpg
    title: Kalymnos, Greece (circa May 2017)
  - image_path: /assets/img/gallery/CWG_Disko_2015.jpg		
    title: Disko Island Ice Cap, Greenland (circa May 2015, photo cred Luke Trusel)
  - image_path: /assets/img/gallery/NH_2017.jpg
    title: Upper Dewey Lake, NH (circa August 2017)
  - image_path: /assets/img/gallery/WoodsHole_2015.jpg
    title: Woods Hole, MA (circa July 2015)
  - image_path: /assets/img/gallery/CWG_Dogs_2015.jpg
    title: Ilulissat, Greenland (circa Apr. 2015)
  - image_path: /assets/img/gallery/GC_Mancave_2012.jpg
    title: Grand Canyon, AZ (circa Feb 2012, photo cred Jordan Carey)
  - image_path: /assets/img/gallery/NICL_2015.jpg
    title: National Ice Core Laboratory, CO (circa July 2014, photo cred Sarah Das)
  - image_path: /assets/img/gallery/CWG_Glaciers_2015.jpg
    title: East of Qaarsut, Greenland (circa Apr. 2015)
  - image_path: /assets/img/gallery/Great_Sand_Dune_2015.jpg
    title: Great Sand Dune National Park, CO (circa Jan. 2016)
  - image_path: /assets/img/gallery/Idaho_2019.jpg
    title: Northern Idaho, near Victor (circa Sept. 2019)
  - image_path: /assets/img/gallery/Rockies_2011.jpg
    title: Rocky Mountain National Park, CO (circa Jan. 2011)
  - image_path: /assets/img/gallery/CWG_Margin_2018.jpg
    title: West Greenland Ice Sheet margin, ~50 km south of Ilulissat (circa July 2018).
  - image_path: /assets/img/gallery/Guilin_2013.jpg
    title: Lijiang River, Guilin vicinity, China (circa Oct. 2013)
  - image_path: /assets/img/gallery/Rockies_2015.jpg
    title: Grenadiers, CO (circa July 2015).
  - image_path: /assets/img/gallery/CWG_MedialMoraine_2015.jpg
    title: Nuussuaq Peninsula, Greenland (circa Apr. 2015).
  - image_path: /assets/img/gallery/JIRP_Pose_2012.jpg
    title: Taku Glacier terminus, Juneau, AK (circa June 2012, photo cred Carrie Jennings)
  - image_path: /assets/img/gallery/Boston_2019.jpg
    title: Boston Harbor, Boston, MA (circa Aug. 2019)
  - image_path: /assets/img/gallery/SW_China_2013.jpg
    title: Somewhere outside Chengdu, China (circa Oct. 2013)
  - image_path: /assets/img/gallery/JIRP_Skiing_2012.jpg
    title: Juneau Icefield, AK (circa June 2012)
nav: true
---

***

<div class="row justify-content-sm-center">

{% for image in page.images %}

  <div class="col-sm-6 mt-4 mt-md-4">
      <a href="{{ image.image_path }}"><img class="img-fluid rounded z-depth-2" src="{{ image.image_path }}"  alt="{{ image.title }}" title="{{ image.title }}"/></a>
  </div>

{% endfor %}
</div>

<!-- - image_path: /assets/img/gallery/CWG_NU_2015.jpg
  title: Nuussuaq Ice Cap (circa Apr. 2015, photo cred Luke Trusel) -->
<!-- - image_path: /assets/img/gallery/Kalymnos_Scooter_2017.jpg
  title: Kalymnos, Greece (circa May 2017, photo cred Ally Frickman) -->

<!-- <br><i> "The world is big and I want to have a good look at it before it gets dark."</i> <br> - John Muir <br><br> Random collection of some places I've been, things I've seen.  -->
