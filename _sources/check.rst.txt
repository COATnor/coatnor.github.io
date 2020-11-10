.. _check:

Quick check
==================================

Before uploading a dataset to the COAT Data Portal, we suggest to perform a quick check
of compliance to mandatory formatting requirements.

This section aims at providing a synthetic checklist to help during datasets upload operations.
For a full detailed description of the formatting rules please refer to the :ref:`data formatting section <formatting>`

The data formatting rules are also included in the Data Management Plan of the COAT project.

1. Dataset requirements
^^^^^^^^^^^^^^^^^^^^^^^

* A coordinates file is mandatory. Se below for more details
* A Sampling Protocol related to the dataset needs to be already available in the portal

2. Data files
^^^^^^^^^^^^^^^^^^^^^^^^

* All tabular files formatted as ";"-separated txt files
* All column names should start with **sn_**, **sc_**, **t_** or **v_**
* No empty cells - use NA
* Only lower case (except NA)
* Correct spelling of spatial names (according to COAT vocabulary for localities)
* Date format: yyy-mm-dd

3. Sampling protocol
^^^^^^^^^^^^^^^^^^^^^^^^

* The protocol should be formatted using the template for COAT protocols available on BOX
* A protocol need to be added to the portal before the datasets referring to it
* A protocol will be saved as a PDF/A and the name should start with "\protocol_\"
* A protocol is a special type of dataset in the data portal, and will be added with a similar procedure,
  with slightly different metadata
* An example of a protocol can be found on BOX

4. Coordinates file
^^^^^^^^^^^^^^^^^^^^^^^^

* Should be a txt file
* Same formatting requirements as for data files
* The file should include the coordinates of all dataset's sampling sites
* Coordinates need to be provided both as geographical (decimal degrees) and UTM33 (easting and northing in meters)
* The file should include the following columns: 'sn_site', 'e_dd', 'n_dd', 'e_utm33', 'n_utm33'
* Find an example in BOX

5. Auxiliary files
^^^^^^^^^^^^^^^^^^^^^^^^

* Same formatting requirements
* The file can include further information about the sites included in the study design
* For example the years when a site has been included in the study design
* Another example: old site names
* Example on BOX

6. Readme file
^^^^^^^^^^^^^^^^^^^^^^^^

* The file should be saved as PDF/A
* No special formatting rules
* The file can include other necessary information about the dataset,
  for example a description of the variables included in the dataset, or changes in the protocol



