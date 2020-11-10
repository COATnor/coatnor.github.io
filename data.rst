.. _data:

Data upload
==================================

Check for protocol
-------------------------------

**Warning:** Before uploading a dataset you have to be sure that the related protocol is already in the portal.
If it's not yet available, follow the instruction for :ref:`protocol upload <protocol>`



.. contents::
    :depth: 2
    :local:

Upload a dataset
-------------------------------

* Login with a user with editor role for the module the dataset belongs to
* Go to Datasets and select "Add Dataset" (if not visible, you are not authorized: contact the module leader)

.. image:: _images/addataset.png
    :align: center
    :width: 92%

* The title should be identical to the dataset name
* The title should follow formatting rules (starting with \V_\ for datasets from Varanger and \S_\ for datasets from Svalbard)
* Add a short description of the dataset. Here an example in Markdown format:
* Select an embargo policy. If the dataset doesn't require an embargo, go on with next point. If your dataset include data less than 2 years old, you could select an embargo end date. Read the detailed instructions on how to manage embargo data and dataset versions :ref:`here <embargo>`
* After filling all metadata, select Next: "Add data"
* Upload all the data file in the following order, add a filename (best to keep the file's name by click on "Fill field with filename or URL") and choose the correct file format


.. contents::
    :depth: 2
    :local:

Data files upload order
-------------------------------

#. Upload the **readme** file as a PDF/A. A description can be added, for example: "Additional information about the dataset, including a description of the variables included in the dataset"

#. Upload the **auxiliary file/s** A description can be added, for example: "Auxiliary information about the sampling sites including information about whem the site has been included in the sampling design"

#. Upload the **coordinates** file. A description can be added, for example: "Coordinates of all sites included in the dataset"

#. Upload all **data files** in chronological order (from older to newer)

.. contents::
    :depth: 2
    :local:


Publishing the dataset
-------------------------------

After the upload is completed, the dataset can be set to *'Public'* by selecting **'Manage'** in the
menu of the dataset and setting the *'Visibility'* metadata element to *'Public'*.

.. contents::
    :depth: 2
    :local:

.. image:: _images/manage.png

.. image:: _images/arrow.png
    :align: center


.. image:: _images/visibility.png

Dataset Versions
-------------------------------

Datasets already published cannot be removed or modified, because of the FAIR requirement of being permanent and findable for citation and reuse purposes.
whenever a dataset content changes, it is necessary to create a new version of it.

.. contents::
    :depth: 2
    :local:

Embargo management
-------------------------------

.. _embargo:

Datasets in embargo follow a particular setup, which guarantees availability of older data contents and protection of more recent ones.

.. contents::
    :depth: 2
    :local:

