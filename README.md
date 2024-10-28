# ocpvirtdemo

# rough outline

## Create Credentials in AAP

### Red Hat Automation Hub Credentials

### OpenShift Service Account Credentials

### OpenShift Virtualization SSH Key for RHEL VMs

## Create Project linking to GitHub repo https://github.com/david-rh/ocpvirtdemo.git

## Create OpenShift Dynamic Inventory
 Add Source link to source project with inventory file pointing to root path. This will autosearch for *.kubevirt.yml files

## Create Job Templates

* Create RHEL VM (create_rhelvm.yml)
  ** ssh_pub:
  ** vm_count:
* Register RHEL host (register-host.yml)
  ** activationkey:
  ** org_id:
  ** pool_id: 
* Run RHEL STIG (rhel9_stig.yml) ## Untested

# Create WorkFlow Template

* Create RHEL VM
* Update Inventory
* Register RHEL host
* Run RHEL STIG



