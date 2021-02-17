Golang QA/Config Engine:
------------------------

Move2Kube (https://github.com/konveyor/move2kube) has a config mechamism which also doubles down as QA engine. The goal of this idea is to refactor the module out of Move2Kube to make it resusable for any golang based project.

It allows for the below interfaces:
1. CLI based interactive discovery
1. Yaml based config
1. Cache questions and answers as yaml
1. Config setting using command line parameters
1. REST based QA

It supports the below QA types:
1. Select 
1. Multi-select
1. Confirm
1. Single line text input
1. Multi line text input
1. Password
