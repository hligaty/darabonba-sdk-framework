# Darabonba SDK Template

> **Note**
>
> Click the <kbd>Use this template</kbd> button and clone it in local.

Darabonba SDK Template is a repository that provides a pure template to make it easier to create a Multilingual SDK project.

## Quick start

1. `${projectDir}` exec:

```shell
$ npm install -g @darabonba/cli
```

2. `${projectDir}/sample` and `${projectDir}/sdk` exec:

```shell
$ dara install darabonba:Util -S
$ dara install alibabacloud:OpenApiUtil -S
```

## Darabonba configuration

1. Read [Darafile guide](https://github.com/aliyun/darabonba/blob/master/doc/darafile.md).
2. Change `scope`|`name`|`package`|`namespace` in both `Darafile` files.
3. Modify the `hligaty:SDK` of `sample/.libraries.json` to the `scope:name` configured in `SDK/Darafile`.

## SDK template structure

A generated Darabonba SDK Template repository contains the following content structure:

```
.
├── sample                  CodeSample sources
│   ├── .libraries.json     Dependency system path
│   ├── Darafile/           Darabonba configuration file
│   └── main.dara/          Darabonba production sources
├── sdk                     SDK sources
│   ├── Darafile/           Darabonba configuration file
│   └── main.dara/          Darabonba production sources
├── .gitignore              Git ignoring rules
├── LICENSE                 License, MIT by default
└── README.md               README
```

## Reference documentation

* [Official Aliyun Darabonba documentation](https://github.com/aliyun/darabonba/blob/master/README.md)
* [Darafile guide](https://github.com/aliyun/darabonba/blob/master/doc/darafile.md)
