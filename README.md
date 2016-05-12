[![Build Status](https://travis-ci.org/Unipoole/master-web.svg?branch=master)](https://travis-ci.org/Unipoole/master-web)
[![License](https://img.shields.io/badge/License-ECL%202.0-blue.svg)](https://opensource.org/licenses/ECL-2.0)
# master-web
The master web project is the parent project for the web based projects (Admin Tool & Unipoole Service).
It Inherits dependency versions from the master project and it only lists dependencies which will be available to to base-web project.
This is a POM project and does not contain deployable artefacts.

## Building
```bash
git clone https://github.com/Unipoole/master-web.git
cd master-web
mvn clean install
```