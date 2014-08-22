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


Released versions
-----------------

- v1.0 - based on bpmPaaS from JBoss BRMS 6.0.2 with Cool Store installed.
