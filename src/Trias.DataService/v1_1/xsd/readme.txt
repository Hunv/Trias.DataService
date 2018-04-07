Due to copyright reasons, this files are not provided in the repository.
You can download it from this page: https://www.vdv.de/ip-kom-oev.aspx
At the right is a "Download"-Box. You can also use this direct link:
v1.1 https://www.vdv.de/trias-xsd-v1.1.zipx?forced=true
v1.2 https://www.vdv.de/trias-xsd-v1.2.zipx?forced=true


How to generate the Schema file?
1. Install Xsd2Code+ Visual Studio Addin via "Tools => Extensions and Updates..." and restart VS
2. Import XSD-Files to xsd folder in the project
3. Select the trias.xsd
4. Click in the Menubar Tools => Xsd2Code class generator
5. Configure the following:
	Serialization => GenerateOrderXmlAttributes = True
	Serialization => GenerateXmlAttributes = True
	Collection => CollectionObjectType = Array