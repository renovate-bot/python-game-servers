.. This file is automatically generated. Do not edit this file directly.

Google Cloud Game Servers Python Samples
===============================================================================

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/README.rst


This directory contains samples for Google Cloud Game Servers. The `Google Cloud Game Servers`_ is a managed service that enables game developers to deploy and manage their dedicated game servers across multiple Agones clusters around the world through a single interface.




.. _Google Cloud Game Servers: https://cloud.google.com/game-servers/docs/





Setup
-------------------------------------------------------------------------------


Authentication
++++++++++++++

This sample requires you to have authentication setup. Refer to the
`Authentication Getting Started Guide`_ for instructions on setting up
credentials for applications.

.. _Authentication Getting Started Guide:
    https://cloud.google.com/docs/authentication/getting-started

Install Dependencies
++++++++++++++++++++

#. Clone python-docs-samples and change directory to the sample directory you want to use.

    .. code-block:: bash

        $ git clone https://github.com/GoogleCloudPlatform/python-docs-samples.git

#. Install `pip`_ and `virtualenv`_ if you do not already have them. You may want to refer to the `Python Development Environment Setup Guide`_ for Google Cloud Platform for instructions.

   .. _Python Development Environment Setup Guide:
       https://cloud.google.com/python/setup

#. Create a virtualenv. Samples are compatible with Python 2.7 and 3.4+.

    .. code-block:: bash

        $ virtualenv env
        $ source env/bin/activate

#. Install the dependencies needed to run the samples.

    .. code-block:: bash

        $ pip install -r requirements.txt

.. _pip: https://pip.pypa.io/
.. _virtualenv: https://virtualenv.pypa.io/

Samples
-------------------------------------------------------------------------------

Create game server deployment
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/create_deployment.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python create_deployment.py

    usage: create_deployment.py [-h] --project-id PROJECT_ID --deployment-id
                                DEPLOYMENT_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --deployment-id DEPLOYMENT_ID
                            Your game server deployment ID.



Delete game server deployment
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/delete_deployment.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python delete_deployment.py

    usage: delete_deployment.py [-h] --project-id PROJECT_ID --deployment-id
                                DEPLOYMENT_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --deployment-id DEPLOYMENT_ID
                            Your game server deployment ID.



Get game server deployment
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/get_deployment.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python get_deployment.py

    usage: get_deployment.py [-h] --project-id PROJECT_ID --deployment-id
                             DEPLOYMENT_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --deployment-id DEPLOYMENT_ID
                            Your game server deployment ID.



Update game server deployment
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/update_deployment.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python update_deployment.py

    usage: update_deployment.py [-h] --project-id PROJECT_ID --deployment-id
                                DEPLOYMENT_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --deployment-id DEPLOYMENT_ID
                            Your game server deployment ID.



Get rollout
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/get_rollout.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python get_rollout.py

    usage: get_rollout.py [-h] --project-id PROJECT_ID --deployment-id
                          DEPLOYMENT_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --deployment-id DEPLOYMENT_ID
                            Your game server deployment ID.



List game server deployments
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/list_deployments.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python list_deployments.py

    usage: list_deployments.py [-h] --project-id PROJECT_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.



Update rollout to set default config
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/update_rollout_default.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python update_rollout_default.py

    usage: update_rollout_default.py [-h] --project-id PROJECT_ID --deployment-id
                                     DEPLOYMENT_ID --config-id CONFIG_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --deployment-id DEPLOYMENT_ID
                            Your game server deployment ID.
      --config-id CONFIG_ID
                            Your game server config ID.



Update rollout to set override config
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/update_rollout_override.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python update_rollout_override.py

    usage: update_rollout_override.py [-h] --project-id PROJECT_ID --deployment-id
                                      DEPLOYMENT_ID --config-id CONFIG_ID
                                      --realm-location REALM_LOCATION --realm-id
                                      REALM_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --deployment-id DEPLOYMENT_ID
                            Your game server deployment ID.
      --config-id CONFIG_ID
                            Your game server config ID.
      --realm-location REALM_LOCATION
                            Your game server config ID.
      --realm-id REALM_ID   Your game server config ID.



Update rollout to remove default config
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/update_rollout_remove_default.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python update_rollout_remove_default.py

    usage: update_rollout_remove_default.py [-h] --project-id PROJECT_ID
                                            --deployment-id DEPLOYMENT_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --deployment-id DEPLOYMENT_ID
                            Your game server deployment ID.



Update rollout to remove override config
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/update_rollout_remove_override.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python update_rollout_remove_override.py

    usage: update_rollout_remove_override.py [-h] --project-id PROJECT_ID
                                             --deployment-id DEPLOYMENT_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --deployment-id DEPLOYMENT_ID
                            Your game server deployment ID.



Create game server config
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/create_config.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python create_config.py

    usage: create_config.py [-h] --project-id PROJECT_ID --deployment-id
                            DEPLOYMENT_ID --config-id CONFIG_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --deployment-id DEPLOYMENT_ID
                            Your game server deployment ID.
      --config-id CONFIG_ID
                            Your game server config ID.



