.. Kylo Operations Guide documentation master file, created by
   sphinx-quickstart on Wed Jan  4 19:21:44 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

===========================
Welcome to the Kylo Project
===========================

|image1| Kylo website: |kylo_io_link|

The documentation for the site is organized into a few sections:

* :ref:`about_toc`
* :ref:`installation_toc`
* :ref:`security_toc`
* :ref:`how_to_guides`
* :ref:`developer_guides`
* :ref:`user_guides`
* :ref:`tips_tricks`

.. _about_toc:
.. toctree::
    :maxdepth: 1
    :caption: About

    about/KyloFeatures
    about/KyloFrequentlyAskedQuestions
    about/KyloTerminology
    release-notes/ReleaseNotes

.. _installation_toc:
.. toctree::
    :maxdepth: 1
    :caption: Installation

    installation/KyloDeploymentGuideIndex

.. _security_toc:
.. toctree::
    :maxdepth: 1
    :caption: Security

    Authentication <security/Authentication>
    Access Control <security/AccessControl>
    Ranger <security/EnableRangerAuthorizationGuide>
    Sentry <security/EnableSentryAuthorizationGuide>
    Kerberos <security/Kerberos>
    Kerberos SPNEGO <security/KyloKerberosSPNEGO>

.. _how_to_guides:
.. toctree::
    :maxdepth: 1
    :caption: How to guides

    Kylo UI & SSL <how-to-guides/KyloUIWithSSL>
    NiFi Cluster <how-to-guides/SetupaNiFiClusterinaKyloSandbox>
    Kylo Cluster <how-to-guides/KyloClusterConfiguration>
    NiFi & SSL <how-to-guides/ConfigureNiFiWithSSL>
    NiFi & HDFS Encryption <how-to-guides/ConfigNififorHDFSEncryption>
    NiFi & Kylo Provenance <how-to-guides/NiFiKyloProvenance>
    NiFi & Kylo Reporting Task (deprecated) <how-to-guides/NiFiKyloProvenanceReportingTask>
    how-to-guides/NiFiProcessorsDocs
    how-to-guides/S3DataIngestTemplate
    S3 & Data Wrangler <how-to-guides/AccessingS3fromtheDataWrangler>
    Feed Lineage <how-to-guides/FeedLineage>
    how-to-guides/SentryInstallationGuide
    SUSE Configuration <how-to-guides/SuseConfigurationChanges>
    Configuration Properties <how-to-guides/ConfigurationProperties>
    Validator Tuning <how-to-guides/ValidatorTuning>
    Kylo & Global Search <how-to-guides/ConfigureKyloForGlobalSearch>

.. _developer_guides:
.. toctree::
    :maxdepth: 1
    :caption: Developer guides

    Developer Guide <developer-guides/KyloDeveloperGuide>
    Contributing <developer-guides/ContributingtoKylo>
    Plugin APIs <developer-guides/PluginApiIndex>
    REST API <developer-guides/KyloRestApi>

.. _user_guides:
.. toctree::
    :maxdepth: 1
    :caption: User guides

    user-guides/KyloOperationsGuide

.. _tips_tricks:
.. toctree::
    :maxdepth: 1
    :caption: Tips and tricks

    tips-tricks/TroubleshootingandTips
    tips-tricks/KyloBestPractices


.. |image1| image:: media/common/kylo-logo-orange.png
    :width: 600px
    :height: 338px
    :scale: 50%
    :align: middle
    :alt: kylo logo


..  files that are not part of the toctree:
    how-to-guides/KyloIconsAndColors
    installation/KyloDependencies
    installation/ClouderaDockerSandboxDeploymentGuide
    installation/HDP25ClusterDeploymentGuide
    installation/HortonworksSandboxConfiguration
    installation/KerberosInstallationExample-Cloudera
    installation/KyloConfiguration
    installation/KyloDependencies
    installation/KyloManualDeploymentGuide
    installation/KyloSetupWizardDeploymentGuide
    installation/KyloTARFileInstallation
    installation/KylosConfigurationforaKerborosCluster
    installation/NiFiConfigurationforaKerberosCluster
    installation/Postgres_Hive_Metadata_Configuration

.. |kylo_io_link| raw:: html

   <a href="https://kylo.io" target="_blank">https://kylo.io</a>
