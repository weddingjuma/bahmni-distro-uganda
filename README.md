![alt tag](readme/cchu-logo.png)
# Bahmni CURE Uganda distribution

_A Bahmni distribution to support standardized terminology, clinical processes, and reporting analytics at CURE Children's Hospital of Uganda_

-----

This repository maintains the 'distro POM' for CURE's Bahmni distribution in use at the CURE Children's Hospital of Uganda.
It downloads and brings in one place all artifacts needed by the distribution, simply run:
```
mvn clean package
```
### Target inventory:

* `bahmni_emr/`
<br/>The target version of the front-end apps that makes 'Bahmni EMR'.
* `bahmni_config/`
<br/>The bespoke Bahmni configuration (more [here](https://github.com/CURE-EMR/bahmni-config-uganda)) to be consumed by Bahmni Apps.
* `openmrs_modules/`
<br/>The required set of OpenMRS modules.
* `openmrs_config/`
<br/>The OpenMRS bespoke configuration (more [here](https://github.com/CURE-EMR/openmrs-config-uganda)) to be processed by the [Initializer module](https://github.com/mekomsolutions/openmrs-module-initializer).
* `openmrs_core/`
The target version of OpenMRS Core.