Delete game server config
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/delete_config.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python delete_config.py

    usage: delete_config.py [-h] --project-id PROJECT_ID --deployment-id
                            DEPLOYMENT_ID --config-id CONFIG_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --deployment-id DEPLOYMENT_ID
                            Your game server deployment ID.
      --config-id CONFIG_ID
                            Your game server config ID.



Get game server config
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/get_config.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python get_config.py

    usage: get_config.py [-h] --project-id PROJECT_ID --deployment-id
                         DEPLOYMENT_ID --config-id CONFIG_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --deployment-id DEPLOYMENT_ID
                            Your game server deployment ID.
      --config-id CONFIG_ID
                            Your game server config ID.



List game server configs
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/list_configs.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python list_configs.py

    usage: list_configs.py [-h] --project-id PROJECT_ID --deployment-id
                           DEPLOYMENT_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --deployment-id DEPLOYMENT_ID
                            Your game server deployment ID.



Create realm
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/create_realm.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python create_realm.py

    usage: create_realm.py [-h] --project-id PROJECT_ID --location LOCATION
                           --realm-id REALM_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --location LOCATION   Your realm location.
      --realm-id REALM_ID   Your realm ID.



Delete realm
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/delete_realm.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python delete_realm.py

    usage: delete_realm.py [-h] --project-id PROJECT_ID --location LOCATION
                           --realm-id REALM_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --location LOCATION   Your realm location.
      --realm-id REALM_ID   Your realm ID.



Get realm
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/get_realm.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python get_realm.py

    usage: get_realm.py [-h] --project-id PROJECT_ID --location LOCATION
                        --realm-id REALM_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --location LOCATION   Your realm location.
      --realm-id REALM_ID   Your realm ID.



Update realm
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/update_realm.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python update_realm.py

    usage: update_realm.py [-h] --project-id PROJECT_ID --location LOCATION
                           --realm-id REALM_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --location LOCATION   Your realm location.
      --realm-id REALM_ID   Your realm ID.



List realms
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/list_realms.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python list_realms.py

    usage: list_realms.py [-h] --project-id PROJECT_ID --location LOCATION

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --location LOCATION   Your realm location.



Create game server cluster
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/create_cluster.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python create_cluster.py

    usage: create_cluster.py [-h] --project-id PROJECT_ID --location LOCATION
                             --realm-id REALM_ID --cluster-id CLUSTER_ID
                             --gke-cluster-name GKE_CLUSTER_NAME

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --location LOCATION   Your realm location.
      --realm-id REALM_ID   Your realm ID.
      --cluster-id CLUSTER_ID
                            Your game server cluster ID.
      --gke-cluster-name GKE_CLUSTER_NAME
                            The name of the GKE cluster which is managed by the
                            game server cluster being created.



Delete game server cluster
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/delete_cluster.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python delete_cluster.py

    usage: delete_cluster.py [-h] --project-id PROJECT_ID --location LOCATION
                             --realm-id REALM_ID --cluster-id CLUSTER_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --location LOCATION   Your realm location.
      --realm-id REALM_ID   Your realm ID.
      --cluster-id CLUSTER_ID
                            Your game server cluster ID.



Get game server cluster
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/get_cluster.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python get_cluster.py

    usage: get_cluster.py [-h] --project-id PROJECT_ID --location LOCATION
                          --realm-id REALM_ID --cluster-id CLUSTER_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --location LOCATION   Your realm location.
      --realm-id REALM_ID   Your realm ID.
      --cluster-id CLUSTER_ID
                            Your game server cluster ID.



Update game server cluster
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/update_cluster.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python update_cluster.py

    usage: update_cluster.py [-h] --project-id PROJECT_ID --location LOCATION
                             --realm-id REALM_ID --cluster-id CLUSTER_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --location LOCATION   Your realm location.
      --realm-id REALM_ID   Your realm ID.
      --cluster-id CLUSTER_ID
                            Your game server cluster ID.



List game server cluster
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. image:: https://gstatic.com/cloudssh/images/open-btn.png
   :target: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=/list_clusters.py,/README.rst




To run this sample:

.. code-block:: bash

    $ python list_clusters.py

    usage: list_clusters.py [-h] --project-id PROJECT_ID --location LOCATION
                            --realm-id REALM_ID

    optional arguments:
      -h, --help            show this help message and exit
      --project-id PROJECT_ID
                            Your cloud project ID.
      --location LOCATION   Your realm location.
      --realm-id REALM_ID   Your realm ID.





The client library
-------------------------------------------------------------------------------

This sample uses the `Google Cloud Client Library for Python`_.
You can read the documentation for more details on API usage and use GitHub
to `browse the source`_ and  `report issues`_.

.. _Google Cloud Client Library for Python:
    https://googlecloudplatform.github.io/google-cloud-python/
.. _browse the source:
    https://github.com/GoogleCloudPlatform/google-cloud-python
.. _report issues:
    https://github.com/GoogleCloudPlatform/google-cloud-python/issues


.. _Google Cloud SDK: https://cloud.google.com/sdk/