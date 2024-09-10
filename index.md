<html>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en';

			embeddedservice_bootstrap.init(
				'00DO9000007tPxp',
				'Testing_Deployment',
				'https://MYDOMAIN--patricksbx.sandbox.my.site.com/ESWTestingDeployment1721060666954',
				{
					scrt2URL: 'https://MYDOMAIN--patricksbx.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://MYDOMAIN--patricksbx.sandbox.my.site.com/ESWTestingDeployment1721060666954/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
</html>
