# viaa-okd
Shared OKD resources, such as templates.

This is the single and authorative source of [OKD](https://www.okd.io/) resources that are used by different application stacks and projects within VIAA.  They are typivally deployed in the viaa-OKD namespace.


## Usage

```bash
$ oc project myproject
$ oc process viaa-postgresql --param-file=parameters.int -n viaa-okd | oc create -f -
```
