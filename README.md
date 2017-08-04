# ![logo](static/appIconAlt.png) Dose Monitoring with Splunk

[Derek Merck](email:derek_merck@brown.edu), Brown University and Rhode Island Hospital  
[Scott Collins](email:scollins1@lifespan.org), Rhode Island Hospital  
Karen Laurie, The Miriam Hospital  

<https://github.com/derekmerck/SplunkDoseApp>


## Overview

`SplunkDoseApp` is a [Splunk][] app that provides dashboards for radiation dose monitoring from DICOM
structured reports and a simple incident ticketing system.

It is intended to be used with [CopyDICOM][], a python script that can monitor an installation of Jodogne's
[Orthanc][] and copies [DICOM][] structured report tags to a Splunk index.

[CopyDICOM]: https://github.com/derekmerck/CopyDICOM
[Orthanc]: https://orthanc.chu.ulg.ac.be
[DICOM]: http://dicom.nema.org
[Splunk]: https://www.splunk.com
[DIANA]: https://github.com/derekmerck/miip


## Dependencies

- Splunk 6.6
