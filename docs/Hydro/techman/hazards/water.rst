.. _lbl-water:

Water-borne Natural Hazards
================================

Tsunami
-----------

The term *tsunami* is derived from two Japanese words, namely "tsu" (meaning harbor) and "nami" (meaning wave). Some of the original literature described them as tidal waves or seismic sea waves. Tsunamis are usually created by disturbances in the crust of the Earth. The resulting uplifting of the water surface over a large area forms a train of the long-period waves. These waves generated from tsunamis have huge wavelengths. In contrast to wind-generated waves, where the periods are about one minute, the periods are of the order of one hour and more. 

Once generated, these tsunami waves travel across the ocean basin to cause great destruction at locations far from the source. Owing to their destructive nature, it is imporant to comprehend the mechanisms of their generation, propagation and predict the extent of flooding/effect of wave forces in the coastal areas that are potential to tsunamis. In these areas susceptible to tsunamis, it is imperative to build resilient structures and communities.

This documentation compiles some of the basic ideas and information about tsunami events and modeling efforts.

.. toctree::
   :maxdepth: 1

   tsu-intro
   tsu-measure
   tsu-risk
   tsu-numerics

Storm Surge
---------------

Storm surge can be defined as the abnormal rise of water generated by a storm, over and above the predicted astronomical tides. Flooding from storm surge depends on several factors, including track, intensity, size, and forward speed of the hurricane and the characteristics of the coastline where it comes ashore or passes nearby. :numref:`SLOSHInunNJ` is obtained from the map generated by the US Environmental Protection Agency (EPA). It shows the storm surge inundation map obtained from the SLOSH numerical model. It shows the vulnerable points on the Eastern US coast that are significantly vulnerable to inundation heights of up to 9 feet. 

.. _SLOSHInunNJ:

.. figure:: images/StormInundation.png
   :width: 600px
   :alt: Storm surge inundation in eastern seaboard of USA
   :align: center

   This map displays the results from SLOSH (Sea, Lake, and Overland Surges from Hurricanes) model. SLOSH is a numerical model used by NWS (National Weather Service) to compute storm surge. (Source: `Storm surge inundation map by EPA <https://www.arcgis.com/apps/MapSeries/index.html?appid=852ca645500d419e8c6761b923380663>`_.)

New Jersey coastal risk
^^^^^^^^^^^^^^^^^^^^^^^^^
New Jersey (NJ) has about 1792 miles of coastline covering 17 / 21 counties in the state. This accounts to approximately 80% of the state's population and caters to almost $400B in annual economic outputs. The changes in sea level and increase in hurricane activity has significantly increased the coast's exposure to storm surges in the past four decades. :numref:`NJSeaLevel` shows the change in mean sea level in Atlantic city, which is almost 16 inches since 1912 and 6 inches since 1980.

.. _NJSeaLevel:

.. figure:: images/SeaLevelAtCity.png
   :width: 600px
   :alt: Changes in mean sea level in Atlantic city 
   :align: center

   Mean sea level in inches w.r.t  1912 in Atlantic city. (Source: National Oceanic and Atmospheric Administration (NOAA))

This increase in sea levels not only increases the risk of tidal flooding but also storm-related flooding that occurs during hurricanes and coastal storms. For example, during hurricane Sandy in 2012, the storm tide measured as much as 8.9 feet while the inundation in Monmouth and Middlesex counties were up to 9 feet deep. The surge in 2012 flooded an area of almost 27 square miles greater than in 1880. A recent report by the `Rhodium group <https://rhg.com/research/new-jersey-flooding-hurricanes-costs-climatechange/>`_ estimated the NJ's hurricane flood risk and how it may change through 2050. They employed various techniques including a GeoClaw model to estimate the hurricane-related flood risk as shown in :numref:`NJRisks` 

.. _NJRisks:

.. figure:: images/FloodHomesNJ.png
   :width: 600px
   :alt: Changes in houses in NJ coast facing flood risk 
   :align: center

   Increase in the number of buildings that are subject to flood risk of once in 30 years. The undertainity is due to changes in human activity and sea levels (Source: `Rhodium group report <https://rhg.com/research/new-jersey-flooding-hurricanes-costs-climatechange/>`_)


Chesapeake bay coastal risk
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^