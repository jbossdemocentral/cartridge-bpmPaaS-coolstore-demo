## Cartridge for bpmPaaS with CoolStore Demo

Summary
-------
This cartridge provides the **_Red Hat JBoss BRMS_** for easy deployment to OpenShift based bpmPaaS with pre-loaded Cool Store Demo.

For more information on the [Cool Store Demo see here] (https://github.com/eschabell/brms-coolstore-demo).

JBoss BRMS logins: 

   * u:erics  p: jbossbrms1!  (admin)

   * u: alan  p: jbossbrms1!  (analyst)


Important Note
--------------
You need the ability to setup MEDIUM gears, which is freely available if you [upgrade your account to Bronze here] (https://www.openshift.com/products/pricing). 


Deployment
----------

To try out JBoss BRMS on OpenShift please follow the instructions:

If you want to use the [OpenShift create application page](https://openshift.redhat.com/app/console/application_types), enter the cartridge URI of **https://raw.githubusercontent.com/eschabell/cartridge-bpmPaaS-coolstore-demo/master/metadata/manifest.yml** in the entry field (at the bottom left of the form).

Or if you want to use the [rhc command line](https://www.openshift.com/developers/rhc-client-tools-install) type:

    rhc app create -g medium <APP NAME> https://raw.githubusercontent.com/eschabell/cartridge-bpmPaaS-coolstore-demo/master/metadata/manifest.yml

This will output the generated users and passwords for Business Central.

You can use them to login into Business Central or BAM applications.


Supporting Articles
-------------------

[Red Hat JBoss BRMS - all product demos updated for version 6.0.2.GA release](http://www.schabell.org/2014/07/redhat-jboss-brms-product-demos-6.0.2-updated.html)

[Red Hat JBoss BRMS 6 - Demo Cool Store Dynamic Rule Updates (video)](http://www.schabell.org/2014/05/redhat-jboss-brms6-demo-coolstore-dynamic-rule-updates.html)

[Red Hat JBoss BRMS 6 - The New Cool Store Demo] (http://www.schabell.org/2014/03/redhat-jboss-brms-v6-coolstore-demo.html)
 
[JBoss BRMS Cool Store Demo updated with EAP 6.1.1] (http://www.schabell.org/2013/09/jboss-brms-coolstore-demo-updated-eap-611.html)

[A shopping cart example in the Cool Store Demo] (http://www.schabell.org/2013/04/jboss-brms-coolstore-demo.html)

[Cool Store installation video part I] (http://www.schabell.org/2013/05/jboss-brms-coolstore-demo-video-partI.html)

[Cool Store CEP and Rules video part II] (http://www.schabell.org/2013/05/jboss-brms-coolstore-demo-video-partII.html)

[Cool Store BPM and Decision Tables video part III] (http://www.schabell.org/2013/05/jboss-brms-coolstore-demo-video-partIII.html)


Released versions
-----------------

- v1.0 - based on bpmPaaS from JBoss BRMS 6.0.2 with Cool Store installed.

![Digital Sign Annoucement](https://github.com/eschabell/brms-coolstore-demo/blob/master/docs/demo-images/announce-sign.jpg?raw=true)

![Decision Table](https://github.com/eschabell/brms-coolstore-demo/blob/master/docs/demo-images/coolstore-decision-table.png?raw=true)

![Domain Model](https://github.com/eschabell/brms-coolstore-demo/blob/master/docs/demo-images/coolstore-model.png?raw=true)
