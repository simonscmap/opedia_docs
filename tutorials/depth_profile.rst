
Plot Depth Profile
==================




Create depth profile plots using model and BGC-Argo float profiles.



Note:
Pisces model is a weekly-averaged global model with spatial resolution  1/2° X 1/2°  (data is available only at one-week intervals).

Darwin_Climatology is a monthly climatology version of the Darwin model with spatial resolution  1/2° X 1/2° .

Argo float data set has irregular temporal and spatial resolution.

.. code:: python


    from opedia import plotDepthProfile as DEP

    tables = ['tblPISCES_NRT', 'tblArgoMerge_REP', 'tblDarwin_Chl_Climatology']
    variables = ['CHL', 'argo_merge_chl_adj', 'chl01_darwin_clim']
    startDate = '2016-04-30'   # PISCES is a weekly model, and here we are using monthly climatology of Darwin model
    endDate = '2016-04-30'
    lat1 = '20'
    lat2 = '24'
    lon1 = '-170'
    lon2 = '-150'
    depth1 = '0'
    depth2 = '1500'
    fname = 'DEP'
    exportDataFlag = False      # True if you you want to download data

    DEP.plotDepthProfile(tables, variables, startDate, endDate, lat1, lat2, lon1, lon2, depth1, depth2, fname, exportDataFlag)









.. raw:: html

    <iframe src="../_static/depth_profile.html"  frameborder = 0  height="1600px" width="100%">></iframe>