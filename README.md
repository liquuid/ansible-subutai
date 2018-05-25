Plugins and Drivers for Subutai Integration
===========================================

How to run
-----------

Inside this module directory, run: 

`ansible-playbook --module-path . tests/all_tests.yml -i ./hosts`

Replace `tests/all_tests.yml` with path to your recipe/playbook.

You'll need create a `hosts` file describing which servers this script will run, for example to run on localhost on port 2222: 

`localhost:2222`

Dev Branch
----------

On dev branch you can find more modules from early subutai version. This `subutai.py` is exactly the same subimitted to ansible upstream, with few modules and merged to one single file.

Using on pre-production enviroment
----------------------------------

Is possible try this module using our fork with module installed running on 2.6 ansible using the following ansible fork: 

https://github.com/liquuid/ansible

Generating Documentation
------------------------

To generate Markdown documentation run:

`./docgen.py`

Online documentation for subutai module can be found in: https://github.com/subutai-io/ansible/wiki/subutai
