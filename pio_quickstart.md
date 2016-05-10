{{#template name= 'pio_quickstart'}}
# Quickstart

Requirements:

 - A 'nix distribution like Redhat, Centos, Debian, Unbuntu, or Mac OS X. If you are running Windows we recommend a VM with `nix.
 - 16G memory for real data, 8g for experimentation
 - Java SE Development Kit 7 or 8
 
## Method 1: Quick Install

On Linux / Mac OS X, PredictionIO can now be installed with a single command:
 
    `bash -c "$(curl -s https://github.com/actionml/PredictionIO/blob/v0.9.6/bin/install.sh)"`

The above script will complete the installation for you including prerequisites. If you already have some prerequisites or plan a custom or clustered config use the manual install instructions. 

## Method 2: Manual Installation Guides
 
Choose the guide that best fits your needs.

 - **[Single Machine](/docs/single_machine)**: This sets up a single machine to run all services but does so in a way that allows for easier cluster expansion in the future.
 
 - **[Small High Availability Cluster](/docs/small_ha)**: This sets up a 3 machine cluster with all services running on all machines with no single point of failure. This setup will allow you to expand by moving clustered services into their own cluster as needed. For instance Spark may be moved to separate machines for scaling purposes. 
  
 - **[Fully Distributed Clusters](/docs/single_driver_machine)**: This sets up a single machine to run all services but does so in a way that allows for easier cluster expansion in the future.
{{/template}}