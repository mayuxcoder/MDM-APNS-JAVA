MDM-APNS-JAVA
=============

its a extended version of notnoop JAVA APNS to support MDM functionality 


//Initialing with certificate location and password
APNSInitiator apns=new APNSInitiator("/home/mayuran/workspace/IOSMDM/src/certificates/MDM_ WSO2 Inc_Certificate.p12", "shan130474");
//Calling the method to push
apns.pushingToAPNS(devicesInfoList);

Note:Here devicesInfoList parameter should be something similar to this 
        [{magictoken=7DDAFFA8-B82C-45CB-B3C2-7B71850F1803, devicetoken=L6lUGSrOIx5jnHtQgAWqBELzpkXhGexWiHVHfCfzwZ8=}, {magictoken=7DDAFFA8-B82C-45CB-B3C2-7B71850F1803, devicetoken=L6lUGSrOIx5jnHtQgAWqBELzpkXhGexWiHVHfCfzwZ8=}]
