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


+-------------------------------+----------+----------+-------------+------------------------+----------------------+--------------+------------+
| Dataset Name                  | Coverage | Sensor   |  Make       |     Spatial Resolution | Temporal Resolution  |  Start Date  |  End Date  |
+===============================+==========+==========+=============+========================+======================+==============+============+
| :ref:`SeaFlow`                | |globe|  ||cruise|  | Observation |     Irregular          |    Three Minutes     |  2003-01-06  | 2015-12-21 |
+-------------------------------+----------+----------+-------------+------------------------+----------------------+--------------+------------+



Recommended Visualizations
**************************

+---------------------------+---------------------------+---------------------------+
| |sm|                      |    |ts|                   |           |hst|           |
+---------------------------+---------------------------+---------------------------+
|**Regional Sparse Map**    | **Time Series**           |  **Histogram**            |
+---------------------------+---------------------------+---------------------------+


Table of Variables
******************

.. raw:: html

    <iframe src="../../_static/var_tables/tblSeaFlow/tblSeaFlow.html"  frameborder = 0 height = '300px' width="100%">></iframe>



Dataset Description
*******************


SeaFlow is a new environmental flow cytometer designed by the Armbrust lab to be deployed on oceanographic research vessels to monitor continuously photosynthetic microorganisms. Since its first deployment in 2008, the SeaFlow instrument has collected over 200,000 samples in surface waters of the North Pacific and Atlantic Ocean. The geographical distribution of marine phytoplankton, their optical characteristics (size and pigment content), and their dynamics in relation to environmental factors are of major interest for the oceanographers.

Unlike a conventional flow cytometer, SeaFlow directly analyzes a raw stream of seawater using two detectors that determine the position of the particle in the focal region of the instrument optical system (Swalwell et al. 2011). With this technology, measurements from particles that pass through the ideal focal position of the collection optics can be differentiated from improperly positioned particles, producing a measurement equivalent to that obtained with a conventional cytometer (see OPP filtration). The ratio of these optimally positioned particles (OPP) to the total detectable particles is used to retrieve the volumetric flow rate, allowing accurate estimation of cell abundances (see Virtual Core calibration). Each particle is defined by its light scatter and by two different wavelengths of fluorescence associated with chlorophyll pigment (690 nm for red fluorescence) and phycoerythrin pigment (570 nm for orange fluorescence), which allow the discrimination between cells and detritus or suspended sediments and between photosynthetic and non-photosynthetic organisms.


|



Sample of SeaFlow Prochlorococcus Abundance
###########################################

.. raw:: html

    <iframe src="../../_static/var_plots/seaflow_vis.html"  frameborder = 0  height="700px" width="100%">></iframe>

|


Data Source
***********

Simons CMAP

Armbrust Lab, UW

How to Acknowledge
******************

Version History
***************
