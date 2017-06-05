# Clinical Guidelines Modeler (Camunda Modeler)

[![Build Status](https://travis-ci.org/camunda/camunda-modeler.svg?branch=master)](https://travis-ci.org/camunda/camunda-modeler)

An integrated modeling solution for Clinical Guidelines Based BPMN Modeling (Camunda)

![Camunda Modeler](https://raw.githubusercontent.com/camunda/camunda-modeler/master/docs/screenshot.png)

## Project: Process modelling for dynamically adaptive contextualisation of clinical practice guidelines based pathways 
By: Department of Medical Informatics, Sri Balaji Vidyapeeth (Deemed University)

## Building the Application

```
# checkout a tag
git checkout v1.1.0

# install
npm install

# run all tests
npm run all
```


### Build a Snapshot (the master branch)

Building the master branch may fail due to snapshot dependencies being missing.
If that is the case, link them into the modeler project using the [wiredeps](https://github.com/nikku/wiredeps) utility:

```
npm install wiredeps

node_modules/.bin/wiredeps
```

### Development Setup

Spin up the application for development, all strings attached:

```
npm run dev
```


## License

MIT

Contains parts ([bpmn-js](https://github.com/bpmn-io/bpmn-js), [dmn-js](https://github.com/bpmn-io/dmn-js), [cmmn-js](https://github.com/bpmn-io/cmmn-js)) released under the [bpmn.io license](http://bpmn.io/license).
