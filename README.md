# Swifty Viper

![](https://img.shields.io/badge/swift-3.0.1-green.svg)
![](https://img.shields.io/badge/VIPER-generamba-orange.svg)


# HOWTO:


1) [Install Generamba](https://github.com/rambler-digital-solutions/Generamba)

2) [Initialize Generamba](https://github.com/rambler-digital-solutions/Generamba/wiki/Available-Commands#basic-generamba-configuration) in your project's folder and install templates from this repo

3) open terminal and execute this in the same project's folder: 
```bash
$ generamba gen ModuleName viper_module
```
To instantiate a module you have just to call **ModuleViewController.instantiate()**

The new VIPER Module/Submodule(whatever) will be generated in your project's folder with structure:

<!-- AUTO-GENERATED-CONTENT:START (DIRTREE:dir=./) -->
```
Module
  ├── ModuleStoryboard.swift
  ├── View
  │    └── ModuleViewController.swift
  ├── Presenter
  │    └── ModulePresenter.swift
  ├── Interactor
  │    └── ModuleInteractor.swift
  ├── Router
  │    └── ModuleRouter.swift
  ├── Configurator
  │    ├── ModuleConfigurator.swift 
  └── Protocols
       └── ModuleProtocols.swift
```
