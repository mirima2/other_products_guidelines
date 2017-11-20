.. _oas:type:

7. Type (M)
====================

``datacite:resourceType``

Specifies the type of the research product being described. Free text.

7.1 type (M)
-------------------


**Usage Instruction**

This element contains information about the type of the research product. Possible values for this element are: research object, EGI Virtual Appliance, Virtual Machine Imaga, workflow, protocol, method, research package.

Since we are describing ORPs resources, the resourceTypeGeneral must be set to the DataCite term "Other"

.. note::
  For OpenAIRE-Connect communities a controlled vocabulary established for each community must be used
  
**Example**

.. code-block:: xml
   :linenos:

   <resourceType resourceTypeGeneral="Other">
     	Research object
   </resourceType>

   
