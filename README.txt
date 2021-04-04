How to test:
1. Start the Eureka registry server.
2. Start the Eureka client. Client will take some time to register itself to Eureka registry.
3. Check "http://localhost:8080/service-instances/EurekaDiscoveryClient"
The output should be something like below:

<List>
<item>
<port>8080</port>
<host>host.docker.internal</host>
<metadata>
<management.port>8080</management.port>
</metadata>
<secure>false</secure>
<instanceInfo>
<instanceId>host.docker.internal:EurekaDiscoveryClient</instanceId>
<app>EUREKADISCOVERYCLIENT</app>
<appGroupName/>
<ipAddr>192.168.1.212</ipAddr>
<sid>na</sid>
<homePageUrl>http://host.docker.internal:8080/</homePageUrl>
<statusPageUrl>http://host.docker.internal:8080/actuator/info</statusPageUrl>
<healthCheckUrl>http://host.docker.internal:8080/actuator/health</healthCheckUrl>
<secureHealthCheckUrl/>
<vipAddress>EurekaDiscoveryClient</vipAddress>
<secureVipAddress>EurekaDiscoveryClient</secureVipAddress>
<countryId>1</countryId>
<dataCenterInfo _class="com.netflix.appinfo.InstanceInfo$DefaultDataCenterInfo">
<name>MyOwn</name>
</dataCenterInfo>
<hostName>host.docker.internal</hostName>
<status>UP</status>
<overriddenStatus>UNKNOWN</overriddenStatus>
<leaseInfo>
<renewalIntervalInSecs>30</renewalIntervalInSecs>
<durationInSecs>90</durationInSecs>
<registrationTimestamp>1617573938252</registrationTimestamp>
<lastRenewalTimestamp>1617574087125</lastRenewalTimestamp>
<evictionTimestamp>0</evictionTimestamp>
<serviceUpTimestamp>1617573937487</serviceUpTimestamp>
</leaseInfo>
<isCoordinatingDiscoveryServer>false</isCoordinatingDiscoveryServer>
<metadata>
<management.port>8080</management.port>
</metadata>
<lastUpdatedTimestamp>1617573938252</lastUpdatedTimestamp>
<lastDirtyTimestamp>1617573937085</lastDirtyTimestamp>
<actionType>ADDED</actionType>
<asgName/>
</instanceInfo>
<instanceId>host.docker.internal:EurekaDiscoveryClient</instanceId>
<serviceId>EUREKADISCOVERYCLIENT</serviceId>
<uri>http://host.docker.internal:8080</uri>
<scheme/>
</item>
</List>