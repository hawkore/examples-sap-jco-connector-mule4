# Sample mule4 application

# Steps to test

1. Import this application into Anypoint Studio 7+ (Recomended version 7.3.4, Anypoint Studio 7.3.5 has a bug related to external libraries).
2. Configure connection properties for your SAP ECC (src/main/resources/sap.properties)
3. Install Official SAP JCo/IDoc libraries into your local maven repository. See [SAP JCo connector for Mule 4 Documentation](https://docs.hawkore.com/private/sap-jco-connector-mule4/) to know how.
4. Run `mvn test` from command line at this project root directory or right click over project -> MUnit -> Run Tests in Anypoint Studio 7+.

## Valid product license required

You will need a valid product license to run/test SAP Jco Connector for Mule 4.

Put your license for SAP JCo Connector for Mule 4 in `src/main/resources` directory.

Please, contact [HAWKORE](https://www.hawkore.com) to obtain a valid license.

**NOTE**: You do not need a license to design Mule flows using this connector.

## More resources

Sign up at [www.hawkore.com](https://www.hawkore.com) to access full documentation.
