Ansible Role: Intel_IPP_Crypto
=========

Ansible Role to build and install [Intel's IPP Crypto](https://github.com/intel/ipp-crypto) library from source.

Requirements
------------

Pre-requisites not be covered by Ansible or the role:
- None

Role Variables
--------------

See variables defined in defaults/main.yml.

Dependencies
------------

Roles hosted on Galaxy and their parameters:
- None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: melhindi.intel_ipp_cyrpto }

License
-------

Apache 2.0

Contribute
-------

To contribute to the development of this role the following setup is recommended:

```
# 1. Clone the repository with the expected role name:
git clone git@github.com:melhindi/ansible-role-intel-ipp-crypto.git melhindi.intel_ipp_crypto

# 2. Initialize the virtual environment
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install -r requirements.txt

# 3. Use molecule to test the role
molecule converge
```
*Note*: This setup assumes that you do not have any globally installed ansible or molecule. Sometimes globally installed ansible/molecule can cause package/dependency conflicts.
