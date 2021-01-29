# Catalogue of Services Demo Validator

This is a demo validator based on CPSV-AP to showcase an example of a shared validator with common
specifications and core validation rules, extended by National contributions. The sample is based
on RDF and SHACL shapes for validation but a similar configuration could be applied for other types
of validators (XML, JSON or CSV).

The files you may edit to adapt the validation are as follows:
* Folder `resources\shapes` contains the SHACL shapes that drive the validation.
* File `resources\config.properties` contains configuration that you may want to adapt.

To publish changes commit and push your updates. In 1-2 minutes the online service will be updated.

The online service is accessible as follows:
* Web UI: https://www.itb.ec.europa.eu/shacl/cos/upload
* REST API: https://www.itb.ec.europa.eu/shacl/swagger-ui.html (use 'cos' as the domain value in requests)
* SOAP API: https://www.itb.ec.europa.eu/shacl/soap/cos/validation?wsdl