---
layout: page
title: Locations
permalink: /locations/
---
<style type="text/css" media="screen">
    
    h1{
        text-align: center;
        /* border: 1.5px solid black; */
        /* font-style: italic; */
    }
    
    .grid-container {
        display: grid;
        grid-template-columns: auto auto auto;
        padding: 10px;
    }

    .location_container{
        border-radius: 5px;
        background-color: lightgray;
        box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
        transition: 0.3s;
        padding: 1rem 1rem 1rem 1rem;
        border: 1.5px solid black;
        margin: 1rem 1rem 1rem 1rem;
        text-align: center;
    }

    .location_container:hover {
        box-shadow: 0 16px 32px 0 rgba(0,0,0,0.2);
    }

</style>

<div class="grid-container">
    <div class="location_container">
        <div class="txt_container">
        <h4><b>Place 1</b></h4>
        <p>address</p>
        <p>hours</p>
        </div>
    </div>
    <div class="location_container">
        <div class="txt_container">
        <h4><b>Place 2</b></h4>
        <p>address</p>
        <p>hours</p>
        </div>
    </div>

</div>