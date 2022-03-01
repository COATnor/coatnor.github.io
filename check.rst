.. _check:

Quick check
==================================

Before uploading a dataset to the COAT Data Portal, we suggest to perform a quick check
of compliance to mandatory formatting requirements.

This section provides a checklist for dataset uploading new datasets.
For a full detailed description of the formatting rules please refer to the :ref:`data formatting section <formatting>`

The data formatting rules are also included in the
`COAT Data Management Plan <https://data.coat.no/dataset/d854b87c-ce4d-49fe-9704-c72b9333506f/resource/45404559-6c00-4061-a93b-bfeca8e09187/download/coat-data-management-plan-v1.1.pdf>`_.

1. Dataset requirements
^^^^^^^^^^^^^^^^^^^^^^^

* A **coordinates** file is mandatory. Se below for more details
* A Sampling Protocol related to the dataset needs to be already available in the portal

2. Data files
^^^^^^^^^^^^^^^^^^^^^^^^

* All tabular files formatted as ";"-separated txt files
* All column names should start with **sn_**, **sc_**, **t_** or **v_** for variables that are either spatially nested, spatially crossed, temporal, or other (i.e. data variables).
* No empty cells - use NA
* Only lower case (except NA)
* Correct spelling of spatial names (according to COAT vocabulary for localities)
* Date format: yyyy-mm-dd

3. Sampling protocol
^^^^^^^^^^^^^^^^^^^^^^^^

* The protocol should be formatted using the template for COAT protocols available on BOX folder *COAT/Protocol/COAT Research protocol*
* A protocol need to be added to the portal before the datasets referring to it
* A protocol will be saved as a PDF/A and the name should start with "\protocol_\"
* A protocol is a special type of dataset in the data portal, and will be added with a similar procedure,
  with slightly different metadata

4. Coordinates file
^^^^^^^^^^^^^^^^^^^^^^^^

* Should be a txt file
* Same formatting requirements as for data files
* The file should include the coordinates of all dataset's sampling sites
* Coordinates need to be provided both as geographical (decimal degrees) and UTM33 (easting and northing in meters)
* The file should include the following columns: 'sn_site', 'e_dd', 'n_dd', 'e_utm33', 'n_utm33'
* Find an example in BOX folder *COAT/Data management*

5. Auxiliary files
^^^^^^^^^^^^^^^^^^^^^^^^

* Same formatting requirements as for data files
* The file can include further information about the sites included in the study design
* For example the years when a site has been included in the study design
* Another example: old site names
* Example on BOX folder *COAT/Data management*

6. Readme file
^^^^^^^^^^^^^^^^^^^^^^^^

* The file should be saved as PDF/A
* No special formatting rules
* The file can include other necessary information about the dataset,
  for example a description of the variables included in the dataset, or changes in the protocol



