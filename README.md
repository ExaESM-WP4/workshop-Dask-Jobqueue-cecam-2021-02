# Workshop nesh 2020-03

_Workshop materials for a development workshop on interactive workflows on nesh._

**Lead:** _Katharina Höflich_ & _Willi Rath_


## Date and Place

- March 5th 2020, 09:00 - 12:00
- GEOMAR, Westshore, Kleiner Praktikumsraum


## Agenda [3 hours]

-	Introduction to ExaESM WP4 and hands-on training on established Jupyter-based workflow. [45 minutes]
-	Development session [75 minutes]
  -	enabling other currently unsupported interactive workflows
  -	improving documentation
  -	adapting existing workflows
-	Discussion / outlook [60 minutes]


## Contents

### Jupyter-based interactive workflows [45 minutes]

_(Meant to show existing partial solutions.)_

-	Brief overview of interactive-analysis efforts in ExaESM
-	Managing Python and Jupyter environments on HPC systems
-	Using Jupyter on Compute nodes
-	Using Dask on single compute nodes
-	Using (elastic) Dask clusters spanning multiple compute nodes

### Development session [75 minutes]

_(Meant to start collaboration on specific solutions.)_

-	Split into groups
-	Possible tasks:
  -	Install and test a Matlab / Ferret Kernel in Jupyter
  -	Gauge possibility of using interactive with X forwarding
  -	Document Jupyter-based workflow specific to Nesh

### Discussion / Outlook [60 minutes]

_(Meant to define future road.)_

-	Are there changes to the setup / configuration of the machine that would help with interactive workflows?
-	Who continues to work on solutions started in the development session?
-	Where do we document solutions?
-	Should we repeat this? Should we have a more user-focused workshop?
-	…


## Preparations

### Attendees

-	Bring a Laptop
  -	with Linux, MacOS, or Windows,
  -	that can VPN somewhere with NESH accesss,
  -	that has an SSH client (Git Bash works fine for Windows.),
  -	that has a Web Browser (Preferrably Chrome / Chromium, because proxy via SSH tunnel is easy there.)
- Have an Account on Nesh.
- Have an Eduroam Account. (But we might be able to fall back to a dedicated WiFi if necessary.)

### Nesh Admins

- Prepare dedicated Queue on the Linux Cluster or block parts of an existing queue?

### Lead

-	[ ] Prepare materials
-	[ ]	Short preparation meeting / phone call with Nesh Admins
- [x]	Find Date
- [x]	Book Room
