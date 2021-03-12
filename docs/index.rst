CubeViz: Visualization & Analysis Tool for Data Cubes from Integral Field Units (IFUs)
======================================================================================

.. DANGER:: 

      Please note that this version of CubeViz is **no longer being actively supported
      or maintained**. The functionality of CubeViz is now available and being actively
      developed as part of `Jdaviz <https://github.com/spacetelescope/jdaviz>`_.

CubeViz is an visualization and analysis toolbox for data cubes from `integral
field units (IFUs)
<https://jwst-docs.stsci.edu/display/JPP/Introduction+to+IFU+Spectroscopy>`__.
It is built as part of the `glue visualiztion tool <http://glueviz.org>`__.
CubeViz is designed to work with data cubes from the `NIRSpec
<https://jwst-docs.stsci.edu/display/JTI/NIRSpec+IFU+Spectroscopy>`__ and `MIRI
<https://jwst-docs.stsci.edu/display/JTI/MIRI+Medium-Resolution+Spectroscopy>`__
instruments on `JWST
<https://jwst-docs.stsci.edu/display/HOM/JWST+User+Documentation+Home>`__, and
will work with data cubes from any IFU.  It uses the `specutils
<https://specutils.readthedocs.io/en/latest/>`__ package from `Astropy
<http://www.astropy.org>`__.

The core functionality of CubeViz currently includes the ability to:
  * view the wavelength slices (RA, DEC) in a data cube,
  * view flux, error, and data quality slices simultaneously,
  * view spectra from selected spatial (RA, DEC) regions,
  * smooth cubes spactially (RA, DEC) and spectrally (wavelength), and
  * create and display contour maps.
  * collapse cubes over selected wavelength regions,
  * fit spectral lines,
  * create moment maps,
  * perform continuum subtraction,
  * cube arithmetic,
  * overlay spectral line lists,
  * save edited cubes,
  * save figures,
  * mock slit observations,
  * accurate spectro-photometry,
  * fit models to every spaxel

Future functionality will include the ability to:
  * save and restore a session,
  * create kinematic maps (rotation velocity and velocity dispersion),
  * create RGB images from regions collapsed in wavelength space (i.e., linemaps),
  * output python scripts for making figures,
  * output astropy commands,
  * match spatial resolution among selected data cubes,
  * bin data into constant signal-to-noise regions

Reference/API
=============

.. toctree::
  :maxdepth: 2

  installation
  functionality
  image_viewers
  spectrum_viewer
  analysis
  shortcuts
  readingindata
  developer_guide
