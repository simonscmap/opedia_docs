:orphan:

.. _SeaFlow:

SeaFlow
*******



.. |cruise| image:: /_static/catalog_thumbnails/sailboat.png
   :scale: 10%
   :align: middle

.. |globe| image:: /_static/catalog_thumbnails/globe.png
  :scale: 10%
  :align: middle

.. |sm| image:: /_static/tutorial_pics/sparse_mapping.png
  :align: middle
  :scale: 10%
  :target: ../../tutorials/regional_map_sparse.html


.. |ts| image:: /_static/tutorial_pics/TS.png
  :align: middle
  :scale: 25%
  :target: ../../tutorials/time_series.html

.. |hst| image:: /_static/tutorial_pics/hist.png
  :align: middle
  :scale: 25%
  :target: ../../tutorials/histogram.html

.. |sec| image:: /_static/tutorial_pics/section.png
  :align: middle
  :scale: 20%
  :target: ../../tutorials/section.html

.. |dep| image:: /_static/tutorial_pics/depth_profile.png
  :align: middle
  :scale: 25%
  :target: ../../tutorials/depth_profile.html

.. |edy| image:: /_static/tutorial_pics/eddy_sampling.png
  :align: middle
  :scale: 25%
  :target: ../../tutorials/eddy.html


+-------------------------------+----------+----------+-------------+------------------------+----------------------+---------------------+---------------------+
| Dataset Name                  | Coverage | Sensor   |  Make       |     Spatial Resolution | Temporal Resolution  |  Start Date         |  End Date           |
+===============================+==========+==========+=============+========================+======================+=====================+=====================+
| :ref:`SeaFlow`                | |globe|  ||cruise|  | Observation |     Irregular          |    Three Minutes     | 2010-05-04 23:13:08 |2018-07-17 07:42:39  |
+-------------------------------+----------+----------+-------------+------------------------+----------------------+---------------------+---------------------+




Dataset Description
*******************


The data sets consist of SeaFlow-based cell abundance, forward light scatter,
and pigment fluorescence of individual cells, as well as derived estimates of
equivalent spherical diameter (ESD) and cellular carbon content of
picophytoplankton, which includes the cyanobacteria Prochlorococcus,
Synechococcus and small-sized Crocosphaera (< 5 μm ESD), and picophytoplankton
and nanophytoplankton (2-5 μm ESD). SeaFlow data were collected in surface
waters (≈5 m depth) from oceanographic cruises carried out across the Northeast
Pacific Ocean since 2010. Data provides high spatial
resolution (≈1 km) measurements across ocean basin, along with near-monthly data
at the long-term sampling site (Station ALOHA) of the Hawaii Ocean Time-Series
since 2015. Further information can be found here:
https://github.com/armbrustlab/popcycle

|

The SeaFlow Instrument
----------------------

SeaFlow is a new environmental flow cytometer designed by the Armbrust lab to be deployed on oceanographic research vessels to monitor continuously photosynthetic microorganisms. Since its first deployment in 2008, the SeaFlow instrument has collected over 200,000 samples in surface waters of the North Pacific and Atlantic Ocean. The geographical distribution of marine phytoplankton, their optical characteristics (size and pigment content), and their dynamics in relation to environmental factors are of major interest for the oceanographers.

Unlike a conventional flow cytometer, SeaFlow directly analyzes a raw stream of seawater using two detectors that determine the position of the particle in the focal region of the instrument optical system (Swalwell et al. 2011). With this technology, measurements from particles that pass through the ideal focal position of the collection optics can be differentiated from improperly positioned particles, producing a measurement equivalent to that obtained with a conventional cytometer (see OPP filtration). The ratio of these optimally positioned particles (OPP) to the total detectable particles is used to retrieve the volumetric flow rate, allowing accurate estimation of cell abundances (see Virtual Core calibration). Each particle is defined by its light scatter and by two different wavelengths of fluorescence associated with chlorophyll pigment (690 nm for red fluorescence) and phycoerythrin pigment (570 nm for orange fluorescence), which allow the discrimination between cells and detritus or suspended sediments and between photosynthetic and non-photosynthetic organisms.



Details of the SeaFlow project can be found here: https://armbrustlab.ocean.washington.edu/tools/seaflow/




Table of Variables
******************

.. raw:: html

    <iframe src="../../_static/var_tables/tblSeaFlow/tblSeaFlow.html"  frameborder = 0 height = '300px' width="100%">></iframe>

|

Data Source
***********

François Ribalet, Annette Hynes and Chris Berthiaume, Armbrust lab, University of Washington

How to Acknowledge
******************

François Ribalet, Chris Bertiaume, Annette Hynes, Jarred Swalwell, Michael Carlson,  Sophie Clayton, Gwenn Hennon, Camille Poirier, Eric Shimabukuro, Angelicque White, E. Virginia Armbrust, SeaFlow data 1.0: high-resolution abundance, size and biomass of small phytoplankton in the North Pacific. Scientific Data - Under Review

Version History
***************


**V1.1** - Jun 11, 2019

.. image:: https://zenodo.org/badge/DOI/10.5281/zenodo.3240587.svg
   :target: https://doi.org/10.5281/zenodo.3240587



**V1.0** - May 22, 2019

.. image:: https://zenodo.org/badge/DOI/10.5281/zenodo.2678022.svg
   :target: https://doi.org/10.5281/zenodo.2678022
