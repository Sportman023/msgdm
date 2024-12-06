<html>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DWF0000019IbR',
				'Bot_settings_testing_Demo',
				'https://atlanticarehealthsystem--activedev.sandbox.my.site.com/ESWBotsettingstestingD1733491842736',
				{
					scrt2URL: 'https://atlanticarehealthsystem--activedev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://atlanticarehealthsystem--activedev.sandbox.my.site.com/ESWBotsettingstestingD1733491842736/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</body>
</html>
